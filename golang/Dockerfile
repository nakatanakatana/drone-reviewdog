FROM golang:1.10-alpine

RUN apk add --no-cache ca-certificates wget git && \
wget -q https://github.com/nakatanakatana/reviewdog/releases/download/x.x.x/reviewdog -O /bin/reviewdog && \
chmod +x /bin/reviewdog
