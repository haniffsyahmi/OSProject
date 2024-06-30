# Use the official Node.js image
FROM node:14

# Create and change to the app directory
WORKDIR /usr/src/app

# Copy dependency manifests to the container
COPY package*.json ./

# Install production dependencies
RUN npm install

# Copy code to the container
COPY . .

# Run the application on startup
CMD [ "node", "index.js" ]
