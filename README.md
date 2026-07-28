(.venv) ssamuel_admin@melnetmgmt02:~/projects/DC_MEL_Automation$ python service_validator.py
Loaded hardcoded credentials from creds.yaml

--- Validation Scope ---
1. Specific Device
2. Fabric (DCN or DCS)
3. All Switches
Select an option (1-3): 3

Enter Service VRF Name: global_vrf

--- Service Validation: VRF global_vrf ---
Gathering Layer 3 Overlay & VRF evidence...
Traceback (most recent call last):
  File "/home/ssamuel_admin/projects/DC_MEL_Automation/service_validator.py", line 457, in <module>
    main()
  File "/home/ssamuel_admin/projects/DC_MEL_Automation/service_validator.py", line 319, in main
    table = Table(title=f"Service Validation Summary: VRF {service} (Scope: {scope_name})", show_lines=True)
NameError: name 'scope_name' is not defined
