# EX - 6 Implementation Of Identity Management (Amazon IAM) For Your Team

## NAME: HEMANATH K
## REG. NO: 212223100012
---

## Aim

To implement identity and access management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

---

## Algorithm

1. Sign in to the AWS Management Console.
2. Navigate to the IAM service.
3. Create IAM groups with defined policies (e.g., Admin, Developer).
4. Create IAM users and assign them to appropriate groups.
5. Create IAM roles if cross-account or service-based access is needed.
6. Attach permissions using managed or custom policies.
7. Enable MFA (Multi-Factor Authentication) for users.
8. Monitor access using IAM Access Analyzer and CloudTrail.

---

## Procedure

### 1. Access IAM

- Go to *AWS Console* → *Services* → *IAM*.

### 2. Create IAM Groups

- Click *Groups* → *Create New Group*.
- Name the group (e.g., Admins, Developers).
- Attach predefined or custom policies (e.g., AmazonEC2FullAccess).

### 3. Create IAM Users

- Click *Users* → *Add Users*.
- Enter usernames and choose *Programmatic access* and/or *AWS Management Console access*.
- Assign users to the appropriate group.

### 4. Create IAM Roles (if needed)

- Go to *Roles* → *Create Role*.
- Select use case (AWS service, another AWS account).
- Attach necessary permissions.

### 5. Apply Policies

- Use AWS managed policies or create custom JSON-based policies.
- Assign them to users, groups, or roles.

### 6. Enable MFA

- For each user, go to *Security credentials*.
- Click *Manage MFA* → Choose *Virtual MFA device* (e.g., Google Authenticator).

### 7. Monitor IAM Usage

- Use *IAM Access Analyzer* to detect unused permissions.
- Use *CloudTrail* for auditing user activity.

---

### Outcome

## 1.IAM Group Creation

<img width="959" height="434" alt="image" src="https://github.com/user-attachments/assets/fb954179-30aa-4472-ae13-1eb1f161f46b" />


## 2.Attach an IAM Policy to the group

<img width="959" height="434" alt="image" src="https://github.com/user-attachments/assets/1a95619f-6610-439c-84b9-54b9ff29f70b" />



## 3.Create an IAM User

<img width="959" height="433" alt="image" src="https://github.com/user-attachments/assets/10607bf6-6f79-442d-a03d-92a0341c4dcf" />



## 4.Add The user to the IAM Group

<img width="959" height="434" alt="image" src="https://github.com/user-attachments/assets/af419baa-760f-4565-8bb6-aad759bf5494" />



## 5.Verify user Permissions

<img width="959" height="434" alt="image" src="https://github.com/user-attachments/assets/2c761252-493d-457a-88c4-d0a57c94dcbd" />




## 6.Verify Least-Privilege Access

<img width="959" height="421" alt="image" src="https://github.com/user-attachments/assets/99ca6d7e-0244-4a1c-8368-001993a9b43f" />

<img width="959" height="419" alt="image" src="https://github.com/user-attachments/assets/b32e0ad7-95ca-4dbe-aa5f-0acab5731a96" />





---

## Result

Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.
