# RPC Filters

RPC Filters to prevent Coercion attacks

- **ms-rprn.txt**: PrinterBug (PrintSpooler service)
- **ms-efsr.txt**: PetitPotam (Encrypting File System Remote Protocol)
- **ms-fsrvp.txt**: ShadowCoerce (File Server VSS Agent Service)
- **ms-dfsnm.txt**: DFSCoerce (Distributed File System Namespace Management protocol)
- **all.txt**: MS-RPRN, MS-EFSR, MS-FSRVP, and MS-DFSNM combined

To use the RPC-filters use the netsh utility like so:
```
netsh -f filter.txt
```
