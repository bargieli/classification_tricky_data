### Treść zadania:

Załóżmy, że chcemy kupić mieszkanie. Do dyspozycji mamy 100 000$, możemy też wziąć kredyt na kolejne 250 000 $, co da nam w sumie budżet w wysokości 350 000 $. Stwórzmy model który pomoże nam przewidzieć, czy mieszkanie o zadanych parametrach możemy kupić za własne pieniądze (cheap), z kredytem (average), czy jest poza naszym zasięgiem (expensive).

W oparciu o dostępne atrybuty zbuduj model, który pomoże oszacować, czy dana nieruchomość należy do klasy cheap, average czy expensive. Do dyspozycji mają Państwo dane treningowe (train_data.csv) z oryginalnymi cenami nieruchomości (SalePrice), oraz zbiór testowy (test_data.csv).

Końcowe wyniki obliczane będą w oparciu o średnią dokładność (accuracy) dla każdej klasy. Proszę zwrócić uwagę na fakt, że klasy są mocno niezbalansowane! W pliku evaluation.py znajduje się funkcja, przy użyciu której obliczana będzie skuteczność Państwa modelu.
