FROM n8nio/n8n:latest

COPY .n8n /home/node/.n8n

USER root
RUN chown -R node:node /home/node/.n8n
USER node