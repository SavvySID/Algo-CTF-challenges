# Algo-Capture The Flag-Challenges 
## By Siddhant Mehrotra

Welcome to my Algo-Capture the Flag (CTF) challenges repository! These are the CTF challenges by Algorand. This repo contains the code and output for these challenges. I have documented the results of each challenge so you can see how things played out on the Algorand TestNet.

## CTF challenge-1

Task:
In this challenge, I had to uncover a hidden clue stored in the global storage of a deployed smart contract. The clue could be retrieved by analyzing one of the contract’s transactions.

Receiver address(task): 2JAZQO6Z5BCXFMPVW2CACK2733VGKWLZKS6DGG565J7H5NH77JNHLIIXLY

Terminal Output:
```
Address: FBXYHGE537YPL4JAUAWXUDQCZFEAK6KBMSKJXKWHIUWT7BJX7BU5O3NVBM
Txn sent: https://testnet.explorer.perawallet.app/tx/ZJ72AB2RUKNUJ5GC4JPMABJU6YJKLZ4YCNPQ7OYR7HQWAUMYLACA
Txn Confirmed in round 44390993
```
Txn: [ctf transact-1](https://testnet.explorer.perawallet.app/tx/ZJ72AB2RUKNUJ5GC4JPMABJU6YJKLZ4YCNPQ7OYR7HQWAUMYLACA)

<img width="901" alt="transaction1" src="https://github.com/user-attachments/assets/bb205766-df9f-4094-a8d1-97c6d19da533">

## CTF challenge-2
Task:
This challenge involved uncovering a hidden clue encrypted within six different strings. The clue was deciphered using substitution cipher techniques.

Asset ID(task): 720485937

```
Address: FBXYHGE537YPL4JAUAWXUDQCZFEAK6KBMSKJXKWHIUWT7BJX7BU5O3NVBM
Txn sent: https://testnet.explorer.perawallet.app/tx/WUJKDFMLXIFBZWSW23W6ZN5EXXJ5GNLT4AVSZQFIOMOK4P3Q32PQ
Txn Confirmed in round 44391057
```
Txn: [ctf transact-2](https://testnet.explorer.perawallet.app/tx/WUJKDFMLXIFBZWSW23W6ZN5EXXJ5GNLT4AVSZQFIOMOK4P3Q32PQ)

<img width="887" alt="optintransaction" src="https://github.com/user-attachments/assets/92cbb8fb-28ca-47e0-8d96-e543dfa07d32">

## CTF challenge-3
Challenge 3: Asset ID and Message Encryption
In this challenge, I needed to use an asset ID and a wallet address to form a 9-character key. This key was then used to encrypt the message:
"Algorand uses Pure Proof of Stake Algorithm."

After encrypting the message, I had to send 1 Algo to a given wallet address, including the encrypted string as a note in the transaction. I completed the task programmatically on the Algorand TestNet.

Message in encryption: ae6ebfcff2e1d10cafb51c0e4ab77da22838436dd3b5d82b7d2eb6104bd30dc3

```
Address: FBXYHGE537YPL4JAUAWXUDQCZFEAK6KBMSKJXKWHIUWT7BJX7BU5O3NVBM
Txn sent: https://testnet.explorer.perawallet.app/tx/I4KXUQQ65R32VJXCQVGYQY6D7BB7GLLCQ4GQHHBTPR6XRIIK6D7A
Txn Confirmed in round 44391123
```

Txn: [ctf transact-3](https://testnet.explorer.perawallet.app/tx/I4KXUQQ65R32VJXCQVGYQY6D7BB7GLLCQ4GQHHBTPR6XRIIK6D7A)

<img width="850" alt="transaction3" src="https://github.com/user-attachments/assets/15063649-f5ee-4275-9e6f-d76f5925acf1">
