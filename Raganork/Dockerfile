FROM RHYTHMHACKER /devil-bot:test

RUN git clone https://github.com/RHYTHMHACKER/DEVIL-BOT
WORKDIR /nspro/devil-bot
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
