# Quest 00. Hello, git


## Introduction
* git은 2018년 현재 개발 생태계에서 가장 각광받고 있는 버전 관리 시스템입니다. 이번 퀘스트를 통해 git의 기초적인 사용법을 알아볼 예정입니다.

## Topics
* git
  * `git clone`
  * `git add`
  * `git commit`
  * `git push`
  * `git pull`
  * `git branch`
  * `git stash`
* GitHub

## Resources
* [git, 분산 버전 관리 시스템](http://www.yes24.com/24/goods/3676100?scode=032&OzSrank=1), 인사이트
* [GitHub 사용 설명서](http://www.yes24.com/24/Goods/17638082?Acode=101), 교학사
* https://try.github.io
* http://pcottle.github.io/learnGitBranching

## Checklist
* 버전 관리 시스템은 왜 필요한가요?
 * 한눈에 프로젝트 히스토리에 대한 모든 맥락과 타임라인을 알 수 있기 때문이다.
 * 소스코드를 온전하게 유지하면서 시간대에 무관하게 언제나 협업할 수 있기 때문이다. 브랜치를 이용해서 안전하게 프로덕션 코드에 아이디어를 제안할 수 있다.
 * 팀 간 소통의 장벽을 허물 수 있고, 비즈니스에 최선을 다하는데 집중할 수 있게 하기 때문이다.
* git 외의 버전관리 시스템에는 무엇이 있나요? git은 그 시스템과 어떤 점이 다르며, 어떤 장점을 가지고 있나요?
 * git 외의 버전관리 시스템에는 Subversion, Team Foundation Server, Mercurial 등이 있다. Git의 차별점 제 가지는 아래와 같다. 첫 번째, 분산형 모델이라 빠르고 오프라인으로도 작업할 수 있다. 그리고 내 작업은 나만의 작업으로 할 수도 있고 필요하다면 공개도 가능하다. 두 번째, 브랜칭과 병합이 쉽다. 빠르고 공간을 조금만 차지하기 때문에 작업 비용이 저렴해 원할 때는 언제나 브랜치를 만들 수 있고, 내가 만든 기능이나 아이디어를 메인스트림이 준비될 때까지 내 공간에서만 작업할 수 있다. 세 번째, 워크플로우가 유연하다. Git은 나만의 워크플로우를 선택할 수 있게 해주기 때문에 큰 프로젝트에서도 매우 효율적으로 작업할 수 있다. 네 번째, 공짜다.
* git의 `clone`/`add`/`commit`/`push`/`pull`/`branch`/`stash` 명령은 무엇이며 어떨 때 이용하나요? 그리고 어떻게 사용하나요?
 * clone은 원격 저장소의 복사본을 로컬에 생성할 때 이용하며, `git clone [url]`로 사용한다.
 * add는 변경된 파일들을 스테이지할 때 이용하며, `git add [file]`로 사용한다.
 * commit은 변경내역을 저장할 때 이용하며, `git commit -m "[descriptive message]"`로 사용한다.
 * push는 로컬로 만들어진 모든 commit을 원격 저장소에 업데이트할 때 이용하며, `git push [remote] [branch]`로 사용한다.
 * pull을 다른 브랜치의 변경점을 현재 브랜치에 업데이트하고 싶을 때 이용하며, fetch와 merge가 한번에 이루어지는 개념이다. `git pull`로 사용한다.
 * branch는 commit 시리즈의 이름을 설정할 때 이용하며, `git branch [branch-name]`로 사용한다.  
 * stash는 불완전한 변경 사항을 보류하고 스테이지하기 전의 상태로 복원시키고 싶을 이용하며, `git stash`로 사용한다.


## Quest
* github에 가입한 뒤, [이 커리큘럼의 github 저장소](https://github.com/KnowRe/WebDevCurriculum)의 우상단의 Fork 버튼을 눌러 자신의 저장소에 복사해 둡니다.
* [GitHub Desktop](https://desktop.github.com/)을 다운받아 설치합니다.
* Windows의 경우 같이 설치된 git shell을, MacOSX의 경우 터미널을 실행시켜 커맨드라인에 들어간 뒤, 명령어를 이용하여 복사한 저장소를 clone합니다.
  * 앞으로의 git 작업은 되도록 커맨드라인을 통해 하는 것을 권장합니다.
* 이 문서가 있는 폴더 바로 밑에 있는 sandbox 폴더에 파일을 추가한 후 커밋해 보기도 하고, 파일을 삭제해 보기도 하고, 수정해 보기도 하면서 각각의 단계에서 커밋했을 때 어떤 것들이 저장되는지를 확인합니다.
* `clone`/`add`/`commit`/`push`/`pull`/`branch`/`stash` 명령을 충분히 익혔다고 생각되면, 자신의 저장소에 이력을 push합니다.
