# Info

## Mining

### Etherium Wallets
* Coinbase: `0x308a7114c237c81A485780D9A25adae0DD779bF3`

### T-Rex Miner
ETH-ethermine.bat
```
t-rex.exe -a ethash -o stratum+tcp://us2.ethermine.org:4444 -u 0x308a7114c237c81A485780D9A25adae0DD779bF3 -p x -w bPc
pause
```

### Team Red Miner
start-eth.bat
```
teamredminer.exe -a ethash -o stratum+tcp://us2.ethermine.org:4444 -u 0x308a7114c237c81A485780D9A25adae0DD779bF3.bFullNode -p x --enable_compute
```