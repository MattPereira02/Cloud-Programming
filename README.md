#Installation Manual
Deploy Using AWS Management Console 
1. Open the CloudFormation console. 
2. Click Create stack > With new resources (standard). 
3. Under Specify template, upload CloudFrontCode.yaml. 
4. Click Next and fill in the stack name. 
5. Click Next, then Next again. 
6. Check the acknowledgement box and click Create Stack.
   
Upload Website Files to S3 after the stack is created 
1. Go to the S3 service. 
2. Open the bucket created by the template. 
3. Upload index.html and error.html. 
