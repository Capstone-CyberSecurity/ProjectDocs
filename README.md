# README
NFC LockGuard's README

# 목차

1. [프로젝트 소개](#프로젝트-소개)
2. [핵심 기능](#핵심기능)
3. [기술 스택](#기슬-스택)
4. [시스템 아키텍처](#시스템-아키텍처)
5. [코드 저장소](#코드-저장소)
6. [팀원 소개](#팀원-소개)

## 🔐 프로젝트 소개
현대의 보안 환경에서 Windows 컴퓨터는 대부분 비밀번호 입력을 통해 접근 권한을 획득한다.
다만 사용자의 컴퓨터 비밀번호가 노출될 경우 해킹 및 계정 탈취의 위험이 존재한다.
또한 공공장소나 업무 환경에서 사용자가 잠시 자리를 비울 때 보안의 공백이 생기는 경우가 발생하고 민감한 정보가 노출될 가능성이 있다. 
본 프로젝트에서는 NFC 기반의 인증 시스템을 활용하여, 특정 인증된 기기가 비콘 위에 놓였을 때만 컴퓨터를 사용할 수 있도록 한다.
인증된 기기가 비콘에서 떨어지면 즉시 컴퓨터 사용이 제한되도록 설계하고, 이를 통해 보안성을 강화하고 사용자의 편의성을 향상시키는 것을 목표로 한다.

### 핵심기능

- NFC 태그 인식을 통해 컴퓨터의 입력 장치 및 USB 포트를 실시간으로 제어
- 인증 서버와의 암호화된 네트워크 통신을 통해 인증 여부를 판단
- 인가된 사용자만이 잠금을 해제할 수 있으며 빠른 응답성과 안정적인 작동을 제공
- Python의 pynput 라이브러리를 활용하여 키보드/마우스 입력 인터셉트 기능을 수행하고 Windows 레지스트리 값 수정을 통해 USB 저장장치 드라이버를 차단

## 기술 스택

<details>
  <summary>📌 클릭해서 자세한 내용 보기</summary>

개발 환경

<img src="https://img.shields.io/badge/windows-0078D6?style=for-the-badge">
<img src="https://img.shields.io/badge/Mac%20OS-000000?style=for-the-badge&logo=macos&logoColor=white">
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white">
<img src="https://img.shields.io/badge/raspberrypi%20OS-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white">

개발 도구

<img src="https://img.shields.io/badge/VS%20code-1581C9?style=for-the-badge">
<img src="https://img.shields.io/badge/VS%20studio-8C59C6?style=for-the-badge">
<img src="https://img.shields.io/badge/Mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">

개발 언어

<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/c-A8B9CC?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/c%23-9B75D5?style=for-the-badge">
<img src="https://img.shields.io/badge/sql-005286?style=for-the-badge">

주요 기술

<img src="https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/NFC-002E5F?style=for-the-badge&logo=NFC&logoColor=white">
<img src="https://img.shields.io/badge/pynput-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/RSA-000000?style=for-the-badge">
<img src="https://img.shields.io/badge/AES--GCM-000000?style=for-the-badge">

</details>

## 시스템 아키텍처
<img width="1363" height="568" alt="image" src="https://github.com/user-attachments/assets/49363eb0-7d82-4e9d-888a-c61e348a7bb0" />



## 코드 저장소
- NFC 비콘: https://github.com/Capstone-CyberSecurity/NFC-module
- 인증 서버: https://github.com/Capstone-CyberSecurity/AuthServer
- DB 서버: https://github.com/Capstone-CyberSecurity/db-server
- 잠금 시스템: https://github.com/Capstone-CyberSecurity/input-lock


## 👥 팀원 소개
|역할|이름|Github|
|------|---|---|
|인증 시스템|김시훈|[@ihatehudwedge](https://github.com/ihatehudwedge)|
|DB 관리|박수빈|[@so0bean](https://github.com/so0bean)|
|NFC 하드웨어|박기윤|[@parkgiyun](https://github.com/parkgiyun)|
|PC 잠금 시스템|천유석|[@chunys](https://github.com/chunys)|
