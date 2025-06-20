# aws-cloudformation-webserver
Automated Web Server Deployment using AWS CloudFormation

## Step 1 : Open CloudFormation Console
 1.Click on “Create stack”
 2.Select "Upload a template file"
 3. Create a template file in notepad or vscode
 4.Upload the "webserver.yml" file 
 5.Click "Next" ( Screenshot is attached Creation of stack)

## Added Screenshots

## Step 2: Specify Stack Details
  1. Stack name → Enter a name like: WebserverStack
  2. Click" Next "

## Step 3: Configure Stack Options
  1. This page lets you add tags, permissions, notifications, etc.
  2. Leave everything as default
  3. Click the “Next” button

## Step 4 : Review and create stack
  1.Scroll down and review the settings (you don’t need to change anything).
  2.At the bottom, you'll see a checkbox:
  3.Click "Submit"

## Step 5:  View the Output (Public IP)
  1.Click on the stack name WebServerStack
  2.Go to the Outputs tab
  3.You’ll see a key called:" Piblic IP"
  4.Copy the IP address shown

## Step 6:Open the Website in Browser
  1.Open a new tab in your browser
  2.Paste the IP like this: For example: http://13.235.45.123
  3.You should be able to see output " Hello from CloudFormation "






     




