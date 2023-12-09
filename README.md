#include <stdio.h>

int main() {
    int toplam = 0;

    for (int sayi = 1; sayi <= 100; sayi += 2) {  // 1 ile 100 arasındaki tek sayıları alır
        if (sayi % 3 == 0) {  // 3'e tam bölünen sayıları kontrol eder
            toplam += sayi;
        }
    }

    printf("1 ile 100 arasındaki tek sayılardan 3'e tam bölünen sayıların toplamı: %d\n", toplam);

    return 0;
}
