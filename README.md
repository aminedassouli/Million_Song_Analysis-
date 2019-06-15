# Million Songs Analysis
### Problem description
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Given a song, the goal is to find some other similar ones. 

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The choice of ‘similarity’ is left to the user depending on what he is looking for (same artist, similar attributes like hotness or danceability...)

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There are some other restrictions that must be taken into consideration :
 
   - A user should be able to narrow the search by giving more specific information

   - The responding time should be short enough to seem interactive

   - The data should be analyzed in a scalable way 

### Data set
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The data set being used is called 'Million Song Dataset', it contains meta data from around one million different songs, and has a total size of 300 GB.
 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It is stored using Hierarchical Data Format version 5 (HDF5) which is a storage model for data with many dimensions and complex objects.
 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The data set does not store any actual audio but instead consists of song features and meta-data collected and analyzed by The Echo Nest. Each HDF5 file stores information about one song as seen in the picture below.

 <p align="center"><img src="https://github.com/aminedassouli/Million_Song_Analysis-/blob/master/HDF5.png"></p>

