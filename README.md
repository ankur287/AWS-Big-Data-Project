# AWS-Big-Data-Project
This repo is for my big data project on AWS. I analyzed the sentiments of tweets for Google Pixel3 and compared them with iPhoneXS and oneplus6T as these phones were launched at almost same point of time.

I used AWS kinesis to stream twitter data in real time and stored it in AWS S3. After that I used AWS Lambda which helps in serverless cimputing and called AWS comprehend to analyze the tweets and provide a sentiment score to it. This output data along with raw data is queried using AWS Athena and visualized using AWS QuickSight.

Below is the snapshot of the entire processflow:

## Process Flow

![Alt text](https://github.com/ankur287/AWS-Big-Data-Project/blob/master/Images/Process%20flow.JPG?raw=true "Optional Title")

And here is the sanpshot of what QuickSight dashboard looks like.

## Dashboard

![Alt text](https://github.com/ankur287/AWS-Big-Data-Project/blob/master/Images/Dashboard.JPG?raw=true "Optional Title")
