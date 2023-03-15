email = input('Enter your string')

flag = True
if not email [0].isaplha():
  flag = False
  lenemail = len(email)
  if lenemail <= 5 or lenemail >= 30:
    flag = False
if email.find('@') == -1:
    flag = False 
else:
  atidx = email.find('@')
  if email [atidx+1:].find(".") == -1:
    flag = False
    
