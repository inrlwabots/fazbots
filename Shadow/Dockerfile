FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/inrlwabots/inrl /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/inrlwabots/uploads
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
