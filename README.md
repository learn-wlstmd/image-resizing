# AWS Lambda Function for Resizing Images
```sh
npm init -y
npm install --os=linux --cpu=x64 aws-sdk
npm install --os=linux --cpu=x64 sharp
zip -r function.zip .
aws lambda update-function-code --function-name wsi-resizing-function --zip-file fileb://function.zip --region us-east-1
```