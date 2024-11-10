# AptoSnap

### Features of App
- Support for multiple accounts
- Integrated all Aptos API features over all three networks: testnet, devnet, mainnet
- Uses custom UI dialog boxes
- Cron jobs for regularly notifying the user about the balance and status of last 5 transactions.

### Getting Started
#### Snap
- Run the below commands to start the snap
  ```shell
  cd packages/snap
  yarn install
  npx mm-snap build
  npx mm-snap serve
  ```

#### Frontend
- Clone the repository
- Run the below commands to start the app
```shell
  cd packages/site
  yarn start
```



#### **Note:** 
Make sure snapID(in _packages/site/src/components/Header.tsx_) is same as port on which the server is running (i.e if is snap is running at localhost port 8080 then snapID is _local:http://localhost:8080_)
Also install Metamask Flask
