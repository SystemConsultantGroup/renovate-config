# Renovate
### 개요
Renovate는 SCG 깃허브에 있는 의존성을 자동으로 최신버전으로 관리해줍니다. <br>
해당 앱은 ArgoCD에서 확인하실 수 있습니다.

### Renovate가 관리하는 레포지토리 추가하기
1. `overlays/github/config.json` 에 들어가주세요.
2. `repositories` 리스트에 `<your-name-orgs>/<repo-name>` 형태로 추가해주세요.
3. 매주 화요일 오후 4시 30분에 Renovate 앱이 자동으로 실행됩니다.

### 최초 설정
최초 1회에 한해, Renovate가 `Configure Renovate` PR을 생성합니다. 해당 PR을 머지해주세요. <br>
그 이후에는 의존성 검사를 해서 수정사항이 있으면 PR을 생성합니다

