# base image node.js v16
FROM node:16-slim
# Make the variables (key=value) available to the container
ENV SERVER_HOSTNAME=0.0.0.0
ENV SERVER_PORT=8080
# Set the working directory to /app
WORKDIR /app
# Copy the current directory contents into the container at /app
COPY app /app
# Run server.js when the container launches
CMD ["node", "/app/server.js"]
# Make port 8080 available to the world outside this container
EXPOSE 8080

# author: @Gervais_Pierre
# exercice 2