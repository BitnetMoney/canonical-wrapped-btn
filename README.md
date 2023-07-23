# Wrapped BTN
The Wrapped BTN protocol allows BTN native coins to be wrapped and
used in other on-chain protocols or interact with other BTS20 tokens
directly.

### Token Information
**Name:** Wrapped Bitnet
**Symbol:** WBTN
**Decimals:** 18

**Live Contract Address:**
```
0x8148b71232162EA7a0b1c8bFE2b8F023934BFb58
```

## Read Functions

### allowance
Fetches the contract allowance from a particular address to another.  
`owner` *address*: Owner of the WBTN balance.  
`spender`*address*: Spender of the owner's WBTN.  

### balanceOf
Fetches the balance of WBTN from a wallet.  
`account` *address*: Account to query the balance from.  

### decimals
Returns the number of decimals of the token (18).  

### name
Returns the name of the contract.  

### symbol
Returns the symbol of the contract.  

### totalSupply
Returns the total supply of WBTN in circulation.  

### paused
Returns the pause status of the contract.  

### isPauser
Returns an address pauser status.  
`account` *address*: Account to query.  