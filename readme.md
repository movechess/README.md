# MoveChess - Play your brilliant Moves

**The Envision and Mission**

Enter MoveChess, MoveLabs flagship project, designed to pioneer a new era in blockchain gaming. By seamlessly integrating the growing market of online chess, with optimized smart contract design; MoveChess is poised to revolutionize online Monetized Chess Matches (MCM’s). We are committed to not only harnessing the potential of blockchain but also making it accessible and user-friendly. With MoveChess, we aim to provide a secure, transparent, and enjoyable experience that truly revolutionizes online gaming while simultaneously building trust in the blockchain industry.

**What problem does it solve?**

We are developing the MoveChess product to provide products for the ecosystem and community. The most important thing is the community about creating a playground for users and the ecosystem. We want to create a Chess-loving community for degens users (almost all DeFi user activities are very limited in terms of physicality). About the product, we will create a physical project about the mind for users. At the same time, everything in the product will operate on-chain and contribute transaction hashes to the operation of the Aleph Zero blockchain by using the native token (AZERO) to develop the product.

**KEY IDEAS**

**CONTRIBUTION TO THE BLOCKCHAIN**

Based on the image above, we will implement on-chain activities of MoveChess. This will help the activities contribute transactions and increase the activity of the Aleph Zero blockchain through on-chain activities. The following are typical activities:
1. POAPs
2. On-chain NFTs Achievement
3. Prediction
4. Match Bettings
5. Merchandise/Game Store
6. Daily On-chain Reward

<img width="817" alt="Screenshot 2023-10-29 at 10 04 19" src="https://github.com/movechess/README.md/assets/143335690/145ab766-3ceb-4690-be05-1b1c2e694671">

**Technology and Architecture**			
1. On-chain NFT Achivement
2. 02 DAILY QUIZZES
3. MCMs
4. TOURNAMENTS
5. SKIN STORE
6. ARBITERS

**SMART CONTRACT DESIGN**
<img width="950" alt="Screenshot 2023-10-29 at 10 05 38" src="https://github.com/movechess/README.md/assets/143335690/01031119-ac95-4a68-b015-432a85385d43">

**01-03 MATCHMAKING**

MoveChess is a blockchain-based chess game that uses a peer-to-peer gaming system called MCM. To start a game, users select a staking pool and their Elo score is retrieved from the blockchain. Players are then paired with an opponent and have a brief pre-game window to initiate a skip, which is limited to a few free skips per day. Beyond this threshold, players can employ a paid NFT-based skip.

**04-05 GAME START**

Once the game starts, the off-chain game engine logs every move on the chain. The goal is to do this with a single signature to avoid flooding the chain with signatures. The actual gameplay happens off-chain in the game engine, and the moves are then sent to the smart contract. The smart contract has the funds from the user vault contract and holds them for the duration of the game.

**06 Smart Contract Determines Winner**

When the game ends, the in-game logic declares a winner or results in a draw. In the event of a draw, players can choose to rematch. If not, the staked funds are returned to each player, minus fees. The anti-cheat system sends data to the game contract to determine a winner. If cheating is detected, the staked funds are returned only to the innocent player, and the cheater faces a penalty.			

**07 FUNDS & DATA TRANSFERED**

When the game is over, the winner gets their staked funds back, minus some fees. The MoveChess platform and the arbiters also get a cut of the fees. The game data is sent to the players' accounts, which updates their Elo scores.

**Deploy Instruction**

README: https://github.com/movechess/movechesscontract/blob/main/README.md
MoveChess Smart-Contracts: 


