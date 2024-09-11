# a_diagram_for_PVE_network-bridge_PCIE-passthrough_SR-IOV
I demonstrated how the simple PVE network for VMs works

## The Network Diagram on the PVE system

Read here <https://www.cnblogs.com/spaceship9/p/18251423>

The Network Diagram on the PVE system
Until now

VMs only use Network Bridge
I didn't do the ethernet-card-passthrough on any VM other than the OpenWRT VM. In other words, all VMs uses PVE Network Bridge (vmbr0 or vmbr1).

In the past, I did the ethernet-card-passthrough on a NAS VM which works great with physical router and can run at speed of 2.35Gbps full-duplex.
