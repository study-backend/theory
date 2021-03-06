## Node.js
구글의 크롬 V8 자바스크립트 엔진을 기반으로한 비동기 IO를 지원하는 고성능 네트워크 서버이며 프로그래밍 언어로 JavaScript를 사용한다. 2009년 유럽 JSConf의 라이언 달이 V8을 이용하여 자바스크립트의 강력함과 단순함을 활용한 이벤트 기반의 논블로킹 I/O를 주 컨셉으로 만든 백엔드 자바스크립트 기반 서버이다.

<h3>장점</h3>
<ul>
  <li>매우 빠른 고성능 서버: 비동기 처리로 인해 퍼포먼스가 증가한다.</li>
  <li>한가지 언어(JavaScript)를 사용: 서버, 클라이언트 모두를 개발할 수 있다.</li>
  <li>프론트엔드 개발자들이 직접 서버 개발을 할 수 있다.</li>
  <li>커뮤니티가 광범위하다.</li>
  <li>생산성이 탁월하다.</li>
</ul>

<h3>주의사항</h3>
<ul>
  <li>싱글스레드이기 때문에 하나의 작업 자체가 시간이 많이 걸리면 전체 시스템의 성능이 낮아진다.</li>
  <li>코드의 가독성이 좋지않다. (유지보수가 어려워 질 수 있음)</li>
  <li>실행을 거쳐야 에러를 확인할 수 있다.</li>
  <li>프로그래밍 컨셉이 기존의 서버사이드 컨셉과는 달라서 적응 시간이 필요하다.</li>
</ul>

<h3>적합한 어플리케이션</h3>
짧은 시간에 대량의 클라이언트 요청을 처리하는 웹 어플리케이션을 개발하기에 적합하나, CPU의 사용이 높게 필요한 어플리케이션의 경우에는 오히려 성능이 좋지 않을 수 있다. (간단하지만 많은 양의 처리를 요구하는 서버 구축에 적합)

<h3>package.json</h3>

package.jso 은 npm을 위한 정보들을 저장 해 놓은 파일이며 package.json 에서 가장 중요한 항목은 name과 version 이다. name과 version이 누락되면 패키지는 설치 할 수 없다. 또한 name 과 version을 통해서 각 패키지의 고유성을 판별한다. 즉, 패키지의 내용을 변경하려면 version을 변경해야한다.

<h3>exports와 module.exports의 차이</h3>

exports라는 단어는 import와 반대된다. 뭔가를 내보낸다는 의미이다. Node.js에서의 exports는 주로 모듈을 내보낸다. 간략히 비유해서 설명하면, C언어의 사용자 정의 헤더파일 , 자바의 라이브러리(jar) 비슷한 형태라고 할 수 있다.

## 레퍼런스
https://javafa.gitbooks.io/nodejs_server_basic/content/
