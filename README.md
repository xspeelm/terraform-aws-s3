# Terraform AWS S3 Module

Creates a simple S3 bucket.

## Usage

module "s3_bucket" {
  source  = "username/s3/aws"
  version = "1.0.0"

  bucket_name = "my-demo-bucket"
}