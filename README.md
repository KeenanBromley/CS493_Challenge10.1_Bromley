# Challenge10.1

Simple Express app that responds to GET / with Hello, world!.

## Local Run

```bash
npm install
npm start
```

The server listens on PORT if it is set, otherwise it uses 3000.

## Docker

```bash
docker build -t challenge10-1 .
docker run --rm -p 3000:3000 challenge10-1
```

Then open http://127.0.0.1:3000/ or test with curl.

## Render

1. Push this repo to a public GitHub repository.
2. Create a new Render Web Service.
3. Choose Public Git Repo, paste the clone URL, and select the Free plan.
4. Deploy and open the Render URL once the service is live.
5. Suspend the service when you are done testing.
