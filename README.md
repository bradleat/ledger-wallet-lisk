# Lisk Wallet Ledger
Lisk wallet application for Ledger  Nano S

***Under development***

## Setting Up The Development Environment
- Install ledger vagrant https://github.com/bradleat/ledger-vagrant
- Clone this repo under `apps/`
- Connect your ledger Nano S

## Developing the Lisk Ledger App

- Connect to the vagrant machine `vagrant ssh`
- `cd apps/ledger-wallet-lisk/@packages/blue-app-lisk`
- Build the ledger wallet code `make`
- Deploy the ledger wallet code `make load`
- Undeploy the ledger wallet code `make delete`


## Developing the Python Lisk Ledger SDK

## Developing the Node Lisk Ledger SDK

## TODO
- [ ] Make derivation path working
- [ ] Make derivation path working
- [ ] Generate correct address
- [ ] Parse serialized transactions
  - [ ] Simple Transaction
  - [ ] Delegate Votes
- [ ] Sign transaction
- [ ] Make network agnostic

## Thanks to:
https://github.com/fix/ledger-vagrant
https://github.com/fix/ark-ledger