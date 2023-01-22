# Домашнее задание к занятию "Введение в Java"

## Задание. Рецепт  

Ваша задача  проанализировать программу рассчёта распределения ингредиентов на порцию. Программе на вход даётся рецепт со всеми граммовками каждого ингредиента, а также количество человек, которые будут в одинаковых порциях его есть. На выходе программа указывает, какое точное количество (без округлений) каждого ингредиента пришлось на одну порцию еды.  


```java
public class Main {
    public static void main(String[] args) {

        int eaters = 5; // сколько людей будут есть

        int water = 3000; // миллилитров воды
        int potatoes = 5; // картофелин
        int chicken = 6; // куриных бёдер
        int spices = 10; // ложек специй

        System.out.println("Сварили суп. На одного человека вышло:");
        System.out.println((water / eaters) + " миллилитров воды");
        System.out.println((potatoes / eaters) + " картофелин(а)");
        System.out.println((chicken / eaters) + " куриных(ое) бёдер(ро)");
        System.out.println((spices / eaters) + " ложек(ка) специй");

    }
}
```

1. Поместить код выше в класс `Main`.
1. Проанализировать код и вывод программы. Найти в них дефект(ы). Менять код программы не нужно.
1. Оформите баг-репорт с помощью Github Issues, описывающий найденный дефект.
1. Прикрепите ссылку на ваш публичный гитхаб-репозиторий.

### Результат выполнения задачи:
[ссылка на текущий репозиторий](https://github.com/Ekaterina-Isabel/recipe)  
[ссылка на баг-репорт](https://github.com/Ekaterina-Isabel/recipe/issues/1)
