# mininet-walktrough

In this walktrough we replicate the following topology:

```
         10mbps   1Gbps    1Gbps    1Gbps    1Gbps    1Gbps    1Gbps    1Gbps    1Gbps    1Gbps    10mbps
  Sender —---- R0 ----- R1 ----- R2 ----- R3 ----- R4 ----- R5 ----- R6 ----- R7 ----- R8 ----- R9 ------ Receiver
          6ms      7ms      7ms      7ms     7ms      7ms      7ms      7ms      7ms      7ms       6ms
```

see also: http://mininet.org/walkthrough/

arch install for mininet: https://aur.archlinux.org/packages/mininet
you also need openvswitch: https://archlinux.org/packages/?name=openvswitch
