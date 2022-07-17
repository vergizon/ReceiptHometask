# Отчёт о тестировании <Название приложения>
## Краткое описание
17.07.2022 - <Дата окончания> было проведено функциональное тестирование программы расчёта распределения ингредиентов на порцию.

На тестирование затрачено: 2 часа

В результате тестирования выявлен следующий дефект:

1. [Incorrect result in the third string](https://github.com/vergizon/ReceiptHometask/issues/1) .


# Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:

Чек лист: https://github.com/netology-code/javaqa-homeworks-video/blob/main/JAVA_INTRO.md



В качестве тестовых данных использовались данные:

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

Тестирование производилось в следующем окружении:

версия и разрядность ОС - Windows 11 Pro; 
версия Java - 11.0.11;
другое ПО, при необходимости - IntelliJ IDEA Community Edition version 2022.1.3