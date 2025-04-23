FROM node:current

WORKDIR /home/node

# Copy and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of your app (including index.js)
COPY . .

# Expose the port your app uses
EXPOSE 3000

# Run your app
CMD ["node", "index.js"]

