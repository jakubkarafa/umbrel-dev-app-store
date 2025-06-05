FROM node:20

RUN npm install -g firebase-tools

WORKDIR /app
COPY . .

RUN cd functions && npm install

CMD ["firebase", "emulators:start", "--only", "auth,firestore,functions", "--project", "local-project"]
