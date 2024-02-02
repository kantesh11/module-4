# LoyaltyPointsToken

## Overview

`LoyaltyPointsToken` is an ERC-20 token on the Ethereum blockchain designed to manage and utilize loyalty points. This contract empowers users to earn, redeem, transfer, and burn loyalty points, offering flexibility in reward mechanisms. Ownership is initially assigned, enabling the owner to mint points, add or remove rewards, and oversee the contract's operations.

## Key Features

- **Minting Points:** The contract owner can create new loyalty points and allocate them to specific addresses.
- **Redeeming Rewards:** Users can exchange their points for a variety of rewards, such as discounts, free items, or exclusive access.
- **Burning Points:** Users have the ability to reduce their total point balance by burning points.
- **Transferring Points:** Points can be transferred from one address to another.
- **Managing Rewards:** The contract owner can dynamically add or remove rewards along with their respective point costs.

## Reward Points Costs

- **Discount5%:** 50 points
- **FreeItem:** 100 points
- **ExclusiveAccess:** 200 points

##  Functions used

### `mintPoints(address to, uint256 points)`

Create and assign a specified number of loyalty points to a designated address.

### `redeemRewardPoints(string rewardName, uint256 points)`

Exchange a defined quantity of points for a specific reward, deducting the corresponding point cost.

### `burnPoints(uint256 points)`

Decrease the user's total point balance by burning a specified number of points.

### `transferPoints(address to, uint256 points)`

Transfer a designated number of points from one address to another.

### `addReward(string rewardName, uint256 cost)`

Exclusively for the owner, add a new reward to the system along with its associated point cost.

### `removeReward(string rewardName)`

Exclusively for the owner, remove an existing reward from the system.

## Usage 

1. Deploy the `LoyaltyPointsToken` contract on the Ethereum blockchain.
2. Initiate loyalty points minting using the `mintPoints` function.
3. Users can explore the options to redeem, burn, and transfer their points.
4. The owner has the capability to manage rewards dynamically by adding or removing them.

## License Details

This project adheres to the MIT License. The specifics are available in the [LICENSE](./LICENSE) file.

## Auhtor details 

Kantesh

kanteshmh11@gmail.com
