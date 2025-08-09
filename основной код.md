# Запрашиваем ввод строки у пользователя
input_string = input("Введите строку: ")

# Проверяем длину введённой строки
if len(input_string) > 10:
    # Обрезаем строку до первых 10 символов и добавляем троеточие
    output_string = input_string[:10] + '...'
else:
    # Просто выводим исходную строку
    output_string = input_string

# Выводим итоговую строку
print(output_string)
