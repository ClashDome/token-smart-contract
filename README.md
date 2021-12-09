# clashdometkn
ClashDome tokens: LUDIO, CDCARBZ and CDJIGO

# Build

```cd <smart_contract_directory>
git clone
go to directory
md build
cd build
cmake ..
make
```

# Update contract

While testing in testnet:
cleos -u https://testnet.waxsweden.org set contract clashdometkn ./eosio.token -p clashdometkn@active

In production:
cleos -u https://api.waxsweden.org set contract clashdometkn ./clashdometkn -p clashdometkn@active

## License

[MIT](./LICENSE)
