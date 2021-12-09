# clashdometkn
ClashDome tokens: LUDIO, CDCARBZ and CDJIGO

LUDIO           Max Supply	10,000,000,000.0000 LUDIO
CDCARBZ         Max Supply	500,000,000.0000 CDCARBZ
CDJIGO          Max Supply	750,000,000.0000 CDJIGO

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
cleos -u https://api.waxsweden.org set contract clashdometkn ./eosio.token -p clashdometkn@active

## License

[MIT](./LICENSE)
