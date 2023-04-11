FROM node:18.15.0-buster

RUN mkdir /etc/truffle
RUN mkdir /etc/truffle/contracts
WORKDIR /etc/truffle

RUN npm --registry https://registry.npm.taobao.org install -g truffle@5.8.2
RUN npm --registry https://registry.npm.taobao.org install -g @truffle/hdwallet-provider@2.1.9
RUN npm --registry https://registry.npm.taobao.org install -g solc@0.8.4
RUN npm --registry https://registry.npm.taobao.org install -g @openzeppelin/contracts@4.8.2