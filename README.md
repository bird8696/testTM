
---

## ✅ `README.md`

```markdown
# 🧠 Teachable Machine 기반 사물 인식 프로그램

**Teachable Machine**과 **TensorFlow.js**를 활용한 웹 기반 실시간 사물 인식 프로젝트입니다.  
웹캠을 통해 사물을 인식하고, 학습된 AI 모델로 예측 결과를 화면에 시각적으로 표시합니다.


## 📌 프로젝트 소개

- 사용자가 직접 학습한 Teachable Machine 모델을 웹에서 로딩하여 **실시간으로 사물 인식**을 수행합니다.
- 웹캠을 통해 캡처된 영상을 기반으로, 사물의 이름과 예측 확률(%)을 실시간으로 출력합니다.
- 사용자의 기기에서만 동작하며, **서버 전송 없이 클라이언트에서 모든 추론이 처리**됩니다.
- 모바일/데스크탑 모두 지원 가능한 **웹 기반 머신러닝 인터페이스**입니다.


## 🌐 데모 사이트

👉 **[👉 사이트 바로가기 (클릭)](https://bird8696.github.io/testTM/index.html)**  
> 웹캠 사용 허용 후 "Start" 버튼을 누르면 작동합니다.  
> PC 또는 모바일 브라우저에서 확인 가능!


## ⚙️ 사용 기술

| 구분              | 내용                                                                 |
|-------------------|----------------------------------------------------------------------|
| **기계학습 모델** | [Teachable Machine](https://teachablemachine.withgoogle.com/)      |
| **AI 프레임워크** | TensorFlow.js                                                       |
| **프론트엔드**    | HTML5, CSS3, JavaScript (Vanilla JS)                                |
| **디자인 요소**   | 반응형 UI, 직관적인 구성, 실시간 피드백 표시                        |
| **배포**          | GitHub Pages                                                         |


## 🖼 주요 기능

- ✅ 웹캠 영상 실시간 캡처 및 화면 출력
- ✅ 학습된 모델 불러와 실시간 예측
- ✅ 예측 결과 및 확률을 시각적으로 출력
- ✅ 버튼 중복 실행 방지 처리
- ✅ 이쁘고 직관적인 UI 구성


## 📁 폴더 구조

```
testTM/
├── index.html
├── README.md
└── my_model/
    ├── model.json
    ├── metadata.json
    └── group1-shard1of1.bin
```

> `my_model` 폴더는 Teachable Machine에서 내보낸 모델 폴더입니다.


## 🧑‍💻 개발자 가이드

```bash
# 로컬에서 테스트할 경우
python -m http.server
# 또는 VSCode의 Live Server 확장 사용 가능
```

> 반드시 `http://localhost` 환경에서 테스트해야 웹캠이 정상 작동합니다.

