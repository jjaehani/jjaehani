<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/identity-dark.svg">
    <img src="assets/identity-light.svg" width="404" alt="이재환. 현장 업무를 분석해 AI를 쓸 곳을 정하고, 클라우드에 올려 실제로 돌아가게 만듭니다. KT AIVLE School 빅프로젝트 우수상(6인 팀), 인턴 3회, 배재대학교 사이버보안학과 졸업.">
  </picture>
  <a href="https://github.com/jjaehani/llm-fault-intake">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/demo-dark.svg">
      <img src="assets/demo-light.svg" width="404" alt="LLM 고장 접수 챗봇 시연. 접수자가 '인버터 Oc 알람 떴어요'라고 보내면 장비(인버터), 증상(과전류 트립), 증상 분류(INV-ALM-01)를 뽑고, 발생 시점과 작업 상태는 되물어 받은 뒤, 긴급도는 규칙으로 정해 접수 초안을 채웁니다. 확정은 담당자가 합니다.">
    </picture>
  </a>
</p>

<p align="center">
  <a href="mailto:jjaehani@kakao.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/btn-email-dark.svg">
      <img src="assets/btn-email-light.svg" height="36" alt="Email">
    </picture>
  </a>
  <a href="Resume_LeeJaehwan.pdf">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/btn-resume-dark.svg">
      <img src="assets/btn-resume-light.svg" height="36" alt="Resume PDF">
    </picture>
  </a>
  <a href="Portfolio_LeeJaehwan.pdf">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/btn-portfolio-dark.svg">
      <img src="assets/btn-portfolio-light.svg" height="36" alt="Portfolio PDF">
    </picture>
  </a>
  <a href="CV_LeeJaehwan.pdf">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/btn-cv-dark.svg">
      <img src="assets/btn-cv-light.svg" height="36" alt="CV PDF">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://github.com/jjaehani/llm-fault-intake">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/llm-dark.svg">
      <img src="assets/llm-light.svg" width="404" alt="LLM 고장 접수 챗봇. 개인 프로젝트, 2026. 카카오톡에 평소 말투로 증상을 보내면 LLM이 접수 항목을 뽑고, 빠진 것은 되묻습니다. 2023년 인턴 때 다룬 고장 접수 문제를 다시 풀었습니다. 요구사항, 대화 흐름, 분류표, 채점까지 혼자 설계하고 구현. 카카오 5초 제한에 맞춰 LLM 호출을 4초에서 끊고 대화는 보존. 모르는 정보는 짐작하지 않고 되묻거나 비워 둠. 카카오 i 오픈빌더, FastAPI, Gemini API, Python.">
    </picture>
  </a>
  <a href="https://github.com/jjaehani/llm-fault-intake/blob/main/docs/evaluation.md">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/record-dark.svg">
      <img src="assets/record-light.svg" width="404" alt="채점 기록. 조정용 20문장은 프롬프트를 고치며 16, 18, 19개 통과. 끝까지 남은 실패는 장비 두 개를 한 번에 말한 18번 문장. 프롬프트를 고칠 때 보지 않은 시험용 12문장은 11개 통과. 가상 데이터이고 문장 수가 적어, 실제 접수 성능은 아닙니다.">
    </picture>
  </a>
</p>

<p align="center">
  <sub>근거:
    <a href="https://github.com/jjaehani/llm-fault-intake/blob/main/docs/requirements.md">요구사항 정의서</a>,
    <a href="https://github.com/jjaehani/llm-fault-intake/blob/main/docs/evaluation.md">채점 기록</a>,
    <a href="https://github.com/jjaehani/llm-fault-intake/blob/main/src/dialog.py">대화 흐름 코드</a>
  </sub>
</p>

<p align="center">
  <a href="https://github.com/jjaehani/KT-AIVLESCHOOL-BIGproj">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/shipsay-dark.svg">
      <img src="assets/shipsay-light.svg" width="404" alt="SHIP-SAY 스마트 조선소 안전관리. KT AIVLE School 빅프로젝트, 6인 팀 우수상. 작업 허가, 안전 신고, CCTV 감시, 디지털 트윈을 묶은 조선소 안전관리 서비스에서 클라우드와 디지털 트윈 화면을 맡았습니다. ALB, ECS Fargate, RDS, CloudFront 구성과 GitHub Actions + OIDC 자동 배포. 배포 직후 로그인 실패를 curl로 추적해 CORS 허용 목록 누락 수정. 디지털 트윈을 이어받아 15개 시설 경계를 직접 따서 지도로 구현. AWS, GitHub Actions, React, Kakao Map API.">
    </picture>
  </a>
  <a href="https://github.com/jjaehani/KT-AIVLESCHOOL-BIGproj/blob/main/frontend/src/components/digitalTwin/KakaoYardMap.jsx">
    <img src="assets/shipsay-shot.png" width="404" alt="SHIP-SAY 디지털 트윈 2D 지도 화면. 위성 지도 위에 조선소 15개 시설 경계가 폴리곤으로 표시되어 있습니다. 저장된 CCTV 데이터로 시뮬레이션한 화면입니다.">
  </a>
</p>

<p align="center">
  <sub>근거:
    <a href="https://github.com/jjaehani/KT-AIVLESCHOOL-BIGproj/tree/main/infra">인프라 설계 기록</a>,
    <a href="https://github.com/jjaehani/KT-AIVLESCHOOL-BIGproj/blob/main/.github/workflows/deploy-backend.yml">배포 워크플로</a>,
    <a href="https://github.com/jjaehani/KT-AIVLESCHOOL-BIGproj/blob/main/frontend/src/components/digitalTwin/KakaoYardMap.jsx">지도 화면 코드</a>
  </sub>
</p>

<p align="center">
  <a href="Portfolio_LeeJaehwan.pdf">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/engstok-dark.svg">
      <img src="assets/engstok-light.svg" width="404" alt="고장 접수 업무 설계. 엔지니어스톡 인턴, 2023. 전화, 문자, 엑셀로 나뉘어 있던 산업장비 고장 접수를 따라가 챗봇 도입 문서로 옮겼습니다. DSC 기업애로기술 해결프로젝트 랩(장려상)에서 이어진 인턴입니다. 현행 흐름에서 문제점 3가지를 찾아 수리, 구매, 내역조회로 재설계. 요구사항정의서 기능 9개, 비기능 4개와 화면설계서를 챗봇 개발사와 작성. 자동 연동 제안을 현업 우려에 맞춰 담당자 확인 방식으로 조정. 업무 분석, 요구사항정의서, 카카오 i 오픈빌더, Figma.">
    </picture>
  </a>
  <a href="Portfolio_LeeJaehwan.pdf">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/flow-dark.svg">
      <img src="assets/flow-light.svg" width="404" alt="고장 접수 흐름 재설계. 기존에는 전화로 연락처를 남기고, 문자와 카톡으로 사진을 보내고, 다시 전화로 상담한 뒤 엑셀로 관리했습니다. 재설계에서는 카카오톡 챗봇 접수를 수리, 구매, 내역조회(신설) 세 갈래로 나누고 최종 입력은 담당자가 확인합니다.">
    </picture>
  </a>
</p>

<p align="center">
  <sub>회사 문서라 원본은 올리지 않았습니다.<br>분석과 설계 과정은 <a href="Portfolio_LeeJaehwan.pdf">포트폴리오 PDF</a> 14~20쪽에 있습니다.</sub>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/about-dark.svg">
    <img src="assets/about-light.svg" width="404" alt="AI와 일하는 방식. 맡기는 것과 확인하는 것을 나눕니다. AI에 맡긴 것: 처음 보는 코드의 모듈 구조 정리, 작업량 비교 초안. 직접 정한 것: 구현 범위와 우선순위, 3D 야드를 2D 지도로 바꾼 결정. 직접 확인한 것: 실행 화면, 로그, 채점 결과. 어긋난 지도는 15개 시설 경계를 직접 따서 고쳤습니다. LLM 결과는 초안으로 두고, 틀렸을 때 누가 고치는지부터 정합니다.">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/career-dark.svg">
    <img src="assets/career-light.svg" width="404" alt="경력과 교육. 2026.03~09 KT AIVLE School AI 트랙(840시간, 클라우드와 디지털 트윈, 빅프로젝트 우수상). 2023.07~08 엔지니어스톡 인턴(고장 접수 업무 분석, 챗봇 설계 문서). 2023.01~02 충남정보문화산업진흥원 인턴(DB 설계, 약 6,000만 건 이관과 검증). 2022.09~12 아이와즈 인턴(웹하드 침해 조사, Selenium 크롤러, 데이터 태깅). 2020.03~2024.02 배재대학교 사이버보안학과, DSC 공유대학 모빌리티 SW/AI 융합전공.">
  </picture>
</p>
