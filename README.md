#include <stdio.h>

int main() {
    //Создаем массив из 5 строк
    char colors[5][10] = {"green", "blue", "pink", "black", "gray"};

    //Выводим массив на экран
    for (int i = 0; i < 5; i++) {
        printf("%s\n", colors[i]);
    }

    return 0;
}
