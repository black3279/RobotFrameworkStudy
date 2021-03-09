# RobotFrameworkStudy

- Robot Framework 는 ATDD(테스트로부터 시작해서 구현을 마무리 짓는 TDD의 범위를 코드 수준에서 기능 테스트 수준까지 확장한 것) 와 인수검사 (시스템이 실제 운영 환경에서 사용될 준비가 되었는지 최종적으로 확인하는 단계) 를 위한 포괄적인 테스트 자동화 프레임이다.
- Keyword-driven 테스트 프레임 워크로 tabular 테스트 데이터 문법을 따르며 Keyword-Driven end-to-end acceptance 프레임워크라 할 수 있다.
- 확장가능성이 있고 Remote library interface 를 사용하여 RF가 작동 중이 아닌 다른 머신에서도 테스트 라이브러리를 사용할 수 있게 해준다.

<pre>
<code>
*** Test Cases ***
Demo
    Log  Hello world
</code>
</pre>

위와 같이 log 를 찍으며 Selenium 라이브러리를 사용하면 하기와 같이 사용도 가능하다.

<pre>
<code>
*** Test Cases ***
Demo
    Open Browser  https://www.google.com  ie
    Input Text  id=lst-ib  Hollywood Celebrities
    Click Button  Google Search
</code>
</pre>

<pre>
<code>

</code>
</pre>
