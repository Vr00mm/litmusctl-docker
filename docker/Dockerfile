FROM alpine as downloader
RUN wget -O litmusctl.tgz https://litmusctl-production-bucket.s3.amazonaws.com/litmusctl-linux-amd64-v0.5.0.tar.gz \
      && tar xzvf litmusctl.tgz \
      && mv litmusctl /usr/local/bin/ \
      && rm litmusctl.tgz && touch /root/.litmusconfig
