while True:
    euro = float(input('€ → $:'))
    multiplier = (1.17)
    dollar_count = (euro * multiplier)
    print('$', round(dollar_count, 1))