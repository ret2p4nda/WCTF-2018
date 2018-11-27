Belluminar Bank is very small and special. It works as follows:

- Anyone can invest any amount of money and should specify deposit term (deposit will be locked before that);
- Deposit term must be at least 1 year greater than deposit term of previous client;
- An account number is assigned to each deposit;
- Account 0 contains 31337 wei, locked for many years by the bank owner (contract creator);
- The bank owner can confiscate your deposit 1 year after the deposit term (if you don't withdraw).

Your goal is to hack this bank and empty its balance. If you succeed, the bot will send you the flag in transaction data.
Your eth address: 0x72d45c0dc7EfdAfd00467086B65B2fe078788c44
Unlock password: 123qwe
Contract address: 0x8630b28e30890060bc32a48d077d9873ec7499c4
Geth RPC address: http://172.16.13.94:8001

Just in case, here's genesis.json:
{
"config": {
"chainId": 31338,
"homesteadBlock": 0
},

"coinbase" : "0x571dc32a4A4DA1FD6fF02642537D85Be8984dCB2",
"difficulty" : "0x1",
"extraData" : "",
"gasLimit" : "0xffffff",
"mixhash" : "0x0000000000000000000000000000000000000000000000000000000000000000",
"parentHash" : "0x0000000000000000000000000000000000000000000000000000000000000000",
"alloc" : {
"0x72d45c0dc7EfdAfd00467086B65B2fe078788c44": {"balance": "10000000000000000000"},
"0x571dc32a4A4DA1FD6fF02642537D85Be8984dCB2": {"balance": "10000000000000000000"}
}
}