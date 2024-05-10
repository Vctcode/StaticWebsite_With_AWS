# This is a mini-project to deploy a Static Website using AWS S3 Bucket and CloudFront

In this mini-project, I hosted a static website using AWS S3 Bucket for storage and CloudFront for content delivery.

## STEPS

### Created S3 bucket

![alt text](images/1Capture.PNG)
![alt text](images/1bCapture.PNG)

### Uploaded the static website files

![s3-created](images/1aCapture.PNG)
![alt text](images/3Capture.PNG)

### Created a Distribution with CloudFront

![create_distribution](images/create_distribution.png)

### Created OAC - Origin Access Control - to restrict access to public

![oac](images/oac.png)
![update_policy](images/update_policy.PNG)

### Added policy to make it public

![added_policy_s3](images/added_policy_s3.PNG)

### Finally, confirm website with distribution domain name

- copy the domain name link and open in a new browser tab
  ![distr_domain](images/distr_domain.PNG)
  ![cloudfront_dist_endpoint](images/cloudfront_dist_endpoint.PNG)

### For Static Template

- Get your Static Website for free from [Tooplate](https://www.tooplate.com/free-templates)

## END
