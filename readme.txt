Code build deploy with AWS :
0. Create new project on git hub.
1. Create New Create environment in AWS Elastic Beanstalk by selecting Platform as Node.js
2. Keep all setting as it is.  (default : Sample application) and create new environment.
3. Go to Aws CodePipeline and create new pipeline.
4. Select source provider as Github in new pipleline.
5. Create a new node app & add commit, remote and push on git hub.  (app.js & package.json)
6. open the URL mantioned on Elastic Beanstalk newly created environment.

Done!!

Do Some changes on code and commit and push it on git and check changes on Live URl.

