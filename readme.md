# FINAL PROJECT


## Closed Issues
Below are the links to closed issues along with brief descriptions:

1. **[Issue #1 - Email Verification Failure](https://github.com/vraj-shaileshbhai-patel/user_management_final_project/issues/1)**  
   When a new user is created, the system fails to send a verification email to Mailtrap. This issue has been resolved by ensuring the email service is correctly configured and triggers the verification process upon user creation.

2. **[Issue #2 - Admin Email Verification](https://github.com/vraj-shaileshbhai-patel/user_management_final_project/issues/3)**  
   Previously, the system allowed admin accounts to bypass email verification, which is incorrect. This issue has been resolved by ensuring that admins are also required to verify their email before accessing the system.

3. **[Issue #3 - Weak Password Allowed](https://github.com/vraj-shaileshbhai-patel/user_management_final_project/issues/5)**  
   The system allowed weak passwords like '12345678' to be approved, which is a security risk. This issue has been fixed by implementing a password strength validator that ensures passwords contain uppercase and lowercase letters, numbers, and special characters (e.g., $, #, etc.).

4. **[Issue #4 - Incorrect Role Update](https://github.com/vraj-shaileshbhai-patel/user_management_final_project/issues/7)**  
   During email verification, the role was incorrectly updated to AUTHENTICATED even if the role was ADMIN. This issue has been fixed to ensure that only users with the role ANONYMOUS are updated to AUTHENTICATED after successful email verification.

5. **[Issue #5 - 401 Error on Token Handling](https://github.com/vraj-shaileshbhai-patel/user_management_final_project/issues/9)**  
   The require_role dependency did not properly handle invalid or missing tokens, resulting in a 401 error when accessing the delete_user endpoint. This issue has been resolved by improving token validation to ensure proper handling of missing or invalid tokens.

---

## New Feature: User Search and Filtering
You can explore the details here in the feature branch:  
[Link to the Feature Branch](https://github.com/vraj-shaileshbhai-patel/user_management_final_project/tree/feature)

---
### About feature
- The Search and Filtering feature allows administrators to easily find and manage users. Admins can search by username, email, or role and filter users based on account status or registration date range. The user management API now supports these capabilities for improved efficiency.

### Feature Image
![Image](https://github.com/vraj-shaileshbhai-patel/user_management_final_project/blob/79154daeb89957530bd612032eb2f7092130b69c/featurefinal.png)
---

## Docker Hub Repository
### You can find the Docker image for this project on Docker Hub:  
### [Link to Docker Hub Repository](https://hub.docker.com/repository/docker/vraj2712/final_project/general)
![Image](https://github.com/vraj-shaileshbhai-patel/user_management_final_project/blob/79154daeb89957530bd612032eb2f7092130b69c/dockerfinal.png)
---

## My Experience

I had a very good experience throughout this course, guided by Professor Keith Williams. I learned a lot of new technologies and tools like Docker and GitHub Actions, which have significantly expanded my technical skills. The course provided great exposure to industry-level coding practices, helping me understand how real-world software development works. Overall, it was a really valuable experience, and I feel more confident in applying my skills to future projects.

