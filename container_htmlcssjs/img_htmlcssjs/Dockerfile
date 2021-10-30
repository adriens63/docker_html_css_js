FROM alpine:latest

# apt-get install -y = apk add pour alpine package add, et pas besoin de update
#ex : RUN apk add --no-cache mysql-client
RUN apk add git
RUN apk add nodejs npm=4.3.1
# et comme npm dépend de nodejs, on pourrait juste ecrire apk add --update npm
RUN npm install -g browser-sync
#installe browser sync, mais autant installer live server en extension vs code directement




