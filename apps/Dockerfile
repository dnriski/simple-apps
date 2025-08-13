#Menentukan Images
FROM node:18.16

#Perintah Yang Dijalankan
RUN apt update -y && npm install

#Copy file to image
ADD . /app

#MAINTANER IMAGE 
LABEL email="nugrohoriski@gmail.com"

#Perintah yg dijalankan pada saat container sudah up
CMD ["npm", "start"]

#Describe expose port
EXPOSE 3000