---
title: "Week 7 Worklog"
date: 2026-07-30
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Week 7 Objectives:

* Integrate AWS S3 for file/document storage needed by backend features.
* Migrate the application's database to an AWS managed database service (RDS/DynamoDB) for better scalability.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Learn about S3 concepts<br>&emsp; + Bucket<br>&emsp; + Object<br>&emsp; + Permissions<br>- Create S3 bucket, configure bucket policy & CORS | 13/07/2026 | 13/07/2026 | https://docs.aws.amazon.com/s3/ |
| 3 | - Integrate AWS SDK into backend for upload/download files<br>- Implement file upload endpoints used by the application | 14/07/2026 | 14/07/2026 |  |
| 4 | - Research RDS and DynamoDB, evaluate which fits the current data model best<br>- Create RDS instance / DynamoDB table, configure security | 15/07/2026 | 15/07/2026 | https://docs.aws.amazon.com/rds/ |
| 5 | - Migrate schema/data from the self-hosted database to the managed database<br>- Update backend application to connect to the new database service | 16/07/2026 | 16/07/2026 |  |
| 6 | - Test file upload/download and database connectivity after migration<br>- Optimize file access (presigned URL) and monitor database performance | 17/07/2026 | 17/07/2026 |  |

### Week 7 Achievements:

* Understood S3 core concepts and created a properly configured S3 bucket for the application's files.
* Implemented file upload/download endpoints using the AWS SDK and S3.
* Compared RDS and DynamoDB against the project's actual data patterns and chose the more suitable option.
* Successfully migrated the database from self-hosted to the AWS managed database service with no data loss.
* Updated and re-tested the backend application against the new database, confirming stable performance.
