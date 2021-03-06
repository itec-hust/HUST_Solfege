# HUST_Solfege

**HUST_Solfege** is a public solfege dataset for solfege assessment, you can also use this dataset for solfege onset detection or note transcription.

------------------------------------------------------------------------------
**HUST_Solfege** contains 103 audios  including 73 self-built solfege recordings and 30 singing recordings from [MARG](http://marg.snu.ac.kr/automatic-music-transcription/?doing_wp_cron=1554862378.4888939857482910156250).

Among these recordings are 31 male recordings, 35 female recordings and 37 juvenile  recordings. All of the audios are stored as monophonic, 44100Hz sampling rate and 16-bits wav files. Each audio includes  a complete piece of music corresponding to a provided music score.

The statistics of HUST-Solfege is below.

Solfege type|Number of recordings|Number of onset
---|---|---
Male|31|1444
Female|35|1532
Juvenile|37|2092
**TOTAL**|**103**|**5110**



This dataset includes three files in repository: 1) *wav*, 2) *onset&pitch* and 3) *alignment*.

The description of wav files is stated above. All the audios are compressed in ZIP format.

The *onset&pitch* contains the notations for onset and actual pitch of each recording. The notations for offset **haven't** been done yet, please ignore the offset part, it will be completed in future work.
The format of txt in *onset&pitch* is below.

onset|offset|pitch
---|---|---
...|...|...

Note: The 30 recordings from *MARG* are just for onset detection. Pitch notations are not done for MARG recordings.

The *alignment* contains 30 txt file for alignment relationship between actual pitch and score note. 
The statistics of the test set is also available in *statistics_of_testset.txt*.
Note: Test recordings are randomly selected from 73 solfege recordings.
