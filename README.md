## Screenshots
### Homepage
![Screenshot 2023-12-15 233856](https://github.com/SATYA-CHARAN/Blood-Bank-Management-System/assets/147343366/0f967306-8391-481a-864c-8ffa5f0b1f8d)

### Admin Dashboard
![Dashboard](https://github.com/SATYA-CHARAN/Blood-Bank-Management-System/assets/147343366/c8d70e5f-66d2-4c7c-b884-0d27d56b77ee)

### Admin Login
![Admin Login](https://github.com/SATYA-CHARAN/Blood-Bank-Management-System/assets/147343366/7992b8df-8ee8-40fe-9d9b-f4e82baa505a)

### Blood Request
![Screenshot 2024-02-04 231835](https://github.com/SATYA-CHARAN/Blood-Bank-Management-System/assets/147343366/f2e0e612-c573-45a7-a78f-a136d9c72fec)
### Logout
![doctor snap](https://github.com/sumitkumar1503/bloodbankmanagement/blob/master/static/screenshot/logout.png?raw=true)
---
## Functions

### Admin
- Create Admin account using following command
```
py manage.py createsuperuser
```
- After Login, can see Unit of blood of each blood group available, Number Of Donor, Number of blood request, Number of approved request, Total Unit of blood on Dashboard.
- Can View, Update, Delete Donor.
- Can View, Update, Delete Patient.
- Can View Donation Request made by donor and can approve or reject that request based on disease of donor.
- If Donation Request approved by admin then that unit of blood added to blood stock of that blood group.
- If Donation Request rejected by admin then 0 unit of blood added to stock.
- Can View Blood Request made by donor / patient and can approve or reject that request.
- If Blood Request approved by admin then that unit of blood reduced from blood stock of that blood group.
- If Blood Request rejected by admin then 0 unit of blood reduced from stock.
- Can see history of blood request.
- Can Update Unit Of Particular Blood Group.


### Donor
- Donor can create account by providing basic details.
- After Login, Donor can donate blood, After approval from admin only, blood will be added to blood stock.
- Donor can see their donation history with status (Pending, Approved, Rejected).
- Donor can also request for blood from blood stock.
- Donor can see their blood request history with status.
- Donor can see number of blood request Made, Approved, Pending, Rejected by Admin on their dashboard.
> **_NOTE:_**  Donor can donate blood and can also request for blood.





### Patient
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can see number of blood request Made, Approved, Pending, Rejected by Admin on their dashboard.
- Patient can request for blood of specific blood group and unit from blood stock.
- Patient can see their blood request history with status (Pending, Approved, Rejected).

---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :

```
python -m pip install -r requirements. txt
```

```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```
