FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Shadow-Sir-V1/Shadow-Sir_V3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
