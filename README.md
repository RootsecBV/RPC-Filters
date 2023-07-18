# RPC Filters

RPC Filters to prevent Coercion attacks

- **MS-RPRN**: PrinterBug
- **MS-EFSR**: PetitPotam
- **MS-FSRVP**: ShadowCoerce
- **MS-DFSNM**: DFSCoerce
- **all.txt**: MS-RPRN, MS-EFSR, MS-FSRVP, and MS-DFSNM combined

To use the RPC-filters use the netsh utility like so:
```
netsh -f filter.txt
```
