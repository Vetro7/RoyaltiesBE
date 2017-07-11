# Royalties-Blockchain-Explorer
Block explorer for Royalties CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon royaltiesd. It should be accessible from the Internet. Run royaltiesd with open port as follows:
```bash
./royaltiesd --rpc-bind-ip=0.0.0.0 --rpc-bind-port=24888
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon. You will also need to go through the API pages and update the links to point to your daemon IP as well. The API pages are located in the "q/" directory, the index.php file must point to your daemon IP. You must change all 4 of them "hashrate" "reward" "supply" "height"
