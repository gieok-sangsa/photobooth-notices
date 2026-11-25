# photobooth-notices

기억한장 부스 PC가 확인하는 **사용 중지 목록**입니다.

- `revoked.txt` : 기억상사 발급 키로 서명된 목록입니다. 서명이 맞지 않으면 부스 PC는 무시합니다.
- 목록은 `관리자용\기억한장_소스\scripts\make_notice.py revoke / unrevoke` 로만 바꿉니다. 이 파일을 손으로 고치지 마세요.
- 개인정보나 비밀 키는 들어 있지 않습니다. 기기 코드만 있습니다.
