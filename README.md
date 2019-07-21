# Ether_Miner

1. Create a directory called private-eth.

2. Inside that directory add the CustomGenesis.json file.

3. Creating a directory to store the complete blockchain
 ```
  $ geth --datadir ./Ethblockchain --networkid 8888
 ```
4. Open another instance of the terminal and navigate to private-eth directory.

5. Attach geth.ipc to the blockchain directory to communicate with the ethereum blockhain.
 ```
 $ geth attach Ethblockchain/geth.ipc
 ```
6. Create account and start mining.
  Commands:
  a)Create an account : personal.newAccount()
  a)Start mining : miner.start()
  b)Check the balance : eth.getBalance("your_password" a long string usually)
  c)Stop mining : miner.stop()
  
7. Once you start mining you can see the ethers rising in your wallets.Wala you are Richie Rich now.Those are fake ethers haha
.Because its a private ethereum network same happens in the real public ethereum network as well. 
  
 Note : Save the password since it is required for checking the balance after mining.  
