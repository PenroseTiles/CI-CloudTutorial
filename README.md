# CI-CloudTutorial
Tutorial for Cloud CI 

We'll walk through the process of setting up a Cloud9 environment on AWS.

Go to https://console.aws.amazon.com

Here, you will see the AWS services tab. Look up 'Cloud9' in the search bar.


Then, just select the default options and create a new Cloud9 environment.




Set up the SSH passphrase for Bidirectional Communication with the Github account so you can access it securely via the Cloud9 terminal. 

Now log into circleci.com using your Github account and add your repo to the Circleci account. 

IMPORTANT:
Create a hidden directory called circleci in your repo, add the config.yml file to it, which can be downloaded from circleci when you attempt a build.


Make some changes to your repository and commit them from your cloud9 terminal

IMPORTANT:

Your make command must be added to the config file here, or the build will not happen. You can try this by adding bad code to your repo and then seeing the result of the automated build tests from CI. 
