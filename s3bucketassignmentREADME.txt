	CREATING AN S3 BUCKET

1.create a new bucket with a name.(leave every other thing as default)

click create.

2. Upload a folder inside the bucket( click upload) add folder
 select the folder path that contains your html page to upload in few minutes time.

There will be a success display that the whole file has been copied into the browser.

3. copy the whole file into bucket root location
click action--MOVE

SELECT BROWSE and click on the bucket, select DESTINATION
MOVE the bucket then close.

You can go back to confirm everything is already in the root directory.

		CLOUD FRONT

CLICK cloudfront and click new distribution.

ORIGIN is our bucket details/name.

2. SELECT ORIGIN ACESSS CONTROL SETTTINGS --click Create new OAC


3. Enable security root protection.

4. DEFAULT ROOT OBJECT --type index.html
5. click Create distribution.
6. copy POLICY and paste inside of your s3bucket
7. click bucket, PERMISSIONS 
8. EDIT bucket policy and paste whats copied from the cloudfront policy click SAVE.
9 GO BACK TO YOUR cloud front  --click on the name( select DISTRIBUTION DOMAIN NAME)
COPY THE distribution domain name 
10. paste into your browser to display the page that it ran succesfuly.