
1. Prebid.js Core
	1. Execute the auction.
2. Modules
	1. Modules are optional components that extend Prebid.js' capabilities. 
	2. There are many different kinds of modules for purposes like ad request enrichment, analytics, consent management, and more. 
3. #Bid_Adapters
	1. Bid Adapters are functional components that allow bidders to be integrated into Prebid.js.
		1. Bid adapters are plugins that enable Prebid.js to send bid requests to and receive bid responses from bidders. 	
	2. Each bidder has its own bid adapter.
		1. A company that wants to be able to compete in Prebid auctions builds their own bid adapter and contributes it to the Prebid repository.
4. Ad Units
	1. Ad Units are where ad slots are defined within Prebid.js
	2. They describe the characteristics of ad slots and are used to determine the set of bidders that are allowed to serve on each slot
	3. 