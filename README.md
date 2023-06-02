# detaChain

Layer 2 blockchain based on Substrate

### Website

https://detachain.org

### Testnet Explorer

http://scan.boka.network/#/Galois

### Build from Sourcecode

1、The first thing you will need to do is prepare the computer for Rust development. This is same as substrate installation. Here is the document: https://substrate.dev/docs/en/knowledgebase/getting-started/

2、Clone detaChain from Github:

``` git clone https://github.com/detawallet/detaChain.git ```

3、Enter the directory:

``` cd detaChain ```

4、Init the submodule:

``` git submodule update --init --recursive ```

5、Now you can build the detaChain from source code:

``` cargo build --release ```
