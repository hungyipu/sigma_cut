# sigma_cut
## score images of different sigma cut (sc), with 3598 hi data

### data
sc = 1 are from the image library used in the paper V </br>
sc = 4 are from bh:/bd3/eht/M87/sigma_cut/sc_4/* </br>
sc = 64 are from bh:/bd3/eht/M87/sigma_cut/sc_64/* </br>
each contatins 100 snapshots.</br>
The THEMIS pipeline scoring results are availbe in the folders HARM_sc{1,4,64}</br>

### data_movie
Various movie showing the comparision of the data is in the folder [data_move](https://github.com/hungyipu/sigma_cut/tree/master/data_movie)</br>
For example, the data (100 frames) for MAD, a+0.94, Rhigh=160 with three different sigma cuts:

![example](https://github.com/hungyipu/sigma_cut/blob/master/data_movie/mov_sc_sc_MAD_a%2B0.94_m160.gif)

### results
comparision of the scoring result is shown in the folder [scoring_result](https://github.com/hungyipu/sigma_cut/tree/master/compare_result) </br>
For example, the best fit for M/D for sc=1 is
![example](https://github.com/hungyipu/sigma_cut/blob/master/compare_result/sc1_mod.png)
for sc=4 is
![example](https://github.com/hungyipu/sigma_cut/blob/master/compare_result/sc4_mod.png)
for sc=64 is
![example](https://github.com/hungyipu/sigma_cut/blob/master/compare_result/sc64_mod.png)

A movie for the above results is
![example](https://github.com/hungyipu/sigma_cut/blob/master/compare_result/movie_all_mod.gif)

