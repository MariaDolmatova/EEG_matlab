# EEG_matlab
This projec is a part of the final assignment for the course of Machine Learning for Neuroscience at Bar-Ilan University. Pre project aims to take a real raw lab data, preprocess it, and build models that would classify the signals.
## Social Neuroscience Lab experiment description
100 participants were divided by pairs and asked to perform freestyle drumming. They didn't have any other instructions, including the instruction to math each others rythm or beat. The electrodes are being attached to 8 regions of participants' heads and EEG signal is being recorded for the whole time of the session, estimating around 4 minutes of record. In many cases participants were starting to math each other, achieving a sertain level of cohesion after a while. After the session all the participants had to fill in a survey about their subjective evaluation of cohesion achieved. Each statement was ranked on a scale from 1 to 6 (1 - strongly disagree, 6 - fully agree), the questions were concentrating on the teamwork and included questions like "I think me and my pair are a good team" and "I would want to work with this person again as a team". 
## Some important notes
Upon the closer inspection of the data, I understood that many samples were not suitable for the analysis due to either accidental earlier termination of the recording, either to a failure in one or several detectors. Some files were simply missing. Since the data in the frame of this project is valuable only in pairs, if one participant in pair had an invalid recording, I had to eliminate the whole pair. This lead to me and my team using only 43 pairs or 86 participants' data in the project. The assumption made in this project is that subjective percieved cohesion could potentially be predicted by physiological data. 
## Data description
- Raw scattered not normalised raw EEG data of 100 participants
- Frequency sample: 500 Hz
- Amount of channels: 8
- Length of the recordings: ~4 minutes (119520 points after normalisation)
- Questionnaire of 5 statements, each ranked 1-6

