# Valory's ETH-Lisbon-23 Hack

## What shorts.wtf is
Shorts.wtf enables anyone to create an entire AI-generated short film (with narration, audio and video) as an NFT, from a single prompt. 

We’ve all enjoyed image generation, now have fully-fledged audiovisual fun in an easy-to-use, cryptonative way.

## Why it’s so cool
Built using Olas autonomous agent-based technology, shorts.wtf enables humans to create more with less labor. Here, it seamlessly pays to use multiple AI models using XDAI and mints the output as an NFT. 

This could be used for any complex AI outcomes in crypto, but here the models are used to create a short film.

shorts.wtf utilizes Olas AI Mechs for the autonomous agent-based AI work, XDAI for payment, Safe as a smart account, WalletConnect for log-in and notifications and runs on three different EVM blockchains Polygon zkEVM, Neon EVM and Gnosis Chain for quick, speedy EVM-compatible transactions. 

## How it works

### Actions I take 
Instead of a human having to prompt 4 different AI models, the shorts.wtf autonomous service combines the output and creates an NFT manually.

Here, anyone with some XDAI can: 
* Log into the site via WalletConnect, choosing from Gnosis Chain, Polygon zkEVM or Neon blockchains.
* Enter one short prompt on the site, then sign the triggered message to simultaneously approve a) the funds triggering the autonomous agent to create the video and b) the ultimate NFT minting in one step.
* Wait for a notification from WalletConnect’s Web3Inbox that your short film has been created, then you’ll find the NFT added to the frontend. 

### Actions the autonomous agent-based service takes
Between steps 2 and 3, all the interim actions are taken by the autonomous service, represented on-chain by a Safe. These actions include: 

* The autonomous service feeds the user’s single prompt to ChatGPT, generating a detailed input for the narration, soundtrack, and video based on the user’s topic. 
* It then uses a new Olas Mech tool to create the narration using Afiaka87’s Tortoise-TTS model on Replicate. 
* Once the narration is created, the autonomous service identifies the narration length. 
* It simultaneously feeds the inputs for the soundtrack and video to Meta’s musicgen and X’s Y respectively, requesting the same length as the narration. 
* It combines the video clip, narration, and soundtrack into one video.
* It then creates a still from the video, hosts the video and image on IPFS and creates an NFT with both linked in the metadata. All the NFTs are displayed on the home page. 
* Once the NFT Short is complete, Web3Inbox sends the Imaginooorr an email to notify them that their Short is ready. 

## Repos and other links

### Frontend:
https://shorts.wtf 

### Repos:
* https://github.com/valory-xyz/generatooorr  - agent
* https://github.com/valory-xyz/mech-eth-lisbon-2023  - contracts
* https://github.com/valory-xyz/mech-offchain-eth-lisbon-2023 - mech
* https://github.com/valory-xyz/shorts-frontend - frontend
  
### Documentation:
This readme
### Tweet, including @GnosisChain:
https://x.com/valoryag/status/1721110013182439428?s=20

## Learn more
* Autonomous agents in crypto - https://olas.network and https://docs.autonolas.network
* Valory - https://valory.xyz/press-kit 
