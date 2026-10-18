# Snake Game

The classic snake game, built with Python's `turtle` module. Eat the green food to grow; the game speeds up as your score rises, and the high score is saved to a file. One of the first programs I wrote while learning Python, between July and November 2023, kept here as it was.

## Run

Requires Python 3 with Tkinter (included in the standard installers). Run it from the project folder, because the high score file is read from the current folder.

```bash
cd snakegame
python3 main.py
```

Use the arrow keys to move. Hitting the edge or your own tail resets the score and starts over; close the window to quit.

## Notes

- The code is kept exactly as written back then; only line endings were normalized.
- `high_score_data.txt` holds the high score and is updated while you play.
- Above 100 points the game has no delay left, so it runs as fast as your computer allows.
- Originally published in July 2023 and updated in August 2023 (high score table, game border, saving the high score to a file).

## License

[MIT](LICENSE)

---

## Yılan Oyunu (Türkçe)

Python'un `turtle` modülüyle yazılmış klasik yılan oyunu. Yeşil yemleri yiyerek uzarsın; puan arttıkça oyun hızlanır, en yüksek puan bir dosyaya kaydedilir. Python öğrenirken, Temmuz ile Kasım 2023 arasında yazdığım ilk programlardan biri; hatıra olarak olduğu gibi saklanıyor.

### Çalıştırma

Tkinter içeren Python 3 gerekir (standart kurulumlarda hazır gelir). En yüksek puan dosyası bulunulan klasörden okunduğu için proje klasöründen çalıştır.

```bash
cd snakegame
python3 main.py
```

Yön tuşlarıyla hareket edilir. Kenara ya da kendi kuyruğuna çarpınca puan sıfırlanır ve oyun baştan başlar; çıkmak için pencereyi kapat.

### Notlar

- Kod o zaman yazıldığı gibi duruyor; yalnızca satır sonları düzenlendi.
- `high_score_data.txt` en yüksek puanı tutar ve oynarken güncellenir.
- 100 puandan sonra oyunda bekleme kalmaz, bilgisayarın izin verdiği en yüksek hızda akar.
- İlk olarak Temmuz 2023'te yayımlandı, Ağustos 2023'te güncellendi (en yüksek puan tablosu, oyun kenarı, en yüksek puanın dosyaya kaydedilmesi).

### Lisans

[MIT](LICENSE)
