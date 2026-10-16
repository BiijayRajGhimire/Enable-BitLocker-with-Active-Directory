# Enable-BitLocker with-Active-Directory
Step-by-step Group Policy setup with recovery keys stored in AD DS
First step to create Group policy enable BitLocker
<img width="1045" height="436" alt="image" src="https://github.com/user-attachments/assets/ecbe559b-e8ca-458e-84ed-e5a42416c53c" />

. Computer Configuration
 -Policies
   -Administrative Templates
     - Windows Components
          -BitLocker Drive Encryption
Store BitLocker recovery information in Active Directory Domain Services

Select:

✅ Require BitLocker backup to AD DS
✅ Recovery passwords and key packages
<img width="1045" height="366" alt="image" src="https://github.com/user-attachments/assets/0c4b2bfa-7112-4a5e-9d4d-d083d08f5fbe" />
<img width="1045" height="393" alt="image" src="https://github.com/user-attachments/assets/fa45ffa5-2b52-41f9-8d5f-5ab99b91408f" />

: enable require additional authentication 
Computer Configuration
- Policies
- Administrative Templates
- Windows Components
- BitLocker Drive Encryption
- Operating System Drives
<img width="1045" height="490" alt="image" src="https://github.com/user-attachments/assets/7e55300c-2f96-4f3f-891d-f24c1da9b530" />
<img width="1045" height="464" alt="image" src="https://github.com/user-attachments/assets/69714e28-71e5-4f38-9115-c44c265f2645" />

Configure OS Drive Recovery Settings
Computer Configuration
-Policies
- Administrative Templates
- Windows Components
-BitLocker Drive Encryption
- Operating System Drives
<img width="1045" height="341" alt="image" src="https://github.com/user-attachments/assets/2a2a8760-4184-433e-829c-d7fb0a1d5231" />
<img width="1045" height="350" alt="image" src="https://github.com/user-attachments/assets/8101d0af-1fed-43d2-8bee-e949c2b35815" />

After Enable this Require additional authentication at startup windows
<img width="1045" height="386" alt="image" src="https://github.com/user-attachments/assets/2acabc40-cdfb-477e-a5f7-bea4f8d58b53" />
<img width="1045" height="410" alt="image" src="https://github.com/user-attachments/assets/647f6e53-3f03-4d6c-a6e8-f4b1a34c6aea" />

Apply the Policy
gpupdate /force
Install BitLocker drive Encryption through Add Role and feature Wizard
<img width="1045" height="366" alt="image" src="https://github.com/user-attachments/assets/1dd31a2f-e231-414a-80d0-46006925880b" />

Make sure BitLocker is installed properly 
<img width="1045" height="335" alt="image" src="https://github.com/user-attachments/assets/74c2056d-6f34-4775-9514-5db964d88e96" />

open Resultant set of policy and conform BitLocker enable or not?
<img width="953" height="365" alt="image" src="https://github.com/user-attachments/assets/b2259152-4f0f-4258-b37a-eaf6ef3a0a3b" />
<img width="1040" height="399" alt="image" src="https://github.com/user-attachments/assets/a95ba579-e536-449a-a922-26b7dc1b4689" />
<img width="1045" height="379" alt="image" src="https://github.com/user-attachments/assets/a01bb2ed-03fb-497c-9a0c-c3bcf5c6abc6" />

After opening control panel >system and security>BitLocker Driver Encryption and turn on.
<img width="1045" height="469" alt="image" src="https://github.com/user-attachments/assets/9af843dc-1c63-49c0-b43e-135f641076dc" />
<img width="1045" height="319" alt="image" src="https://github.com/user-attachments/assets/4ee0d545-db58-4d2b-bdc1-f43a4bc47536" />
<img width="953" height="448" alt="image" src="https://github.com/user-attachments/assets/7032e07b-9ab2-43b1-aa1f-c743ec71172d" />
<img width="934" height="491" alt="image" src="https://github.com/user-attachments/assets/ab64ed30-c93d-44fb-b122-509a78757b5e" />
<img width="878" height="391" alt="image" src="https://github.com/user-attachments/assets/66aef9a0-f34d-4da8-82c8-a8b7d9979871" />

After restarting bitlocker policy worked 
<img width="1045" height="285" alt="image" src="https://github.com/user-attachments/assets/7db2cdbe-ada4-4507-9600-f0e08dc58b76" />
Conform enable or not BitLocker?
<img width="515" height="340" alt="image" src="https://github.com/user-attachments/assets/aad1fc36-ab8e-45ef-9187-cd28c174e796" />

Need to view and enable Advance feature
<img width="915" height="320" alt="image" src="https://github.com/user-attachments/assets/83a7f384-82e9-4363-a9bb-d48b8687209d" />
<img width="1045" height="430" alt="image" src="https://github.com/user-attachments/assets/a3f9126a-4884-4808-8184-07cdfec86bf4" />

