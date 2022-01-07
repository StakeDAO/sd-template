## Stakedao template

This repository gives a basic template in order to develop a stakedao strategy

## Tasks

1. Building a strategy which offers fixed APY </br> </br>
![photo_2022-01-07 16 25 00](https://user-images.githubusercontent.com/22425782/148534153-050e49f6-5696-4653-9ab8-6c9ea1d75d7f.jpeg) </br> </br>
2. Review the contracts + tests of phase 1 of the new architecture which is meant to be deployed shortly, to find exploits and vulnerabilities. The code is [here](https://github.com/StakeDAO/sd-frax-veSDT) </br> </br>
3. Finish implementation of strategies section on top of frax finance, in the new achitecture. Basic version of contracts have been implemented [here](https://github.com/StakeDAO/contracts-v2/tree/master/contracts/strategies). Task is to adjust these to updated contract of frax gauge and write tests to ensure correctness. </br> </br>
![Screenshot 2022-01-07 at 4 33 33 PM](https://user-images.githubusercontent.com/22425782/148534914-508515ed-60eb-4bf5-9913-00c9004a18eb.png) </br> </br>
4. Cross-chain deposit support for existing strategies. For example, as a user on polygon, I want to deposit my assets in polygon and wanna particiate in a strategy that is deployed on avalanche. A common bridging layer is supposed to be implemented focused on asset transfers between Ethereum <> Polygon <> Avalanche

## Env variables

```
ALCHEMY_MAINNET=
ETHERSCAN_KEY=
DEPLOYER_PRIVATE_KEY=
```
