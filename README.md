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
