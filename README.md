Enter Service VRF Name: global_vrf

--- Service Validation: VRF global_vrf ---
Gathering Layer 3 Overlay & VRF evidence...
                                                                                     Service Validation: VRF global_vrf (Scope: All Switches (Spines excluded))                                                                                      
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━┓
┃ Switch                      ┃ Local Ports                                                                                         ┃ Local Endpoints (MAC / IP)                              ┃ Remote Routes ┃ Classification            ┃ Health  ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━┩
│ DCN-DHL-CC239-BGW-93240-01  │ Vlan500, Vlan501, Vlan502, Vlan503, Vlan670, Vlan671, Vlan2168, port-channel501, Ethernet1/51.71,   │ e8eb.3412.152f (), c02c.177a.6b1f () (+3 more)          │           131 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│                             │ Ethernet1/54.71, Ethernet1/7.3279                                                                   │                                                         │               │                           │         │
│ DCN-DHL-CC249-BGW-93240-01  │ Vlan500, Vlan501, Vlan502, Vlan503, Vlan670, Vlan671, Vlan2168, port-channel501, Ethernet1/51.71,   │ e8eb.3412.152f (), c02c.177a.6b1f () (+3 more)          │           131 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│                             │ Ethernet1/54.71, Ethernet1/7.3279                                                                   │                                                         │               │                           │         │
│ DCN-DHL-CC237-LEAF-9348-01  │ Vlan500, Vlan501, Vlan503, Vlan670, Vlan671, Vlan2168                                               │ None                                                    │           199 │ ACTIVE - REMOTE VXLAN     │ REVIEW  │
│ DCN-DHL-CC240-LEAF-9348-01  │ Vlan500, Vlan501, Vlan503, Vlan670, Vlan671, Vlan2168                                               │ 482e.72f8.9e58 (), e8d3.2205.0e08 ()                    │           197 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC242-LEAF-9348-01  │ Vlan500, Vlan501, Vlan2168                                                                          │ e8d3.2249.da30 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC249-LEAF-9348-01  │ Vlan501, Vlan503, Vlan2168                                                                          │ e8d3.2249.d178 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC252-LEAF-9348-01  │ Vlan501, Vlan503, Vlan2168                                                                          │ c0f8.7fc5.7a98 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC254-LEAF-9348-01  │ Vlan501, Vlan2168                                                                                   │ 10b3.d568.c3e8 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC256-LEAF-9348-01  │ Vlan501, Vlan503, Vlan2168                                                                          │ 10b3.d557.65e8 (), e8d3.222f.8260 () (+2 more)          │           196 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC259-LEAF-9348-01  │ Vlan501, Vlan2168                                                                                   │ e8d3.2204.d6e8 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC265-LEAF-9348-01  │ Vlan501, Vlan2168                                                                                   │ None                                                    │           200 │ ACTIVE - REMOTE VXLAN     │ REVIEW  │
│ DCN-DHL-CC250-LEAF-9336-01  │ Vlan500, Vlan501, Vlan502, Vlan670, Vlan671, Vlan2168                                               │ 0050.56a7.223d (), 0050.56b0.20f7 () (+8 more)          │           179 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC251-LEAF-9336-01  │ Vlan500, Vlan501, Vlan502, Vlan670, Vlan671, Vlan2168                                               │ 0050.568e.ccb8 (), 0050.56a7.9d54 () (+8 more)          │           179 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC254-LEAF-93240-01 │ Vlan500, Vlan501, Vlan502, Vlan670, Vlan671, Vlan672, Vlan2168                                      │ None                                                    │           199 │ ACTIVE - REMOTE VXLAN     │ REVIEW  │
│ DCN-DHL-CC255-LEAF-93240-01 │ Vlan500, Vlan501, Vlan502, Vlan670, Vlan671, Vlan672, Vlan2168                                      │ None                                                    │           199 │ ACTIVE - REMOTE VXLAN     │ REVIEW  │
│ DCN-DHL-CC253-LEAF-9348-01  │ Vlan501, Vlan503, Vlan2168                                                                          │ 1096.c69a.c844 (), e8d3.2249.d208 () (+3 more)          │           195 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC253-LEAF-9348-02  │ Vlan501, Vlan503, Vlan2168                                                                          │ 1096.c6ce.4950 (), 0027.e380.5ad6 () (+3 more)          │           195 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC272-LEAF-9348-01  │ Vlan500, Vlan501, Vlan503, Vlan670, Vlan671, Vlan2168                                               │ e8d3.222f.c8b0 (), 44ae.25e0.82f0 () (+6 more)          │           192 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC272-LEAF-9348-02  │ Vlan501, Vlan503, Vlan2168                                                                          │ e8d3.2249.d568 (), e8eb.3412.14d1 ()                    │           198 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCN-DHL-CC266-LEAF-93240-01 │ Vlan501, Vlan2168                                                                                   │ None                                                    │           200 │ ACTIVE - REMOTE VXLAN     │ REVIEW  │
│ DCN-DHL-CC267-LEAF-93240-01 │ None                                                                                                │ None                                                    │             0 │ STALE / RESIDUE           │ REVIEW  │
│ DCS-DHL-CC314-BGW-93240-01  │ Vlan500, Vlan501, Vlan502, Vlan503, Vlan670, Vlan671, Vlan2168, Ethernet1/51.71, Ethernet1/54.71,   │ e8eb.3412.14bf (), 40a6.b74d.6560 () (+3 more)          │           133 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│                             │ Ethernet1/7.3279                                                                                    │                                                         │               │                           │         │
│ DCS-DHL-CC323-BGW-93240-01  │ Vlan500, Vlan501, Vlan502, Vlan503, Vlan670, Vlan671, Vlan2168, Ethernet1/51.71, Ethernet1/54.71,   │ e8eb.3412.14bf (), 40a6.b74d.6560 () (+3 more)          │           133 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│                             │ Ethernet1/7.3279                                                                                    │                                                         │               │                           │         │
│ DCS-DHL-CC311-LEAF-9348-01  │ Vlan501, Vlan2168                                                                                   │ e8d3.2249.a550 ()                                       │           198 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC312-LEAF-9348-01  │ Vlan501, Vlan2168                                                                                   │ e8d3.2249.bd80 ()                                       │           198 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC315-LEAF-9348-01  │ Vlan500, Vlan501, Vlan503, Vlan670, Vlan671, Vlan2168                                               │ e8d3.2249.d0e8 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC317-LEAF-9348-01  │ Vlan501, Vlan2168                                                                                   │ 482e.72f8.c3c0 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC322-LEAF-9348-01  │ Vlan501, Vlan2168                                                                                   │ None                                                    │           200 │ ACTIVE - REMOTE VXLAN     │ REVIEW  │
│ DCS-DHL-CC324-LEAF-9348-01  │ Vlan501, Vlan503, Vlan2168                                                                          │ e8d3.2204.d6a0 (), e8d3.222f.b788 ()                    │           198 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC326-LEAF-9348-01  │ Vlan500, Vlan501, Vlan503, Vlan2168                                                                 │ e8d3.2249.d520 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC335-LEAF-9348-01  │ Vlan501, Vlan503, Vlan2168                                                                          │ e80a.b907.2a28 (), 10b3.d568.c598 (), 482e.72f8.c7b0 () │           197 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC343-LEAF-9348-01  │ Vlan501, Vlan2168                                                                                   │ e8d3.2249.9110 ()                                       │           199 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC324-LEAF-9336-01  │ Vlan500, Vlan501, Vlan502, Vlan670, Vlan671, Vlan2168                                               │ 0050.56a7.8bb0 (), 0050.56a7.dbde () (+10 more)         │           175 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC325-LEAF-9336-01  │ Vlan500, Vlan501, Vlan502, Vlan670, Vlan671, Vlan2168                                               │ 0050.56a7.19f4 (), 0050.56a7.6a5c () (+10 more)         │           175 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC336-LEAF-93240-01 │ Vlan500, Vlan501, Vlan502, Vlan670, Vlan671, Vlan672, Vlan2168                                      │ None                                                    │           199 │ ACTIVE - REMOTE VXLAN     │ REVIEW  │
│ DCS-DHL-CC337-LEAF-93240-01 │ Vlan500, Vlan501, Vlan502, Vlan670, Vlan671, Vlan672, Vlan2168                                      │ None                                                    │           199 │ ACTIVE - REMOTE VXLAN     │ REVIEW  │
│ DCS-DHL-CC345-LEAF-93240-01 │ None                                                                                                │ None                                                    │             0 │ STALE / RESIDUE           │ REVIEW  │
│ DCS-DHL-CC346-LEAF-93240-01 │ None                                                                                                │ None                                                    │             0 │ STALE / RESIDUE           │ REVIEW  │
│ DCS-DHL-CC327-LEAF-9348-01  │ Vlan501, Vlan503, Vlan2168                                                                          │ 1096.c6ce.4818 (), e8d3.2249.ccb0 () (+4 more)          │           194 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC327-LEAF-9348-02  │ Vlan501, Vlan503, Vlan671, Vlan2168                                                                 │ 1096.c6ce.48b4 (), 70df.2f1a.9af8 () (+5 more)          │           193 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC347-LEAF-9348-01  │ Vlan500, Vlan501, Vlan503, Vlan2168                                                                 │ e8d3.2249.be58 (), 44ae.25e0.8458 () (+3 more)          │           195 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
│ DCS-DHL-CC347-LEAF-9348-02  │ Vlan501, Vlan503, Vlan670, Vlan2168                                                                 │ e8d3.222f.b6b0 (), e462.c416.a894 () (+5 more)          │           193 │ ACTIVE - LOCALLY ATTACHED │ HEALTHY │
└─────────────────────────────┴─────────────────────────────────────────────────────────────────────────────────────────────────────┴─────────────────────────────────────────────────────────┴───────────────┴───────────────────────────┴─────────┘

                          Physical Attachment Details                          
┏━━━━━━━━┳━━━━━━━━━━━━━━━┳━━━━━━━┳━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
┃ Switch ┃ Physical Port ┃ Speed ┃ Transceiver ┃ CDP Neighbor ┃ Neighbor Port ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━╇━━━━━━━╇━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
└────────┴───────────────┴───────┴─────────────┴──────────────┴───────────────┘

Report saved to: reports/global_vrf.txt


physical attachment details is emptiy. 

also i want the full list nder  Local Endpoints (MAC / IP)  . map and ip learned on each port and vlan id as a sperate entry. may be make the first table as summary table. then another table with detaisl such as mac , ip , mapping to each vlan and interface. 
in that table you can map the interface description. 
then the table 3 for pyshuical attachment details
(.venv) ssamuel_admin@melnetmgmt02:~/projects/DC_MEL_Automation$ 
