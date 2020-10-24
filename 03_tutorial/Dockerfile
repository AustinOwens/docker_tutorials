# Download base image from the latest ubuntu
FROM ubuntu:latest

# Update and upgrade Ubuntu software repository and install various packages
# from ubuntu repositories
RUN apt-get update && apt-get upgrade -y

# Install various packages from ubuntu repository
RUN apt-get install -y python3

# Copying code to file /root/my_py_app.py
COPY ./my_py_app.py /root/my_py_app.py

# Default cmd when starting the container if not overwritten by user
CMD python3 /root/my_py_app.py
