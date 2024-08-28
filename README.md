# NICT-Tib1
NICT-Tib1: A public speech corpus of the Lhasa dialect for benchmarking Tibetan language speech recognition systems developed by NICT

# Overview
This dataset is released by NICT under the Creative Commons Attribution 4.0 International License (CC BY 4.0). This dataset is an audio corpus consisting of recorded audio of Tibetan, a low-resource language, and transcriptions. It consists of 33.5 hours of audio of a man and a woman (8 men and 12 women, 15-30 years old) reading a Tibetan news manuscript and its transcriptions. As for the speakers, it contains native speakers who regularly use the Tibetan Lhasa dialect. In the research and development of speech recognition, a test set for evaluating its performance and training data for model learning are essential. This database can be used as both a test set and training data.

# Download
https://ast-astrec.nict.go.jp/en/release/NICT-Tib1/

# Extracted directory
The files have been compressed in 'zip' format (~3.0G). The extracted directory should look like the following.

-------------------------------------------------------------------------------------------
Tibetan/
    data/
       speaker-id/
                 speaker-session-id/
                                    wave-files
    wav.scp (kaldi format)
    label.txt (kaldi format)
    README
-------------------------------------------------------------------------------------------

# Citation
Please cite the following when using the corpus.

-------------------------------------------------------------------------------------------
@INPROCEEDINGS{nict-tib1,
  author={Soky, Kak and Gong, Zhuo and Li, Sheng},
  booktitle={Proc. O-COCOSDA}, 
  title={Nict-Tib1: A Public Speech Corpus Of Lhasa Dialect For Benchmarking Tibetan Language Speech Recognition Systems}, 
  year={2022},
  pages={1-5},
  doi={10.1109/O-COCOSDA202257103.2022.9997917}}
-------------------------------------------------------------------------------------------
