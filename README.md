# Adding Users and Remote Access Lab

## Summary
I created multiple users in Active Directory, applied group policies to manage locked accounts, verified the policies, unlocked accounts, and reset passwords as needed.  

### Steps

- **Step 1: Create Multiple Users**
  - Ran a PowerShell script to automatically create a batch of new user accounts in Active Directory.
 
     <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/5dbb9118-c669-4225-b40b-182b0522c4d1" />

- **Step 2: Verify Users**
  - Checked Active Directory to confirm that all the new users were successfully created.
 
    <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/35b21f01-1103-4364-b38a-cb2e29930ba0" />

- **Step 3: Apply Group Policy**
  - Edited Group Policy to manage locked accounts, setting rules for account lockout and security policies.
 
    <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/fe133cb6-e2a3-46be-8ae2-ce4d1489adef" />

- **Step 4: Verify Policy**
  - Tested the policy by attempting logins that triggered account lockouts and confirmed the policy worked as expected.
 
    <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/60491f6e-0948-458f-854f-015bada832a0" />

- **Step 5: Unlock Accounts**
  - Manually unlocked accounts that were locked due to policy enforcement.
 
    <img width="918" height="1142" alt="image" src="https://github.com/user-attachments/assets/9eb27e5f-f8d1-4aca-bb96-ecf436a41c45" />

- **Step 6: Confirm Accounts Unlocked**
  - Verified in Active Directory that the previously locked accounts were now unlocked and could log in.
 
    <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/03ea551d-e1ce-4f2e-b257-14746c1d9e44" />

- **Step 7: Reset User Passwords**
  - Reset passwords for selected users to ensure proper account access and security.
 
    <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/1b2c41bf-1be1-4b15-9af9-8edd60f8b316" />
