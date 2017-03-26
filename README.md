# Yahoo Ad Keyword Performance Prediction

In this project, we explore search engine advertiser keyword bidding data over a period of 4 months released by Yahoo! to study the effects of bidding strategies in keyword performance defined by advertisement rank and click through rate. 

Empirical studies have shown that pulse bidding strategies significantly improve keyword performance at lower cost compared to fixed bidding strategies. Advertisers make use of keyword performance feedback given by search engine to optimize their subsequent bid to meet their marketing goals. Strategies adopted in this bidding process are trade secrets that estimate search engines evaluation of advertisement and competitor bidding strategies. As a part of this project, we have designed a regression model that predicts keyword performance for advertisers bid to aid him in evaluating whether the
predicted performance is sufficient to meet his marketing goals. 

To achieve this goal, we engineered a Gradient Boost Regressor built with features based on historical keyword performance of advertiser, competitiveness of keyphrases and bid pulsing strategies. Our prediction model achieved a mean absolute error of 1.99947 for rank prediction task and 0.010386 for click through rate prediction task.
