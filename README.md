# cloud-security-s3-project
**Demo project:** Private AWS S3 bucket with least-privilege IAM policy.

## Project Overview
This project demonstrates basic cloud security principles using AWS S3:
- Created a **private S3 bucket** (`secure-bucket-sophiapradhan-2025`)
- Uploaded a test file (`hello.txt`)
- Applied **least-privilege IAM policy** to allow a single IAM user (`bucket-reader-sophia`) to read only this file
  
### Policy JSON
<img width="622" height="320" alt="Screenshot 2025-12-04 at 11 10 46 AM" src="https://github.com/user-attachments/assets/616b0c07-d569-455b-a502-ce27395831c0" />
## IAM User
<img width="1439" height="670" alt="Screenshot 2025-12-04 at 11 20 58 AM" src="https://github.com/user-attachments/assets/e9bceb85-7f00-4809-9a26-a5c926fbbc10" />
### S3 Bucket
<img width="623" height="309" alt="Screenshot 2025-12-04 at 11 10 14 AM" src="https://github.com/user-attachments/assets/529b8b9a-493a-4860-bf17-eb7627441c6c" />
## Policy Simulation Test
<img width="1440" height="592" alt="Screenshot 2025-12-04 at 12 02 46 PM" src="https://github.com/user-attachments/assets/0790809e-08b7-480f-94ed-ad8ead7c16c3" />


## How It Works
1. Create a private S3 bucket and upload a test file.
2. Create an IAM user with minimal permissions.
3. Attach a policy allowing only `GetObject` on the specific bucket.
4. Test access to confirm the user can read the file, but the bucket remains private.

## Tools & Services
- AWS S3
- AWS IAM (Identity and Access Management)

## Key Learnings
- How to configure a private S3 bucket  
- How to create a least-privilege IAM policy  
- How to attach IAM policies to users  
- Understanding cloud security best practices
