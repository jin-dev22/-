#노마드코더 파이썬 웹 스크래퍼 만들기
"""
plus 더하기
minus 빼기
times 곱하기
division 나누기
negation 부정
power 제곱
reminder 나머지
"""

def intro_select(intro):
  if intro == 0:
    class plus():
   
   elif intro == 1:
     class minus():
   
      elif intro == 2:
        class division():
          
        elif intro == 3:
          class negation():
            
          elif intro == 4:
            class power():
              
            else intro == 5:
              class reminder():

intro = int(input("고르세요: 더하기 = 0, 빼기 = 1, 곱하기 = 2, 나누기 = 3, 부정 = 4, 제곱 = 5, 나머지 = 6"))

def getnumber(a,b):
  a = int(input("첫 번째 수를 입력하세요."))
  b = int(input("두 번째 수를 입력하세요."))

class plus():

  getnumber(a,b)

  def f_plus(a,b):
   return a + b
  print(f_plus(a,b))

class minus():

 getnumber(a,b)

  def f_minus(a,b):
   return a-b
  print(f_minus(a,b))

class times():

 getnumber(a,b)

  def f_times(a,b):
   return a*b
  print(f_times(a,b))

class division():

  getnumber(a,b)

  def f_division(a,b):
   return a/b
  print(f_division(a,b))

class negation():

  a = int(input("숫자를 입력하세요."))

  def f_negation(a):
   return -int(a)
  print(f_negation(a,b))


class power():

  a = int(input("숫자를 입력하세요."))
  b = int(input("거듭제곱 할 횟수를 입력하세요."))

  def f_power(a,b):
   return a**b
  print(f_power(a,b))
  

class reminder():

  getnumber(a,b)

  def f_reminder(a,b):
   return a//b
  print(f_reminder(a,b))
