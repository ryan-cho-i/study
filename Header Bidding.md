
1. What is #Header_bidding ?
	1. Header bidding is a technology used by website publishers and app developers to sell advertising opportunities through programmatic advertising marketplaces.
	2. Website publishers and app developers are #seller
2. Problem 
	1. Publishers and app developers earn money through advertising, and they want to maximize the revenue they earn from a finite amount of traffic.
3. Solution
	1. To maximize yield, a seller will need to form #relationships with a selection of buyers that are able to buy advertising impressions at good prices.
	2. They’ll also set up #an_advertising_technology_stack that gives their buyers the opportunity to compete for each and every ad impression. 
	3. The ad stack is also responsible for rendering the ads and offers the seller controls that influence pricing, ad quality, and user experience. Analytics, A/B testing, and other optimization tools help the seller grow their yield over time.
	4. In digital media, there are two prominent techniques for managing yield: the waterfall and header bidding.
4. #Waterfall 
	1. The waterfall predates header bidding.
	2. In a waterfall, the seller creates #a_prioritized_ranking of their buyer partners. Each time an impression is available for sale, the top partner in the ranking is shown the opportunity and has the option to buy it or refuse it. If they choose to buy, they deliver their ad. If they refuse, the waterfall shows the impression to the next partner in the ranking, and the cycle repeats until a willing buyer is found.
	3. The waterfall’s design limits publishers’ ability to maximize yield, because it doesn’t expose impression opportunities to all of the potential buyers and can’t find the best price for each impression. Its sequential nature also makes it a slow process, which causes some impressions to go unsold.
6. #Header_bidding 
	1. Auctions allow all potential buyers to see the impression simultaneously and compete for it by bidding. This ensures that the impression is sold for a fair price and delivers the ad quickly and efficiently.
7. #header_bidding_wrapper
	1. The header bidding component
	2. When a web page or app loads, the header bidding wrapper also loads. The wrapper initiates an auction for the available ad spaces on the page, and sends bid requests to potential buyers, notifying them that an impression is available for sale.
	3. In a fraction of a second, the buyers respond with bids containing the ad they want to serve, the price they’re willing to pay, and other relevant information. The header bidding wrapper then collects and passes these bids to the primary ad server.