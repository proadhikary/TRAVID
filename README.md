# <div align="center"><img src="https://user-images.githubusercontent.com/55135657/189181536-42f858f5-3567-472f-972c-495e45345117.png" alt="TRAVID" width="180"/></div>

![HomePage](https://user-images.githubusercontent.com/55135657/188446021-80aec522-881a-43cb-b956-319918d20105.png)

Travid is a small-scale Face-to-Face Video Translator project that lets users translate a short-duration video in one language to a selected language while maintaining the lip synchronisation, as well as an attempt at voice-cloning.

# Installation
To use our Face-to-Face Translator, Travid, simply place /TRAVID folder from this repository next to your program, or <b>clone our repository</b> using the following line of code:
```
git clone https://github.com/Sugandhi1701/TRAVID
```
### Requirements
The python dependencies required to run our code can be installed using **pip install** command as below:
```
pip install SpeechRecognition pydub deep-translator librosa gTTS pyttsx3
```
For lip synchronisation, we have used an existing Wav2Lip model. **Clone** the same using the following lines of code:
```
!git clone https://github.com/zabique/Wav2Lip
!wget "https://www.adrianbulat.com/downloads/python-fan/s3fd-619a316812.pth" -O "/content/Wav2Lip/face_detection/detection/sfd/s3fd.pth"
!wget 'https://iiitaphyd-my.sharepoint.com/personal/radrabha_m_research_iiit_ac_in/_layouts/15/download.aspx?share=EdjI7bZlgApMqsVoEUUXpLsBxqXbn5z8VTmoxp55YNDcIA' -O '/content/Wav2Lip/checkpoints/wav2lip_gan.pth'
!wget 'https://iiitaphyd-my.sharepoint.com/:u:/g/personal/radrabha_m_research_iiit_ac_in/Eb3LEzbfuKlJiR600lQWRxgBIY27JZg80f7V9jtMfbNDaQ?e=TBFBVW' -O '/content/Wav2Lip/checkpoints/wav2lip.pth'
!pip install https://raw.githubusercontent.com/AwaleSajil/ghc/master/ghc-1.0-py3-none-any.whl
```
Further, the libraries supported by the lip sync model Wav2Lip can be installed using the following line of code:
```
cd Wav2Lip && pip install -r requirements.txt
```
# A Guide through our Website
![Github Guide 1](https://user-images.githubusercontent.com/55135657/188560174-2f2dfd44-248a-43ff-96a5-38fd0e3a7992.png)
![Github Guide 2](https://user-images.githubusercontent.com/55135657/188560181-131b10a6-f5db-4649-a6b6-3846f97e157f.png)
<div align="center"><img src="https://user-images.githubusercontent.com/55135657/188560187-9307886c-18e6-4103-9716-ea6b025f35cd.gif" alt="Github Guide 3" width="50%" align="center"/></div>

