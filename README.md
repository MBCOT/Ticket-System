# A generic Ticketing System <img src="logo_yellow.png" width="350" title="Ticketing System" alt="Ticketing System" align="right">
**Ticketing system to avoid fraud and over saturation and proof authentiticy**

<br/><br/>
- Buid a generic ticketing system that any company, organization, user can use to create his own tickets for any event or anything and manage automatically the selling and the authentication of the tickets, or simply register any information and generate and NFT token with it.

# Use cases:
-  **A city, car park company**, can set up QR codes from his tickets, everyone representing a place on parking lot.
   - A  user who wants to park on this lot, scans the QR code  and pays automatically for a period of time of 24 hours.
   - When the user got his car back, scan the QR code again and is only charged with the period of time of use and a refund is sent to him less the period of time used.
  This sppecific use case can be very useful to people who want to park on a city, showing the free lots spaces to park your car all over the city near your position or a target destination with a very cheap investment from the City hall or any company that manages parking lots areas.
-  **On concerts, events, meetings, football** competitions, race competitions..... people have to get their 
tickets usually online and most of times on a high demand the system got collapsed or the tickets
once printed they got falsificated.

- **Create a recipe NFT token from any info or transaction.**
  - A company, organitzations or people can get an NFT token configured with some info given.
    - It can be used on many ways and integrated into shops, businness, healthcare systems, real world contracts, etc..

# A ticketing system Dapp over minima will avoid most of those problems, the organization of the
events would buy a specific number of NFT's configured according their needs and with his
publicity chosen embedded on the NFT, so the user would only had to install the DAPP (One dapp
for all systems) , choose the competition or the concert or whatever tickets they want to buy, and
once payed the NFT's tickets, they are sent to the wallet's user.
  -  On the event day, only the people who got the NFT on his wallet can access to the event and avoid
fraud and the over saturation when some kind of event is high demanded by a lot of people.

  - An API can also be developed so third parties can use the system from his own system without they need to install any dapp on minima.

# Approaches:
  - **1: Central System to sell confifured on demand Tokens events and his token tickets related to.**
    - It requires a server that will run a dapp so other companies or organizations can buy configured tokens.
    - Token_event and token_ticket tokens or any other token must be created and a tokenomics should be done.
      - Every token has his own smart contract embeeded that force all parties not to cheat and rules the states changes betwenn several actions.
    - To sell the tickets to the users the third party company/organization can send the buyed configured tokens into an smart contract that says:
      **" you can only get one ticket if you pay an x ammount of minimas and set on the state variable 0 your wallet"**.
      - The ticket token has an smart contract embedded that once is sent to your wallet, you can only move it to a specific wallet address avoiding any abuse.
    - **PROS**
      - Tokenized system
      - The transactions to sell tokens can be delivered over maxima to be posted by the user in order not to pay any possible burn.
      - As the tokens are bought by companies or organizations is not expected a huge load of work on the server side.
      - An ecosytem over minima can be created to monetize the system easily and even the tokens could be tradeable on any minima DEX.
    - **CONS**
      - Requires a server that runs the Dapp to configure and sell tokens.
      
  - **2: Fully Decentralized System.**
    - **A dapp that anyone** can install that let your create all the tokens and the tickets and build the functionality you want.
      -  Configure the event token with event info and where to buy the tikets for this event.
      -  Configure the smart contracts conditions where people will get the tickets from, paying an x amount of tokens in (minimas or whatever).
      -  Configure the tickets to sell, the number of them and the information and publicity that they must have.
      -  Configure the tickets smart contract to avoid fraud and abuse.
      -  Create all the tokens with his smart contracts and also the selling smart contract configured on the previous steps.
      -  Publish on the public events dashboard contract,  the token event configured, so users can start buying tickets.
    - **A dapp that let you read** the events dashboard contract and select an event token to get the info to buy the tickets.
      - The user choose an event from the fetched list.
      - The user buys a ticket for that event doing the required transaction according the event token requirements info.
      - The dapp also let you proof that you onwn the ticket for specific event, this could be done on chain or using Maxima and the archive nodes to check that you own the coin.
      - The dapp also let the organizers of the event to check if a user owns a token to access to the event.
      - **PROS**
        - Fully decentralized, no third party are needed.
        - You configure and create your own tokens.
      - **CONS**
        - More complex to develop.
        - More complex to Monetize and tokenize the system.
          - **Posibilities:**
            - Pay per use based on the nummber of tickets tokens to generate.
            - Monthly Plan Subscription, every plan offers a default free ticket number of tokens to be created. 
      
