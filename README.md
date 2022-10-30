# unit-12-12-7-3-
per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
money = float(input("Введите сумму: "))
tkb = money / 100 * per_cent["ТКБ"]
skb = money / 100 * per_cent["СКБ"]
vtb = money / 100 * per_cent["ВТБ"]
sber = money / 100 * per_cent["СБЕР"]
deposit = [tkb, vtb, skb, sber]
deposit_spiskom = [tkb, skb, vtb, sber]
max_value = max(deposit_spiskom)
print("Максимальная сумма, которую вы можете заработать - ", round(max_value, 2))
