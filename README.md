# Mainnet beta v1 p2p Release Guide - Libonomy Beta.1 Release
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Libonomy is one of a kind blockchain which through innovation and creativity has achieved
all the set goals with great success. The kind of innovation that attracts and reaches out to
masses of people who have knowledge and understanding that this system is fulfilling its role
of greatness.
Many only talk about the next level blockchain technology that would fix all the existing
problems all in one, Libonomy is already on a road to fulfill this ideology.

We are designing and coding an autonomous blockchain that will run on first ever AI based consensus algorithm, which will make
libonomy worlds first every autonomous, interoperable and scalable blockchain.
To learn more about Libonomy visit [https://libonomy.com](https://libonomy.com).

To learn more about the libonomy upcoming blockchain [Read this](https://libonomy.com/assets/pdf/white-paper-libonomy-v1.0.pdf).

### Benefits
The major difference is that Libonomy Blockchain resolves the issues previous consensus
algorithms that have been used for a very long time. All of these consensus algorithms have
their own drawbacks, Libonomy believes in providing an error-free consensus engine that has
been architecture very carefully. It uses Artificial Intelligence – automated, computer
generated engine that saves time, energy and gives high throughput, is scalable, interoperable and autonomous.

### Project Status
We are working hard towards our first patch - which is public mainnet beta release running libonomy AI consensus algorithm. In the upcoming
days our team will be release the full node running the consensus algithm with which users will be able to carry out the transactions on their local systems as well.

### Important
The current release interacts with staking consensus through our AI protocol so as to ensure that current community acceptance is achieved and in the later 
upgrades libonomy will depricate such systems.

### How to begin

Download the build file from linux https://github.com/libonomy/network-connection/tree/main-beta-v1
Or
Build Your Own Using Libonomy Full Node Implementation Beta.V1.Release (With Crypto Currency support) 
> IMPORTANT: Please use Chrome, Firefox or Safari to browse the guide. 

## Before Connection
Build is supported on Linux
Ensure that `$GOPATH` is set correctly and that the `$GOPATH/bin` directory appears in `$PATH`.
1. Install [Go 1.14 or later](https://golang.org/dl/) for your platform, if you haven't already.
2. Configure protocbuf
3. Download the sm_config.toml file 
4. Ensure that sm_config file exist in the same directory as build file is in
5. Open CLI and run
```bash
./libonomy-main-beta-v1-p2p --tcp-port 7152 --config ./sim_config.toml -d ./libo_data
```
As soon as you are done you will be connected to the main network.
## After Connection

1. Make sure that you have configured the wallet CLI properly and the url to live server is properly set.

2. Build the wallet using the :

```bash
make build-linux
```
3. Open console and run 

```bash
./cli_wallet_linux_amd64
```
You will get wallet commands which you can use in order to interact with the network
#### Upcoming Release
- We will be releasing the main-beta-libocoin light node build with for the community.
- Libonomy Software for macOS,Linux and windows
- Mainnet Wallet Support
- .....
