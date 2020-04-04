# 60 Points
```
Catalias
60

Hmmm… maybe missing a hyphen somewhere?

Note: This challenge is reset every five minutes. If you are on the wrong side of the clock, you may need to reconnect.

Connect with:

ssh user@jh2i.com -p 50004 # password is 'userpass'
```

There was a flag.txt file right there when logging in via ssh. 
Tried running cat, strings etc.. didn't work. file was owned by root so tried to get root, but that was a rabbit hole for the amount of points.

Then tried `head flag.txt` and got the flag

# FLAG :
LLS{you_let_the_cat_out_of_the_bag}