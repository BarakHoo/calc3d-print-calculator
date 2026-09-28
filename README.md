# 3D Print Cost Calculator

A static web app for estimating 3D printing costs (material, time, electricity, and margins).

**Live demo:** https://munkys.dev/calc3d

## Run locally
Open `index.html` in a browser, or serve it with Docker:

```bash
docker build -t calc3d .
docker run --rm -p 8080:80 calc3d
```

Then open http://localhost:8080

## Deployment
Deployed as a lightweight Nginx container behind Caddy on munkys.dev under `/calc3d`.
