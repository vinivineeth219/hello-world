# hello-world
tutorial of github
def fun(a,b):
    return a+b
fun(3,4)
fun(6,7)
#decorator fucntion

def deco(func):
    def inner():
        print('decorator function')
        func()
    return inner
@deco
def main():
    print("main function")
main()

