# cis246_final_challenge

Name: Bobby Hoffman

Date: 12/19/2020

### Commands Used

Create groups:
```groupadd group_name```

Create new user with specified primary group:
```sudo useradd -g group_name user_name```

Create password for user:
```sudo passwd username```

Give a user admin privileges:
```sudo usermod -aG wheel user_name```

Change owner and group of directory:
```chown user:group filename```

Set permissions for department directory:
```sudo chmod 770 filename```

Set the directory’s setgig and restricted deletion flags
```sudo chmod g+s directory_name```
```sudo chmod o+s directory_name```
