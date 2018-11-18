# Claymore-s-Dual-Ethereum-AMD-NVIDIA-GPU-Miner-v11.9.2

Currently probably one of the best miners for Ethash algo today. It provides stability and high performance to get maximum from modern GPUs (GPU and NVIDIA).

claymore dual miner 11.9.2 nvidia cuda amd opencl ethereum miner latest

FEATURES:
?? Supports new "dual mining" mode: mining both Ethereum and Decred/Siacoin/Lbry/Pascal at the same time, with no impact on Ethereum mining speed. Ethereum-only mining mode is supported as well
?? Effective Ethereum mining speed is higher by 3-5% because of a completely different miner code - much less invalid and outdated shares, higher GPU load, optimized OpenCL code, optimized assembler kernels
?? Supports both AMD and nVidia cards, even mixed
?? No DAG files
?? Supports all Stratum versions for Ethereum: can be used directly without any proxies with all pools that support eth-proxy, qtminer or miner-proxy
?? Supports Ethereum and Siacoin solo mining
?? Supports both HTTP and Stratum for Decred
?? Supports both HTTP and Stratum for Siacoin. Note: not all Stratum versions are supported currently for Siacoin
?? Supports Stratum for Lbry and Pascal
?? Supports failover
?? Displays detailed mining information and hashrate for every card
?? Supports remote monitoring and management
?? Supports GPU selection, built-in GPU overclocking features and temperature management
?? Supports Ethereum forks (Expanse, etc)
?? Windows and Linux versions

This miner is compatible with POOL/SOLO modes for the next coins:

✔︎ Ethereum

✔︎ Siacoin

For POOL only mode the next coins are compatible:

✔︎ Decred

✔︎ Lbry

✔︎ Pascal

Please note for multi-GPU systems, it's crucial to set Virtual Memory size in Windows at least 16 GB+:
"Computer properties / Advanced System Settings / Performance / Advanced / Virtual Memory".

This miner is free-to-use, however, current developer fee is 1% for Ethereum-only mining mode (-mode 1) and 2% for dual mining mode (-mode 0).Decred/Siacoin/Lbry/Pascal is mined without developer fee.
If the user doesn't agree with the dev fee, it's possible to disable it using "-nofee" option, however the miner will slowdown the performance enabling this option.

Requirements :

AMD cards: 7000 series, 200 series, 300 series and RX series with 2GB+ VRAM

NVIDIA cards: Maxwell and Pascal based cards with at least 2GB+ VRAM
Windows and Linux 64bit editions are supported only.

 

The latest release (v11.9.2) includes the following fixes, optimizations and features:

✔︎ Fixed issue with incorrect shares for Keccak

✔︎ New algo: bcd

✔︎ Speed improvements: x16r/s, bitcore, renesis, hmq1725 - 2-3%

✔︎ Add ability to change averaging hashrate window, enable protocol dump mode, and change GPU report interval via API or web browser on the fly (without stopping the miner) - see the help file

✔︎ Showing configured pools upon start up

✔︎ Displaying colour representation of hashorders for x16r/s

✔︎ Miner uptime is displayed as part of GPU stats report
