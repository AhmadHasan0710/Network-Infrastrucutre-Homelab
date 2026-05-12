<h1>Troubleshooting</h1>

<p>
During the configuration process, several technical challenges were encountered that required iterative troubleshooting and system adjustments.
</p>

<p>
The first major issue was the presence of a double NAT configuration between the ISP router and pfSense. This resulted in restricted inbound access and inconsistent routing behavior when attempting to access the pfSense WebGUI from devices outside the local management network.
</p>

<p>
To mitigate this, initial firewall restrictions were temporarily relaxed to allow direct access to the management interface. This enabled continued configuration without being blocked by early-stage security policies.
</p>

<p>
A secondary troubleshooting step involved the implementation of Tailscale on the pfSense device. This provided a secure overlay network, allowing remote access to the firewall without relying on traditional port forwarding or NAT traversal methods.
</p>

<p>
Additional issues were encountered during VLAN and interface configuration. Misaligned trunk settings and incomplete VLAN tagging initially prevented proper communication between pfSense and the core switch.
</p>

<p>
DHCP assignment inconsistencies were also observed, particularly when overlapping scopes or incorrect interface bindings were applied. These issues were resolved through systematic reconfiguration of VLAN interfaces and validation of subnet assignments.
</p>

<p>
The most complex troubleshooting phase involved firewall rule conflicts. Several rules that appeared correct in isolation created unintended blocking behavior when evaluated in combination. This required a methodical review of rule order, specificity, and interface assignment.
</p>

<p>
Through repeated testing and adjustment, stable connectivity and predictable traffic flow were eventually achieved across all configured networks.
</p>