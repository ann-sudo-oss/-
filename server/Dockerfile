FROM node:22-alpine
WORKDIR /app
COPY . .
ENV HOST=0.0.0.0 PORT=8787 DATA_DIR=/data COOKIE_SECURE=1
VOLUME ["/data"]
EXPOSE 8787
CMD ["node", "server/server.mjs"]
