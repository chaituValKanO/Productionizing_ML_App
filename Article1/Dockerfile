FROM ubuntu:18.04

# Set working directory
WORKDIR /home

# Copy files
COPY welcome.sh .

# Update Software repository
RUN apt-get update
 
# Install nginx from ubuntu repository
RUN apt-get install -y nginx

# Expose port required by nginx
EXPOSE 8080
