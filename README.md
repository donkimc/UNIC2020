# UNIC2020
UNIC 2020 Apotex Competition

# APOTEX CASE STUDY
## Bid Win Rate Prediction and Optimization

# The Case
## Abstract
A significant portion of Apotex global business is gained through customer bids and Request for
Proposals (RFPs) for our product portfolio. The U.S. generic market is predominantly driven by a
bidding process, where business is won or lost through multiple, short-term (annual or lower)
bid opportunities, as well as less frequent full line RFPs that extend over multiple years. Pricing
and market share vary dramatically based on the number of competitors for each product and
in each market. With over 50 generic competitors operating in the U.S. market, it is a highly
competitive and challenging market to operate in; the key differentiators for success are
portfolio, relationships, service, and bids response time.

Apotex takes a strategic cross-functional approach to assessing our supply capability and pricing
strategy for submitting bids on time to optimize our chances of gaining new business and
maintaining existing business. The Commercial Operations team for each market notifies the
Global Demand Planning team when a bid/RFP contract is opened by a customer and provide
the details of the list of products, monthly/annual volumes being requested, supply start date
and bid submission deadline for supply evaluation. At the same time, the Sales Planning and
Pricing teams work on determining the pricing strategy for each product on the bid. The Global
Demand Planning team assesses and compiles additional data on each product within the scope
of the bid to enable further evaluation by the supply chain teams including:

x Current forecast and potential forecast increase based on bid volume
x Current inventory on hand, and inventory levels after consumption based on bid volume
x Risk inventory
x Next supply replenishment dates and quantities
x API inventory on hand, on order, and API quantity required based on bid volume

The bid is assessed by Supply Chain Execution, External Supply, and Global API teams for
manufacturing and packaging capacity and API coverage. A recommendation is made to the
Commercial team to approve the bid for the supply start date requested or offer an alternate
date based on supply availability and production replenishment plans. Before recommending to
decline to submit a bid, all options are explored to support the bid and escalated for discussion
and final decision making. This includes exploring the option to adjust production schedules by
trading off an already-planned product to make a requested product for the bid, or to make the
decision to carry lower safety stock levels on products to support the volume requested for the
bid.

It is imperative that a proper supply chain assessment is performed prior to the decision to
pursue a bid as the inability to fulfill the details of a contract could lead to significant Failure to
Supply penalties. Given that the turnaround time for responding to bids in the U.S. market is
within 24-48 hours of receiving a bid notification, it is crucial to optimize the bid process with a
focused effort to not only meet customers͛ response time expectations but also to make a bid 
recommendation that provides Apotex with the best competitive advantage in the market to
win bids.

# Task
Your task is to create a recommendation that will help Apotex better understand win rate by
products and customers. This will enable our supply chain and commercial teams to assess and
respond to individual bids more strategically and optimize our chances of gaining new business.
Based on the inputs that are available, determine what their correlation to win rates are so that
we can either focus or completely ignore certain inputs and make the bids analysis process
more efficient.

The model should also be able to help in optimization by predicting feature set that Apotex
needs to adjust/achieve in order to be 100% successful at its first attempt at its bidding
Typical output of ML model will be:

1. Probability (%) of winning an individual bid at the customer and molecule level.
2. For bids with a low probability, recommend what factors can be adjusted to have the
greatest marginal increase in win probability.

Justify how the outcome can be used for: 
1. Driving demand/supply balancing actions within our supply chain that will better
position us to win and support new bid opportunities, including:
a. Forecast adjustments that will drive downstream MRP requirements.
b. Trade-off discussions and adjustments to master production schedules so that
we can prioritize certain opportunities.
2. Pricing strategy for individual bids.
3. Identifying growth opportunities on specific molecules so that our commercial team can
start to approach customers for opportunities instead of waiting for bids to come in for
the product. 
