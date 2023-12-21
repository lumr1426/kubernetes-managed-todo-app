# Using python version 3.9
FROM python:3.9

# the working directory when the conatiner is ran
WORKDIR /usr/src/app

# copy every files in curdir to the workdir
COPY . .

# install requirements when building image
RUN pip install --no-cache-dir -r requirements.txt

# Expose port number, default is 5000
EXPOSE 5000

# command that will run when container starts
CMD ["python", "./app.py"]