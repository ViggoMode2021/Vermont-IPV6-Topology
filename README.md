# Vermont-IPV6-Topology
Vermont county topology map configured with IPV6 unique local addresses.

<code><img height="700" src="https://raw.githubusercontent.com/ViggoMode2021/Vermont-IPV6-Topology/refs/heads/main/Vermont-Topology-MAP.png"></code>

* Vermont IPV6 ULA network*

FC00::/7 - Unique Local Address prefix

RID - Router ID

Bennington RID 3.3.3.3

Windham RID 2.2.2.2

Rutland RID 4.4.4.4

Windsor RID 5.5.5.5

Orange RID 6.6.6.6

Addison RID 7.7.7.7

Washington RID 8.8.8.8

Chittenden RID 35.52.154.42

Lamoille RID 73.196.37.57

Caledonia RID 111.75.130.142

Franklin RID 106.56.183.0

Orleans RID 111.16.5.2

Grand-Isle RID 10.241.140.255

Essex RID 106.11.92.224

--------------------------------------------------------------------

Bennington int f0/0 - Windham int f0/0  (FD7B:C91F:C250::/48)
FD7B:C91F:C250::1    FD7B:C91F:C250::2
                  
**************************************

Bennington int f0/1 - Rutland int f0/0  (FD00:9225:8472::/48)
FD00:9225:8472::1    FD00:9225:8472::2

**************************************

Windham int f0/1 - Windsor int f0/0     (FDB4:C399:279E::/48)
FDB4:C399:279E::1  FDB4:C399:279E::2

**************************************

Rutland int f0/0 - Windsor int f0/1     (FD1D:6E94:F5AB::/48)
FD1D:6E94:F5AB::1  FD1D:6E94:F5AB::2                             

**************************************

Windsor int f1/0 - Orange int f0/0       (FD2D:6E94:F5AB::/48)
FD2D:6E94:F5AB::1  FD2D:6E94:F5AB::2

**************************************

Addison int f0/0 - Rutland int f1/0   	 (FD3D:6E94:F5AB::/48)
FD3D:6E94:F5AB::1  FD3D:6E94:F5AB::2   

**************************************

Orange int f0/1 - Addison int f0/1   	 (FD8F:DFC9:C5C0::/48)
FD8F:DFC9:C5C0::1 FD8F:DFC9:C5C0::2  

**************************************

Orange int f1/0 - Washington int f0/0    (FD78:6581:D5E3::/48)
FD78:6581:D5E3::2 FD78:6581:D5E3::1

**************************************

Orange int f1/0 - Washington int f0/0    (FD78:6581:D5E3::/48)
FD78:6581:D5E3::2 FD78:6581:D5E3::1

**************************************

Addison int f1/0 - Washington int f0/1    (FD7B:E351:492E::/48)
FD7B:E351:492E::2  FD7B:E351:492E::1    

**************************************

Washington int f1/0 - Chittenden int f0/0 (FD34:D971:6596::/48)
FD34:D971:6596::2     FD34:D971:6596::1 

**************************************

Chittenden int f0/1 - Lamoille int f0/0   (FD34:D971:6596::/48)
FD34:D971:6596::2     FD34:D971:6596::1

**************************************

Lamoille int f0/1 - Caledonia int f0/0    (FD23:F840:96E2::/48)
FD23:F840:96E2::2   FD23:F840:96E2::1

**************************************

Caledonia int f0/1 - Washington int f2/0 (FD3F:B486:461C::/48)
FD3F:B486:461C::1   FD3F:B486:461C::2

**************************************

Franklin int f0/0 - Lamoille int f1/0 (FD1F:2385:EBC5::/48)
FD1F:2385:EBC5::1   FD1F:2385:EBC5::2

**************************************

Orleans int f0/0 - Lamoille int f2/0 (FDBA:4899:9958::/48)
FDBA:4899:9958::1  FDBA:4899:9958::2

**************************************

Grand-Isle int f0/0 - Franklin int f1/0 (FD95:1630:6E82::/48)
FD95:1630:6E82::1 FD95:1630:6E82::2

**************************************

Franklin int f1/0 - Orleans int f0/1 (FDFD:408B:FD0D::/48)
FDFD:408B:FD0D::1 FDFD:408B:FD0D::2

**************************************

Essex int f0/0 - Orleans int f1/0 (FD7B:4711:F0A3::/48)
FD7B:4711:F0A3::1 FD7B:4711:F0A3::2
                  
**************************************

Bennington int f0/1 - Rutland int f0/0  (FD00:9225:8472::/48)
FD00:9225:8472::1    FD00:9225:8472::2

**************************************

Windham int f0/1 - Windsor int f0/0     (FDB4:C399:279E::/48)
FDB4:C399:279E::1  FDB4:C399:279E::2

**************************************

Rutland int f0/0 - Windsor int f0/1     (FD1D:6E94:F5AB::/48)
FD1D:6E94:F5AB::1  FD1D:6E94:F5AB::2                             

**************************************

Windsor int f1/0 - Orange int f0/0       (FD2D:6E94:F5AB::/48)
FD2D:6E94:F5AB::1  FD2D:6E94:F5AB::2

**************************************

Addison int f0/0 - Rutland int f1/0   	 (FD3D:6E94:F5AB::/48)
FD3D:6E94:F5AB::1  FD3D:6E94:F5AB::2   

**************************************

Orange int f0/1 - Addison int f0/1   	 (FD8F:DFC9:C5C0::/48  )
FD8F:DFC9:C5C0::1  FD8F:DFC9:C5C0::   

**************************************
