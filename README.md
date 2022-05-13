# nminer

NOVO gpu miner

## Features

- M1 Macintosh, AMD and Nvidia gpus
- M1 Macintosh, Intel Macintosh, Linux and Windows binaries
- 21.8% fee

## Usage

```
USAGE:
    nminer [OPTIONS]

OPTIONS:
    -a, --coinbase-address <ADDRESS>
            payout address for solo mined blocks [default: 1cozyb2MgHZF71uHrnzDq53VrZeCRX5Yg]

    -D, --device-selector <DEVICE NUMBERS>


    -h, --rpchost <HOST>
            Connect to JSON-RPC on <HOST>

    -H, --print-hashrate


        --help
            Print help information

    -m, --coinbase-message <MESSAGE>
            coinbase message for solo mined blocks [default: gm]

    -o, --output-file <OUTPUT_FILE>
            [default: ./stats.json]

    -p, --rpcport <PORT>
            Connect to JSON-RPC on <PORT> [default: 8665]

    -P, --rpcpassword <PASSWORD>
            Password for JSON-RPC connections

    -S, --show-devices


    -u, --rpcuser <USER>
            Username for JSON-RPC connections

    -V, --version
            Print version information
```

## Coming Soon

- Stratum compatibilty
- Nvidia turbo mode
