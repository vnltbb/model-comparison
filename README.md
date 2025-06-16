# model-comparison

## 사용할 모델
- MobileNet
- ResNet
- EfficientNet
- DenseNet

## 사용할 데이터 셋과 클래스
|class|disease name|pathogen type|
|---|----|----|---|
|1|pepper bacterial spot|세균|
|2|pepper powdery mildew|곰팡이|
|3|pepper Healthy|-|
|4|Pepper Mild Mottle Virus|virus|
|5|Pepper - Tomato Spotted Wilt Virus|virus|

### 1. Plant leaf diseases 데이터셋
- 병해: bacterial spot
- 병원균: 세균(Xanthomonas campestris)
- 다운로드 방법: 
	- GitHub 저장소에서 ZIP 파일 형태로 다운로드: 'Download ZIP' 
	- Git 명령어: `git clone https://github.com/spMohanty/PlantVillage-Dataset.git`
	- 데이터는 MIT 라이선스로 학술 및 연구 목적으로 자유롭게 사용 가능
	- 캐글 : Plant village 

### 3. AI Hub 데이터셋
- 노지작물 질병 진단 이미지: 고추흰가루병(12,562)
- 시설작물 질병 진단 이미지: 고추마일드모틀바이러스(54,429), 고추점무늬병(9,053)

### 4. 촬영 이미지
- TSWV: 대략 300장
