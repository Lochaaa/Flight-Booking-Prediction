Problem Statement

Business Context

An aviation company operating in both domestic and international markets seeks to strengthen its customer acquisition strategy. Historically, the company relied on traditional outreach methods such as telecalling and mass marketing campaigns — approaches that are expensive, time-consuming, and yield low conversion rates.

To modernize its marketing efforts, the company has partnered with a leading social networking platform to leverage insights from customers digital footprints and social engagement patterns. By analyzing users online activities — such as time spent on travel-related pages, likes, comments, and interactions — the company aims to identify individuals with a high propensity to purchase flight tickets.

Given that digital advertising costs are substantial, especially in highly competitive travel markets, it is crucial to target only high-potential customers. This data-driven, predictive approach will enable the company to allocate marketing budgets more efficiently, increase conversion rates, and improve return on investment (ROI) through precision-based targeting and smarter customer segmentation.

Objective

As a data scientist, my objective is to develop predictive models that estimate the likelihood of customers purchasing flight tickets based on their online behavioral patterns. To capture distinct user preferences and engagement dynamics, two separate models are built — one for laptop users and another for mobile users — as device type significantly influences browsing and purchase behavior.

These predictive models enable the aviation company to optimize its digital marketing strategy, focusing advertisements on high-potential customers. This approach helps reduce advertising expenditure, increase conversion rates, and ultimately enhance overall return on investment (ROI) through more targeted and efficient campaigns.

Understanding business/Social Opportunity
In today’s digital-first economy, optimizing customer acquisition through data-driven targeting has become a major competitive advantage. The aviation and travel sectors, where average online conversion rates range from 1% to 5% (Contentsquare, 2022), face rising advertising costs and a pressing need to allocate budgets efficiently. According to REVE Chat (2024), the global average conversion rate across industries stands at 2.35%, highlighting a significant performance gap that data science models can address.

Several industry and academic initiatives validate this project’s business potential. For instance, Scandinavian Airlines effectively implemented a booking propensity model to enhance the timing of customer outreach, resulting in improved engagement and conversion. Academic studies further confirm that combining behavioral and social signals (such as device usage and online interaction patterns) leads to superior predictive accuracy compared to transaction-based models alone.

By leveraging these insights, our project explores how device-specific behavioral modeling (Laptop vs. Mobile) can help aviation companies predict customer intent, improve ad personalization, and maximize ROI. This approach not only reduces marketing costs but also promotes a more sustainable, targeted, and user-centric digital marketing ecosystem — a tangible business and social advancement.

Data Description:

The dataset contains different attributes for potential customers of the aviation company. The detailed data dictionary is given below:

UserID: Unique ID of user

Buy_ticket: Buy a ticket next month

Yearly_avg_view_on_travel_page: Average yearly views on any travel-related page by user

preferred_device: Through which device user prefer to do login

total_likes_on_outstation_checkin_given: Total number of likes given by a user on out-of-station check-ins in the last year

yearly_avg_Outstation_checkins: Average number of out-of-station check-ins done by the user

member_in_family: Total number of relationships mentioned by the user in the account

preferred_location_type: Preferred type of location for travelling of user

Yearly_avg_comment_on_travel_page: Average yearly comments on any travel-related page by user

total_likes_on_outofstation_checkin_received: Total number of likes received by a user on out-of-station check-ins in the last year

week_since_last_outstation_checkin: Number of weeks since last out-of-station check-in update by user

following_company_page: Whether the customer is following the company page (Yes or No)

montly_avg_comment_on_company_page: Average monthly comments on the company page by user

working_flag: Whether the customer is working or not

travelling_network_rating: Does the user have close friends who also like travelling? 1 is high and 4 is lowest

Adult_flag: Whether the customer is an adult or not

Daily_Avg_mins_spend_on_traveling_page: Average time spent on the company page by user on a daily basis
