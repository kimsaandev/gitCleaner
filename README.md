# 🚀 GitHub Fork Cleaner (Cyber-Tech Edition)

![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)
![Version: 2.0.0](https://img.shields.io/badge/Version-2.0.0-cyan.svg)
![Platform: Web](https://img.shields.io/badge/Platform-Web-brightgreen.svg)

**"Analyze and purge hundreds of cluttered fork repositories professionally."**
*"우후죽순 쌓인 수백 개의 포크(Fork) 리포지토리, 이제는 전문적으로 진단하고 일괄 삭제하십시오."*

This is a browser-based open-source tool that works with a single HTML file—no complex installation required. Analyze repositories in detail and purge hundreds of units in seconds through a technical UI inspired by the Cobra Command Center.
이 프로젝트는 브라우저 기반의 오픈소스 도구로, 복잡한 설치 과정 없이 HTML 파일 하나만으로 작동합니다. Cobra Command Center 스타일의 테크니컬 UI를 통해 리포지토리를 상세 분석하고, 수백 개의 유닛을 단 몇 초 만에 정화(Purge)할 수 있습니다.

---

## 📺 SYSTEM OPERATION DEMO

<div align="center">
  <video src="demo.mp4" width="100%" autoplay loop muted playsinline style="border: 1px solid #4a3512; border-radius: 8px;"></video>
  <p><i>[Analysis - Filtering - Purge] Process Simulation</i></p>
</div>

---

## ✨ Core Protocols (핵심 기능)

* **Cyber-Tech Interface:** Amber/Orange-toned technical UI for an immersive management environment. (다크 테크니컬 UI로 몰입감 있는 관리 환경 제공)
* **Deep Analysis:** Instantly parse and preview `README.md` content and images upon selection. (리포지토리 선택 시 README 본문과 이미지를 즉시 프리뷰)
* **Auto-Pagination:** Seamlessly load 200, 500, or more repositories by bypassing GitHub API limits. (API 제약을 우회하여 수백 개의 리포지토리 자동 로드)
* **Smart Filtering:** Quickly secure target units with language/name filters and "Select All" functionality. (언어/이름 필터링과 전체 선택 기능으로 유닛 신속 확보)
* **Safe Purge Sequence:** Automatically identifies the user ID to accurately target only your own repository paths. (사용자 ID를 자동 인식하여 본인 계정 경로만 정확히 삭제)
* **Zero-Server Security:** Your token is never transmitted to any server; it stays within your browser's local memory. (입력한 토큰은 서버로 전송되지 않으며 브라우저 내에서만 작동)

---

## 🛠️ Usage (사용 방법)

1.  **Access System:** Open the deployed URL or the `index.html` file in your browser. (배포된 URL 또는 index.html 파일을 브라우저에서 실행합니다.)
2.  **Acquire Token:** Generate a [Personal Access Token(Classic)](https://github.com/settings/tokens) with `delete_repo` scope. (delete_repo 권한이 포함된 PAT 토큰을 발급받으십시오.)
3.  **Initialize:** Enter your token and click `INITIALIZE_CONNECTION` to scan all forks. (토큰 입력 후 초기화 버튼을 눌러 포크 목록을 스캔합니다.)
4.  **Target Selection:** Review the list and check the units to be deleted. (리스트를 검토하며 삭제할 유닛을 체크합니다.)
5.  **Purge:** Click the red `PURGE_UNITS` button to start the sequence. Check real-time logs in the left panel. (빨간색 버튼을 눌러 정화 시퀀스를 시작하고 실시간 로그를 확인합니다.)

---

## 🔒 Security (보안)

This is a **Client-Side** tool. All communications occur directly between the user's browser and GitHub API. No data is collected by external servers.
본 시스템은 클라이언트 사이드 도구입니다. 모든 통신은 사용자의 브라우저와 GitHub API 간에 직접 이루어지며, 외부 서버로 데이터를 수집하지 않습니다.

---

## 📄 License (라이선스)

This project is distributed under the **MIT License**.
