To Create an Ubuntu EC2 instance in AWS, follow the steps below:

1. **Sign in to the AWS Management Console**:
   - Go to the Management Console at https://aws.amazon.com/console/.
   - Sign in with your AWS account credentials.

2. **Navigate to EC2**:
   - once logged in, navigate to the EC2 dashboard by typing "EC2" in the search bar at the top or by selecting "Services" and then "EC2" under the "Compute" section.

3. **Launch Instance**:
   - Click on the "Instances" link in the EC2 dashboard sidebar.
   - Click the "Launch Instance" button.

4. **Choose an Amazon Machine Image(AMI)**:
   - In the "Step 1: Choose an Amazon Machine Image (AMI)" section, select "Ubuntu" from the list of available AMIs.
   - Choose the Ubuntu version you want to use. For example, "Ubuntu Server 20.04 LTS".
   - Click "Select".

5. **Choose an Instance Type**:
   - In the "Step 2: Choose an Instance Type:" section, select the instance type that suits your requirements. The default option (usually a t2.micro instance) is suitable for testing and small workloads.
   - Click "Next: Configure Instance Details".

6. **Configure Instance Details**:
   - Optionally, configure instance details such as network settings, subnets, IAM role, etc. You can leave these settings as default for now.
   - Click "Next: Add Storage".

7. **Add Storage**:
   - Specify the size of the volume (default is usually fine for testing purposes).
   - Click "Next: Add Tags".

8. **Add Tags**:
   - Optionally, add tags to your instance for better organization and management.
   - Click "Next: Configure Security Group".

9. **Configure Security Group**:
   - In the "Step 6: Configure Security Group" section, configure the security group to allow SSH access (port 22) from your IP address.
   - You may also want to allow other ports based on your requirements (e.g., HTTP, HTTPS) as in the attached picture(....png)
   - Click "Review and Launch".

10. **Review and Launch**:
    - Review the configuration of your instance.
    - Click "Launch".

11. **Select key Pair**:
    - In the pop-up window, select an existing key pair or create a new one(Select the .pem format).
    - Check the acknowledgement box.
    - Click "Launch Instances".

12. **Access Your Instance**:
    - Use MobaXterm