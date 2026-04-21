# Awesome DigitalOcean [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![DOI](https://zenodo.org/badge/1115921989.svg)](https://doi.org/10.5281/zenodo.19673276)  
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) &nbsp; 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

📌 This repository is archived with Zenodo and can be cited using the DOI above.

> A curated list of tools, services, tutorials, integrations, and best practices for building, deploying, and scaling applications on **DigitalOcean**.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official Resources](#official-resources)
- [Compute & Networking](#compute--networking)
- [Managed Databases & Storage](#managed-databases--storage)
- [Kubernetes & Containers](#kubernetes--containers)
- [App Platform & PaaS](#app-platform--paas)
- [Developer Tooling & APIs](#developer-tooling--apis)
- [CI/CD & Automation](#cicd--automation)
- [Monitoring, Logging & Security](#monitoring-logging--security)
- [Marketplace & Add-ons](#marketplace--add-ons)
- [Tutorials & Learning Resources](#tutorials--learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [DigitalOcean](https://www.digitalocean.com/) – Cloud infrastructure provider focused on simplicity and developer experience.
- [DigitalOcean Docs](https://docs.digitalocean.com/) – Official documentation for products, APIs, and tutorials.
- [DigitalOcean Community](https://www.digitalocean.com/community) – Tutorials and Q&A written by engineers and community members.
- [DigitalOcean Status](https://status.digitalocean.com/) – Real-time service status and incident updates.
- [DigitalOcean Blog](https://www.digitalocean.com/blog) – Product updates, engineering posts, and best practices.

## Compute & Networking

- [Droplets](https://www.digitalocean.com/products/droplets) – Scalable virtual machines for running applications and services.
- [CPU-Optimized Droplets](https://www.digitalocean.com/products/droplets#cpu-optimized) – Compute-heavy instances for performance workloads.
- [Load Balancers](https://www.digitalocean.com/products/load-balancer) – Managed load balancing with automatic SSL.
- [VPC Networking](https://www.digitalocean.com/products/vpc) – Private networking between resources.
- [Floating IPs](https://docs.digitalocean.com/products/networking/floating-ips/) – Static IP addresses for high availability.
- [Firewalls](https://www.digitalocean.com/products/cloud-firewalls) – Network-level security rules for Droplets.

## Managed Databases & Storage

- [Managed Databases](https://www.digitalocean.com/products/managed-databases) – Fully managed PostgreSQL, MySQL, Redis, MongoDB, and Kafka.
- [Spaces Object Storage](https://www.digitalocean.com/products/spaces) – S3-compatible object storage for files and media.
- [Volumes Block Storage](https://www.digitalocean.com/products/block-storage) – Persistent block storage for Droplets.
- [Backups & Snapshots](https://docs.digitalocean.com/products/backups/) – Automated backups and system snapshots.

## Kubernetes & Containers

- [DigitalOcean Kubernetes (DOKS)](https://www.digitalocean.com/products/kubernetes) – Managed Kubernetes service with auto-upgrades.
- [Container Registry](https://www.digitalocean.com/products/container-registry) – Private Docker image registry integrated with DO.
- [Helm on DOKS](https://docs.digitalocean.com/tutorials/how-to-install-software-on-kubernetes-with-helm/) – Package management for Kubernetes apps.
- [Ingress Controllers](https://docs.digitalocean.com/products/kubernetes/how-to/configure-ingress/) – Traffic routing for Kubernetes workloads.
- [Autoscaling](https://docs.digitalocean.com/products/kubernetes/how-to/autoscale/) – Scale pods and nodes based on demand.

## App Platform & PaaS

- [App Platform](https://www.digitalocean.com/products/app-platform) – Platform-as-a-Service for deploying web apps and APIs.
- [Static Sites](https://docs.digitalocean.com/products/app-platform/how-to/create-static-sites/) – Host static websites directly from GitHub.
- [Serverless Functions](https://docs.digitalocean.com/products/functions/) – Event-driven compute without server management.
- [Buildpacks](https://docs.digitalocean.com/products/app-platform/reference/buildpacks/) – Language detection and build automation for apps.

## Developer Tooling & APIs

- [DigitalOcean API](https://docs.digitalocean.com/reference/api/) – REST API for managing infrastructure programmatically.
- [doctl](https://docs.digitalocean.com/reference/doctl/) – Official CLI for interacting with DigitalOcean services.
- [Terraform Provider](https://registry.terraform.io/providers/digitalocean/digitalocean/latest) – Infrastructure as code for DigitalOcean resources.
- [Pulumi DigitalOcean](https://www.pulumi.com/registry/packages/digitalocean/) – Cloud infrastructure using general-purpose languages.
- [Client Libraries](https://docs.digitalocean.com/reference/api/api-libraries/) – Community SDKs for Python, Go, Ruby, and more.

## CI/CD & Automation

- [GitHub Actions](https://docs.digitalocean.com/products/app-platform/how-to/deploy-from-github/) – Automated deployments from GitHub repositories.
- [GitLab CI](https://docs.digitalocean.com/products/app-platform/how-to/deploy-from-gitlab/) – Continuous deployment with GitLab pipelines.
- [Terraform Workflows](https://docs.digitalocean.com/products/terraform/) – Declarative infrastructure automation.
- [Ansible](https://www.ansible.com/) – Configuration management for Droplets and services.
- [Cloud-Init](https://docs.digitalocean.com/products/droplets/how-to/cloud-init/) – Bootstrapping scripts for new Droplets.

## Monitoring, Logging & Security

- [Monitoring & Alerts](https://www.digitalocean.com/products/monitoring) – Built-in metrics and alerting for infrastructure.
- [Uptime Checks](https://docs.digitalocean.com/products/uptime/) – Endpoint monitoring for applications.
- [Audit Logs](https://docs.digitalocean.com/products/audit-logs/) – Track account and resource activity.
- [VPC Peering](https://docs.digitalocean.com/products/networking/vpc/) – Secure private networking.
- [DDoS Protection](https://www.digitalocean.com/security/ddos-protection) – Built-in mitigation for network attacks.

## Marketplace & Add-ons

- [DigitalOcean Marketplace](https://marketplace.digitalocean.com/) – One-click apps and images for common stacks.
- [WordPress Droplet](https://marketplace.digitalocean.com/apps/wordpress) – Preconfigured WordPress installation.
- [Docker Droplet](https://marketplace.digitalocean.com/apps/docker) – Docker-ready server image.
- [Plesk](https://marketplace.digitalocean.com/apps/plesk) – Web hosting control panel.
- [OpenLiteSpeed](https://marketplace.digitalocean.com/apps/openlitespeed-wordpress) – High-performance web server stack.

## Tutorials & Learning Resources

### Tutorials
- [DigitalOcean Community Tutorials](https://www.digitalocean.com/community/tutorials) – Step-by-step guides for deploying and managing apps.
- [Deploying with Docker on DigitalOcean](https://docs.digitalocean.com/tutorials/docker-nginx/) – Container-based deployment guides.
- [Kubernetes on DigitalOcean](https://docs.digitalocean.com/tutorials/kubernetes-quickstart/) – Getting started with DOKS.

### Guides
- [Best Practices for Droplets](https://docs.digitalocean.com/products/droplets/guides/recommended-droplet-setup/) – Security and performance guidance.
- [Scaling Applications](https://docs.digitalocean.com/products/app-platform/how-to/scale/) – Horizontal and vertical scaling strategies.
- [Database Management Guides](https://docs.digitalocean.com/products/databases/) – Backup, scaling, and migration practices.

### Courses
- *Cloud Fundamentals with DigitalOcean* – Introductory cloud infrastructure course.
- *Deploying Production Apps on DigitalOcean* – Practical deployment workflows.
- *Kubernetes on DigitalOcean* – Managed Kubernetes operations and scaling.

## Related Awesome Lists

- [Awesome Cloud](https://github.com/awesomelistsio/awesome-cloud)
- [Awesome Kubernetes](https://github.com/awesomelistsio/awesome-kubernetes)
- [Awesome Docker](https://github.com/awesomelistsio/awesome-docker)
- [Awesome DevOps](https://github.com/awesomelistsio/awesome-devops)
- [Awesome SaaS](https://github.com/awesomelistsio/awesome-saas)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
