## Run Without docker
1) Create a VM
2) SSH into VM (ssh username@ip-address)
3) Update and upgrade system (sudo apt-get update && apt-get upgrade -y)
4) install pip (sudo su && apt install python3-pip)
				
6) clone your repo (git clone {repo https link}, branch main, git checkout main)
7) install libraries (pip install -r requirements.txt)
8) Run your app (fastapi run app.py)
9) open port 8000 on VM(govto azure vm network setting
						create inbound port rule)
10) Test your application (open browser, enter public_ip:8000/home in url bar)						

### note port 8000 should be open in VM network setting as FastAPI runs on port 8000 by default
