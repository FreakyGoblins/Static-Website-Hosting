# Static-Website-Hosting
# Creating a static website in 5 minutes using S3 on AWS
Steps
1. Create a bucket on S3 named rahbuc01
2. Give a unique name for the bucket since bucket name must be unique on S3
3. Create three files, index.html, error.html, about.html
4. Upload the files in the S3 bucket


Files upload on S3 bucket

Go to S3 > select your bucket > Edit Public Acess Settings > unselect "Block all public access" > Save > Confirm

Click on your bucket > select your 3 files > click on Actions > Make public

Click on Properties > Static Website Properties > select "Use this bucket to host a website" > Index document: type index.html > Error document: type error404.html

Click on Static Website Hosting to get the endpoint url.

There you go! Your website is online, you can visit it using the provided endpoint url.

# MY STATIC WEBSITE

[About](https://rahulbuc01.s3.amazonaws.com/index.html)

![Screenshot (44)](https://github.com/FreakyGoblins/Static-Website-Hosting/assets/143277720/fd273ea2-31c5-4804-8e3d-60a69ae68ded)

