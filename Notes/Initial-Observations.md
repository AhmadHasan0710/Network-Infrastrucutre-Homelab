<h1>Initial Observations</h1>

<p>
This section documents the initial state of the network environment prior to full configuration of VLANs, firewall rules, and service integrations.
</p>

<p>
The pfSense system is deployed on a Protectli Vault 4-port appliance, acting as the primary firewall and routing device for the homelab infrastructure. At the start of the configuration process, only basic WAN connectivity and limited LAN functionality were available.
</p>

<p>
The WAN interface was connected directly to a home ISP router, providing internet access but also introducing a double NAT environment that impacted direct management access from internal devices.
</p>

<p>
A single LAN interface was designated for internal traffic, with plans to implement VLAN trunking to a core switch for segmented network design. At this stage, no VLANs or DHCP scopes were fully configured.
</p>

<p>
Early testing revealed that while basic connectivity was functional, management access to the pfSense WebGUI from external networks was unstable due to NAT layering and routing constraints.
</p>

<p>
Overall, the system was operational at a minimal level, but required significant configuration work to achieve the intended segmented and secure architecture.
</p>