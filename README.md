<h1 align="center">
<br/><br/>
BoskaCoin [BOSKA]
</h1>

<div align="center">

## This branch contains the latest version of the BoskaCoin codebase.

BoskaCoin is a cryptocurrency forked from LebowskisCoin, which itself is a fork of Litecoin, and ultimately Bitcoin. It aims to be a fun and accessible digital currency for everyday use.

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
    ./src/lebowskiscoind # needs to be changed to boskacoind later
    ```
