x = [[4, 5, 2],
    [6, 3, 12],
    [11, 3, 7],
    [9, 6, 2]]

y = [[8, 4, 2],
    [5, 10, 13],
    [5, 2, 3],
    [7, 3, 10]]

result= [[0, 0, 0],
        [0, 0, 0],
        [0, 0, 0],
        [0, 0, 0]]

for i in range(Len(x)):
    for j in range(Len(0)):
        result[i][j] = x[i][j] + y[i][j]

for r in result:
    print(r)
