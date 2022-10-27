# coqui_TTS_Korean_for7.1
I edit this for 7.1 internship

## <how to install>
1. pip install TTS==0.4.2
2. pip install jamo, gdown, librosa
3. conda install pytorch==1.9.0 torchvision==0.10.0 torchaudio==0.9.0 cudatoolkit=11.3 -c pytorch -c conda-forge

## what I worked
실행은 바로 된다... 다만 tts라는 명령어로 실행되는 체계이기 때문에 이걸 옮겨올 필요가 있다.
그래서 tts라는 명령어가 TTS패키지 폴더에서 bin/synthesize.py 파일이 실행되는 것임을 확인, 이 항목 중 main()부분을 노트북으로 복사해서 make_sound라는 함수로 만들어서 바로 적용이 되었다.
