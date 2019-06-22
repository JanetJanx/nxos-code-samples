# nxos-code-samples
## These are added Code Script samples to the existing CiscoDevNet/nxos-code repository. https://github.com/CiscoDevNet/nxos-code for Open NX-OS Learning Labs.

### The added script get_bgp_mode.py, feteches the bgp router mode using the XML String as a NETFCONF Filter defined according to nxos_bgp.txt file that contains the yang model description. 

```yang/02-yang/get_bgp_mode.py```

```
(nxos) nxos-code/yang/02-yang$ python get_bgp_mode.py 
The BGP router mode for sbx-nxos-mgmt.cisco.com is fabric

```
