---
title: 'Flexbox'
description: 'Ok'
pubDate: '2023 12 30'
heroImage: '/flexbox.png'
---

# <span id='flexbox'>Flexbox</span>

## Wprowadzenie

Flexbox, znany także jako Flexible Box Layout, jest potężnym narzędziem do zarządzania układem stron internetowych. Umożliwia efektywne i elastyczne pozycjonowanie elementów, zarówno w pionie, jak i poziomie, co znacznie ułatwia tworzenie responsywnych układów.

## Podstawy Flexbox

Aby korzystać z Flexbox, należy zastosować właściwość `display: flex;` do kontenera, który stanie się 'flex container'. Elementy wewnątrz tego kontenera stają się 'flex items'.

```css
.container {
  display: flex;
}
```

### Właściwości Flex Containera

- **flex-direction**: Określa kierunek głównej osi (row, column).
- **justify-content**: Wyrównuje elementy wzdłuż głównej osi (center, space-between).
- **align-items**: Wyrównuje elementy wzdłuż osi poprzecznej (center, stretch).
- **flex-wrap**: Pozwala elementom przechodzić na nowy wiersz lub kolumnę (wrap, nowrap).

### Właściwości Flex Itemów

- **flex-grow**: Określa zdolność elementu do rozszerzania się, by zająć dostępną przestrzeń.
- **flex-shrink**: Określa, jak element może się kurczyć, gdy nie ma wystarczająco dużo miejsca.
- **flex-basis**: Określa domyślny rozmiar elementu przed rozdysponowaniem wolnej przestrzeni.
- **align-self**: Umożliwia indywidualne wyrównanie elementu wzdłuż osi poprzecznej.

### Przykłady użycia Flexbox

1. **Wyrównanie elementów poziomo w centrum:**

   ```css
   .container {
     display: flex;
     justify-content: center;
     align-items: center;
   }
   ```

2. **Elastyczny układ z zawijaniem elementów:**

   ```css
   .container {
     display: flex;
     flex-wrap: wrap;
   }
   ```

### Dobre praktyki

- Używaj Flexbox do tworzenia responsywnych układów, które dostosowują się do różnych rozmiarów ekranów.
- Wykorzystaj elastyczność Flexbox do uproszczenia CSS i uniknięcia złożonych hacków pozycjonujących.
- Pamiętaj, że Flexbox jest szczególnie użyteczny w układach jednowymiarowych (w jednej linii, w pionie lub poziomie).

## Podsumowanie

Flexbox to potężne narzędzie, które znacznie ułatwia tworzenie skomplikowanych układów na stronach internetowych, zarówno w projektach statycznych, jak i responsywnych.
