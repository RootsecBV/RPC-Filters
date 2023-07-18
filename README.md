# RPC Filters

RPC Filters to prevent Coercion attacks

*`MS-RPRN` is the PrinterBug
*`MS-EFSR` is PetitPotam
*`MS-FSRVP` is ShadowCoerce
*`MS-DFSNM` is DFSCoerce
*`all.txt` is MS-RPRN, MS-EFSR, MS-FSRVP and MS-DFSNM combined

To use the RPC-filters use the netsh utility like so:
```
netsh -f filter.txt
```
