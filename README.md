# Vue.js 학습 노트 애플리케이션

인프런 [Vue.js Endgame 강의](https://www.inflearn.com/course/vue-js-%EB%81%9D%EB%82%B4%EA%B8%B0-%EC%BA%A1%ED%8B%B4%ED%8C%90%EA%B5%90)에서 다루는 애플리케이션 소스 코드입니다.

## 기술 스택

- Vue.js 2.6.10
- Vue Router
- Vuex
- Axios
- Vue Test Utils

## 개발 환경

- [Chrome](https://www.google.com/intl/ko/chrome/)
- [Git](https://git-scm.com/downloads)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js LTS 버전(v10.x 이상)](https://nodejs.org/ko/)
- [Vue.js Dev Tools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)

💡 참고 사항 : 수업에서는 VSCode를 기준으로 설명합니다. 별도로 선호하시는 IDE가 있다면 그걸 쓰셔도 괜찮습니다 😄

## VSCode 플러그인 목록

- 색 테마 : [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl)
- 파일 아이콘 테마 : [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- 뷰 확장 플러그인 : [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- 뷰 코드 스니펫 : [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)
- 문법 검사 : ESLint, [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
- 실습 환경 보조 : [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- 기타
  - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode), [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense), [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager), [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css), [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag), [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens), [Atom Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings), [Jetbrains IDE Keymap](https://marketplace.visualstudio.com/items?itemName=isudox.vscode-jetbrains-keybindings) 등

## License & Copyright

**Copyright © 2019 Captain Pangyo**
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivs 4.0 Unported License</a>.

### vue cli 설치 페이지
```
https://cli.vuejs.org/guide/installation.html
```

### 프로젝트 설치옵션
```
Manually select features
Babel, Linter, Unit
2.x <-- Vue 2로 하시는게 중요합니다. 아직 Vue 3는 상용 서비스에 적용하기에는 무리가 있습니다.
Prettier
Lint on Save
Jest
In dedicated config files
n
```