# 생애전환 인바디 진단

현재 나의 **생애전환 준비도**를 파악하는 웹 기반 자가진단 도구입니다. 각 질문에 답하면 준비도 점수와 종합 피드백, 추천 행동을 확인할 수 있으며 결과를 PDF로 저장할 수 있습니다.

## 🔗 배포 주소

- **Live**: https://testai-three-phi.vercel.app

## ✨ 주요 기능

- 생애전환 준비도 문항 기반 진단
- 준비도 단계별 종합 피드백 및 추천 행동 제시
- 진단 결과 PDF 저장
- 별도 설치 없이 브라우저에서 바로 사용 가능한 정적 페이지

## 🛠 기술 스택

- 순수 HTML / CSS / JavaScript (단일 파일 `index.html`)
- PDF 생성용 클라이언트 라이브러리 사용
- Vercel 정적 호스팅

## 🚀 로컬에서 실행하기

별도 빌드 과정이 없습니다. 저장소를 클론한 뒤 `index.html`을 브라우저에서 열면 됩니다.

```bash
git clone https://github.com/eklee-sangsangwoori/testai.git
cd testai
# index.html 을 브라우저로 열기
```

## 📦 배포

`master` 브랜치에 푸시하면 Vercel이 자동으로 재배포합니다.
