# Use the official Node.js image as the base image
FROM node

# Set the working directory inside the container to /app
#Say to Docker that all commands should be excuted in that folder
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install the dependencies listed in package.json during the image build
RUN npm install

# Expose port 80 to allow external access to the application this is optiona; 
EXPOSE 80

# Command to run the application when the container starts
CMD ["node", "server.js"]
