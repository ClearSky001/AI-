# AI를 활용한 과일 자동분류 서비스

## 프로젝트 개요 & 성과 요약  
본 프로젝트는 **과학기술정보통신부**가 주최하고 **정보통신기획평가원, 한국정보산업연합회**가 주관하는 **2024 한이음 ICT 멘토링 공모전** 출품작입니다.  
이 GitHub Repository에는 **공모전에 출품했던 코드 및 자료 파일**들과 **공모전 이후 성능 개선 및 프로젝트 고도화에 사용된 코드**가 포함되어 있습니다.  

본 프로젝트에서는 **YOLO, EfficientDet, EfficientNet** 등의 AI 모델을 활용해 과일의 정상 여부를 실시간으로 분류하는 **자동화 시스템**을 개발했습니다.  
라즈베리파이와 아두이노를 사용하여 수집된 데이터를 실시간으로 처리하고, 웹 기반 서비스로 시각화하여 **농업 자동화 시스템**을 설계했습니다.  

**성과 요약:**  
- 2024 한이음 ICT 멘토링 공모전 **입선 수상**  
- 프로젝트 후속 연구로 **AI 모델 성능 개선** 진행  
- 공모전 보고서 및 자료는 리포지토리의 **'2024_Hanium_ICT_mentoring_competition_and_Paper' 폴더**에서 확인할 수 있습니다.

---

## 프로젝트 배경  
- **문제 인식:** 농촌의 인구 감소와 고령화로 인해 **농산물 품질 관리 자동화 시스템의 필요성**이 지속적으로 증가하고 있습니다. 기존의 수작업 품질 검사는 **효율성과 정확도 측면에서 한계**가 있으며, 이를 해결하기 위한 기술적 대안이 요구됩니다.  

- **프로젝트 목표:**  
  - **AI 기반의 과일 분류 시스템**을 개발하여 **정확한 품질 관리**와 **자동화된 생산성 향상**을 도모합니다.  
  - **정상 과일과 비정상 과일을 실시간으로 분류**하고, 결과를 웹 기반 서비스로 시각화하여 사용자가 쉽게 모니터링할 수 있도록 합니다.  

---

## **기술 스택**

- **언어**:  
  - Python  

- **프레임워크 및 라이브러리**:  
  - **PyTorch**: (공모전 이후)EfficientNet-B0 모델 설계 및 구현  
  - **TensorFlow**: YOLOv5s, EfficientDet-D0, EfficientNet-B0 모델 설계 및 구현  
  - **Scikit-learn**: 데이터 전처리
  - **OpenCV**: 이미지 전처리 및 이미지 파일들의 증강에 사용
  - **Augmentor**: 이미지 데이터 증강(좌우 대칭, 밝기, 대비, 색상 조절)

- **데이터 처리 및 분석**:  
  - **Pandas**: 데이터 조작 및 분석  
  - **NumPy**: 수치 데이터 처리 및 배열 연산
  - **Matplotlib**: 결과 시각화

- **모델 학습 관리 및 시각화**:  
  - **Weights & Biases (wandb)**: (공모전 이후)실험 및 하이퍼파라미터 튜닝 관리  

---

## 모델 학습에 사용된 이미지 데이터 파일들
- 한이음 ICT 공모전 당시 제작했던 모델들에 쓰인 데이터
  - [YOLOv5s(링크의 데이터 그대로 사용)](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification)
  - [EfficintDet-D0](https://drive.google.com/drive/u/2/folders/1AotMBlR4IlhqmpxC5WBf-SbpKsxDilvy)
  - [EfficientNet-B0](https://drive.google.com/drive/u/2/folders/1tXkCgdoUun-kd0XHSJ6oGFw6jI1e00of)
- 한이음 ICT 공모전 이후 제작한 모델에 쓰인 데이터(**Test 데이터셋의 이미지와 유사하도록 Train, Validation 데이터를 구성**)
  - [EfficientNet-B0](https://drive.google.com/drive/u/2/folders/1Tv1ODKL3YgzKIJprE9YUsFy9Nngy-45G)
 
---

## 방법론

---

## 주요 성과

---

## 개인 기여
