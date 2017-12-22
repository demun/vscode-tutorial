# 단축키

`파일 > 기본 설정 > 바로가기 키` 에서 현재 활성화된 키보드 단축키를 볼 수 있습니다 .


## 기본 편집

키	| 명령 | 명령 ID |
----------|------------|------------|
ctrl+X | 행 삭제 (빈 선택) | editor.action.clipboardCutAction
ctrl+C | 행 복사 (빈 선택) | editor.action.clipboardCopyAction
ctrl+shift+k | 행 삭제 | editor.action.deleteLines
ctrl+Enter | 아래에 선 삽입 | editor.action.insertLineAfter
ctrl+shift+Enter | 위의 선 삽입 | editor.action.insertLineBefore
alt+Down | 줄을 아래로 이동 | editor.action.moveLinesDownAction
alt+Up | 라인 이동 | editor.action.moveLinesUpAction
shift+alt+Down | 줄 바꿈 복사 | editor.action.copyLinesDownAction
shift+alt+Up | 라인 복사 | editor.action.copyLinesUpAction
ctrl+d | 다음 찾기 일치에 선택 추가 | editor.action.addSelectionToNextFindMatch
ctrl+k ctrl+d | 마지막 선택 항목을 다음 찾기 항목으로 이동 | editor.action.moveSelectionToNextFindMatch
ctrl+u | 마지막 커서 작업 실행 취소 | cursorUndo
shift+alt+i | 선택한 각 줄 끝의 커서 삽입 | editor.action.insertCursorAtEndOfEachLineSelected
ctrl+shift+l | 현재 선택 항목을 모두 선택하십시오. | editor.action.selectHighlights
ctrl+F2 | 현재 단어의 모든 항목 선택 | editor.action.changeAll
ctrl+i | 현재 행 선택 | expandLineSelection
ctrl+alt+Down | 커서를 아래에 삽입하십시오. | editor.action.insertCursorBelow
ctrl+alt+Up | 위의 커서 삽입 | editor.action.insertCursorAbove
ctrl+shift+\ | 일치하는 대괄호로 건너 뛰기 | editor.action.jumpToBracket
ctrl +] | 들여 쓰기 라인 | editor.action.indentLines
ctrl+[ | Outdent Line | editor.action.outdentLines
Home | 라인의 시작으로 이동 | cursorHome
End | 행의 끝으로 이동 | cursorEnd
ctrl+End | 파일 끝으로 이동 | cursorBottom
ctrl+Home | 파일의 시작으로 이동 | cursorTop
ctrl+Down | 스크롤 다운 | scrollLineDown
ctrl+Up | 스크롤 라인 업 | scrollLineUp
alt+PageDown | 아래로 페이지 스크롤 | scrollPageDown
alt+PageUp | 페이지 위로 스크롤 | scrollPageUp
ctrl+shift+[ | 접기 (접기) 영역 | editor.fold
ctrl+shift +] | 펼치기 (펼친 곳) 영역 | editor.unfold
ctrl+K ctrl+[ | 모든 하위 지역 접기 (접기) | editor.foldRecursively
ctrl+K ctrl +] | 모든 소구역 펼치기 (펼치기 해제) | editor.unfoldRecursively
ctrl+K ctrl+0 | 모든 지역 접기 (접기) | editor.foldAll
ctrl+K ctrl+j | 모든 지역 펼치기 (펼치기 해제) | editor.unfoldAll
ctrl+K ctrl+c | 줄 주석 추가 | editor.action.addCommentLine
ctrl+K ctrl+u | 행 주석 제거 | editor.action.removeCommentLine
ctrl+/ | 토글 라인 코멘트 | editor.action.commentLine
shift+alt+a | 차단 댓글 토글 | editor.action.blockComment
ctrl+f | 찾기 | actions.find
ctrl+h | 바꾸기 | editor.action.startFindReplaceAction
F3 | 다음 찾기 | editor.action.nextMatchFindAction
shift+F3 | 이전 찾기 | editor.action.previousMatchFindAction
alt+Enter | 모든 일치 항목을 선택하십시오. | editor.action.selectAllMatches
alt+c | 대소 문자 찾기를 토글 | toggleFindCaseSensitive
alt+r | 정규식 찾기 전환 | toggleFindRegex
alt+w | 전체 단어 찾기 토글 | toggleFindWholeWord
ctrl+m | 포커스 설정을 위해 Tab 키 사용 토글 | editor.action.toggleTabFocusMode
할당되지 않은 | 렌더링 공백을 토글합니다. | toggleRenderWhitespace
alt+z | 단어 감싸기 토글 | editor.action.toggleWordWrap


## 풍부한 언어 편집

키 | 명령 | 명령 ID |
----------|------------|------------|
ctrl+스페이스 | 트리거 제안 | editor.action.triggerSuggest
ctrl+shift+스페이스 | 트리거 매개 변수 힌트 | editor.action.triggerParameterHints
shift+alt+f | 문서 서식 지정 | editor.action.formatDocument
ctrl+k ctrl+f | 형식 선택 | editor.action.formatSelection
F12 | 정의로 이동 | editor.action.goToDeclaration
ctrl+k ctrl+i | 호버 표시 | editor.action.showHover
alt+F12 | 픽 정의 | editor.action.previewDeclaration
ctrl+k F12 | 측면 정의 열기 | editor.action.openDeclarationToTheSide
ctrl+. | 빠른 수정 | editor.action.quickFix
shift+F12 | 참조 표시 | editor.action.referenceSearch.trigger
F2 | 심볼 이름 바꾸기 | editor.action.rename
ctrl+shift+. | 다음 값으로 바꾸기 | editor.action.inPlaceReplace.down
ctrl+shift+, | 이전 값으로 바꾸기 | editor.action.inPlaceReplace.up
shift+alt+오른쪽 | AST 선택 확장 | editor.action.smartSelect.grow
shift+alt+왼쪽 | 축소 AST 선택 | editor.action.smartSelect.shrink
ctrl+k ctrl+x | 트림 공백 제거 | editor.action.trimTrailingWhitespace
ctrl+km | 언어 모드 변경 | workbench.action.editor.changeLanguageMode


## 항해

키 | 명령 | 명령 ID |
----------|------------|------------|
ctrl+t | 모든 기호 표시 | workbench.action.showAllSymbols
ctrl+g | 라인으로 이동 ... | workbench.action.gotoLine
ctrl+p | 파일로 이동 ..., 빠른 열기 | workbench.action.quickOpen
ctrl+shift+o | 기호로 이동 ... | workbench.action.gotoSymbol
ctrl+shift+m | 쇼 문제 | workbench.actions.view.problems
F8 | 다음 오류 또는 경고로 이동 | editor.action.marker.next
shift+F8 | 이전 오류 또는 경고로 이동 | editor.action.marker.prev
ctrl+shift+p | 모든 명령 표시 | workbench.action.showCommands
ctrl+shift+Tab | 편집기 그룹 기록 탐색 | workbench.action.openPreviousRecentlyUsedEditorInGroup
alt+왼쪽 | 돌아 가기 | workbench.action.navigateBack
alt+오른쪽 | 앞으로 이동 | workbench.action.navigateForward


## 편집자 창 관리

키 | 명령 | 명령 ID |
----------|------------|------------|
ctrl+shift+n | 새창 | workbench.action.newWindow
ctrl+w | 창 닫기 | workbench.action.closeWindow
ctrl+F4 | 편집기 닫기 | workbench.action.closeActiveEditor
ctrl+kf | 폴더 닫기 | workbench.action.closeFolder
할당되지 않은 | 편집기 그룹 사이주기 | workbench.action.navigateEditorGroups
ctrl+\ | 편집기 나누기 | workbench.action.splitEditor
ctrl+1 | 첫 번째 편집기 그룹에 초점 맞추기 | workbench.action.focusFirstEditorGroup
ctrl+2 | 두 번째 편집기 그룹에 초점 맞추기 | workbench.action.focusSecondEditorGroup
ctrl+3 | 세 번째 편집기 그룹에 초점 맞추기 | workbench.action.focusThirdEditorGroup
ctrl+k ctrl+왼쪽 | 왼쪽의 편집기 그룹에 초점 맞추기 | workbench.action.focusPreviousGroup
ctrl+k ctrl+오른쪽 | 오른쪽 편집기 그룹에 초점 맞추기 | workbench.action.focusNextGroup
ctrl+shift+PageUp | 왼쪽으로 편집기 이동 | workbench.action.moveEditorLeftInGroup
ctrl+shift+PageDown | 편집기 오른쪽으로 이동 | workbench.action.moveEditorRightInGroup
ctrl+k 왼쪽 | 활성 편집기 그룹을 왼쪽으로 이동 | workbench.action.moveActiveEditorGroupLeft
ctrl+k 오른쪽 | 활성 편집기 그룹을 오른쪽으로 이동하십시오. | workbench.action.moveActiveEditorGroupRight
ctrl+alt+오른쪽 | 편집기를 다음 그룹으로 이동 | workbench.action.moveEditorToNextGroup
ctrl+alt+왼쪽 | 편집기를 이전 그룹으로 이동 | workbench.action.moveEditorToPreviousGroup


## 파일 관리
키 | 명령 | 명령 ID |
----------|------------|------------|
ctrl+n | 새 파일 | workbench.action.files.newUntitledFile
ctrl+o | 파일 열기 | workbench.action.files.openFile
ctrl+s | 저장 | workbench.action.files.save
ctrl+ks | 모두 저장 | workbench.action.files.saveAll
ctrl+shift+s | 다른 이름으로 저장 | workbench.action.files.saveAs
ctrl+F4 | 닫기 | workbench.action.closeActiveEditor
할당되지 않은 | 기타 닫기 | workbench.action.closeOtherEditors
ctrl+kw | 그룹 닫기 | workbench.action.closeEditorsInGroup
할당되지 않은 | 다른 그룹 닫기 | workbench.action.closeEditorsInOtherGroups
할당되지 않은 | 왼쪽에서 왼쪽 그룹 닫기 | workbench.action.closeEditorsToTheLeft
할당되지 않은 | 그룹을 오른쪽으로 닫기 | workbench.action.closeEditorsToTheRight
ctrl+k ctrl+w | 모두 닫기 | workbench.action.closeAllEditors
ctrl+shift+t | 닫힌 편집기 다시 열기 | workbench.action.reopenClosedEditor
ctrl+k Enter | 계속 열기 | workbench.action.keepEditor
ctrl+Tab | 다음 열기 | workbench.action.openNextRecentlyUsedEditorInGroup
ctrl+shift+Tab | 이전 열기 | workbench.action.openPreviousRecentlyUsedEditorInGroup
ctrl+kp | 활성 파일의 경로 복사 | workbench.action.files.copyPathOfActiveFile
ctrl+kr | Windows에서 활성 파일 공개 | workbench.action.files.revealActiveFileInWindows
ctrl+ko | 새 창에 열린 파일 표시 | workbench.action.files.showOpenedFileInNewWindow
할당되지 않은 | 열린 파일 비교 | workbench.files.action.compareFileWith


## 디스플레이
키 | 명령 | 명령 ID |
----------|------------|------------|
F11 | 전체 화면 토글 | workbench.action.toggleFullScreen
ctrl+kz | 젠 모드 토글 | workbench.action.toggleZenMode
Escape Escape | 젠 모드에서 나가기 | workbench.action.exitZenMode
ctrl+= | 확대 | workbench.action.zoomIn
ctrl+- | 축소 | workbench.action.zoomOut
ctrl+Numpad 0 | 재설정 확대 | workbench.action.zoomReset
ctrl+b | 사이드바 토글 | workbench.action.toggleSidebarVisibility
ctrl+shift+e | 탐색기 표시 / 포커스 전환 | workbench.view.explorer
ctrl+shift+f | 검색보기 | workbench.view.search
ctrl+shift+g | 소스 제어 표시 | workbench.view.scm
ctrl+shift+d | 디버그 표시 | workbench.view.debug
ctrl+shift+x | 광고 확장 표시 | workbench.view.extensions
ctrl+shift+u | 출력보기 | workbench.action.output.toggleOutput
ctrl+q | 명령창에서 빠른 열기 | workbench.action.quickOpenView
ctrl+shift+c | 새 명령 프롬프트 열기 | workbench.action.terminal.openNativeConsole
ctrl+shift+v | 마크다운 미리보기 토글 | markdown.showPreview
ctrl+kv | 측면에 미리보기 열기 | markdown.showPreviewToSide
ctrl+` | 통합 터미널 토글 | workbench.action.terminal.toggleTerminal


## 검색
키 | 명령 | 명령 ID |
----------|------------|------------|
ctrl+shift+f | 검색보기 | workbench.view.search
ctrl+shift+h | 파일에서 바꾸기 | workbench.action.replaceInFiles
alt+c | 대 / 소문자 전환 | toggleSearchCaseSensitive
alt+w | 전체 단어 맞추기 토글 | toggleSearchWholeWord
alt+r | 정규 표현식 사용 토글 | toggleSearchRegex
ctrl+shift+j | 검색 세부 사항 전환 | workbench.action.search.toggleQueryDetails
F4 | 검색 바꾸기 열기 | search.action.focusNextSearchResult
shift+F4 | 이전 검색 바꾸기 검색 결과 | search.action.focusPreviousSearchResult
alt+Down | 다음 검색 용어 표시 | search.history.showNext
alt+Up | 이전 검색 용어 표시 | search.history.showPrevious


## 환경 설정
키 | 명령 | 명령 ID |
----------|------------|------------|
ctrl+, | 사용자 설정 열기 | workbench.action.openGlobalSettings
할당되지 않은 | 작업 공간 설정 열기 | workbench.action.openWorkspaceSettings
ctrl+k ctrl+s | 키보드 단축키 열기 | workbench.action.openGlobalKeybindings
할당되지 않은 | 사용자 스니펫 열기 | workbench.action.openSnippets
ctrl+k ctrl+t | 색상 테마 선택 | workbench.action.selectTheme
할당되지 않은 | 디스플레이 언어 구성 | workbench.action.configureLocale


## 디버그
키 | 명령 | 명령 ID |
----------|------------|------------|
F9 | 중단점 토글 | editor.debug.action.toggleBreakpoint
F5 | 디버그 시작 | workbench.action.debug.start
F5 | 디버그 확인 | workbench.action.debug.continue
ctrl+F5 | 시작(디버깅하지 않음) | workbench.action.debug.run
F6 | 중지 | workbench.action.debug.pause
F11 | 들어가기 | workbench.action.debug.stepInto
shift+F11 | 스텝 아웃 | workbench.action.debug.stepOut
F10 | 스텝 오버 | workbench.action.debug.stepOver
shift+F5 | 중지 | workbench.action.debug.stop
ctrl+k ctrl+i | 호버 표시 | editor.debug.action.showDebugHover


## 할 일 목록
키 | 명령 | 명령 ID |
----------|------------|------------|
ctrl+shift+b | 빌드 작업 실행 | workbench.action.tasks.build
할당되지 않은 | 테스트 작업 실행 | workbench.action.tasks.test












