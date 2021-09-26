#create by NosferStudios
#this program will is to management game master


from tkinter import *
import pyautogui as pg
import time
import os

pastaApp=os.path.dirname(__file__)


Tk()



move="move "



def moverKefra():
    

    time.sleep(1)
    pg.write(move+'3250 1702')


def moverReinoRed():
    pg.alert("Seu computador será usado pelo Macro")
    time.sleep(1)
    pg.write(move+'3250 1702')

def moverReinoBlue():
    time.sleep(1)
    pg.write(move+'3250 1702')

def moverUxmal():
    time.sleep(1)
    pg.write(move+'3250 1702')






janela=Tk()
#janela.geometry('800x600')
janela.title('ToolsWydGM')


#imgLogo=PhotoImage(file=pastaApp+"\\bg.png")
#l_logo=Label(janela, image=imgLogo)
#l_logo.place(x=0, y=0 )


#login_btn = PhotoImage(file='images/BtnWYD.png')

#img_label= Label(janela,image=login_btn)
#img_label.pack(pady=30)



BttMoveReinoRed=Button(janela,text= 'MoverReino Red', command=moverReinoRed)
BttMoveReinoRed.grid(row=5, column=2, padx= 10)

BttMoveReinoBlue=Button(janela,text= 'MoverReino Blue', command=moverReinoBlue)
BttMoveReinoBlue.grid(row=5, column=6)

BtnKefra=Button(janela,text= 'MoverReino Blue', command=moverKefra)
BtnKefra.grid(row=9, column=2)

BtnUxmal=Button(janela,text= 'MoverReino Blue', command=moverUxmal)
BtnUxmal.grid(row=9, column=6)

BtnUxmal=Button(janela,text= 'MoverReino Blue', command=moverUxmal)
BtnUxmal.grid(row=9, column=6)



janela = mainloop()

