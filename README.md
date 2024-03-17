### Token creation
```cmd
node ./dist/index.js createtoken --name "TOKEN_NAME" --symbol "TS" --image "TOKEN_IMAGE_LINK" --decimals 5 --website "web_link" --initial-minting 10000 --url devnet
```

### Minting 
```cmd
node ./dist/index.js minting --token "TOKEN_ADDRESS" --amount 100 --url 'devnet'
```

### Revoke Authority:
```cmd
node ./dist/index.js revokeauth --token "TOKEN_ADDRESS" --url 'devnet'
```

## Burn token
```cmd
node ./dist/index.js burn --token "TOKEN_ADDRESS" --amount 10 --url 'devnet'
```