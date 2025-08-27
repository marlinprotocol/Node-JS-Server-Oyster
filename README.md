# Steps to deploy
### Step 1: `npm install`
### Step 2: Install pkg using: `npm i -D pkg`
### Step 3: Create a binary using: `npx pkg -t node18-alpine app.js`
### Step 4: Build the enclave image using: `sudo docker run -it --privileged -v `pwd`:/app/mount marlinorg/enclave-builder`
### Step 5: Change permission of `enclave.eif` from root to user using `sudo chown <userName> -R enclave.eif`
### Step 6: Upload it for downloading (Already added in github releases)
### Step 7: Deploy : ![alt text](https://github.com/ayush-ranjan-official/Node-JS-Server-Oyster/blob/main/Screenshot%20from%202025-08-07%2020-52-38.png)
### Step 8: Use: `curl <IP>:4000`
