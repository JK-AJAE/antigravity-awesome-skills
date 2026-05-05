# Windows 경로 길이 제한 해결 가이드

Windows 사용자라면 스킬 설치 중 파일 경로가 너무 길어 파일명이 잘리거나 에러가 발생하는 경우가 있을 수 있습니다. (Windows 기본 제한: 260자)

## 1. 레지스트리에서 긴 경로(Long Paths) 활성화

가장 근본적인 해결 방법입니다.

1. `Win + R` 키를 누르고 `regedit`을 입력하여 레지스트리 편집기를 엽니다.
2. 다음 경로로 이동합니다:
   `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`
3. `LongPathsEnabled` 값을 찾아 더블 클릭하고 데이터를 `1`로 변경합니다.
4. 컴퓨터를 재부팅합니다.

## 2. PowerShell 명령어로 활성화

관리자 권한으로 PowerShell을 열고 다음 명령어를 실행하세요:

```powershell
New-ItemProperty -Path "HKLM:\System\CurrentControlSet\Control\FileSystem" `
-Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force
```

## 3. 짧은 설치 경로 사용

위 방법이 어렵다면, 저장소를 `C:\skills` 처럼 최대한 짧은 경로에 설치하는 것을 권장합니다.
`C:\Users\Username\Downloads\Long_Project_Name\...` 처럼 깊은 경로는 피하세요.

---
문제가 지속된다면 [GitHub Issues](https://github.com/sickn33/antigravity-awesome-skills/issues)에 제보해 주세요.
