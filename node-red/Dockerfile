#armhf:FROM nodered/node-red-docker:rpi
#amd64:FROM nodered/node-red-docker:slim

WORKDIR /usr/src/node-red

USER root

# Expose tcp/1880
EXPOSE 1880

# Environment variable holding file path for flows configuration
ENV FLOWS=flows.json

CMD ["npm", "start", "--", "--userDir", "/data"]