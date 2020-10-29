# Depression-Detection
•	Detecting depression from acoustic features in speech. The tool is aimed at lowering the barrier of entry in seeking help for potential mental illness and supporting medical professionals' diagnoses.

•	All audio recordings and associated depression metrics were provided by the DAIC-WOZ Database, which was compiled by USC's Institute of Creative Technologies and released as part of the 2016 Audio/Visual Emotional Challenge and Workshop

•	The first step in analysing a person's prosodic features of speech is segmenting the person's speech from silence, other speakers, and noise. Fortunately, the participants in the DAIC-WOZ study were wearing close proximity microphones in low noise environments, which allowed for fairly complete segmentation in 84% of interviews using pyAudioAnanlysis segmentation module.

•	Segmentation also included splitting of participant and interviewers’ voices and removing noise from these audio files.

•	Using these audio files spectrogram was generated for each audio files using Python library Librosa.

•	Generated spectrogram images were later fed into CNN to predict the Depression.
