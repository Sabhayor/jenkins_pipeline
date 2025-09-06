What is a Jenkins Pipeline Job

A Jenkins pipeline job is a way to define and automate a series of steps in the software delivery process. It allows you to script and organize your entire build, test, and deployment. Jenkins pipelines enable organizations to define, visualize, and execute intricate build, test, and deployment processes as code. This facilitates the seamless integration of continuous integration and continuous delivery (CI/CD) practices into software development.

Creating a Pipeline Job

Let's create our first pipeline job

i. From the dashboard menu on the left side, click on new item
ii. Create a pipeline job and name it "first pipeline job"

Configuring Build Trigger

Create a build trigger for jenkins to trigger new build

i. Click "Configure" your job and add this configurations
ii. Click on build trigger to configure triggering the job from GitHub webhook

iii. Create a github webhook.

Writing Jenkins Pipeline Script

A jenkins pipeline script refers to a script that defines and orchestrates the steps and stages of a continuous integration and continuous delivery (CI/CD) pipeline. Jenkins pipelines can be defined using either declarative or scripted syntax. Declarative syntax is a more structured and concise way to define pipelines. It uses a domain-specific language to describe the pipeline stages, steps, and other configurations while scripted syntax provides more flexibility and is suitable for complex scripting requirements.

Let's write our pipeline script

