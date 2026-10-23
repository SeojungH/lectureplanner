# 인강 진도 플래너

인강 사이트의 강의구성 표를 붙여넣으면 날짜별로 나눠 주고, 수강 체크·할 일·복습 노트·D-day를 관리하는 웹앱이에요.

- 기록은 쓰는 사람의 브라우저에 저장돼요. 다른 기기와는 이어지지 않아요.
- 브라우저 데이터를 지우면 기록도 사라지니, 가끔 오른쪽 위 **기록 백업**으로 파일을 받아 두세요. **불러오기**로 되살리거나 다른 기기로 옮길 수 있어요.

## 아이폰에서 앱처럼 쓰기

Safari로 이 사이트를 열고 공유 버튼 → **홈 화면에 추가**를 누르세요. 홈 화면 아이콘으로 열면 주소창 없이 전체 화면으로 열려요.

## GitHub Pages에 올리는 법

1. GitHub에서 새 저장소(Repository)를 만들어요. 이름은 예를 들어 `lecture-planner`, 공개(Public)로 만드세요.
2. 저장소 화면에서 **Add file → Upload files**를 누르고 이 폴더의 파일 6개(`index.html`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`, `README.md`)를 끌어다 놓은 뒤 **Commit changes**를 눌러요.
3. **Settings → Pages**에서 Source를 **Deploy from a branch**, Branch를 **main** / **/(root)** 로 고르고 **Save**를 눌러요.
4. 1~2분 뒤 같은 화면 위쪽에 `https://아이디.github.io/lecture-planner/` 주소가 나타나요. 이 주소를 친구들에게 보내면 돼요.
