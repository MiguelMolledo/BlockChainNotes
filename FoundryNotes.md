# Foundry

## Building

to check what information is being cached in Storage 
```shell
forge inspect ContractName storageLayout
```
  Execute a script with --rpc-url and with private key

```shell
  	forge script script/DeployFundMe.s.sol --rpc-url http://127.0.0.1:8545 --private-key 0x0
```
Using Cast
```shell
	cast storage [ContractDddress] [storageSlotNumber]
```


## Testing
Run tests
```shell
	forge test
	forge test --match-test testMethodName
	forge test --fork-url
	forge coverage ( to see how much of our code is covered by testing) 
```
## Anvil



## Chisel
Like script editor to test solidity code in real time


``` shell
> chisel
(chisel) > !help 
```
