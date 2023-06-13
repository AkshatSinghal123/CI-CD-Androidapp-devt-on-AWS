# CI-CD-Androidapp-devt-on-AWS
adding a continuous integration and continuous delivery (CI/CD) pipeline to the Android application development process

To achieve this, we will be using the following AWS services -\
•	AWS CodeCommit - As a code repository for the Android app.\
•	AWS CodeBuild - To compile, package, and deliver the Android app.\
•	AWS Device Farm - To test the Android app on real physical devices.\
•	Amazon S3 - to store build artifacts (apk file).\
•	AWS CodePipeline - Overall pipeline - - To monitor the changes in CodeCommit repository - To trigger the build using CodeBuild and - To test using Device Farm.\
•	AWS CloudFormation - To provision all of these resources\

![image](https://github.com/AkshatSinghal123/CI-CD-Androidapp-devt-on-AWS/assets/88577880/055bf03f-ddd3-4d42-a4f0-40a395660478)

