## NGINX Reverse Proxy & Backend Gateway

Showcases how to use NGINX reverse proxy for backend gateway for different endpoints.

The Nginx config has two endpoints `/auth` and `/tenants`. 

### Assumptions
- Two containers named `auth` and `tenants` are already running.
- The containers hosting the backend services are running on the same docker network
- Configuration to reflect the `auth` and `tenants` url is updated in the [.env](.env) file
