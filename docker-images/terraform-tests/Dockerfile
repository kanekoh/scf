FROM ruby:2-alpine
ADD https://releases.hashicorp.com/terraform/0.6.14/terraform_0.6.14_linux_amd64.zip /usr/local/bin/
RUN unzip -d /usr/local/bin/ /usr/local/bin/terraform_0.6.14_linux_amd64.zip
RUN apk add --update openssh-client
