# ML-coursework
<h1>Machine learning coursework for Applied Machine Learning Systems ELEC0134</h1>

<h1> PLEASE NOTE : If you want to download the folders and data, use google drive (https://drive.google.com/drive/folders/1naSTeo-hc3iDq3w3OobtL6cDkuL-3D2o?usp=sharing) as the files are too big for Github </h1>

Project aim : To develop multiple machine learning models for classifying images of brain tumors (2 binary models, one non-deep learning approach and one deep learning appraoch and one multi-class model) and tune the models to achieve "good" performance. 

The code is seprated into a number of files, each one is a seperate jupyter notebook (.ipynb). <br />

Files that start with "Machine learning" are draft files. These files are rough drafts and only included to show progress over time of the model as required by the specification. The files that contain the final model are:

<h4>No task</h4>
split_data : contains the code for the code used to spilt that data into seperate folders depending on the image class.<br />
visulising data : contains the code for the code used to visulise the dataset.<br />
testing better ways : contains code for trying various things that may have imrpoved the models.
<br>
<h4>Task A)</h4>
Binary SVM : contains the code for the SVM model - this inlcudes pulling in the data from the folders and fitting the model.<br />
Binary CNN : contains the code for the binary deep learning model - this includes pulling the the data and training the model.<br />
Binary CNN with augemented images : contains the code for the same as the binary CNN but on a dataset with augmented images <br />
<br>
<h4>Task B)</h4>
Multi-class CNN : contains the code for the multi-class deep learning model - this includes pulling the the data and training the model.<br />
Ensemble CNN : contains the code for multi-class using two CNNs 

Each file can be ran independently, all required modules are listed at the end of this file.  
Please note: some redundant files are included here to ensure that progress over term could be seen as requested in the spec. 

<h2>Dependencies</h2> 
<br>
Python 3.9 (at the time of writing this code doesnt work with Python 3.10)

<h3>Libraries</h3>
<h4>Data handling</h4>
<ul>
 <li> pandas </li>
 <li> numpy </li>
 <li> OS </li>
 <li> PIL </li>
</ul>
<h4>Machine Learning (non deep learning)</h4>
<ul>
 <li> sklearn </li>
</ul>
<h4>Deep learning</h4>
<ul> 
 <li> tensorflow </li>
 <li> keras </li>
</ul>
<h4>Plotting</h4>
<ul>
 <li> seaborn </li>
 <li> matplotlib </li>
</ul>

