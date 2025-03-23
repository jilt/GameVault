# GameVault
Repository for the aleph hackathon's Game Vault generator project

## This project is a simple graphic generator for videogames that runs on an [open source UI](https://www.comfy.org/) on low ram environments generating all graphic assets with the right naming to be included in the JS game.
[Graphics generation configuration](https://github.com/jilt/GameVault/blob/main/Graph-generator.json)

The JS files interact with ethers6 cdn to connect with a simple Vault 4676 contract on ZKsync, allowing LP tokens owner to access shares of a vault.

1) to start the game you need to have an amount of token0 on your connected wallet.
2) based on the timing of your play you get an amount of token1 when you finish the game
3) at the end of the game you are asked to put all your tokens in the Liquid Pool in order to mint shared of the GameVault contract tokens.
4) With these shares you can access *GameJoinLike* possible external lending strategies, Liquid pools fees and the Vault's *pot* yield strategy.

   [Working generator app](https://drive.google.com/file/d/1L75W9rvduy3-wXnP62Nncd3jLobutjwK/view?usp=sharing)
   
   [Demo video](https://drive.google.com/file/d/1CeDLd0Ag3nnjEpxKEV_IlkmIEXeDpVmY/view?usp=sharing)

## how to play
move the robot with a w and d keys, enter doors and jump with w
