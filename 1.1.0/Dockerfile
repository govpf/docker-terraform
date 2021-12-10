FROM govpf/alpine:3
ENV VERSION 1.1.0
RUN wget https://releases.hashicorp.com/terraform/${VERSION}/terraform_${VERSION}_linux_amd64.zip \
        && unzip terraform_${VERSION}_linux_amd64.zip \
        && mv terraform /usr/local/bin/terraform \
        && rm terraform_${VERSION}_linux_amd64.zip
ENTRYPOINT ["terraform"]
