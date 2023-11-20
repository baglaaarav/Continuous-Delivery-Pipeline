## Creating a continuous delivery pipeline

####  This is a project where any commit changes on GitHub will also be refelected on elastic beanstack with the help of codebuild and code pipeline

#### Resources used in this project:
- GitHub
- CodeBuild
- Code PileLine
- AWS Elastic Beanstalk
- git


### Project Architecture:


### What I did:

Firstly, I initiated a GitHub repository and cloned it onto my local machine. Leveraging HTML, CSS, and JavaScript, I crafted a simple website, committing these changes to the GitHub repository. With the foundation laid, I proceeded to create an Elastic Beanstalk environment with Node.js on a Linux instance, incorporating a sample codebase. Following successful deployment, I turned my attention to setting up CodeBuild to compile the source code stored in the GitHub repository. I ensured that the necessary access permissions were granted.

Subsequently, I orchestrated the linkage between CodeBuild and CodePipeline, connecting them to both Elastic Beanstalk and CodeCommit. This integration established a seamless pipeline, poised to automate the deployment process. However, recognizing the importance of authentication before committing changes to Elastic Beanstalk, I introduced a pivotal step—a manual review after CodeBuild. This manual review ensures a human checkpoint, allowing for an additional layer of validation before the deployment proceeds.

In conclusion, this orchestrated pipeline not only streamlines the development workflow but also incorporates a crucial manual review stage to safeguard the deployment process. By combining the power of GitHub, CodeBuild, CodePipeline, and Elastic Beanstalk, this setup not only enhances efficiency but also ensures a controlled and secure deployment environment.

