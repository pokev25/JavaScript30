# key 이벤트에 따른 css 연동 이벤트 처리

동영상 강의의 코드와 FINISHED의 코드의 차이점

- Array.from
  - log를 찍어보니 NodeList, Array로 반환되며 내용은 동일함
  - Array로 받는것이 깔끔해 보임
- this 와 e.target
  - e.target과 e.currentTarget에 대한 링크자료 참고

## css 의 transition

- transitionend  : 완료 이벤트
- ease 에니메이션을 자연스럽게 만든다.

### 참고 링크

<https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions>
<https://developers.google.com/web/fundamentals/design-and-ux/animations/the-basics-of-easing?hl=ko>
<http://lidaf.tistory.com/38>

## TIL

### vscode

#### git commit 방법

1. 소스제어로 이동
2. 변경내용 스테이징
   - 상단 + 혹은 개별 파일 + 클릭
3. 커밋 메시지 입력 후 커밋
4. 하단 동기화 버튼으로 동기화 혹은 메뉴에서 실행

<https://demun.github.io/vscode-tutorial/git/#vscode-git>

#### short cut

- 사이드바 토글 : cmd + b
- MD preview : cmd +k v

### MarkDown Lint

- vscode에 markdown 문법체크를 해서 오류를 수정 할 수 있게 해준다.
  atom 은 linter-markdown
- 정식 markdown 문서가 아니라 메모용 문서라면 귀찮을 수 있다.
  똑같아 보이는 문장 구조인데 한 문단으로 인식하지 못해서 오류를 표시할 수도 있다
- 강제 재검사 방법이 있나?
- order 와 list를 혼용 할 경우 3공백
