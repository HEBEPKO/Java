1.Создать упорядоченный массив от 1_000_000 до 1_999_999.{1000000,1000001,…….,1999998,1999999}
    Найти индекс случайного элемента в массиве при помощи бинарного поиска (своя реализация!!!).
    Чтобы получить случайное число, воспользуйтесь кодом:
    Random random = new Random();
    int randomInt = random.nextInt(1_000_000,2_000_000);
    или
    int randomInt = (int) (Math.random()*1_000_000) + 1_000_000;

2.Создать массив int[100_000]. 
    Заполнить его случайными числами. 
    Выполнить сортировку пузырьком. 
    Через консоль получить два числа, разделённых пробелом - это будут начальный и конечный индексы. 
    И вывести на экран часть массива, ограниченного полученными индексами.
3.Создать класс, реализующий функциональность, аналогичную классу ArrayList.   
    Класс может хранить объекты любого типа. 
    Реализация должна содержать методы:
        добавление одного элемента
        добавление массива элементов
        добавление по индексу
        удаление по индексу
        удаление всех элементов