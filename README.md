# r2spin

This document details the recordings and supplementary files for the Re-recorded Revised Speech Perception in Noise Test (R2SPIN). 

When using these files they should be cited as: 

*L. Ward, C. Robinson, M. Paradis, K. Tucker and B. Shirley, “R2SPIN: Re-recording the Revised Speech Perception in Noise Test”, in Interspeech 2019, Graz, Austria, Sept, 2019.*

Reasons for re-recording the corpus, methodology used and validation undertaken are outlined in the above paper. The remainder of this README details the files, their formats and how they may be used. 
We would like to acknowledge the Department of Speech & Hearing Science at the University of Illinois who hold the license for the original R-SPIN recordings for their permission to re-record them. 

The corpus is being made freely available for download under a [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/).

### Audio Recordings 

The .wav files for the R2SPIN are hosted at:
#### [http://data.bbcarp.org.uk/r2spin/](http://data.bbcarp.org.uk/r2spin/) 

The naming convention for these files is:
 
List[#]_[SpeakerGender]_[SNR].wav

Three versions of the new speech recordings are presented, with speech at 0dB, -4dB and -6dB. Each sentence has been normalised to -23 LUFs, as detailed in the paper, before setting the overall level.  Each have the numbers included in the audio file. -4dB is the level used for the validation in the paper and yields an approximate speech reception threshold of 50% for the male speaker. -6dB was used for a small pilot in the paper and yields and approximate speech reception threshold of 50% for the female speaker. These sentences have their keyword align with the timing of the keyword in the original RSPIN recording for ease of comparison with the original. The validation data given in the paper only holds for these timings when used with the original RSPIN multi-talker noise. 

A separate track with the numbers only is also provided. 

If you wish to obtain the original R-SPIN recordings please contact shs[at]illinois.edu 


####Subjective Listening Test Results – Filename: SubjectiveEvaluationResults.xlsx

This is an .xlsx file with all the subjective intelligibility results used to validate the new R2SPIN speakers. This contains each participant’s results at the sentence level (1 denotes a correct response) in a separate worksheet. Each participant completed four lists for each speaker gender, leaving four lists for each gender uncompleted (denoted by columns of zeros). Collated word recognition rates per participant, per list, pre predictability level are also presented, along with standard deviation and standard error of these results. Basic demographic data including gender and age are also given for each participant. 


####Glimpse Proportion Results – Filename: Glimpse_Proportion_Results.xlsx

This is an .xlsx file with all the objective intelligibility metric results for all lists and all speakers at -4dB SNR using the noise from the original recording. Three glimpse proportion calculations are made: over the whole word (noted ‘whole’), over the keyword only (noted ‘keyword’) and over the speech preceding the keyword (noted ‘prime’). Means across speaker and list and their standard deviation (noted ‘STDEV’) are also presented. 


####All Collated Data – Filename: AllData.csv 

This is a .csv file with all the objective and subjective data for all participants for all sentences formatted for use in R. This was used to perform the significance analysis using GEE as detailed in the forthcoming paper. 


####Phonetic Transcriptions – Filename: Phonetic_Transcription_AllSpeakers.xlsx

This excel spreadsheet contains the phonetic transcription of all the keywords, as well as the totals of each type of phoneme for each of the three speakers. The original speaker using Standard American pronunciation is denoted as ‘Original_American’ whilst the male and female Received Pronunciation speakers are denoted as ‘New_RP_Male’ and ‘New_RP_Female’ respectively. 
There is a readme in the first worksheet which describes the transcriptions and noted differences between speakers.


####Acknowledgements

This work was supported by the EPSRC Programme Grant S3A: Future Spatial Audio for an Immersive Listener Experience at Home (EP/L000539/1), the BBC Audio Research Partnership and General Sir John Monash Foundation. 
The authors acknowledge the University of Illinois for their permission to re-record RSPIN and in obtaining original RSPIN documentation.


