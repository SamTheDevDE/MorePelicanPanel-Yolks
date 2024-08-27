# Use the base Node.js image with version 12.x
FROM node:12.22.12

# Set the working directory inside the container
WORKDIR /app

# Install dependencies with elevated permissions to avoid EACCES errors
RUN npm install -g --unsafe-perm canvas@2.8.0 canvacord@5.0.1

# Alternatively, you can install the packages globally and avoid using the deprecated version
# RUN npm install -g @canvacord/assets canvas --unsafe-perm

# Copy the application code to the container
COPY . .

# Install app dependencies using the legacy peer deps flag
RUN npm install --legacy-peer-deps --unsafe-perm

# Set the command to run your app using Node.js
CMD ["bash"]
