```
---
psh-fractional
-- fractional math in pure sh, successor to psh-float-micro
---
Plan
-- The plan here is to devise hackish ways to do fractional math
-- for each of the base operations addition, subtraction, multiplication, & division
---
Dev Status
-- this is on pause for now; I'm really tired
---
Current Status
-- addition 100% working
-- subtraction ~80% working
---- has major issues with decimal placement
---- I have no fix for this other than flat out long subtraction
-- multiplication ~50% working
---- has a lot of issues I need to look into
-- division ~80% working 
---- issues with decimal placement
---
Tester
-- a tester is present at ./tester; it is ofc not pure sh as it compares with bc
-- additionally using it requires that $RPATH is set to ?/psh-prng/ran
---
```
