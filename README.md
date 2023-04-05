# demo1class parent1:
    def fun1(self):
      print("hello father")
class parent2:
    def fun2(self):
      print("hello mother")
class child(parent1 ,parent2):
    def fun3(self):
      print("hello child")
test=child()
test.fun1()
test.fun2()
test.fun3()
    



