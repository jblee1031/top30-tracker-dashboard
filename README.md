# TOP30 트렌드 대시보드 (public)

몽당연필(비밀과외TOP30) 게시글에서 파생된 데이터만 게시하는 정적 대시보드입니다.
원문 텍스트는 포함되지 않으며, [private 처리 저장소](../../private-repo)에서
자동으로 이 저장소의 `data/summary.json`(전체 기간 집계)과
`data/boards/YYYYMM.json`(월별 종목 상세)을 갱신합니다. 대시보드는 기본적으로
최신 월의 종목 상세만 불러오고, "전체 기간" 보기를 선택했을 때만 나머지 월을 추가로 불러옵니다.

## GitHub Pages 설정 (1회)

Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)`

배포 후 `https://<사용자명>.github.io/<이 저장소 이름>/` 에서 대시보드를 확인할 수 있습니다.
