def Python():
# python patern
    import time
    for row in range(7):
        for col in range(5):
            if ((col == 0 or col == 4) and (row != 0 and row != 3 and row <= 3)) or (
                    (row == 0 or row == 3) and (col >= 0 and col < 4)):
                print('*', end='')
            elif (row > 3 and col == 0):
                print('*', end='')
            else:
                print(end=' ')
        time.sleep(0.1)
        print()
    for row in range(7):
        for col in range(7):
            if ((col == 0 or col == 6) and row == 0) or ((col == 1 or col == 5) and row == 1) or (
                    (col == 2 or col == 4) and row == 2):
                print('*', end='')
            elif (row >= 3 and col == 3):
                print('*', end='')
            else:
                print(end=' ')
            time.sleep(0.1)
        print()


    for row in range(7):
        for col in range(7):
            if ((col == 3) and (row != 0 )) or (
                    (row == 0 ) and (col >= 0 and col <= 6)):
                print('*', end='')
            else:
                print(end=' ')
        time.sleep(0.1)
        print()

    for row in range(7):
        for col in range(6):
            if ((col == 0 or col == 5) ) or (
                    (row == 3 ) and (col > 0 and col <= 4)):
                print('*', end='')
            else:
                print(end=' ')
        time.sleep(0.1)
        print()
    for row in range(7):
        for col in range(7):
            if ((col == 0 or col == 6) and (row != 0 and row != 6)) or (
                    (row == 0 or row == 6) and (col > 0 and col <= 5)):
                print('*', end='')
            else:
                print(end=' ')
        time.sleep(0.1)
        print()

    for row in range(9):
        for col in range(9):
            if ((col == 0 or col == 7) and (row >= 0 and row <= 6)) or ((col == 1) and (row == 1)) or \
                    ((col == 2) and (row == 2)) or ((col == 3) and (row == 3)) or ((col == 4) and (row == 4)) or (
                    (col == 5) and (row == 5)) or \
                    ((col == 6) and (row == 6)):
                print('*', end='')

            else:
                print(end=' ')

        print()
        time.sleep(0.01)
        print()

Python()







