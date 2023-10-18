# How to prepare for the AWS Certified Solutions Architect - Professional (SAP-C02)? 

## Background
Coming from AWS EMR service, my daily task involves how a cluster of EC2 instances interact with other AWS services, for example: IAM, S3, CloudWatch, CloudTrail, VPC, KMS, EBS, ASG, EKS and etc. To study for the exam, thorough review of the exam guide gives me a better idea of what will come up in the exam. 

## Process
1. Review the exam requirements using the [official exam guide](https://d1.awsstatic.com/training-and-certification/docs-sa-pro/AWS-Certified-Solutions-Architect-Professional_Exam-Guide.pdf).
    
    I copy all the services, and populate them into an excel sheet to understand them per domain. This helps my mind to automatically catagorize these services into their domain, and it is easier for me to memorize them in general, and later on, dive deep into the service itself. 

2. Compare your current knowledge to the exam requirement to understand the area of focus
    
    Thanks to the excel sheet, I was able to summarize the area of focus that I need to spend more time to study. For me, the area of focus was around:
    - Networking option between on prem and AWS VPC
        - This YouTube video [AWS Networking Fundamentals](https://www.youtube.com/watch?v=hiKPPy584Mg)  explains the core concept of networking in AWS. This is a great refresher and starting point if your area of focus is networking related. From here, you can deep dive into each service as needed. 
    - Content Delivery Network and Domain Name System 
        - Both CloudFront and Route53 are frequently used together in AWS solutions. It is easy to mix up their features. 
        - By reading the [AWS Architecture Blog](https://aws.amazon.com/blogs/architecture/), specifically about [Amazon Route53](https://aws.amazon.com/blogs/architecture/category/networking-content-delivery/amazon-route-53/) and [CloudFront](https://aws.amazon.com/blogs/networking-and-content-delivery/tag/amazon-cloudfront/) has been helpful to identify the purpose of the service within the solution itself. They will also prepare you to design your AWS solution based on the requirements. 
    - Disaster Recovery
        - The first three domains in this exam covers disaster recovery. This is an area where my background doesn't really have exposure on. So, I started with the concept of [disaster recovery options in AWS](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-options-in-the-cloud.html), then deep dive into the related services to understand what disaster recovery option AWS offer. These are essential for not only the exam, but also build your confidence when you are speaking about AWS services in the future.  
    - Migration Strategy
        - The last domain of this exam is all about migration. By mastering the [migration strategy in AWS](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-guide/migration-strategies.html), you will have the confidence to choose the optimum option based on the use case scenario.   

3. Come up with a study plan by working backwards from the exam date

    - This is done by having a set exam date in mind. Use the exam date and work backward for a study plan. In my case, I incorporate more study time on the area of focus, so I can deep dive into them. For services that I am already familiar with, I will glimpse through it, and reinforce my understanding. 
    - Other than study time, make sure to include time to take practice exams. The exam itself is three hours long. Practice and observe how you response during this three hours will help you to manage and plan your time when you are in the real exam. Also, these practice exams are a good checkpoint that will help you to identify how much you had learn/progress in the study plan. 
    - Of course, the study plan can change, but do not try to change the exam date too many times. Once the plan is finalized, go ahead and schedule the exam itself. Having the exam scheduled actually force me to stick with the plan, and execute it. 

4. Taking the exam
    - Given the difficulty and length of this exam, I opted in for the test center option. This helps to ensure the network connectivity, getting immediate assistance in case running into technical issue during the exam, and your family members wont panic when you're locked inside a room for 3 hours. 
    - For non-native English speaker, [A 30-minute exam extension](https://aws.amazon.com/certification/policies/before-testing/) is available upon request. This gives you a total of 220 minutes to answer 75 questions.
    -  During the exam, you want to allocate enough time for each question. I did it by flagging the question that I cannot answer right away. If there's comment or thought on these question, I also make use of the comment feature to notate them. This save me some time to re-read the question again when I come back to review them. After reading all the questions and answered the one that I am confident, I use the rest of my time to answer those flagged questions. 
    - There will be time where I am left with two options that looks like the correct answer. One rule that I apply in this situation is to choose the option that include terms that I had heard before, as these options sometime include distractor, a term that was made up and its not a AWS services or feature.

## Tools
- [Ultimate AWS Certified Solutions Architect Professional 2023 by Stephane Maare](https://www.udemy.com/course/aws-solutions-architect-professional/) - the structure of this course is helpful to understand the basic feature of AWS Services. The author did a great job in explaining how AWS services interact with each other. This makes it easier for the audience to then apply their knowledge to design their AWS solution. 
- [AWS Certified Solutions Architect Professional Practice Exams 2023 by Jon-Bonso](https://portal.tutorialsdojo.com/courses/aws-certified-solutions-architect-professional-practice-exams/?_ga=2.115428815.896634075.1697649659-1980030706.1692804572&_gl=1*qedgrw*_ga*MTk4MDAzMDcwNi4xNjkyODA0NTcy*_ga_L96TFJ1R9K*MTY5NzY0OTY1OC4xNC4xLjE2OTc2NDk2NjguMC4wLjA) - this is the most pratical way to familiarize yourself with the length and format of the exam question. The question itself include the link to the AWS service feature that you can read to understand the correct option. 
- [AWS Training and Certification - Exam Prep Course and Official Practice Question Set](https://skillbuilder.aws/search?page=1&trainingCategory=5&courseLevel=45&domain=8) - this course is a great repositary of references and reading materials about AWS services. The practice exam itself is definitely helpful to familiar yourself with the exam question format.
- [AWS Cloud Quest](https://explore.skillbuilder.aws/learn/course/external/view/elearning/7636/cloud-quest?acq=sec&sec=intro) - you can read as many whitepaper as you want, but without hands on practices, it will be challenging to pass this exam. This game-based learning option has different roles, include Solution Architect, where you will be task to complete all assignment for your role. These hands-on practices will enforce your understanding on how AWS services interact with each other.  
- [AWS Training and Certification - Advanced Architecting on AWS](https://www.aws.training/SessionSearch?pageNumber=1&courseId=10000) - this is a 3 days long instructor-led training with hands on labs where you will deep dive into different scenarios with an architectural challenge. You will need to identify the bottleneck of the scenario, and apply the appropriate AWS services to improve the architecture. 


## Food for Thoughts 
- After all, this is an exam. A good friend of mine had shared that "no one goes into this exam by knowing all the features of AWS services, all you can do during the exam is to do you best". With this mentality, I was able to rebuild my confidence everytime after going through unneccessary melt down when my study is not directly improving my score on practice exam. Anyways, stay positive and remember to breath during the exam, and you will be successful. 
