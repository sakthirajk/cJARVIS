# cJARVIS
Car Jacking and Road Violence Information System.  This product will listen to the conversation from car jacker (or) the violent person in the car, utilize AI and Machine Learning to determine the threat and act immediately.

Our architechture utilizes transformer based VOSK model for speech recognition and convert the audio to text.  This text is then used for prediction using a trained SVM model (Support Vector Machine).  We have used Facebook threat analysis dataset for training our model with around 150000 observations.  This model will classify whether the text that was converted from speech is a violent nature or normal conversation.  

Our idea is to integrate this product in all the cars with a microphone, so driver / passenger does not need to take any action and car will take care of making an emergency call and sending the location information for quicker action.

Primary reason for utilizing the VOSK model is, It is built on Kaldi, a well-established speech recognition toolkit, Vosk simplifies the integration of advanced speech models into applications. The decision to use Vosk is driven by its open-source nature, accuracy, and the ease with which it can be employed in various industries. 
some of the best things in Vosk are:
1. Supports 20+ languages and dialects - English, Indian English, German, French, Spanish, Portuguese, Chinese, Russian, Turkish, Vietnamese, Italian, Dutch, Catalan, Arabic, Greek, Farsi, Filipino, Ukrainian, Kazakh, Swedish, Japanese, Esperanto, Hindi, Czech, Polish, Uzbek, Korean, Breton, Gujarati, Tajik, Telugu. More to come.
2. Works offline, even on lightweight devices - Raspberry Pi, Android, iOS
3. Portable per-language models are only 50Mb each, but there are much bigger server models available.
4. Provides streaming API for the best user experience (unlike popular speech-recognition python packages).

There are lot of scope for training this product with real time conversation that is more related to carjack situation.  At this moment, it does better job with the threat identifier dataset we trained from facebook.  

Thank you for reading this and supporting our product.
