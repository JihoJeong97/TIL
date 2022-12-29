1. 파이썬 프로그램을 설치하고 내부 구조를 이해하고 설명할 수 있다.
[PVM] .py -> .pyc -> exe

python -v, python --help

1-1 기본 코아 패키지 진입점 확인
import sys 임포트 -> 전역변수 설정 확인, 데이터 크기 확인, 파이선 버전 확인
dir(sys) 목록확인
sys.path 기본 코아 패키지 및 모듈 확인

1-2 pip 명령을 이용해서 추가 라이브러리 설치(Python Package Index) https://pypi.org / [numpy,pandas]
~파이썬/Lib\site-package 하위에 설치된다

2. 기본 자료형을 이해하고 객체를 통한 속성 및 메소드를 확인 할 수 있다.
 2-1 : dir() 내장함수 , 메모리에 생서된 객체의 목록을 확인
 
 2-2 : type()_class (멤버_속성(값)+메소드)기능))	/ str ,int ,float,list,tuple,dict (5가지 기본자료형) -> index[str,list,tuple]
* ex) str 라는 클래스를 s라는 객체로 생성해서 count()메소드로 확인
* ex) a = 100 -> 100 정수를 a라는 int 클래스의 객체를 생성(__init__=생성자) 했다.
* ex) f = 90.9 -> 90.9 실수를 f라는 float 클래스의 객체를 생성(__init__=생성자) 했다.
* ex) my_list = [1,2,3,4] -> [1,2,3,4]라는 목록을 my_list라는 list 클래스의 객체를 생성(__init__=생성자) 했다.
* ex) my_tuple = (1,2,3,4) -> (1,2,3,4) 라는 목록을 my_tuple 라는 tuple클래스의 객체를 생성(__init__=생성자) 했다.
* ex) my_dict = {'a':1,'b':2} -> {'a':1,'b':1} 값을 my_dict 라는 dict 클래스의 객체를 생성(__init__=생성자) 했다.

 2-3 help()_ 객체의 활용정보

 2-4 del -> 객체 명시 삭제 -> 소멸자 호출 -> 객체 소멸
	int, float,str -> class
 2-5 object -> 클래스, 상속, 다형성