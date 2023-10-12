# basic-1

Just a basic Solana application that is powered by the Anchor Framework.

# To run the project
Create a new key-gen (optional)
```
solana-keygen new
```
Install dependencies
```
yarn install
```
Build
```
anchor build
```
Get the address of your program and paste it to the ```declare_id!()``` macro and ```Anchor.toml```
```
solana address -k target/deploy/basic_1-keypair.json
```
Build again and deploy with the new id
```
anchor build
anchor deploy
```
