# fermat-s-theorem
a = int(raw_input('value to use for a?\n'))
b = int(raw_input(' value to use for b?\n'))
c = int(raw_input('value to use for c?\n'))
n = int(raw_input(' value to use for n?\n'))


def check_fermat(a, b, c, n):
    if n == 2:
        return 'Pythagoras got that one already.'
    elif a**n + b**n == c**n:
        return 'Holy Smokes, Fermat was Wrong!'
    return "No, that doesn't work."

print check_fermat(a, b, c, n)
