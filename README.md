# azure-cloud
End-to-end Azure cloud projects including Azure Data Factory pipelines, storage automation, triggers, ForEach &amp; Filter activities, and Azure AI Custom Vision models. Designed for real-world data engineering and cloud automation use cases.
azure-cloud-projects/
│
├── Azure-Data-Factory/
│   ├── copy-activity/
│   │   ├── pipeline-copy-blob-to-blob.json
│   │   ├── screenshots/
│   │   │   └── copy-activity-success.png
│   │   └── README.md
│   │
│   ├── filter-activity/
│   │   ├── pipeline-filter-files.json
│   │   ├── screenshots/
│   │   │   └── filter-output.png
│   │   └── README.md
│   │
│   ├── foreach-activity/
│   │   ├── pipeline-foreach-copy.json
│   │   ├── screenshots/
│   │   │   └── foreach-run.png
│   │   └── README.md
│   │
│   ├── triggers/
│   │   ├── tumbling-window-trigger.json
│   │   ├── schedule-trigger.json
│   │   └── README.md
│
├── Azure-Storage/
│   ├── blob-storage-automation.md
│   └── screenshots/
│
├── Azure-AI-Custom-Vision/
│   ├── dataset/
│   ├── training-steps.md
│   ├── performance-metrics.md
│   └── screenshots/
│
├── Architecture-Diagrams/
│   └── end-to-end-architecture.png
│
├── README.md
└── LICENSE

# Azure Cloud Projects 🚀

This repository showcases my hands-on experience with Microsoft Azure services, focusing on data engineering, automation, and AI-based solutions.

## 🔧 Technologies Used
- Azure Data Factory
- Azure Blob Storage
- Azure Triggers (Schedule & Tumbling Window)
- Azure AI Custom Vision
- Azure Integration Runtime

## 📂 Projects Overview

### 1. Azure Data Factory Pipelines
- Copy activity between Blob Storage accounts
- Filter activity to process selective files
- ForEach activity for batch file processing
- Trigger-based pipeline automation

### 2. Azure Storage Automation
- Secure blob-to-blob data transfer
- Event-driven pipeline execution

### 3. Azure AI Custom Vision
- Image classification using Custom Vision
- Model training with Quick & Advanced training
- Performance evaluation using Precision, Recall & AP

## 📊 Key Highlights
- Designed end-to-end cloud data pipelines
- Implemented automation using triggers
- Achieved 100% Precision & Recall in AI model testing
- Followed real-world cloud architecture best practices

## 📎 Architecture
See `Architecture-Diagrams/` for end-to-end workflow diagrams.

## 🔗 Connect With Me
- LinkedIn: https://www.linkedin.com/in/YOUR_USERNAME
- GitHub: https://github.com/YOUR_USERNAME

- # Azure Data Factory – Copy Activity

## 📌 Objective
Transfer files from one Azure Blob Storage container to another using Azure Data Factory.

## ⚙️ Services Used
- Azure Data Factory
- Azure Blob Storage
- Azure Integration Runtime

## 🔄 Pipeline Flow
1. Source: Blob Storage container
2. Sink: Destination Blob Storage
3. Copy activity executes file transfer
4. Triggered manually / scheduled

## 📸 Screenshots
Refer to the `screenshots/` folder for successful pipeline runs.

## ✅ Outcome
- Successfully transferred files
- Verified pipeline execution and logs
