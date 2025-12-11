FROM mcr.microsoft.com/devcontainers/universal:2-linux
 
# (Optional) Example of installing a Debian package
RUN apt-get update && apt-get install -y xz-utils
 
# Install Vue.js CLI globally (Vue.js tooling)
RUN npm install -g @vue/cli
 
# Install Flask
RUN pip install --no-cache-dir flask