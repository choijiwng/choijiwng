**한국어** | [English](https://github.com/choijiwng/choijiwng/blob/main/README.en.md)

# 최지웅 (Jiwoong Choi)

상명대학교 정보보안공학과 학부생이며, 2027년 오펜시브 보안 분야 취업을 준비하고 있습니다.

## Interests

- 취약점 연구, 시스템 보안
- 모의해킹, 레드팀
- 바이너리 익스플로잇(pwnable), CTF
- AI 에이전트 보안, AI 기반 보안 도구

## Affiliation

- **상명대학교** 정보보안공학과, 2022.03 – 현재
- **WhateverTakes**, CTF 팀

## Research

### InodeFence, 2026.10 – 현재

TAR 압축 해제 전후의 파일시스템 상태를 관찰해, 추출된 파일이 추출 디렉터리 밖의 파일과 inode를 공유하는 것과 같은 보안 경계 위반을 검사하는 연구 프로토타입입니다. 팀 프로젝트입니다.

- 알려진 CVE 두 건, CVE-2026-23745와 CVE-2026-24842의 node-tar 하드링크 탈출을 통제된 환경에서 재현했습니다. 결과 기반 oracle(외부 파일과의 inode 공유) 하나로 두 건 모두 영향 릴리스와 수정 릴리스를 구분합니다. 이는 알려진 취약점의 재현이며 제가 발견한 것이 아니고, 새로운 취약점을 발견했다고 주장하지 않습니다.
- 팀 저장소의 제 커밋(Claude AI 도구로 구현)에는 재현 스크립트와 raw 증거 기록, 같은 oracle로 Python `tarfile`의 추출 정책(`fully_trusted`와 `data`)을 비교한 테스트, symlink 대상 경로 범위 판정, 데모 실행용 터미널 요약이 포함됩니다.
- 한계: 결과는 일회용 Linux 환경의 통제된 fixture에서 얻은 것입니다. 무작위 또는 기준 전략 대비 퍼저의 효과는 입증되지 않았습니다.

저장소: [TheWaitForAGI/InodeFence](https://github.com/TheWaitForAGI/InodeFence)

## Awards and Honors

- **본선 진출**, `2026 KISIA 정보보호 경진대회(본선)` as *WhateverTakes* (2026.08), [증명서](https://github.com/choijiwng/choijiwng/blob/main/certificates/2026-kisia-finals-participation.pdf)
- **우수상**, `2025 충남 IT Hackathon (초급 부문)` as *SS통합* (2025.09), [증명서](https://github.com/choijiwng/choijiwng/blob/main/certificates/2025-chungnam-it-hackathon-excellence-award.pdf)

## Projects & Write-ups

- [InodeFence](https://github.com/TheWaitForAGI/InodeFence) (2026.10 – 현재): TAR 추출 경계 위반 연구 프로토타입, 위에 설명.
- [CTF-OS](https://github.com/whatevertakes/CTF-OS) (2026.06 – 2026.08): Codex 기반 엔진으로, 사람이 고른 CTF 문제 하나를 문제 단위로 격리된 Docker 샌드박스에서 풉니다. 문제 선택과 플래그 제출은 사람이 합니다. WhateverTakes 팀의 메인 개발자이자 팀장입니다.
- [BBS](https://github.com/choijiwng/BBS) (2026.05 – 2026.06): Node.js, Express, PostgreSQL 기반 게시판으로, bcrypt 비밀번호 해싱, CSRF 방어, Helmet, rate limiting을 적용했습니다.
- [cic-ids2017-visualization](https://github.com/choijiwng/cic-ids2017-visualization) (2026.04 – 2026.05): CIC IDS 2017 데이터셋의 정상·공격 트래픽 분포를 Python으로 분석하고 시각화했습니다.
- [pwnable](https://github.com/choijiwng/pwnable) (2025.12 – 2026.02): 버퍼 오버플로, return-to-shellcode, return-to-libc, ROP, use-after-free, tcache poisoning 학습 노트와 익스플로잇 풀이.

## Contact

- GitHub: [choijiwng](https://github.com/choijiwng)
- Email: jiwoong729@gmail.com
