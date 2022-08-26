<h1>Deploy Static Website on AWS</h1>

Screenshots showing steps for Deploying Static Website on AWS.

The following activities has been performed:

<ol>
  <li>All website files are added to the S3 bucket.</li>
  <li>The bucket configuration is set up to support static website hosting.</li>
  <li>The S3 bucket is configured to support static website hosting.</li>
  <li>The permission access to the bucket is configured to allow public access.</li>
  <li>The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.</li>
</ol>

Website Distribution:

The website is distributed via Cloudfront. CloudFront has been configured to retrieve and distribute website files.

<h3>Site Url:</h3>

<a href = "https://d25loijkf5z8l6.cloudfront.net/" target = "_blank">Josh Travelog</a>

https://d25loijkf5z8l6.cloudfront.net/

<h3>CloudFront Distribution:</h3>

<a href = "http://mystaticweb930573094765bucket.s3-website-us-east-1.amazonaws.com/" target = "_blank">Josh Travelog</a>


http://mystaticweb930573094765bucket.s3-website-us-east-1.amazonaws.com/

<img src = "./webpage.jpeg">
