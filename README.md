# Firewall-Configuration-PFSense-Rules-
Below is the breakdown of the pfsense firewall rules for configuration I have created and what they are used for.

1. Default Deny Policy: Blocks all unsolicited inbound traffic on the WAN interface by default, protecting internal networks from external threats unless explicitly allowed.

2. Internal Allow Rules: Permits all outbound traffic from the LAN interface, allowing internal devices to access the internet or other permitted networks without restriction.

3. Guest Network Restrictions: Allows the guest network to access the internet only, while blocking any attempts to reach internal or private subnets to maintain network isolation.

4. Management Access Rules: Grants access to pfSense management interfaces (SSH/WebGUI) only from trusted internal subnets, reducing the attack surface and securing administrative access.

5. Logging: Enables logging on critical firewall rules to maintain an audit trail, aiding in troubleshooting, monitoring, and detecting unauthorized activity.
