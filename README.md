# anomaly-detection-in-traffic-videos-using-opencv--python
This system will identify the violation in traffic rules at traffic junctions using the cctv footage obtained at different traffic junctions with the help of  multilevel hdp and guassian process with active learning and opencv python.

As we all know the ccv footage obtained from different important places is kept ideal without any use until any incident has happend. After the occurence of the incident like atm theft, chain snatching and traffic rules violation at the junctions which will ultimatley lead to an accident the police man will go through a tremduous amount of video footage to find the cause, instead doing this we can identify the anomalies mentioned above using computer vision and python. Which will reduce the hectic job of watching the cctv footage by man. It can also be converted to real-time solving problem by using buzz system when ever the system finds an abnormality.

File- Full code Gmm with active learning is a jupyter notebookfile. Here Guassian mixture model clustering technique is used clustering the activities and active learning also included to improve the classification capacity of the guassian process classifier.

File- Full code GMM without active learning is a jupyter notebookfile. Which is same as above file only difference is active learning is not included. 

File- Full code HDP directly giving motion vectors, is jupyter notebook file. Here for HDP clustering technique is used for clustering and the input provided is the magnitude of the history obtained from optical flow.

In all files we should  provide a input path to the video and annotation file(used for labeling the clips). Video used as input is IDIAP junction dataset(traffic-junction.avi). Dataset link: https://www.idiap.ch/~odobez/RESSOURCES/DataRelease-TrafficJunction.php 

Sample annotation file also provided. (Note: annotation should be in the format provided)


