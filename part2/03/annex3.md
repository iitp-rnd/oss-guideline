# 부록 3 기여자 가이드라인 문서 예
## Contributing to Hamonize 환영합니다!
먼저 시간을 내서 프로젝트에 참여해 주셔서 감사합니다.<br>
이 문서는 프로젝트 참여 방법에 대한 가이드라인입니다.<br>
언제든지 저희에게 여러분의 아이디어를 PR 요청으로 문서변경을 제안해주세요.<br>
<br>

+ 소스 코드 저장소
    - 하모나이즈 저장소 : https://github.com/hamonikr/hamonize
    - 하모니카 프로젝트 깃헙 : https://github.com/hamonikr/<br>
<br>

+ 개선 제안
Hamonize 프로젝트에 제안하려는 경우 최대한 상세하게 이슈에 등록해 주세요.<br>
이슈를 작성하기 전에 이미 요청이 있는지 이슈 목록을 확인해주세요.<br>
<br>

+ 버그 보고
버그 발견 시 이슈에 BUG 라벨로 정보를 제공해주세요.<br>
최대한 상세하게 작성해주시고 스크린 캡처를 첨부해주시면 더 좋습니다.<br>
<br>

+ 기여 가능한 부분
    - 개발
    - 기획 / 퍼블리싱
    - 문서
    * 참여 부분을 저희에게 알려주세요. 더욱 자세하게 알려드립니다.<br>
    이슈 또는 Slack 채널을 이용해 주세요.<br>
    #hamonize 방 : 누구나 참여할 수 있는 커뮤니티 채널<br>

<br>

- 컨트리뷰션 하는 방법<br>    
    1. Fork<br>
        Upstream Repository를 자신의 GitHub 계정으로 Fork 합니다.<br>
        <br>
    2. Clone<br>
        Fork한 Repository를 자신의 Local working directory로 Clone 합니다.<br>
        ```
        $ mkdir -p $working_dir
        $ cd $working_dir
        $ git clone https://github.com/hamonikr/hamonize.git
        ```
    3. Create a branch<br>
        개발용 branch를 생성하여 해당 branch에서 작업 및 테스트를 수행합니다.<br>
        ```
        $ cd hamonize
        $ git checkout -b myfeature
        ```
    4. Commit<br>
        수정 사항을 commit 합니다.<br>
        ```
        $ git commit -a -m '[commit message]'
        ```
    5. Push<br>
        수정 사항을 자신의 GitHub Repository에 Push 합니다.<br>
        ```
        git push origin myfeature
        ```
    6. 빌드 테스트<br>
        travis-ci 를 통해 수정한 소스 코드가 정상적으로 빌드 되는 것을 확인해주세요.<br>
            1) travis-ci.com 에 접속, github 계정으로 로그인<br>
            2) 포크한 hamonize 저장소 활성화<br>
            3) 환경변수 GITHUB_TOKEN 등록<br>
            4) release 브랜치를 작업한 브랜치의 상태로 업데이트<br>
            5) travis-ci에서 이뤄진 빌드의 상태가 'passed' 인 것을 확인<br>
    7. Pull Request 생성하기<br>
        자신의 Github Repository에서 수정 및 테스트가 완료되면, New pull request 버튼을 클릭해 Pull Request를 생성합니다.<br>Pull Request를 생성할 때, comment로 해당 이슈가 논의된 위치와 수정된 사항에 대한 설명을 포함해 주세요.

    8. CLA<br>
        생성한 Pull Request에 Contributor License Agreement 사인 방법을 안내하는 댓글이 생성됩니다.<br>안내에 따라 CLA 사인을 완료하면, Upstream Repository의 관리자가 요청된 Pull Request를 검토할 것입니다.
    9. Feedback<br>
        프로젝트 관리자가 Pull Request를 검토한 후, 수정을 요청하거나, 거절하거나, 수락할 것입니다.