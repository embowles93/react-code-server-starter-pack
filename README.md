# The React Code Server Starter Pack

I created this repository to make it easier to get going with a react app on code-server. In my environment, I am running code server via the [one-click deployment method on AWS](https://github.com/cdr/deploy-code-server/blob/main/guides/aws-ec2.md), and using the 'link' flag for authentication.

Specifically, this deployment requires some [additional configuration of two environment variables to run properly](https://github.com/cdr/code-server/blob/main/docs/guide.md#proxying-to-create-a-react-app) using code-server's port forward proxy. That is the only file which differs from running 'npx create-react-app'.