FROM vuminhtuan/android-sdk:ubuntu

# Install NodeJS, Npm
RUN apt-get update -yqq && apt-get install -y \
  nodejs \
  npm \
  && apt-get clean

# Install Ionic
RUN npm install -g ionic cordova
