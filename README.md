# UPLOAD IMAGE TO AMAZON S3

## Link API

https://hidden-headland-73625.herokuapp.com/

## Reference

https://www.youtube.com/watch?v=yGYeYJpRWPM

## Description

When call api to upload image from Frontend, this image will auto upload to S3 and api return url of image, just use this url to assign to src attribute of img
tag. Open folder client to understand flow code.

## Install

Download [Nodejs](http://nodejs.org/)

Clone project and install dependencies

```
git clone https://github.com/lehuuhieu-1011/upload-image.git
cd upload-image
cd server
npm install
```

## Usage

#### Create a file .env in root directory

```
ACCESS_KEY_ID=Access key ID of user in IAM
SECRET_ACCESS_KEY=Secret access key of user in IAM
AWS_REGION=AWS Region
BUCKET_NAME=Name of bucket
```

#### Run application

> `npm start`
