ocal Endpoint Details
========================================================================================================================
Switch                         | MAC                | IP               | Intf       | Egress Port     | Description                   
------------------------------------------------------------------------------------------------------------------------
DCN-DHL-CC239-BGW-93240-01     | 9ca9.b81a.1102     | 172.22.32.2      | Ethernet1/51.12 | Standalone Ethernet1/51 |                               
DCN-DHL-CC239-BGW-93240-01     | 08f4.f0eb.a102     | 172.22.32.10     | Ethernet1/54.12 | Standalone Ethernet1/54 |                               
DCN-DHL-CC249-BGW-93240-01     | 9ca9.b81a.1102     | 172.22.32.6      | Ethernet1/51.12 | Standalone Ethernet1/51 |                               
DCN-DHL-CC249-BGW-93240-01     | 08f4.f0eb.a102     | 172.22.32.14     | Ethernet1/54.12 | Standalone Ethernet1/54 |                               
DCS-DHL-CC314-BGW-93240-01     | 08f4.f0eb.a102     | 172.21.32.10     | Ethernet1/51.12 | Standalone Ethernet1/51 |                               
DCS-DHL-CC314-BGW-93240-01     | 9ca9.b81a.1102     | 172.21.32.2      | Ethernet1/54.12 | Standalone Ethernet1/54 |                               
DCS-DHL-CC323-BGW-93240-01     | 08f4.f0eb.a102     | 172.21.32.14     | Ethernet1/51.12 | Standalone Ethernet1/51 |                               
DCS-DHL-CC323-BGW-93240-01     | 9ca9.b81a.1102     | 172.21.32.6      | Ethernet1/54.12 | Standalone Ethernet1/54 | 



on local end points , add another column to report the traffic bw rx and tx . see below


DCN-DHL-CC237-LEAF-9348-01     | 8030.e030.eed8     | 172.19.249.17    | Vlan11     | Standalone Eth1/5 |  

 Load-Interval #2: 5 minute (300 seconds)
    300 seconds input rate 48 bits/sec, 0 packets/sec
    300 seconds output rate 272 bits/sec, 0 packets/sec
    input rate 48 bps, 0 pps; output rate 272 bps, 0 pps



DCS-DHL-CC312-LEAF-9348-01     | 2067.7cef.a86c     | 172.19.248.16    | Vlan10     | Standalone Eth1/3 |   
 Load-Interval #2: 5 minute (300 seconds)
    300 seconds input rate 40480 bits/sec, 23 packets/sec
    300 seconds output rate 83408 bits/sec, 30 packets/sec
    input rate 40.48 Kbps, 23 pps; output rate 83.41 Kbps, 30 pps

DCS-DHL-CC312-LEAF-9348-01     | 2067.7cef.a86d     | 172.19.248.17    | Vlan10     | Standalone Eth1/5 |   
  Load-Interval #2: 5 minute (300 seconds)
    300 seconds input rate 0 bits/sec, 0 packets/sec
    300 seconds output rate 2104 bits/sec, 1 packets/sec
    input rate 0 bps, 0 pps; output rate 2.10 Kbps, 1 pps

DCS-DHL-CC312-LEAF-9348-01     | 8030.e030.ee96     | 172.19.249.16    | Vlan11     | Standalone Eth1/6 |   
  Load-Interval #2: 5 minute (300 seconds)
    300 seconds input rate 8 bits/sec, 0 packets/sec
    300 seconds output rate 280 bits/sec, 0 packets/sec
    input rate 8 bps, 0 pps; output rate 280 bps, 0 pps


    so it needs to rx ie input rate  and tx output rate





    then the local end points are reporting onyl interfaces that has both ip and mac. some interfaces has mac only. that is omitted

    ========================================================================================================================
Table 2: Local Endpoint Details
========================================================================================================================
Switch                         | MAC                | IP               | Intf       | Egress Port     | Description                   
------------------------------------------------------------------------------------------------------------------------
DCN-DHL-CC239-BGW-93240-01     | 9ca9.b81a.1102     | 172.22.32.2      | Ethernet1/51.232 | Standalone Ethernet1/51 |                               
DCN-DHL-CC239-BGW-93240-01     | 08f4.f0eb.a102     | 172.22.32.10     | Ethernet1/54.232 | Standalone Ethernet1/54 |                               
DCN-DHL-CC249-BGW-93240-01     | 9ca9.b81a.1102     | 172.22.32.6      | Ethernet1/51.232 | Standalone Ethernet1/51 |                               
DCN-DHL-CC249-BGW-93240-01     | 08f4.f0eb.a102     | 172.22.32.14     | Ethernet1/54.232 | Standalone Ethernet1/54 |                               
DCS-DHL-CC314-BGW-93240-01     | 08f4.f0eb.a102     | 172.21.32.10     | Ethernet1/51.232 | Standalone Ethernet1/51 |                               
DCS-DHL-CC314-BGW-93240-01     | 9ca9.b81a.1102     | 172.21.32.2      | Ethernet1/54.232 | Standalone Ethernet1/54 |                               
DCS-DHL-CC323-BGW-93240-01     | 08f4.f0eb.a102     | 172.21.32.14     | Ethernet1/51.232 | Standalone Ethernet1/51 |                               
DCS-DHL-CC323-BGW-93240-01     | 9ca9.b81a.1102     | 172.21.32.6      | Ethernet1/54.232 | Standalone Ethernet1/54 |   

DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.1589     | 172.27.128.13    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.c827     | 172.27.128.18    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.4c52     | 172.27.128.20    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.d639     | 172.27.128.23    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.ca1b     | 172.27.128.24    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.f59d     | 172.27.128.25    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.81dc     | 172.27.128.26    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.5ca0     | 172.27.128.27    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.08ea     | 172.27.128.28    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.8406     | 172.27.128.29    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.3cf1     | 172.27.128.32    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.91c0     | 172.27.128.33    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.a5fa     | 172.27.128.52    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.a8c8     | 172.27.128.55    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.5a8c     | 172.27.128.57    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.d953     | 172.27.128.60    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.00f4     | 172.27.128.62    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.ecd9     | 172.27.128.65    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.92a9     | 172.27.128.231   | Vlan460    | vPC Po2         |                               
DCN-DHL-CC250-LEAF-9336-01     | 0050.56a7.ef22     | 172.27.128.233   | Vlan460    | vPC Po2         |                               
DCN-DHL-CC251-LEAF-9336-01     | 0050.56a7.1589     | 172.27.128.13    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC251-LEAF-9336-01     | 0050.56a7.c827     | 172.27.128.18    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC251-LEAF-9336-01     | 0050.56a7.4c52     | 172.27.128.20    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC251-LEAF-9336-01     | 0050.56a7.d639     | 172.27.128.23    | Vlan460    | vPC Po2         |                               
DCN-DHL-CC251-LEAF-9336-01     | 0050.56a7.ca1b     | 172.27.128.24    | Vlan460    | vPC Po1         |                               
DCN-DHL-CC251-LEAF-9336-01     | 0050.56a7.f59d     | 172.27.128.25    | Vlan460    | vPC Po1         |               
