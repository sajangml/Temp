--- Service Validation Report: VRF vblock_vrf ---
Scope: All Switches (Spines excluded)
Date: 2026-07-28 02:45:15

===========================================================================================================================================================
Table 1: Active Switches (>0 Endpoints)
===========================================================================================================================================================
Switch                         | vPC Domain | Local Ports                    | Endpoint Count  | Remote Routes | Classification            | Health    
-----------------------------------------------------------------------------------------------------------------------------------------------------------
DCN-DHL-CC254-LEAF-93240-01    | 1          | Vlan52, Vlan54, Vlan58, Vlan2192 | 2 Endpoints     | 487           | ACTIVE - LOCALLY ATTACHED | HEALTHY   
DCN-DHL-CC255-LEAF-93240-01    | 1          | Vlan52, Vlan54, Vlan58, Vlan2192 | 2 Endpoints     | 487           | ACTIVE - LOCALLY ATTACHED | HEALTHY   
DCS-DHL-CC336-LEAF-93240-01    | 1          | Vlan52, Vlan54, Vlan58, Vlan2191 | 3 Endpoints     | 486           | ACTIVE - LOCALLY ATTACHED | HEALTHY   
DCS-DHL-CC337-LEAF-93240-01    | 1          | Vlan52, Vlan54, Vlan58, Vlan2191 | 3 Endpoints     | 486           | ACTIVE - LOCALLY ATTACHED | HEALTHY   
DCN-DHL-CC239-BGW-93240-01     | 2          | Vlan2192, Standalone Po501, Standalone Ethernet1/51.62, Standalone Ethernet1/54.62, Standalone Ethernet1/7.3278 | 4 Endpoints     | 253           | ACTIVE - LOCALLY ATTACHED | HEALTHY   
DCN-DHL-CC249-BGW-93240-01     | 2          | Vlan2192, Standalone Po501, Standalone Ethernet1/51.62, Standalone Ethernet1/54.62, Standalone Ethernet1/7.3278 | 4 Endpoints     | 253           | ACTIVE - LOCALLY ATTACHED | HEALTHY   
DCS-DHL-CC314-BGW-93240-01     | 2          | Vlan2191, Standalone Ethernet1/51.62, Standalone Ethernet1/54.62, Standalone Ethernet1/7.3278 | 3 Endpoints     | 254           | ACTIVE - LOCALLY ATTACHED | HEALTHY   
DCS-DHL-CC323-BGW-93240-01     | 2          | Vlan2191, Standalone Ethernet1/51.62, Standalone Ethernet1/54.62, Standalone Ethernet1/7.3278 | 3 Endpoints     | 254           | ACTIVE - LOCALLY ATTACHED | HEALTHY   

===========================================================================================================================================================
Table 4: Stale Switches (0 Endpoints)
===========================================================================================================================================================
Switch                         | vPC Domain | Local Ports                    | Endpoint Count  | Remote Routes | Classification            | Health    
-----------------------------------------------------------------------------------------------------------------------------------------------------------
DCN-DHL-CC237-LEAF-9348-01     | 3          | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC240-LEAF-9348-01     | 3          | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC311-LEAF-9348-01     | 3          | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC312-LEAF-9348-01     | 3          | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC250-LEAF-9336-01     | 4          | Vlan52, Vlan54, Vlan58, Vlan2192 | 0 Endpoints     | 491           | ACTIVE - REMOTE VXLAN     | REVIEW    
DCN-DHL-CC251-LEAF-9336-01     | 4          | Vlan52, Vlan54, Vlan58, Vlan2192 | 0 Endpoints     | 491           | ACTIVE - REMOTE VXLAN     | REVIEW    
DCS-DHL-CC324-LEAF-9336-01     | 4          | Vlan52, Vlan54, Vlan58, Vlan2191 | 0 Endpoints     | 492           | ACTIVE - REMOTE VXLAN     | REVIEW    
DCS-DHL-CC325-LEAF-9336-01     | 4          | Vlan52, Vlan54, Vlan58, Vlan2191 | 0 Endpoints     | 492           | ACTIVE - REMOTE VXLAN     | REVIEW    
DCN-DHL-CC242-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC249-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC252-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC253-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC253-LEAF-9348-02     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC254-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC256-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC259-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC265-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC266-LEAF-93240-01    | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC267-LEAF-93240-01    | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC272-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCN-DHL-CC272-LEAF-9348-02     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC315-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC317-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC322-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC324-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC326-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC327-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC327-LEAF-9348-02     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC335-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC343-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC345-LEAF-93240-01    | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC346-LEAF-93240-01    | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC347-LEAF-9348-01     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    
DCS-DHL-CC347-LEAF-9348-02     | Standalone | None                           | 0 Endpoints     | 0             | STALE (VRF DEFINITION ONLY) | REVIEW    

========================================================================================================================
Local Endpoint Details
========================================================================================================================
Switch                         | MAC                | IP               | Intf       | Egress Port     | Description                   
------------------------------------------------------------------------------------------------------------------------
DCN-DHL-CC254-LEAF-93240-01    | 0060.1699.2e68     | 172.26.32.230    | Vlan52     | vPC Po200       |                               
DCN-DHL-CC254-LEAF-93240-01    | 0060.1699.2e68     | 172.26.38.230    | Vlan58     | vPC Po200       |                               
DCN-DHL-CC255-LEAF-93240-01    | 0060.1699.2e68     | 172.26.32.230    | Vlan52     | vPC Po200       |                               
DCN-DHL-CC255-LEAF-93240-01    | 0060.1699.2e68     | 172.26.38.230    | Vlan58     | vPC Po200       |                               
DCS-DHL-CC336-LEAF-93240-01    | 0060.1699.2b94     | 172.26.34.220    | Vlan54     | vPC Po200       |                               
DCS-DHL-CC336-LEAF-93240-01    | 0060.1699.2b94     | 172.26.32.220    | Vlan52     | vPC Po200       |                               
DCS-DHL-CC336-LEAF-93240-01    | 0060.1699.2b94     | 172.26.38.220    | Vlan58     | vPC Po200       |                               
DCS-DHL-CC337-LEAF-93240-01    | 0060.1699.2b94     | 172.26.38.220    | Vlan58     | vPC Po200       |                               
DCS-DHL-CC337-LEAF-93240-01    | 0060.1699.2b94     | 172.26.34.220    | Vlan54     | vPC Po200       |                               
DCS-DHL-CC337-LEAF-93240-01    | 0060.1699.2b94     | 172.26.32.220    | Vlan52     | vPC Po200       |                               
DCN-DHL-CC239-BGW-93240-01     | c02c.177a.6b1f     | 172.26.52.130    | port-channel501.47 | Standalone Po501 |                               
DCN-DHL-CC239-BGW-93240-01     | 9ca9.b81a.1102     | 172.22.32.2      | Ethernet1/51.62 | Standalone Ethernet1/51 |                               
DCN-DHL-CC239-BGW-93240-01     | 08f4.f0eb.a102     | 172.22.32.10     | Ethernet1/54.62 | Standalone Ethernet1/54 |                               
DCN-DHL-CC239-BGW-93240-01     | 4006.d539.7c87     | 172.22.10.61     | Ethernet1/7.3278 | Standalone Ethernet1/7 |                               
DCN-DHL-CC249-BGW-93240-01     | c02c.177a.6b1f     | 172.26.52.134    | port-channel501.44 | Standalone Po501 |                               
DCN-DHL-CC249-BGW-93240-01     | 9ca9.b81a.1102     | 172.22.32.6      | Ethernet1/51.62 | Standalone Ethernet1/51 |                               
DCN-DHL-CC249-BGW-93240-01     | 08f4.f0eb.a102     | 172.22.32.14     | Ethernet1/54.62 | Standalone Ethernet1/54 |                               
DCN-DHL-CC249-BGW-93240-01     | 4006.d539.7c88     | 172.22.11.89     | Ethernet1/7.3278 | Standalone Ethernet1/7 |                               
DCS-DHL-CC314-BGW-93240-01     | 08f4.f0eb.a102     | 172.21.32.10     | Ethernet1/51.62 | Standalone Ethernet1/51 |                               
DCS-DHL-CC314-BGW-93240-01     | 9ca9.b81a.1102     | 172.21.32.2      | Ethernet1/54.62 | Standalone Ethernet1/54 |                               
DCS-DHL-CC314-BGW-93240-01     | 482e.723a.d007     | 172.21.10.61     | Ethernet1/7.3278 | Standalone Ethernet1/7 |                               
DCS-DHL-CC323-BGW-93240-01     | 482e.723a.d008     | 172.21.11.89     | Ethernet1/7.3278 | Standalone Ethernet1/7 |                               
DCS-DHL-CC323-BGW-93240-01     | 08f4.f0eb.a102     | 172.21.32.14     | Ethernet1/51.62 | Standalone Ethernet1/51 |                               
DCS-DHL-CC323-BGW-93240-01     | 9ca9.b81a.1102     | 172.21.32.6      | Ethernet1/54.62 | Standalone Ethernet1/54 |                               

=====================================================================================================================================================================
Physical Attachment Details
=====================================================================================================================================================================
Switch                         | Port            | Logical Port    | Description               | Status     | Speed   | Transceiver        | Neighbor        | Neighbor Port  
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
DCN-DHL-CC254-LEAF-93240-01    | Eth1/58         | Po200           | --                        | notconnec  | auto    | N/A                | N/A             | N/A            
DCN-DHL-CC254-LEAF-93240-01    | Eth1/60         | Po200           | --                        | connected  | 40G     | N/A                | N/A             | N/A            
DCN-DHL-CC255-LEAF-93240-01    | Eth1/58         | Po200           | --                        | connected  | 40G     | N/A                | N/A             | N/A            
DCN-DHL-CC255-LEAF-93240-01    | Eth1/60         | Po200           | --                        | connected  | 40G     | N/A                | N/A             | N/A            
DCS-DHL-CC336-LEAF-93240-01    | Eth1/58         | Po200           | --                        | connected  | 40G     | N/A                | N/A             | N/A            
DCS-DHL-CC336-LEAF-93240-01    | Eth1/60         | Po200           | --                        | connected  | 40G     | N/A                | N/A             | N/A            
DCS-DHL-CC337-LEAF-93240-01    | Eth1/58         | Po200           | --                        | connected  | 40G     | N/A                | N/A             | N/A            
DCS-DHL-CC337-LEAF-93240-01    | Eth1/60         | Po200           | --                        | connected  | 40G     | N/A                | N/A             | N/A            
DCN-DHL-CC239-BGW-93240-01     | Eth1/3          | Po501           | po to NextDC              | connected  | 10G     | N/A                | N/A             | N/A            
DCN-DHL-CC239-BGW-93240-01     | Eth1/1          | Po501           | NEXTDC_UPLINK_1_10G       | connected  | 10G     | N/A                | N/A             | N/A            
DCN-DHL-CC239-BGW-93240-01     | Ethernet1/7     | N/A             | N/A                       | N/A        | N/A     | 10Gbase-SR         | N/A             | TenGigabitEthernet0/0/7
DCN-DHL-CC239-BGW-93240-01     | Ethernet1/54    | N/A             | N/A                       | N/A        | N/A     | QSFP-100G-LR       | N/A             | HundredGigE1/0/1
DCN-DHL-CC239-BGW-93240-01     | Ethernet1/51    | N/A             | N/A                       | N/A        | N/A     | QSFP-100G-LR       | N/A             | HundredGigE1/0/1
DCN-DHL-CC249-BGW-93240-01     | Eth1/3          | Po501           | Po to NextDC              | connected  | 10G     | N/A                | N/A             | N/A            
DCN-DHL-CC249-BGW-93240-01     | Ethernet1/7     | N/A             | N/A                       | N/A        | N/A     | 10Gbase-SR         | N/A             | TenGigabitEthernet0/0/8
DCN-DHL-CC249-BGW-93240-01     | Ethernet1/54    | N/A             | N/A                       | N/A        | N/A     | QSFP-100G-LR       | N/A             | HundredGigE1/0/2
DCN-DHL-CC249-BGW-93240-01     | Eth1/2          | Po501           | Po to NextDC              | connected  | 10G     | N/A                | N/A             | N/A            
DCN-DHL-CC249-BGW-93240-01     | Ethernet1/51    | N/A             | N/A                       | N/A        | N/A     | QSFP-100G-LR       | N/A             | HundredGigE1/0/2
DCS-DHL-CC314-BGW-93240-01     | Ethernet1/54    | N/A             | N/A                       | N/A        | N/A     | QSFP-100G-LR       | N/A             | HundredGigE1/0/3
DCS-DHL-CC314-BGW-93240-01     | Ethernet1/51    | N/A             | N/A                       | N/A        | N/A     | QSFP-100G-LR       | N/A             | HundredGigE1/0/3
DCS-DHL-CC314-BGW-93240-01     | Ethernet1/7     | N/A             | N/A                       | N/A        | N/A     | 10Gbase-SR         | N/A             | TenGigabitEthernet0/0/7
DCS-DHL-CC323-BGW-93240-01     | Ethernet1/54    | N/A             | N/A                       | N/A        | N/A     | QSFP-100G-LR       | N/A             | HundredGigE1/0/4
DCS-DHL-CC323-BGW-93240-01     | Ethernet1/7     | N/A             | N/A                       | N/A        | N/A     | 10Gbase-SR         | N/A             | TenGigabitEthernet0/0/8
DCS-DHL-CC323-BGW-93240-01     | Ethernet1/51    | N/A             | N/A                       | N/A        | N/A     | QSFP-100G-LR       | N/A             | HundredGigE1/0/4
