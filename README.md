# Learn the fundamentals of Cloud Computing in 6 months.

![Timeline](img/timeline.png)

This is the learning path I would take if I had to start all over again and work my way up to junior cloud engineer skill set in about 6 months. Any links you see ARE NOT AFFILIATE LINKS, I don't want your money. Okay, let's go.

## Phase 1: Linux and networking essentials

The reason I pair them together is because lots of networking tasks are done via command line and Linux management is all about command line.

### Linux and networking Resources

I'll put these in the order I'd learn them in. If a row has a same number, it means I would watch/read along side each other.

| Order      | Title    | Notes     |
| :------------- | :----------: | -----------: |
|  1| [Linux Basics for Hackers](https://nostarch.com/linuxbasicsforhackers)   | This book made learning Linux FUN! It's pretty easy to follow and take a chapter day by day.   |
| 1   | [The Linux Command Line](https://nostarch.com/tlcl2) | I used this more as a reference to reinforce topics from the first book. |
| 2   | [Introduction to Networking](https://www.youtube.com/watch?v=cNwEVYkx2Kk&list=PLDQaRcbiSnqF5U8ffMgZzS7fq1rHUI3Q8) | Great YouTube playlist of basic networking concepts. |
| Optional   | [Computer Networking Course - Network Engineering](https://youtu.be/qiQR5rTSshw) | This full college-level computer networking course will prepare you to configure, manage, and troubleshoot computer networks. |

Once you have gone through this content, I think you would have a solid basic level of Linux and networking knowledge, no you're not a professional, but you shouldn't feel lost or clueless. The two books I mentioned have several projects, DO THEM! Do not just read the theory! If there is a concept you don't understand, look it up, don't limit yourself to the resources I am sharing here.

### Linux and networking Projects

 Title    | Resources     |
 :----------: | -----------: |
 Install Linux on a computer   | Research a distro and install it (I really like [Pop!_OS](https://pop.system76.com/)) |
Setup a [LAMP server](https://en.wikipedia.org/wiki/LAMP_(software_bundle)) | A pretty popular Linux admin task. |
 Deploy a NAS server | Checkout [FreeNAS](https://www.freenas.org/) |
 Deploy your own cloud | Checkout [NextCloud](https://nextcloud.com/) |

## Phase 2: Learn to code

You'll be using code to automate tasks and deploy infrastructure and you even though you don't need to know how to build full applications, Understanding the basics of programming will give you an upper hand. In the previous step you would've been introduced to bash scripting, so you should know some concepts by now.

For this step, I would go with [Python](https://www.python.org/). It's a very popular language and there are many quality free resources out there to learn it. It's one of the simpler ones to get started with too. Also please create a [GitHub](https://github.com/) account NOW if you don't already have one. It'll be your code portfolio and you should put as many projects as you'd like on there.

| Order      | Title    | Notes     |
| :------------- | :----------: | -----------: |
|  1 | [Python Crash Course](https://ehmatthes.github.io/pcc/)   | Another fun book to follow, also there is an Appendix in there on Git which is great!   |
| 1   | [Automate the boring stuff with Python](https://automatetheboringstuff.com/) | I haven't fully finished this book, but it can be used to learn Python too |
| 1   | [FreeCodeCamp Learn Python](https://www.youtube.com/watch?v=rfscVS0vtbw) | One of the many amazing resources provided by [FreeCodeCamp](https://www.freecodecamp.org/)|
| 2   | [Git tutorial for beginners](https://www.youtube.com/watch?v=8JJ101D3knE) | You'll need Git, learn it!|

You can follow any one of the python resources, you don't have to do them all, but definitely do the Git one, Once you finish one of them, it's time to build something for your GitHub. The books will have plenty of projects. These can just be text based, don't worry about building UIs, unless you want to.

### Projects for coding practice

 Title    | Resources     |
 :----------: | -----------: |
 Product Inventory Project  |  Create an application which manages an inventory of products. This will help you practice OOP concepts. |
Thumbnail Creator  | Create an program that can take multiple images and converts them to a specified size in the background, this will help you practice threading concepts. |
 Score Tracker | Create a program that you provide a team name and it will tell you if that team played today and what the game score was. #HalaMadrid btw. |

 Honestly, there are plenty of lists of projects out there you can do. Google is your best bet here.

 Alright, so where are we at now?  We're 4 1/2 months in, we've got some solid basic Linux, networking and programming skills. Time to learn some cloud.

## Phase 3: Learn a Cloud Computing Platform

This phase is the longest and for good reason, I mean it's called cloud engineering for a reason.

LET ME START OFF BY SAYING THAT YES I AM BIASED TOWARDS AZURE. Azure was the cloud platform I learned as a sysadmin to get promoted to Cloud Engineer. I started my YouTube channel with Azure tutorials. I was an Azure MVP and most recently, I now work for Microsoft.

AWS, Azure, GCP, the million dollar question. I would rule out GCP because there's so much more content, community, and jobs around the other two, essentials things when you're getting started. AWS or Azure? You can't go wrong with either. Regardless of which one you choose, the fundamentals are the same and my advice is the same.

Whichever cloud you pick, make sure you create an account and setup some budgets and alerts so you don't wake up to surprises on your bill. [Here](https://youtu.be/FZD0s7KE83Y) is how to do it in the Azure portal, and here [AWS](https://www.youtube.com/watch?v=fvz0cphjHjg).

### A note on paid cloud learning platforms

There are platforms out there like [A Cloud Guru](https://acloudguru.com) and [CloudAcademy](https://cloudacademy.com) that you can pay for a monthly or yearly subscription and gain access to content and lab environments for your learning. These do help you avoid spending your own money in your own AWS and Azure accounts, which when you're getting started is a good thing. Ultimately, if you sign up for one, it's up to you. I had a subscription to A Cloud Guru and Linux Academy when I was getting started, my work paid for it though, maybe this is a perk your work can pay for too.

### Take a certification

I personally like cloud certifications, they give you a nice outline to follow in terms of learning. However I don't think you need to have every single certification out there. One or two, plus the Linux, networking, programming, knowledge is plenty and already quite impressive.

### What should my first cloud certification be?

You have two options here:

- Entry level certification: Like the [AWS Certified cloud practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) or the [Azure Fundamentals AZ-900](https://docs.microsoft.com/en-us/learn/certifications/exams/az-900).
- Skip the entry level and go for an associate level: AWS has [three](https://aws.amazon.com/certification/) associate level certifications and Azure has I believe [four now](https://docs.microsoft.com/en-us/learn/certifications/browse/?resource_type=certification&products=azure&terms=associate).

You can skip the entry level one a take more time studying for the associate, or take them both. Up to you.

For the associate level AWS, I would go with any of them, I've heard the [SysOps](https://aws.amazon.com/certification/certified-sysops-admin-associate/) one is the hardest. Personally I have the [AWS certified developer associate](https://aws.amazon.com/certification/certified-developer-associate/) (it expired, but hey I still studied for it so I'm counting it!) it was a fun certification to study for. For Azure I would go for the [AZ-104](https://docs.microsoft.com/en-us/learn/certifications/azure-administrator/) or [AZ-204](https://docs.microsoft.com/en-us/learn/certifications/azure-developer/). The other associate level ones are a little more specificized. You can of course take them later on :)

### Cloud learning Resources

| Level      | Title    | Notes     |
| :------------- | :----------: | -----------: |
| AZ-900 | [Microsoft learn](https://docs.microsoft.com/en-us/learn/certifications/exams/az-900)   | Microsoft learn and Microsoft documentation is my go to for learning anything Azure related  |
| AZ-104   | [Microsoft learn](https://docs.microsoft.com/en-us/learn/certifications/exams/az-104)| Microsoft learn and Microsoft documentation is my go to for learning anything Azure related |
| AZ-204   | [Microsoft learn](https://docs.microsoft.com/en-us/learn/certifications/exams/az-204) | Microsoft learn and Microsoft documentation is my go to for learning anything Azure related |
| AZ-900 | [A Cloud Guru](https://acloudguru.com/course/az-900-microsoft-azure-fundamentals)   | I used to work with Lars, so I know how much work and care he puts into his courses, 10/10 recommend. |
| AZ-104   | [A Cloud Guru](https://acloudguru.com/course/az-104-microsoft-azure-administrator-certification-prep)| I haven't done this one personally, but I know ACG is pretty good quality.|
| AZ-204   | [A Cloud Guru](https://acloudguru.com/course/az-204-developing-solutions-for-microsoft-azure) | I haven't done this one personally, but I know ACG is pretty good quality. |
| AWS | [Rishab's Cloud Notes](https://rishabkumar7.github.io/CloudNotes/) | I don't have recent first hand experience with any AWS content besides A Cloud Guru, but my good friend [Rishab](https://twitter.com/rishabk7) does, checkout his very details exam guides :)

### How to approach learning cloud computing

Regardless which learning material you choose, it'll have some sort of demo/hands-on aspect to it. Do it. Don't just watch/read. This isn't a Netflix show you're consuming, this is learning time. If the instructor is doing something on screen, watch it, and then try it on your own.

When you are first getting started with cloud, you'll be doing everything via the UI, This is fine for getting started, however once you're in a job, you'll be using a CLI to manage your environments. My advice here is, for every exercise you do via the UI, look up the CLI command and do it that way too.

Eventually you'll learn these commands and it'll become easier to remember which one to use, but this is also a great time to introduce yourself to the official documentation, [AWS](https://docs.aws.amazon.com/index.html) and [Azure](https://docs.microsoft.com/en-us/azure/?product=featured)

If there is something you don't understand about a service or command, your go to should be the documentation. After that you can look up articles, tutorials, etc.

### Cloud Projects

 Title    | Resources     |
 :----------: | -----------: |
[Cloud Resume Challenge](https://cloudresumechallenge.dev/)  | Build your resume with AWS services. |
[Azure Cloud Resume Challenge](https://youtu.be/ieYrBWmkfno) | Similar to the previous project, except using Azure. |
 [100DaysOfCloud](https://github.com/100DaysOfCloud/100DaysOfCloudIdeas) | A list of many projects to do |
 Create a script that will deploy an ubuntu VM | You provide a name and region |
 Deploy a [ghost blog](https://ghost.org/docs/install/) | Blogs are great for you to document your learning, here's [mine](https:madebygps.com), deployed on Azure :) |


## Phase 4: DevOps

Final phase. First off, read some stuff about what DevOps is. Each cloud platform has a suite of DevOps tools, I've linked a few articles here.

- https://azure.microsoft.com/en-us/overview/what-is-devops/#overview
- https://aws.amazon.com/devops/what-is-devops/
- https://www.ibm.com/cloud/learn/devops-a-complete-guide

I also think it's worth reading [The Phoenix Project](https://itrevolution.com/the-phoenix-project/) it's a pretty fun read because it's a fictional story but it explains the importance of DevOps.

### Learn DevOps practices

- Continuous integration and continuous delivery (CI/CD)
- Version Control
- Infrastructure as Code
- Configuration management
- Continuous monitoring

You might be thinking that 4 weeks isn't a lot of time to cover all these, and you're right. With DevOps, it's so hard to establish a standard of learning, because every organization implements it differently. However, I think if you spent these 4 weeks learning Version control, CI/CD and Infrastructure as Code, you'll have  good foundation. You'll also be exposed to these practices in the resume projects I listed in the cloud projects table.

[DevOps Engineering Course for Beginners](https://youtu.be/j5Zsa_eOXeY)

### DevOps learning resources

| Practice      | Tool    |
| :------------- | :----------:
| Continuous integration and continuous delivery | [GitHub actions](https://docs.github.com/en/actions) |
| Version Control (you should've become familiar with Git in phase 2)| [Git and GitHub](https://docs.github.com/en/github/getting-started-with-github/quickstart)|
| Infrastructure as Code | [Terraform](https://www.terraform.io/) |

### DevOps projects

Title    | Resources     |
 :----------: | -----------: |
| Deploy a VNet (or VPC) and 2 VMs in the cloud with Terraform | Make sure you can SSH into both VMs and from vm1 you can ping vm2 and vice-versa. |
| Remember that NAS project from Phase 1? | Deploy it with Terraform |


## What's next

If you made it through all this, you're a legend and you have the work ethic required. You now need someone to take a chance on you and for that my friend I have no secrets.

