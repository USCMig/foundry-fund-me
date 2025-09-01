-include .env

build:; forge build

deploy-sepolia:
	forge script script/DeployFundMe.s.sol:DeployFundMe --rpc-url $(SEPOLIA_RPC_URL) --account devwallet --sender 0x0588A3FEE4f72a6166dC5c2C6Cfeca9349bAd897 --broadcast --verify --etherscan-api-key $(ETHERSCAN_API_KEY)-vvvv