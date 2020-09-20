## Prerequisites
- truffle@latest

## Installation
```
npm install
```

## Config
Create your own config file
```
cp config/default.json config/local.json
```

Update `local.json` file to custom the params.

## Deployment
```
truffle deploy --network tao --reset
```
Note: Make sure you have enough TAO for TX contract creation fee.
