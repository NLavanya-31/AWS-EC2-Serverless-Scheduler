# AWS-EC2-Serverless-Scheduler
In certain organizations, running EC2 instances round the clock isn't necessary; they only need instances operational during specific time windows, like standard working hours from 8:00 AM to 5:00 PM. To accommodate this requirement, I'll develop two Lambda functions to manage instance start-up and shutdown. These functions will be triggered by CloudWatch Events set for morning and evening schedules. This approach is entirely serverless.

![Architecture](https://github.com/NLavanya-31/AWS-EC2-Serverless-Scheduler/assets/155809688/aa514c80-1c53-4cba-b8e8-c4733f02f96a)
