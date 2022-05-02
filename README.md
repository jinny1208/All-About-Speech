# Everything About Speech
This repository organizes papers, learning materials, codes for the purpose of understanding speech. There is another repository for machine/deep learning [here](https://github.com/jinny1208/All-Resources-Related-to-ML-DL).

## To Dos:
- organize stars
- add more papers 
  - papers to read:
    1. Speech=T:Transducer for TTS and Beyond

## Organizations
* DeepMind [[repo]](https://github.com/deepmind/deepmind-research)
* OpenAI [[repo]](https://github.com/openai)
* Club House: WeeklyArxivTalk [[repo]](https://github.com/jungwoo-ha/WeeklyArxivTalk)

## Other Repositories to Refer to - Speech Included/Related
* Speech Researchers List [[repo]](https://github.com/mutiann/speech_rankings)
* Jackson-Kang [[repo]](https://github.com/Jackson-Kang/Awesome-DL-based-Text-to-speech-Papers-and-Resources)
* Rosinality's ML [[repo]](https://github.com/rosinality/ml-papers)
* ivallesp's [[repo]](https://github.com/ivallesp/papers)
* ddlBoJack's Speech Pretraining [[repo]](https://github.com/ddlBoJack/Awesome-Speech-Pretraining)
* fuzhenxin's Style Transfer in Text [[repo]](https://github.com/fuzhenxin/Style-Transfer-in-Text)


## TTS
* TTS
  - DC-TTS [[paper]] [[pytorch]](https://github.com/chaiyujin/dctts-pytorch)[[tensorflow]](https://github.com/Kyubyong/dc_tts)
  - Microsoft's LightSpeech [[paper]] [[code]](https://github.com/microsoft/NeuralSpeech)
  - SpeechFormer [[paper]] [[code]](https://github.com/HappyColor/SpeechFormer)
  - Non-Attentive Tacotron [[paper]]() [[pytorch]](https://github.com/JoungheeKim/Non-Attentive-Tacotron)
  - Parallel Tacotron 2 [[paper]] [[code]](https://github.com/keonlee9420/Parallel-Tacotron2)
  - FCL-taco2: Fast, Controllable and Lightweight version of Tacotron2 [[paper]] [[code]](https://github.com/Wendison/FCL-taco2)
  - Transformer TTS: Neural Speech Synthesis with Transformer Network [[paper]] [[code]](https://github.com/soobinseo/Transformer-TTS)
  - VITS: Conditional Variational Autoencoder with Adversarial Learning for End-to-End Text-to-Speech [[paper]] [[code]](https://github.com/jaywalnut310/vits)


* Voice Conversion / Voice Cloning / Speaker Embedding
  - StarGan-VC: Non-parallel many-to-many voice conversion with star generative adversarial networks [[paper]] [[code]](https://github.com/liusongxiang/StarGAN-Voice-Conversion)
  - Neural Voice Cloning with Few Audio Samples (Baidu) [[paper]]  [[code]](https://github.com/VisionBrain/Neural_Voice_Cloning)
  - Assem-VC: Realistic Voice Conversion by Assembling Modern Speech Synthesis Techniques [[paper]] [[code]](https://github.com/mindslab-ai/assem-vc)
  - Unet-TTS: Improving Unseen Speaker and Style Transfer in One-Shot Voice Cloning [[paper]](https://arxiv.org/abs/2109.11115) [[code]](https://github.com/CMsmartvoice/One-Shot-Voice-Cloning)
  - FragmentVC: Any-to-any voice conversion by end-to-end extracting and fusing fine-grained voice fragments with attention [[paper]] [[code]](https://github.com/yistLin/FragmentVC)
  - VectorQuantizedCPC: Vector-Quantized Contrastive Predictive Coding for Acoustic Unit Discovery and Voice Conversion [[paper]] [[code]](https://github.com/bshall/VectorQuantizedCPC)
  - Cotatron: Transcription-Guided Speech Encoder for Any-to-Many Voice Conversion without Parallel Data [[paper]] [[code]](https://github.com/mindslab-ai/cotatron)
  - Again-VC: A One-shot Voice Conversion using Activation Guidance and Adaptive Instance Normalization [[paper]] [[code]](https://github.com/KimythAnly/AGAIN-VC)
  - AutoVC: Zero-Shot Voice Style Transfer with Only Autoencoder Loss [[paper]] [[code]](https://github.com/auspicious3000/autovc)
  - SC-GlowTTS: an Efficient Zero-Shot Multi-Speaker Text-To-Speech Model [[code]](https://github.com/Edresson/SC-GlowTTS)
  - Deep Speaker: an End-to-End Neural Speaker Embedding System [[paper]] [[code]](https://github.com/philipperemy/deep-speaker)
  - VQMIVC: One-shot (any-to-any) Voice Conversion [[paper]] [[code]](https://github.com/Wendison/VQMIVC)

* Style (Emotion, Prosody)
  - SMART-TTS Single Emotional TTS [[code]](https://github.com/SMART-TTS/SMART-Single_Emotional_TTS)
  - Cross Speaker Emotion Transfer [[paper]] [[code]](https://github.com/keonlee9420/Cross-Speaker-Emotion-Transfer)
  - AutoPST: Global Rhythm Style Transfer Without Text Transcriptions [[paper]] [[code]](https://github.com/auspicious3000/AutoPST)
  - Transforming spectrum and prosody for emotional voice conversion with non-parallel training data [[paper]] [[code]](https://github.com/KunZhou9646/emotional-voice-conversion-with-CycleGAN-and-CWT-for-Spectrum-and-F0)
  - Multi-Reference Neural TTS Stylization with Adversarial Cycle Consistency [[paper]] [[code]](https://github.com/entn-at/acc-tacotron2)
  - Learning Latent Representations for Style Control and Transfer in End-to-end Speech Synthesis (Tacotron-VAE) [[paper]] [[code]](https://github.com/jinhan/tacotron2-vae)
  - Time Domain Neural Audio Style Transfer (NIPS 2017) [[paper]] [[code]](https://github.com/pkmital/time-domain-neural-audio-style-transfer)
  - Meta-StyleSpeech and StyleSpeech [[paper]] [[code]](https://github.com/KevinMIN95/StyleSpeech)
  - Cross-Speaker Emotion Transfer Based on Speaker Conditino Layer Normalization and Semi-Supervised Training in Text-to-Speech [[paper]] [[code]](https://github.com/keonlee9420/Cross-Speaker-Emotion-Transfer)

* Cross-lingual
  - End-to-End Code-switching TTS with Cross-Lingual Language Model
    - mandarin and english
    - cross-lingual and multi-speaker
    - baseline: "Building a mixed-lingual neural TTS system with only monolingual data"
  - Building a mixed-lingual neural TTS system with only monolingual data
  - Transfer Learning, Style Control, and Speaker Reconstruction Loss for Zero-Shot Multilingual Multi-Speaker Text-to-Speech on Low-Resource Languages
    - has many good references

* Music Related
  - Learning the Beauty in Songs: Neural Singing Voice Beautifier (ACL 2022) [[paper]] [[code]](https://github.com/MoonInTheRiver/NeuralSVB)
  - Speech to Singing (Interspeech 2020) [[paper]] [[code]](https://github.com/ericwudayi/speech2singing)
  - DiffSinger: Singing Voice Synthesis via Shallow Diffusion Mechanism (AAAI 2022) [[paper]] [[code]](https://github.com/MoonInTheRiver/DiffSinger)
  - A Universal Music Translation Network (ICLR 2019) 
  - Jukebox: A Generative Model for Music (OpenAI) [[paper]](https://arxiv.org/pdf/2005.00341.pdf) [[code]](https://github.com/openai/jukebox/tree/master/jukebox)


* Toolkits
  - IMS Toucan Speech Synthesis Toolkit [[paper]](http://festvox.org/blizzard/bc2021/BC21_IMS.pdf) [[code]](https://github.com/DigitalPhonetics/IMS-Toucan)
  - CREPE pitch tracker [[code]](https://github.com/maxrmorrison/torchcrepe)
  - SpeechBrain - Useful tools to facilitate speech research  [[code]](https://github.com/speechbrain/speechbrain)

* Vocoders

## ASR
- Towards End-to-End Spoken Language Understanding 

## Speech Classification, Detection, Filter, etc.
- HTS-AT: A Hierarchial Token-Semantic Audio Transformer for Sound Classification and Detection [[paper]] [[code]](https://github.com/RetroCirce/HTS-Audio-Transformer)
- Google AI's VoiceFilter System [[paper]] [[code]](https://github.com/mindslab-ai/voicefilter)
- Improved End-to-End Speech Emotion Recognition Using Self Attention Mechanism and Multitask Learning (Interspeech 2019) [[paper]] [[code]](https://github.com/KrishnaDN/speech-emotion-recognition-using-self-attention)
- Multimodal Emotion Recognition with Tranformer-Based Self Supervised Feature Fusion [[paper]] [[code]](https://github.com/shamanez/Self-Supervised-Embedding-Fusion-Transformer)
- Emotion Recognition from Speech Using Wav2vec 2.0 Embeddings (Interspeech 2021) [[paper]] [[code]](https://github.com/habla-liaa/ser-with-w2v2)
- Exploring Wav2vec 2.0 fine-tuning for improved speech emotion recognition [[paper]] [[code]](https://github.com/b04901014/FT-w2v2-ser)
- Rethinking CNN Models for Audio Classification [[paper]] [[code]](https://github.com/kamalesh0406/Audio-Classification)
- EEG-based emotion recognition using SincNet [[paper]] [[code]](https://github.com/meiyor/SincNet-for-Autism-EEG-based-Emotion-Recognition)

## Speaker Verification
- Cross attentive pooling for speaker verification (IEEE SLT 2021) [[paper]] [[code]](https://github.com/seongmin-kye/CAP)

## Linguistics

## Learning Materials
1. Digital Signal Processing Lecture [[link]](https://github.com/spatialaudio/digital-signal-processing-lecture)
2. Ratsgo's Speechbook [[link]](https://github.com/ratsgo/speechbook)
3. YSDA Course in Speech Processing [[code]](https://github.com/yandexdataschool/speech_course)

## Datasets
1. VGGSound: A Large-scale Audio-Visual Dataset [[paper]] [[code]](https://github.com/hche11/VGGSound)
2. CSS10: A collection of single speaker speech datsets for 10 langauges [[code]](https://github.com/Kyubyong/css10)
3. IEMOCAP: 12 hours of audiovisual data with 10 male and female actors [[website](https://sail.usc.edu/iemocap/iemocap_release.htm)]

## Aligners
1. Montreal Forced Aligner
  - For Korean [[link](https://chldkato.tistory.com/195)]
3. df

## Data (Pre)processing / Augmentation
* Data (pre)processing
1. Korean pronunciation and romanization based on Wiktionary ko-pron lua module [[code]](https://github.com/kord123/ko_pron)
2. Audio Signal Processing [[code]](https://github.com/sooftware/Audio-Signal-Processing)
3. Phonological Features (for the paper "Phonological features for 0-shot multilingual speech synthesis") [[paper]] [[code]](https://github.com/papercup-open-source/phonological-features)
4. SMART-G2P (change English and Kanji expressions in Korean sentence into Korean pronunciation) [[code]](https://github.com/SMART-TTS/SMART-G2P)
5. Kakao Grapheme to Phoneme Conversion Package for "Mandarin" [[code]](https://github.com/kakaobrain/g2pM)

* Data Augmentation
1. Audiomentations (Fast audio data augmentation in pytorch) [[code]](https://github.com/asteroid-team/torch-audiomentations)

## Other Research That May Help
* Text to Image Synthesis
  - Dalle2 [[code]](https://github.com/lucidrains/DALLE2-pytorch)
* 
