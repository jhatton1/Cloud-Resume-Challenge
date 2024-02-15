# Cloud Resume Challenge

<h2>Description</h2>
The Cloud Resume Challenge is all about showcasing your abilities in designing, building, and deploying a modern web application using cloud technologies. The goal is simple: create a personal resume website that highlights your skills, experience, and projects, and then deploy it using cloud platforms like AWS, Azure, or GCP. For my project, I chose to go with AWS.
<br />

<h2>Languages and Utilities Used</h2>

  - <b>HTML</b>
  - <b>CSS</b>
  - <b>JavaScript</b>
  - <b>Python</b>
  - <b>AWS Management Console</b>
  - <b>AWS CLI</b>
  - <b>Terraform</b>
  - <b>GitHub Actions</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)
<br />
<br />
<h2>Challenge Outline</h2>
<br />

<p align="center">
  Challenge Outline Steps 1-11: <br/>
  <img src="https://i.imgur.com/3cVMsNm.png" height="80%" width="80%" alt="Challenge Outline 1-11"/>
  <br />
  <br />
  Challenge Outline Steps 12-16 <br/>
  <img src="https://i.imgur.com/zoOJsfk.png" height="80%" width="80%" alt="Challenge Outline 12-16"/>
  <br />
  <br />
  Step 1: Certification 
  <br/>
</p>

- I obtained my Cloud Practitioner certification from AWS last summer. I had taken an interest in cloud computing at the time, and figured this would be a great place for me to start my cloud journey. As for the Cloud Resume Challenge, this is the first task required for the user to complete. <br/>
  <p align="center">
  <img src="https://i.imgur.com/0DOgqyJ.png" height="80%" width="80%" alt="Cloud Practitioner Cert"/>
  </p>
  <br />
  <br />
<p align="center">
Step 2 and 3: Create your resume using HTML and CSS <br/>
</p>

- The next step in the Cloud Resume Challenge is to create a resume for yourself using HTML and CSS. This part wasn't too bad for me since I already having prior HTML and CSS experience from [FreeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/), as well as prior [projects](https://github.com/jhatton1). <br/>
  <p align="center">
  <img src="https://i.imgur.com/UMpY7xD.png" height="80%" width="80%" alt="Resume"/>
  </p>
  <br />
  <br />

<p align="center">
Step 4: Host a static website using AWS S3 <br/>
</p>

- Now that I had created the resume portion of the Cloud Resume Challenge, it was time to host it on a static website. This can be done using Amazon AWS services such as [S3.](https://aws.amazon.com/pm/serv-s3/?gclid=Cj0KCQiA5rGuBhCnARIsAN11vgTKqNE8PfkDUtUM9YgcC4LNBr3gLtH9Ne9TSeuprgDzgx5XWDuFCuwaAvmEEALw_wcB&trk=20e04791-939c-4db9-8964-ee54c41bc6ad&sc_channel=ps&ef_id=Cj0KCQiA5rGuBhCnARIsAN11vgTKqNE8PfkDUtUM9YgcC4LNBr3gLtH9Ne9TSeuprgDzgx5XWDuFCuwaAvmEEALw_wcB:G:s&s_kwcid=AL!4422!3!651751060962!e!!g!!amazon%20s3!19852662362!145019251177) You can configure the static website settings when creating your S3 bucket, and then you just have to upload your files. <br/>
  <p align="center">
  <img src="https://i.imgur.com/kwVogoZ.png" height="80%" width="80%" alt="S3"/>
  </p>
  <br />
  <br />
<p align="center">
Step 5 and 6: Secure your static website with HTPPS and configure DNS<br/>
</p>

- This next step involves using [AWS CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html), a content delivery network (CDN), to securely deliver web pages, videos, applications, and other files globally with minimal latency. <br/>
<p align="center">
<img src="https://i.imgur.com/mm0gu5o.png" height="80%" width="80%" alt="CloudFront"/>
</p>

- In order to do properly configure CloudFront, you will also have to utilize [AWS Route 53](https://aws.amazon.com/route53/), a domain name service (DNS), to configure a domain that will then be used to get a secure socket layer (SSL) certificate from [AWS Certificate Manager](https://aws.amazon.com/certificate-manager/). I already had experience with these two services from a previous AWS [project](https://www.linkedin.com/pulse/hosting-wordpress-website-aws-beginner-jeremy-hatton/) so it didn't give me much trouble.<br/>
<p  align="center">
 <img src="https://i.imgur.com/XCZordh.png" height="80%" width="80%" alt="Route 53"/> 
</p>
<p align="center">
<img src="https://i.imgur.com/NnA7TLS.png" height="80%" width="80%" alt="Certificate Manager"/>
</p>
<br />
<br />

<p align="center">
Steps 7-9: Create a visit counter, a DynamoDB database, an API, a lambda function, and implement tests within the Python code  <br/>
</p>

- This is where I currently am in my Cloud Resume Challenge. I created my visit counter using JavaScript. I then created a DynamoDB database in AWS. Then using AWS API gateway and AWS Lambda, I created an API with the lambda function to accept requests from my webpage and communicate with my database.
- As you can see in my resume website, there is a "cannot read views" in the bottom left of my resume where my view counter is supposed to be. This is an error message that shows if there is an issue retrieving the view count. I have been trying to debug my view counter JavaScript code, API, and lambda function to see what is causing the error. This page will be updated once I have resolved this issue. Stay tuned! <br/>

<p align="center">
<img src="https://i.imgur.com/8CWLPYA.png" height="80%" width="80%" alt="Error Message"/>

