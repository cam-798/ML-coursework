# ML-coursework
<h1>Machine learning coursework for Applied Machine Learning Systems ELEC0134</h1>

Project aim : To develop multiple machine learning models for classifying images of brain tumors (2 binary models, one non-deep learning approach and one deep learning appraoch and one multi-class model) and tune the models to achieve "good" performance. 

The code is seprated into 5 files, each one is a seperate jupyter notebook (.ipynb). <br />
File 1 contains the code used to spilt that data into seperate folders depending on the image class.<br />
File 2 contains the code used to visulise the dataset.<br />
File 3 contains the SVM model - this inlcudes pulling in the data from the folders and fitting the model.<br />
File 4 contains the binary deep learning model - this includes pulling the the data and training the model.<br />
File 5 contains the multi-class deep learning model - this includes pulling the the data and training the model.<br />

Each file can be ran independently, all required modules are listed at the end of this file.  
Please note: some redundant files were included to ensure that progress over weeks could be seen, the 'final' versions of each model can be seen in files : Binary SVM.ipynb ...

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

