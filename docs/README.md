# html2pdf-service

This service provides a simple API to print out PDF from HTML documents over a Restful API.
The rendering is using [puppeteer] as its core.

[puppeteer]: https://pptr.dev/

## Getting started

Pull the docker image to run the service

```bash
docker pull pawritharya/html2pdf-service:latest
```

Then launch a container

```bash
docker run --rm -p 3000:3000 pawritharya/html2pdf-service:latest
```

The web server will by default listen on the port 3000, it may be changed with the environment variable `PORT`.

You may now call the [API](api.md)
