# 2.Pre-analysis tasks

## 2-1. Seeing the shape of original series
### Before you apply the time series model to your data, it is extremely important to know the 'shape' of your data. Without knowing this, you will make the mistake of applying wrong model(s) to your data. To do this, the easiest way is to make graph of the data. In SAS, you can submit following code to do this.
![Code of Sgplot](/images/ProcStepSgPlot1.jpg)
### Submitting this code, the graph below is shown on the results window. There seems to be up trend and cyclic changing patterns are there in this data. 
![Result of Sgplot](/images/Graph1.jpg)
### To see these 'basic patterns' clearer, I would like to make 'year-on-year' oveorlayed graphs from this dataset. To do this, the first thing I must do is to cut down data into 'single' year. So I wrote data step shown below.
![Code for transformation](/images/DataStep3.jpg)



