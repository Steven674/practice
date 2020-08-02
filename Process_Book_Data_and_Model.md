<b>Data and Model</b>
<ul>
	<li><b>Week 1</b> Steven and Bobby assigned to data and model.  Two proposals are made for the project: 1. create a CNN for image classification as well as an RNN to generate text dynamically 2. Build new features on top of a pre-built model for number reading, and work on developing interesting application features (https://nanonets.com/blog/deep-learning-ocr/).
	<img src="">	
	<li><b>Week 2</b> .ipynb and dataset uploaded to GitHub as placeholders.  Decision made to make a simpler model which partners a CNN with a systematic text generator on the application side.  Decision also not to use any software for developing the model outside of Tensorflow, pandas, and PIL.
	[My image](https://github.com/Steven674/practice/blob/master/images/Week%201.png)

	<li><b>Week 3</b> Many .csv’s received holding Real Estate data. As the project goal becomes finalized, a decision is made to move towards Keras wrapper for the rest of model development.

	<li><b>Week 4</b> 14GB zip received holding Real Estate images.  New plan is to use a much larger dataset in order to more strongly train CNN.
	[My image](https://github.com/Steven674/practice/blob/master/images/Week%204.png)

	<li><b>Week 5</b> Return to .csv’s due to greater uniformity of images (outside shots of full buildings) and more easily parsed categories (shown below).
	[My image](https://github.com/Steven674/practice/blob/master/images/Week%205.png)

	<li><b>Week 6</b> A Keras CNN was built from the ground up predicting categories listed in .csv [SOLDPRICE, ZIP, BEDS, BATHS, etc.], data was cleaned (month by month files combined, rows with missing images removed, nonsensical and NA-items removed or replaced).
	[My image](https://github.com/Steven674/practice/blob/master/images/Week%206.png)
		</li>

	<li><b>Week 7</b> VGGnet-16 keras model used for transfer learning. Current model generates feature-vec to be compared to feature-vec of dataset images in order to present similar real estate images. Model finally connected to application routes.
	[My image](https://github.com/Steven674/practice/blob/master/images/Week%207.png)
</ul>