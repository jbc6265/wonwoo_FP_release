# 원우ENG 서열정보&소요자재 자동 취합 프로그램

## 다운로드

아래 파일을 다운로드해서 실행합니다.

- `Wonwoo_Key_Column_Merge_Planner.exe`

직접 다운로드:

https://github.com/jbc6265/wonwoo_FP_release/raw/main/Wonwoo_Key_Column_Merge_Planner.exe

## 실행 방법

1. `Wonwoo_Key_Column_Merge_Planner.exe`를 다운로드합니다.
2. 다운로드한 EXE 파일을 더블클릭합니다.
3. 화면 안내에 따라 월확정 서열정보 파일과 물류번호별 자재소요현황 파일을 선택합니다.
4. 결과 저장 폴더를 지정한 뒤 병합 엑셀을 생성합니다.

## 설치 조건

- Python 설치가 필요 없습니다.
- 별도 프로그램 설치 없이 Windows PC에서 실행합니다.
- DRM 또는 비표준 xlsx 파일을 자동 변환해야 하는 경우 Microsoft Excel이 설치되어 있어야 합니다.

## 엑셀 파일 선택 안내

SRM에서 내려받은 엑셀 파일이 보안 처리되어 있거나 표준 xlsx 구조가 아닌 경우, 프로그램이 Microsoft Excel을 이용해 임시 표준 xlsx 파일로 변환한 뒤 읽기를 다시 시도합니다.

자동 변환도 실패하면 Excel에서 해당 파일을 직접 열어 `다른 이름으로 저장(.xlsx)` 후 다시 선택합니다.

## 보안 경고 안내

Windows에서 처음 실행할 때 SmartScreen 또는 보안 경고가 표시될 수 있습니다.
이는 코드서명 인증서가 없는 사내 제작 실행 파일에서 발생할 수 있는 일반적인 경고입니다.

경고가 표시되면 파일 출처를 확인한 뒤 실행합니다.

## 배포 파일

이 저장소는 협력사 배포용 저장소이며, 실행 파일만 배포합니다.

