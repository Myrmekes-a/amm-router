# Introduction
Amm router for EVM dexs forking Conveyor Aggregator

Designed to be integrated with UniswapV2, UniswapV3 and Sushi, Pancake and ShibaSwap.

## Features
- Synchronize Dex states and activities by capturing blocks with indexer.
- Simulate various swap functions for each DEXs.
- Find path for route cross multiple DEXs.
- Generate swap call data to build aggregated swap multicalls.

## Progresses
- Integrated with uniswapV2, uniswapV3 and sushiswap.
- Simulate swap functions and generate call data for multicalls.
- Routing with simple paths 1 & 2 depth.
- As the purpose of forking Conveyor API, tested generated call data with conveyor API result.
- Changed the routing and multicall contract as oneself deployed.
- Changed the addresses for fee and callback data.

