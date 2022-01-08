![CCSLOGO](https://raw.githubusercontent.com/CloutContracts/cloutcontracts.github.io/main/assets/images/c-128x128.png)

Insert about section here

*This includes the code of Agoric's Fungible Faucet DAPP. This needs massive updating.*

Install the [prerequisites](https://agoric.com/documentation/getting-started/before-using-agoric.html). Then in a first terminal in the directory where you want to put your dapp, install the dapp:
```sh
# Start the Agoric platform
agoric install && agoric start --reset
```

In a second terminal, deploy this contract and the API server
```sh
agoric deploy contract/deploy.js
agoric deploy api/deploy.js
```

In a third terminal, 
```sh
# Navigate to the `ui` directory and start a local server
cd ui && yarn start
```
Then navigate to http://127.0.0.1:3000.

## Using the Dapp

1. Navigate to http://127.0.0.1:3000.
2. Enter `agoric open` in your terminal
3. A window for your wallet should open.
4. Under "Dapps" in the wallet, enable the Dapp:

To learn more about how to build Agoric Dapps, please see the [Dapp Guide](https://agoric.com/documentation/dapps/).

See the [Dapp Deployment Guide](https://github.com/Agoric/agoric-sdk/wiki/Dapp-Deployment-Guide) for how to deploy this Dapp on a public website.
