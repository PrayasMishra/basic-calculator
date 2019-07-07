from tkinter import *
w=Tk()
w.title("my Calculator")               
w.geometry("260x240")
exp=""
def clear():
    global exp
    exp=""
    v.set(exp)

def btnclk(n):
    global exp
    exp+=str(n);
    v.set(exp)

def calculate():
    global exp
    res=eval(exp)
    v.set(res)

v=StringVar()
E=Entry(w,text="",bg="aqua",font=("arial",18,"bold"),textvariable=v)
b0=Button(w,text="0",font=("arial",18,"bold"),command=lambda:btnclk(0))
b1=Button(w,text="1",font=("arial",18,"bold"),command=lambda:btnclk(1))
b2=Button(w,text="2",font=("arial",18,"bold"),command=lambda:btnclk(2))
b3=Button(w,text="3",font=("Arial",18,"bold"),command=lambda:btnclk(3))
b4=Button(w,text="4",font=("arial",18,"bold"),command=lambda:btnclk(4))
b5=Button(w,text="5",font=("arial",18,"bold"),command=lambda:btnclk(5))
b6=Button(w,text="6",font=("arial",18,"bold"),command=lambda:btnclk(6))
b7=Button(w,text="7",font=("arial",18,"bold"),command=lambda:btnclk(7))
b8=Button(w,text="8",font=("arial",18,"bold"),command=lambda:btnclk(8))
b9=Button(w,text="9",font=("arial",18,"bold"),command=lambda:btnclk(9))
bAns=Button(w,text="=",font=("arial",18,"bold"),command=calculate)
bReset=Button(w,text="C",font=("arial",18,"bold"),command=clear)
bPlus=Button(w,text="+",font=("arial",18,"bold"),command=lambda:btnclk('+'))
bMinus=Button(w,text="-",font=("arial",18,"bold"),command=lambda:btnclk('-'))
bTimes=Button(w,text="*",font=("arial",18,"bold"),command=lambda:btnclk('*'))
bDivide=Button(w,text="/",font=("arial",18,"bold"),command=lambda:btnclk('/'))

E.grid(row=1,column=1,columnspan=4)
b1.grid(row=2,column=1)
b2.grid(row=2,column=2)
b3.grid(row=2,column=3)
b4.grid(row=2,column=4)
b5.grid(row=3,column=1)
b6.grid(row=3,column=2)
b7.grid(row=3,column=3)
b8.grid(row=3,column=4)
b9.grid(row=4,column=1)
b0.grid(row=4,column=2)
bAns.grid(row=4,column=3)
bReset.grid(row=4,column=4)
bPlus.grid(row=5,column=1)
bMinus.grid(row=5,column=2)
bTimes.grid(row=5,column=3)
bDivide.grid(row=5,column=4)
w.mainloop()
