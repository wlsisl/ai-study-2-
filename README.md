# ai-study-2-
Python

*목차*

참여하게 된 계기  
강의소개

1. 컴퓨터 구조
2. python

인공지능 스터디를 마치고

<h3><참여하게 된 계기></h3>

프로그래밍에 관심을 갖게 된 것은 대학교에 입학하기 전이다. '분석'에 더 흥미를 가지고 통계학과에 진학하였지만 프로그래밍을 늘 배우고 싶었다. 그래서 학교 교양 강의로 처음 기본을 다졌다. 학교 강의에서는 기본적으로 파이썬, HTML,프로세싱 이렇게 세가지 특징을 파악할 정도로만 공부했다. 종강을 하고 1학년 여름방학을 마주하여 가장 기본적 언어인 파이썬에 대해서 자세히 알아보고 공부하고 싶었다. 내가 관심있는 내용을 하루 하루 공부하며 채워나가고 다른 사람들과 발표를 통해 공유하고 싶다고 생각했었다. 그런데 마침 학교 커뮤니티에 인공지능 글쓰기 스터디 회원 모집 공고가 올라왔고 참여하게 되었다. 항상 프로그래밍 공부할 때 명령어를 배우고 따라 작성하는 것 외에 접해본 적이 없어서 어떻게 스스로 학습하고 문제풀이를 진행할 수 있는지 궁금했다. 파이썬에 입문하기 앞서 제대로 알아가고 싶었던 점들을 작성하며 이를 중점으로 공부하려 다짐했고, 좋은 기회가 있어 참여하게 되었다.

<h3><인공지능 강의></h3>
   
이번 인공지능 스터디에서는 컴퓨터 구조학습을 통해 프로그래밍을 하는 이유를 알아보고 파이썬 언어를 배우며 실습하는 과정을 거친다. 해당 내용은 2021년 여름방학 전남ict이노베이션 인공지능 강의를 통해 진행된 점을 알린다.

먼저 컴퓨터 구조를 배운다. 프로그래밍에 앞서 컴퓨터 구조를 알아보는 이유는 프로그래밍이 이루어지는 컴퓨터의 특징을 먼저 파악하고자 이다. 기본개념은 무엇이고 왜 컴퓨터에게 명령해야 하는지를 알고 프로그래밍 언어를 배우면 더 효과가 좋기 때문에 컴퓨터 구조를 먼저 학습했다.

<h2>컴퓨터 구조</h2>
*기계어(Machine Languag e): 0과 1로 표현된 언어*
*어셈블리어(Assembly Language): 기계어와 일대일 대응하는 언어*
*고급언어(High Level Language): 인간 입장에서 컴퓨터에게 명령을 내릴 수 있도록 구성된 언어*

컴퓨터는 인간이 사용하는 언어를 알아먹을 수 없다. 그래서 우리들이 사용하는 언어를 컴퓨터가 알아볼 수 있는 언어로 바꿔줘야한다.

<h4>Hardware</h4>
cpu와 memory, i/o device가 연결되어있다.

CPU(Central Processing Unit): 산술연산/관계연산/논리연산
연산 자체는 담당하지만 기억기능이 없다.
   ALU(Arithmetic Logical Unit):연산
  
   CU(Control Unit):제어   
   
   Register:임시 기억 장소   
Memory: 프로그램(명령의 집합)이나 데이터(값)를 기억  
   RAM(Random Access Memory): 주로 사용하는 메모리, 전원이 연결된 상태에서만 저장, 읽기/쓰기 모두 가능
   
   ROM(Read Only Memory): 기억기능밖에 없어서 RAM에 복사되어 사용된다. 속도가 느리다.
   
I/O(input/output)Device:입/출력 장치
   input Deice(입력장치): 키보드, 마우스, 마이크, 카메라 등을 말한다. 
**입력내용은 Memory에 저장된다.**
   
   Output Device(출력 장치):모니터, 스피커, 출력내용은 Memory에 있는 내용을 출력한다.(그러니까 컴퓨터 하드웨어 장치를 동작하는 것은 명령으로 제어를 할텐데 명령을 내리기 위해서 출력장치가 필요)
   
   2nd Memory(보조 기억 장치):HDD, SSD, Memory에 보관되었던 프로그램이나 데이터를 보관하는 목적의 저장 장치. 즉 Memory는 전원이 연결된 상태에서만 저장해주기 때문에 이를 대신해준다.
   
<h4>Software</h4>
컴퓨터 시스템의 기계장치를 운영하는 프로그램
   * System Software: 우리는 cpu, memory, i/o device에 명령을 내릴 수 있어야한다. System software은 H/W를 제어하고 Application Software를 동작할 수 있는 환경을 제공하는 프로그램을 뜻한다.   
   O/S(Operation System):Windows/Linux/Mac OS
   
   * Library:Application Software가 사용하는 함수 집합
   
   * Application Software: 일반 사용자를 위한 프로그램, End-user를 위한 프로그램
+ 컴퓨터 네트워크(computer network): 컴퓨터간 통신(데이터공유, 프로그램 공유)을 수행할 수 있도록 연결
+ LAN(local area network): 좁은 지역의 컴퓨터를 연결한 network
+ WAN(wide area network): 넓은 지역의 컴퓨터를 연결한 network
+ internet: 전세계 컴퓨터를 연결한 network
+ 프로토콜 (protocol): 네트워크에 연결된 컴퓨터간 통신을 하기 위한 규칙
+ TCP/IP: internet에서 사용하는 protocol
+ WWW(world wide web): internet에서 제공하는 서비스 형태
+ HTTP: wep에서 사용하는 protocol
+ HTML: web에서 제공되는 서비스를 구현할 때 사용하는 프로그램 언어
+ server computer: 요청에 대한 응답을 수행하는 컴퓨터
   - server program: Server computer 에서 요청에 대한 응답 처리를 수행하는 프로그램
+ client computer: 요청을 하는 컴퓨터
   - Client program: Server computer 에게 요청하는 처리를 수행하는 프로그램
   
+ cloud service: server computer에 있는 공간(물리적인 공간 또는 서비스를 제공하는 프로그램)을 사용자에게 대여해주는 서비스고 반드시 internet에 연결된 상태이어야한다. web browser를 사용하여 cloud service를 이용한다.
<hr></hr>

<H2>Python</H2>
본 과정은 머신러닝에 필요한 파이썬 프로그래밍을 학습한다.

<h4>1.파이썬</h4>
  - Open Source: 프로그램을 작성한 소스(source)코드를 모두 공개하는 방식, 무료방식, GNU정신에 따른 S/W   

  - GNU정신: 누구든지 자유롭게 사용할 수 있고 수정할 수 있고, 배포할 수 있다.   
  
  - 컴퓨터 프로그램 언어유형(고급언어)
 > 인간입장에서 프로그래밍으로 컴퓨터에게 명령을 내리려면 고급언어를 사용하면 된다. 하지만 고급언어는 컴퓨터가 이해할 수 없다. 그래서 컴퓨터가 이해할 수 있는 형태로 바꿔주는 것을 번역이라고 한다. 그 번역방식에 따라서 Compile(영화 자막 작업같은), Interpreter(실시간)방식 프로그램 언어가 있다.
    
   * COMPILE 방식 프로그램 언어:일괄 번역에 의하여 기계어를 생성하는 방식의 프로그램 언어, 동작 속도가 비교적 빠름   
    
   * Interpreter 방식 프로그램 언어(Python 해당):단계적으로 번역하여 기계어를 생성하는 방식의 프로그램 언어, 동작 속도가 비교적 느림   
  
  - 자료형(Data Type):메모리에 공간을 확보하기 위한 방법   
    
   * 정적 자료형(Static data type):미리 메모리 공간이 정보를 결정하는 방식 - compile 방식 프로그램 언어가 주로 사용   
    
   * 동적 자료형(Dynamic data type):파이썬이 사용하는 자료형, 실행시 메모리 공간에 정보를 결정하는 방식 - interpreter방식 프로그램 언어가 주로 사용
    
 <h4>2.파이썬 언어 특징</h4>
 * 대화식 인터프리터 언어(고급언어)이다.
 
 * 동적 자료형을 지원   
 
 * 플랫폼에 독립적인 언어/ 파이썬은 리눅스와 유닉스, 윈도우, mac os등 대부분의 운영 체제에서 실행된다.   
 
 * 개발 기간 단축에 초점을 맞춘 언어   
 
 * 파이썬은 list, dictionary, string, tuple, set등 고수준의 자료구조를 제공한다.   

개념: 컴퓨터 시스템에게 명령을 내리기 위한 용도로 사용하는 프로그램언어

<h4>2.파이썬 개발환경 구축</h4>
파이썬 개발과정을 살펴본다.

   - 개발 환경: 소스코드를 작성하고 기계어를 번역하고 실행하고 에러 또는 버그를 수정하기 위한 여러 프로그램을 설치한 환경, 실행가능한 프로그램을 만들기 위한 환경이다.
   
   * 소스 코드 편집기: tect형식의 문서를 작성할 수 잇는 프로그램   
   
   * compiler/interpreter:기계어(binary)로 번역하는 프로그램   
   
   * 실행프로그램(실행기):완성된 실행 프로그램을 실행 시킬수 있는 프로그램/번역된 결과를 컴퓨터가 동작할 수 있도록 처리해주는 프로그램   
   
   * debugger:bug(error)를 수정하기 위해서 사용하는 프로그램
   
   - 실행환경: 완성된 프로그램(binary 형태)이 실행하는 환경   
   
   - Python 개발환경 구축 유형   
        1. 파이썬 공식 개발 환경을 이용한 개발환경 구축   
            *(https://www.python.org/)
            
        2. 파이썬 배포판을 이용한 개발환경구축   
            *(https://www.anaconda.com/) 
            
            -파이썬 기본 개발 환경에 추가적으로 빅데이터 처리, ai모델개발을 위한 환경을 모두 포함
            
            -windows O/S에 설치할 때는 C:/Anaconda3로 설치 위치를 하는 게 차후 사용시 편리. d드라이브가 있으면 D:/Anaconda3에 설치
            
* http://www.wearedev.net/247?PHPSESSID=863fed721b9b507a98f1d8b9118874c5 설치방법안내

       3. cloud service를 이용한 파이썬 개발 환경 이용
         
         -goolge에서 제공하는 파이썬 개발 환경 이용이다. 활용 과정은 google drive에 접속->내 드라이브-> 마우스 오른쪽 클릭 -> 프로그램 더보기->google colaboratory프로그램 실행을 누른다. google에서 제공하는 환경이기 때문에 서버에 설치된다. 그래서 내 pc사양에 상관없이 사용할 수 있다는 장점이 있다.
         
<h4>파이썬 개발 환경 이해</h4>

 -Anaconda 개발 환경 이해
   
  * 통합 개발 환경(IDE,integrated Development Environment):코드 편집, 번역, 실행, debugging을 하나의 tool을 이용하여 수행할 수 있도록 하는 개발 환경 anaconda의 spider,pycharm등이 있다.
       
  * jupyter notebook/jupyter lab:python 코드편집, 실행, Markdown을 이용한 문서화, 실행 결과를 하나의 notebook으로 표현(데이터분석, ai할 때는 데이터분석 사용할 코드도 필요하고 그 코드에 의한 결과물이 필요하고 이를 문서화할 때 용이)
       
  * windows O/S : anaconda prompt 프로그램 실행
             
  - dir 명령
             
  - 드라이브 이동 명령 :드라이브문자
             
  -mkdir 디렉토리이름 :디렉토리 생성
             
  -cd 디렉토리이름 : 디렉토리 이동
             
   * jupyter notebook -> new-> python3-> 새로운 notebook생성
       - 명령셀:파이썬 명령을 입력하는 용도로 사용하는 셀   
       - Markdown 셀:Markdown스크립트를 입력하는 셀,문서작성을 목적으로 한다.   
       - 셀이 선택되면 녹색 테두리, 셀이 선택되지 않으면 파란색 테두리로 감싼다.   
       - 셀을 선택을 해제할 때는 esc키를 사용한다.   
       - shift enter or run:셀 실행   
       - a: 현재 셀 위에 새로운 셀 생성, b: 현재 셀 아래에 새로운 셀 생성   
       - dd: 현재 셀 삭제   
       - y:code 셀로 변환   
       - m:makrdown셀로 변환
       
       # 파이썬 스크립트(프로그램)
        
            print('python progrm')
            print('5+10=',5+10)
            print('5-10=',5-10)
            print('5*10=',5*10)
            print('5/10=',5/10)}
        
   * Markdown:스크립트(script)방식을 이용하여 문서 형태를 표현하는 언어
     
     - 태그를 이용하여 문서 형식을 결정한다.   
     - Tex을 이용한 수식표현도 가능하다. (https://en.wikipedia.org/wiki/Help:Displaying_a_formula#Formatting_using_Tex)   
     - 마크다운은 표준 형식이 없다. 따라서 마크다운 태그를 사용시 jupyter notebook에서 제대로 적용이 안되는 태그도 있다.
             
            # Markdown

            # 제목1 
            ## 제목2
            ### 제목3
            #### 제목4

            ## 목록

            - 첫번째
            - 두번째 
               - 세번째

            1. 첫번째
            2. 두번째
               1. 세번째
    
            ## 표 작성

            |항목1|항목2|항목3|항목4|
            |---|:---|---:|:---:|
            |내용1|내용2|내용3|내용4|

            ## 링크

            [Google]( http://www.google.com )
            [Naver]( http://www.naver.com )

            ## 수식표현

            $$x = { -b \pm \sqrt { b^2 - 4ac } \over 2a}$$
            문장중에 수식을 표현할 때는 $X^2 \times Y^2$ 이와 같이 표현한다. 
            
![image](https://user-images.githubusercontent.com/86647080/128700624-c5580d23-b020-4ff4-96fd-e8b906995e12.png)
    
![image](https://user-images.githubusercontent.com/86647080/128700546-db54c024-4ec3-4d62-9305-53ffb2e17688.png)

   * jupyter lab: jupyter notebook의 개선된 기능을 제공하는 개발환경

- google colab
 
   * google drive 상에서 실행하는 jupyter notebook   
   * google cloud 환경에서 실행되므로 server computer의 H/W 자원을 사용한다.   
   * 어디서든지 web browser를 실행해서 colab을 실행할 수 있다.

<h4>파이썬 프로그램 구조</h4>

   - 파이썬 프로그램 구조는 특별한 규칙은 없고 명령 실행 순서대로 위에서 아래로 나열하면 된다.   
   - 명령을 기술할 때는 반드시 공백없이 바로 명령을 기술한다. **(indentation을 적용할 때와 적용하지 않을 때를 구분해서 명령을 기술)**   
   - 명령의 끝이':'(colon)으로 끝날때에는 최소한 다음줄 한 줄은 indentation(들여쓰기,통산tab간격,4칸)을 적용한다.  
   - indentation을 통해서 코드블록(code block,코드집합)을 구분한다.   
   - **파이썬은 대소문자를 구분하는 언어** 이므로 대소문자를 구분해서 명령을 기술한다.   
   - 단어끝에 ()가 있으면 함수(function)라고 한다.   
   - comment(주석)는 파이썬 프로그램 코드가 아니고 설명을 위한 내용으로 기계어 번역 대상이 아니다.   
   - comment는 #ㅡ로 시작한다.   
   - 파이썬 언어의 단어 종류   
       + 예약어(reserved word,키워드):파이썬 인터프리터에 미리 등록되어 있는 단어   
       + 사용자 정의어(user define word): 사용자가 임의로 정의한 단어   
   
<h4>자료형(Data Type) 이해</h4>

   - 컴퓨터에서 사용하는 값의 형태
     
      + 숫자: 산술 연산이 가능한 값   
      + 문자: 산술 연산이 불가능한 값. 통상 '(단일 따옴표), "(이중따옴표)로 묶어 준다. 
      
           문자(character):단일 문자   
           문자열(string):문자 집합
           
           파이썬은 문자열과 문자를 구분하지 않는다.
          
   - 파이썬 자료형 확인 함수:type()함수 -> 파이썬 기본 함수   
   - 값을 컴퓨터 메모리에 저장하기 위해 메모리 공간이 필요. 이와 같은 메모리 공간을 확보하기 위해서는 두 가지 정보가 결정 되어야 한다. 

       + 저장 구조: 값을 저장할 메모리 모양(구조)   
          
          기억장소 크기 , 값 저장 방식, 저장되는 값의 범위
            
       + 연산: 메모리에 저장된 값을 이용하거나 변경하는 동작(연산)

          값 읽기(메모리 내용을 읽기), 값 쓰기(메모리 내용을 변경하는), 산술 연산, 관계 연산, 논리 연산
          
          
       + 컴퓨터에서 사용하는 용량(크기) 단위

           1bit: 2진수 한자리(0또는1, 1가지 표현)
           
           8bit==1byte:2진수 8자리(2의 8승, 256가지표현)==영어 한문자
           
           16bit==2byte:2진수 16자리(65536가지 표현)===한글 한문자

   - 자료형:메모리에 값을 저장하기 위한 정보
   
       + 저장구조:메모리 모양   
       + 연산: 메모리 내용 변경/이용

<h4>파이썬 기본 자료형</h4>

   - 파이썬 자료형(원시자료형, 원자형) 종류   
      + 기본자료형은 하나의 기본 값을 저장하기 위한 자료형을 말한다.
          
          * 논리형(boolean)참(true,0이아닌 정수) 거짓(false,0또는 공백문자), 정수(integer), 실수(float), 복소수(complex), bytes: 1byte문자 등이 있다.
          
          * 파이썬은 모든 문자 표현을 uni code(2byte,국제 표준화 코드)로 표현한다. 일반적으로 컴퓨터에서 사용하는 코드는 ASCII code(1byte)이다. 네트워크에서는 모든 데이터를 1byte단위로 전송한다. 파이썬에서는 기본 자료형에 대하여 기억장소 크기가 정해져 있지 않고 따라서 값의 범위가 제한되지 않는다. (동적 자료형: 실행시 자료형의 크기를 결정하는 방법-> 파이썬 사용하는 자료형 방식)
              
      + sequence 자료형은 여러 값을 저장하기 위한 자료형을 말한다. 문자, tuple, list, dict, set이 대표적인 sequence자료형이다.
          
   - 파이썬 자료형은 값 변경이 가능할 수도 있고 가능하지 않을 수도 있다. 값 변경이 가능한 경우를 가변형이라 하고 정확히 설명하자면 기억장소에 저장된 값을 변경할 수 있는 자료형을 말한다.  
   list, dict, set은 가변형 자료형들 이다. 반면 불변형은 기억장소에 저장된 값을 변경할 수 없는 자료형으로 값을 변경할 때는 새로운 기억장소에 값을 저장한다. 기본자료형, str, tuple이 불변형 자료형에 속한다.
   
   - literal은 값을 나타낸다,   
   - 변수(variable)는 값을 저장하는 기억 장소이다.   
   - 변수명:기억장소 이름   
       + 변수명은 사용자 정의어이다. 즉 사용자가 마음대로 정하는 것이다. 하지만 변수를 설정하는 데에도 법칙이 따른다. 변수명은 영어 대/소문자,숫자, _ (under bar)를 저합하여 표현한다. 변수명은 소문자로 표현한다. 변수명을 여러 단어로 조합할 때는 단어와 단어 사이를 +로 구분하는 snake표기법을 주로 사용한다. 변수명이 숫자로 시작해서는 안 된다. 변수명을 _ (under bar)로 시작하는 경우는 특수한 경우에 사용한다. 파이썬 내부 변수(system 변수)는 _ (under bar) 2개로 시작하는 변수명을 사용한다. 그래서 시작할때는 언더바 하나로 하는 것이 좋다. 파이썬에 저장된 키워드를 사용하면 안된다. 이 법을 지켜서 변수를 설정해야한다.   
       
   - 변수 정의: 변수명을 표현하고 =기호 다음에 초기값을 부여하면 변수가 생성된다.( 변수형 <L value> =값/수식/변수 <R value> )   
   - 파이썬은 동적 자료형을 지원하는 언어이기 때문에 변수에 초기값을 정의한 경우에 변수가 생성된다.   
   - 변수의 기억장소 정보를 확인하는 함수(변수의 메모리 위치 정보): id()   
   
   - 파이썬의 변수는 실제 값을 저장하는 것이 아니고 값의 위치값(reference)을 저장한다. 그래서 a=10, b=10 에서 a,b의 id는 같다.
  
   - 논리형(bool):참/거짓을 표현하는 기본 자료형
  
       + True(1 = 파이썬이 내부적으로 정한 값),0과 아무것도 쓰지않는 것을 제외한 모든 것은 True로 본다.
  
       + False(0) keyword를 이용하여 논리값 표현   
       
       + True/False 이외에 0이나 공백이 아니면 모두 참이고, 0또는 공백이면 거짓으로 인식한다.   
       + 논리형은 주로 관계 연산이나 논리 연산의 결과로서 사용된다. 
  
       + 논리형으로 형변환(casting)함수 :bool()
  
  - 정수형(int):소수점이 없는 수를 표현하는 기본 자료형
     
       + 나누어 나머지가 0인 수를 의미한다.   
       + 정수를 10진수(기본표현), 2진수(접두사:0b), 8진수(0o), 16진수(0x)로 표현할 수 있다.   
  
            2진수로 변환 함수 : bin()
  
                    -> bin(10) 10진수를 2진수로 바꿔줌
  
            8진수로 변환 함수: oct()
              
            16진수로 변환 함수: hex()
  
            문자에 대한 code값 확인 함수: ord()
   
            정수에 대한 문자 변환 함수: chr()
       + 정수형에 대한 연산 
          
          * 산술연산: +,-,*,/나눗셈 결과 실수,//나눗셈 결과 정수, %나머지, **제곱

          * 산술 연산을 이용한 누적 표현에 대한 단축 연산: +=,-=,*=,/=,//= (number +=1 하면 앞에 number에 +1해줌)
  
          * 관계연산: ==같다,<=,>=,<,>,!=같지않다
            > <=에서 =가 꼭 오른쪽에 와야한다.

          * 논리연산: and , or
       
       + 정수형으로 형변환(casting)함수:int()
            -> 반올림이 일어나지 않는다. 
      > 동적 자료형인 경우이므로 명시적인 형변환을 사용한다. 파이썬은 값이 저장될 때 형이 결정되기 때문에 형변환을 하려면 형변환 함수를 써야한다.
  
      + 누적: 변수의 내용을 정해진 값 만큼 증가하는 연산
 
  - 실수형(float)은 소수점이 있는 수를 표현하는 기본 자료형이다. 실수 표현은 일반적인 실수 표현과 지수 형식의 실수 표현 사용   
  
           산술연산(%도 의미가 없다. 나머지가 나오기 힘듦), 관계연산( 실수형은 ==를 적용하지 않는다.error가 나는 것은 아니지만 실행결과가 항상 같지 않을 수 있다. 소숫점 뒤에 무엇이 있는지 모르니까.) , 논리연산
          
       + 실수형으로 형변환(casting)함수:float()
    
       + ()는 연산자의 우선순위를 무시하고 먼저 연산을 수행할 때 사용하고, ()의 결합성은 오른쪽에서 왼쪽이다.
  
 - bytes:1 byte크기로 한 문자를 저장하는 기본 자료형
     
       + 일반 문자 표현시 보다는 네트워크 프로그램 작성시 많이 사용
  
       + bytes형 리터럴을 표현시 'b'를 항상 붙여준다.
       + 파이썬에서 한 문자는 2byte로 저장된다.
       + 1byte로 한 문자를 저장할 때 사용하는 기본 자료형이다. 
       + bytes 기억장소의 한 문자는 수정할 수 없다.   
       + bytearray()함수로 생성된 bytes형 기억장소의 한 문자는 수정할 수 있다.   
       + bytes형 문자를 문자 (str)로 변환하는 메서드:.decode()   
       + 문자(str)을 bytes형 문자로 변환하는 메서드:.encode()
    
       + 메서드(method):객체에 대한 함수
  
 * type( b1.decode() )  #bytes변수 내용을 str로 변환한 후 자료형 확인 -> str
   
   type( 'python'.encode() )  ->bytes
 
  
  - 표준 입출력
   
       + 표준 입출력 장치: 특별한 장치 지정없이 입출력을 수행할 대 사용하는 장치
           1. 표준 입력장치(stdin):입력시 사용하는 장치. keyboard
  
           2. 표준 출력 장치(stdout):출력시 사용하는 장치. monitor
   
           3. 표준 에러 표시 장치(stderr):에러 표시 장치. monitor
  
       + 표준 출력 함수:print()
           
         1. 표준 출력 장치를 사용하여 출력을 수행   
        
         2. 자동 줄바꿈 기능을 가지고 있다.
  
         3. 자동 줄바꿈 수행하고 싶지 않을 때는 end 옵션을사용한다. ( print('n=),n, end=' ')
  
         4. 제어문자: 특별한 문제에 제어 기능을 적용한 문자. 항상\를 먼저 쓰고 문자를 쓴다. 
  
             \n:개행 문자(줄 바꿈)

             \t:탭 간격
  
             \문자:해당 문자 적용  ('python\'s') 가능
  
            print(출력할 내용, [end=문자]) 
  
       + 표준 입력 함수:input()
  
            표준 입력 장치를 사용하여 입력을 수행
          
            input()함수의 입력 결과는 항상 문자열(str)이다. 때문에 정수 또는 실수값을 입력 받으려면 반드시 형변환 해서 사용한다. (int(input('number=')))
  
  
 <h4>제어문</h4>
 
  - 프로그램의 구조는 3가지 구조가 있다.
    + 순차구조: 명령어를 위에서 아래로 차례대로 나열하고 순서대로 실행하는 구조로 별도의 키워드가 없다.   
  
    + 선택구조: 명령어를 수행시 조건에 따라 명령의 실행 순서를 변경하여 실행하는 구조   
    
         * 선택 구조는 if elif else keyword사용
  
         * 단순 선택구조:조건이 참인 경우에 대한 처리 방향만 결정
  
            if<조건식>:
                조건이 참일 때 수행할 코드 블럭

         * 양자 택일 구조      
           
            if<조건식>:
  
                조건이 참일 때 수행할 코드 블럭
  
            else:
  
                조건이 거짓일 때 수행할 코드 블럭
  
          * 다중 선택 구조: 여러 조건에 따른 각각의 조건이 참인 경우와 거짓인 경우의 처리 방향 결정
   
            if<조건식1>:
  
               조건1이 참일 때 수행할 코드 블럭
  
            elif<조건식2>:
  
               조건2가 참일 때 수행할 코드 블럭
  
             ...
       
             elif<조건식n>:
   
               조건n이 참일 때 수행할 코드 블럭
   
             else:
              
           * 중첩 선택 구조: 선택구조 안에 선택 구조가 포함된 구조
          
             if<조건식1>:
  
                 if<조건식2>:
   
                     조건식1이 참이고 조건식2가 참일 때 수행할 코드블럭
  
 
  
  - 프로그램은 3가지 구조의 조합에 의하여 동작한다.
  
  - 입력시 항상 입력 값에 대한 오류를 확인한다.
     + 입력 값 자료형 체크->프로그램 logic으로 해결하기 어렵고 별도의 자료형 확인 함수를 사용한다.    
     + 입력값 범위 체크->프로그램 logic으로 해결할 수 있다.
  
     + 반복구조: 명령을 수행할 때 일정한 반복 횟수나 조건이 참이 되는 동안 반복해서 명령을 실행하는 구조
  
          * 반복 횟수가 정해진 경우 - for문
  
              for <반복제어변수> in range():
                  반복시 수행할 코드 블럭
            
               range()함수는 반복 횟수를 정해주는 함수
               range(반복 시작값, 반복 종료값, 반복 간격)
               반복 시작값:기본값은0, 생략하면 0으로 간주
        
               반복 종료값:반복 종료값을 결정하며 반복종료값은 반복에 포함되지 않는다. (반복 종료값-1)까지
        
               반복 간격:기본값은1, 생략하면 1로 간주
  
               중첩 for문: for문안에 for문을 표현하는 경우
 
             <code>
                  for i in range(1,11):
                        if i%2:  #2로나눠서 나머지1이면? 참이네!print 해야지
                   print(i,end='\t') 
             <code>
                      
        * 반복 횟수가 정해지지 않은 경우 -while문  #반복하다가 어느 특정값 입력하면 멈추도록 할 수 있음.
      
      + while문은 반복탈출조건이 참인동안에 반복하는 반복구조이다. while문은 반복을 한번도 수행하지 않을 수 있다. while블럭안에서 반복탈출조건에 대한 값 변경 코드가 없으면 반복을 탈출할 수 없어서 무한 반복이 될 수 있다. 반복문 중간에 탈출하기 위해서는 break문 사용해야 한다. 반복문 중간에 특정 반복 내용을 건너뛰기 위해서는 continue문 사용한다.      
        
<h4>문제 풀이 과정</h4>

- 프로그램 구조

    1. 변수 정의 메모리 구조 결정   
    2. 제어 구조를 이용한 알고리즘 표현-메모리 내용을 이용하거나 변경하는 방법   
    3. 결과 도출-사용자가 요구하는 결과

- 알고리즘(Algorithm):문제 해결을 위한 일처리 순서, 의사코드 형태로 표현   
   + 입력:0개 이상의 입력이 있어야한다.   
   + 출력:1개 이상의 출력이 있어야 한다.   
   + 유한성:특정 수의 작업 이후에 종료할 수 있어야 한다.   
   + 유일성:각 단계마다 명확한 다음 단계를 가져야 한다.   
   + 타당성:프로그램 언어로 표현하고 실용적이어야 한다.   
   + 일반성:정의된 입력들에 일반적으로 적용할 수 있어야 한다.

- 파이썬 for문에서 반복 제어 변수를 별도로 활용하지 않을 때는 _ 를 사용한다.

- Symbolic Constant(의미화 상수):상수(constant,literal,값)에 의미를 부여. 일반 변수와 구분을 위해 대문자로 작성한다.-> 프로그램 유지 보수성 향상을 위해 활용
 
- 문제 풀이 단계

   1. 문제 이해(분석 단계)- what을 파악   
   
          a. 문제에서 주어진 값이 어떤 값인지 파악   
          b. 문제에서 요구하는 결과 파악
          
   2. 문제 해결을 위한 알고리즘 설계(설계단계)-논리를 표현. 가극적 how를 표현   
   3. 프로그램 언어로 표현(구현단계)-프로그램 언어의 문법으로 표현. 구체적 how를 표현


<h4>Sequence 자료형</h4>

 - 자료 처리 과정의 컴퓨터 시스템
     
      Data(데이터, 값) --(입력)--> Process(처리) --(결과)--> information(정보, 결과)
      
     > 예를들어 전화번호부가 있을 때 전화번호들을 데이터라고 하고 특징을 검색해서 나온 결과가 정보가 된다. 

 - Process(처리):요청에 대하여 내부적인 logic에 의한 결과를 도출하는 것
 
 - 컴퓨터 프로그램(Computer Program):Process를 프로그램 언어를 이용하여 표현한 형태   
 - 컴퓨터 프로그램 구성
  
   data+algorithm(logic)구성
   
     + data: 메모리에 저장된 값   
     + algorithm(logic):메모리에 저장된 값을 이용하거나 변동하는 명령의 집합으로서 일처리 순서

메모리의 데이터를 어떻게 잘 관리를 할 것인가? --> 자료구조를 이용해보자.

 - 자료구조(Data Structure)
 
     + 자료(data)를 구조적으로 관리하는 방법(여러개의 값을 관리하는 방법)   
     + 자료 구조 구성   
         저장구조: 메모리에 여러개의 값을 저장하는 모양   
         연산 : 저장 구조에 대한 동작(읽기/쓰기)
            1. 생성(create):자료구조 생성   
            2. 소멸(destroy):자료구조 소멸   
            3. 추가(append):데이터 추가   
            4. 삽입(insert):데이터 삽입   
            5. 삭제(delete):데이터 삭제   
            6. 정렬(sort):저장된 데이터 정렬   
            7. 검색(serch):저장된 데이터에서 원하는 값 검색   
            8. 순회(traversal):저장된 전체 데이터 확인

 - 프로그램 언어에서 데이터 관리 방법   
     + 기본 자료형(메모리 구성, 그 메모리 데이터를 읽고 저장 연산)을 이용한 하나의 값 관리 방법->파이썬에서는 기본 자료형   
     + 자료 구조를 이용한 여러개의 값 관리방법->파이썬에서는 sequence자료형   

  - 기본 자료형 : 하나의 값을 저장하는 기억장소 확보시 사용. 스킬라(scalar)형이라고도 함   
  - Sequence자료형: 여러개의 값을 저장하는 기억장소 확보시 사용.
     
     + str:문자열표현 자료형, 여러값이 아닌 하나의 값을 표현-> 기본자료형과 같은 용도로 사용. 즉 문자값을 표현할 때 사용     
     + tuple(튜플):여러값을 저장하기 위한 자료형, 불변형(immutable)   
     + list(리스트):여러값을 저장하기 위한 자료형, 가변형(mutable)   
     + dict(dictionary,사전):key:value형식으로 여러값을 저장하기 위한 자료형,가변형(mutable)   
     + set(셋,집합):중복 없는 여러값을 저장하기 위한 자료형, 가변형(mutable)   

 - Sequence 자료형 공통 연산   
     + indexing:index(위치값)를 이용하여 값에 접근하기 위한 연산   
     + slicing:부분값에 접근하기 위한 연산   
     + 연결:sequence자료형을 연결하기 위한 연산   
     + 반복:sequence자료형을 반복하기 위한 연산   
     + 포함 유무 확인: 특정값이 sequence자료형에 포함되었는지 확인하는 연산    
     + 길이 계산:sequence자료형에 포함된 데이터 개수 확인 연산   

<h4>str(문자열, 문자집합)</h4>

 - 문자열을 표현하기 위한 sequence 자료형   
 - **여러개의 문자열을 의미하는 게 아니고 값으로서의 문자열을 표현하는 목적으로 사용한 sequence자료형   
 - sequence 자료형이지만 실제 프로그램에서 사용하는 성격은 기본자료형의 성격으로 사용한다.   
 
 - str 생성   
   + '(단일 따옴표),"(이중 따옴표), ''',""" (삼중 따옴표)를 이용한 생성   
> 단일따옴표, 이중따옴표: 문자열에 포함된 white space문자(눈에 보이지 않는 문자)문제는 실제 사용시 적용되지 않는다.   
> 삼중따옴표: 문자열에 포함된 모든 문자(white space문자포함)를 원래의 입력형식 그대로 표현. 주석의 용도로도 사용한다.

   + str()함수를 이용한 생성=>형변환 함수   
     
 - str에 대한 sequence 자료형 공통연산   
    
     + indexing
          
          sequence자료형의 하나의 값을 선택하기 위해 값의 위치값(index)을 통한 선택
          
          index는 0부터 시작하고 마지막 값의 index는 전체길이 -1이다.
     
> 기본자료형에서는 10.0하나가 하나의 값인데 sequence자료형은 1,0,.,0이 각각의 값임
> ex)python에서 p는 string[0]으로 표현이 가능하고 index가 0인 것이다.

  
  + slicing #얼마나 끊어 내겠는지
  
  
  [시작인덱스:끝인덱스:인덱스간격]형식으로 사용. 끝인덱스는 포함되지 않음
          
   시작인덱스 생략시 0, 인덱스 간격 생략시0
          
   -(minus)부호를 붙이면 역순으로 인덱스적용. 마지막 값의 인덱스는 -1이다.
       str의 내용중 부분값을 사용하는 용도
          
  + 연결   

      연산자를 이용하여 str변수나 literal을 연결
          
  + 결합   
   
      * 연산자를 이용하여 str변수 내용이나 literal을 반복한다.
          
  + 포함유무확인   

      in 연산자를 통하여 특정 내용이 str에 포함되었는지의 결과를 bool형의 결과로 확인
          
          
  + 길이계산

      len()함수 사용하여 str을 구성하는 문자길이 확인 가능
      
      
   - sequence자료형 반복자(iterator)를 이용한 순회
       
     + sequence 자료형 변수(기억장소)에는 여러 값을 저장하고 있다.   
     + indexing을 이용하여 하나의 값을 사용하거나, slicing을 이용하여 부분집합의 값을 사용할 수 있다.    
     + 만약 sequence자료형 기억장소 내용 전체를 순회할 때는 하나의 값에 접근해야 하는데 이때 index를 이용하여 접근할 수 있지만 sequence자료형의 내부에는 반복자(iterator)가 내장 되어 있어 따로 반복에 대한 별도의 처리없이도 자동 반복을 수행한다.   
     + enumerate()함수:sequence자료형을 반복하면서 index와 value를 tuple형식으로 제공하는 함수


   - str메서드(method) 
     + 함수(function):단위 기능을 수행하는 코드집합
        함수 호출 방법:함수명([인수 목록])
        ex)print(len(string))
        
     + 메서드(method): **객체(object)에 포함된 함수.** 파이썬에서는 모든 내용을 객체로 관리한다. 변수도 객체의 한 종류이다.   
        메서드 호출 방법:변수명(객체),메서드명([인수 목록])
        ex)print(string.upper())
       
     + str메서드:str내용을 가공하는 용도의 함수, 메서드가 동작하는 시점에만 변화가 적용된다.

![image](https://user-images.githubusercontent.com/86647080/128658511-107d0c38-61d2-4020-a701-6a56a7be8788.png)


print(string.upper())
I LIKE PROGRAMMING. I LIKE PYTHON

print(string.lower())
i like programming. i like python

print(string.capitalize()) #문자열 첫 글자만 대문자 변환
I like programming. i like python

print(string.title()) #단어별 첫글자만 대문자로 변환
I Like Programming. I Like Python
  
  
   + \:제어문자를 표현할 때 사용함으로 \를 직접 사용하고자 할 때는 반드시 \를 두번 기술한다. (string.split('\\'))   
   
string.rstrip() #뒤 공백 제거
string.lstrip() #앞 공백 제거

   + is로 시작하는 메서드나 함수는 결과가 True/False 값을 반환한다.   

 - 형식 문자열(문자 포매팅)
  
   + str(문자열)의 내용을 형식을 지정해서 표현하는 방법   
   + 기본 형식 문자열  
     ' 형식 문자가 포함된 문자열' % (literal 또는 변수)

     <형식문자>
     %-20s:전체 공간 20칸에 왼쪽 정렬하여 문자 출력   
     %5d:전체 공간 5칸에 오른쪽 정렬하여 정수 출력   
     %8.2f:전체 공간 8칸에 소수점이하 2자리로 오른쪽 정렬하여 실수 출력

   + format()메서드를 이용한 형식 문자열   
     ' 형식 문자가 포함된 문자열'.format(literal또는 변수)
     <형식문자>
     
     {0:<20}:0번째변수/값을 전체 공간 20칸에 왼쪽 정렬하여 문자 출력   
     {1:5}:1번째 변수/값을 전체 공간 5칸에 오른쪽 정렬하여 정수 출력   
     {4:8:2f}:8번째 변수/값을 전체 공간 8칸에 소수점이하 2자리로 오른쪽 정렬하여 실수 출력
     {4:8:2}:8번째 변수/값을 전체 8칸에 소수점이하 2자리로 오른쪽정렬하여 실수 출력(지수형식)
     
   + f=string을 이용한 형식 문자열  -> 최신방식, 3.6이상 버전에서 사용가능
   
     f'형식 문자와 변수가 포함된 문자열'
      
        <형식 문자>
      * {name:<20}:name변수 내용을 전체 공간 20칸에 왼쪽 정렬하여 출력  
      * {average:8.2f}:average변수 내용을 전체 8칸에 소수점 이하 2자리로 오른쪽 정렬하여 실수 출력  
      
 <h4>tuple</h4>
 
   - tuple은 여러 값을 저장하는 sequence자료형   
>str은 하나의 값을 저장한다는 차이가 있다.

   - tuple은 불변자료형   
   - tuple은 저장된 값이 변경되지 않아야 할 때 사용하는 sequence자료형    - tuple은 생성시 값을 저장하지 않으면 생성 후에는 값 추가를 할 수 없다.   
   
   - tuple생성   
      + 0:빈 tuple이나 literal을 초기값으로 갖는 tuple생성   
      + ,(comma)로 구분   
      + tuple()함수로 형변환   
      + tuple생성시 하나의 값이라도 반드시 ,(comma)를 포함해야 한다. 
      
      ![image](https://user-images.githubusercontent.com/86647080/128660949-95187db7-0265-4802-9b2e-aaf1724c7f2e.png)

    
   - sequende자료형 공통 연산-tuple   
      + indexing   
      + slicing: tuple부분 요소 읽기   
      + 길이계산: len()함수   
      + 포함 윰 확인: in연산   
      + 연결   
      + 반복

t라는 이름의 tuple을 생성하면 t=(1,10.5,'python')으로 저장할 수 있다. 즉 여러값을 저장할 수 있는데 그 타입은 정수, 실수 , 문자 모두 혼합해서 저장하는 것이 가능하다. 

 + tuple은 불변(immutable)자료형이므로 초기에 tuple에 저장된 값에 대한 변경, 삭제, 값 추가 동작이 모두 불가능하다.   

  - indexing을 이용한 tuple요소 읽기

 + indecing: tuple요소(원소)에 대한 읽기 수행. tuple은 불변 자료형이므로 indexing을 통한 tuple요소에 대한 쓰기는 불가능


![image](https://user-images.githubusercontent.com/86647080/128661010-25826bbc-37c2-4873-a6a3-bdb3ddad4236.png) 
  > 위 t=(1,10.5,'python')에서 0에는 1이 저장되어 있겠고 그 type은 int 즉 정수이다.

- 중첩 tuple
   
 + tuple의 요소가 tuple인 형태   
 + 중첩 tuple을 구성한 경우 tuple의 요소가 tuple이므로 indexing을 중첩해서 사용해야한다.   
 
- tuple메서드   
 + count()메서드:원하는 값의 개수 확인   
 + index()메서드:원하는 값의 위치값 확인   

- tuple을 이용하여 여러값을 변수에 치환   
- tuple을 이용한 두 변수의 내용 교환   
- tuple을 이용한 packing과 unpacking
   
 + packing:하나의 변수에 여러값을 저장하는 방법   
 + unpacking:하나의 변수의 내용을 여러 변수에 나누어 저장하는 방법   
 + 확장 기능을 이용한 unpacking:변수에 '(asterisk)기호를 붙이면 tuple에 포함된 데이터 개수와 상관없이 unpacking가능   

- tuple비교:tuple간의 비교는 크기 비교가 아니고 원소의 수 (길이)비교   

> t1,t2,t3를 지정하고 f1>t2 처럼 관계연산자를 사용하여 참 거짓을 출력하는 것

- tuple도 반복자(literator)를 포함하고 있다.  

<h2>2.list</h2>

- 여러 값을 저장하는 sequence자료형   
- list는 **가변(mutable) 자료형**   
- list는 파이썬 스크립트 작성시 가장 많이 활용하는 sequence자료형  
- list생성 방법   
  + [] 대괄호를 이용하여 생성   
  + list()함수를 이용한 생성   
 
- sequence자료형 공통 연산- list  
  + indexing   
  + slicing   
  + 길이 계산   
  + 포함 유무 확인('py' in l)   
  + 연결(l=l+[1,2,3,]),반복(l*3)   
  + 포함

- 중첩 list: list에 list를 요소로 포함하여 구성하는 방법

- list 메서드(method)   
  + append(): list 마지막 요소로 값을 추가할 때 사용하는 메서드   
  + insert():원하는 위치에 값을 추가할 때 사용하는 메서드(ex: l.list(3,'땡땡') )   
  + slicing기능을 이용하여 list요소 내용을 변경할 수 있다. 
  + 삭제
    
    1. del명령-> del l[0]  
       indexing이나 slicing을 이용하여 원하는 위치의 값 삭제
       
    2. remove()메서드 -> l.remove(100)
       list에서 지정된 값을 검색해서 삭제
       
       검색할 값이 여러 개인 경우에는 처음 찾은 값만 삭제하는 것이다.
       
       검색 실패시 예외발생   
    
    3. pop()메서드 -> l.pop()
    
       list의 마지막 요소를 삭제
       
       삭제한 값을 반환한다.( print(f'remove data : {value}') )
       자료구조 종류중에 stack(스택)
           LIFO( last in first out,후입선출) 구조의 자료구조   
           한 방향으로 입력과 추력을 수행   
           주로 임시 데이터 저장용으로 사용
           
    4. clear()메서드:list전체 삭제   

  + index()   
    1. 데이터 검색하여 index반환   
    2. 중복된 데이터에 대해서는 먼저 검색된 데이터의 index반환   
    3. 검색 실패시 예외 발생 

  + count():원하는 값의 개수 파악하는 메서드   
  + sort(정렬)-> l_sorted=sorted(l)

    1. 데이터를 기준에 따라 순서대로 나열하는 Algorithm   
    2. sort(정렬) Algorithm
         정렬 키: 정렬을 하기 위한 기준 값   
         정렬 방향: 작은 값에서 큰값순 정렬(Ascending),큰 값에서 작은값순 정렬(Descending)   
    3. sort()메서드:list전체를 내부적으로 (in place)로 정렬   
    4. sorted()함수: list전체를 정렬한 복사본 반환
    
<한 달 간의 인공지능 스터디를 마치고>

 짧은 기간동안 파이썬 입문을 해보았다. 굉장히 적은 내용인 것 같지만 배울 때 만큼은 최대한 모든 것을 흡수하려 노력했다. 기초 지식부터 파이썬의 여러가지 함수들과 자료형을 배웠고 이를 적용하여 문제풀이를 연습해볼 수 있었다. 이번 스터디를 하기로 마음먹고 배우면서 가장 좋았던 점은 왜 프로그래밍을 하는가였다. 사실 공부 시작하기 전부터 내게 늘 던져왔던 질문이었다. 프로그래밍이 무엇인지는 알겠는데, 그걸 왜 명령어로 복잡하게 나타내지? 라는 어린 생각을 가졌었다. 그런데 문제풀이를 하고 여러 복잡한 함수들도 보면서 그저 명령어를 입력하고 프로그램들을 실행하기 위해서가 아니라 왜 명령어를 입력해줘야하는지를 알게 되었다. 특히 다른 벗들의 스터디 흔적을 보면서 새롭게 알게 된 점도 많았다. 나는 아직 간단하고 기본적인 부분을 배우고 적용하는 반면 다른 벗들은 심화과정과 좀 더 복잡한 것을 구현하는 모습을 보고 프로그래밍에 본질에 대해서 알게 되었다. 벗들과 일주일동안 했던 공부 기록을 공유하니 더 폭넓은 인공지능 세계를 알 수 있었고 앞으로 내가 밟아야 할 절차에 대해서 알게 되어 뜻깊었다. 
