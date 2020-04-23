##Personal information

* Su Liang / Male / 1994
* Undergraduate / Xihua University / Software Engineering
* Hometown: Dazhou, Sichuan
* GitHub: https://github.com/mmflys
* Working years: 3 years
* Residence: Baoan District, Shenzhen
* Desired position: Java Development Engineer
* Desired city: Shenzhen

##contact details
* 📱: 18408243829
* 📮: 627162322@qq.com

##Self-evaluation
With 3 years of IT experience and 1 year of infrastructure and cloud operation experience, familiar with AWS Cloud and proposed some solutions and documents for different scenarios, full English office 1.5 years, 1.5 years DevOps experience.

## work experience

### ** Wen Si Hai Hui Technology Co., Ltd. ** (2019/03/01 ~ present)

#### ** Expedia **

* ** Project description **: Online service for foreign tourism hotels
* ** Description of Responsibility **: Responsible for LIS Inventory Platform
* ** Mission **
* Designed in Java, implemented an automated testing framework, the main function is to use rest-assured to build http request, use Mockito mock data, use sharkchili-feifei to obtain data from the database, and finally compare whether the HTTP request response and the data obtained by the database are consistent
* Write a crawler script with Pthon to crawl all servers of all services on the service management page and generate a report page
* Use Powershell to write automated patch scripts, and use Jenkins automated deployment to patch large-volume windows server clusters
* Update the service certificate from AWS IAM to AWS ACM. After encountering the certificate verification problem, research the ssl after rolling back the certificate change and successfully repair the certificate verification problem
* Migrate service from stack AWS to shared AWS account of ECS, ELB, EKS to stack ASG, ELB, EC2, Shipit, Haproxy (TCP proxy), Consul (service governance) private AWS account, add SpringCould profile to service layer Solve the problem of incompatible configuration files during the migration process, and provide the English documentation guide for migration, and follow-up other services will be migrated according to the documentation
* Research service running multi-region poc solution on AWS, providing a public access solution for front-end ALB back-end multi-service operation, multi-region routing at AWS Route53 layer, disaster tolerance, multi-region data consistency by supporting multi-region AWS DB (DynamoDB, Aurora) guarantee
* Build a stack of services running multiple regions on AWS, and use NLB + ALB + Lambda to solve the problem that the ip will change when the private cloud accesses ALB, and then provide support for the private cloud service to access the AWS service, use stability before releasing the service test to test the stability of the ALB solution, use load test to test the load limit of ALB, use smoke test to test whether the private cloud service can access the service managed by ALB, use shadow test to ensure that even if the access to the service managed by ALB fails, you can still switch to the old one service
* According to the migration document, migrate a service with MongdoDB from a shared AWS account to a private AWS account, use AWS DocumentDB to replace the self-managed MongoDB to solve the problem of difficult maintenance, and migrate data from MongoDB on EC2 to AWS DocumentDB through AWS DMS To ensure data consistency, set the AWS VPC Endpont to point to the new DocumentDB to solve the problem that the legacy service still needs to access the DB
* Set up a complete monitoring system for a service, use Splunk Alert to monitor business related alarms, Grafana to monitor JVM, TPS related underlying data, AWS Alarm to monitor service AWS stak (ELB, ASG, EC2) system running status, use pagerduty Set to call the person responsible for support when the corresponding alarm occurs

### ** Shenzhen Tianhe Interactive Technology Co., Ltd. ** (2017/07/01 ~ 2019/03/01)

####**match**

* ** Project description **: Matching service in the Thai chess and card hall
* ** Description of Responsibility **: Complete the matching service independently and access the matching function for all game services under the company
* **A detailed description**
* Redesigned the user request processing path from the original "user-> gateway-> game" to "user-> gateway-> match-> game".
* Matching service abstracts all game service top interfaces, game specific implementation, decoupling gateway and game
* Use NSQ message queue to count game data of each game service
* Use Redis for persistence, match server restart, does not affect match queue
* Match service, test and release with each game server engineer
* Use zookeeper to manage the cluster

The
## Open source project
### [sharkchili-feifei] (https://github.com/mmflys/sharkchili-feifei) (ORM)
A lightweight orm framework, including original SQL query and object statement query, custom cache, paging, removed DAO and AO, less configuration.

##professional skill
* Proficient in Java, familiar with Jvm related knowledge, have experience in .net, Python
* Familiar with Html, CSS, JS, JQuey
* Familiar with SSM, SSH, SpringBoot, SpringCould, Netty
* Familiar with Linux commands, have operation and maintenance experience
* Familiar with CICD tools TeamCity, Jenkins, version control tools Git, SVN
* Familiar with Terraform, Chef, Packer
* Familiar with monitoring tools Splunk, Grafana, Pagerduty
* Familiar with testing tools Jmeter, Postman
* Familiar with containerization technology Docker
* Good at AWS Cloud

## Educational experience
2013.3.1 ~ 2017.7.1 Xihua University Software Engineering Bachelor
