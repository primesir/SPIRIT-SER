FROM fusuf/whatsasena:latest

RUN git clone https://github.com/SPlRlT-YT/SPIRIT-SER /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/SPlRlT-YT/media

CMD ["node", "bot.js"]
