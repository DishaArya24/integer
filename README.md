# integer
# given an integer,n,perform the following condidtional actions
# if n is odd,print weird
# if n is even and in the inclucive range of 2 to 5,print not weird
# if n is even and in the inclusive range of 6 to 20,print Weird
# if n is even and greater than 20,print Not Weird


import math
import os
import random
import re
import sys

if __name__ == '__main__':
    n = int(input(), strip())

    if n % 2 != 0:
        print("Weird")
    else:
        if (n > 5 and n <= 2) or n > 20:
            print("Not Weird")
        else:
            print("Weird")

