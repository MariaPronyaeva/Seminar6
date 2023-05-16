// Задача 41: Пользователь вводит с клавиатуры M чисел. 
// Посчитайте, сколько чисел больше 0 ввёл пользователь.
// 0, 7, 8, -2, -2 -> 2
// 1, -7, 567, 89, 223-> 3

// Считать число с консоли
int Prompt(string message)
{
    System.Console.Write(message); // вывести сообщение
    string value = Console.Readline(); // Считать с консоли строчку
    int result = Convert.ToInt32(value); // Преобразовать срочку в целое число
    return result; // вернуть результат
}

// Ввести массив
{
int [] array = new int [length];
for (int i = 0; i< array.Lenght; i++)
{
    array [i] = Prompt ($ "Введите {i + 1}-ый элемент);
}
    return array;
}

void PrintArray (int[] array)
{
    for (int i = 0; i< array.Lenght; i++)
    {
        Console.Writeline($"a[{i}] = {array[i]}");
        }
}

int CountPositiveNumbers(int[] array)
{
    int count = 0;
    for (int = 0; i< array.Lenght; i++)
    {
        if (array[i] > 0)
        {
            count++;
        }
    }
    return count;
    }

    int lenght = Prompt ("Введите количество элементов >");
    int[] array;
    array = InputArray(lenght);
    PrintArray(array);
    Console.WriteLine("Количество чисел больше 0 - 
    {CountPositiveNumbers(array)"});
    
    