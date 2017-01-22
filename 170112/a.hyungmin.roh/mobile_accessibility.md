##공인인증서 도입 배경 :lock_with_ink_pen:

- 1999년 전자서명법 발효와 인터넷 금융 거래의 증가로 새로운 보안 체계에 대한 필요성이 커졌다.  
- 당시 미국은 48비트 이상의 암호화 기술 수출을 금지했기 때문에  
국내에서 자체적으로 128비트 암호화 대칭키 알고리즘 SEED를 개발했다.  
- SEED는 온라인 표준도 아니었고 브라우저에서 지원도 하지 않아서 ActiveX릍 통해 애드온의 형태로 자리잡게 됐다. 

##공인인증서 문제점 :unlock:

1. 보안 체계가 허술한 개인 사용자에게 암호키 보관과 책임을 떠넘긴다는 점이다.  
공인인증서는 대칭키 방식을 택하고 있고 인증서 자체가 암호키 역할을 한다.  
대칭키 방식은 암호키가 유출되면 양쪽의 정보를 모두 해독할 수 있다.  
많은 인력과 보안 설비를 보유한 기업쪽보다 개인이 암호키를 보관하게 하는 것은 위험한 선택이다.  
공인인증서는 보안을 강화하기 위한 용도인데, 인증서 체계는 현시점에서 보안수준이 허술하다.  
게다가 인증서 유출로 금융범죄가 일어나도 개인의 책임으로 돌리게 된다.  

2. 보안 프로그램을 제공하는 기업들의 신뢰성이 부족하다.  
엔프로텍트와 같은 프로그램을 깔면 사용자의 컴퓨터 설정을 멋대로 바꾸는 경우가 있다.  
공인 인증서를 사용하려면 이와같은 프로그램들을 의무적으로 깔아야 하기 때문에  
보안 프로그램들 간에 충돌이 일어나기도 하고 특정 제품군을 해킹하면  
그 프로그램을 설치한 모든 사람들의 정보를 빼낼 수 있어 오히려 위험도가 더 높다.

3. 공인인증서는 표준화되지 않은 기술인 Active X를 통해 배포된다.  
액티브 X는 사용자가 주의를 기울이지 않으면 프로그램 설치/삭제까지 관여할 수 있어 악성 프로그램이나 스파이/멀웨어가 침투하기 쉽다.   

```
당시에는 좋은 기술이었으나 2007년 이를 법으로 의무화하고
친기업적인 방향으로 정책을 제정하면서 공인인증서는 천덕꾸러기가 되었다.  
2014년부터 순차적으로 의무사용을 폐지하고 있으나  
의무사용폐지는 사용하지 말라는 것이 아니라 안해도 된다라는 뜻으로 아직까지 완전한 철폐는 이루어지지 않고 있다.  
```

##App 접근성 :dolls:

- 장애인, 고령자 등 신체적 불리함을 가진 사람들과 그렇지 않은 사람들이 App 서비스를 이용할 때  
모든 사용자가 App의 정보와 기능에 동등하게 접근할수 있도록 설계하고 개발하고 자료를 편집하는 일.

- 시각, 운동성, 청각, 발작, 인지 등의 사항 등을 고려해야 한다.


##App 접근성의 현 상황 :loudspeaker:

- 스마트폰의 많은 기능은 오히려 신체적 약자들의 접근성을 제약시켰다.  
터치 기능이나 음성인식기능도 시각장애인이나 청각장애인에게는 불편하거나 쓸모없는 기능일 뿐이다. 

- 한국정보화진흥원에 따르면 2004년 장애인의 정보화 수준은 비장애인의 57.5%에 머물렀으나 2012년에는 83.4%까지 올랐다.  
하지만 모바일로 들어서면 이야기가 전혀 달라진다. 모바일 접근도는 34.1%, 역량은 27.6%, 활용도는 30.2%다.  
2005년부터 웹 접근성 개선에 공을 들여와 지금의 수준에 이르렀다면 모바일 접근성은 아직 미흡한 수준이다.

- 접근성이란 도로와 같아서 서울에서 부산까지 가는 길이 경주쯤와서 끊어졌다면  
경주에 왔다고 해도 아무런 쓸모가 없어지는 것과 마찬가지라고 한다.

- 같은 수준으로 스마트 기기를 사용할 수준이 되지 않으면 신체적 약자들에게는 안쓰는 것과 마찬가지라는 의미다.   

- 스마트폰 시대가 열리면서 다양한 앱이 쏟아져 나오고 있다.  
하지만 자신의 서비스가 장애인도 이용할 것이라는 인식이 부족하기 때문에 접근성을 고려하기란 쉽지 않다.  
여기에 장애인 이용 편의를 위해 대체 텍스트를 다는 등 추가적인 작업이 필요해  
일정에 쫓기는 개발자들이 이런 일들까지 신경쓰기란 더 어렵다.

- 대부분 장애인 접근성은 비장애인이 설계하는 경우가 많다.  
외형적으로는 접근성이 우수한 것처럼 보여도 실질적인 사용에는 제약이 따르는 서비스가 많다.  
예를 들어 날씨 앱의 경우 지역별 날씨까지 접근하는 것은 무리가 없지만  
정작 날씨의 내용에는 아무런 설명이 없는 경우가 있다

- 웹 접근성과 마찬가지로 모바일 접근성은 정보격차로 이어질 수 있다.  
모바일 스마트기기는 언제(밀착성) 어디서나(이동성) 바로(즉시성) 사용할 수 있다.  
잘만 사용하면 정보격차를 크게 해소할 수 있지만  
사용 자체에서 접근이 제한된 사람들은 더 유용한 정보에서 멀어지게 된다.  
소셜네트워크 서비스 등을 통해서도 자신의 목소리를 낼 기회가 상실되기 때문에  
모바일 정보격차는 장애인의 목소리를 여론에 반영하는 데에도 영향을 미치고 있다.

- 이를 반영해서 네이버, 다음/카카오에서는 개발할 때 접근성 검증을 마친 후 서비스를 내놓고 있다.   

- 한국정보통신기술협회에서 2011년 모바일 어플리케이션 접근성 지침 1.0을 발표했다.  
- 모바일 애플리케이션 서비스 제공자가 장애인, 고령자 등의 접근성을 보장하기 위해 지켜야 할 규정을 마련하는 데  
목적을 두고 2.0지침을 만들어 발표할 예정이다.

- 인식의 용이성, 이해의 용이성, 운용의 용이성, 견고성의 준수해야 할 4개의 원칙과  
19개의 세부 지침으로 구성될 예정이다.





