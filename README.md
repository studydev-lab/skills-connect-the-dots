<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280x640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280x640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub 저장소에서 단서 연결하기

_저장소를 탐색할 때 유용한 팁들._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## 1단계: 중복 이슈 해결하기

_과정에 오신 것을 환영합니다 :tada:_

GitHub에는 다른 정보를 참조하는 특별한 기능이 있습니다. 예를 들어, 다른 이슈나 풀 리퀘스트를 번호로 참조하면 해당 번호가 하이퍼링크로 변환됩니다. 동시에 참조된 이슈나 풀 리퀘스트에 교차 참조(cross-reference)가 생성됩니다. 이 양방향 참조는 GitHub 전체에서 정보의 관계를 추적하는 데 도움이 됩니다.

![이슈에서 PR을 연결하고, PR에서 이슈로의 교차 참조가 표시된 스크린샷](https://user-images.githubusercontent.com/6351798/172456846-2daec570-08b0-4ffa-a7cb-41acc50b836e.png)

여러 팀원이 협업하다 보면 이슈가 중복될 수 있습니다. 위 예시에서 새 이슈 `#8346`은 이전 이슈 `#8249`의 중복입니다. 교차 참조 기능을 통해 이러한 중복을 추적하고 적절하게 이슈를 닫을 수 있습니다.

### 참조 만들기

다른 이슈에 연결하면 GitHub 내에서 자동으로 참조가 생성됩니다. 사실 전체 링크를 포함하지 않아도 됩니다. 댓글에 `#5`를 입력하면 이슈 또는 풀 리퀘스트 번호 5로 연결되는 링크로 변환됩니다.

교차 링크를 만들려면 `#` 기호 바로 뒤에 이슈나 풀 리퀘스트 제목을 입력하세요. GitHub가 올바른 위치로 연결될 이슈나 풀 리퀘스트를 추천합니다. 더 자세한 내용은 [자동 링크 참조 및 URL](https://docs.github.com/en/articles/autolinked-references-and-urls) 문서를 확인하세요.

### :keyboard: 활동: 교차 연결된 이슈 찾아서 닫기

1. 이슈 #1 (Welcome)로 이동합니다
2. "Duplicate of #2"를 댓글로 입력하고 이슈 #1을 닫습니다
3. 약 20초 기다린 후 이 페이지(지침을 따르고 있는 페이지)를 새로고침합니다. [GitHub Actions](https://docs.github.com/en/actions)가 자동으로 다음 단계로 업데이트합니다.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

도움받기: [토론 게시판에 글 남기기](https://github.com/orgs/skills/discussions/categories/connect-the-dots) &bull; [GitHub 상태 페이지 확인](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [행동 강령](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT 라이선스](https://gh.io/mit)

</footer>
