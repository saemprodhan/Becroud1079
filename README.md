# Becroud1079
Weighted Average
N = int(input())
for _ in range(N):
    x, y, z = map(float, input().split())
    weighted_mean = ((x * 2) + (y * 3) + (z * 5)) / 10
    print(f"{weighted_mean:.1f}")
