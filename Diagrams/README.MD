<h1>Network Topology Diagram</h1>

<p>
This diagram shows the layout of the homelab network and how everything is connected.
It includes the core switch, distribution switches, and the pfSense firewall.
</p>

<p>
It is meant to give a clear view of how traffic moves through the network and how each part of the system fits together.
</p>

<h2>Overview</h2>

<ul>
  <li>The core switch connects to all distribution switches</li>
  <li>Each distribution switch handles different VLAN groups</li>
  <li>pfSense manages routing between VLANs and internet access</li>
  <li>All VLANs are separated for organization and security</li>
</ul>

<h2>Purpose</h2>

<p>
This diagram is used as a reference for how the network is built and how the devices interact with each other.
It helps explain the structure of the lab in a simple way.