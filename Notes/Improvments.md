<h1>Improvements</h1>

<p>
Following the successful deployment and stabilization of the network infrastructure, several improvements were identified to enhance performance, scalability, and security.
</p>

<p>
One of the primary improvements was the structured implementation of VLAN segmentation across all network services. This design significantly improved isolation between different functional areas such as user devices, servers, and management systems.
</p>

<p>
Centralizing DNS services within the VLAN 20 server network provided a major enhancement in consistency and control. This allows all connected devices to resolve domain names through a single trusted internal source, improving both security and reliability.
</p>

<p>
The adoption of Tailscale introduced a secure and modern remote access solution, eliminating the need for direct exposure of management interfaces to external networks. This significantly reduced attack surface while maintaining full administrative accessibility.
</p>

<p>
Firewall rule restructuring was another critical improvement. By organizing rules based on priority, specificity, and dependency, the overall network behavior became more predictable and easier to maintain.
</p>

<p>
Future improvements may include:
</p>

<ul>
  <li>Implementation of centralized logging and monitoring (e.g., SIEM integration)</li>
  <li>Deployment of automated configuration backups for pfSense</li>
  <li>Further VLAN expansion for more granular segmentation</li>
  <li>Integration of IDS/IPS systems for enhanced threat detection</li>
</ul>

<p>
Overall, the network has evolved into a scalable and secure homelab environment that closely mirrors enterprise-level design principles while remaining flexible for continued experimentation and learning.
</p>