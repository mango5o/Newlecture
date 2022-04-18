# Newlecture

### JAVA  Basic 
<br>

**🤍 JAVA는 C++언어에서 파생된 언어 🤍**  
<br>

**🤍 C / C++ 언어가 가지는 문제점들 → JAVA에서 수정됨 🤍**  
<br>
↓ ↓ ↓
<br>  
객체 생성과 제거 → delete 키워드 제거  
참조 변수와 포인터 변수 → 객체의 포인터 제거  
이차 이상의 포인터 문제 →  모든 포인터 제거   
데이터 구조를 정의하는 두 가지 방법 → struct 키워드 제거  
함수지향? 객체지향? → 함수는 메소드로만 사용하도록 제약 (완전한 객체지향으로 바뀜)  
컬렉션의 부재 → 언어에 컬렉션을 **포함**  
글로벌한 문자 데이터처리의 복잡성 → 다양한 인코딩 문자열 기능 개선 

- - -

**🤍 자바언어의 특징 🤍**   
<br>
① 간결성  
② 언어에 컬렉션 포함  
③ **완전한 객체지향** 언어  
<br>   
- - -
**🤍 새로운 WORA API의 탄생-platform independent 🤍**  
<br>
<img width="{60%}" src="https://user-images.githubusercontent.com/85277818/163794204-a5c79fc0-3400-4a72-af2b-7432a0ff3d99.png"/> <br>
**<장점>**   
<br>
→ 자바는 운영체제들이 갖고 있는 환경에서 실행되는 프로그램의 API가 달라서 각각의 운영체제용으로 만들어지는 것을 피할 수 있었다.<br>
→ (단일한 API)<br>
→ A 운영체제에 A API를 설치하고, B 운영체제에 B API를 설치하고, C 운영체제에 C API를 설치하면 단일한 API를 사용할 수 있다.<br>
→ 자바프로그램은 JAVA API만 이용해서 프로그램을 만들게 된다.<br>   
**<단점>**
<br>
→ 플랫폼에 먼저 API를 설치해야하는 단점 <br>
→ 각각의 운영체제만 갖고 있는 기능에 대해서는 자바 플랫폼에서 단일화 시킬수 없었다.<br>
- - -

**🤍 자바 번역기(Complier)의 특징 🤍**  
<br>
1단계 : 형태소 분석   
2단계 : 구문 분석   
3단계 : 의미 분석   
4단계 : 중간 코드 → 컴파일러 사용   
5단계 : 최적화 → 인터프리터 사용   
6단계 : 물리 코드   
<br>
JDK (Complier / Debuger) 안에 JRE(JIT Complier / Garbage Collector / Security / Loader)이 포함되어 있다.   
<br>
- - -   
<!-- **🤍 자바에서의 값의 종류와 표현 방법 🤍**
|정수값|실수값|문자값|진리값 |
|:---:|:---:|:---:|:---:|
|||||

- - - -->
**🤍 선언이란? 🤍**   
<br> → 모든 키워드는 선언하고 사용해야하 한다.<br>

변수 / 함수 / 참조변수 / ...  ↔ <선언> ↔ int kor; / void add(int x, int y); / Animal 망망이; / ...   <br>

- - -
**🤍변수란?🤍**
<br>→ 값을 저장하기 위한 공간<br>

<변수를 선언하는 방법> <br>

* **변수 명명 규칙** : int kor; (앞에 숫자나 공백, 특수기호가 들어갈 수 없다.)<br>
* **여러 변수를 한번에 선언하기** : int kor1, kor2, kor3; <br>
- - - 
**🤍 출력 스트림 객체와 API 🤍** <br>

<입/출력 장치를 위한 인터페이스의 필요성><br>
<img width="{60%}" src ="https://user-images.githubusercontent.com/85277818/163802992-6465138f-49ff-413c-b55f-f85edf0fb6b1.PNG"/> <br>

<프로그램에서 사용하는 재료>  <br>
<img width="{60%}" src="https://user-images.githubusercontent.com/85277818/163803519-e33dabed-f2a7-4454-8733-697df9d2e28b.PNG"/> <br>

<자바 플랫폼의 내장 입/출력 객체와 멤버 함수>
<img width="{60%}" src="https://user-images.githubusercontent.com/85277818/163803973-0e42a11f-335e-47c9-8417-0590090ec1f2.png" /> <br> 
→ System.**out**.… = '출력'   
→ System.**in**.… = '입력'<br>

<객체를 이용하는 함수>
<img width="{60%}" src="https://user-images.githubusercontent.com/85277818/163805927-96e3dc7f-0cd6-489c-a34d-0aa20cce234e.png" /> <br>
→ '**out**' 이라는 객체명을 통해 write() / flush() 해준다. <br>
→ '**in**' 이라는 객체명을 사용해야한다. <br>

- - - 
**🤍 개체(Entity)와 객체(Object) 🤍** <br>
→ **객체(Object)** : 실존하는 것 <br>
→ **개체(Entitiy)** : 객체가 있기 위해서 사용되는 type <br>
- - -

<br>

[출처 바로가기](https://www.youtube.com/watch?v=tvciu9_jHjQ&list=PLq8wAnVUcTFV7wEVu2qcAChtAOYusZwzj&index=1)
