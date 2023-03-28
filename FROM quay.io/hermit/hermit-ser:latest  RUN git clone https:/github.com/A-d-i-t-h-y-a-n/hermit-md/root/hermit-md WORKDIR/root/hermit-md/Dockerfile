FROM quay.io/junaid/junaid-ser:latest

RUN git clone https://github.com/deadsoul101/whatsapp-chatgpt-1
WORKDIR /root/hermit-md/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
