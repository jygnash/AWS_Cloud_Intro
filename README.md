# AWS Cloud Introduction

## Pre-requisite
Log on given chromebook with credentials shared  at the desk.

## Hands-on exersice: 1

Description: Design & Create Web Page that "Define's Yourself"

Steps to follow to complete the exersice:

1. Open "caret" application from chromebook (This is editor for writing HTML)
2. Open Github repository: https://raw.githubusercontent.com/jygnash/AWS_Cloud_Intro/master/Template.html
3. Right click on browser and Click on "Save as..."
4. Save "Template.html" under "Download" folder
5. Search for any 3 pictures on web (https://images.google.com) that you would like to use to defines yourself!
   OR If you wish, you can use your own picture from internet
6. Open "Template.html" in "caret" application
7. Replace "image.jpg" with the pictures you downloaded in step #5
   - This needs to be done for all 3 images. Simply find "image.jpg" for all 3 location
8. Write details that describe yourself in the place of "Decscription1...", "Decscription2..." and "Decscription3..."
9. Highlight/bold the importance word using <b> if you want
10. Make the heading bold using <b> 
11. Open "files" application
12. Goto "Download" folder
13. Double tap on "Template.html"
14. Click on "View" to open it on the browser
15. Review your web page on browser and make more modication if you want


## Hands-on exersice: 2

Description: Host your web page on the AWS Cloud

Steps to follow to complete the exersice:

1. Click on one of the link below to login on AWS Cloud Console

| #  | Details |
| ------------- | ------------- |
| 1  | https://244549576870.signin.aws.amazon.com/console  |
| 2  | https://605601036605.signin.aws.amazon.com/console  |

2. Click on "S3"
3. Click on "Create bucket"
4. Enter "Bucket name"
6. Click on your newly created bucket 
7. Under "Overview", click on "Upload"
8. Click on "Add files" and select the files from "Download" folder of your chromebook
9. Click Next, Under "Manage public permissions", select "Grant public read access to this object(s)"
10. Click Next and Upload
11. Verify all your files are beign uploaded successfully 
12. Goto "Properties" tab and select "Static website hosting"
13. Enter your HTML file name (i.e. Template.html) instead of "index.html"
14. Copy "Endpoint" hyperlink
15. Try hitting enpoint link on the browser and verify

Congratuations! You have learned on basic of AWS Cloud and completed hands-on exercise successfully! :)
