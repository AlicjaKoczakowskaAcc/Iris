# Iris
1. Charakterystyka oprogramowania:
Nazwa skrócona: IrisClassifier
Nazwa pełna: Iris Flower Classification Web App
Krótki opis ze wskazaniem celów: Aplikacja internetowa wykorzystująca model uczenia maszynowego do klasyfikacji kwiatów irysów na podstawie pomiarów działek kielicha i płatków. Celem jest dostarczenie użytkownikom interaktywnego narzędzia do przewidywania gatunku irysa oraz wizualizacji cech wejściowych i prognoz modelu.
2. Prawa autorskie:
Autor: Alicja Koczakowska
Licencja MIT (Massachusetts Institute of Technology):
Pozwala na dowolne korzystanie, modyfikowanie, publikowanie, sprzedaż i dystrybucję oprogramowania, pod warunkiem zachowania oryginalnej licencji i informacji o prawach autorskich
3.Specyfikacja wymagań:
Identyfikator	Nazwa	Opis	Kategoria
1	SepalLengthCm	Długość działki kielicha w centymetrach	Funkcjonalne
2	SepalWidthCm	Szerokość działki kielicha w centymetrach	Funkcjonalne
3	PetalLengthCm	Długość płatka w centymetrach	Funkcjonalne
4	PetalWidthCm	Przycisk do przewidywania gatunku irysa na podstawie wprowadzonych danych	Funkcjonalne
5	Predict		Przycisk do przewidywania gatunku irysa na podstawie wprowadzonych danych	Funkcjonalne
6	Input Validation	Walidacja wejścia, sprawdzenie poprawności wprowadzonych danych	Niefunkcjonalne
4. Architektura systemu/oprogramowania:

Architektura rozwoju – stos technologiczny:

Python (backend)
Flask (web framework)
Scikit-learn (machine learning)
Pandas (data manipulation)
Matplotlib (data visualization)
Architektura uruchomieniowa – stos technologiczny:

Web Browser (front-end)
Flask (back-end)
Python (interpreter)
Machine learning model (DecisionTreeClassifier)

Testy:

a. Scenariusz testów:
Test poprawności klasyfikacji:

Kroki:
Wprowadź poprawne wartości dla SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm.
Kliknij przycisk "Predict".
Oczekiwany wynik:
Aplikacja powinna poprawnie sklasyfikować gatunek irysa.
Test walidacji wejścia:

Kroki:
Wprowadź nieprawidłowe wartości (np. tekst zamiast liczby) dla jednego z atrybutów.
Kliknij przycisk "Predict".
Oczekiwany wynik:
Aplikacja powinna wyświetlić komunikat o błędzie i nie dokonać predykcji.
