# gominer
GPU miner for siacoin in go

All available opencl capable GPU's are detected and used in parallel.


## Installation from source

### Prerequisites
* go version 1.4.2 or above (earlier version might work or not), check with `go version`
* opencl libraries on the library path
* gcc

```
go get github.com/robvanmieghem/gominer
```

## Run
```
gominer
```

Usage:
```
  -H string
    	siad host and port (default "localhost:9980")
  -I int
    	Intensity (default 28)
  -cpu
    	If set, also use the CPU for mining, only GPU's are used by default
  -v	Show version and exit
```

See what intensity gives you the best hashrate.

## FAQ

- ** You have to help me set up mining SIA **

  No I don't

- ** Can you log in on my machine to configure my mining setup? **

  No

- ** ERROR fetching work - Get http://localhost:9980/miner/headerforwork: dial tcp 127.0.0.1:9980: connection refused **

  Make sure `siad` is running

- ** Is there a windows executable download? **

  No: https://github.com/robvanmieghem/gominer/issues/5

## Support development

If you really want to, you can support the gominer development:

SIA: 79b9089439218734192db7016f07dc5a0e2a95e873992dd782a1e1306b2c44e116e1d8ded910

BTC: 3QrmVRLU2JZKHiLdATud2vvL9b376wbmKU
