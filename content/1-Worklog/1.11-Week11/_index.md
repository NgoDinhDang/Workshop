---
title: "Worklog Week 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives

* Implement the core features of the project.
* Build the automated document processing workflow on AWS.
* Test the document processing pipeline after files are uploaded to Amazon S3.

### Tasks to be completed this week

| Day | Tasks | Start Date | Completion Date | Reference |
| --- | ----- | ---------- | --------------- | --------- |
| Mon | - Developed the file upload feature from the frontend to Amazon S3.<br>- Verified file storage in Amazon S3. | 29/06/2026 | 29/06/2026 | https://docs.aws.amazon.com/s3/ |
| Tue | - Configured Amazon S3 Event Notifications.<br>- Connected Amazon S3 with AWS Lambda for automatic processing. | 30/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/lambda/ |
| Wed | - Developed an AWS Lambda function to process S3 events.<br>- Verified Lambda execution after file uploads. | 01/07/2026 | 01/07/2026 | https://docs.aws.amazon.com/lambda/ |
| Thu | - Integrated Amazon Textract to extract text from images and PDF documents.<br>- Tested OCR results using sample documents. | 02/07/2026 | 02/07/2026 | https://docs.aws.amazon.com/textract/ |
| Fri | - Tested the complete workflow from Amazon S3 → AWS Lambda → Amazon Textract.<br>- Reviewed and adjusted the system configuration where necessary. | 03/07/2026 | 03/07/2026 | https://www.youtube.com/@AWSStudyGroup |

### Week 11 Results

* Successfully implemented file uploads from the frontend to Amazon S3.

* Configured Amazon S3 Event Notifications to trigger AWS Lambda automatically.

* Developed an AWS Lambda function to process uploaded files.

* Integrated Amazon Textract for OCR processing of image and PDF documents.

* Successfully tested the processing workflow:

  * Frontend
  * Amazon S3
  * Amazon S3 Event Notification
  * AWS Lambda
  * Amazon Textract

* Completed the foundation for AI integration and database storage in the following week.