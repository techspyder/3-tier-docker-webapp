#Taking python base image 
FROM python:3.8-slim

#Creating working dir
WORKDIR /app

#Copy dependencies
COPY requirements.txt .
#Install dependencies
RUN pip install -r requirements.txt

#copy code here 
COPY . .

#command to run python 
CMD ["python", "app.py"]

