# ChemSus Deployment Case Study

A written case study documenting the real-world deployment, failure, and rebuild of [chemsus.in](https://chemsus.in) — a production Node.js application for ChemSus Technologies Pvt Ltd.

## About

This article covers:

- How a 2TB bandwidth overuse caused a server suspension on RackNerd VPS
- The architectural mistake of mixing development and production on the same server
- The full rebuild: Node.js via NVM, PM2, Nginx, SSL (Let's Encrypt), and UFW firewall
- A clean developer/client responsibility split during redeployment
- How both the developer and a non-technical client used AI (Claude) independently to own their respective parts of the deployment

## Stack

- **Application**: Node.js 20 + SQLite
- **Process Manager**: PM2
- **Reverse Proxy**: Nginx
- **SSL**: Let's Encrypt via Certbot
- **Firewall**: UFW
- **DNS**: Namecheap
- **Hosting**: RackNerd VPS

## Author

**Pavan Kumar Ponnuri** — AI Native Developer

## File

| File | Description |
|------|-------------|
| `index.html` | The full case study article (self-contained HTML with inline CSS) |
