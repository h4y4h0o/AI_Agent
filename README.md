A multi-agent AI shopping assistant that searches and ranks product offers across multiple e-commerce sites to provide the best price.

Finding the best price for a product online is increasingly challenging due to fragmented marketplaces, dynamic pricing, and the time-consuming process of manually comparing multiple e-commerce websites. Consumers often overpay or miss deals because current solutions—browser extensions or comparison sites—cover only a subset of stores and rarely provide real-time, structured results.

Our solution is a multi-agent AI shopping assistant that automates the entire search-to-rank workflow. Given a product name or reference, the agent:
1. Searches multiple online stores and identifies relevant product pages.
2. Scrapes price and availability information from each page, intelligently handling different currencies and website structures.
3. Ranks the offers based on price (and optionally availability or merchant rating).
4. Delivers structured results in real-time, allowing users to quickly identify the best deals.

Built with Google ADK and integrated with its LoggingPlugin, the agent is fully observable, ensuring transparency and traceability of all decisions and outputs. Its operates as a multi-agent system where three distinct agents perform their roles in sequence. The tools used by these agents are implemented as functional tools.
This system saves time, reduces costs, and can scale easily to support new products or marketplaces, making it a robust solution for both consumers and businesses seeking actionable e-commerce insights.
