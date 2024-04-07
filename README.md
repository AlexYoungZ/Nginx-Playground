Implemented various NGINX use cases and configurations to enhance web server performance, security, and scalability. Key components and configurations include:

- Utilizing NGINX as a Layer 7 proxy to manage traffic between multiple backend NodeJS services, leveraging IP Hash load balancing for optimal distribution and blocking certain requests.
- Configuring NGINX as a Layer 4 proxy for efficient load balancing between services at the network level.
- Setting up NGINX as a web server to serve static content, utilizing regular expressions for URL matching, and proxy_pass for routing requests.
- Creating DNS records and enabling HTTPS using certbot for secure communication.
- Implementing TLS 1.3 and enabling HTTP/2 support on NGINX to enhance security and performance.
- Managing timeouts and scaling WebSocket connections with NGINX for real-time communication applications.
- Implementing techniques such as TLS passthrough vs termination and blocking undesired requests to ensure security and efficient resource utilization.
- Leveraging NGINX for layer 7 load balancing and layer 4 load balancing to distribute traffic across multiple services effectively.