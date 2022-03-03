# Deployment

## Compile
```
npm install
npm audit fix
truffle compile
npm run generate-types
```

## Test
```
npm run test
npm run coverage
```

## Deploy contracts
```
npm run migrate -- --network rinkeby
```
using hardhat
```
npx hardhat run scripts/deploy-mockerc20.ts --network rinkeby
```

## Verify
```
truffle run verify MockErc20 --network rinkeby
```
