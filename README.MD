# INITIAL JENKINS TEMPLATE

EC2 instance creation to support jenkins from scratch 

## Installation

1. Upload the file to a S3 bucket 
2. Copy the S3 url of the object 
3. Go to cloudformation and create a stack from template, paste the S3 address 
4. Enjoy


## Usage

This template provides the initial steps to configure a Jenkins server running on EC2 Instances

TODO: Write usage instructions

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

We have been following the guidelines provided by the post [Setting up a CI/CD pipeline by integrating Jenkins with AWS CodeBuild and AWS CodeDeploy](https://aws.amazon.com/blogs/devops/setting-up-a-ci-cd-pipeline-by-integrating-jenkins-with-aws-codebuild-and-aws-codedeploy/)


## License

MIT
