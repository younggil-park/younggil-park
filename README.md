얼굴인식 프로그램 사용법
준비사항
1. 아나콘다 최신버전을 다운로드하여 설치한다.
2. 아나콘다 파워쉘(Anacoda Powershell Prompt(base))를 윈도우 돋보기를 선택하여 찾아서 실행한다.
3. github에서 받은 자료를 D:\face 폴더를 만들어 놓는다.
4. 아나콘다 명령창에서 d: -> cd \face 로 이동을 한다.
5. pip install opencv-python opencv-contrib-python pillow 명령을 입력하여 얼굴인식 라이브러리를 설치한다.
6. jupyter notebook을 실행한다.

단계별 설명
먼저 face 폴더에 3개의 폴더(face_dataset, face_models, face_train)를 만든다.
face_image_making_01.ipynb -> 카메라를 통해 얼굴 영상을 저장하는 프로그램 (데이터 셋을 만들기 위한)
face_train_model_making_02.ipynb -> 저장된 얼굴 영상을 학습하는 프로그램
final_face_detect_03.ipynb -> 학습 모델을 이용하여 얼굴을 인식하는 프로그램
