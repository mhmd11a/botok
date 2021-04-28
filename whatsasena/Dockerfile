FROM fusuf/whatsasena:latest

RUN git clone https://github.com/bagusdwip/SHINZU /root/SHINZU
WORKDIR /root/SHINZU/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
