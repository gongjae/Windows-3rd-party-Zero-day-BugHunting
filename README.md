# Windows-3rd-party-Zero-day-BugHunting


---

## 📌 목적

- Windows Driver Model (WDM)을 기반으로 동작하는 서드파티 커널 드라이버 타겟 수집
- 로컬 권한 상승(Local Privilege Escalation) 또는 DoS(서비스 거부) 취약점 분석

---

## 📦 포함 항목

1. **설치파일 (.exe / .msi)**  
   - 소프트웨어 공식 배포 사이트나 기타 채널에서 수집된 인스톨러

2. **설치 후 생성된 드라이버 목록 (.sys)**  
   - C:\Windows\System32\drivers 또는 다른 경로에서 수집

3. **타겟 설명 README**  
   - 드라이버 명칭 및 기능 설명  
   - 공격 벡터 가능성 (IOCTL, RPC, 취약한 API 등)  
   - 과거 CVE 여부 및 ZDI 제보 이력 확인  
   - 버그 트리거를 위한 기본 사용법

---

