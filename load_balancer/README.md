# Load balancer

Scripts to set up two Nginx web servers with an X-Served-By header and an HAProxy load balancer (roundrobin).

- 0-custom_http_response_header: installs Nginx and adds the X-Served-By header (web-01 and web-02)
- 1-install_load_balancer: installs HAProxy on lb-01 and balances traffic between web-01 and web-02
