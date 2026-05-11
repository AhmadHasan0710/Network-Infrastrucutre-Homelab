<ul>
  <li>Management IP addressing per switch</li>
  <li>Default gateway assignment (VLAN 80 - Infrastructure Management)</li>
  <li>Hostname and domain naming conventions</li>
  <li>VLAN-to-subnet mapping reference structure</li>
</ul>

<h2>Design Philosophy</h2>

<p>
The goal of this approach is to maintain a clean separation between <b>infrastructure design</b> and <b>service-level configuration</b>, ensuring scalability, readability, and ease of automation in future deployments.
</p>

<p>
This structure also reflects real-world enterprise networking practices, where configuration is modularized across switching, routing, security, and service layers.
</p>