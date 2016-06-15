

This is an example of showing how to perform Karatsuba multiplication for 2 two digit numbers say x1x2 and y1y2

Eg:::::

	11
		*
	22
--------
	22
   220
--------
   242

   x1=1, x2=1 ***** y1=2, y2=2;

   x1.y1 = 1*2 = 2 (A)
   x2.y2 = 1*2 = 2 (B)
  (x1+x2).(y1+y2) = 2*4 = 8 (C)
  C-A-B = 8-2-2 = 4 (K)
  A.100 + k.10 + B = 2.100 + 4.10 + 2 = 242
  
