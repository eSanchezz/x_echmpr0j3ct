FROM launcher.gcr.io/google/nodejs
RUN install_node v8.9.1
COPY . /app/
RUN (cd programs/server && npm install --unsafe-perm)
CMD node main.js