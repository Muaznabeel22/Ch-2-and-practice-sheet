# Ch-2-and-practice-sheet{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "15\n",
      "24.333333333333332\n",
      "5\n",
      "38\n",
      "1024\n",
      "3\n",
      "29.95\n"
     ]
    }
   ],
   "source": [
    "#Q2\n",
    "#2.1(a)\n",
    "x=1+2+3+4+5\n",
    "print(x)\n",
    "#b\n",
    "x=(23+19+31)/3\n",
    "print(x)\n",
    "#c\n",
    "x=403//73\n",
    "print(x)\n",
    "#d\n",
    "x=403%73\n",
    "print(x)\n",
    "#E\n",
    "y=(2**10)\n",
    "print(y)\n",
    "#F\n",
    "x=abs (54 - 57 )\n",
    "print(x)\n",
    "#g\n",
    "y= min(34.99, 29.95, 31.50)\n",
    "print(y)\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "False\n",
      "True\n",
      "True\n",
      "False\n",
      "True\n",
      "False\n",
      "True\n"
     ]
    }
   ],
   "source": [
    "#2.2\n",
    "#(a)\n",
    "x=2 + 2 < 4\n",
    "print(x)\n",
    "#(b)\n",
    "x=7 // 3 == 1 + 1\n",
    "print(x)\n",
    "#(c)\n",
    "x=3**2 + 4**2 == 25\n",
    "print(x)\n",
    "#(d)\n",
    "x=2 + 4 + 6 > 12 \n",
    "print(x)\n",
    "#e\n",
    "x=1387 % 19 == 0\n",
    "print(x)\n",
    "#f\n",
    "x=31 % 2 == 0 \n",
    "print(x)\n",
    "#g\n",
    "x=min(34.99, 29.95, 31.50) < 30.00\n",
    "print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3\n",
      "4\n",
      "25\n"
     ]
    }
   ],
   "source": [
    "#2.3\n",
    "#a\n",
    "a = 3\n",
    "print(a)\n",
    "#b\n",
    "b = 4\n",
    "print(b)\n",
    "#c\n",
    "c = a * a + b * b\n",
    "print(c)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "antbatcod\n",
      "antantantantantantantantantant\n",
      "antbatbatcodcodcod\n",
      "antbatantbatantbatantbatantbatantbatantbat\n",
      "batbatcodbatbatcodbatbatcod\n"
     ]
    }
   ],
   "source": [
    "#2.4\n",
    "s1 = 'ant'\n",
    "s2 = 'bat'\n",
    "s3 = 'cod'\n",
    "#a\n",
    "x=s1 + ''+ s2 + ''+ s3\n",
    "print(x)\n",
    "#b\n",
    "x=10 * (s1 + '')\n",
    "print(x)\n",
    "#c\n",
    "x=s1 + '' + 2 * (s2 + '') + 2 * (s3 + '') + s3\n",
    "print(x)\n",
    "#d\n",
    "x=7 * (s1 + ''+ s2 + '')\n",
    "print(x)\n",
    "#e\n",
    "x=3 * (2 * s2 + s3 + '')\n",
    "print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'9'"
      ]
     },
     "execution_count": 1,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#2.5\n",
    "s = '0123456789'\n",
    "#a\n",
    "s[0]\n",
    "#b\n",
    "s[1]\n",
    "#c\n",
    "s[6]\n",
    "#d\n",
    "s[8]\n",
    "#e\n",
    "s[9]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "badminton\n",
      "racket\n"
     ]
    }
   ],
   "source": [
    "#2.6\n",
    "words = ['bat', 'ball', 'racket', 'basket', 'badminton']\n",
    "a=min(words)\n",
    "print(a)\n",
    "b=max(words)\n",
    "print(b)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# 2.7\n",
    "grades = [9, 7, 7, 10, 3, 9, 6, 6, 2]\n",
    "#part a\n",
    "a=grades.count(7)\n",
    "print(a)\n",
    "#part b\n",
    "grades[8]=4\n",
    "print(grades)\n",
    "#partc\n",
    "c=max(grades)\n",
    "print(c)\n",
    "#part d\n",
    "d=grades.sort()\n",
    "print(d)\n",
    "#part e\n",
    "e=sum(grades) / len(grades)\n",
    "print(e)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "-28\n",
      "10.651685393258427\n",
      "9.5367431640625e-07\n",
      "265716\n",
      "34\n"
     ]
    }
   ],
   "source": [
    "#2.11\n",
    "#a\n",
    "x=-7-6-5-4-3-2-1\n",
    "print(x)\n",
    "#b\n",
    "import math\n",
    "total_kids=17+24+21+27\n",
    "avg=((17*9)+(24*10)+(21*11)+(27*12))/total_kids\n",
    "print(avg)\n",
    "#c\n",
    "import math\n",
    "x=2**-20\n",
    "print(x)\n",
    "#d\n",
    "x=61*4356\n",
    "print(x)\n",
    "#e\n",
    "x=4365%61\n",
    "print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "-+\n",
      "-+-\n",
      "+--\n",
      "+--+--\n",
      "+--+--+--+--+--+--+--+--+--+--+\n",
      "+-+++--+-+++--+-+++--+-+++--+-+++--\n"
     ]
    }
   ],
   "source": [
    "#2.12\n",
    "\n",
    "s1= '-'\n",
    "s2= '+'\n",
    "x1=s1+s2\n",
    "x2=s1+s2+s1\n",
    "x3=s2+s1+s1\n",
    "x4=s2+s1+s1+s2+s1+s1\n",
    "x5=s2+s1+s1+s2+s1+s1+s2+s1+s1+s2+s1+s1+s2+s1+s1+s2+s1+s1+s2+s1+s1+s2+s1+s1+s2+s1+s1+s2+s1+s1+s2 \n",
    "x6=s2+s1+s2+s2+s2+s1+s1+s2+s1+s2+s2+s2+s1+s1+s2+s1+s2+s2+s2+s1+s1+s2+s1+s2+s2+s2+s1+s1+s2+s1+s2+s2+s2+s1+s1\n",
    "print(x1)\n",
    "print(x2)\n",
    "print(x3)\n",
    "print(x4)\n",
    "print(x5)\n",
    "print(x6)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 30,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "abcdefghijklmnopqrstuvwxyz\n"
     ]
    }
   ],
   "source": [
    "#2.13\n",
    "\n",
    "s='abcdefghijklmnopqrstuvwxyz'\n",
    "print(s)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 31,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "(True, False, False, False, False, False)"
      ]
     },
     "execution_count": 31,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#2.14\n",
    "s='goodbye'\n",
    "s[0] == 'g',s[6] == 'g',(s[0] == 'g' and s[1] == 'a'),s[-2] == 'x',s[0] == s[-1],s[-4:] == \"tion\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 37,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "5\n",
      "6\n",
      "0.45454545454545453\n",
      "None\n"
     ]
    }
   ],
   "source": [
    "# 2.19\n",
    "\n",
    "answers = ['Y', 'N', 'N', 'Y', 'N', 'Y', 'Y', 'Y', 'N', 'N', 'N']\n",
    "numYes = answers.count('Y')\n",
    "numNo = answers.count('N')\n",
    "percentYes = answers.count('Y')/len(answers)\n",
    "x=answers.sort()\n",
    "print(numYes)\n",
    "print(numNo)\n",
    "print(percentYes)\n",
    "print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'pot'"
      ]
     },
     "execution_count": 40,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#2.20\n",
    "s='top'\n",
    "s[::-1]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 41,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'nm'"
      ]
     },
     "execution_count": 41,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#2.21\n",
    "s='nabeel'\n",
    "t='muaz'\n",
    "s[0]+t[0]\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "a) ((2 + 3) == 4) or (a >= 5)\n",
      "b) (((lst[1]) * (-3)) < (-10)) == 0\n",
      "c) (((lst[1]) * (-3)) < (-10)) in [0, True]\n",
      "d) 2 * (3**2)\n",
      "e) (4 / 2) in [1, 2, 3]\n"
     ]
    }
   ],
   "source": [
    "#2.8\n",
    "print('a)','((2 + 3) == 4) or (a >= 5)')\n",
    "print('b)','(((lst[1]) * (-3)) < (-10)) == 0' )\n",
    "print('c)','(((lst[1]) * (-3)) < (-10)) in [0, True]')\n",
    "print('d)','2 * (3**2)')\n",
    "print('e)','(4 / 2) in [1, 2, 3]')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "a) 0 ,which is int valued\n",
      "b) 18.0 ,which is float\n",
      "c) 2 ,which is integer\n",
      "d) True ,which is bool valued\n"
     ]
    }
   ],
   "source": [
    "#2.9\n",
    "print('a)',False + False,\",which is int valued\")\n",
    "print('b)',2 * 3**2.0 ,',which is float')\n",
    "print('c)', 4 // 2 + 4 % 2 ,',which is integer')\n",
    "print('d)',2 + 3 == 4 or 5 >= 5,',which is bool valued')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "a) sqrt(a**2 + b**2)\n",
      "b) sqrt(a**2 + b**2) == 5\n",
      "c) pi * a**2\n",
      "d) (x - a)**2 + (y - b)**2 < r**2\n"
     ]
    }
   ],
   "source": [
    "#2.10\n",
    "from math import pi\n",
    "\n",
    "print('a)','sqrt(a**2 + b**2)')\n",
    "print('b)','sqrt(a**2 + b**2) == 5' )\n",
    "print('c)','pi * a**2')\n",
    "print('d)','(x - a)**2 + (y - b)**2 < r**2')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "number of character in anachronistically is : 17\n",
      "number of character in counterintuitive is : 16\n",
      "The number of characters in the word anachronistically is 1 more than the number of characters in the word counterintuitive\n",
      "\n",
      "\n",
      "sorting of dictionary gives words in this order: \n",
      "['misinterpretation', 'misrepresentation']\n",
      "\n",
      "\n",
      "number of time e appear in floccinaucinihilipilification is 0\n",
      "\n",
      "\n",
      "number of character in counterrevolution is :17\n",
      "sum of number of character in counter and resolution is :17\n"
     ]
    }
   ],
   "source": [
    "#2.15\n",
    "#a\n",
    "x = \"anachronistically\"\n",
    "y = \"counterintuitive\"\n",
    "\n",
    "print(\"number of character in anachronistically is : \" +str(len(x)))\n",
    "print(\"number of character in counterintuitive is : \" +str(len(y)))\n",
    "print(\"The number of characters in the word anachronistically is \" +str(len(x)-len(y))+ \" more than the number of characters in the word counterintuitive\" )\n",
    "#b\n",
    "dictionary = ['misrepresentation', 'misinterpretation' ] \n",
    "dictionary.sort()\n",
    "print(\"\\n\\nsorting of dictionary gives words in this order: \") \n",
    "print(dictionary )\n",
    "#c\n",
    "word='floccinaucinihilipilification' \n",
    "print(\"\\n\\nnumber of time e appear in floccinaucinihilipilification is \" +str(word.count(\"e\")))\n",
    "#d\n",
    "word_1='counterrevolution' \n",
    "word_2='counter' \n",
    "word_3='resolution'\n",
    "print(\"\\n\\nnumber of character in counterrevolution is :\" +str(len(word_1)) ) \n",
    "print(\"sum of number of character in counter and resolution is :\" +str(len(word_2)+(len( word_3) )))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 15,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "John Fitzgerald Kennedy\n"
     ]
    }
   ],
   "source": [
    "#2.16\n",
    "#a\n",
    "a= 6\n",
    "b= 7\n",
    "#b\n",
    "c= (a+b)/2\n",
    "#c\n",
    "inventory = [\"paper\",\"pencil\",\"staples\"]\n",
    "#d\n",
    "first = \"John\"\n",
    "middle = \"Fitzgerald\"\n",
    "last = \"Kennedy\"\n",
    "#e\n",
    "full_name = (first+\" \"+middle+\" \"+last)\n",
    "print(full_name)\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "a) True\n",
      "b) False\n",
      "c) True\n",
      "d) True\n",
      "e) False\n",
      "f) False\n"
     ]
    }
   ],
   "source": [
    "#2.17\n",
    "#a\n",
    "print(\"a)\",((17-9)<10))\n",
    "#b\n",
    "print(\"b)\",len(inventory)==5 * len(full_name))\n",
    "#c\n",
    "print(\"c)\",c <= 24)\n",
    "#d\n",
    "print(\"d)\",6.75 > a and 6.75 < b)\n",
    "#e\n",
    "print(\"e)\",len(middle)>len(first) and len(middle)<len(last))\n",
    "#f\n",
    "print(\"f)\",len(inventory)==0 or len(inventory)>10)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "a) ['rose', 'bougainvillea', 'yucca', 'marigold', 'daylilly', 'lilly of the valley']\n",
      "b) False\n",
      "c) ['rose', 'bougainvillea', 'yucca']\n",
      "d) ['rose']\n"
     ]
    }
   ],
   "source": [
    "#2.18\n",
    "#a\n",
    "flowers = ['rose', 'bougainvillea','yucca', 'marigold', 'daylilly','lilly of the valley']\n",
    "#b\n",
    "print('a)',flowers)\n",
    "print('b)','potato' in flowers)\n",
    "#c\n",
    "thorny=flowers[:3]\n",
    "print('c)',thorny)\n",
    "#d\n",
    "poisnous = flowers[:1]\n",
    "print('d)',poisnous)\n",
    "dangerous = thorny + poisnous"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 19,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "14\n"
     ]
    }
   ],
   "source": [
    "#2.22\n",
    "lst = [3, 7, -2, 12]\n",
    "print(max(lst)-min(lst))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 20,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[4, 4, 2, 2, 1]\n"
     ]
    }
   ],
   "source": [
    "#2.24\n",
    "grades = ['B','B','F','C','B','A','A','D','C','D','A','A','B']\n",
    "count = [grades.count('A'),grades.count('B'),grades.count('C'),grades.count('D'),grades.count('F')]\n",
    "print(count)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[4, 4, 2, 2, 1]\n"
     ]
    }
   ],
   "source": [
    "#2.25 \n",
    "#2.24 same as 2.25\n",
    "grades = ('B','B','F','C','B','A','A','D','C','D','A','A','B')\n",
    "count = [grades.count('A'),grades.count('B'),grades.count('C'),grades.count('D'),grades.count('F')]\n",
    "print(count)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "muaz nabeel\n"
     ]
    }
   ],
   "source": [
    "#2.30\n",
    "name=(\"muaz nabeel\")\n",
    "print(name)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Practice sheet\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0.8939966636005579 -0.4480736161291701 1.6197751905438615 3.0 0.7853981633974483 0.11971385039877737 2.718281828459045 0.3428282544153939 729.0 3.141592653589793\n"
     ]
    }
   ],
   "source": [
    "#Q1\n",
    "#Time tag (15min)\n",
    "import math\n",
    "\n",
    "no_1=math.sin(90)\n",
    "no_2=math.cos(90)\n",
    "no_3=math.tan(45)\n",
    "no_4=math.sqrt(9)\n",
    "no_5=math.radians(45)\n",
    "no_6=math.asinh(0.12)\n",
    "no_7=math.e\n",
    "no_8=math.atanh(0.33)\n",
    "no_9=math.pow(9,3)\n",
    "no_10=math.pi\n",
    "print(no_1,no_2,no_3,no_4,no_5,no_6,no_7,no_8,no_9,no_10)\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Help on built-in module math:\n",
      "\n",
      "NAME\n",
      "    math\n",
      "\n",
      "DESCRIPTION\n",
      "    This module is always available.  It provides access to the\n",
      "    mathematical functions defined by the C standard.\n",
      "\n",
      "FUNCTIONS\n",
      "    acos(x, /)\n",
      "        Return the arc cosine (measured in radians) of x.\n",
      "    \n",
      "    acosh(x, /)\n",
      "        Return the inverse hyperbolic cosine of x.\n",
      "    \n",
      "    asin(x, /)\n",
      "        Return the arc sine (measured in radians) of x.\n",
      "    \n",
      "    asinh(x, /)\n",
      "        Return the inverse hyperbolic sine of x.\n",
      "    \n",
      "    atan(x, /)\n",
      "        Return the arc tangent (measured in radians) of x.\n",
      "    \n",
      "    atan2(y, x, /)\n",
      "        Return the arc tangent (measured in radians) of y/x.\n",
      "        \n",
      "        Unlike atan(y/x), the signs of both x and y are considered.\n",
      "    \n",
      "    atanh(x, /)\n",
      "        Return the inverse hyperbolic tangent of x.\n",
      "    \n",
      "    ceil(x, /)\n",
      "        Return the ceiling of x as an Integral.\n",
      "        \n",
      "        This is the smallest integer >= x.\n",
      "    \n",
      "    copysign(x, y, /)\n",
      "        Return a float with the magnitude (absolute value) of x but the sign of y.\n",
      "        \n",
      "        On platforms that support signed zeros, copysign(1.0, -0.0)\n",
      "        returns -1.0.\n",
      "    \n",
      "    cos(x, /)\n",
      "        Return the cosine of x (measured in radians).\n",
      "    \n",
      "    cosh(x, /)\n",
      "        Return the hyperbolic cosine of x.\n",
      "    \n",
      "    degrees(x, /)\n",
      "        Convert angle x from radians to degrees.\n",
      "    \n",
      "    erf(x, /)\n",
      "        Error function at x.\n",
      "    \n",
      "    erfc(x, /)\n",
      "        Complementary error function at x.\n",
      "    \n",
      "    exp(x, /)\n",
      "        Return e raised to the power of x.\n",
      "    \n",
      "    expm1(x, /)\n",
      "        Return exp(x)-1.\n",
      "        \n",
      "        This function avoids the loss of precision involved in the direct evaluation of exp(x)-1 for small x.\n",
      "    \n",
      "    fabs(x, /)\n",
      "        Return the absolute value of the float x.\n",
      "    \n",
      "    factorial(x, /)\n",
      "        Find x!.\n",
      "        \n",
      "        Raise a ValueError if x is negative or non-integral.\n",
      "    \n",
      "    floor(x, /)\n",
      "        Return the floor of x as an Integral.\n",
      "        \n",
      "        This is the largest integer <= x.\n",
      "    \n",
      "    fmod(x, y, /)\n",
      "        Return fmod(x, y), according to platform C.\n",
      "        \n",
      "        x % y may differ.\n",
      "    \n",
      "    frexp(x, /)\n",
      "        Return the mantissa and exponent of x, as pair (m, e).\n",
      "        \n",
      "        m is a float and e is an int, such that x = m * 2.**e.\n",
      "        If x is 0, m and e are both 0.  Else 0.5 <= abs(m) < 1.0.\n",
      "    \n",
      "    fsum(seq, /)\n",
      "        Return an accurate floating point sum of values in the iterable seq.\n",
      "        \n",
      "        Assumes IEEE-754 floating point arithmetic.\n",
      "    \n",
      "    gamma(x, /)\n",
      "        Gamma function at x.\n",
      "    \n",
      "    gcd(x, y, /)\n",
      "        greatest common divisor of x and y\n",
      "    \n",
      "    hypot(x, y, /)\n",
      "        Return the Euclidean distance, sqrt(x*x + y*y).\n",
      "    \n",
      "    isclose(a, b, *, rel_tol=1e-09, abs_tol=0.0)\n",
      "        Determine whether two floating point numbers are close in value.\n",
      "        \n",
      "          rel_tol\n",
      "            maximum difference for being considered \"close\", relative to the\n",
      "            magnitude of the input values\n",
      "          abs_tol\n",
      "            maximum difference for being considered \"close\", regardless of the\n",
      "            magnitude of the input values\n",
      "        \n",
      "        Return True if a is close in value to b, and False otherwise.\n",
      "        \n",
      "        For the values to be considered close, the difference between them\n",
      "        must be smaller than at least one of the tolerances.\n",
      "        \n",
      "        -inf, inf and NaN behave similarly to the IEEE 754 Standard.  That\n",
      "        is, NaN is not close to anything, even itself.  inf and -inf are\n",
      "        only close to themselves.\n",
      "    \n",
      "    isfinite(x, /)\n",
      "        Return True if x is neither an infinity nor a NaN, and False otherwise.\n",
      "    \n",
      "    isinf(x, /)\n",
      "        Return True if x is a positive or negative infinity, and False otherwise.\n",
      "    \n",
      "    isnan(x, /)\n",
      "        Return True if x is a NaN (not a number), and False otherwise.\n",
      "    \n",
      "    ldexp(x, i, /)\n",
      "        Return x * (2**i).\n",
      "        \n",
      "        This is essentially the inverse of frexp().\n",
      "    \n",
      "    lgamma(x, /)\n",
      "        Natural logarithm of absolute value of Gamma function at x.\n",
      "    \n",
      "    log(...)\n",
      "        log(x, [base=math.e])\n",
      "        Return the logarithm of x to the given base.\n",
      "        \n",
      "        If the base not specified, returns the natural logarithm (base e) of x.\n",
      "    \n",
      "    log10(x, /)\n",
      "        Return the base 10 logarithm of x.\n",
      "    \n",
      "    log1p(x, /)\n",
      "        Return the natural logarithm of 1+x (base e).\n",
      "        \n",
      "        The result is computed in a way which is accurate for x near zero.\n",
      "    \n",
      "    log2(x, /)\n",
      "        Return the base 2 logarithm of x.\n",
      "    \n",
      "    modf(x, /)\n",
      "        Return the fractional and integer parts of x.\n",
      "        \n",
      "        Both results carry the sign of x and are floats.\n",
      "    \n",
      "    pow(x, y, /)\n",
      "        Return x**y (x to the power of y).\n",
      "    \n",
      "    radians(x, /)\n",
      "        Convert angle x from degrees to radians.\n",
      "    \n",
      "    remainder(x, y, /)\n",
      "        Difference between x and the closest integer multiple of y.\n",
      "        \n",
      "        Return x - n*y where n*y is the closest integer multiple of y.\n",
      "        In the case where x is exactly halfway between two multiples of\n",
      "        y, the nearest even value of n is used. The result is always exact.\n",
      "    \n",
      "    sin(x, /)\n",
      "        Return the sine of x (measured in radians).\n",
      "    \n",
      "    sinh(x, /)\n",
      "        Return the hyperbolic sine of x.\n",
      "    \n",
      "    sqrt(x, /)\n",
      "        Return the square root of x.\n",
      "    \n",
      "    tan(x, /)\n",
      "        Return the tangent of x (measured in radians).\n",
      "    \n",
      "    tanh(x, /)\n",
      "        Return the hyperbolic tangent of x.\n",
      "    \n",
      "    trunc(x, /)\n",
      "        Truncates the Real x to the nearest Integral toward 0.\n",
      "        \n",
      "        Uses the __trunc__ magic method.\n",
      "\n",
      "DATA\n",
      "    e = 2.718281828459045\n",
      "    inf = inf\n",
      "    nan = nan\n",
      "    pi = 3.141592653589793\n",
      "    tau = 6.283185307179586\n",
      "\n",
      "FILE\n",
      "    (built-in)\n",
      "\n",
      "\n",
      "Help on class int in module builtins:\n",
      "\n",
      "class int(object)\n",
      " |  int([x]) -> integer\n",
      " |  int(x, base=10) -> integer\n",
      " |  \n",
      " |  Convert a number or string to an integer, or return 0 if no arguments\n",
      " |  are given.  If x is a number, return x.__int__().  For floating point\n",
      " |  numbers, this truncates towards zero.\n",
      " |  \n",
      " |  If x is not a number or if base is given, then x must be a string,\n",
      " |  bytes, or bytearray instance representing an integer literal in the\n",
      " |  given base.  The literal can be preceded by '+' or '-' and be surrounded\n",
      " |  by whitespace.  The base defaults to 10.  Valid bases are 0 and 2-36.\n",
      " |  Base 0 means to interpret the base from the string as an integer literal.\n",
      " |  >>> int('0b100', base=0)\n",
      " |  4\n",
      " |  \n",
      " |  Methods defined here:\n",
      " |  \n",
      " |  __abs__(self, /)\n",
      " |      abs(self)\n",
      " |  \n",
      " |  __add__(self, value, /)\n",
      " |      Return self+value.\n",
      " |  \n",
      " |  __and__(self, value, /)\n",
      " |      Return self&value.\n",
      " |  \n",
      " |  __bool__(self, /)\n",
      " |      self != 0\n",
      " |  \n",
      " |  __ceil__(...)\n",
      " |      Ceiling of an Integral returns itself.\n",
      " |  \n",
      " |  __divmod__(self, value, /)\n",
      " |      Return divmod(self, value).\n",
      " |  \n",
      " |  __eq__(self, value, /)\n",
      " |      Return self==value.\n",
      " |  \n",
      " |  __float__(self, /)\n",
      " |      float(self)\n",
      " |  \n",
      " |  __floor__(...)\n",
      " |      Flooring an Integral returns itself.\n",
      " |  \n",
      " |  __floordiv__(self, value, /)\n",
      " |      Return self//value.\n",
      " |  \n",
      " |  __format__(self, format_spec, /)\n",
      " |      Default object formatter.\n",
      " |  \n",
      " |  __ge__(self, value, /)\n",
      " |      Return self>=value.\n",
      " |  \n",
      " |  __getattribute__(self, name, /)\n",
      " |      Return getattr(self, name).\n",
      " |  \n",
      " |  __getnewargs__(self, /)\n",
      " |  \n",
      " |  __gt__(self, value, /)\n",
      " |      Return self>value.\n",
      " |  \n",
      " |  __hash__(self, /)\n",
      " |      Return hash(self).\n",
      " |  \n",
      " |  __index__(self, /)\n",
      " |      Return self converted to an integer, if self is suitable for use as an index into a list.\n",
      " |  \n",
      " |  __int__(self, /)\n",
      " |      int(self)\n",
      " |  \n",
      " |  __invert__(self, /)\n",
      " |      ~self\n",
      " |  \n",
      " |  __le__(self, value, /)\n",
      " |      Return self<=value.\n",
      " |  \n",
      " |  __lshift__(self, value, /)\n",
      " |      Return self<<value.\n",
      " |  \n",
      " |  __lt__(self, value, /)\n",
      " |      Return self<value.\n",
      " |  \n",
      " |  __mod__(self, value, /)\n",
      " |      Return self%value.\n",
      " |  \n",
      " |  __mul__(self, value, /)\n",
      " |      Return self*value.\n",
      " |  \n",
      " |  __ne__(self, value, /)\n",
      " |      Return self!=value.\n",
      " |  \n",
      " |  __neg__(self, /)\n",
      " |      -self\n",
      " |  \n",
      " |  __or__(self, value, /)\n",
      " |      Return self|value.\n",
      " |  \n",
      " |  __pos__(self, /)\n",
      " |      +self\n",
      " |  \n",
      " |  __pow__(self, value, mod=None, /)\n",
      " |      Return pow(self, value, mod).\n",
      " |  \n",
      " |  __radd__(self, value, /)\n",
      " |      Return value+self.\n",
      " |  \n",
      " |  __rand__(self, value, /)\n",
      " |      Return value&self.\n",
      " |  \n",
      " |  __rdivmod__(self, value, /)\n",
      " |      Return divmod(value, self).\n",
      " |  \n",
      " |  __repr__(self, /)\n",
      " |      Return repr(self).\n",
      " |  \n",
      " |  __rfloordiv__(self, value, /)\n",
      " |      Return value//self.\n",
      " |  \n",
      " |  __rlshift__(self, value, /)\n",
      " |      Return value<<self.\n",
      " |  \n",
      " |  __rmod__(self, value, /)\n",
      " |      Return value%self.\n",
      " |  \n",
      " |  __rmul__(self, value, /)\n",
      " |      Return value*self.\n",
      " |  \n",
      " |  __ror__(self, value, /)\n",
      " |      Return value|self.\n",
      " |  \n",
      " |  __round__(...)\n",
      " |      Rounding an Integral returns itself.\n",
      " |      Rounding with an ndigits argument also returns an integer.\n",
      " |  \n",
      " |  __rpow__(self, value, mod=None, /)\n",
      " |      Return pow(value, self, mod).\n",
      " |  \n",
      " |  __rrshift__(self, value, /)\n",
      " |      Return value>>self.\n",
      " |  \n",
      " |  __rshift__(self, value, /)\n",
      " |      Return self>>value.\n",
      " |  \n",
      " |  __rsub__(self, value, /)\n",
      " |      Return value-self.\n",
      " |  \n",
      " |  __rtruediv__(self, value, /)\n",
      " |      Return value/self.\n",
      " |  \n",
      " |  __rxor__(self, value, /)\n",
      " |      Return value^self.\n",
      " |  \n",
      " |  __sizeof__(self, /)\n",
      " |      Returns size in memory, in bytes.\n",
      " |  \n",
      " |  __str__(self, /)\n",
      " |      Return str(self).\n",
      " |  \n",
      " |  __sub__(self, value, /)\n",
      " |      Return self-value.\n",
      " |  \n",
      " |  __truediv__(self, value, /)\n",
      " |      Return self/value.\n",
      " |  \n",
      " |  __trunc__(...)\n",
      " |      Truncating an Integral returns itself.\n",
      " |  \n",
      " |  __xor__(self, value, /)\n",
      " |      Return self^value.\n",
      " |  \n",
      " |  bit_length(self, /)\n",
      " |      Number of bits necessary to represent self in binary.\n",
      " |      \n",
      " |      >>> bin(37)\n",
      " |      '0b100101'\n",
      " |      >>> (37).bit_length()\n",
      " |      6\n",
      " |  \n",
      " |  conjugate(...)\n",
      " |      Returns self, the complex conjugate of any int.\n",
      " |  \n",
      " |  to_bytes(self, /, length, byteorder, *, signed=False)\n",
      " |      Return an array of bytes representing an integer.\n",
      " |      \n",
      " |      length\n",
      " |        Length of bytes object to use.  An OverflowError is raised if the\n",
      " |        integer is not representable with the given number of bytes.\n",
      " |      byteorder\n",
      " |        The byte order used to represent the integer.  If byteorder is 'big',\n",
      " |        the most significant byte is at the beginning of the byte array.  If\n",
      " |        byteorder is 'little', the most significant byte is at the end of the\n",
      " |        byte array.  To request the native byte order of the host system, use\n",
      " |        `sys.byteorder' as the byte order value.\n",
      " |      signed\n",
      " |        Determines whether two's complement is used to represent the integer.\n",
      " |        If signed is False and a negative integer is given, an OverflowError\n",
      " |        is raised.\n",
      " |  \n",
      " |  ----------------------------------------------------------------------\n",
      " |  Class methods defined here:\n",
      " |  \n",
      " |  from_bytes(bytes, byteorder, *, signed=False) from builtins.type\n",
      " |      Return the integer represented by the given array of bytes.\n",
      " |      \n",
      " |      bytes\n",
      " |        Holds the array of bytes to convert.  The argument must either\n",
      " |        support the buffer protocol or be an iterable object producing bytes.\n",
      " |        Bytes and bytearray are examples of built-in objects that support the\n",
      " |        buffer protocol.\n",
      " |      byteorder\n",
      " |        The byte order used to represent the integer.  If byteorder is 'big',\n",
      " |        the most significant byte is at the beginning of the byte array.  If\n",
      " |        byteorder is 'little', the most significant byte is at the end of the\n",
      " |        byte array.  To request the native byte order of the host system, use\n",
      " |        `sys.byteorder' as the byte order value.\n",
      " |      signed\n",
      " |        Indicates whether two's complement is used to represent the integer.\n",
      " |  \n",
      " |  ----------------------------------------------------------------------\n",
      " |  Static methods defined here:\n",
      " |  \n",
      " |  __new__(*args, **kwargs) from builtins.type\n",
      " |      Create and return a new object.  See help(type) for accurate signature.\n",
      " |  \n",
      " |  ----------------------------------------------------------------------\n",
      " |  Data descriptors defined here:\n",
      " |  \n",
      " |  denominator\n",
      " |      the denominator of a rational number in lowest terms\n",
      " |  \n",
      " |  imag\n",
      " |      the imaginary part of a complex number\n",
      " |  \n",
      " |  numerator\n",
      " |      the numerator of a rational number in lowest terms\n",
      " |  \n",
      " |  real\n",
      " |      the real part of a complex number\n",
      "\n"
     ]
    }
   ],
   "source": [
    "#Q2\n",
    "#time tag(2min)\n",
    "\n",
    "help(math)\n",
    "help(int)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "11"
      ]
     },
     "execution_count": 6,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#Q3\n",
    "#time tag(4min)\n",
    "my_name='MUAZ NABEEL'\n",
    "len(my_name)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "<class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'>\n"
     ]
    }
   ],
   "source": [
    "#Q4\n",
    "#time tag (25min)\n",
    "\n",
    "name=('muaz nabeel')\n",
    "dob=('22 april 2001 ')\n",
    "cellno=('03323033990')\n",
    "email=('muazuit22@gmail.com')\n",
    "favdish=('Handdi')\n",
    "favcol=('Black and Blue')\n",
    "favmovie=('Antman')\n",
    "favflower=('jasmine')\n",
    "favgame=('cricket')\n",
    "print(type(name),type(dob),type(cellno),type(email),type(favdish),type(favcol),type(favmovie),type(favflower),type(favgame))\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "invalid syntax (<ipython-input-35-168e249bc343>, line 16)",
     "output_type": "error",
     "traceback": [
      "\u001b[1;36m  File \u001b[1;32m\"<ipython-input-35-168e249bc343>\"\u001b[1;36m, line \u001b[1;32m16\u001b[0m\n\u001b[1;33m    print(\"Total distance travelled: \",distance,\"m\")\u001b[0m\n\u001b[1;37m        ^\u001b[0m\n\u001b[1;31mSyntaxError\u001b[0m\u001b[1;31m:\u001b[0m invalid syntax\n"
     ]
    }
   ],
   "source": [
    "#Q5\n",
    "#timetag(20min)\n",
    "import math\n",
    "\n",
    "v=15\n",
    "g=9.8\n",
    "a=30\n",
    "#Formula\n",
    "height=((v**2)*(math.sin(math.pi/6)**2))/2*g\n",
    "print(\"Max height above the ground: \",height,\"m\")\n",
    "\n",
    "time=(2*v*math.sin(math.pi/6))/g\n",
    "print(\"Total time in the air: \",time,\"sec\")\n",
    "\n",
    "distance=(vo**2*(math.pi*(2/6))/g                 \n",
    "print(\"Total distance travelled: \",distance,\"m\")\n",
    "\n",
    "\n",
    "\n",
    "\n",
    "      "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.3"
  }{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Practice sheet\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0.8939966636005579 -0.4480736161291701 1.6197751905438615 3.0 0.7853981633974483 0.11971385039877737 2.718281828459045 0.3428282544153939 729.0 3.141592653589793\n"
     ]
    }
   ],
   "source": [
    "#Q1\n",
    "#Time tag (15min)\n",
    "import math\n",
    "\n",
    "no_1=math.sin(90)\n",
    "no_2=math.cos(90)\n",
    "no_3=math.tan(45)\n",
    "no_4=math.sqrt(9)\n",
    "no_5=math.radians(45)\n",
    "no_6=math.asinh(0.12)\n",
    "no_7=math.e\n",
    "no_8=math.atanh(0.33)\n",
    "no_9=math.pow(9,3)\n",
    "no_10=math.pi\n",
    "print(no_1,no_2,no_3,no_4,no_5,no_6,no_7,no_8,no_9,no_10)\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Help on built-in module math:\n",
      "\n",
      "NAME\n",
      "    math\n",
      "\n",
      "DESCRIPTION\n",
      "    This module is always available.  It provides access to the\n",
      "    mathematical functions defined by the C standard.\n",
      "\n",
      "FUNCTIONS\n",
      "    acos(x, /)\n",
      "        Return the arc cosine (measured in radians) of x.\n",
      "    \n",
      "    acosh(x, /)\n",
      "        Return the inverse hyperbolic cosine of x.\n",
      "    \n",
      "    asin(x, /)\n",
      "        Return the arc sine (measured in radians) of x.\n",
      "    \n",
      "    asinh(x, /)\n",
      "        Return the inverse hyperbolic sine of x.\n",
      "    \n",
      "    atan(x, /)\n",
      "        Return the arc tangent (measured in radians) of x.\n",
      "    \n",
      "    atan2(y, x, /)\n",
      "        Return the arc tangent (measured in radians) of y/x.\n",
      "        \n",
      "        Unlike atan(y/x), the signs of both x and y are considered.\n",
      "    \n",
      "    atanh(x, /)\n",
      "        Return the inverse hyperbolic tangent of x.\n",
      "    \n",
      "    ceil(x, /)\n",
      "        Return the ceiling of x as an Integral.\n",
      "        \n",
      "        This is the smallest integer >= x.\n",
      "    \n",
      "    copysign(x, y, /)\n",
      "        Return a float with the magnitude (absolute value) of x but the sign of y.\n",
      "        \n",
      "        On platforms that support signed zeros, copysign(1.0, -0.0)\n",
      "        returns -1.0.\n",
      "    \n",
      "    cos(x, /)\n",
      "        Return the cosine of x (measured in radians).\n",
      "    \n",
      "    cosh(x, /)\n",
      "        Return the hyperbolic cosine of x.\n",
      "    \n",
      "    degrees(x, /)\n",
      "        Convert angle x from radians to degrees.\n",
      "    \n",
      "    erf(x, /)\n",
      "        Error function at x.\n",
      "    \n",
      "    erfc(x, /)\n",
      "        Complementary error function at x.\n",
      "    \n",
      "    exp(x, /)\n",
      "        Return e raised to the power of x.\n",
      "    \n",
      "    expm1(x, /)\n",
      "        Return exp(x)-1.\n",
      "        \n",
      "        This function avoids the loss of precision involved in the direct evaluation of exp(x)-1 for small x.\n",
      "    \n",
      "    fabs(x, /)\n",
      "        Return the absolute value of the float x.\n",
      "    \n",
      "    factorial(x, /)\n",
      "        Find x!.\n",
      "        \n",
      "        Raise a ValueError if x is negative or non-integral.\n",
      "    \n",
      "    floor(x, /)\n",
      "        Return the floor of x as an Integral.\n",
      "        \n",
      "        This is the largest integer <= x.\n",
      "    \n",
      "    fmod(x, y, /)\n",
      "        Return fmod(x, y), according to platform C.\n",
      "        \n",
      "        x % y may differ.\n",
      "    \n",
      "    frexp(x, /)\n",
      "        Return the mantissa and exponent of x, as pair (m, e).\n",
      "        \n",
      "        m is a float and e is an int, such that x = m * 2.**e.\n",
      "        If x is 0, m and e are both 0.  Else 0.5 <= abs(m) < 1.0.\n",
      "    \n",
      "    fsum(seq, /)\n",
      "        Return an accurate floating point sum of values in the iterable seq.\n",
      "        \n",
      "        Assumes IEEE-754 floating point arithmetic.\n",
      "    \n",
      "    gamma(x, /)\n",
      "        Gamma function at x.\n",
      "    \n",
      "    gcd(x, y, /)\n",
      "        greatest common divisor of x and y\n",
      "    \n",
      "    hypot(x, y, /)\n",
      "        Return the Euclidean distance, sqrt(x*x + y*y).\n",
      "    \n",
      "    isclose(a, b, *, rel_tol=1e-09, abs_tol=0.0)\n",
      "        Determine whether two floating point numbers are close in value.\n",
      "        \n",
      "          rel_tol\n",
      "            maximum difference for being considered \"close\", relative to the\n",
      "            magnitude of the input values\n",
      "          abs_tol\n",
      "            maximum difference for being considered \"close\", regardless of the\n",
      "            magnitude of the input values\n",
      "        \n",
      "        Return True if a is close in value to b, and False otherwise.\n",
      "        \n",
      "        For the values to be considered close, the difference between them\n",
      "        must be smaller than at least one of the tolerances.\n",
      "        \n",
      "        -inf, inf and NaN behave similarly to the IEEE 754 Standard.  That\n",
      "        is, NaN is not close to anything, even itself.  inf and -inf are\n",
      "        only close to themselves.\n",
      "    \n",
      "    isfinite(x, /)\n",
      "        Return True if x is neither an infinity nor a NaN, and False otherwise.\n",
      "    \n",
      "    isinf(x, /)\n",
      "        Return True if x is a positive or negative infinity, and False otherwise.\n",
      "    \n",
      "    isnan(x, /)\n",
      "        Return True if x is a NaN (not a number), and False otherwise.\n",
      "    \n",
      "    ldexp(x, i, /)\n",
      "        Return x * (2**i).\n",
      "        \n",
      "        This is essentially the inverse of frexp().\n",
      "    \n",
      "    lgamma(x, /)\n",
      "        Natural logarithm of absolute value of Gamma function at x.\n",
      "    \n",
      "    log(...)\n",
      "        log(x, [base=math.e])\n",
      "        Return the logarithm of x to the given base.\n",
      "        \n",
      "        If the base not specified, returns the natural logarithm (base e) of x.\n",
      "    \n",
      "    log10(x, /)\n",
      "        Return the base 10 logarithm of x.\n",
      "    \n",
      "    log1p(x, /)\n",
      "        Return the natural logarithm of 1+x (base e).\n",
      "        \n",
      "        The result is computed in a way which is accurate for x near zero.\n",
      "    \n",
      "    log2(x, /)\n",
      "        Return the base 2 logarithm of x.\n",
      "    \n",
      "    modf(x, /)\n",
      "        Return the fractional and integer parts of x.\n",
      "        \n",
      "        Both results carry the sign of x and are floats.\n",
      "    \n",
      "    pow(x, y, /)\n",
      "        Return x**y (x to the power of y).\n",
      "    \n",
      "    radians(x, /)\n",
      "        Convert angle x from degrees to radians.\n",
      "    \n",
      "    remainder(x, y, /)\n",
      "        Difference between x and the closest integer multiple of y.\n",
      "        \n",
      "        Return x - n*y where n*y is the closest integer multiple of y.\n",
      "        In the case where x is exactly halfway between two multiples of\n",
      "        y, the nearest even value of n is used. The result is always exact.\n",
      "    \n",
      "    sin(x, /)\n",
      "        Return the sine of x (measured in radians).\n",
      "    \n",
      "    sinh(x, /)\n",
      "        Return the hyperbolic sine of x.\n",
      "    \n",
      "    sqrt(x, /)\n",
      "        Return the square root of x.\n",
      "    \n",
      "    tan(x, /)\n",
      "        Return the tangent of x (measured in radians).\n",
      "    \n",
      "    tanh(x, /)\n",
      "        Return the hyperbolic tangent of x.\n",
      "    \n",
      "    trunc(x, /)\n",
      "        Truncates the Real x to the nearest Integral toward 0.\n",
      "        \n",
      "        Uses the __trunc__ magic method.\n",
      "\n",
      "DATA\n",
      "    e = 2.718281828459045\n",
      "    inf = inf\n",
      "    nan = nan\n",
      "    pi = 3.141592653589793\n",
      "    tau = 6.283185307179586\n",
      "\n",
      "FILE\n",
      "    (built-in)\n",
      "\n",
      "\n",
      "Help on class int in module builtins:\n",
      "\n",
      "class int(object)\n",
      " |  int([x]) -> integer\n",
      " |  int(x, base=10) -> integer\n",
      " |  \n",
      " |  Convert a number or string to an integer, or return 0 if no arguments\n",
      " |  are given.  If x is a number, return x.__int__().  For floating point\n",
      " |  numbers, this truncates towards zero.\n",
      " |  \n",
      " |  If x is not a number or if base is given, then x must be a string,\n",
      " |  bytes, or bytearray instance representing an integer literal in the\n",
      " |  given base.  The literal can be preceded by '+' or '-' and be surrounded\n",
      " |  by whitespace.  The base defaults to 10.  Valid bases are 0 and 2-36.\n",
      " |  Base 0 means to interpret the base from the string as an integer literal.\n",
      " |  >>> int('0b100', base=0)\n",
      " |  4\n",
      " |  \n",
      " |  Methods defined here:\n",
      " |  \n",
      " |  __abs__(self, /)\n",
      " |      abs(self)\n",
      " |  \n",
      " |  __add__(self, value, /)\n",
      " |      Return self+value.\n",
      " |  \n",
      " |  __and__(self, value, /)\n",
      " |      Return self&value.\n",
      " |  \n",
      " |  __bool__(self, /)\n",
      " |      self != 0\n",
      " |  \n",
      " |  __ceil__(...)\n",
      " |      Ceiling of an Integral returns itself.\n",
      " |  \n",
      " |  __divmod__(self, value, /)\n",
      " |      Return divmod(self, value).\n",
      " |  \n",
      " |  __eq__(self, value, /)\n",
      " |      Return self==value.\n",
      " |  \n",
      " |  __float__(self, /)\n",
      " |      float(self)\n",
      " |  \n",
      " |  __floor__(...)\n",
      " |      Flooring an Integral returns itself.\n",
      " |  \n",
      " |  __floordiv__(self, value, /)\n",
      " |      Return self//value.\n",
      " |  \n",
      " |  __format__(self, format_spec, /)\n",
      " |      Default object formatter.\n",
      " |  \n",
      " |  __ge__(self, value, /)\n",
      " |      Return self>=value.\n",
      " |  \n",
      " |  __getattribute__(self, name, /)\n",
      " |      Return getattr(self, name).\n",
      " |  \n",
      " |  __getnewargs__(self, /)\n",
      " |  \n",
      " |  __gt__(self, value, /)\n",
      " |      Return self>value.\n",
      " |  \n",
      " |  __hash__(self, /)\n",
      " |      Return hash(self).\n",
      " |  \n",
      " |  __index__(self, /)\n",
      " |      Return self converted to an integer, if self is suitable for use as an index into a list.\n",
      " |  \n",
      " |  __int__(self, /)\n",
      " |      int(self)\n",
      " |  \n",
      " |  __invert__(self, /)\n",
      " |      ~self\n",
      " |  \n",
      " |  __le__(self, value, /)\n",
      " |      Return self<=value.\n",
      " |  \n",
      " |  __lshift__(self, value, /)\n",
      " |      Return self<<value.\n",
      " |  \n",
      " |  __lt__(self, value, /)\n",
      " |      Return self<value.\n",
      " |  \n",
      " |  __mod__(self, value, /)\n",
      " |      Return self%value.\n",
      " |  \n",
      " |  __mul__(self, value, /)\n",
      " |      Return self*value.\n",
      " |  \n",
      " |  __ne__(self, value, /)\n",
      " |      Return self!=value.\n",
      " |  \n",
      " |  __neg__(self, /)\n",
      " |      -self\n",
      " |  \n",
      " |  __or__(self, value, /)\n",
      " |      Return self|value.\n",
      " |  \n",
      " |  __pos__(self, /)\n",
      " |      +self\n",
      " |  \n",
      " |  __pow__(self, value, mod=None, /)\n",
      " |      Return pow(self, value, mod).\n",
      " |  \n",
      " |  __radd__(self, value, /)\n",
      " |      Return value+self.\n",
      " |  \n",
      " |  __rand__(self, value, /)\n",
      " |      Return value&self.\n",
      " |  \n",
      " |  __rdivmod__(self, value, /)\n",
      " |      Return divmod(value, self).\n",
      " |  \n",
      " |  __repr__(self, /)\n",
      " |      Return repr(self).\n",
      " |  \n",
      " |  __rfloordiv__(self, value, /)\n",
      " |      Return value//self.\n",
      " |  \n",
      " |  __rlshift__(self, value, /)\n",
      " |      Return value<<self.\n",
      " |  \n",
      " |  __rmod__(self, value, /)\n",
      " |      Return value%self.\n",
      " |  \n",
      " |  __rmul__(self, value, /)\n",
      " |      Return value*self.\n",
      " |  \n",
      " |  __ror__(self, value, /)\n",
      " |      Return value|self.\n",
      " |  \n",
      " |  __round__(...)\n",
      " |      Rounding an Integral returns itself.\n",
      " |      Rounding with an ndigits argument also returns an integer.\n",
      " |  \n",
      " |  __rpow__(self, value, mod=None, /)\n",
      " |      Return pow(value, self, mod).\n",
      " |  \n",
      " |  __rrshift__(self, value, /)\n",
      " |      Return value>>self.\n",
      " |  \n",
      " |  __rshift__(self, value, /)\n",
      " |      Return self>>value.\n",
      " |  \n",
      " |  __rsub__(self, value, /)\n",
      " |      Return value-self.\n",
      " |  \n",
      " |  __rtruediv__(self, value, /)\n",
      " |      Return value/self.\n",
      " |  \n",
      " |  __rxor__(self, value, /)\n",
      " |      Return value^self.\n",
      " |  \n",
      " |  __sizeof__(self, /)\n",
      " |      Returns size in memory, in bytes.\n",
      " |  \n",
      " |  __str__(self, /)\n",
      " |      Return str(self).\n",
      " |  \n",
      " |  __sub__(self, value, /)\n",
      " |      Return self-value.\n",
      " |  \n",
      " |  __truediv__(self, value, /)\n",
      " |      Return self/value.\n",
      " |  \n",
      " |  __trunc__(...)\n",
      " |      Truncating an Integral returns itself.\n",
      " |  \n",
      " |  __xor__(self, value, /)\n",
      " |      Return self^value.\n",
      " |  \n",
      " |  bit_length(self, /)\n",
      " |      Number of bits necessary to represent self in binary.\n",
      " |      \n",
      " |      >>> bin(37)\n",
      " |      '0b100101'\n",
      " |      >>> (37).bit_length()\n",
      " |      6\n",
      " |  \n",
      " |  conjugate(...)\n",
      " |      Returns self, the complex conjugate of any int.\n",
      " |  \n",
      " |  to_bytes(self, /, length, byteorder, *, signed=False)\n",
      " |      Return an array of bytes representing an integer.\n",
      " |      \n",
      " |      length\n",
      " |        Length of bytes object to use.  An OverflowError is raised if the\n",
      " |        integer is not representable with the given number of bytes.\n",
      " |      byteorder\n",
      " |        The byte order used to represent the integer.  If byteorder is 'big',\n",
      " |        the most significant byte is at the beginning of the byte array.  If\n",
      " |        byteorder is 'little', the most significant byte is at the end of the\n",
      " |        byte array.  To request the native byte order of the host system, use\n",
      " |        `sys.byteorder' as the byte order value.\n",
      " |      signed\n",
      " |        Determines whether two's complement is used to represent the integer.\n",
      " |        If signed is False and a negative integer is given, an OverflowError\n",
      " |        is raised.\n",
      " |  \n",
      " |  ----------------------------------------------------------------------\n",
      " |  Class methods defined here:\n",
      " |  \n",
      " |  from_bytes(bytes, byteorder, *, signed=False) from builtins.type\n",
      " |      Return the integer represented by the given array of bytes.\n",
      " |      \n",
      " |      bytes\n",
      " |        Holds the array of bytes to convert.  The argument must either\n",
      " |        support the buffer protocol or be an iterable object producing bytes.\n",
      " |        Bytes and bytearray are examples of built-in objects that support the\n",
      " |        buffer protocol.\n",
      " |      byteorder\n",
      " |        The byte order used to represent the integer.  If byteorder is 'big',\n",
      " |        the most significant byte is at the beginning of the byte array.  If\n",
      " |        byteorder is 'little', the most significant byte is at the end of the\n",
      " |        byte array.  To request the native byte order of the host system, use\n",
      " |        `sys.byteorder' as the byte order value.\n",
      " |      signed\n",
      " |        Indicates whether two's complement is used to represent the integer.\n",
      " |  \n",
      " |  ----------------------------------------------------------------------\n",
      " |  Static methods defined here:\n",
      " |  \n",
      " |  __new__(*args, **kwargs) from builtins.type\n",
      " |      Create and return a new object.  See help(type) for accurate signature.\n",
      " |  \n",
      " |  ----------------------------------------------------------------------\n",
      " |  Data descriptors defined here:\n",
      " |  \n",
      " |  denominator\n",
      " |      the denominator of a rational number in lowest terms\n",
      " |  \n",
      " |  imag\n",
      " |      the imaginary part of a complex number\n",
      " |  \n",
      " |  numerator\n",
      " |      the numerator of a rational number in lowest terms\n",
      " |  \n",
      " |  real\n",
      " |      the real part of a complex number\n",
      "\n"
     ]
    }
   ],
   "source": [
    "#Q2\n",
    "#time tag(2min)\n",
    "\n",
    "help(math)\n",
    "help(int)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "11"
      ]
     },
     "execution_count": 6,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#Q3\n",
    "#time tag(4min)\n",
    "my_name='MUAZ NABEEL'\n",
    "len(my_name)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "<class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'> <class 'str'>\n"
     ]
    }
   ],
   "source": [
    "#Q4\n",
    "#time tag (25min)\n",
    "\n",
    "name=('muaz nabeel')\n",
    "dob=('22 april 2001 ')\n",
    "cellno=('03323033990')\n",
    "email=('muazuit22@gmail.com')\n",
    "favdish=('Handdi')\n",
    "favcol=('Black and Blue')\n",
    "favmovie=('Antman')\n",
    "favflower=('jasmine')\n",
    "favgame=('cricket')\n",
    "print(type(name),type(dob),type(cellno),type(email),type(favdish),type(favcol),type(favmovie),type(favflower),type(favgame))\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "invalid syntax (<ipython-input-35-168e249bc343>, line 16)",
     "output_type": "error",
     "traceback": [
      "\u001b[1;36m  File \u001b[1;32m\"<ipython-input-35-168e249bc343>\"\u001b[1;36m, line \u001b[1;32m16\u001b[0m\n\u001b[1;33m    print(\"Total distance travelled: \",distance,\"m\")\u001b[0m\n\u001b[1;37m        ^\u001b[0m\n\u001b[1;31mSyntaxError\u001b[0m\u001b[1;31m:\u001b[0m invalid syntax\n"
     ]
    }
   ],
   "source": [
    "#Q5\n",
    "#timetag(20min)\n",
    "import math\n",
    "\n",
    "v=15\n",
    "g=9.8\n",
    "a=30\n",
    "#Formula\n",
    "height=((v**2)*(math.sin(math.pi/6)**2))/2*g\n",
    "print(\"Max height above the ground: \",height,\"m\")\n",
    "\n",
    "time=(2*v*math.sin(math.pi/6))/g\n",
    "print(\"Total time in the air: \",time,\"sec\")\n",
    "\n",
    "distance=(vo**2*(math.pi*(2/6))/g                 \n",
    "print(\"Total distance travelled: \",distance,\"m\")\n",
    "\n",
    "\n",
    "\n",
    "\n",
    "      "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

 },
 "nbformat": 4,
 "nbformat_minor": 2
}

}
