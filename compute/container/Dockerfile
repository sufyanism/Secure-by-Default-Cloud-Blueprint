FROM node:18-alpine
RUN adduser -D appuser
USER appuser
WORKDIR /app
COPY . .
CMD ["node","app.js"]
