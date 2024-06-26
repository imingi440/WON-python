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

jeju_temperature=int(input("제주의 온도를 입력해주세요:"))
if jeju_temperature==10:
  print("야외에서 운동했을텐데")
elif jeju_temperature==-1:
  print("실내에서 운동했을텐데")
else:
  print("운동안할텐데")

  print("오늘은 학교에서 코딩 기본반 수업이 있는 날이다.")
print("수업 시작 시간은 오전 10시이다.")
print("현재 시간은 오전 9시이다.")
print("어떻게 하지...?")
print("1. 밥을 먹고 간다. 2. 밥을 먹지 않고 학교에 간다.")

selection=int(input("선택지를 입력해 주세요."))

if selection==1:
  print("밥을 먹고 학교에 가기로 했다.")
  print("밥을 먹고 학교에 가기로 했는데 뭘 먹지...?")
  print("1. 집밥 2. 시리얼 3. 라면 4. 샐러드 5. 배달음식")

  selection=int(input("선택지를 입력해 주세요."))

  if selection ==1:
    print("집밥을 먹기로 했다.")
    print("집밥을 먹으려고 밥솥을 열었는데 밥이 없다...")
    print("배고픈데 어떻게 하지..?")
    print("1. 밥을 새로한다. 2. 시리얼을 먹는다. 3. 시간이 없다 그냥 학교로 간다.")

    selection=int(input("선택지를 입력해 주세요."))

    if selection==1:
      print("밥을 새로했는데 밥이 안성되니 9시 50분이 되었다...")
      print("지각이다...망했다...")
    elif selection==2:
      print("급한대로 시리얼을 먹었다. 배가 든든하다.")
      print("이제 학교로 가야겠다.")
    elif selection==3:
      print("무언가를 먹기에는 너무 늦었다.")
      print("학교에 지각하지 않고 올 수 있었다.")
  elif selection==2:
    print("시리얼을 먹기로 했다.")
  elif selection==3:
    print("라면을 먹기로 했다.")
  elif selection==4:
    print("샐러드을 먹기로 했다.")
  elif selection==5:
    print("배달음식을 먹기로 했다.")
  else:
    print("선택지를 잘못 입력하셨습니다.")

elif selection==2:
  print("밥을 먹지 않고 학교에 가기로 했다.")
else:
  print("선택지를 잘못 입력하셨습니다.")

print("오늘부터 시험기간이다.")
print("어디에 가서 공부를 할까")
print("1. 학교 2. 카페 3. 집")

select=int(input("선택지를 입력해 주세요."))

if select==1:
  print("학교에 가서 공부하기로 했다.")
  print("어느 강의실에 가서 공부를 할까")
  print("1. 1층 강의실 2. 2층강의실 3. 3층 강의실 4. 4층 강의실 5. 5층 강의실")

  select=int(input("선택지를 선택해 주세요."))

  if select==1:
    print("1층 강의실에 왔다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")
    study=int(input("선택지를 선택해 주세요."))
    if select==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif select==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif select==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")

  elif select==2:
    print("2층 강의실에 왔다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")
    study=int(input("선택지를 선택해 주세요."))
    if select==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif select==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif select==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")

  elif select==3:
    print("3층 강의실에 왔다.")
    print("자리가 없다!")
    print("아쉽지만 집으로 돌아갔다.")
    print("집에서 공부하기로 했다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")
    study=int(input("선택지를 선택해 주세요."))
    if select==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif select==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif select==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")

  elif select==4:
    print("4층 강의실에 왔다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")
    study=int(input("선택지를 선택해 주세요."))
    if select==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif select==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif select==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")

  elif select ==5:
    print("5층 강의실에 왔다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")
    study=int(input("선택지를 선택해 주세요."))
    if select==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif select==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif select==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")
  else:
      print("잘못된 선택지입니다.")

elif select==2:
  print("카페에 가서 공부하기로 했다.")
  print("어느 카페로 가서 공부를 할까")
  print("1. 스타벅스 2. 이다야커피 3. 메가커피 4. 빽다방")

  cafe=int(input("선택지를 선택해 주세요."))

  if cafe==1:
    print("스타벅스에 왔다")
    print("자리가 없다!")
    print("아쉽지만 집으로 돌아갔다.")
    print("집에서 공부하기로 했다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")

    study=int(input("선택지를 선택해 주세요."))

    if study==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif study==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif study==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")

  elif cafe==2:
    print("이디야커피로 왔다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")
    study=int(input("선택지를 선택해 주세요."))
    if study==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif study==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif study==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")

  elif cafe==3:
    print("메가커피에 왔다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")
    study=int(input("선택지를 선택해 주세요."))
    if study==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif study==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif study==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")

  elif cafe==4:
    print("뺵다방에 왔다.")
    print("어떤 과목을 공부할까")
    print("1. c언어 2. 파이썬 3. 자바")
    study=int(input("선택지를 선택해 주세요."))
    if study==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
    elif study==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
    elif study==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
    else:
      print("잘못된 선택지입니다.")
  else:
    print("잘못된 선택집입니다.")


elif select==3:
  print("집에서 공부하기로 했다.")
  print("어떤 과목을 공부할까")
  print("1. c언어 2. 파이썬 3. 자바")

  study=int(input("선택지를 선택해 주세요."))

  if study==1:
      print("c언어를 공부했다.")
      print("c언어에 대한 지식이 늘었다!")
  elif study==2:
      print("파이썬을 공부했다.")
      print("파이썬에 대한 지식이 늘었다!")
  elif study==3:
      print("자바를 공부했다.")
      print("자바에 대한 지식이 늘었다!")
  else:
      print("잘못된 선택지입니다.")

else:
  print("잘못된 선택지입니다.")

print("이제 공부를 마치고 잠에 들었다.")

#리스트를 사용하는 이유는?
#카테고리가 비슷한 데이터를 하나의 변수에 저장하기 위해서

음료수냉장고=[]

#음료수 추가
#append는 리스트 맨 뒤에 값을 붙이는 메서드
음료수냉장고.append("콜라")
음료수냉장고.append("사이다")

#다른 리스트 추가
#extend는 리스트 맨 뒤에 리스트를 추가합니다.
추가냉장고=["오렌지주스","사이다","오렌지주스"]
음료수냉장고.extend(추가냉장고)

#음료수 개수 확인
#리스트의 길이를 확인하기 위해서 len()을 사용한다.
음료수개수=len(음료수냉장고)
print("음료수 개수:",음료수개수)

#음료수 조회
#리스트의 주소값은 0부터 시작한다.
print("첫 번째 음료수:",음료수냉장고[0])
print("두 번째 음료수:",음료수냉장고[1])
print("세 번째 음료수:",음료수냉장고[2])

#음료수가 몇 개의 사이다 음료가 있는지 확인
#개수를 확인하기 위해서는 count() 사용
print("사이다 개수:",음료수냉장고.count("사이다"),"개")

print(음료수냉장고)
#음료수냉장고 오름차순 정렬
#sort()가 리스트를 오름차순으로 정렬해줌
음료수냉장고.sort()
print(음료수냉장고)

#음료수냉장고 내림차순 정렬
#sort(reverse=True)가 리스트를 내림차순으로 정렬해줌
음료수냉장고.sort(reverse=True)
print(음료수냉장고)

#리스트 뒤집기
#리스트 안의 데이터의 순서를 뒤집고 싶으면 reverse()를 사용한다
음료수냉장고.reverse()
print(음료수냉장고)

#리스트를 비우는 메서드
음료수냉장고.clear()
음료수냉장고=[]

num=[0,3,5,6,2,1,4,7]

#초기값
print(num)

#오름차순
num.sort()
print(num)

#내림차순
num.sort(reverse=True)
print(num)

#뒤집기
num.reverse()
print(num)

#비우기
num.clear()
print(num)

i=1
while i<=10:
  print(i)
  i+=1

fruits=["apple","banana","cherry"]
for fruit in fruits:
  print(fruit)

#range 함수는 연속된 숫자를 생성하는데 사용되는 파이썬 함수이다
#range 함수를 사용하는 이유 -> 파이썬에서 for문으로 반복문을 실행 시킬때 불편한 점이 있었다.
#파이썬에서 코드를 작성할 때 특정 횟수만큼 반복해야하는 경우가 많이 존재함
#이때 while문을 통해 직접 숫자를 카운팅 해 반복문을 탈출 할 수도 있지만
#range 함수를 사용하여 측정 구간의 리스트를 생성해 for문을 사용하게 되면
#실수 없이 코드를 사용할 수 있다.

#range 함수의 문법
#range 함수는 기본적으로 3가지 옵션이 있다
#인자값은 최소 1개부터 3개까지 입력할 수 있다
#range(start, stop, step)

#인자값이 1개 일때
#range(stop)
#인자값을 1개 입력했을 경우 위와 같이 stop으로 인식 함.
#이 때 stop은 최대값을 지정하는데 최대 값을 stop-1이이서
#range 함수는 0부터 stop-1까지의 리스트를 생성한다.
#ex
range(10)#[0,1,2,3,4,5,6,7,8,9]

#인자값이 2개 일때
#range(start, stop)
#인자값을 2개 입력 했을 경우 위와 같이 start와 stop으로 인식 함.
#이 때 range 함수는 start의 값부터 stop-1까지의 값까지 리스트를 생성한다.
#ex
range(1,10)#[1,2,3,4,5,6,7,8,9]

#인자값이 3개 일때
#range(start, stop, step)
#인자값을 3개 입력했을 경우 위와 같이 start, stop, step으로 인식함.
#이 때 range 함수는 start의 값부터 stop-1까지의 값까지 step의 간격으로 리스트를 생성한다.
#ex
range(1,10,2)#[1,3,5,7,9]
range(10,0,-2)#[10,8,6,4,2]
