Please complete the following steps:/
1. Create a hosted git repository account of your choice (if you do not already possess one/
Github/
2. Provide us with the account name/
Samikh2020/
3. Share the account and the details once complete/
https://github.com/samikh2020/River-safe-app/
4. Use the Repository and pick a CI/CD Tool of your choice and create a pipeline to/
I used Python to create my simple Hello world application./
For this task I used Jenkins along with my github repository to create a CI pipeline for my python application./
To create the Jenkins server I used a Docker container./
My pipeline works by using a github webhook to start a Jenkins job when there’s a new push to the developer branch. /
The job then tests the application. Once all the tests pass the application will move to the master branch./
I also attempted to used Azure DevOps to create the pipeline, along with Azure repos. However I struggled to pass/
along the tested code to the master branch./
d. Deploy the application to a Server (Bonus: Deployment of Application to multiple flavours - Windows/Linux)/
For this I used Azure to create a linux and Microsoft server for me to test that my application will work. /
e. Test the Deployment is successful/
To check whether my my application worked, I manually SSH into the azure linux server and ran the application which I /
had sent over from my personal laptop./
5. Extra credits for building the application as a Container (docker image)./
I create the dockerfile needed to create the containers which will be able to create the environment required and will run the code./

