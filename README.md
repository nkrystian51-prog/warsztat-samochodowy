#include <stdio.h>

int main(void) {
    int liczba1, liczba2, liczba3;

    printf("Podaj trzy liczby calkowite, oddzielajac je spacja: ");
    scanf("%d %d %d", &liczba1, &liczba2, &liczba3);

    int najwieksza;

    if (liczba1 >= liczba2 && liczba1 >= liczba3) {
        najwieksza = liczba1;
    } else if (liczba2 >= liczba1 && liczba2 >= liczba3) {
        najwieksza = liczba2;
    } else {
        najwieksza = liczba3;
    }

    printf("Najwieksza liczba to: %d\n", najwieksza);

    return 0;
}
