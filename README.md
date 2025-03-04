# Amplificator de Tensiune (Joasă Frecvență)

## Descriere
Acest proiect constă în proiectarea și realizarea unui amplificator de tensiune de joasă frecvență, conform specificațiilor definite. Scopul amplificatorului este de a crește amplitudinea semnalelor electrice de joasă frecvență (20 Hz - 20 kHz) menținând integritatea semnalului original.

## Specificații Tehnice
- **Semnal de intrare:** 1.5V
- **Sarcina la ieșire:** 250 Ω
- **Rezistența de intrare (Ri):** >150 kΩ
- **Rezistența de ieșire (Ro):** < 2.5Ω
- **Amplificare in tensiune (Av):** 10
- **Temperaturi de funcționare:** -20°C - 120°C
- **Indicator LED pentru prezența tensiunii de alimentare**

## Principiul de Funcționare
Amplificatorul funcționează conform principiilor circuitelor electrice, utilizând tranzistoare pentru amplificarea semnalului. Formula fundamentală este:

```
Av = Uout / Uin
```

unde:
- Av este câștigul de tensiune
- Uout este tensiunea de ieșire
- Uin este tensiunea de intrare

Pentru stabilitate, este utilizată reacția negativă, care menține amplificarea constantă.

## Componente Principale
1. **Etajul diferențial de intrare** - folosește tranzistoare Q1 și Q2 (QBC846B)
2. **Sursa de curent constant** - tranzistor Q5 reglează curentul circuitului
3. **Etajul de amplificare de tensiune** - include tranzistoarele Q6, Q7 și rezistențe de stabilizare
4. **Etajul de ieșire** - configurat push-pull cu tranzistoare Q12 și Q13 (QBC807-25)
5. **Indicator LED** - pentru semnalizarea prezenței tensiunii de alimentare

## Schema Bloc
(Schema bloc a amplificatorului poate fi adăugată sub formă de imagine)

## Instalare și Utilizare
1. Descărcați fișierele proiectului din acest repository.
2. Construiți circuitul conform schemei electrice.
3. Alimentați circuitul cu tensiunea corespunzătoare.
4. Testați funcționarea și verificați amplificarea tensiunii de ieșire.

## Autori
- **Student:** Nistor Flaviu-Cristian (431D)
- **Coordonatori:** Draghici Florin, Pantazica Mihaela

## Licență
Acest proiect este realizat în cadrul Universității Naționale de Știință și Tehnologie Politehnica București, Facultatea de Electronică, Telecomunicații și Tehnologia Informației, 2024.

