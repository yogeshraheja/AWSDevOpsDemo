These file are for CodeDeploy Demo
# Clone these files and create a gip file
#Create your application.zip and load it into CodeDeploy:

aws deploy create-application --application-name mywebapp

aws deploy push --application-name mywebapp --s3-location s3://<MY_BUCKET_NAME>/mywebapp.zip --ignore-hidden-files
 
