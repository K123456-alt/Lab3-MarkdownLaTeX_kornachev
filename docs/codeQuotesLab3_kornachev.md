# Блоки кода и цитаты в Markdown

## Встроенный (inline) код

Команда `git status` показывает состояние репозитория.

Команда `git add .` добавляет все файлы в staging area.

Команда `git commit -m "message"` создаёт коммит с описанием.

---

## Блок кода без указания языка

```
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Введите первое число: ");
        double number1 = Convert.ToDouble(Console.ReadLine());
        
        Console.WriteLine("Введите второе число: ");
        double number2 = Convert.ToDouble(Console.ReadLine());
        
        double sum = number1 + number2;
        Console.WriteLine($"Сумма: {sum}");
    }
}
```
>Markdown — это лёгкий язык разметки, который используется для оформления README-файлов, документации и отчётов.
>>Git — это распределённая система контроля версий.
