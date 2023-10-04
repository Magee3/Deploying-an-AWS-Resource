# Deploying-an-AWS-Resource

## Objective

We will create a proof of concept virtualization deployment. We will explore the AWS Console interface, create a resource group to manage a departments AWS resources, and lastly we will configure and scale a virtual machine.

### Stage 1: Access the AWS Console

This is you default AWS homepage after you log in of course. 

![1](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/13bd0b15-99a0-42d9-b833-ab6feb05051c)

In the top right corner of the AWS console you can select what region you would like to be in. 

![2](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/0e9cf9c0-7793-43fd-a037-f763dc86b261)


### Stage 2: Access Common AWS Services

We will continue to explore AWS and check out what services they have.

![3](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/dbd3604d-ff9d-4c61-b1c0-fd939ac87c7b)

Click on "All Services"

![4](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/5117d4f7-a653-476d-a9c7-cb16a670d56c)

Click on "Compute" the select EC2"

![5](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/6516a490-38e5-4d2a-b730-b1c7d7761ae0)

Here is the EC2 Dashboard, the HUB in which you will change all of your EC2 settings.

![6](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/84f9aece-55c0-4694-9a93-31e382c63d15)

Select "Instances"

![7](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/ecb9e04d-4b4b-486e-b32e-76444736a366)

Here is you Instances page where you will find what services are running, stopped, etc. To return to the main page select "EC2 Dashboard"

![8](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/a1599489-01b2-4126-a493-72fc2b7fb3f2)

Type in "compute" in the searchbar above and select "Elastic Container Service". If it does not show up select "See all results" and proceed.

![9](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/3e1ff209-6dab-4893-84fe-e37c7d5dddba)
![10](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/3ae1c321-abbb-4500-b9ec-68133a801142)

Here is the Container Service page / Cluster page. 
Select "Create cluster"

![11](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/34bbd7c0-1f8c-448b-bdce-4e8c8157d490)

Here is where we can create and modify clusters. Just scroll down to the bottom and click cancel. 

![12](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/a1139cf6-86e0-420e-97fe-4c334ec0a643)
![13](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/2cbcd107-d185-4df2-b369-e9ab3506312f)

ECS is a fully managed orchestration service for containers. Fargate is a serverless pay-as-you-go compute engine that allows you to focus on building apps without managing servers. This leverages a serverkess archutectyre for resources on your container.

![14](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/db3522e1-712f-437a-95e2-4f0860865737)

At the top click the AWS logo or tpye "home" to return to the dashboard.

![15](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/ffb285dc-f970-43cb-b3d1-53f4f5cddc94)


### Stage 3: Create a Default Virtual Private Cloud (VPC)

![16](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/fa02d8af-94b7-437a-b72d-edc0c667f521)

![17](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/4b96d3e9-2ae1-48ab-b2b7-5fcdb4e22207)

![18](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/5dc82f94-ba0e-4273-aeaa-be43a84b7f34)

![19](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/ea4b3fb3-ee11-4c1d-88f3-82e5a98772a6)

![20](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/ff36ebd1-36b8-4b42-a981-f3589bc6771b)

![21](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/310e3ab0-f499-43d1-9488-0e8402e706a3)

![22](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/3d8510a2-9f8d-47c7-b254-c167e411cbd7)

![23](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/4558f8ad-a0d9-4c1c-acc0-cad9e25ce70f)

![24](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/c9502bee-9b58-45fc-a390-c0bbb9dbd67f)








### Stage 4: Deploy an EC2 Instance


![25](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/76e06c54-6d1e-4824-ad01-b714b996a8ea)

![26](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/7d335b04-4838-4642-a5bb-fce3a1db80ee)

![28](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/0d97a464-1b60-4158-bd1a-2af98c962b8e)

![29](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/f70d6389-0670-4cdf-94a4-522fbff1aee1)

![30](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/fa11ad19-cd55-4167-ab3f-be54a559b1d2)

![31](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/af63fa9d-6a2d-481d-8a28-939b84faadeb)

![32](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/088dd9eb-7b67-4156-8991-658dc80e7ca1)

![33](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/b0d020e5-434a-4e4b-ac12-f594c5ca908d)

![34](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/f4855956-36df-4740-83db-9a864287376d)

![35](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/8417e58b-4a67-4a6e-adb5-9337082da0ca)



![36](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/bd1e7943-d2bb-45d6-a200-1e5a4fa86fde)

![37](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/c33dc7c5-8a8b-485d-b403-765dee1cf1d2)

![38](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/98c1b0e8-a6ad-4cfd-8f53-fd26c8805236)



### Stage 5: Manage EC2 Instance State

![39](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/422d4b41-38ab-47d9-becc-e1f3e1ae98f2)

![40](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/31c62e5f-6051-4ae3-a974-5f0ebc46c9ba)

![41](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/0f62f17d-d247-4385-ad96-f2ff8c3f0060)

![42](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/4b481e54-b478-4f8e-aed9-996adc0f6eb0)

![43](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/23884eb8-c134-4b6e-9052-0e96a37bbbf4)

![44](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/54b740bf-ff84-4a3b-b230-60d437a3da4d)

![45](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/4554ba80-600a-421c-9ea1-2c8aedda8a7e)


### Stage 6: Scale an Existing EC2 Instance


![46](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/0d324ec6-9401-4ad4-b6ee-ad76eafcbc43)

![47](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/d2ba2a3b-1231-4b38-8c11-d1c261d60d5e)


![48](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/2f73d154-fbf7-4a38-a703-147be09d4382)

![49](https://github.com/Magee3/Deploying-an-AWS-Resource/assets/134301259/d501ecf8-599f-42e9-90fc-70500c68fd70)




