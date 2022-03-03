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
Open `.env.example` file and follow instructions.

After that:
```
npm run migrate -- --network rinkeby
```
Or using hardhat
```
npx hardhat run scripts/deploy-mockerc20.ts --network rinkeby
```

## Verify
```
truffle run verify MockErc20 --network rinkeby
```
