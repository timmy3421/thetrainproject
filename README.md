# the train project
**A project to express my skills in AWS and beyond.**
&nbsp;

**Problem to solve:**
A train runs by my house making it an annoyance to record music when not knowing when the train will come by.
&nbsp;

**Solution:**
Use an Arduino (NodeMCU) with a vibration sensor and sound sensor to capture when the train last went by. This data will be sent to AWS IOT Analytics and eventually will calculate when the next train will come by based on Machine Learning. This end calculation will populate a device on-prem that will show when it predicts the next train will go by. 
Use AWS side technologies in an API First Manner.  
&nbsp;

**code directories -  [x] marks completion**
- [ ] arduino - code for the IOT device
- [ ] hugo -  
&nbsp;

**Technologies Used**
Service/Technology | Use/Reason
------------ | -------------
Powershell | Install Hugo
Arduino | NodeMCU is used as the primary IOT device since it has wifi capabilities and is cost effective
AWS Certificate Manager | Certificates for both CMS and Static site
Route53 | Deploy Subdomains of Static Sites (future)
Cloud Formation | Method by which to deploy site onto CDN

**Notes**
- For Certificates in Certificate Manager make sure to use the us-east-1 because if you plan on using CloudFront it only supports us-east-1. 
