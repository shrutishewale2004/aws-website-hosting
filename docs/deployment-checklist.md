# Deployment Checklist

Use this checklist while carrying out a real deployment. Mark items only after verifying them.

## Planning
- [ ] Select AWS Region and instance size.
- [ ] Choose a supported Linux image.
- [ ] Estimate costs and set a budget alert.
- [ ] Decide whether WordPress or Joomla is being hosted.

## Network and access
- [ ] Configure a security group with only required inbound ports.
- [ ] Restrict SSH access to a trusted IP range.
- [ ] Use an appropriate key pair or approved access method.
- [ ] Prefer an IAM role for AWS service access.

## Server and application
- [ ] Apply operating-system security updates.
- [ ] Install and configure a web server.
- [ ] Install the supported runtime and database components.
- [ ] Download CMS files from the official source.
- [ ] Configure database and application secrets securely.
- [ ] Set ownership and permissions according to official guidance.

## Public access
- [ ] Configure DNS if using a domain.
- [ ] Configure HTTPS and renewals.
- [ ] Verify the site from an external network.
- [ ] Confirm logs do not expose secrets.

## Operations
- [ ] Configure backups and test a restore.
- [ ] Document monitoring and troubleshooting.
- [ ] Review AWS costs and remove unused resources.
- [ ] Add sanitized screenshots and verified notes to this repository.
