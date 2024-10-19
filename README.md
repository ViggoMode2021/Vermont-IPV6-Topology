# Vermont-IPV6-Topology
Vermont county topology map configured with IPV6 unique local addresses.

<code><img height="700" src=""></code>

* Vermont IPV6 *

FC00::/7

Bennington RID 3.3.3.3

Windham RID 2.2.2.2

Rutland RID 4.4.4.4

Windsor RID 5.5.5.5

Orange RID 6.6.6.6

Addison RID 7.7.7.7

Washington RID 8.8.8.8

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

Orange int f0/1 - Addison int f0/1   	 (FD8F:DFC9:C5C0::/48  )
FD8F:DFC9:C5C0::1  FD8F:DFC9:C5C0::   

**************************************
