# A script used by Bitbucked Webhook to deploy


### Usage

1. Clone deploy.php file into the deployment server in a web accesable directory.
2. Update deploy.php settings to match you deployment server's system.
3. Use Bitbucket Webhook. Add the URL of the deployment server's deploy.php script. For example: https://mywebspace.com/deploy.php
4. Set the Webhook to be triggered on "Repository push" state. Save Webhook.
5. You are good to go. Whenever you will push to a Bitbucket's repo a Webhook will be triggered and your code will be pulled by the deployment server.