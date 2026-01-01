<h1>Hosting a static webpage on AWS S3.</h1>

<p>Step1:<br>
 Create and configure S3 bucket.<br>
Step2:<br>
Create bucket policy for static webpage.<br>
Step3:<br>
 Test using S3 website endpoint.</p>

<h1>Working</h1>
<p>User’s browser sends an HTTP request to the S3 website endpoint URL (http://my-bucket.s3-website-ap-south-1.amazonaws.com](http://sharq-webapp.s3-website.ap-south-1.amazonaws.com/).</p>
<p>The S3 website endpoint reads objects (HTML, CSS, JS, images) from your S3 bucket and returns them as static web content to the browser.</p>

<h1>Architecture Diagrem</h1>
<img width="3600" height="2400" alt="S3_arch_diag" src="https://github.com/user-attachments/assets/54e38ae5-cb77-4bf1-ace2-ac4097d7e7ec" />

<h1>Result</h1>
<img width="1888" height="1003" alt="image" src="https://github.com/user-attachments/assets/97f2b80c-bc7c-44b8-b7de-8a0fc855c2ad" />
