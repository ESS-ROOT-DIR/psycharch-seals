# PsychArch living seal, seed 1eb537d54bf499d2. Serves the baked seal on
# port 80. Build the image on any Docker host:
#   docker build -t psycharch-seal .
#   docker run -p 8080:80 psycharch-seal
FROM nginx:alpine
COPY . /usr/share/nginx/html
EXPOSE 80
