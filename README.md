# belajar_dart
6 april 2022

link youtube
https://www.youtube.com/watch?v=-mzXdI27tyk&t=1366s

## print
```bash
void main() {
  print('Muhamad Randi Septiansah');
}
```

## Variable
untuk mengulang output tanpa penambahan ukuran data

```bash
void main() {
  String namaSaya;
  namaSaya = ('Muhamad Randi Septiansah');

  print(namaSaya);
  print(namaSaya);
  print(namaSaya);
  print(namaSaya);
}
```
## deklarasi langsung
versi lebih simpelnya

```bash
void main() {
  String namaSaya = ('Muhamad randi Septiansah');

  print(namaSaya);
  print(namaSaya);
}
```
## var
menentukan tipe data secara otomatis

```bash
void main() {
  String namaSaya = ('Muhamad randi Septiansah');

  print(namaSaya);
  print(namaSaya);
}
```
## final
tipe data final tidak bisa menduplikasi value
tipe data var bisa menduplikasi value

```bash
void main() {
  var namaSaya = ('Muhamad randi Septiansah');

  print(namaSaya);
  print(namaSaya);

  var namaAwal = ('randi');
  final namaAkhir = ('septiansah');

  namaAwal = ('usop');
  namaAkhir = ('ujang');

  print(namaAwal);
  print(namaAkhir);
}
```
