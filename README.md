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
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## 3단계: 깨진 사이드바 수정하기

_커밋을 잘 찾으셨습니다 :heart:_

커밋을 찾아주셔서 감사합니다! 이제 사이드바가 실제로 추가되었고, 해당 커밋에서 이루어졌다는 것을 알게 되었습니다. 이 변경과 관련하여 댓글을 사용한 계획이나 대화가 있었는지 좀 더 깊이 파헤쳐 봅시다.

이미 보았듯이, 이슈와 풀 리퀘스트의 대화는 다른 작업을 참조할 수 있지만, 맥락의 범위는 교차 링크를 넘어 훨씬 더 넓습니다. Git은 버전 관리라는 것을 기억하세요! 예를 들어, 이전 단계에서 찾은 커밋은 다음과 같은 훨씬 더 많은 정보와 연결되어 있습니다:

- 누가 커밋했는지.
- 어떤 다른 변경이 포함되었는지.
- 언제 커밋이 이루어졌는지.
- 커밋이 어떤 풀 리퀘스트의 일부였는지.

풀 리퀘스트는 커밋이 언제 발생했는지 아는 것을 넘어서 중요합니다. 커밋이 _왜_ 발생했는지 알 수 있습니다. 히스토리를 찾는 것은 누군가를 _탓하는_ 것이 아니라 더 큰 그림을 보는 것입니다. 왜 결정이 내려졌는가? 누가 관여했는가? 각 커밋의 빌드 출력과 테스트 결과는 무엇이었는가? 누가 변경을 요청하고 누가 승인했는가?

### 커밋에서 풀 리퀘스트 찾기

GitHub에서 커밋을 보면 많은 정보를 확인할 수 있습니다. 이 뷰에서 커밋이 생성된 풀 리퀘스트로의 링크도 찾을 수 있습니다. 다음 단계에서 이것을 사용합니다.

![GitHub에서 커밋을 보는 뷰의 스크린샷, 풀 리퀘스트 링크가 강조 표시됨](https://user-images.githubusercontent.com/16547949/67341250-3edbb480-f4fd-11e9-805a-6bce5a8ba2d1.png)

### :keyboard: 활동: 깨진 사이드바 수정하기

1. main 브랜치에서 [`docs/_sidebar.md` 파일을 편집](/docs/_sidebar.md)합니다.
2. 4번째 줄의 `(doc-references__.md)` 참조를 `(doc-references.md)`로 수정하여 철자를 교정합니다.
3. 이 커밋을 위한 새 브랜치 `fix-sidebar`를 선택하거나 생성하고 풀 리퀘스트를 시작합니다.
4. **base:**에 **main**이, **compare:**에 **fix-sidebar**가 선택되어 있는지 확인합니다.
5. 오른쪽의 **Assignees** 섹션을 사용하여 풀 리퀘스트에 자신을 할당합니다.
6. PR 댓글에 'Closes #2'를 추가하여 이슈 #2를 자동 연결합니다.
7. **Create pull request**를 클릭하고 약 20초 기다립니다.
8. 이 풀 리퀘스트를 머지합니다.
9. 'fix-sidebar' 브랜치를 삭제합니다.
10. 약 20초 기다린 후 이 페이지(지침을 따르고 있는 페이지)를 새로고침합니다. [GitHub Actions](https://docs.github.com/en/actions)가 자동으로 다음 단계로 업데이트합니다.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

도움받기: [토론 게시판에 글 남기기](https://github.com/orgs/skills/discussions/categories/connect-the-dots) &bull; [GitHub 상태 페이지 확인](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [행동 강령](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT 라이선스](https://gh.io/mit)

</footer>
