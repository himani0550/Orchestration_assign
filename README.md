# SampleMERNwithMicroservices
## HelloService
1. ##### We have created .env file and docker file inside helloservice in backend.
2. ##### We have tested out helloservice container. Kindly find below image for same.
![backend_helloservice](https://github.com/himani0550/Orchestration_assign/assets/77041503/c8d3be52-ac31-41ab-b195-4f3cb6d21258)
3. Now, we will push the image to ECR.
![final_image](https://github.com/himani0550/Orchestration_assign/assets/77041503/088c6539-c511-4eae-85e4-4a022cee4e97)

## Profile Microservice
1. ##### We have created .env file inside profile service and have passed mongo URL isnide it.
2. ##### We have created a docker file which will help to containerize the profile microservice.
   ![backend_profileservice](https://github.com/himani0550/Orchestration_assign/assets/77041503/470758f6-9919-4274-b274-09970abd1a87)
3. ##### Now, we will push the image to ECR.
   ![image](https://github.com/himani0550/Orchestration_assign/assets/77041503/82b75ab3-befd-4221-a7a7-8648e0194c2d)

# Microservice deployment using EKS
1. Total three microservices.
   Helloservice
   Profileservice
   Frontend
2. We will set up the EC2 instance.
   ![image](https://github.com/himani0550/Orchestration_assign/assets/77041503/c86bd6d0-7728-4446-9237-e1c87458e0d6)
3. Now, we have to setup AWS CLi on EC2 instance. Use below command for AWS CLI.
   aws configure --profile
4. Conatinerize MERN application.
   For frontend microservice.
   ##### https://github.com/himani0550/Orchestration_assign/tree/main/frontend
5. Push the docker images to ECR repository.
   https://gallery.ecr.aws/c3w1m1q2/himani_orches_backend_hello
   https://gallery.ecr.aws/c3w1m1q2/himani_orches_backend_profiles
   https://gallery.ecr.aws/c3w1m1q2/himani_orches_frontend
   ![image](https://github.com/himani0550/Orchestration_assign/assets/77041503/bbb81c96-532d-45bf-b706-d227bc028ba1)
7. AWS Codecommit
   Have pushed code to codecommit successfully. kindly find below screenshot for same.
   ![image](https://github.com/himani0550/Orchestration_assign/assets/77041503/9941aede-819d-4818-9058-dd4da656545b)

        




         




