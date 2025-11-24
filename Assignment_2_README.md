# Assignment 2: Cloud Service Providers Comparison Report

## Assignment Overview

Conduct a comparison of **AWS**, **Azure**, and **GCP** focusing on their cloud services for remote data and real-time applications. Submit your report as a README.md file in a public GitHub repository.

---

## Report Structure & Requirements

Your README.md file must include the following sections:

### 1. Executive Summary (10%)

- Brief overview of the comparison (200-300 words)
- Key findings and recommendations

# Summary

## Brief overview of the comparison

This report compares cloud services offered by **AWS, Azure, and Google Cloud Platform (GCP)** that are used for remote data and real-time applications. These services are utilized for three primary purposes: _remote data storage_, _real-time data and streaming_, and _real-time application support_. All three cloud providers offer strong tools and solutions, but each has its own strengths.

To **store and retrieve remote data**, cloud providers offer object, file, and block storage services. **AWS (Amazon S3)** leads in remote data storage. Amazon S3 is the most widely adopted object storage service, offering the best durability and tooling. **Azure Blob Storage** integrates seamlessly with Microsoft's enterprise ecosystem, making it an excellent choice for organizations running Windows-based workloads. **Google Cloud Storage** is optimized for global performance and simplicity, appealing to data-intensive applications and analytics-driven environments.

To **process or transmit real-time data streams**, cloud providers use streaming ingestion, stream processing, IoT/telemetry messaging, and specialized video-streaming services. **AWS Kinesis** has a broad suite of streaming capabilities, including analytics and video ingestion. **Azure Event Hubs**, in pair with Stream Analytics, is an ideal solution for enterprise telemetry pipelines and IoT solutions. **GCP’s Pub/Sub and Dataflow** are the best in global, event-driven architectures and large-scale data processing.

To enable real-time interactions, cloud providers provide serverless compute, real-time APIs and messaging, and low-latency databases. In** real-time application support**, all three providers offer serverless compute, low-latency databases, and real-time messaging services. **AWS Lambda** is the most mature serverless compute service that enables faster development, improved performance, enhanced security, and cost efficiency. **Azure Functions** integrates deeply with enterprise services and is used to handle key scenarios. **Google Cloud Run Functions** is a serverless, Function-as-a-Service (FaaS) that allows developers to deploy and run lightweight, event-driven functions without managing
infrastructure.

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

### 2. Introduction (10%)

- Purpose and scope of the comparison
- Brief overview of the three cloud providers

### 3. Service Comparison (60%)

Compare the three CSPs across these categories:

**a) RESTful API Services (15%)**

- API Gateway services and management tools
- Pricing models

**b) GraphQL Services (15%)**

- Native GraphQL support
- Third-party integration options

**c) WebSocket Services (10%)**

- Real-time communication services
- Scalability features

**d) Data Streaming Services (10%)**

- Stream processing platforms
- Data ingestion capabilities

**e) Stream Analytics (10%)**

- Real-time analytics platforms

### 4. Use Case Analysis (15%)

- Present **two real-world scenarios** for real-time applications
- Recommend the most suitable CSP for each with justification
- Consider: cost, performance, ease of integration, ecosystem

### 5. Conclusion (5%)

- Summary of findings and overall recommendations

### 6. References

- Properly cite all sources (official documentation, articles, etc.)

---

## Submission Instructions

1. Create a **public GitHub repository**
2. Complete your report in `README.md`
3. Submit the **GitHub repository URL** via Brightspace.

---

## Use of Generative AI (Permitted)

- **Must disclose** AI usage in a section titled "AI Usage Disclosure"
- Specify how AI was used (e.g., brainstorming, editing)
- Content must reflect **your own understanding**
- Undisclosed AI use = academic misconduct

---

# References

- https://aws.amazon.com/s3/
- https://azure.microsoft.com/en-us/products/storage/blobs/?msockid=3f9ae475ca466e9014bcf1ddcb876f81
- https://cloud.google.com/storage?hl=en
- https://aws.amazon.com/kinesis/
- https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features
- https://docs.cloud.google.com/pubsub/docs/stream-messages-dataflow
- https://aws.amazon.com/lambda/
- https://www.geeksforgeeks.org/devops/what-is-microsoft-azure-functions/
- https://cloud.google.com/functions?hl=en
