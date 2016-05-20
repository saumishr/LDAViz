# LDAViz
1.Install R. 

2.Install the following packages: readr, tm, SnowballC, Matrix, lda, LDAvis, servr (You can Run R Studio and Install a package by running the command: install.packages(“<package_name>”)

3. Dataset has forum posts related to 20 different news groups: 
alt.atheism, 
comp.graphics, 
comp.os.ms-windows.misc, 
comp.sys.ibm.pc.hardware, 
comp.sys.mac.hardware, 
comp.windows.x, 
misc.forsale, 
rec.autos, 
rec.motorcycles, 
rec.sport.baseball, 
rec.sport.hockey, 
sci.crypt, 
sci.electronics, 
sci.med, 
sci.space, 
soc.religion.christian, 
talk.politics.guns, 
talk.politics.mideast, 
talk.politics.misc, 
talk.religion.misc

4. Change your working directory by running setwd(“<directory_path>”). Make sure this directory contains the dataset and the script. 
5. Run the script LDAvis.R. 

This will generate following files: d3.v3.js, lda.css, lda.json, ldavis.js, index.html In the same working directory run the following command python -m SimpleHTTPServer
8000. Now access http://localhost:8000/results.html . You should see the visualization of all the topics detected. In the visualization left hand shows the Intertopic Distance Map and the right side shows the top 30 terms for the selected topic.

