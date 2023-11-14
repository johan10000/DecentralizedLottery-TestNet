# DecentralizedLottery-TestNet

This application is deployed on Ethereum test network(Sepolia).

Takeaways:

1. Metamask
2. Role of Ethereum test network
3. Ethereum blockchain infrastructure

Entities in the project:

1. Manager(controller of lottery operation)
2. Participants(players)

Algorithm:
<img width="753" alt="Screenshot 2023-11-14 at 2 17 16 PM" src="https://github.com/johan10000/DecentralizedLottery-TestNet/assets/99970103/d288a22a-4cad-454f-8bff-0b3bc4b1dcbd">


Roles of Manager:

1. Activates lottery
2. Checks number of participants >=3

Rules to become a participant:

1. Must have a wallet
2. Can transfer ether more than once(buy more than one lottery ticket)
3. A lottery ticket is 2 Ether.(Set by us)
4. The address of the participant gets registered when she transfers the ether (for winner announcement)

The contract will reset once a lottery's round is completed.

Learning Source: https://www.youtube.com/watch?v=aFI_XPll_mg&list=PLgPmWS2dQHW_CuryjGPkyH0PNXJ2B0hAk&index=13
