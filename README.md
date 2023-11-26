# ios_python_2023
Python Library for iOS and iPadOS

# 修正履歴

- 修正 0000:2023/05/20

＝が消えていたので修正

arkit¥arkit_sensor_ar_ex.py

676:        self.eulerAngles = None

- 修正 0001:2023/05/20

_carnets_avaudio_recorder

改行が入っていたものを削除
frequencies, times, spectrogram = signal.spectrogram( data[:, 0], samplerate, nperseg=1024)

- 修正 0002:2023/05/20

_carnets_avfoundation_manualCapture.ipynb

改行が入っていたものを削除

imagefileName = uid +'_iso:050_timescale:{}'.format( denominator )+ext

- 修正 0003:2023/05/20

_carnets_uikit_take_pick_photo

下記行が向けていたので修正

img  = Image.open('_take.jpg')

- 修正 0004:2023/11/26
  
speech/speech_recognizer.py

self.speech_recognizer = SFSpeechRecognizer.alloc().initWithLocale(locale)

と修正
