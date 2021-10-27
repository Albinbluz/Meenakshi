FROM fusuf/whatsasena:latest

RUN git clone https://github.com/vishnuserkl29/Meenakshi /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Chennai
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
