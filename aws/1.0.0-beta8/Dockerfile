FROM microsoft/aspnet:1.0.0-beta8

# Install aws-cli
RUN bash -c "curl https://s3.amazonaws.com/aws-cli/awscli-bundle.zip -o awscli-bundle.zip \
	&& unzip awscli-bundle.zip \
  	&& ./awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws"