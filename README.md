# PClub_SecyRecruitment_Task3

Although i was unable to code the task. I studied about this task during the time and i wanted to document it.

I had found a research paper https://www.sciencedirect.com/science/article/pii/S0957417424000447#sec4 in which it was being discussed about the masked face gender detection task. 
Also https://link.springer.com/article/10.1007/s41870-023-01565-4 this paper discusses the points in great details.

The algorithm that can be used is to train with normal face and then ommit the region of teh face where we generally wear the mask and then train it again. This means we have to hide a few features and eventually the model must learn from remaining points and understand the details there to distinguish between the gender.
