# OpenStack Cinder Driver and Manila Driver For Huawei Storage
## Overview
Huawei Cinder driver is used to adapt OpenStack and SAN storage which in order to 
provide LUNs to VMs. In addition, cinder driver also provides a series of LUN-related services, 
such as snapshots, retype, manage-existing, replication, hypermetro and QoS. 
Otherwise, the Manila driver is used to adapt OpenStack and NAS storage which mount the 
filesystem directly to the VMs. Also, manila driver support snapshot, replication, hypermetro, 
QoS and so on.

## Compatibility Matrix
The strategies of Huawei Cinder Driver and Manila Driver are consistent with the OpenStack community, we support the latest 6 versions. For other versions, it can be used but no longer maintained. More details [release doc](https://github.com/Huawei/OpenStack_Driver/blob/master/RELEASE.md)
