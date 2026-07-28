Please enter credentials:
Username: SSamuel_Admin
Password: 

--- Validation Scope ---
1. Specific Device
2. Fabric (DCN or DCS)
3. All Switches
Select an option (1-3): 3

Enter Service VRF Name: ams_vrf

--- Service Validation: VRF ams_vrf ---
Gathering Layer 3 Overlay & VRF evidence...
                          Service Validation: VRF ams_vrf (Scope: All Switches (Spines excluded))                          
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━┓
┃ Switch                      ┃ Local Ports ┃ Local Endpoints (MAC / IP) ┃ Remote Routes ┃ Classification        ┃ Health ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━┩
│ DCN-DHL-CC239-BGW-93240-01  │ None        │ None                       │           304 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC249-BGW-93240-01  │ None        │ None                       │           304 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC237-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC240-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC242-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC249-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC252-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC254-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC256-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC259-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC265-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC250-LEAF-9336-01  │ None        │ None                       │           536 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC251-LEAF-9336-01  │ None        │ None                       │           536 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC254-LEAF-93240-01 │ None        │ None                       │           562 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC255-LEAF-93240-01 │ None        │ None                       │           562 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC253-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC253-LEAF-9348-02  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC272-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC272-LEAF-9348-02  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC266-LEAF-93240-01 │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCN-DHL-CC267-LEAF-93240-01 │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC314-BGW-93240-01  │ None        │ None                       │           304 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC323-BGW-93240-01  │ None        │ None                       │           304 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC311-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC312-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC315-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC317-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC322-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC324-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC326-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC335-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC343-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC324-LEAF-9336-01  │ None        │ None                       │           545 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC325-LEAF-9336-01  │ None        │ None                       │           545 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC336-LEAF-93240-01 │ None        │ None                       │           571 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC337-LEAF-93240-01 │ None        │ None                       │           571 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC345-LEAF-93240-01 │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC346-LEAF-93240-01 │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC327-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC327-LEAF-9348-02  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC347-LEAF-9348-01  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC347-LEAF-9348-02  │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
└─────────────────────────────┴─────────────┴────────────────────────────┴───────────────┴───────────────────────┴────────┘

                          Physical Attachment Details                          
┏━━━━━━━━┳━━━━━━━━━━━━━━━┳━━━━━━━┳━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
┃ Switch ┃ Physical Port ┃ Speed ┃ Transceiver ┃ CDP Neighbor ┃ Neighbor Port ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━╇━━━━━━━╇━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
└────────┴───────────────┴───────┴─────────────┴──────────────┴───────────────┘

Report saved to: reports/ams_vrf.txt
(.venv) ssamuel_admin@melnetmgmt02:~/projects/DC_MEL_Automation$ 


remote only  DCN-DHL-CC239-BGW-93240-01  │ None        │ None                       │           304 │ ACTIVE - REMOTE VXLAN │ OK    

shows health ok. that means it bot valid. so it should say review only . 


i think you are picking the local attchments corrctly becuase this vrf global vrf has alot of local end points

                          Physical Attachment Details                          
┏━━━━━━━━┳━━━━━━━━━━━━━━━┳━━━━━━━┳━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
┃ Switch ┃ Physical Port ┃ Speed ┃ Transceiver ┃ CDP Neighbor ┃ Neighbor Port ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━╇━━━━━━━╇━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
└────────┴───────────────┴───────┴─────────────┴──────────────┴───────────────┘

Report saved to: reports/ams_vrf.txt
(.venv) ssamuel_admin@melnetmgmt02:~/projects/DC_MEL_Automation$ ^C
(.venv) ssamuel_admin@melnetmgmt02:~/projects/DC_MEL_Automation$ python service_validator.py
Please enter credentials:
Username: SSamuel_Admin
Password: 

--- Validation Scope ---
1. Specific Device
2. Fabric (DCN or DCS)
3. All Switches
Select an option (1-3): 3

Enter Service VRF Name: global_vrf

--- Service Validation: VRF global_vrf ---
Gathering Layer 3 Overlay & VRF evidence...
                        Service Validation: VRF global_vrf (Scope: All Switches (Spines excluded))                         
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━┓
┃ Switch                      ┃ Local Ports ┃ Local Endpoints (MAC / IP) ┃ Remote Routes ┃ Classification        ┃ Health ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━┩
│ DCN-DHL-CC239-BGW-93240-01  │ None        │ None                       │           131 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC249-BGW-93240-01  │ None        │ None                       │           131 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC237-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC240-LEAF-9348-01  │ None        │ None                       │           197 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC242-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC249-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC252-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC254-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC256-LEAF-9348-01  │ None        │ None                       │           196 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC259-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC265-LEAF-9348-01  │ None        │ None                       │           200 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC250-LEAF-9336-01  │ None        │ None                       │           179 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC251-LEAF-9336-01  │ None        │ None                       │           179 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC254-LEAF-93240-01 │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC255-LEAF-93240-01 │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC253-LEAF-9348-01  │ None        │ None                       │           195 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC253-LEAF-9348-02  │ None        │ None                       │           195 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC272-LEAF-9348-01  │ None        │ None                       │           192 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC272-LEAF-9348-02  │ None        │ None                       │           198 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC266-LEAF-93240-01 │ None        │ None                       │           200 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCN-DHL-CC267-LEAF-93240-01 │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC314-BGW-93240-01  │ None        │ None                       │           133 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC323-BGW-93240-01  │ None        │ None                       │           133 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC311-LEAF-9348-01  │ None        │ None                       │           198 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC312-LEAF-9348-01  │ None        │ None                       │           198 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC315-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC317-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC322-LEAF-9348-01  │ None        │ None                       │           200 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC324-LEAF-9348-01  │ None        │ None                       │           198 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC326-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC335-LEAF-9348-01  │ None        │ None                       │           197 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC343-LEAF-9348-01  │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC324-LEAF-9336-01  │ None        │ None                       │           175 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC325-LEAF-9336-01  │ None        │ None                       │           175 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC336-LEAF-93240-01 │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC337-LEAF-93240-01 │ None        │ None                       │           199 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC345-LEAF-93240-01 │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC346-LEAF-93240-01 │ None        │ None                       │             0 │ STALE / RESIDUE       │ REVIEW │
│ DCS-DHL-CC327-LEAF-9348-01  │ None        │ None                       │           194 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC327-LEAF-9348-02  │ None        │ None                       │           193 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC347-LEAF-9348-01  │ None        │ None                       │           195 │ ACTIVE - REMOTE VXLAN │ OK     │
│ DCS-DHL-CC347-LEAF-9348-02  │ None        │ None                       │           193 │ ACTIVE - REMOTE VXLAN │ OK     │
└─────────────────────────────┴─────────────┴────────────────────────────┴───────────────┴───────────────────────┴────────┘

                          Physical Attachment Details                          
┏━━━━━━━━┳━━━━━━━━━━━━━━━┳━━━━━━━┳━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
┃ Switch ┃ Physical Port ┃ Speed ┃ Transceiver ┃ CDP Neighbor ┃ Neighbor Port ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━╇━━━━━━━╇━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
└────────┴───────────────┴───────┴─────────────┴──────────────┴───────────────┘

Report saved to: reports/global_vrf.txt
(.venv) ssamuel_admin@melnetmgmt02:~/projects/DC_MEL_Automation$ 
