# cnnGenderClassification
**Deep learning project based on the CNN ( Convolutional Neural Network) architecture using Tensorflow opensource framework.**

**Major contributing Libraries/modules:<br />**
  	1.Numpy<br />
 	2.Matplotlib<br />
  	3.OS ( To load the Images from local Directories)<br />
  	4.Open CV (To process the images and resizing)
  
**Project Architecture:<br />**
 	Total no. of layers: 08 <br />
   		Conv2D layers: 05<br /> 
   		Fully connected layers: 02<br /><br />
   		Output layer : 01<br />
 	Except the Output layer **Relu** activation function has been used in each layer to avoid any loss of details(gradient vanishing effect may lead to no adjustment in the parameters of intial layers)<br />
	Since **Sigmoid** activatioin function has good binary classification efficieny, hence we used it final neuron.<br />
	
Optimizer: **Adam** <br />
	
Total 2178 Images were passed through the model (90% Training , 10% test) and below were the results:<br />
	Training accuracy: **50.41%**
	Test set Accuracy :**50.46%**
		
Model accuracy was stuck at a point due to local minima of parameters, that's a possibility.
		
Thanks.	

	
	
	
	
	
	

