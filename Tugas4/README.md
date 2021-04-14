# Masalah mesin cuci: Fuzzy Logic dengan modul skfuzzy

Sistem control fuzzy memodelkan waktu yang dibutuhkan mesin cuci untuk mencuci pakaian sesuai dengan jenis pakaian, kekotoran, berat pakaian dan level kekotoran. Sehingga kita perlu mempertimbangkan jenis pakaian, kotoran, berat pakaian dan level kekotoran, nilai antara 0 sampai 10. Hal ini digunakan untuk mengetahui berapa lama waktu yang dibutuhkan mesin cuci untuk mencuci pakaian antara 0 sampai 20 menit.

# Antecedents (inputs):
•	Jenis pakaian (tClothes) ◦ Universe: Jenis pakaian dengan skala 0-10 ◦ Set fuzzy: sutra, katun
•	Jenis kotoran (tDirty) ◦ Universe: Jenis kotoran pada skala 0-10 set Set fuzzy: berminyak, tidak berminyak, campur
•	Berat pakaian (mClothes) ◦ Universe: Berat pakaian (dalam lb (0-10)) ◦ Set fuzzy: Berat pakaian 1-3 lb, 4-6 lb dan 7-10 lb
•	Level kekotoran kain (dClothes) ◦ Universe: Level kekotoran kain dalam skala (1-10) ◦ Set Fuzzy: rendah, sedang, tinggi

# Konsekuensi (Output)
•	Waktu mencuci (wTime) • Universe: Berapa lama waktu yang dibutuhkan mesin cuci untuk mencuci pakaian antara 0 – 20 menit? • Set fuzzy: Very short, short, medium, large, very larg.

# Simulasi :
washing_time.input['tClothes'] = 5
washing_time.input['tDirty'] = 4
washing_time.input['mClothes'] = 9
washing_time.input['dCloths'] = 3

==> Maka hasilnya adalah 13,4 menit waktu yang dibutuhkan dalam proses mencuci pada simulasi tersebut.
