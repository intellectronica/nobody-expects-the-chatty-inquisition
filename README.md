We know that we can ask GPT questions. But how about it asking us? In this example Azure Open AI GPT-3.5-turbo is working for us as a waiter in a restaurant. Instead of us asking it questions, it is taught to ask us for the details of our order, so that it can be fullfilled. The state of the order is maintained outside the model, and passed in and out in each interaction as JSON. This example is bare, without using any libraries, to make it easy to see how the mechanism work, but it would be even easier using LangChain / Guidance / SK.

See [notebook](chatty-inquisition.ipynb).
