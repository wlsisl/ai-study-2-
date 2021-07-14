# ai-study-2-
Python

<H2>Python</H2>
본 과정은 머신러닝에 필요한 파이썬 프로그래밍 부터 데이터 분석 및 시각화 다양한 알고리즘 등을 학습한다.

<h4>1.파이썬 개요</h4>
  - Openn Source:프로그램을 작성한 소스(source)코드를 모두 공개하는 방식, 무료방식, GNU정신에 따른 S/W   
  - GNU정신:누구든지 자유롭게 사용할 수 있고, 누구든지 자유롭게 수정할 수 있고, 배포할 수 있다.   
  - 컴퓨터 프로그램 언어유형(고급언어)
 > 인간입장에서 프로그래밍으로 컴퓨터에게 명령을 내리려면 고급언어를 사용하면 된다. 하지만 고급언어는 컴퓨터가 이해할 수 없다. 그래서 컴퓨터가 이해할 수 있는 형태로 바꿔주는 것을 번역이라고 한다. 그 번역방식에 따라서 Compile(영화 자막 작업같은), Interpreter(실시간)방식 프로그램 언어가 있다.
    * COMPILE 방식 프로그램 언어:일괄 번역에 의하여 기계어를 생성하는 방식의 프로그램 언어, 동작 속도가 비교적 빠름   
    * Interpreter 방식 프로그램 언어(Python 해당):단계적으로 번역하여 기계어를 생성하는 방식의 프로그램 언어, 동작 속도가 비교적 느림   
  - 자료형(Data Type):메모리에 공간을 확보하기 위한 방법   
    * 정적 자료형(Static data type):미리 메모리 공간이 정보를 결정하는 방식 - compile 방식 프로그램 언어가 주로 사용   
    * 동적 자료형(Dynamic data type):파이썬이 사용하는 자료형, 실행시 메모리 공간에 정보를 결정하는 방식 - interpreter방식 프로그램 언어가 주로 사용
    
 <h4>2.파이썬 언어 특징</h4>
 * 대화식 인터프리터 언어(고급언어) 
 
 * 동적 자료형을 지원   
 
 * 플랫폼에 독립적인 언어/ 파이썬은 리눅스와 유닉스, 윈도우, mac os등 대부분의 운영 체제에서 실행된다.   
 
 * 개발 기간 단축에 초점을 맞춘 언어   
 
 * 파이썬은 list, dictionary, string, tuple, set등 고수준의 자료구조를 제공한다.   

 개념: 컴퓨터 시스템에게 명령을 내리기 위한 용도로 사용하는 프로그램언어

<h4>2.파이썬 개발환경 구축</h4>
먼저 파이썬 개발과정부터 살펴본다.
   - 개발 환경: 소스코드를 작성하고 기계어를 번역하고 실행하고 에러 또는 버그를 수정하기 위한 여러 프로그램을 설치한 환경, 실행가능한 프로그램을 만들기 위한 환경   
   
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
            
*http://www.wearedev.net/247?PHPSESSID=863fed721b9b507a98f1d8b9118874c5 설치방법안내

   3. cloud service를 이용한 파이썬 개발 환경 이용
         
         -goolge에서 제공하는 파이썬 개발 환경 이용
         
         -google drive에 접속->내 드라이브-> 마우스 오른쪽 클릭 -> 프로그램 더보기->google colaboratory프로그램 실행
         
         -내 pc사양에 상관없이 서버에 설치된다.
         
<h4>파이썬 개발 환경 이해</h4>

 -Anaconda 개발 환경 이해
   
  * 통합 개발 환경(IDE,integrated Development Environment):코드 편집, 번역, 실행, debugging을 하나의 tool을 이용하여 수행할 수 있도록 하는 개발 환경 anaconda의 spider,pycharm등이 있다.
       
  * jupyter notebook/jupyter lab:python 코드편집, 실행, Markdown을 이용한 문서화, 실행 결과를 하나의 notebook으로 표현(데이터분석, ai할 때는 데이터분석 사용할 코드도 필요하고 그 코드에 의한 결과물이 필요하고 이를 문서화할 때 용이)
       
  * windows O/S : anaconda prompt 프로그램 실행
             
  - dir 명령
             
  - 드라이브 이동 명령 :드라이브문자:
             
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
|---|:---|---:|:---:|                         -> 오른쪽/왼/오/가운데 정렬
|내용1|내용2|내용3|내용4|

## 링크

[Google]( http://www.google.com )
[Naver]( http://www.naver.com )

## 수식표현 (TeX)

$$x={-b \pm \sqrt {b^2-4ac} \over 2a} $$   

문장중에 수식을 표현할 때는 $X^2 \times Y^2$ 이와 같이 표현한다.


   * jupyter lab: jupyter notebook의 개선된 기능을 제공하는 개발환경

- google colab
 
   * google drive 상에서 실행하는 jupyter notebook   
   * google cloud 환경에서 실행되므로 server computer의 H/W 자원을 사용한다.   
   * 어디서든지 web browser를 실행해서 colab을 실행할 수 있다.

<h4>파이썬 프로그램 구조</h4>

   - 파이썬 프로그램 구조는 특별한 규칙은 없고 명령 실행 순서대로 위에서 아래로 나열하면 된다.   
   - 명령을 기술할 때는 반드시 공백없이 바로 명령을 기술한다. **(indentation을 적용할 때와 적용하지 않을 때를 구분해서 명령을 기술)**   
   - 명령의 끝이':'(colon)으로 끝날때에는 최소한 다음줄 한 ㅈ루은 indentation(들여쓰기,통산tab간격,4칸)을 적용한다.  
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
      + 기본자료형: 하나의 기본 값을 저장하기 위한 자료형
          
          * 논리형(boolean)참(true,0이아닌 정수) 거짓(false,0또는 공백문자) 
          
          * 정수(integer) 
          
          * 실수(float) 
          
          * 복소수(complex) 
          
          * bytes: 1byte문자 
          
          * 파이썬은 모든 문자 표현을 uni code(2byte,국제 표준화 코드)로 표현
          
          * 일반적으로 컴퓨터에서 사용하는 코드는 ASCII code(1byte)
          
          * 네트워크에서는 모든 데이터를 1byte단위로 전송한다.
          
          * 파이썬에서는 기본 자료형에 대하여 기억장소 크기가 정해져 있지 않고 따라서 값의 범위가 제한되지 않는다.(동적 자료형: 실행시 자료형의 크기를 결정하는 방법-> 파이썬 사용하는 자료형 방식)
          
         
      + sequence 자료형: **여러 값을 저장하기 위한 자료형

          문자, tuple, list, dict, set
          
   - 파이썬 자료형은 값 변경 가능 유무에 따라   
       + 가변형(mutable): 기억장소에 저장된 값을 변경할 수 있는 자료형

            * list
            
            * dict
            
            * set
            
       + 불변형(immutable):기억장소에 저장된 값을 변경할 수 없는 자료형으로 값을 변경할 때는 새로운 기억장소에 값을 저장한다.   

            * 기본 자료형   
            
            * str
           
            * tuple
   
   - literal:값   
   - 변수(variable):값을 저장하는 기억 장소   
   - 변수명:기억장소 이름   
       + 변수명은 사용자 정의어이다.   
       + 변수명은 영어 대/소문자,숫자, _ (under bar)를 저합하여 표현한다.   
       + 변수명은 소문자로 표현한다.   
       + 변수명은 의미있는 단어의 조합으로 작성한다.   
       + 변수명을 여러 단어로 조합할 때는 단어와 단어 사이를 +로 구분하는 snake표기법을 주로 사용한다.   
       + 변수명은 숫자로 시작x   
       + 변수명을 _ (under bar)로 시작하는 경우는 특수한 경우에 사용한다.   
       + 파이썬 내부 변수(system 변수)는 _ (under bar) 2개로 시작하는 변수명을 사용한다. 그래서 시작할때는 언더바 하나로 하는 것이 좋다.   
       + 변수명은 파이썬에 저장된 키워드를 사용하면 안된다.   
       > 변수명 
       
   - 변수 정의: 변수명을 표현하고 =기호 다음에 초기값을 부여하면 변수가 생성된다.( 변수형 <L value> =값/수식/변수 <R value> )   
   - 파이썬은 동적 자료형을 지원하는 언어 이기때문에 변수에 초기값을 정의한 경우에 변수가 생성된다.   
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
 
  - 실수형(float):소수점이 있는 수를 표현하는 기본 자료형
      
      + 나누어 나머지가 0이 아닌수   
      + 실수 표현은 일반적인 실수 표현과 지수 형식의 실수 표현 사용   
      + 실수형에 대한 연산 
  
           산술연산(%도 의미가 없다. 나머지가 나오기 힘듦), 관계연산( 실수형은 ==를 적용하지 않는다.error가 나는 것은 아니지만 실행결과가 항상 같지 않을 수 있다. 소숫점 뒤에 무엇이 있는지 모르니까.) , 논리연산
          
       + 실수형으로 형변환(casting)함수:float()
    
       + ()는 연산자의 우선순위를 무시하고 먼저 연산을 수행할 대 사용하고, ()의 결합성은 오른쪽에서 왼쪽이다.
  
  
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
    
         * 선택 구조는 if~elif~else keyword사용
  
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
  
        <pre>
        <code>
        
                {for i in range(1,11):
                      if i%2:  #2로나눠서 나머지1이면? 참이네!print 해야지
                 print(i,end='\t')
       } 
        <code>
        <pre>
 
  
           * 반복 횟수가 정해지지 않은 경우 -while문
