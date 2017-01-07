---
layout: project

summary:
    name: Reading Terminal Market Purchasing Platform
    tagline: Bringing the Popular Reading Terminal Market completely online 

team:
    - year: 2016
      semester: Spring
      pm: Alex Piatski
      tl: Abhinav Suri
      developers:
          - Maya Ebsworth
          - Rani Iyer
          - Annie Meng
    - year: 2015
      semester: Fall
      pm: Natasha Narang
      tl: Jonathan Dubin
      developers:
          - Krishna Bharathala
          - Cathy Chen
          - Hunter Lightman
          - Max McCarthy
          - Rodrigo Ornelas

client:
    - name: Reading Terminal Market
      description: >
        The Reading Terminal Market, one of the nation’s largest and oldest public markets, is a 501(c)3 non-profit, with the following mission statement: To preserve the architectural and historical character, and function, of the Reading Terminal Market as an urban farmers' market; To provide a wide variety of produce, meat, fish, bakery and dairy products, and other raw and prepared food, brought to a public market in the center of the city by farmers, growers, producers and chefs; To maintain an environment that recognizes and celebrates the diversity of our citizens and fosters their interaction; To strengthen the historic link and mutual dependency of our rural and urban communities; and, To achieve this, while preserving the financial viability and achieving self-sufficiency for the Market.
      website_url: http://www.readingterminalmarket.org/

project:
    problem: >
        Until now, all merchant-vendor interactions have taken place offline. Our goals are to: Introduce greater transparency into the merchant-vendor market by making all vendor listings and prices available to merchants; Allow smaller vendors to be easily discovered; Discourage artificially high prices; and Make merchant-vendor interactions more efficient. We can do this by: Making all vendor listings and prices available to merchants; Providing separate accounts for vendors, merchants, and administrators; and Providing flexibility to constantly update product listings, invoices, and addition of new merchants and vendors into the community.

    features:
        - "Vendors: Create their own business profiles with contact information, address, business description, payment preferences"
        - "Vendors: Review Accept, Reject orders received from merchants. Email coming soon"
        - "Vendors: Post listings to the site with: Description, Cost per Unit, Availability"
        - "Merchants: Filter and Search Listings by price range"
        - "Merchants: Store Favorite Items"
        - "Merchants: Add Listings to Shopping Cart"
        - "Merchants: Checkout to receive e-mail consisting of invoices for each individual vendor in order to complete transactions offline"
        - "Merchants: View invoice history"
    technologies:
        - Flask
        - SQL
        - Semantic-UI
    technical_challenges:
        - The bulk upload work required lots of handling of different input data formats. Many edge cases were tried and tested.
        - Most of the functionality had been implemented, but we had yet to have vendors or merchants use the app. Their testing provided useful input for changes in the app.
    impact: >
        The purpose of the project is to allow and cultivate more local farmers, small "mom and pop vendors who would normally not be able to be a provider without a medium to reach all merchants in the market. By inviting these smaller vendors into bring locally grown, fresher products to market. Additionally it will give all of our merchants choices and allowing us to become more competitive for the Market as well as  to continue to give our customers the best choices.

code:
    github_repo_name: reading-terminal-market
    live_url: http://rtmprocurement.com

keywords:
    social_impact_keywords:
        - procurement
        - small business
        - marketplace
    tech_keywords:
        - platform
        - cost-saving
        - transparency

media:
    screenshots:
        - screenshot_caption: Search Results
          screenshot_url: https://raw.githubusercontent.com/hack4impact/reading-terminal-market/master/ss1.jpg
        - screenshot_caption: Manage Carts
          screenshot_url: https://raw.githubusercontent.com/hack4impact/reading-terminal-market/master/ss2.jpg
        - screenshot_caption: Manage Orders
          screenshot_url: https://raw.githubusercontent.com/hack4impact/reading-terminal-market/master/ss3.jpg
---
