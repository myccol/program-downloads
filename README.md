# 프로그램 다운로드

프로그램 설치 파일과 포터블 버전을 내려받을 수 있는 공개 배포 페이지입니다.
아래 표에서 원하는 프로그램의 **다운로드**를 누르세요. GitHub 로그인 없이 받을 수 있습니다.

## 프로그램 목록

| 프로그램 | 설명 | 버전 | 운영체제 | 다운로드 |
|---|---|---|---|---|
| **소리상자** | AI 음성 생성 프로그램 · MSI 설치형 | 0.5.6 | Windows x64 | **[MSI 다운로드](https://github.com/myccol/program-downloads/releases/download/sorisangja-v0.5.6/Sorisangja-0.5.6-Windows-x64.msi)** · [사용설명서](https://github.com/myccol/program-downloads/releases/download/sorisangja-v0.5.6/Sorisangja-0.5.6-Quick-Start-Light-2pages.pdf) · [설치 안내](https://github.com/myccol/program-downloads/releases/tag/sorisangja-v0.5.6) |
| **Content FindAll** | 문서 검색 프로그램 · 포터블 버전 | 3.0.5 | Windows | **[ZIP 다운로드](https://github.com/myccol/program-downloads/releases/download/content-findall-v3.0.5/Content_FindAll_Ver_3.0.5_Portable.zip)** · [실행 안내](https://github.com/myccol/program-downloads/releases/tag/content-findall-v3.0.5) |

## 소리상자 설치 방법

1. 위의 **MSI 다운로드**를 눌러 설치파일을 받습니다. 파일 크기는 약 592 MiB입니다.
2. 기존 앱을 사용 중이면 종료하고 중요한 데이터를 백업한 뒤 MSI를 실행합니다.
3. 설치 후 앱의 **[모델]** 메뉴에서 사용할 AI 모델을 다운로드합니다.

Python·FFmpeg·기본 CPU 실행 구성은 포함되어 있습니다. AI 모델과 GPU 가속 구성은 앱에서 별도로 다운로드합니다. 코드 서명되지 않은 설치파일이며, 실제 설치 교체·모델 생성·GPU 동작은 미검증입니다. 제3자 라이선스 및 완전한 대응 소스 검토 미완료 상태는 [릴리즈 안내](https://github.com/myccol/program-downloads/releases/tag/sorisangja-v0.5.6)를 확인하세요.

## Content FindAll 실행 방법

1. 위의 **ZIP 다운로드**를 눌러 파일을 받습니다. 파일 크기는 약 334 MiB입니다.
2. ZIP 파일의 압축을 **모두** 풉니다. 압축파일 안에서 바로 실행하지 마세요.
3. `Content FindAll Portable` 폴더를 엽니다.
4. `Content FindAll.exe` 또는 `Content FindAll.cmd`를 실행합니다.
5. 앱에서 문서 폴더를 추가한 뒤 검색을 시작합니다.

실행 파일과 `_internal`, `node` 폴더를 함께 유지하세요. Python과 Node.js는 포함되어 있어 별도 설치가 필요하지 않습니다. 선택형 AI 모델은 앱의 모델 관리자에서 따로 다운로드합니다.

자세한 사용 안내와 변경 사항은 압축파일에 포함된 `README_PORTABLE.txt`, `UPDATE_NOTES.txt`, `DISCLAIMER_KO.md`를 확인하세요. 프로그램별 라이선스와 제3자 고지는 배포 파일에 포함된 `LICENSE` 및 `licenses` 폴더를 따릅니다.

## 이전 버전 및 공유

- **[전체 배포 버전 보기](https://github.com/myccol/program-downloads/releases)**
- 회사 게시판 등에는 **[이 다운로드 목록](https://github.com/myccol/program-downloads)** 주소를 공유하면 됩니다.
- 특정 버전의 파일 다운로드 링크는 그 버전에 고정됩니다. 새 버전이 등록되면 이 페이지의 목록을 업데이트합니다.

이 저장소는 배포 파일과 다운로드 안내를 관리합니다. 개발 소스 저장소는 별도로 관리합니다.
