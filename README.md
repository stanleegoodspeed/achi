# Allison Chi Personal Site

### How to deploy:
1. Run 'hugo' locally to build the /public folder
2. Go to AWS console and find www.allisonchi.com S3 bucket
3. Manually copy the contents of the public folder to that bucket
4. Go to Cloudfront -> Invalidations -> Create Invalidation for "*"
