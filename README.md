# CandyMachine Assesstment | Module3
A Simple NFT Minting Dapp where people mint NFTs using a custom SPL Token

## Descriptioon
In this project I have used surgar-cli(v2), and candy machine-ui to demonstrate custom spl token minting, by connecting the phantom wallet to the dapp and proceeding with the minting of NFTs, after deploying the candymachine NFT configuration file and then using the frontend to view and proceed with the details of the configuration.

### Installation
1. Install node
2. Install yarn
3. Install ts-node
4. Install sugar-cli
5. Install solana-cli
6. Clone the https://github.com/metaplex-foundation/candy-machine-ui in the project repo.

### Execution
1. SPL Token is minted and transferred to a particular account using this repo https://github.com/rsiru37/Sol-Beginner-Mod2-Assessment
2. Hence the splTokenAccount, creator's addresses and splToken entries are populated in the config file
3. We deploy our NFT assets using sugar.
4. sugar validate
5. sugar upload
6. sugar deploy
7. sugar verify
8. sugar mint
9. Hence we get our Candy Machine ID as : F6Sf42iFhZic38Mv91eSGoDN8VvVC6zTRygUXsmrBktC
10. Paste the ID in the .env file inside assets
11. yarn start to start the development server
12. Once the server has started, we will connect our phantom wallet and mint the NFT using C1FUUh4kjDhBF2acFZscLLYNtZvj6TvD3exLsrsyYeET SPL Token on devnet.

## Author
Raj Siruvani - rajsiruvani@gmail.com
   

