# rest-graphql
Build a GraphQL API with REST API endpoints
We'll combine the Get NFTs by Contract and Get NFT Transfers by Contract endpoints from two Moralis NFT APIs into a single GraphQL API.

With the Get NFTs by Contract REST API, all of the NFTs accessible from a specified contract address, along with their information, will be retrieved.

All transfers from the NFT collection will be retrieved using the Get NFT Transfers by Contract REST API. 
You should also note on the response sample that the data response is nested and all the fields of interest are placed in the result field. 
The NFT contract address is a necessary argument for both REST APIs.
