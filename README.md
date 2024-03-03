# Deploying-high-available-and-scalable-wordpress-using-cloudformation
Deploying high available and scalable wordpress using cloudformation, MySQL RDS

## Introduction

Let see the architecture

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/244f9d24-321b-4cc4-844c-6e513cf5c4ed)

## Cloudformation

Connect in Cloudformation console to create stack

Chose "use a sample of template"

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/098698a2-09d2-4708-a5a7-241e5f9250ca)

Select WordPress Blog " The template installs high-available scalable WordPress deployemnt using using a multi-az Amazon RDS Database instance for storage"

Click "View in Designer"

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/78988801-6c44-4061-87fa-1cca652d4f05)

Then click create stack icon

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/35810e82-bcdf-413e-8b50-bf69ca8a7f91)

The template is ready and Amazon S3 URL is provided an Amazon S3 URL to my template.

Click next

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/5c01c445-7f48-45ab-b108-cd4ed4d62d68)

I give it name "wordpresstest" and select parameters and click next

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/b27cbd00-20ec-4f54-9375-1f7804a5074c)

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/2ae03dbc-da9c-4ad0-b53e-1d77f1432e7b)


Keep "Configure stack options" default and click next

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/49495679-04e7-4af3-983a-89669913b4c6)

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/4fa40b3f-3612-4c82-a0bd-90a43e80e8a0)

Keep "Review and create" default and click submit. This is trigger Cloudformation to run and create aws resources

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/98e06251-01db-4cc7-af76-00f2c9d0ac70)

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/9e2da0ec-d839-4c80-b2dc-3e6f5c445d59)

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/d496b2fb-2c06-4d9f-a3cb-86f7947899f6)

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/1807a6cb-e2b0-4ec8-a2da-436fd011e7d0)

Creating Cloudformation stack in progress.It's running and creating aws resources.it created the database instance, launch config, etc..

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/756eb840-99a9-4636-9914-4422c13415a3)

All resouces are completed

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/df2677c9-f25b-4afa-b55b-d6b095ebd4d4)

So let's go check out the RDS database as well as the EC2 and then we are going to access this web server.

if I go to EC2, we should see an instance running. This is the instance that's running t2micro.

And if I go to the tags so it shows the tags and, and you know, this is created using our cloudformation stack "wordpresstest".

![image](https://github.com/felixdagnon/Deploying-high-available-and-scalable-wordpress-using-cloudformation/assets/91665833/3f151e87-cbd4-4b61-933d-e7013ad1ebe3)
































