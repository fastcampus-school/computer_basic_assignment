##ActiveX 란?
COM(컴포넌트 오브젝트 모델)과 OLE(오브젝트 링킹 앤 임베딩) 기술 두 개를 합쳐서 이름을 새로 붙여준 것.

마이크로소프트의 웹브라우저인 인터넷익스플로러(Internet Explorer)용 플러그인

####장점
액티브엑스의 가장 큰 장점이라면 서비스 제공자의 편의성이 매우 높다는 점이다. 액티브엑스가 설치되면 사용자의 PC에서 이를 실행하는 것 만으로 손쉽게 웹사이트와 기능이 연동되므로, 웹사이트 쪽에서 사용자 PC의 기능을 제어하는 과정도 매우 간편하다.

####단점
마이크로소프트의 인터넷익스플로러에서만 쓸 수 있다.
또한 사용자의 PC에 직접 설치된다는 액티브엑스의 특징을 악용해 악성코드를 심거나 개인정보를 유출하는 경우도 종종 발생하고 있으며, 액티브엑스를 설치하는 과정에서 사용자가 원하지 않는 기능까지 함께 설치하는 경우도 많다.




##국내 웹에 ActiveX가 정착되게 된 이유와 배경
한국에서 인터넷 뱅킹이나 인터넷을 이용한 다양한 금융 거래들이 활발해지면서 국가기관이 보안의 필요성을 느끼고 보안 지침을 내리게 됩니다. 문제는 보안 지침 중 암호화 알고리즘을 국내 기술로 된 것으로 한정을 지었습니다. 그러나 기반이 되는 웹브라우저가 국내 기술로 된 것이 아닌 MS의 IE가 대다수였고 그 외의 웹브라우저 역시 엔진 자체가 IE 기반이던지 아니더라도 해외 웹브라우저였기 때문에 국내 암호화 알고리즘을 자체적으로 지원해줄 수 있는 방법이 없었습니다. 결국 플러그인 방식을 도입했으며 가장 많이 사용하는 윈도 기반의 IE에서 동작하기 위해 ActiveX를 쓸 수 밖에 없었고 보안 서비스의 특성상 지속적인 안정화를 이루면서 지금에 이르게 된 것 입니다.



##'기술적 부채(Technical Debt)'란?
기존의 결함들로 인하여 새로운 기능을 개발하는데 어려움이 생기는 것.
기존의 기술들을 개발할 때에 많은 노력이 필요했을 것이고 이는 많은 발전을 이뤘을 것 입니다. 
그러나 보다 많은 발전을 위해 새로운 기능을 개발해야하는데 새로운 기능을 개발함에 있어서 정착되어 있는 기존의 기능에 방해가 되어 새로운 기능 개발에 악영향을 끼치는 거라 생각되네요.

##느낀 점.
ActiveX의 경우, 국가기관 사이트를 이용했을 때 많은 불편함을 느낀 경험이 있습니다. 항상 사이트를 이용할 때마다, 크롬으로 사이트를 이용했을 때 사이트가 정상적으로 작동되지 않았을 때, **'도대체 왜 이렇게 불편하도록 만들었는 가'**에 대해 많이 생각해 본 적이 있었습니다. 그러나 과제를 통해 ActiveX가 정착된 이유에 대해서 생각해보게 되었습니다. 아직도 많은 사람들이 IE를 사용하고 있지만 확실히 ActiveX는 없어져야 할 부분이고 IE가 아닌 다른 프로그램으로도 편하게 사용할 수 있는 환경이 구축되어야한다고 생각합니다.