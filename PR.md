# Celcius-to-all Conversion Algorithm

## Descriptive

1. Mulai
2. Masukkan Derajat dalam skala celsius
3. Tambah Derajat dengan 273.15, simpan hasil pertambahan tersebut sebagai skala Kelvin
4. Kalikan Derajat celsius dengan pecahan 9/5, lalu tambahkan hasil perkalian tersebut dengan 32, simpan tambahan tersebut sebagai skala Fahrenheit
5. Kalikan derajat celsius dengan pecahan 4/5, simpan hasil perkalian tersebut sebagai skala Reamur
6. Tampilkan nilai-nilai yang sudah disimpan dengan format yang ditentukan
7. Selesai

## Flowchart

```mermaid
flowchart TD
    Start@{ shape: start }
    Input@{ shape: lean-r, label: "Derajat" }
    Kelvin@{ shape: rect, label: "Kelvin = 273.15 + Derajat" }
    Fahrenheit@{ shape: rect, label: "Fahrenheit = Derajat × (9/5) + 32" }
    Reamur@{ shape: rect, label: "Reamur = Derajat × (4/5)"}
    Output@{ shape: lean-r, label: "#quot;Kelvin: #quot;, Kelvin, #quot;Fahrenheit: #quot;, Fahrenheit, #quot;Reamur: #quot;, Reamur" }
    End@{ shape: stop }

    Start --> Input --> Kelvin --> Fahrenheit --> Reamur --> Output --> End
```

## Pseudo-code
```pseudo
DECLARE Derajat : REAL
DECLARE Kelvin : REAL
DECLARE Fahrenheit : REAL
DECLARE Reamur : REAL

INPUT Derajat

Kelvin <- Derajat + 273.5
Fahrenheit <- Derajat * (9/5) + 32
Reamur <- Derajat * (4/5)

OUTPUT "Kelvin: ", Kelvin, "Fahrenheit: ", Fahrenheit, "Reamur: ", Reamur
```