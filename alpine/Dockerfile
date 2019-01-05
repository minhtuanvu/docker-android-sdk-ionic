FROM vuminhtuan/android-sdk:alpine

# Install NodeJS, Npm
RUN apk -U update && apk -U add \
		nodejs \
		npm \
	&& rm -rf /tmp/* \
	&& rm -rf /var/cache/apk/*

# Install Ionic
RUN npm install -g ionic cordova
