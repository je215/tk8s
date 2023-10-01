# Use an official Node.js runtime as the base image
FROM node:14-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and package-lock.json to the container
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the React app source code to the container
COPY . .

# Build the React app
RUN npm run 

# Expose the port the app runs on
EXPOSE 6000

# Start the app
CMD ["npm", "start"]