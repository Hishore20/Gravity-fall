# Gravity-fall




Create a program that determines how quickly an object is traveling when it hits the ground. The user will enter the height from which the object is dropped in meters (m).

Because the object is dropped its initial speed is 0m/s. Assume that the acceleration due to gravity is 9.8m/s.

vf =squareroot(vi+2ad)

You can use the formula given above to compute the final speed, vf , when the initial speed, vi , acceleration, a, and distance, d, are known
Logic Test Case 1

Input (stdin)
45

Expected Output

The object will hit the ground at 29.70 m/s
Logic Test Case 2

Input (stdin)
148

Expected Output

The object will hit the ground at 53.86 m/s





a=int(input())
b=(2*a*9.8)**0.5
print("The object will hit the ground at %.2f"%b,"m/s")
