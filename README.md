# LU5 - Testing, Quality Assurance, and Containerisation

## API checks
```bash
cd api
npm install
npm run lint
npm test
npm run test:coverage
npm run test:api
```

## Docker
```bash
cd api
docker build -t secureapi-api .
```

## Compose
```bash
docker compose up --build
```
