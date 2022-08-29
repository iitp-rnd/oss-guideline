# 공개SW R&D 실무수행 가이드라인 1.0

<p align="center"><img src="/assets/cover.jpg" width="750px" alt="공개SW R&D 실무수행 가이드라인 1.0" title="공개SW R&D 실무수행 가이드라인 1.0"></p><br>

Open Source Software R&D Projects의 수행에 참고하는 IITP의 공개SW R&D 실무수행 가이드라인 1.0 입니다. <br>
+ [가이드라인 목차 바로가기](#content)
+ [IITP_OSS-Guideline_V1.0.1 화일 다운로드](https://github.com/iitp-rnd/oss-guideline/blob/main/IITP_OSS-Guideline_V1.0.1.pdf)
<hr>
<br>

## <보도자료 주요내용>

- 정부는 정보통신기술 연구개발 전담기관인 정보통신기획평가원(IITP)과 함께 연구개발 현장의 의견을 청취하고 공개 소프트웨어 방식의 연구개발을 수행 중인 연구원의 노하우 등을 반영, 실제 연구 수행 과정에서 참고할 수 있는 가이드라인을 개발하였다.

    + 이번 가이드라인은 공개 소프트웨어 연구개발을 수행 전(前)과 수행 중 단계로 구분하고, 단계별로 연구자가 검토해야 하는 항목들을 순서대로 설명함으로써, 가이드라인 순서대로 따라가면 연구개발을 수행할 수 있도록 제작되었다.
    + 또한, 접근성을 높이기 위해 현장에서 빈번하게 발생하는 질의사항들을 질의응답으로 정리하고, 수행 단계에서는 이해하기 쉽도록 공개 소프트웨어 방식의 연구개발이 진행 중인 실제 사례를 제시하였다.

- 수행 전 단계에서는 공개 소프트웨어 연구개발의 목적, 영리 목적의 연구개발 시 적용 가능한 사업 모델, 라이선스 정책 및 외부 공개 소프트웨어 활용 시 리스크 관리 등 연구개발을 수행하기 전 단계에서 미리 검토되어야 하는 사항들을 해설하였다
 + 수행 단계에서는 준비→분석→검증→확산에 이르기까지 공개 소프트웨어 연구개발의 모든 단계에서 실무자가 검토해야 할 사항들을 해설하였다.
<hr>
<br>

본 가이드라인의 목차 구성은 다음과 같습니다.<br>

가이드라인은 공개SW R&D를 계획하고 수행하는 기업 및 연구소, 대학의 연구책임자 및 연구원들에게 도움을 주고자 크게 2개 파트로 구성하고 있습니다. <br>

 - <a href="#part1">첫 번째 파트</a>는 연구를 수행하기 전에 사전 연구계획 준비과정에서의 정책 수립시 검토할 사항을 제시하고, <br>
 - <a href="#part2">두 번째 파트</a>에서는 연구 수행 중에 발생하는 실무자의 궁금한 점을 모아서 연구개발 단계별로 따라할 수 있도록 구성하고 있습니다. <br>
 - 또한, 파트별로 자주 묻는 질문을 FAQ로 구성하여 설명하고 있습니다.<br>
    
<br>
&nbsp;&nbsp;+ 공개SW R&D 과제를 준비하는 과정에서 어떤 항목을 검토해야 하는지 궁금한 사항은 “[파트 1] 2장 1. 공개SW R&D 계획수립의 단계별 검토사항 개요”를 참고하세요.<br>
&nbsp;&nbsp;+ 프로젝트에 적합한 오픈소스 라이선스를 어떻게 결정해야 하는지 궁금한 사항은 “[파트 1] 2장 3. 2단계 공개SW R&D 라이선스 정책수립 단계”를 살펴보세요.<br>
&nbsp;&nbsp;+ 공개SW R&D과제의 기술이전을 준비하는 과정에서 어떤 유형을 검토해야하는지 궁금한 사항은 “[파트 1] 2장 5. 공개SW R&D 기술이전시의 검토사항”을 참고하세요.<br>
&nbsp;&nbsp;+ 프로젝트의 소스코드를 어떻게 관리해야 하는지 궁금한 사항은 “[파트 2] 2장 4. 공개SW R&D 과제 구현”을 통해 프로젝트의 개발방법론, 형상 관리, 커밋, 이슈, 릴리즈 등의 과정을 알아보세요. 이 내용에는 공개SW 프로젝트의 업스트림 개발과정 및 소프트웨어 소스 코드 형상 관리와 지속적 통합 환경을 구축하고 프로젝트를 관리하는 방법을 설명하고 있습니다.<br>
&nbsp;&nbsp;+ 공개SW R&D는 어떤 항목을 성과지표로 관리해야 하는지 궁금한 시항은 “[파트 2] 2장 5. 공개SW R&D 과제 검증”을 살펴보세요.<br>


<hr>
<br>  

## <a id="content" href="#">목차</a>
+ ### <a id="part1" href="https://github.com/iitp-rnd/oss-guideline/tree/main/part1">(파트1) 사전 준비단계</a>
+ [가이드의 대상 및 구성](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/target-configuration.md)
+ [용어 설명](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/terms-definition.md)
+ 1장. 공개SW R&D의 개요<br>
  - [1. 일반SW R&D와 공개SW R&D의 차이점](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/01/01.md)
  - [2. 공개SW R&D 개요 및 기대효과](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/01/02.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개SW R&D의 개요<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 공개SW R&D의 기대효과<br>
+ 2장. 공개SW R&D 계획수립의 단계별 검토사항
  - [1. 공개SW R&D 계획수립의 단계별 검토사항 개요](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/02/01.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개SW R&D 계획수립의 검토 단계<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 공개SW R&D 계획수립의 검토 절차<br>
  - [2. 공개SW R&D 추진전략 및 사업모델 수립단계](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/02/02.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개SW R&D 추진전략 수립<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 공개SW R&D 사업모델<br>
  - [3. 공개SW R&D 라이선스 정책수립 단계](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/02/03.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개SW R&D에 적용할 공개SW 라이선스 분류기준<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 사업화를 위한 공개SW R&D의 사업모델에 따른 라이선스 정책검토<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;다. 비영리 목적의 공개SW R&D의 라이선스 정책검토<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;라. 공개SW R&D 대표 라이선스 및 호환 라이선스 정책 검토<br>
  - [4. 공개SW 사용정책 및 절차 수립단계](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/02/04.md)
  - [5. 공개SW R&D 기술이전 검토사항](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/02/05.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개 R&D 결과물의 기술이전 유형<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 공개 SW R&D 결과물의 기술이전 유형별 검토사항<br>
+ 3장. [자주 묻는 질문과 답변(FAQ)](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/03/faq.md)	<br>
+ [별첨 1. 공개SW 라이선스 의무사항](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/03/annex1.md)	<br>
+ [별첨 2. 사용·결합·통신 방식에 따른 라이선스 의무사항](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/03/annex2.md)<br>
+ [참고문헌](https://github.com/iitp-rnd/oss-guideline/blob/main/part1/03/refList.md)

<hr>

+ ### <a id="part2" href="https://github.com/iitp-rnd/oss-guideline/tree/main/part2">(파트2) 연구수행 실무단계</a><br>
+ [가이드의 대상 및 구성](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/target-configuration2.md)
+ [용어 설명](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/terms-definition2.md)
+ 1장. 공개SW R&D의 개요
  - [1. 공개SW R&D 과제란](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/01/01.md)
  - [2. 일반SW R&D와 공개SW R&D의 차이점](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/01/02.md)
  - [3. 공개SW R&D 과제의 성장 단계](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/01/03.md)
  - [4. 공개SW R&D 과제 점검표](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/01/04.md)
  - [5. 공개SW R&D의 기대효과](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/01/05.md)
+ 2장. 공개SW R&D 수행 가이드
  - [１. 공개SW R&D 과제 수행 준비](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/02/01.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 관리 정책 수립<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 수행 조직 구성<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;다. 개발환경 구축<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;라. 참여연구원 교육
  - [２. 공개SW R&D 과제 분석](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/02/02.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 요구분석 및 조사<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 공개SW 분석 및 평가
  - [３. 공개SW R&D 과제 설계](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/02/03.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개SW 연구개발과제의 소프트웨어 설계 방식<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 공개SW 연구개발과제의 소프트웨어 재사용에 대한 접근	<br>
  - [４. 공개SW R&D 과제 구현](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/02/04.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개SW R&D 과제의 개발 방법론	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 공개SW R&D 과제의 소프트웨어 형상 관리	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;다. 공개SW R&D 과제의 이슈 관리	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;라. 공개SW R&D 과제의 릴리즈 관리	<br>
  - [５. 공개SW R&D 과제 검증](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/02/05.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개SW R&D 과제의 테스트	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 공개SW R&D 과제의 성과지표 관리	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;다. 공개SW R&D 과제의 라이선스 검증	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;라. 공개SW R&D 과제의 보안 취약점 검사	<br>
  - [６. 공개SW R&D 과제의 커뮤니티 관리](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/02/06.md)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;가. 공개SW 커뮤니티의 이해	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;나. 커뮤니티 거버넌스	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;다. 커뮤니티 구성원의 고려사항	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;라. 웹사이트 및 포럼	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;마. 기여자 가이드라인	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;바. 마일스톤 및 로드맵 공유	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;사. 협력기업 관리	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;아. 지적 재산권 관리	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;자. 모니터링	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;차. 홍보	<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;카. 문서화
+ [3장. 자주 묻는 질문과 답변(FAQ)](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/03/faq.md)
+ [부록 1. 기여자 행동 강령 규약의 예](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/03/annex1.md)
+ [부록 2. 기여자 라이선스 동의서 예](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/03/annex2.md)
+ [부록 3. 기여자 가이드라인 문서 예](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/03/annex3.md)
+ [참고문헌](https://github.com/iitp-rnd/oss-guideline/blob/main/part2/03/refList.md)

<br>

## *CONTRIBUTING*

본 가이드라인의 작성 내용은 오픈소스 개발 방법을 적용하여 여러분의 기여를 통해 개선해 나갑니다.<br>

- 일반적인 GitHub Flow에 따라 수정 사항 Commit을 만들어서 Pull Request해 주세요.<br>
- 또는, 이슈를 생성하여 의견을 남겨주세요. 간단한 의견이라도 가이드라인 1.0 개선에 도움이 됩니다.<br>

<hr>
<br>

## *이 문서의 저작권*

본 저작물은 '정보통신기획평가원(IITP)'에서 2022년 작성하여 공공누리 제4유형(출처표시 + 상업적 이용금지 + 변경금지) 저작권(https://www.kogl.or.kr/info/license.do#04-tab) 으로 개방하였습니다. <br>
본 저작물은 '정보통신기획평가원(IITP),https://www.iitp.kr/kr/1/knowledge/openReference/view.it' 에서도 무료로 다운받으실 수 있습니다." <br>
<hr>
<br>
