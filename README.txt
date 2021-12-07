To run the Handwritten Text Recognition Model:

1) Make all the necessary installations in Colab mentioned in REQUIREMENTS.txt (all are native to colab).
2) Open the file CS419 Project.ipynb in Google Colab.
3) MAKE SURE TO CAHNGE COLAB RUNTIME TO GPU.
4) Run the cells one by one:
	a) Importing necessary libraries
	b) Mounting Google Drive: This will give a URL. Click on that URL, sign in (if asked) and copy the authorization code. Then paste this code in the box in the ipynb notebook cell and hit enter. Your drive will be mounted onto Google Colab 
	c) Utilizing GPU if support present
	d) Dataloader Cells
	e) CNN Model Declaration
	f) Training the model
	g) Saving to drive
	h) Testing the Model (includes loading the model): This will give the accuracy on testing data
5) Upload the image of some handwritten text in a location in your Google Drive and copy the path to that image
6) Paste this path in the line testimage=cv2.imread('/content/drive/My Drive/Pics/Ifeel.jpg') (this is an example path) under Image Processing -> Image Input
7) Run the next two cells and check the output


NOTE: PLEASE USE THIS LINK IF THE PROVIDED .ipynb FILE IS INACCESIBLE/NOT RUNNING PROPERLY.