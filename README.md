# RPC Filters

RPC Filters to prevent Coercion attacks

- **ms-rprn.txt**: PrinterBug
- **ms-efsr.txt**: PetitPotam
- **ms-fsrvp.txt**: ShadowCoerce
- **ms-dfsnm.txt**: DFSCoerce
- **all.txt**: MS-RPRN, MS-EFSR, MS-FSRVP, and MS-DFSNM combined

To use the RPC-filters use the netsh utility like so:
```
netsh -f filter.txt
```
