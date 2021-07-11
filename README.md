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
 * 대화식 인터프리터 언어   
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
            *(https://www.anaconda.com/) 파이썬 기본 개발 환경에 추가적으로 빅데이터 처리, ai모델개발을 위한 환경을 모두 포함

        3. cloud service를 이용한 파이썬 개발 환경 이용
