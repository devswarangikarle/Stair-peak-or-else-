# Stair-peak-or-else-
Input Given three space separated integers a, b, c. (0 ≤ a, b, c ≤ 9). Output Print "Stair" if the digits form a stair, "Peak" if the digits form a peak, and "Nothing" otherwise (output the strings without quotes, case specific).

a, b, c = map(int, input().split())

if a < b < c:
    print("Stair")
elif a < b and b > c:
    print("Peak")
else:
    print("Nothing")
