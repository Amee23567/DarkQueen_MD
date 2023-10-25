FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Amee23567/DarkQueen_MD /root/Amee23567
WORKDIR /root/Amee23567/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
