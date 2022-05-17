FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /tests
ADD node_modules.tar.gz /tests/
COPY . .  
CMD ["npm", "test"]

