<h1 align="center">
<br/><br/>
BoskaCoin [BOSKA]
</h1>

<div align="center">

## This branch contains the latest version of the BoskaCoin codebase.

BoskaCoin is a cryptocurrency forked from LebowskisCoin, which itself is a fork of Litecoin, and ultimately Bitcoin. It aims to be a fun and accessible digital currency for everyday use.

Website: [boskacoin.org](https://boskacoin.org)

</div>

## Features
- Random block rewards to keep mining exciting (seeded from previous block hashes)
- Scrypt-based Proof-of-Work

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/boskacoin/boskacoin.git
   ```
2. Navigate to the project directory:
   ```bash
   cd boskacoin
    ```
3. Run autogen and configure:
   ```bash
   ./autogen.sh
   ./configure
   ```
4. Build the project:
   ```bash
   make
    ```
5. Run the BoskaCoin daemon:
    ```bash
    ./src/boskacoind
    ```

## Running A Node
To run a node, you need to have enough disk space and bandwidth.

You can run the BoskaCoin daemon with the following command:
```bash
./src/boskacoind -daemon
```

And to make sure the node is listening for connections, you can use `-listen` flag:
```bash
./src/boskacoind -daemon -listen=1
```

It is defaulted to 1, but you can explicitly set it just in case.

or on Windows, run `boskacoind.exe -daemon -listen=1` from the command prompt.

## More Information
For more information about BoskaCoin, please visit the [official website](https://boskacoin.org) or join the community on [Discord](https://discord.gg/zJuhFChWjF).

BoskaCoin is an open-source project, and contributions are welcome!

## Donations
If you find BoskaCoin useful and would like to support its development, please consider donating to one of the following addresses (BTC and DGB):

- Bitcoin (BTC) (preferred): 13kieE2S3mp2waCxLd6YAGqEfd7nPUoYRi (Imusing/GoombaProgrammer (lead developer))

- DigiByte (DGB): DS1sNk9ncC3K9wSNvg6N3xPWHW9sVGZERv (Imusing/GoombaProgrammer (lead developer))

If you contributed a lot of code, you can also add your own donation address here.

### BoskaCoin Donations

Or you can donate directly with BoskaCoin, but since it's a newer coin, BOSKA donations will be used to pay liquidity for exchanges to get BOSKA listed on exchanges*

- BoskaCoin (BOSKA): 66YjAwvn1yCzfP59co9mg4WE1xiSH8Mwox (Imusing/GoombaProgrammer (lead developer))

\* Most exchanges I found so far require a liquidity deposit (and a fee in USDT) to get listed.
