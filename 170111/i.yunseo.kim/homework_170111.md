- AciveX가 무엇일까?

>* 마이크로소프트사가 개발한 재사용 가능한 객체지향적 소프트웨어 구성요소 개발에 사용되는 기술.

>* AciveX는 기술을 구현하는데 필요한 구성요소를 말하며, 컴포넌트 오브젝트 모델과 객체 연결삽입을 적용해 www으로부터 다운로드 받은 컨텐츠들을 이용하는 데 사용된다.

>* AciveX Control은 AciveX를 이용해 만든 프로그램을 말한다.

>* AciveX는 거대한 프레임 워크이지만, 우리나라에서는 인터넷 익스플로러의 응용프로그램 정도로 인식 되어있다. 

- 국내 웹에 ActiveX가 정착되게 된 이유 및 배경

>* 과거 웹브라우저에 대한 미국의 자국 기술 보호 정책에 따른 보안 수준의 제한으로 인해 우리나라에서 필요한 수준의 암호화 기술의 필요성이 대두 되었고, 이를 해결하기 위해 AciveX가 사용되어진 것이 우리나라 웹브라우저(인터넷익스플로러) AciveX의 시작이라고 볼 수 있다. 

>> 과거에 미국의 자국 기술보호를 위해 해외에 제공되는 웹브라우저의 보안 수준은 40bit로 제한을 시켜 놨었다. 하지만 40bit로 제한된 상황에서 암호기술을 적용 시켰을 때 1990년대 컴퓨팅 환경 상황하에서도 3.5시간 만에 암호화를 무력화되는 허술한 체계였다. 1990년대 후반 우리나라는 인터넷 뱅킹을 도입하기 위해 더욱 안전한 암호화 기술이 필요하였는데, 미국의 제한으로 인해 곤란한 상황에 빠져 있었다. 따라서 한국인터넷진흥원에서 개발한 대칭키 암호와 알고리즘인 SEED를 개발하였다. 이 SEED는 128bit의 암호화 키를 가지는데, 문제는 당시 40bit 제한으로 인해 웹 표준에 128bit 보안을 적용 및 배포하는것이 불가능하였다. 이를 해결하기 위해 AciveX를 통해 SEED를 배포를 하게 되었고, 이것이 우리나라 AciveX 역사의 시작이 되었다.

>> 현재는 미국의 제한도 해제되고, 인터넷 익스플로러 등에 SEED 라이브러리가 제공되며, 128~256bit의 키를 가지는 표준 알고리즘인 AES가 공개되어    인터넷 뱅킹에서의 AciveX가 불필요하게 되었다. 하지만 AciveX는 사용자가 관리자 권한을 승인한다면 윈도우 폴더 내부에 파일 생성, 레지스트리 수정 등 일반적인 웹브라우저가 할 수 없는 일을 개발자 입장에서 편리하게 진행되기 때문에 계속 활용이 되었고, 이후 이러한 편리함은 바이러스와 악성 코드에 노출되는 문제를 낳게 되었다. 

- 기술적 부채 (Technical Debt)에 대해 알아보기

>1.정의

>기술 자본(관련 인력 및 기술에 투자될 수 있는 금액 등)이 많지 않은 집단이 빠르게 기술력을 개발하기 위해 개발단계에서 포기하는 많은것(테스트, 코드품질 등)들이 결국에는 그 집단에 부채로 돌아오는 현상이다.

>2.원인

>>① 비지니스 조직으로 부터의 무리한 압박

>>② 부정확한 요구사항이나 잦은 변경

>>③ 잘못된 의사결정 프로세스

>>④ 부족한 협업

>>⑤ 부족한 테스팅

>>⑥ 부족한 문서화

>>⑦ Refactoring 지연

>>⑧ 낮은 수준의 아키텍쳐 설계

- 위 내용을 조사하면서 느낀점

>현재 우리나라에서 AciveX로 인한 문제는 기술적 부채가 쌓이면서 나타난 문제라고 느껴졌다.

>회계에서 가장 중요한 기본 지식은 `자산 = 자본 + 부채`이다. 부채는 기업의 재무구조에 있어서 가장 기본적인 요소이다. 줄일 수 있지만, 없애는것은 불가능하다(부채가 없다고 건전한 회사로 불 수 있지는 않다). 문제는 부채비율((부채/자본)*100)이 높아지는것이 문제이다. 일반적으로 부채비율이 200%정도 까지는 안정적이라고 보지만 높아질수록 기업의 안정성은 낮아지고 400%를 넘으면 부실기업으로 본다. 
>즉, 부채가 자기자본으로 감당할 수 없는 상황에 직면 하게 되면 부실기업이 된다는 말이다.

>기술자본 또한 마찮가지이다. 어떤 개발을 하게 되어 결과물을 도출하여야할 때 한정된 자원내에서 기술 부채는 필수적으로 나타날 수 밖에 없다고 본다. 

>하지만 AciveX의 문제는 이 기술 부채가 기술 자본을 넘어서서 나타난다고 보는것이다.

>과거의 관행, 기존 사업과 연속성, 잘못된 정책 등으로 인해 발생한 기술적 부채는 결국 우리 모두를 옭죄고 있는 것이다.

>일례로 AciveX와 같이 많이 등장하는 것은 공인인증서 이다. 이미 페이팔과 같은거래를 할 때 우리는 공인인증서와 같은 복잡하고 짜증나는 작업을 거치지 않아도 된다. FDS(Fraud Detection System)로 이상 거래를 감지하여 이상이 있으면 바로 차단을 해버리고 인터넷 결제 등에 관한 사고는 회사에서 책임을 지는것으로 된다. 하지만, 우리나라의 경우 공인인증서와 보안관련 AciveX를 줄줄 끌어다 놓고서는 금융사고가 발생하였을 경우 은행이 책임이 아닌 사용자의 책임으로 해버린다. 

>이 기술적 부채는 이미 기술 자본을 넘어서서 사회 문제가 되지만, 이미 감당할 수 있는 부채비율을 넘어 섰기에 쉽게 되돌아오기 힘든것이다.
