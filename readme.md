# Usage

**Install Foundry**
```
curl -L https://foundry.paradigm.xyz | bash
source ~/.bashrc 
foundryup
```

**Initializing a new Project**
```
forge init .
```

**Building and Testing**
```
forge build
```

**Install openzeppelin dependency**
```
forge install openzeppelin/openzeppelin-contracts
```

**Run test**
```
forge test -vv
```

**Running a Foundry Script**
source .env
forge script script/Deploy.sol:SpacebearScript --broadcast --verify --rpc-url ${GOERLI_RPC_URL}
```