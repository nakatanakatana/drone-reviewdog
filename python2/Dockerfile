FROM python:2.7-alpine

RUN apk add --no-cache ca-certificates wget && \
wget -q https://github.com/nakatanakatana/reviewdog/releases/download/x.x.x/reviewdog -O /bin/reviewdog && \
chmod +x /bin/reviewdog && \
pip install pycodestyle flake8
