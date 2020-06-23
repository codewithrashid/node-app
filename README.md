Code build deploy with AWS :
1. Create new project on git hub (node-app).
2. Create New Create environment in AWS Elastic Beanstalk by selecting Platform as Node.js
3. Keep all setting as it is.  (default : Sample application) and create new environment.
4. Go to Aws CodePipeline and create new pipeline.
5. Select source provider as Github in new pipleline.
6. Create a new node app & add commit, remote and push on git hub.  (app.js & package.json)
7. open the URL mantioned on Elastic Beanstalk newly created environment.

Done!!

Do Some changes on code and commit and push it on git and check changes on Live URl.

