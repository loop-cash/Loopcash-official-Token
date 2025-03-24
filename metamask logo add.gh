# Loopcash official Token update logo in metamask #

## Few steps here ##

##COPY THIS LINK AND GO TO URL##

https://vittominacori.github.io/watch-token/create/

# Select the Ethereum chain mainnet # 
# Paste Transplant Token address # // 0x8af19117aBFb9946B3B6e24c0e203d45eacCb7b5
# Finally paste this link #  //https://raw.githubusercontent.com/loop-cash/Loopcash-official-Token/main/output-onlinepngtools.png







#javascript#

const tokenAddress = '0x8af19117aBFb9946B3B6e24c0e203d45eacCb7b5';
const tokenSymbol = 'LPC';
const tokenDecimals = 18;
const tokenImage = 'https://raw.githubusercontent.com/loop-cash/Loopcash-official-Token/main/output-onlinepngtools.png';

try {
  // wasAdded is a boolean. Like any RPC method, an error may be thrown.
  const wasAdded = await ethereum.request({
    method: 'wallet_watchAsset',
    params: {
      type: 'ERC20', // Initially only supports ERC20, but eventually more!
      options: {
        address: tokenAddress, // The address that the token is at.
        symbol: tokenSymbol, // A ticker symbol or shorthand, up to 5 chars.
        decimals: tokenDecimals, // The number of decimals in the token
        image: tokenImage, // A string url of the token logo
      },
    },
  });

  if (wasAdded) {
    console.log('Thanks for your interest!');
  } else {
    console.log('Your loss!');
  }
} catch (error) {
  console.log(error);
}
```
