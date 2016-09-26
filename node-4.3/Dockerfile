FROM zolweb/nodejs:node-4.3_npm-3.7

RUN apt-get update && apt-get install -yyq \
  sudo \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

RUN npm install -g bower gulp \
 && npm cache clean -f

WORKDIR /data

CMD ["bash"]
