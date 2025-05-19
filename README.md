# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

## NAME: JEEVA K
## REG NO: 212223230090

# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3. 

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard. 

Step 3: Create Bucket Click the Create bucket button. 

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access. 

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none). 

Step 9: Advanced Settings (optional) Add tags, configure logging, etc. 

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

b) i. Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances.
Select your instance → Instance State → Terminate.

# Output:

### Create a Bucket:

 ![image](https://github.com/user-attachments/assets/627c7fd7-5396-4098-817f-7d1e671b7e6c)


#####    Go to S3 in AWS Console → Create bucket → Set name & region → Create


### Create a Folder:

 ![image](https://github.com/user-attachments/assets/809ab610-2b11-4640-89f9-14e47f770078)

#####    Open the bucket → Create folder → Name it → Create


### Upload a File:

 ![image](https://github.com/user-attachments/assets/954b4cc4-c2c0-4518-8681-03c53b7c2a09)

#####    Open the bucket → Upload → Add files → Upload


### Delete Folder/File:

 ![image](https://github.com/user-attachments/assets/60b43ce5-bc0f-4161-bf6f-7929fdc7d794)

#####    Select folder/file → Actions → Delete → Confirm


### Delete a Bucket:
 ![image](https://github.com/user-attachments/assets/301e5b9e-104a-4938-9d40-1ffb3774dae6)

#####    Select the bucket → Delete bucket → Confirm name → Delete






### EC2 Instance Management
### Create an Instance:

 ![image](https://github.com/user-attachments/assets/5472abb9-ff7d-4b86-94c2-09a74c24d3e5)


#####    Go to EC2 → Launch instance
   	Choose AMI (e.g., Amazon Linux) → Select Instance type → Next until Launch
   	Choose or create a Key Pair → Launch

### Stop an Instance:
 
![image](https://github.com/user-attachments/assets/eac84fcf-efae-4861-8e52-96c9490ce116)

#####    Select the instance → Actions → Instance state → Stop


### Terminate/Delete an Instance:
 
![image](https://github.com/user-attachments/assets/97f69960-b415-4d8b-b57d-6f1cb2fe731f)

#####    Select the instance → Actions → Instance state → Terminate


# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
