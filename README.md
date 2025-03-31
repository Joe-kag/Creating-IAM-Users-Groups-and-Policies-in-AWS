# Creating-IAM-Users-Groups-and-Policies-in-AWS




1\. Identity and Access Management (IAM) secures cloud resources by managing user identities and controlling access. It functions like a bouncer, ensuring only authorized individuals can access specific areas.

IAM is crucial for security and efficiency: Why we need it .

- Data Protection – Secures sensitive information from hackers and unauthorized users.
- Efficiency – Enables quick access for employees, improving productivity.
- Regulatory Compliance – Helps businesses meet data protection requirements.
- Access Management – Ensures users have only the necessary permissions, reducing risks.


- **IAM User** – A unique identity representing a person or application with specific permissions to access AWS resources, either via the console or programmatically.
- **IAM Group** – A collection of IAM users sharing the same permissions, simplifying access management by assigning policies to multiple users at once.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/f9c31f98-e9a2-4e38-a0aa-986f9fd0f8d3/screenshot.jpeg?tl_px=0,0&br_px=700,450&force_format=jpeg&q=100&width=806)


2\. Here’s a step-by-step process for setting up IAM groups and users and Policies:

**STEP 1: Signing into your AWS account as a root user.**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/0ce08ea1-ac32-4157-a51f-9686fd7f4790/screenshot.jpeg?tl_px=0,0&br_px=1617,865&force_format=jpeg&q=100&width=1120.0)


3\. Navigate to IAM console click users then click create user to have this dashboard.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/15bf4c8c-63eb-4e59-9970-cbf6c6437835/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


4\. After putting all the information as required then click create user

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/daf4c45b-8b12-4df0-8410-6d5adfe2c539/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


5\. Successfully user created.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/6acbdaa9-539f-4d41-a505-49f3b8738e98/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


6\. New user created account .

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/813c1c95-19df-4a79-badc-c82a55301c00/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


7\. Step

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/ea602d56-666e-414a-94a5-37a4fd12347f/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


8\. And now we have the URL for new user  to sign in on a different browser

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/6ff36dac-2e0d-4c1d-8de0-f200dfe966ec/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


9\. use a different browser eg incognito to sign in the new user using the -Console sign-in URL

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/39f15f1f-cd76-47a1-8477-08560bb69e5e/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


10\. The display after clicking that URL .

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/12c9f7ae-76a7-45e1-8516-9d38facff921/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


11\. After signing in confirm if the user have any permission where you will find none.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/7d47bffe-3682-412e-b20c-8166f7967f3a/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


12\. Adding permission policy  to a user .

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/8eb77b88-8aaa-4499-9c32-04fe51ce34fb/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


13\. By clicking policies you will see a list of them you can use search tab to filter.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/08f4043d-bffb-4181-8cd6-6e5eb33d2869/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


14\. I decided to create my own policy using JSON .

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/b6a4b36f-826a-476e-a65d-2460e0c1d7df/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


15\. Successfully added policy to a user.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/384923fb-9a9e-488b-abc5-c62003fd7347/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


16\. Navigate to users then click your user and add the policy the user needs.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/4eb7e311-71e7-40ba-88db-fd7306cf418b/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


17\. Adding policy to a user.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/2a038105-74d2-4c01-b2a6-1c44072ca5ea/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


18\. Navigate to IAM console and click User group.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/f186cf6f-6615-44d3-9e66-8eb6285ee072/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


19\. Creating a Group.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/14d26b85-5b45-4e0b-a2df-d7b2d8f97e14/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


20\. Adding user to a group

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/ecd585f0-8a67-4a3d-9c5c-a862a43d90ca/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


21\. After successfully  created my group i added the policies needed.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2025-03-31/a18b0185-30c2-49b0-97bd-dcd8eaf4c0e0/screenshot.jpeg?tl_px=0,0&br_px=1920,1080&force_format=jpeg&q=100&width=1120.0)


22\. **Conclusion** 

This project demonstrates my expertise in managing cloud security with AWS IAM. I created a step-by-step guide to set up IAM users and groups, ensuring secure access to resources. By managing permissions individually or through groups, I showcased skills in protecting data, simplifying access, and organizing user roles. This hands-on project highlights my ability to configure IAM, enforce security rules, and optimize resource management on AWS.
