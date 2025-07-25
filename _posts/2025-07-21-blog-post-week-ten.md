Last week, I imported my data and generated some cleaning scripts to reformat it into a customer and agent response chain. After importing my data and performing some cleaning, I realized that my data was much messier than I had thought. Therefore I had to implement api calls to chat GPT to clean up the sentence structure of the item descriptions such that it is grammatically correct. However, I’ve found this process to be pretty suboptimal and calling chatGPT on 500 lines of data takes a while so I may look to alternatives. 




This week I plan on finishing up my data cleaning, and implementing a data pipeline to automatically update my database if I were to add some new data. This is a concept I want to learn how to do so I think it will be useful in practice since many data science roles require building or working with data pipelines. I also plan on training my model using Amazon’s x4ad.xlarge VM or similar as it offers on demand payment which has relatively cheap on demand payment so If I train according to the repositories instructions, over the course of 4 days, that's running me only a few bucks. (Also I just got some of my “cleaned” data back and the API calls to chat GPT didn’t fix grammatical errors as I wanted for many of my item descriptions still make no sense)




The amount of time it will take to complete this may exceed the time constraints of the course, but I am feeling like I am getting close to having a viable project so I will try to get as much as I can done without going over too much. 




I think I performed more research into the actual ways that LLM processes and receives data which helped me understand what I needed to do in order to train my model correctly. I think this made me understand how my model worked, without focussing on the specific code itself. For example thinking of the mechanism it is performing in the sense of input-output (like a black-box function). This also helped me understand industry practices which is useful if I ever get the chance to explain this project in a job interview. How I can make this process work better is to keep doing what I’ve been doing and performing more research that I can utilize in building my model. 
