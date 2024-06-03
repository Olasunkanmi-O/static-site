# Static Website
This project emphasis the use of AWS S3 for hosting static website. I have documend the processed involved in hosting a very basic website with images to assist in learning.<br>
### procedure
- log into your AWS account and navigate to S3
- create a bucket 
![](./img/01%20create-bucket.png)
- upload the files associated with the website 
![](./img/02%20upload-files.png)
- On the property tab, enable static website hosting
![](./img/03%20enable-static-website.png)
- Disable block Public access, this is to enable access through public IP
![](./img/04%20disable-block-publicaccess.png)
- Enable ACL through bucket ownership 
![](./img/05%20enable-ACL.png)
- Make the objects public through properties tab
![](./img/06%20make-objects-public.png)
- Access your website through the endpoint generated URL from the S3 bucket property.
