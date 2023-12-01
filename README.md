# plus-minus
#TUGAS PLUS MINUS<br>
#Nama : Rochman Putra Arifin<br>
#Nim  : 23422028<br>
#Kelas: TIF22A<br>

<h1>Case 0<br></h1>
    python3

    import math
    import os
    import random
    import re
    import sys


    def plusMinus(arr):
        n = len(arr)
        positive_count = sum(1 for num in arr if num > 0)
        negative_count = sum(1 for num in arr if num < 0)
        zero_count = n - positive_count - negative_count

        positive_ratio = positive_count / n
        negative_ratio = negative_count / n
        zero_ratio = zero_count / n

        # Print the ratios with 6 decimal places
        print("{:.8f}".format(positive_ratio))
        print("{:.8f}".format(negative_ratio))
        print("{:.8f}".format(zero_ratio))

        # Sample Input
        arr = [-4, 3, -9, 0, 4, 1]

        # Function call
        plusMinus(arr)

  <h2># Output Saya<br>
        0.500000<br>
        0.333333<br>
        0.166667<br>
  </h2>
        


<h2>Case 1</h2>

    import math
    import os
    import random
    import re
    import sys


    def plusMinus(arr):
        n = len(arr)
        positive_count = sum(1 for num in arr if num > 0)
        negative_count = sum(1 for num in arr if num < 0)
        zero_count = n - positive_count - negative_count

        positive_ratio = positive_count / n
        negative_ratio = negative_count / n
        zero_ratio = zero_count / n

        # Print the ratios with 8 decimal places
        print("{:.8f}".format(positive_ratio))
        print("{:.8f}".format(negative_ratio))
        print("{:.8f}".format(zero_ratio))

        # Sample Input
        arr = [1, 2, 3, -1, -2, -3, 0, 0]
        
        # Function call
        plusMinus(arr)

   <h2># Output Saya<br>
        0.37500000<br>
        0.37500000<br>
        0.25000000<br>
  </h2>
    
