# 🚀 GitHub Fork Cleaner (Cyber-Tech Edition)

![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)
![Version: 2.0.0](https://img.shields.io/badge/Version-2.0.0-cyan.svg)
![Platform: Web](https://img.shields.io/badge/Platform-Web-brighgreen.svg)

**"우후죽순 쌓인 수백 개의 포크(Fork) 리포지토리, 이제는 전문적으로 진단하고 일괄 삭제하십시오."**

이 프로젝트는 브라우저 기반의 오픈소스 도구로, 복잡한 설치 과정 없이 HTML 파일 하나만으로 작동합니다. **Cobra Command Center** 스타일의 테크니컬 UI를 통해 리포지토리를 상세 분석하고, 수백 개의 유닛을 단 몇 초 만에 정화(Purge)할 수 있습니다.

---

## 📺 SYSTEM OPERATION DEMO

<div align="center">
  <video src="demo.mp4" width="100%" autoplay loop muted playsinline style="border: 1px solid #4a3512; border-radius: 8px;"></video>
  <p><i>[분석 - 필터링 - 일괄 삭제] 프로세스 시뮬레이션</i></p>
</div>

---

## ✨ 핵심 기능 (Core Protocols)

* **Cyber-Tech Interface:** Amber/Orange 톤의 다크 테크니컬 UI로 몰입감 있는 관리 환경 제공.
* **Deep Analysis:** 리포지토리 선택 시 `README.md` 본문과 이미지를 즉시 파싱하여 실시간 프리뷰 출력.
* **Auto-Pagination:** GitHub API 제약을 우회하여 200개, 500개 그 이상의 리포지토리도 끊김 없이 자동 로드.
* **Smart Filtering:** 언어별, 이름별 필터링과 전체 선택 기능을 통해 타겟 유닛을 신속하게 확보.
* **Safe Purge Sequence:** 사용자 ID를 자동 인식하여 본인 계정의 경로만 정확히 타격하여 삭제.
* **Zero-Server Security:** 입력한 토큰은 서버로 전송되지 않으며, 오직 당신의 브라우저 로컬 메모리 내에서만 작동합니다.

---

## 🛠️ 사용 방법 (Usage)

1.  **도구 실행:** 아래 배포된 URL 링크를 통해 시스템에 접속합니다.
    > **[🚀 시스템 온라인 접속하기](https://사용자ID.github.io/repo-name/)**
2.  **권한 획득:** GitHub에서 `delete_repo` 권한이 포함된 [Personal Access Token(Classic)](https://github.com/settings/tokens)을 발급받으십시오.
3.  **시스템 연결:** 토큰을 입력하고 `INITIALIZE_CONNECTION`을 클릭하여 전체 포크 목록을 스캔합니다.
4.  **타겟 선택:** 리스트를 검토하며 삭제할 유닛을 체크합니다. (상단 ALL 체크박스로 일괄 선택 가능)
5.  **영구 정화:** 빨간색 `PURGE_UNITS` 버튼을 눌러 정화 시퀀스를 시작합니다. 좌측 패널에서 실시간 삭제 로그를 확인할 수 있습니다.

---

## 🔒 보안 및 개인정보 (Security)

본 시스템은 **클라이언트 사이드(Client-Side)** 도구입니다. 
- 모든 통신은 GitHub API 서버와 사용자의 브라우저 간에 직접 이루어집니다.
- 어떠한 데이터나 토큰 정보도 외부 서버로 수집되지 않습니다.
- 오픈소스 코드로 공개되어 있어 누구나 보안 안정성을 검토할 수 있습니다.

---

## 📄 라이선스 (License)

이 프로젝트는 **MIT License**를 따릅니다. 누구나 자유롭게 수정하고 배포할 수 있습니다.

---
<div align="center">
  <b>Developed for Efficient Developer Workflow.</b><br>
  <i>Clean your GitHub, Clean your Mind.</i>
</div>