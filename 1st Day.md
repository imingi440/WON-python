# WON-python
원광대 웹개발자 양성과정 기본반 2024.06.24-2024.07.05
1일차

#파이썬 변수 선언하는 에제
#파이썬은 변수를 변수명=값; 으로 선언할 수 있다.
age = 22 #age(나이)변수에 정수값 22를 저장합니다.
year = 2024 #년도(year)변수에 정수값 2024를 저장합니다.
temperature=36.5 #temperature 변수에 실수값 36.5를 저장합니다.
price=9.99 #price 변수에 실수값 9.99를 저장합니다.
name="Mingi"#name 변수에 문자열 "Mingi"를 저장합니다.
message="Hello, world!" #message 변수에 문자열 "Hello, world!"를 저장합니다.
is_valid=True #is_valid 변수에 논리값 True를 저장합니다. 파이썬에서 논리값의 앞글자는 무조건 대문자로
is_found=False #is_found 변수에 논리값 False를 저장합니다. 파이썬에서 논리값의 앞글자는 무조건 대문자로

#프로그램에서 사용자가 입력하도록 하는 코드
#input()으로 콘솔에서 사용자에게 데이터를 입력 받을 수 있다.
#input()의 소괄호 안에 사용자에게 어떤 데이터를 입력해야할지 알려주는 문구를 작성한다.
name=input("이름을 입력하세요:")
age=int(input("나이를 입력하세요:"))

#프로그램에서 출력하는 코드
#print()로 콘솔에 출력을 해줄 수 있다
#print()의 소괄호 안에 출력할 데이터를 넣어준다.
print("입력받은 이름:",name)
print("입력받은 나이:",age)

country=input("태어난 곳을 알려주세요 : ")
birth=int(input("태어난 년도를 알려주세요 : "))
print("당신이 태어난 년도는",birth,"년도이고 태어난 곳은",country,"이네요")
