# Intro-To-Programming-5.14
triangle_char = input('Enter a character:\n')
triangle_height = int(input('Enter a triangle height:\n'))
x =0 
y = triangle_height
while x < y:
    x += 1
    if x == 1:
        print(triangle_char, '')
    if x == 2:
        print(triangle_char, triangle_char, '')
    if x == 3:
        print(triangle_char, triangle_char, triangle_char, '')
    if x == 4:
        print(triangle_char, triangle_char, triangle_char, triangle_char, '')
    if x == 5:
        print(triangle_char, triangle_char, triangle_char, triangle_char, triangle_char, '')
