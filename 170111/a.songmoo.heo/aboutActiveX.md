## 1. Active-X 란 무엇일까?
처음엔 단순히 문서를 읽는 것 외에도 동영상이나 음악을 감상하거나 은행 업무를 하는 등 다양한 인터넷 이용형태가 등장하게 되었다. 
그로 인해 웹브라우저와 HTML 문서 자체만으로는 이 모든 기능을 원활히 이용할 수 없게 되었다. 때문에 웹브라우저와 연동되는 특정 프로그램을 사용자의 PC에 추가로 설치해 웹브라우저의 기능을 확장시키는 방법이 등장했다.

인터넷익스플로러를 위한 플러그인, 액티브엑스 이러한 추가 프로그램을 플러그인(plug-in)이라고 한다. 
웹브라우저용 플러그인은 다양한 종류가 존재하는데, 가장 대표적인 것은 마이크로소프트의 웹브라우저인 인터넷익스플로러(Internet Explorer)용 플러그인인 액티브엑스(ActiveX)다. 
PC용 운영체제 중 가장 높은 점유율을 가지고 있는 것이 마이크로소프트의 윈도(Windows)이고, 이 윈도에 기본적으로 내장된 웹브라우저가 
바로 인터넷익스플로러이다 보니 액티브엑스 역시 자연스럽게 웹브라우저용 플러그인의 대명사가 되었다.
액티브X(ActiveX)는 마이크로소프트사가 개발한 재사용 가능한 객체지향적인 소프트웨어 구성 요소 개발에 사용되는 기술이다.
이는 사용자가 직접 별도로 설치파일을 구해 따로 설치하는 경우도 있지만, 대부분은 인터넷 서핑 중에 특정 웹사이트에 접속해 특정 기능을 실행하고자 하면 그와 동시에 설치가 시작되는 경우가 많다. 
해당 웹사이트로부터 필요한 액티브엑스의 설치파일을 내려 받아 사용자의 PC로 설치하는 과정을 마치면 다음 접속부터는 다시 액티브엑스의 설치과정을 거치지 않고 그 기능을 쓸 수 있게 된다. 

### **거의 무한대로 기능을 확장할 수 있는 것이 가장 큰 장점**

액티브엑스의 가장 큰 장점이라면 서비스 제공자의 편의성이 매우 높다는 점이다.
액티브엑스가 설치되면 사용자의 PC에서 이를 실행하는 것 만으로 손쉽게 웹사이트와 기능이 연동되므로, 웹사이트 쪽에서 사용자 PC의 기능을 제어하는 과정도 매우 간편하다. 또한, 여러 가지 액티브엑스를 설치함에 따라 웹브라우저 및 웹사이트의 기능을 거의 제한 없이 확장할 수 있는 것도 장점이다. 실제로 멀티미디어 콘텐츠 구동용, 은행이나 주식 등 금융 거래용, 그리고 사용자의 신원을 증명하고 공문서를 출력하는 등의 기능을 
가진 관공서용 등, 셀 수 없을 정도로 많은 액티브엑스가 개발되어 쓰이고 있다.

### **호환성, 보안성 측면에서 적지 않은 부작용**

하지만 액티브엑스는 단점 또한 적지 않다. 가장 큰 단점은 마이크로소프트의 인터넷익스플로러에서만 쓸 수 있다는 점이다. 
인터넷익스플로러가 PC용 웹브라우저 시장에서 가장 높은 점유율을 차지하고 있는 것은 사실이지만, 2000년대부터 모질라의 파이어폭스(Firefox), 
구글의 크롬(chrome)과 같은 타사의 웹브라우저가 점유율을 크게 끌어올렸으며, 2011년에 들어서는 전세계 PC용 웹브라우저 시장에서 인터넷익스플로러의 점유율이 60% 이하로 떨어졌다. 
더욱이, 윈도 기반의 PC가 아닌 스마트폰이나 태블릿컴퓨터에서는 액티브엑스를 전혀 사용할 수 없으므로 접근성 면에서 명백한 한계가 존재한다. 또한, 사용자의 PC에 직접 설치된다는 
액티브엑스의 특징을 악용해 악성코드를 심거나 개인정보를 유출하는 경우도 종종 발생하고 있으며, 액티브엑스를 설치하는 과정에서 사용자가 원하지 않는 기능까지 함께 설치하는 경우도 많다. 
이 경우 인터넷 서핑 중에 갑자기 광고 창이 출력되거나 원하지 않는 웹사이트로 이동하는 등의 현상이 일어나곤 한다. 
그리고 과도하게 많은 액티브엑스를 설치한 PC는 전반적인 처리 속도가 크게 저하되는 것도 문제다.

![](https://github.com/fastcampus-school/computer_basic_assignment_171q/blob/master/170111/a.songmoo.heo/img/active-x_5.png?raw=true)

### **액티브엑스의 한계를 넘기 위한 노력**
 
윈도 XP 서비스팩 2 이후부터 나온 윈도 운영체제는 팝업 차단기능이 강화되어 사용자가 허용하지 않은 액티브엑스 설치 팝업창은 표시되지 않게 되었고, 
출처나 보안성이 분명하지 않은 액티브엑스는 아예 설치가 차단된다. 이로 인해 무분별한 액티브액스의 남용이 상당이 줄어들게 되었다. 
다만 그렇다고 하여 액티브엑스의 근본적인 문제점(호환성 부재, 성능 저하 등)이 완전히 사라진 것은 아니었으며, 일부 웹사이트는 이용자들에게 팝업 차단 기능을 해제하거나 
아예 웹브라우저의 보안 옵션 수준을 낮출 것을 요구하기도 했다.
이러한 몇 가지 단점에도 불구하고 액티브엑스는 너무나 널리 쓰이고 있기 때문에 인터넷익스플로러 외의 웹브라우저에서도 이를 사용할 수 있도록 하는 방법이 연구되기도 했다. 
대표적인 것이 파이어폭스의 플러그인 중 하나인 ‘IE탭(IE TAB)’이다. IE탭을 설치하면 파이어폭스의 기본적인 인터페이스(메뉴, 창 구성 등)를 사용하면서 인터넷익스플로러의 
엔진(프로그램의 기본적인 구동 방식)을 불러와 웹페이지를 표시할 수 있는 기능이 추가되므로 액티브엑스 역시 사용이 가능하다(다만, 100% 완벽한 호환을 보장하지는 않는다).
그리고 최근 들어 정부나 대기업에서도 액티브엑스의 과도한 사용을 자제하고 웹 표준을 권장하는 움직임을 보이고 있다. 
특히 은행에서는 액티브엑스의 설치 없이 다른 웹브라우저에서도 인터넷 금융 서비스를 사용할 수 있는 이른바 ‘오픈뱅킹’을 적극적으로 도입하는 추세다.
 그 외에도 기존의 HTML을 대신하는 새로운 웹 표준 문서 규격인 ‘HTML5’가 액티브엑스의 문제점을 극복할 수 있는 수단으로써 주목 받고 있다. 
HTML5 규격으로 개발된 웹사이트는 각기 다른 웹브라우저나 운영체제를 사용하더라도 동일하게 웹페이지를 표시할 수 있으며, 액티브엑스와 같은 플러그인의 설치 없이도 자체적으로 
음악이나 동영상의 재생이 가능하다. 또한, 개발자가 특수한 목적으로 부득이 플러그인을 추가하더라도 웹브라우저 간의 호환성 문제 발생 가능성이 거의 없는 것도 장점이다.
HTML5는 2008년에 W3C(World Wide Web Consortium: WWW의 표준을 정하는 단체)를 통해 처음 초안이 발표되었으며, 2014년 규격 확정을 목표로 개발 중에 있다.

## 2. ActiveX가 국내웹에 정착하게 된 이유와 배경

대한민국에 ActiveX가 처음 도입된 배경을 보자면 미국이 자국 기술보호 등을 이유로 해외에 제공되는 웹 브라우저 보안 수준을 40비트로 제한시켰는데 
이런 암호기술로는 인터넷 뱅킹은 꿈도 못 꿀 일이었다. 인터넷 뱅킹을 하기 위해서는 128비트급의 암호 알고리즘이 최소한의 필수 선택이었다. 이 무렵 나온 
인터넷 익스플로러 4 버전을 예로 들면 128비트 암호화 버전은 미국에서 접속해야만 받을 수 있었고, 그 이외 지역은 40비트 암호화 버전만 다운로드 가능하도록 되어 있었다. 
물론 다운로드만 접속 국가별로 제한했기에 우회 접속이나 어둠의 경로를 통한다면 128비트 암호화 버전 브라우저를 받을 수 있었다. 하지만 당시에는 VPN이나 프록시 서버가 일반화된 때가 아니었고, 
무료 배포되는 웹 브라우저를 굳이 와레즈 찾아가면서 힘들여 받을 필요도 없었다. 결국 1990년대 후반의 기술로 40비트 암호화 버전 브라우저에서 암호화가 가능한 방법을 찾아야 했다. 
40비트 암호화는 1997년의 컴퓨팅 환경에서도 겨우 3.5시간만에 깨지는 허술한 체계였고 당시의 표준이었던 DES의 56비트 암호화도 슬슬 위험해지던 시기였다. 덩달아 이게 등장하던 1990년대 후반에는 
이미 PC통신으로 이루어지고 있던 홈뱅킹 서비스에서 해킹 사고가 터진 일이 여러 차례 있어서 온라인 금융의 보안에 대한 관심도 높던 시기였다. 따라서 3-DES[4]의 112비트라도 되어야 그나마 안정성을
보장할 수 있었다. 이러한 문제를 타개하기 위해서 KISA에서는 자체적으로 128비트 키를 가지는 새로운 알고리즘의 개발에 착수하게 된 것이고 그것이 SEED라는 알고리즘이었다. 
128~256비트 키를 갖는 표준 알고리즘인 AES가 공개되어 아무나 갖다 쓸수 있는 오늘날의 기준으로 보면 별 것 아니라고 볼 수 있겠지만 당시에는 AES도 없었고 미국의 암호화 수출제한 
정책이 해금되기 전이라 SEED는 기술적으로 충분한 가치가 있었다. 급하게라도 128비트급인 SEED가 개발되어 배포되고 이를 통해서 대한민국 인터넷 뱅킹이 시작되긴 했는데, 
문제는 웹 브라우저에 당연히 지원도 안 되었고 주요 TLS/SSL 라이브러리에도 없었다. 그래서 SEED를 쓰기 위한 관련 라이브러리와 프로그램 배포를 위해서 ActiveX란 놈을 어거지로 이용하였으며, 
이게 대한민국의 ActiveX 역사의 시작이 되었다.


## **3. 기술적 부채(technical debt)란?**
사회와 각 개인들로 이루어진 소프트웨어 등의 결함에 따라서 새로운 기능을 개발하는데 장애가 발생하는 것이다. 
생산성과 마감을 위해 급한 불만 꺼나가듯이 코드를 작성하여 코드가 복잡해지고 중복성이 발생한다. 이러한 결함들로 인하여 새로운 기능들을 개발하거나 확장하는데 어려움이 발생하는데 
이 것을 기술적 부채라 한다.

##**4. 느낀점**
ActiveX를 많이 설치해봤지만 직접적으로 어떤 것인지 알아본 적은 없었다. ActiveX가 대한민국에 도입되므로써 IT의 많은 발전이 있었다는 것은 부정할 수 없다. 그러나 ActiceX는 단점 또한 많은 플러그인이다.
더불어 ActiveX를 대안할 수 있는 여러 보안시스템이 등장(https...)하였음에도 불구하고 계속해서 ActiveX를 사용하는 것은 이미 너무 많은 사용자들에게 사용되어지고 있음에 그럴 것이다. 대한민국이 IT보안을 
위해 급하게 SEED를 만들고 도입한 것이 기술적 부채의 대표적인 예가 아닐까 싶다. ActiveX에 대해서 아직 완벽하게 이해하진 못했지만 '양날의 검'인 ActiveX를 보안하기 위해서 MS에서도 여러 대안이 
나오고 있음을 알 수 있었다(HTML5). 최근에 Android SCHOOL을 참여하면서 개발에 대해 조금씩 알아가는 기분이 든다. 어떤 프로그램에도 단점이 존재할 수 있으며, 이를 끝 없이 보안하고 노력하는 것이
프로그래머의 갖춰야 할 책임감 같은 것이 아닐까 싶다.
  