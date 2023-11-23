sub goals
========

Pupils are not sufficiently fluent with the syntax


* https://youtu.be/7vyzIqdSiwU?si=QXRNM2NoTIjjYaPz&t=1177
* Write a program that accepts input temperatures one at a time until -999 is entered, then calculates the average of all of the temperatures
* Whole program is too much - students should put in the sub goals


Coins on a grid
Build on existing knowledge

* Write a program to work out the smallest set of coins to make these (or any) amounts of money.
    * 8p
    * 28p
    * 30p
    * 48p
    * £1.39

def coins(amount):
    change=[]
    currency=[200,100,50,20,10,5,2,1]
    while currency != []:
        if amount >= currency[0]:
            change=change+[currency[0]]
            amount=amount-currency[0]
        else:
            currency=currency[1:]
    return change

Exactly the same thing as counting in binary

What if your coins were
£1.28 64p 32p 16p 8p 4p 2p 1p

Try to make the same 
    * 8p
    * 28p
    * 30p
    * 48p
    * £1.39

Coins were crazy!
Shillings, penny, farthings
What about least number of coins? 
