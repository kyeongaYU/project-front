#  BudgetMate - Front

React 기반의 **1인 가구 맞춤형 가계부 자동화 서비스** 프론트엔드입니다.  
영수증 이미지 업로드부터 소비 통계 시각화, 무지출 챌린지 UI까지 사용자 중심의 흐름을 제공합니다.

---

## 🚀 주요 기능

- ✅ 사용자 로그인 / 회원가입 화면
- ✅ OCR 기반 영수증 이미지 업로드 및 결과 표시
- ✅ 소비 항목 분류 및 수정 UI
- ✅ 소비 통계 시각화 (일/주주/카테고리별)
- ✅ 저저지출 챌린지 참여 및 리워드 확인 UI

---

## ⚙️ 실행 방법

### 로컬 개발 서버 실행 (Vite 기준)

```bash
npm install
npm run dev
````

* 기본 주소: [http://localhost:5173](http://localhost:5173)

---

# 기술 스택

| 항목         | 사용 기술                  |
| ---------- | ---------------------- |
| Language   | JavaScript (ES6+), JSX |
| Framework  | React 18               |
| Build Tool | Vite                   |
| Styling    | Tailwind CSS           |
| 상태 관리      | Context API            |
| API 연동     | Axios                  |
| 협업 도구      | Git, GitHub, Notion    |

---

# 팀원 역할 (프론트 기준)

| 이름   | 프론트 담당 영역 |
|--------|------------------|
| 유경아 | 로그인 / 회원가입 화면 구현, OCR 이미지 업로드 처리, 영수증 인식 결과 기반 가계부 화면 구현 (소비 항목 정리 및 저장 흐름 전체) |
| 김현수 | 소비 통계 시각화 UI, 저지출 챌린지 결과 확인 UI, 리워드 응답 처리 및 백엔드 연동 테스트 |


---

## 📌 추후 계획

* 🔐 로그인 상태 Context API 전역 관리
* 📱 모바일 반응형 대응
* 🧪 백엔드 API 연동 후 통합 테스트
* 🚀 Vercel 또는 Netlify를 통한 프론트 배포




