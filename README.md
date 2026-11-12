# Look, Find, and Think!

초등 영어 수업용 그림 차이 찾기·습관 선택·표현 추측 웹앱입니다.

## 파일

- `index.html`: 웹앱 실행 파일입니다. 그림, 디자인, 프로그램이 모두 들어 있습니다.
- `README.md`: 업로드 및 사용 설명서입니다.

별도 프로그램 설치, npm 빌드, API 키 설정은 필요하지 않습니다.

## GitHub에 올리기

1. ZIP을 다운로드한 다음 압축을 풉니다.
2. https://github.com 에 로그인합니다.
3. 오른쪽 위 `+` → `New repository`를 선택합니다.
4. Repository name에 `look-find-think`를 입력합니다.
5. 일반적인 무료 개인 계정에서는 `Public`으로 만들면 GitHub Pages를 이용할 수 있습니다. 이 경우 업로드한 코드와 그림은 공개됩니다. 학교·기관 정책상 공개가 가능한 자료인지 확인해 주세요.
6. `Add a README file`을 선택하고 `Create repository`를 누릅니다.
7. 저장소의 `Code` 탭에서 `Add file` → `Upload files`를 누릅니다.
8. 압축을 푼 `index.html`과 이 `README.md`를 끌어 넣습니다.
9. `Commit changes`로 저장합니다.

중요: ZIP 파일 자체나 압축을 푼 상위 폴더를 올리지 말고, 그 안의 두 파일을 올리세요. 저장소 첫 화면에 `index.html`이 바로 보여야 합니다.

## GitHub Pages 켜기

1. 저장소의 `Settings` → 왼쪽 메뉴 `Pages`를 선택합니다.
2. `Build and deployment`의 `Source`를 `Deploy from a branch`로 설정합니다.
3. Branch는 `main`, Folder는 `/ (root)`로 선택합니다.
4. `Save`를 누릅니다.
5. 게시가 완료되면 같은 Pages 화면의 `Visit site`를 누릅니다. 변경 사항 반영에는 최대 약 10분이 걸릴 수 있습니다.
6. 표시된 웹주소를 학생들에게 공유합니다.

일반적인 프로젝트 주소 형태: https://사용자이름.github.io/look-find-think/
이것은 주소 형식의 예시이며 실제 주소는 Pages 화면에서 확인해야 합니다.

## 수업에서 사용하기

- Find: Picture A와 B의 행동 차이를 찾고 Check로 정답을 확인합니다. 양치 장면은 수도꼭지와 컵을 모두 선택해야 정답입니다.
- Think: 그림에서 발견한 공통점이나 생각을 적습니다.
- Choose: My Habits 여섯 개를 고른 후 하단 My New Choices 버튼으로 이동합니다. 앞으로의 선택도 여섯 개를 고르면 Expressions로 이동합니다.
- Expressions: 첫 그림은 `use a cup`만 정답으로 인정합니다. 대소문자·앞뒤 공백·문장 끝의 문장부호 차이는 허용합니다. `use cups`는 오답입니다.
- 정답을 맞힌 경우와 정답이 공개된 경우 모두 세 번 읽기와 각 4초의 따라 읽기 시간이 끝나야 다음 그림 버튼이 활성화됩니다.
- Guess: 발견한 표현으로 단원의 주제를 추측합니다.

## 음성 및 기록

영어 음성은 브라우저와 기기의 음성 기능을 사용합니다. Chrome 또는 Edge에서 사용하고, 기기 소리와 영어 음성이 사용 가능한지 확인해 주세요. 음성 오류가 나면 다음 그림으로 진행되지 않으며 다시 듣기를 시도해야 합니다.

학생의 말하기를 마이크로 녹음하거나 발음 정확도를 평가하지는 않습니다. 세 번의 음성 재생과 따라 읽기 시간 완료를 확인합니다.

여러 학생이 같은 주소에 각각 접속할 수 있지만, 실시간으로 같은 화면을 조작하거나 교사가 전체 학생의 응답을 모아 보는 기능은 없습니다. 작성 내용과 선택 결과는 각 기기의 브라우저에 저장됩니다.

## 수정본 올리기

새 `index.html`을 같은 저장소 최상위 위치에 다시 업로드하고 `Commit changes`를 누르면 설정한 Pages 주소에 반영됩니다. 반영 후에도 이전 화면이 보이면 Ctrl+F5로 새로고침하세요.

## 문제가 생기면

- 404: 저장소 최상위에 소문자 `index.html`이 있는지, Pages의 `main`과 `/ (root)`가 맞는지 확인합니다.
- Pages 메뉴나 배포가 제한됨: 계정 플랜 또는 조직 관리자 설정을 확인합니다.
- 음성이 나오지 않음: 음소거, 탭 음소거, 영어 음성 지원을 확인한 뒤 다시 듣기를 누릅니다.

공식 문서:
- https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
