# Use the official Node.js image as the base
FROM node:16

# Set the working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port 5000 for the backend
EXPOSE 5000

# Start the application
CMD ["node", "server.js"]
