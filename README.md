# mame4all (MiyooCFW)

Port of MAME 0.37b5 for the MiyooCFW (with ODx frontend)

### Native build (linux):

- compile binary
```
make DEBUG=1 distrib
```

- launch from CWD directory
```
cd distrib/mame4all
./mame4all
```

### Cross-Compile build (MiyooCFW):

- compile binary (e.g. via docker):
```
make
```

- or generate IPK package:
```
make ipk
```

### Credits

- Steward-fu (initial Miyoo port)
- miwasp (extra QOLI changes)

Code based on mame4all for GCW0 by Alekmaul & RS-97 port by bob_fossil.