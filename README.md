DCN-DHL-CC250-LEAF-9336-01# SHOW VPC BRIEF 
Legend:
                (*) - local vPC is down, forwarding via vPC peer-link

vPC domain id                     : 4   
Peer status                       : peer adjacency formed ok      
vPC keep-alive status             : peer is alive                 
Configuration consistency status  : success 
Per-vlan consistency status       : success                       
Type-2 consistency status         : success 
vPC role                          : primary, operational secondary
Number of vPCs configured         : 3   
Peer Gateway                      : Enabled
Dual-active excluded VLANs        : -
Graceful Consistency Check        : Enabled
Auto-recovery status              : Enabled, timer is off.(timeout = 300s)
Delay-restore status              : Timer is off.(timeout = 10s)
Delay-restore SVI status          : Timer is off.(timeout = 10s)
Delay-restore Orphan-port status  : Timer is off.(timeout = 0s)
Operational Layer3 Peer-router    : Disabled
Virtual-peerlink mode             : Disabled

vPC Peer-link status
---------------------------------------------------------------------
id    Port   Status Active vlans    
--    ----   ------ -------------------------------------------------
1     Po99   up     1,10-15,20,30,40,42,52,54,58,60-61,65-66,70,90,                      
                    99-106,109-110,126,130-131,135,140,142-143,150,                      
                    160,180,190,200,202,204,230,245,250,266,270,290,                     
                    302,310,312,320-321,324,326-327,330-336,338,350,                     
                    370,380,402,432,445-450,460,463,465-474,476-482,                     
                    486-488,500-502,510-515,518-524,526-527,550-552,     ...             

vPC status
----------------------------------------------------------------------------
Id    Port          Status Consistency Reason                Active vlans
--    ------------  ------ ----------- ------                ---------------
1     Po1           up     success     success               10-15,20,30,40,42,          
                                                             52,54,58,60-61,             
                                                             65-66,70,90,99-106          
                                                             ,109-110,126,               
                                                             130-131,135,140,            
                                                             142-143,150,...,            
2     Po2           up     success     success               10-15,20,30,40,42,          
                                                             52,54,58,60-61,             
                                                             65-66,70,90,99-106          
                                                             ,109-110,126,               
                                                             130-131,135,140,            
                                                             142-143,150,...,            
3     Po3           up     success     success               10,200,230,330,470          
                                                             ,474,486-487,514,           
                                                             522-523,526-527             

Please check "show vpc consistency-parameters vpc <vpc-num>" for the 
consistency reason of down vpc and for type-2 consistency reasons for 
any vpc.

DCN-DHL-CC250-LEAF-9336-01# 
