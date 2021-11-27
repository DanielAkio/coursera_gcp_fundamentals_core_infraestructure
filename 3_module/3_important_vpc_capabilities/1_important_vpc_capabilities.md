# You control the topology of your VPC network

- Use its route table to forward traffic within the network, even across subnets

- Use its firewall to control what network traffic is allowed

- Use Shared VPC to share a network, or individual subnets, with other GCP projects
- Use VPC Peering to interconnect networks in GCP projects

# With global Cloud Load Balancing, your application presents a single front-end to the world

- Users get a single, global anycast IP address
- Traffic goes over the Google backbone from the closest point-of-presence to the user
- Backends are selected based on load
- Only healthy bacckends receive traffic
- No pre-warming is required

# Google VPC offers a suite of load-balancing options

- Global http(s)
    - Layer 7 load balancing based on load
    - Can route different URLs to different back ends

- Global SSL Proxy
    - Layer 4 load balancing of non-HTTPS SSL traffic based on load
    - Supported on specific port numbers

- Global TCP Proxy
    - Layer 4 load balancing of non-SSL TCP traffic
    - Supported on specific port numbers

- Regional
    - Load balancing of any traffic (TCP, UDP)
    - Supported on any port number

- Regional internal
    - Load balancing of traffic inside a VPC
    - Use for the internal tiers of multi-tier applications

# Cloud DNS is higly available and scalable

- Create managed zones, then add, edit, delete DNS records

- Prigrammatically manage zones and records using RESTful API or command-line interface

# Cloud CDN (Content Delivery Network) (like AWS CloudFront)

- Use Google's globally distributed edge caches to cache content close to your users
- Or use CDN Interconnect if you'd prefer to use a different CDN

# Google Cloud Platform offers many interconnect options

- VPN
    - Secure multi-Gbps connection over VPN tunnels

- Direct Peering
    - Private connection between you and Google for your hybrid workloads

- Carrier Peering
    - Connection through the largest partner network of service providers

- Dedicated Interconnect
    - Connect N x 10G transport circuits fr private cloud traffic to Google Cloud at Google POPs
