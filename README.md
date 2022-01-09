# PRiR_LAB10
Zadanie z laboratoriów 10 z przedmiotu PRiR. Program w Google Colab całkujący 3 metodam(metoda prostokątów, metoda trapezów, metoda simpsona). Całkowanie zostało zaimplementowane zarówno na CPU jak i na GPU.
Następnie wyniki zostały zebrane i porównane na podstawie wykresów gdzie zawarta jest liczba podziałów całki i czas wykonania obliczeń w sekundach a także zostały opisane wnioski.

Metoda prostokątów (czerwony - CPU, niebieski - GPU )

![image](https://user-images.githubusercontent.com/80594314/148692221-737ff2d6-0e68-40eb-a77f-9c3c37f19b35.png)


Metoda trapezów (czerwony - CPU, niebieski - GPU )

![image](https://user-images.githubusercontent.com/80594314/148692232-38020c64-3c31-4e27-91ad-8c15190778ed.png)


Metoda simpsona (czerwony - CPU, niebieski - GPU )

![image](https://user-images.githubusercontent.com/80594314/148692243-d6226b63-f33f-42c8-a953-24bd93d867e5.png)


WNIOSKI
Jak widać całkowanie na GPU wykonuje obliczenia szybciej niż CPU. Zdażył sie jeden przypadek kiedy to CPU było szybsze mogło to być spowodowane obciążeniem kart graficznych w środowisku.

Lista danych które zostały zwrócone przez program(na ich podstawie zostały utworzone wykresy)
CPU
n = 10000
metoda prostokatow czas = 0.00014200
metoda trapezow czas = 0.00014200
metoda simpsona czas = 0.00023600
n = 100000
metoda prostokatow czas = 0.00125100
metoda trapezow czas = 0.00125100
metoda simpsona czas = 0.00224400
n = 1000000
metoda prostokatow czas = 0.01276100
metoda trapezow czas = 0.01276100
metoda simpsona czas = 0.02209800
n = 10000000
metoda prostokatow czas = 0.12444600
metoda trapezow czas = 0.12444600
metoda simpsona czas = 0.21983000
n = 100000000
metoda prostokatow czas = 1.24974900
metoda trapezow czas = 1.24974900
metoda simpsona czas = 2.18544000


GPU
n = 10000
metoda prostokatow czas = 0.132652
metoda trapezow czas = 0.000346796
metoda simpsona czas = 0.000532063
n = 100000
metoda prostokatow czas = 0.00113591
metoda trapezow czas = 0.000942178
metoda simpsona czas = 0.00242353
n = 1000000
metoda prostokatow czas = 0.00851996
metoda trapezow czas = 0.00709647
metoda simpsona czas = 0.0215281
n = 10000000
metoda prostokatow czas = 0.0814226
metoda trapezow czas = 0.0700239
metoda simpsona czas = 0.076948
n = 100000000
metoda prostokatow czas = 1.09126
metoda trapezow czas = 0.745227
metoda simpsona czas = 0.778436
