**Creating an S3 Bucket in AWS with Terraform

**Introduction:

In this lab, we will learn how to create an S3 bucket with versioning enabled using Terraform. Amazon S3 (Simple Storage Service) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This lab will guide you through the process of creating an S3 bucket, enabling versioning, and tagging the bucket for better management and organization

**Objectives:

--Understand the basics of Amazon S3 and bucket configuration.
--Create an S3 bucket using Terraform.
--Enable versioning on the S3 bucket.
--Add tags to the S3 bucket.
--Verify the setup.

**Prerequisites:

--An AWS account with permissions to create S3 buckets.
--Terraform installed on your local machine.

**S3 Buckets:

An S3 bucket is a container for storing objects (files). You can store any number of objects in a bucket, and each object can be up to 5 terabytes in size. Buckets are region-specific, and the name of the bucket must be unique across all AWS accounts.

**Key Components of an S3 Bucket:

--Bucket Name: A unique name for the bucket.

--Region: The AWS region where the bucket is created.

--Access Control List (ACL): Permissions for the bucket (e.g., private, public-read).


**S3 Bucket Versioning:

Versioning in S3 allows you to keep multiple versions of an object in the same bucket. Versioning can help you recover from both unintended user actions and application failures.

**Key Features of S3 Bucket Versioning:

--Enabled: All versions of objects are stored.
--Suspended: Stops accruing new versions, but existing versions remain.