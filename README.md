Project: Deploy Static Website on AWS

CloudFront Endpoint URL:
d2wu2toj0hsczm.cloudfront.net

S3 Website Endpoint:
http://my-3410-3917-9909-bucket.s3-website-us-east-1.amazonaws.com

Notes:
- Website files (HTML, CSS, JS) were uploaded to the S3 bucket.
- Bucket policy allows public read access.
- Static website hosting is enabled on the S3 bucket.
- CloudFront distribution was created with the S3 website endpoint as origin.
- Default root object is set to index.html.
- Website successfully loads via CloudFront, S3 Website Endpoint, and S3 Object URL.

Screenshots Index:
01a-s3-bucket-created.png - S3 bucket creation (setup page)
01b-s3-bucket-list.png - S3 bucket visible in console
02a-s3-objects-all-files.png - Uploaded website files in S3
02b-s3-objects-all-files.png - Uploaded website files in S3
03-s3-static-website-hosting.png - Static website hosting enabled
04-s3-public-access-settings.png - Public access settings
05-s3-bucket-policy.png - Bucket policy applied
06a-browser-s3-website-endpoint.png - Website via S3 website endpoint
06b-browser-s3-website-endpoint.png - Website via S3 website endpoint
07-cloudfront-list.png - CloudFront distribution created
08-cloudfront-origins-website-endpoint.png - Origin set to S3 website endpoint
09-cloudfront-settings-default-root.png - Default root object set to index.html
10-browser-cloudfront-domain.png - Website via CloudFront domain

