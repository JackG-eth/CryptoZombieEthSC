Lesson 1:
  How to write Ethereum smart contracts
  Programming in Solidity, Ethereum's smart contract programming language
  Building games on Ethereum
  Go and test it out (https://share.cryptozombies.io/en/lesson/1/share/JackWeb3?id=Y3p8MTc1MjU0)
    Depending on the name, the smart contract creates an entirely unique zombie!
    
    ![image](https://user-images.githubusercontent.com/33152935/150970033-2838f86d-110b-49f2-b9e0-68181ccfce37.png)

    ![image](https://user-images.githubusercontent.com/33152935/150970095-43d7df1a-9f0a-4179-9f45-2f26fbb4babf.png)

    
Lesson 2:
  Involves learning about solidity Interfaces, Multiple return values, function visibility, different types of storage, require keyword, Msg.Sender Mappings and Addresses.
  https://share.cryptozombies.io/en/lesson/2/share/JackWeb3?id=Y3p8MTc1MjU0

Lesson 3:
  Contract Immutability	
  OpenZeplins Ownable Contract	
  OnlyOwner Function Modifier	
  Gas
  Passing structs as arguments	
  Public Functions & Security	
  More on Function Modifiers	
  Saving Gas	
  Storage Is Expensive	

Lesson 4:
  Is all about building on previous functions while introducing Payability. (storing eth etc)

  
Lesson 5:
  Learning about ERC20 & ERC721 Contracts, Overflow, Onwership etc.
  
Chainlink:

Truffle:
  Before deploying to Ethereum, it is best to test your smart contracts locally.

  You can do so by using a tool called Ganache, which sets up a local Ethereum network.

  Every time Ganache starts, it creates 10 test accounts and gives them 100 Ethers to make testing easier. Since Ganache and Truffle are tightly integrated we can access these     accounts through the accounts array we've mentioned in the previous chapter.
  
Usually, every test has the following phases:

  set up: in which we define the initial state and initialize the inputs.

  act: where we actually test the code. Always make sure you test only one thing.

  assert: where we check the results.
