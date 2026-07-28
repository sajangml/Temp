Loaded hardcoded credentials from creds.yaml

--- Validation Scope ---
1. Specific Device
2. Fabric (DCN or DCS)
3. All Switches
Select an option (1-3): 3

Enter Service VRF Name: vblock_vrf

--- Service Validation: VRF vblock_vrf ---
Gathering Layer 3 Overlay & VRF evidence...
                                              Table 1: Active Switches (>0 Endpoints) - VRF vblock_vrf (Scope: All Switches (Spines excluded))                                              
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━┓
┃ Switch                      ┃ vPC Domain ┃ Local Ports                                                            ┃ Endpoint Count ┃ Remote Routes ┃ Classification            ┃ Health  ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━┩
│ DCN-DHL-CC254-LEAF-93240-01 │ 1          │ Vlan52, Vlan54, Vlan58, Vlan2192                                       │ 2 Endpoints    │ 487           │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
├─────────────────────────────┼────────────┼────────────────────────────────────────────────────────────────────────┼────────────────┼───────────────┼───────────────────────────┼─────────┤
│ DCN-DHL-CC255-LEAF-93240-01 │ 1          │ Vlan52, Vlan54, Vlan58, Vlan2192                                       │ 2 Endpoints    │ 487           │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
├─────────────────────────────┼────────────┼────────────────────────────────────────────────────────────────────────┼────────────────┼───────────────┼───────────────────────────┼─────────┤
│ DCS-DHL-CC336-LEAF-93240-01 │ 1          │ Vlan52, Vlan54, Vlan58, Vlan2191                                       │ 3 Endpoints    │ 486           │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
├─────────────────────────────┼────────────┼────────────────────────────────────────────────────────────────────────┼────────────────┼───────────────┼───────────────────────────┼─────────┤
│ DCS-DHL-CC337-LEAF-93240-01 │ 1          │ Vlan52, Vlan54, Vlan58, Vlan2191                                       │ 3 Endpoints    │ 486           │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
├─────────────────────────────┼────────────┼────────────────────────────────────────────────────────────────────────┼────────────────┼───────────────┼───────────────────────────┼─────────┤
│ DCN-DHL-CC239-BGW-93240-01  │ 2          │ Vlan2192, Standalone Po501, Standalone Ethernet1/51.62, Standalone     │ 4 Endpoints    │ 253           │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│                             │            │ Ethernet1/54.62, Standalone Ethernet1/7.3278                           │                │               │                           │         │
├─────────────────────────────┼────────────┼────────────────────────────────────────────────────────────────────────┼────────────────┼───────────────┼───────────────────────────┼─────────┤
│ DCN-DHL-CC249-BGW-93240-01  │ 2          │ Vlan2192, Standalone Po501, Standalone Ethernet1/51.62, Standalone     │ 4 Endpoints    │ 253           │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│                             │            │ Ethernet1/54.62, Standalone Ethernet1/7.3278                           │                │               │                           │         │
├─────────────────────────────┼────────────┼────────────────────────────────────────────────────────────────────────┼────────────────┼───────────────┼───────────────────────────┼─────────┤
│ DCS-DHL-CC314-BGW-93240-01  │ 2          │ Vlan2191, Standalone Ethernet1/51.62, Standalone Ethernet1/54.62,      │ 3 Endpoints    │ 254           │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│                             │            │ Standalone Ethernet1/7.3278                                            │                │               │                           │         │
├─────────────────────────────┼────────────┼────────────────────────────────────────────────────────────────────────┼────────────────┼───────────────┼───────────────────────────┼─────────┤
│ DCS-DHL-CC323-BGW-93240-01  │ 2          │ Vlan2191, Standalone Ethernet1/51.62, Standalone Ethernet1/54.62,      │ 3 Endpoints    │ 254           │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│                             │            │ Standalone Ethernet1/7.3278                                            │                │               │                           │         │
└─────────────────────────────┴────────────┴────────────────────────────────────────────────────────────────────────┴───────

this is another report. however it is missing a few nodes

DCS-DHL-CC312-LEAF-9348-01# show interface status | i connected
mgmt0         --                 connected routed    full    1000    --         
Eth1/3        BHS                connected 10        full    1000    10/100/1g  
Eth1/5        BHS                connected 10        full    1000    10/100/1g  
Eth1/6        BHS                connected 11        full    1000    10/100/1g  
Eth1/48       OOB VLAN Access Po connected 501       full    1000    10/100/1g  
Eth1/53       connected-to-DCS-D connected routed    full    100G    QSFP-100G40G-BIDI
Eth1/54       connected-to-DCS-D connected routed    full    100G    QSFP-100G40G-BIDI
Po99          "vpc-peer-link DCS connected trunk     auto    auto    --         
Lo0           Routing loopback i connected routed    auto    auto    --         
Lo1           VTEP loopback inte connected routed    auto    auto    --         
Vlan10        BHS_10_NW          connected routed    auto    auto    --
Vlan11        BHS_11_NW          connected routed    auto    auto    --
Vlan60        CASI_60_NW         connected routed    auto    auto    --
Vlan91        APC_91_NW          connected routed    auto    auto    --
Vlan100       NET_MGMT_100_NW    connected routed    auto    auto    --
Vlan131       SKIDATA_131_NW     connected routed    auto    auto    --
Vlan160       PA_EWIS_160_NW     connected routed    auto    auto    --
Vlan310       VOICE_310_NW       connected routed    auto    auto    --
Vlan390       SITA_390_NW        connected routed    auto    auto    --
Vlan501       GLOBAL_501_NW      connected routed    auto    auto    --
Vlan701       LPR_701_NW         connected routed    auto    auto    --
Vlan730       PIDS_730_NW        connected routed    auto    auto    --
Vlan770       VX_MGMT_DCS        connected routed    auto    auto    --
Vlan925       XRAY_925_NW        connected routed    auto    auto    --
Vlan2101      VxBlock VRF        connected routed    auto    auto    --
Vlan2103      NET_MGMT_VRF       connected routed    auto    auto    --
Vlan2107      APC_VRF            connected routed    auto    auto    --
Vlan2109      BHS_VRF            connected routed    auto    auto    --
Vlan2115      CASI_VRF           connected routed    auto    auto    --
Vlan2124      SKIDATA_VRF        connected routed    auto    auto    --
Vlan2129      PA_EWIS_VRF        connected routed    auto    auto    --
Vlan2143      VOICE_VRF          connected routed    auto    auto    --
Vlan2148      SITA_VRF           connected routed    auto    auto    --
Vlan2158      LPR_VRF            connected routed    auto    auto    --
Vlan2159      PIDS_VRF           connected routed    auto    auto    --
Vlan2160      CBST1              connected routed    auto    auto    --
Vlan2164      XRAY_VRF           connected routed    auto    auto    --
Vlan2168      GLOBAL_VRF         connected routed    auto    auto    --
Vlan2179      ABD_ICM_VRF        connected routed    auto    auto    --
Vlan3340      ABD_ICM_3340_NW    connected routed    auto    auto    --
nve1          --                 connected --        auto    auto    --         
DCS-DHL-CC312-LEAF-9348-01# show mac
mac        mac-list   
DCS-DHL-CC312-LEAF-9348-01# show mac address-table interface Eth 1/3
Legend: 
        * - primary entry, G - Gateway MAC, (R) - Routed MAC, O - Overlay MAC
        age - seconds since last seen,+ - primary entry using vPC Peer-Link,
        (T) - True, (F) - False, C - ControlPlane MAC, ~ - vsan,
        (NA)- Not Applicable
   VLAN     MAC Address      Type      age     Secure NTFY Ports
---------+-----------------+--------+---------+------+----+------------------
*   10     2067.7cef.a86c   dynamic  NA         F      F    Eth1/3
DCS-DHL-CC312-LEAF-9348-01# 
DCS-DHL-CC312-LEAF-9348-01# show mac address-table interface Eth 1/5
Legend: 
        * - primary entry, G - Gateway MAC, (R) - Routed MAC, O - Overlay MAC
        age - seconds since last seen,+ - primary entry using vPC Peer-Link,
        (T) - True, (F) - False, C - ControlPlane MAC, ~ - vsan,
        (NA)- Not Applicable
   VLAN     MAC Address      Type      age     Secure NTFY Ports
---------+-----------------+--------+---------+------+----+------------------
*   10     2067.7cef.a86d   dynamic  NA         F      F    Eth1/5
DCS-DHL-CC312-LEAF-9348-01# show mac address-table interface Eth 1/6
Legend: 
        * - primary entry, G - Gateway MAC, (R) - Routed MAC, O - Overlay MAC
        age - seconds since last seen,+ - primary entry using vPC Peer-Link,
        (T) - True, (F) - False, C - ControlPlane MAC, ~ - vsan,
        (NA)- Not Applicable
   VLAN     MAC Address      Type      age     Secure NTFY Ports
---------+-----------------+--------+---------+------+----+------------------
*   11     8030.e030.ee96   dynamic  NA         F      F    Eth1/6
DCS-DHL-CC312-LEAF-9348-01# 
DCS-DHL-CC312-LEAF-9348-01# 
DCS-DHL-CC312-LEAF-9348-01# show ip arp vrf bhs_vrf 

Flags: * - Adjacencies learnt on non-active FHRP router
       + - Adjacencies synced via CFSoE
       # - Adjacencies Throttled for Glean
       CP - Added via L2RIB, Control plane Adjacencies
       PS - Added via L2RIB, Peer Sync
       RO - Re-Originated Peer Sync Entry
       D - Static Adjacencies attached to down interface

IP ARP Table for context bhs_vrf
Total number of entries: 3
Address         Age       MAC Address     Interface       Flags
172.19.248.16   00:00:24  2067.7cef.a86c  Vlan10                   
172.19.248.17   00:03:19  2067.7cef.a86d  Vlan10                   
172.19.249.16   00:02:48  8030.e030.ee96  Vlan11   

this one has a mac and ip but not reproted as active end points. 
