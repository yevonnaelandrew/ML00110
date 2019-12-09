```python
nl = []
for x in range(2000, 3201):
    if x % 7 == 0 and x % 5 != 0:
        nl.append(str(x))
print (', '.join(nl))
```

    2002, 2009, 2016, 2023, 2037, 2044, 2051, 2058, 2072, 2079, 2086, 2093, 2107, 2114, 2121, 2128, 2142, 2149, 2156, 2163, 2177, 2184, 2191, 2198, 2212, 2219, 2226, 2233, 2247, 2254, 2261, 2268, 2282, 2289, 2296, 2303, 2317, 2324, 2331, 2338, 2352, 2359, 2366, 2373, 2387, 2394, 2401, 2408, 2422, 2429, 2436, 2443, 2457, 2464, 2471, 2478, 2492, 2499, 2506, 2513, 2527, 2534, 2541, 2548, 2562, 2569, 2576, 2583, 2597, 2604, 2611, 2618, 2632, 2639, 2646, 2653, 2667, 2674, 2681, 2688, 2702, 2709, 2716, 2723, 2737, 2744, 2751, 2758, 2772, 2779, 2786, 2793, 2807, 2814, 2821, 2828, 2842, 2849, 2856, 2863, 2877, 2884, 2891, 2898, 2912, 2919, 2926, 2933, 2947, 2954, 2961, 2968, 2982, 2989, 2996, 3003, 3017, 3024, 3031, 3038, 3052, 3059, 3066, 3073, 3087, 3094, 3101, 3108, 3122, 3129, 3136, 3143, 3157, 3164, 3171, 3178, 3192, 3199
    


```python
#Write a Python program to accept the user's first and last name and then getting them printed in
#the the reverse order with a space between first name and last name.

name = input("Your name: ")

print(name[::-1])
```

    Your name: Michael Kennedy
    ydenneK leahciM
    


```python
#Write a Python program to find the volume of a sphere with diameter 12 cm.
import math
volume = 4/3*math.pi*12**3
print(volume)
```

    7238.229473870882
    


```python
#Write a program which accepts a sequence of comma-separated numbers from console and generate a list.

sequence = input("Enter comma-separared numbers: ")
sequence.split(",")
```

    Enter comma-separared numbers: 1,2,3,4,5,6,7,8,9,10
    




    ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10']




```python
for x in range(1, 6):
    if x == 5:
        for x in range(5, 0, -1):
            print(x * "*")
    else:
        print(x * "*")
```

    *
    **
    ***
    ****
    *****
    ****
    ***
    **
    *
    


```python
#Write a Python program to reverse a word after accepting the input from the user.
word = input("Enter a word: ")
print(word[::-1])
```

    Enter a word: iNeuron
    norueNi
    


```python
print("WE, THE PEOPLE OF INDIA, \n      having solemnly resolved to constitute India into a SOVEREIGN, \n              SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC \n               and to secure to all its citizens")
```

    WE, THE PEOPLE OF INDIA, 
          having solemnly resolved to constitute India into a SOVEREIGN, 
                  SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC 
                   and to secure to all its citizens
    


