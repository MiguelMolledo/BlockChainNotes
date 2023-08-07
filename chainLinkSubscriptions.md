

# Chain Link Subscriptions
You can subscribe to a smart contract, that allows you to execute X methods without having to spend money in that transaction. So the subscription pulls money from an admin account which holds a limited 
Link Tokens. This allows to have  a budget for this  usage. 

##  About
You can find interesting information in these links

1. subscription Manager: https://vrf.chain.link/
2. Documentation: https://docs.chain.link/vrf/v2/introduction
3. SmartContract : https://github.com/smartcontractkit/chainlink/blob/develop/contracts/src/v0.8/vrf/VRFConsumerBaseV2.sol
4. Remix Link: https://remix.ethereum.org/#url=https://docs.chain.link/samples/VRF/VRFv2Consumer.sol

## General Steps

1. I want  a real random number, what do I need?
2. Go to chainlink documentation and open a subscribed account with an admin address
3. Ineherets from  `contract VRFv2Consumer is VRFConsumerBaseV2, ConfirmedOwner { `
4. override `fulfillRandomWords`
5. Deploy your contract
6. Go to Subscription Manager and add a consumer
   1. This consume will use admin allowed Link tokens

![image](https://github.com/MiguelMolledo/BlockChainNotes/assets/24359861/4a0110ef-8bfc-41a9-a125-d7a0a28ef7ae)
