FROM fusuf/whatsasena:latest

RUN git clone https://github.com/TURBOHYPER/Toxic-Alexa /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --ignore-engines
 
CMD ["node", "bot.js"]
