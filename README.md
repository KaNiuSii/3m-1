
# Podstawy Teoretyczne Pomiarów
1. **Definicja Pomiaru**: Zestaw operacji wyznaczających wartość danej wielkości.
2. **Błąd Pomiaru**: Różnica między wynikiem pomiaru a nieznaną, prawdziwą wartością wielkości. Prawdziwa wartość jest nieznana, więc skupiamy się na niepewności pomiaru.

## Niepewność Pomiaru
1. **Definicja**: Parametr związany z wynikiem pomiaru, wskazujący na rozrzut wartości, które można przypisać mierzonej wielkości.
2. **Ważność**: Wynik pomiaru jest kompletny, gdy zawiera zarówno wartość wielkości mierzonej, jak i związaną z nią niepewność pomiaru.
3. **Estymata Prawdziwej Wartości**: Podanie wyniku pomiaru i przedziału, w którym prawdziwa wartość występuje z określonym poziomem ufności.

## Czynniki Wpływające na Niepewność
1. **Niedoskonałości sprzętu i metod**: Obejmują skończoną rozdzielczość odczytu, błędy definicji, wpływ otoczenia, i niedoskonałości procedur pomiarowych.
2. **Wpływ Środowiska**: Niepełna wiedza o wpływie środowiska na obiekt pomiaru i aparaturę.

## Procedura Pomiarowa
1. **Wielokrotne Pomiary**: Niezbędne do dokładnego oszacowania wielkości mierzonej.
2. **Statystyczna Obróbka**: Prowadzi do estymaty punktowej (średnia z n pomiarów) i przypisanej do niej niepewności (granice przedziału ufności).

## Błędy i Ich Korekta
1. **Błędy Nadmierne**: Usuwane zwykle za pomocą kryterium 3s.
<br>
   ![image](https://github.com/KaNiuSii/3m-1/assets/123270897/5251c5e1-b3dd-481f-8e2b-c91d77267654)
<br>
2. **Błędy Systematyczne**: Usuwane przez stosowne uwzględnienie błędów wprowadzanych przez przyrządy i metody.

## Zapis Wyniku Pomiaru
1. **Estymata i Przedział Niepewności**: Obejmuje wartość pomiaru, poziom ufności i przedział, w którym wartość prawdziwa prawdopodobnie się znajduje.
2. **Zasady Zaokrąglania**: Specyficzne reguły dla wyniku pomiaru i niepewności.
<br>
![image](https://github.com/KaNiuSii/3m-1/assets/123270897/b977f8fa-dd58-4d00-9ff2-0ccc4db0a5df)
<br>

## Niepewność rozszerzona
<br>
![image](https://github.com/KaNiuSii/3m-1/assets/123270897/8a879f3b-e145-429b-bb63-6f66d8010ca0)
<br>

## Podsumowanie
- Niepewność pomiaru jest kluczowym elementem każdego pomiaru, uwzględniającym potencjalny rozrzut wyników.
- Właściwe oszacowanie niepewności wymaga zarówno precyzyjnych pomiarów, jak i dokładnej analizy statystycznej.
- Błędy pomiarowe i systematyczne muszą być rozpoznane i odpowiednio skorygowane w celu uzyskania wiarygodnych wyników.


# Szacowanie Niepewności Typu A i B

## 1. Ogólne Zasady
- Niepewności typu A i B są nieusuwalnymi elementami wyniku pomiaru, które można jedynie oszacować przy danym poziomie ufności p.

## 2. Niepewność Typu A
- **Definicja**: Odchylenie standardowe wartości średniej, znane jako niepewność standardowa typu A.
- **Oszacowanie**: Dla serii n pomiarów jednej wielkości (pomiar bezpośredni) lub serii pomiarów elementarnych dla N wielkości (pomiar pośredni).
- **Wzory**: Niepewność typu A jest określana przez odchylenie standardowe wartości średniej i odchylenie standardowe pojedynczego pomiaru.

## 3. Niepewność Typu B
- **Definicja**: Niepewność oparta na informacjach ze specyfikacji przyrządu, świadectwa wzorcowania, czy innych certyfikatów.
- **Oszacowanie**: Szacowana na podstawie granicznego błędu pomiaru \(\Delta g\) i zakładanego rozkładu gęstości prawdopodobieństwa.
- **Rozkłady Prawdopodobieństwa**: Różne rozkłady, takie jak równomierny, trójkątny, normalny, w kształcie litery U, mają różne wpływy na wartość niepewności typu B.
  <br> ![image](https://github.com/KaNiuSii/3m-1/assets/123270897/2e6c43bc-dea4-4d07-938b-4f398cc54301) <br>


## 4. Obliczanie Niepewności
- **Metoda Typu A**: Wykorzystuje estymatę odchylenia standardowego z serii pomiarów. <br> ![image](https://github.com/KaNiuSii/3m-1/assets/123270897/f88afbc8-7d43-4be5-b53b-c1346a9e3680) <br>

- **Metoda Typu B**: Używa informacji o błędzie granicznym i rozkładzie prawdopodobieństwa do obliczenia niepewności.

## 5. Zastosowanie w Pomiarach
- **Pomiar Bezpośredni i Pośredni**: Różni się w zależności od liczby mierzonych wielkości i sposobu ich pomiaru.
- **Korekta Błędów**: W dokładnych obliczeniach stosuje się korektę błędów na podstawie linii trendu.

## 6. Tabela Niepewności Typu B
- Zawiera wartości niepewności typu B w zależności od typu rozkładu gęstości prawdopodobieństwa (równomierny, trójkątny, normalny, w kształcie litery U).

## 7. Niepewność Łączna
- **Definicja**: Suma geometryczna wszystkich składowych niepewności obliczonych metodami A i B.
- **Wzory**: Uwzględnia wpływ wielu czynników zakłócających, takich jak temperatura, ciśnienie atmosferyczne, wilgotność, pola elektromagnetyczne.


# Obliczanie Niepewności Standardowej Pomiaru Wielkości Wyjściowej

## Prawo Propagacji Niepewności
- Stosując prawo propagacji niepewności, otrzymujemy udziały niepewności wielkości wejściowych w niepewności wielkości wyjściowej.
- Niepewność standardowa wielkości wyjściowej (u(y)) jest sumą geometryczną udziałów niepewności wielkości wejściowych.

## Obliczanie Niepewności
- Wzór: <br> ![image](https://github.com/KaNiuSii/3m-1/assets/123270897/58eb44ab-b02e-4946-bacb-83f962cf5b9e)
 <br>
- Dla wielkości niezależnych (nieskorelowanych) stosuje się powyższy wzór. W przypadku wielkości skorelowanych używa się wzorów z kowariancją lub współczynnikiem korelacji.

## Metody Uproszczone
- W praktyce przemysłowej stosuje się metody uproszczone, wykorzystujące współczynnik rozszerzenia \( k_p \).
  <br> ![image](https://github.com/KaNiuSii/3m-1/assets/123270897/35c18719-fded-4ee4-9d13-4d970f87f1c0) <br>
- Niepewność rozszerzona \( U(y) \) jest obliczana przez pomnożenie niepewności standardowej \( u(y) \) przez współczynnik \( k_p \).
<br> ![image](https://github.com/KaNiuSii/3m-1/assets/123270897/5676427e-4976-4ae2-af51-b93ccfacbc56) <br>

# Odchylenie Standardowe w Pomiarach Złożonych
- Dotyczy pomiarów pośrednich, gdzie wynik jest rezultatem operacji matematycznych na wynikach pomiarów bezpośrednich.
- Używa się rachunku prawdopodobieństwa do obliczenia odchylenia standardowego funkcji złożonej.

## Uwaga Praktyczna
- Gdy funkcja gęstości prawdopodobieństwa jest zbliżona do rozkładu Gaussa, do obliczenia niepewności rozszerzonej na poziomie ufności p = 0,95 można stosować współczynnik \( k_p = 2 \).

## Niepewność Rozszerzona
- Obliczana ze wzoru: \( U_p = k \cdot u_c \)
- \( k \) - współczynnik rozszerzenia, zależny od rozkładu łącznego niepewności obliczanej metodą typu A i B.
- ![image](https://github.com/KaNiuSii/3m-1/assets/123270897/da0ac7c1-ed3f-4c55-9cc9-19deffbb95cf)
 - niepewność standardowa łączna.
