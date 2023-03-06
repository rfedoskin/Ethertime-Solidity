# Ethertime-Solidity
Ethertime smart-contract latest testnet implementation 
https://ropsten.etherscan.io/address/0x347b3b19cb4d372050d0eff5bd0f753fbadd488c

link of Pdf docs about how this lottery and smart-contract functions  works:
https://github.com/rfedoskin/Ethertime-Solidity/raw/main/Whitepaper.pdf

How to deploy:

Add the EthertimeFlat.sol file to the Remix platform.
Compile the file using version 0.5.16.
Deploy the Ethertime contract via MetaMask. One warning may appear, which is normal.
The EthertimeHelpers library will deploy first. Save its address, which is separate from the transaction address.
The main contract will deploy after the library is deployed.
When validating the contract, select the "single file" option and paste the contents of EthertimeFlat.sol in the code section. Add EthertimeHelpers to the library section with the address obtained in step 4.
Click "publish" to finalize the deployment process.
