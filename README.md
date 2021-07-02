{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "37a350ca",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter First Number: 11\n",
      "Enter Second Number: 12\n",
      "Enter which operation would you like to perform?\n",
      "Enter any of these char for specific operation +,-,*,/: +\n",
      "11 + 12 : 23\n"
     ]
    }
   ],
   "source": [
    "#Program to find +,-,*,/: of given Two numbers\n",
    "#Enter Number First and second \n",
    "num1 = int(input(\"Enter First Number: \"))\n",
    "num2 = int(input(\"Enter Second Number: \"))\n",
    "\n",
    "#Enter the Operation like to perform\n",
    "print(\"Enter which operation would you like to perform?\")\n",
    "ch = input(\"Enter any of these char for specific operation +,-,*,/: \")\n",
    "\n",
    "#If No Number Enterered Result is 0\n",
    "result = 0\n",
    "\n",
    "#For Addition Click +\n",
    "if ch == '+':\n",
    "    result = num1 + num2\n",
    "    \n",
    "#For Substraction Click -\n",
    "elif ch == '-':\n",
    "    result = num1 - num2\n",
    " #For Multiplication Click *\n",
    "elif ch == '*':\n",
    "    result = num1 * num2\n",
    "#For Divition Click /\n",
    "elif ch == '/':\n",
    "    result = num1 / num2\n",
    "else:\n",
    "#Prient's If the charter is not above one +,-,*,/:\n",
    "    print(\"Input character is not recognized!\")\n",
    "\n",
    "print(num1, ch , num2, \":\", result)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "e143ec61",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter First Number: 50\n",
      "Enter Second Number: 5\n",
      "Enter which operation would you like to perform?\n",
      "Enter any of these char for specific operation +,-,*,/: /\n",
      "50 / 5 : 10.0\n"
     ]
    }
   ],
   "source": [
    "#Program to find +,-,*,/: of given Two numbers\n",
    "#Enter Number First and second \n",
    "num1 = int(input(\"Enter First Number: \"))\n",
    "num2 = int(input(\"Enter Second Number: \"))\n",
    "\n",
    "#Enter the Operation like to perform\n",
    "print(\"Enter which operation would you like to perform?\")\n",
    "ch = input(\"Enter any of these char for specific operation +,-,*,/: \")\n",
    "\n",
    "#If No Number Enterered Result is 0\n",
    "result = 0\n",
    "\n",
    "#For Addition Click +\n",
    "if ch == '+':\n",
    "    result = num1 + num2\n",
    "    \n",
    "#For Substraction Click -\n",
    "elif ch == '-':\n",
    "    result = num1 - num2\n",
    " #For Multiplication Click *\n",
    "elif ch == '*':\n",
    "    result = num1 * num2\n",
    "#For Divition Click /\n",
    "elif ch == '/':\n",
    "    result = num1 / num2\n",
    "else:\n",
    "#Prient's If the charter is not above one +,-,*,/:\n",
    "    print(\"Input character is not recognized!\")\n",
    "\n",
    "print(num1, ch , num2, \":\", result)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "a4d49726",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter 1st Number15\n",
      "Enter 2nd Number44\n",
      "Enter 3rd Number1\n",
      "44 is largest\n"
     ]
    }
   ],
   "source": [
    "#Largest of three Number\n",
    "#Enter 1st, 2nd and 3rd Number\n",
    "a = int(input(\"Enter 1st Number\"))\n",
    "b = int(input(\"Enter 2nd Number\"))\n",
    "c = int(input(\"Enter 3rd Number\"))\n",
    "\n",
    "#It Checks a is Greater than b and a is greater than c\n",
    "if a > b and a > c:\n",
    "#if Above condition satisfied it prient's a    \n",
    "    print(a, \"is largest\")\n",
    "    \n",
    "\n",
    "#It Checks b is Greater than a and b is greater than c    \n",
    "elif b > a and b > c:\n",
    "    \n",
    "#if Above condition satisfied it prient's b or in next it prient's c    \n",
    "    print(b, \"is largest\")\n",
    "else:\n",
    "    print(c, \"is largest\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "54395027",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter a Number11\n",
      "it's prime\n"
     ]
    }
   ],
   "source": [
    "#Prime Number or Not\n",
    "#A prime number is only Divdid by 1 and it self\n",
    "#Enter Number For which want to find it is orime or not\n",
    "a = int(input(\"Enter a Number\"))\n",
    "\n",
    "#Take a range from 2 to the given Number\n",
    "for i in range(2,a):\n",
    "\n",
    "#Modular Given Number with range 2 to given Number\n",
    "#if Modular Becomes 0 print it is not a prime Number or Print Not a prime\n",
    "    if a % i == 0:\n",
    "        print(\"Not prime\")\n",
    "        break\n",
    "else:\n",
    "    print(\"it's prime\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "id": "9dd43dfd",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[114, 160, 60, 27]\n",
      "[74, 97, 73, 14]\n",
      "[119, 157, 112, 23]\n"
     ]
    }
   ],
   "source": [
    "# Program to multiply two matrices using nested loops\n",
    "  \n",
    "# take a 3x3 matrix\n",
    "A = [[12, 7, 3],\n",
    "    [4, 5, 6],\n",
    "    [7, 8, 9]]\n",
    "  \n",
    "# take a 3x4 matrix    \n",
    "B = [[5, 8, 1, 2],\n",
    "    [6, 7, 3, 0],\n",
    "    [4, 5, 9, 1]]\n",
    "      \n",
    "result = [[0, 0, 0, 0],\n",
    "        [0, 0, 0, 0],\n",
    "        [0, 0, 0, 0]]\n",
    "  \n",
    "# iterating by row of A\n",
    "for i in range(len(A)):\n",
    "  \n",
    "    # iterating by coloum by B \n",
    "    for j in range(len(B[0])):\n",
    "  \n",
    "        # iterating by rows of B\n",
    "        for k in range(len(B)):\n",
    "            result[i][j] += A[i][k] * B[k][j]\n",
    "  \n",
    "for r in result:\n",
    "    print(r)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 17,
   "id": "0b661fb1",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[10, 10, 10]\n",
      "[10, 10, 10]\n",
      "[10, 10, 10]\n"
     ]
    }
   ],
   "source": [
    "\n",
    "# Program to add two matrices using nested loop\n",
    " \n",
    "X = [[1,2,3],\n",
    "    [4 ,5,6],\n",
    "    [7 ,8,9]]\n",
    " \n",
    "Y = [[9,8,7],\n",
    "    [6,5,4],\n",
    "    [3,2,1]]\n",
    " \n",
    " \n",
    "result = [[0,0,0],\n",
    "        [0,0,0],\n",
    "        [0,0,0]]\n",
    " \n",
    "# iterate through rows\n",
    "for i in range(len(X)):  \n",
    "# iterate through columns\n",
    "    for j in range(len(X[0])):\n",
    "        result[i][j] = X[i][j] + Y[i][j]\n",
    " \n",
    "for r in result:\n",
    "    print(r)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "c97f1e82",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Empty Dictionary: \n",
      "{}\n",
      "\n",
      "Dictionary with the use of dict(): \n",
      "{1: 'Geeks', 2: 'For', 3: 'Geeks'}\n",
      "\n",
      "Dictionary with each item as a pair: \n",
      "{1: 'Geeks', 2: 'For'}\n"
     ]
    }
   ],
   "source": [
    "# Creating an Dictionary\n",
    "Dict = {}\n",
    "print(\"Empty Dictionary: \")\n",
    "print(Dict)\n",
    " \n",
    "# Creating a Dictionary\n",
    "# with dict() method\n",
    "Dict = dict({1: 'Geeks', 2: 'For', 3:'Geeks'})\n",
    "print(\"\\nDictionary with the use of dict(): \")\n",
    "print(Dict)\n",
    " \n",
    "# Creating a Dictionary\n",
    "# with each item as a Pair\n",
    "Dict = dict([(1, 'Geeks'), (2, 'For')])\n",
    "print(\"\\nDictionary with each item as a pair: \")\n",
    "print(Dict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "9d87500e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "('tuple', False, 3.2, 1)\n"
     ]
    }
   ],
   "source": [
    "#Create a tuple with different data types\n",
    "tuplex = (\"tuple\", False, 3.2, 1)\n",
    "print(tuplex)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "id": "138b8690",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "11\n",
      "300\n",
      "22\n"
     ]
    }
   ],
   "source": [
    "# a list of numbers\n",
    "numbers = [11, 22, 33, 100, 200, 300]\n",
    "\n",
    "# prints 11\n",
    "print(numbers[0])\n",
    "\n",
    "# prints 300\n",
    "print(numbers[5])\n",
    "\n",
    "# prints 22\n",
    "print(numbers[1])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "id": "4b3153cb",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "(1, [9, 8, 7], 'World')\n",
      "(1, [9, 8, 99], 'World')\n"
     ]
    }
   ],
   "source": [
    "#Changing Element in list using Touple\n",
    "my_data = (1, [9, 8, 7], \"World\")\n",
    "print(my_data)\n",
    "\n",
    "# changing the element of the list\n",
    "# this is valid because list is mutable\n",
    "my_data[1][2] = 99\n",
    "print(my_data)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "id": "21fce038",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter Year: 2020\n",
      "2020 is a Leap Year\n"
     ]
    }
   ],
   "source": [
    "# User enters the year\n",
    "year = int(input(\"Enter Year: \"))\n",
    "\n",
    "# Leap Year Check\n",
    "if year % 4 == 0 and year % 100 != 0:\n",
    "    print(year, \"is a Leap Year\")\n",
    "elif year % 100 == 0:\n",
    "    print(year, \"is not a Leap Year\")\n",
    "elif year % 400 ==0:\n",
    "    print(year, \"is a Leap Year\")\n",
    "else:\n",
    "    print(year, \"is not a Leap Year\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "id": "6a763471",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "4\n",
      "7\n"
     ]
    }
   ],
   "source": [
    "#Loop Program\n",
    "num = 1\n",
    "# loop will repeat itself as long as\n",
    "# num < 10 remains true\n",
    "while num < 10:\n",
    "    print(num)\n",
    "    #incrementing the value of num\n",
    "    num = num + 3"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 15,
   "id": "6efc3671",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "True\n",
      "True\n",
      "False\n"
     ]
    }
   ],
   "source": [
    "# Set Example\n",
    "myset = {\"hi\", 2, \"bye\", \"Hello World\"}\n",
    "\n",
    "# checking whether 2 is in myset\n",
    "print(2 in myset)\n",
    "\n",
    "# checking whether \"hi\" is in myset\n",
    "print(\"hi\" in myset)\n",
    "\n",
    "# checking whether \"BeginnersBook\" is in myset\n",
    "print(\"BeginnersBook\" in myset)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "id": "4f980605",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2\n",
      "hi\n",
      "bye\n",
      "Hello World\n"
     ]
    }
   ],
   "source": [
    "# Set Example\n",
    "myset = {\"hi\", 2, \"bye\", \"Hello World\"}\n",
    "\n",
    "# loop through the elements of myset\n",
    "for a in myset:\n",
    "    print(a)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "fc2e3fac",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
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
   "version": "3.8.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
