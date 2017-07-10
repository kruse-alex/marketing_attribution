# Marketing attribution with markov chains in R
In the world of e-commerce a customer has often seen more than just one marketing channel before they buy a product. We call this a customer journey. Marketing attribution has the goal to find out the importance of each channel over all customers. This information can then be used to optimize your marketing strategy and allocate your budget perfectly but also gives you valuable insights into your customers. There are a lot of different models to allocate your conversions (or sales) to the different marketing channels. Most of the wider known models (e.g. last click) work on a heuristic manner and are fairly simple to implement but with huge restrictions. 

This script focusses on the algorithmic approach of marketing attribution which works on the basis of markov chains. In this model each customer journey is represented in a directed graph where each vertex is channel and the edges represent the probability of transition between the channels. As we are going to focus on how to use this model in R, I totally recommend checking out the research by Eva Anderl and her colleagues. There is another research paper by Olli Rentola which gives a great overview of different algorithmic models for marketing attribution.

There is a great package in R called ChannelAttribution by Davide Altomare which provides you with the right functions to build a markov based attribution model.

![alt text](https://github.com/kruse-alex/codingdurer_twitter/blob/master/twitter_result.jpg)

![alt text](https://github.com/kruse-alex/codingdurer_twitter/blob/master/twitter_result.jpg)


