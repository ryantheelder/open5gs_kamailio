# Open5gs_Config
Open5gs Configuration files for IMS/VoLTE

## Testbed Setup
<pre>
  +-----------+
  |           |
  |  Open5gs  |
  |   (ens3)  |
  +-----------+
</pre>

- OpenStack VM with root user and single interface (ens3)

## Modifications required for respective setups

- Modify all module locations based on your installation.

e.g:
load_extension:
        - module: /root/open5gs/install/lib/x86_64-linux-gnu/freeDiameter/dbg_msg_dumps.fdx
.....

- APN names
- UE pool IP addresses
- P-CSCF address
- Network interface name

