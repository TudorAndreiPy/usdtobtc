# USD TO BTC
Hello, this my valutary exchanger. You can convert USD to BTC , is simple to use and simple to understand
I hope you enjoyed!

You will need this modules to import and to have installed: bs4, request, tkinter

First, import the modules : 
  #################################
  import bs4
  import requests
  from bs4 import BeautifulSoup
  from tkinter import
  from tkinter import messagebox 
  ####################################
  
 Second, you have to :
  root = Tk()
  root.title("Stock prices app") #setting title
  root.geometry("+255+50") #i want to spawn the window here
  bg = '#97d369' #define a color
  root.configure(bg = bg) #use the color for background

 Next, you have to create the title, 2 labels, 2 entry box and one button(line 13-33 and line 57-58)
 
 After i create a function named getMeIt , here i want to get the price of bitcoin in real time
 The number contain a "," so the number can't be transformed in float so we have to replace "," with "" (line 42)
 After that, transform it in float (line43)
 
 We have to get the usd value who was inserted by the user, get it and transorm it in float (line 45)
 
 After that create the result. result = usd_value / price
 
 this is used to delete the entry and after to be enter the result with 7 decimal places:
 
 	bitcoin_entry_text.delete(0,END)
	bitcoin_entry_text.insert(0, f"%.7f" % result)
  
 Nextt create the label with the price value of bitcoin and root.mainloop()
 
 I hope that is useful! 
 
 FOR QUESTIONS DM ME ON: @tudorandreii14 
 
