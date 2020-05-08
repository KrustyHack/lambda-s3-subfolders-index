# lambda-s3-subfolders-index

Allow displaying S3 subfolders as pages (with index.html) with CloudFront : https://aws.amazon.com/fr/blogs/compute/implementing-default-directory-indexes-in-amazon-s3-backed-amazon-cloudfront-origins-using-lambdaedge/

## How

Re-write the request so that CloudFront requests a default index object (index.html in this case) for any request URI that ends in ‘/’.
