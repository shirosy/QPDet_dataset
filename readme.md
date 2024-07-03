## Dataset
Download the dataset from [Google Drive](https://drive.google.com/drive/folders/1ASZCFpPEfSOJRktR8qQ_ZoT9nZR0hOea?usp=sharing) or [Baidu Drive](https://pan.baidu.com/s/19O3IvYNzzrcLqlODHKYUwA) (code:awew).

Organize as follows:
~~~
{DanceTrack ROOT}
|-- dancetrack
|   |-- train
|   |   |-- dancetrack0001
|   |   |   |-- img1
|   |   |   |   |-- 00000001.jpg
|   |   |   |   |-- ...
|   |   |   |-- gt
|   |   |   |   |-- gt.txt            
|   |   |   |-- seqinfo.ini
|   |   |-- ...
|   |-- val
|   |   |-- ...
|   |-- test
|   |   |-- ...
|   |-- train_seqmap.txt
|   |-- val_seqmap.txt
|   |-- test_seqmap.txt
|-- TrackEval
|-- tools
|-- ...
~~~
We align our dataset annotations with MOT, so each line in  gt.txt contains:
~~~
<frame>, <id>, <bb_left>, <bb_top>, <bb_width>, <bb_height>, 1, 1, 1
~~~
