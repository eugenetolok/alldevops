FROM node:18-alpine

RUN apk add --no-cache curl aws-cli jq gettext moreutils git bash terraform --repository=https://dl-cdn.alpinelinux.org/alpine/edge/community
# serverless part
RUN npm i -g serverless \
             serverless-wsgi \
             serverless-offline \
             serverless-prune-plugin \
             serverless-deployment-bucket \
             serverless-python-requirements \
             serverless-plugin-resource-tagging \
             serverless-plugin-elastic-beanstalk
