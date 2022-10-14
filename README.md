<p align="center"> 
<img src="https://cdn.datacamp.com/main-app/assets/brand/logos/DataCamp_Horizontal_RGB-d196011f63ebda76dc5c9772425cf9541b8639af842d5e5476ef10f2460ed1e4.png" width="400">
</p>

# [Datacamp Projects](https://www.datacamp.com/profile/veeralakrishna) from Hari Krishna Veerala
## Contributed to by Marshall Mykietyshyn

This project is forked from [here](https://github.com/veeralakrishna/DataCamp-Project-Solutions-Python)


| Project | Summary of Contribution |
| --- | --- |
| `A Visual History of Nobel Prize Winners` | Added a line showing the average life expectancy at birth to plots of the average Nobel Laureate age over time. This seems to indicate that, after 1940, life expectancy rises at a similar rate. Therefore, the increase in Nobel Laureate age may indicate that the award is simply most often given to late-career researchers. This trend is belied by Nobel Peace Prizes, as mentioned in the original analysis. Adding this line involved searching for, downloading and importing life expectancy data from online sources. <br /> Lessons learned: Experience working in a forked repository, with a more structured git workflow. |
| `Predicting Credit Card Approvals` | Discovered an error in the data pre-processing. Suspiciously, the error had no effect on the model accuracy. Therefore, performed a meta-analysis of the features, demonstrating that the model's accuracy could be replicated using only a single feature, and thus that the model was using only this feature for predictions. All other features simply acted as noise in the model. Furthermore, implemented a neural network to test whether a universal function approximator could improve the prediction accuracy. Ultimately, showed that nothing implemented could improve on the single feature analysis. Therefore, it seems reasonable to say that the data set can be simplified to the feature "prior defaults", or column 8 of the data. <br /> Lessons learned: It is always good to look for the simplest solution before resorting to more complex analysis techniques. Sometimes the data has a lot of noise and the analysis can be simplified by doing some initial pre-processing and feature selection. Practice creating a neural network from scratch, using the official PyTorch [documentation](https://pytorch.org/tutorials/beginner/basics/tensorqs_tutorial.html). |