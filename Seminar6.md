// Задача 41: Пользователь вводит с клавиатуры M чисел. 
// Посчитайте, сколько чисел больше 0 ввёл пользователь.
// 0, 7, 8, -2, -2 -> 2
// 1, -7, 567, 89, 223-> 3

int Prompt(string message)
{
    System.Console.Write(message); // вывести сообщение
    string value = Console.Readline(); // Считать с консоли строчку
    int result = Convert.ToInt32(value); // Преобразовать срочку в целое число
    return result; // вернуть результат
}