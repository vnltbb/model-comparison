# model-comparison
 
## 사용할 모델
- MobileNet
- ResNet
- VGG
- EfficientNet
- DenseNet
- Xception

## 사용할 데이터 셋과 클래스
|class|disease name|pathogen type|image volume|
|---|----|----|---|
|1|pepper bacterial spot|세균|약 11,000장|
|2|pepper powdery mildew|곰팡이|약 12,000장|
|3|pepper anthracnose|곰팡이|약 13,000장|
|4|Pepper Mild Mottle Virus|virus|약 54,000장|
|5|Pepper - Tomato Spotted Wilt Virus|virus|약 300장|

### 1. Plant leaf diseases 데이터셋
- 병해: bacterial spot
- 병원균: 세균(Xanthomonas campestris)
- 이미지 수: 약 1,200장
- 링크: [Plant-leaf-diseases-dataset](https://data.mendeley.com/datasets/tywbtsjrjv/1) 

### 2. Plant village 데이터셋
- 병해 : bacterial spot
- 이미지 수: 997
- 다운로드 방법: 
	- GitHub 저장소에서 ZIP 파일 형태로 다운로드: 'Download ZIP' 
	- Git 명령어: `git clone https://github.com/spMohanty/PlantVillage-Dataset.git`
	- 데이터는 MIT 라이선스로 학술 및 연구 목적으로 자유롭게 사용 가능
	- 캐글 : Plant village 

### 3. AI Hub 데이터셋
- 노지작물 질병 진단 이미지: 고추탄저병(13,145), 고추흰가루병(12,562)
- 시설작물 질병 진단 이미지: 고추마일드모틀바이러스(54,429), 고추점무늬병(9,053)

### 4. 촬영 이미지
- TSWV: 대략 300장
