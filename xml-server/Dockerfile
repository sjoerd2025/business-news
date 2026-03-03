FROM node@sha256:c4bfed36421c310d1fbb6dc51faf98065768fbc1c2c1ddd554813ecaa81bb2db

## Create app directory
WORKDIR /app

# Copy the package.json and package-lock.json files
COPY . . 

# Install dependencies
RUN npm install

# Expose the port your application is running on
EXPOSE 8001

# Start the application
CMD node index.js --port 8001
