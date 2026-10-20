# AWS Website Hosting

A documentation-first project describing an AWS EC2 website-hosting workflow for WordPress and Joomla, including Linux server setup and basic deployment troubleshooting.

> **Accuracy note:** This repository is a starter portfolio template. Add only scripts, screenshots, architecture diagrams, and deployment details that you personally created or verified. Do not claim a live deployment unless you actually completed and tested it.

## Project goals

- Document an EC2-based website-hosting architecture.
- Record Linux server preparation and web-server configuration steps.
- Explain how WordPress or Joomla would be deployed.
- Capture common troubleshooting checks.

## Architecture overview

1. An administrator configures an EC2 instance in AWS.
2. Security-group rules allow only the ports needed for the deployment (commonly HTTP/HTTPS and restricted SSH).
3. A Linux server is configured with a web server and the application's runtime requirements.
4. WordPress or Joomla is installed and configured using secure credentials.
5. DNS and HTTPS are configured if a domain is used.
6. Logs, updates, backups, and access permissions are reviewed.

This is a conceptual outline, not proof that these steps have been executed in a live AWS account.

## Suggested repository structure

- `docs/` — architecture diagrams, verified screenshots, and deployment notes.
- `scripts/` — optional scripts you write and test yourself.
- `docs/deployment-checklist.md` — a checklist to complete during a real deployment.

## Security checklist

- Never commit AWS access keys, private keys, passwords, `.env` files, or database credentials.
- Restrict SSH access to trusted IP addresses rather than opening it to everyone.
- Use IAM roles where appropriate instead of embedding AWS credentials.
- Keep the operating system, web server, CMS, and plugins updated.
- Use HTTPS for public websites and store backups securely.
- Review AWS charges and terminate unused resources.

## How to use this repository

1. Review `docs/deployment-checklist.md`.
2. Add only your own verified notes and screenshots (remove account IDs, public IPs, domains, and sensitive information when needed).
3. If you create scripts, test them in a safe environment and document their requirements.
4. Update this README with your actual environment, results, and lessons learned.

## Technologies

- Amazon EC2
- Linux
- WordPress / Joomla
- Web hosting and deployment fundamentals

## Status

Documentation starter. Add verified implementation evidence before presenting this as a completed hands-on deployment.
