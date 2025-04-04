#include <stdio.h>

int main() {
    //Создание массива из 3 строк
    char colors[3][10] = {"red", "blue", "green"};

    //Вывод массива на экран
    for (int i = 0; i < 3; i++) 
    {
        printf("%s\n", colors[i]);
    }

    return 0;
}
