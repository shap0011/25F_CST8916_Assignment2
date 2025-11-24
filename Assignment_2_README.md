# Assignment 2: Cloud Service Providers Comparison Report

## Assignment Overview

Conduct a comparison of **AWS**, **Azure**, and **GCP** focusing on their cloud services for remote data and real-time applications. Submit your report as a README.md file in a public GitHub repository.

---

# Executive Summary

## Brief overview of the comparison

This report compares cloud services offered by **AWS, Azure, and Google Cloud Platform (GCP)** that are used for remote data and real-time applications. These services are utilized for three primary purposes: _remote data storage_, _real-time data and streaming_, and _real-time application support_. All three cloud providers offer strong tools and solutions, but each has its own strengths.

To **store and retrieve remote data**, cloud providers offer object, file, and block storage services. **AWS (Amazon S3)** leads in remote data storage. Amazon S3 is the most widely adopted object storage service, offering the best durability and tooling [1]. **Azure Blob Storage** integrates seamlessly with Microsoft's enterprise ecosystem, making it an excellent choice for organizations running Windows-based workloads [2]. **Google Cloud Storage** is optimized for global performance and simplicity, appealing to data-intensive applications and analytics-driven environments [3].

To **process or transmit real-time data streams**, cloud providers use streaming ingestion, stream processing, IoT/telemetry messaging, and specialized video-streaming services. **AWS Kinesis** has a broad suite of streaming capabilities, including analytics and video ingestion [4]. **Azure Event Hubs**, in pair with Stream Analytics, is an ideal solution for enterprise telemetry pipelines and IoT solutions [5]. **GCP’s Pub/Sub and Dataflow** are the best in global, event-driven architectures and large-scale data processing [6].

To enable real-time interactions, cloud providers provide serverless compute, real-time APIs and messaging, and low-latency databases. In** real-time application support**, all three providers offer serverless compute, low-latency databases, and real-time messaging services. **AWS Lambda** is the most mature serverless compute service that enables faster development, improved performance, enhanced security, and cost efficiency [7]. **Azure Functions** integrates deeply with enterprise services and is used to handle key scenarios [8]. **Google Cloud Run Functions** is a serverless, Function-as-a-Service (FaaS) that allows developers to deploy and run lightweight, event-driven functions without managing
infrastructure [9].

## Key findings

| Purpose                    | AWS                                                         | Azure                                                                                   | GCP                                                                                                  |
| :------------------------- | :---------------------------------------------------------- | :-------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------- |
| Remote Data Storage        | Amazon S3<br/>(durability and tooling)                      | Azure Blob Storage<br/>(integration with Microsoft's enterprise ecosystem)              | Google Cloud Storage<br/>(global performance and simplicity)                                         |
| Real-Time Data & Streaming | AWS Kinesis<br/>streaming, analytics, video ingestion       | Azure Event Hubs + Stream Analytics<br/>(enterprise telemetry pipelines, IoT solutions) | GCP’s Pub/Sub and Dataflow<br/> global, event-driven architectures, large-scale data processing      |
| Real-Time Applications     | AWS Lambda<br/>(enable faster development, the most mature) | Azure Functions<br/>(integrates with enterprise services)                               | Google Cloud Run Functions<br/>(FaaS for deploying and running code without managing infrastructure) |

## Recommendations:

If you need _versatility_, a _mature ecosystem_, and _high-performance streaming capabilities_, you should choose **AWS**.

If you want _strong enterprise integration_, _compatibility with Microsoft environments_, or _IoT-focused solutions_, **Azure** is the best option.

If your _workloads are analytics-heavy_, _global in scale_, _event-driven_, or _require cost optimization_, **GCP** is the right choice.

---

# Introduction

## Purpose and scope of the comparison

The purpose of comparing cloud providers is to help consumers choose the most suitable cloud service provider for their specific needs. This comparison can be crucial for system performance, security, cost efficiency, and long-term strategy. The comparison empowers businesses to select the best-fit Cloud provider for their remote data and real-time applications solutions [10].

## Brief overview of the three cloud providers

**Amazon Web Services (AWS)** is the market leader with roughly 32% market share. AWS offers a comprehensive cloud platform with over 200 fully featured services across its global data centers. Its extensive offerings cover computing power, diverse storage options, sophisticated networking capabilities, and cutting-edge tools for machine learning, analytics, and much more [10].

**Microsoft Azure** is a cloud computing platform that delivers a comprehensive suite of services for building, testing, deploying, and managing applications and services across Microsoft-managed data centers. Azure is known for its strength in hybrid cloud scenarios and seamless integration with the Microsoft ecosystem. Azure provides everything from virtual machines and databases to AI and machine learning services, catering to diverse business needs [10].

**Google Cloud Platform (GCP)** stands out as a powerful tool for organizations prioritizing data analytics, machine learning, and cutting-edge technologies. GCP offers a suite of cloud computing services running on the same infrastructure that powers Google’s own products, like Search, Gmail, and YouTube. This gives it an inherent advantage in handling massive datasets and complex computations.
Google’s global networking infrastructure, renowned for its low latency and high throughput, ensures fast, reliable access to applications and services regardless of location [10].

---

# Service Comparison

Compare the three CSPs across these categories:

## RESTful API Services

### API Gateway services and management tools

| Provider | Service category | Service Type | Service                   | Description                                                                                                                                                                                                                                                                 | Strengths                                                                                                   | Considerations / Weaknesses                                                                                                |
| :------- | :--------------- | :----------- | :------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------- |
| AWS      | API management   | Portals      | Amazon API Gateway        | A fully managed service for creating, publishing, securing, monitoring, and scaling REST, HTTP, and WebSocket APIs. It enables developers to build APIs that act as a front door to applications running on AWS services, serverless workloads, or external endpoints. [15] | Deep integration with AWS services (e.g., Lambda, IAM) [12]                                                 | Best for AWS‐native workloads; less ideal for hybrid/multi-cloud                                                           |
| Azure    | API management   | Portals      | Azure API Management      | A full-featured API management platform that provides tools for creating, securing, analyzing, and scaling APIs. It includes a gateway, developer portal, policy engine, and analytics features designed for hybrid, on-premises, and cloud-based API ecosystems. [16]      | Strong enterprise integration (Azure AD, Logic Apps), full lifecycle API management [13]                    | If your ecosystem isn’t Azure-centric, it may add overhead                                                                 |
| GCP      | API management   | Portals      | Apigee integrated portals | Support for several developer portal solutions, ranging from simple turn-key solutions to solutions that are fully customizable and extensible [11].                                                                                                                        | GCP’s gateway is simple and managed; Apigee offers advanced features for enterprise API productization [14] | Apigee can be relatively costly / complex; GCP gateway may lack some enterprise full-lifecycle features compared to others |

### Pricing models

**AWS** uses a **usage-based pricing model**, where you pay primarily per API request and for outbound data transfer. This makes AWS cost-efficient for variable or low-traffic workloads [17].

**Azure** uses a **tier-based pricing model**, where you choose a plan (Consumption, Basic, Standard, Premium) and pay a fixed monthly rate, with extra charges for additional requests. This offers predictable costs but may require higher tiers for enterprise features [18].

**Google Cloud** offers two models:

1. **API Gateway**: fully **usage-based**, similar to AWS (pay per API call + data transfer) [19].

2. **Apigee**: an **enterprise tier model** based on editions (Standard, Enterprise, Enterprise Plus) with pricing tied to API call volume and included features.
   This makes GCP flexible for both lightweight and large-scale enterprise API ecosystems [20].

## GraphQL Services

### Native GraphQL support

**AWS**: AWS AppSync is fully managed GraphQL with real-time sync and integrations with DynamoDB, Lambda, etc [21].

**Azure**: Azure API Management can import GraphQL endpoints or create synthetic GraphQL APIs with schema and resolvers [22].

**GCP**: No fully managed GraphQL engine; GraphQL runs on Cloud Run/Functions. Apigee provides GraphQL governance (policies, schema enforcement) [23].

### Third-party integration options

**AWS**: Supports Apollo or other GraphQL servers on Lambda/EC2.

**Azure**: Works with Apollo, Hasura, and other frameworks hosted on Azure services.

**GCP**: Supports any GraphQL server (Apollo, Yoga, etc.) deployed on Google Cloud.

## WebSocket Services

### Real-time communication services

### Scalability features

## Data Streaming Services

### Stream processing platforms

### Data ingestion capabilities

## Stream Analytics

### Real-time analytics platforms

## Use Case Analysis

### Present **two real-world scenarios** for real-time applications

### Recommend the most suitable CSP for each with justification

### Consider: cost, performance, ease of integration, ecosystem

---

# Conclusion

## Summary of findings and overall recommendations

---

## Use of Generative AI (Permitted)

- **Must disclose** AI usage in a section titled "AI Usage Disclosure"
- Specify how AI was used (e.g., brainstorming, editing)
- Content must reflect **your own understanding**
- Undisclosed AI use = academic misconduct

---

# References

- [1] Amazon Web Services. "Amazon S3." https://aws.amazon.com/s3/
- [2] Microsoft Azure. "Azure Blob Storage." https://azure.microsoft.com/en-us/products/storage/blobs/?msockid=3f9ae475ca466e9014bcf1ddcb876f81
- [3] Google Cloud. "Object storage for companies of all sizes." https://cloud.google.com/storage?hl=en
- [4] Amazon Web Services. "Amazon Kinesis." https://aws.amazon.com/kinesis/
- [5] Microsoft Azure Learn. "Features and terminology in Azure Event Hubs." https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features
- [6] Google Cloud Docs. "Stream messages from Pub/Sub by using Dataflow and Cloud Storage." https://docs.cloud.google.com/pubsub/docs/stream-messages-dataflow
- [7] Amazon Web Services. "AWS Lambda." https://aws.amazon.com/lambda/
- [8] GeeksForGeeks. "What is Microsoft Azure Functions?" https://www.geeksforgeeks.org/devops/what-is-microsoft-azure-functions/
- [9] Google Cloud. "Cloud Run functions." https://cloud.google.com/functions?hl=en
- [10] Signiance. "Comparing Cloud providers." https://signiance.com/comparing-cloud-providers/
- [11] Google Cloud Docs. "Compare AWS and Azure services to Google Cloud." https://docs.cloud.google.com/docs/get-started/aws-azure-gcp-service-comparison
- [12] TechTarget. "Compare cloud API management tools from AWS, Azure and Google." https://www.techtarget.com/searchcloudcomputing/tip/Compare-cloud-API-management-tools-from-AWS-Azure-and-Google
- [13] Over New Limits United (ONLU). "The ultimate comparison of API management solutions." https://onlu.ch/en/the-ultimate-comparison-of-api-management-solutions/
- [14] Scadea. "Choose the right gateway API solution Apigee vs AWS vs Azure." https://scadea.com/choose-right-api-solution-apigee-vs-aws-vs-azure/
- [15] Amazon Web Services. "What is Amazon API Gateway?" https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html
- [16] Microsoft Azure Learn. "What is Azure API Management?" https://docs.azure.cn/en-us/api-management/api-management-key-concepts
- [17] Amazon Web Services. "Amazon API Gateway pricing." https://aws.amazon.com/api-gateway/pricing
- [18] Microsoft Azure. "API Management pricing." https://azure.microsoft.com/en-us/pricing/details/api-management/
- [19] Google Cloud. "API Gateway pricing." https://cloud.google.com/api-gateway/pricing
- [20] Google Cloud. "Apigee API Management pricing." https://cloud.google.com/apigee/pricing?hl=en
- [21] Amazon Web Services. "What is GraphQL?" https://aws.amazon.com/graphql/
- [22] Microsoft Azure Learn. "Overview of GraphQL APIs in Azure API Management" https://learn.microsoft.com/en-us/azure/api-management/graphql-apis-overview
- [23] Google Cloud Docs. "Using GraphQL" https://docs.cloud.google.com/apigee/docs/api-platform/develop/graphql
