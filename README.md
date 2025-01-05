# Simple Notes App with Docker
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/omjaju18/django-nginx-db-dockerproject/
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`

## Outputs

![image](https://github.com/user-attachments/assets/91db04a6-4d12-4197-a5ce-2f9ae93546e6)

![image](https://github.com/user-attachments/assets/dfd53150-7a6f-403e-b1ca-0352b8f5e151)

![image](https://github.com/user-attachments/assets/4f3ecede-d9a0-4efa-85be-e591b44595a9)





