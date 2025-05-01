# Setting Up an Internal Web Server for XYZ Company

## The output :

![image](https://github.com/user-attachments/assets/f505b1c3-177f-416b-8f40-51e4e31c873a)


# 1- Configure Network and Connectivity:
## - ip add / Ensure the IP Address is static within the internal network
  ![image](https://github.com/user-attachments/assets/b5251666-ca2d-459f-9357-df0e70242118)
## - Set the hostname to intranet.xyz.local
![image](https://github.com/user-attachments/assets/081d3956-ee10-4a71-8921-cc8a41dba1b9)

## - Modify the /etc/hosts file to set up local name resolution.
![image](https://github.com/user-attachments/assets/e372d794-509a-4354-8747-7f97c1e804b7)


# 2- Create Users and Assign Roles:
## - Create users using useradd. & Set passwords for each user
![image](https://github.com/user-attachments/assets/48150cdc-fe0e-44b2-b4e8-f01c15a77ffe)

## - Add admin1 to the sudo group
![image](https://github.com/user-attachments/assets/35d02e91-0267-4580-a7c5-547152195589)

## - Ensure developer1 can modify website files but has no administrative privileges:
![image](https://github.com/user-attachments/assets/7ef08dc3-7d9c-4b41-a227-91ca25af115e)

# 3- Set Up and Manage Files & Permissions:
## - Required Permissions: 
![image](https://github.com/user-attachments/assets/ca25f690-209b-49bf-9f9f-8c725a36c825)
![image](https://github.com/user-attachments/assets/e6179235-f926-4868-b55a-eb06a0643ce8)



# 4 - Install and Configure Web Server:

## - Install Apache

![image](https://github.com/user-attachments/assets/fef45a3b-b13c-4f95-960c-1f844b4b00a3)


## - test HTML page in /var/www/html/index.html

![image](https://github.com/user-attachments/assets/07a0d19c-d531-4cc1-9eeb-543ad28d0bd6)

