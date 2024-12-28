# Python-app-hosting

In an Ec2 instance Pyhton is already installed or by default. We have to check version of the Python service.

## Steps

### 1) Launce an Ec2 instance with the required port no.
### 2) Checked the version of the python & Updated the package manager
### 3) Installed pip which is python's own package manager.
### 4) make an app for python myapp.
### 5) installed virtual environment for the python and venv source activated.
### 6) Make an file requirements.txt

![Screenshot (17)](https://github.com/user-attachments/assets/273e78b9-ae36-4e32-9ed5-9bd41d46d1a6)

### 7) Also make an python file for website code.

![Screenshot (18)](https://github.com/user-attachments/assets/9e1becd5-adcf-4d7f-a585-a70bf75b7cdd)

### 8) Fired a command which is required to run gunicorn 

![Screenshot (15)](https://github.com/user-attachments/assets/70436f3e-1366-4a35-9527-d24b9b9a4635)

## Result:

![Screenshot (16)](https://github.com/user-attachments/assets/19644b22-b42f-4417-b627-ad2733699c60)


## For converting software into service

### 9) Entered in a path cd /etc/systemd/system and make gunicorn.service file.

![Screenshot (19)](https://github.com/user-attachments/assets/a3589ceb-fb66-44c3-9e08-0bd4fd2ff055)

### 10) Used some commands to run the gunicorn on service

## Result:

![Screenshot (20)](https://github.com/user-attachments/assets/ebb5d3e1-2488-4c2f-bdf8-f7d2545a16d0)

