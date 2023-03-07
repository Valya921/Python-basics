"""Написать цикл для выведения на экран каждой буквы своего ФИО."""


def currency_exchange(usd):
    ref1 = usd/1.17
    return ref1
def exchange_rate_rub(usd):
    ref2 = usd*74.79  # курс рубля к доллару США на 17.02.23
    return ref2
usd = float(input("Ввести сумму в долларах США: "))

print("Сумма перевода в Euro = ",'{:.2f}'.format(currency_exchange(usd)))
print("Сумма перевода в Рубли (по курсу ЦБ РФ) = ",'{:.2f}'.format(exchange_rate_rub(usd)))
