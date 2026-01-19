# Shapesy

Shapesy je Python desktop aplikacija za Windows koja omogućuje izračunavanje osnovnih podataka vezanih za geometrijske oblike, 2D i 3D, poput **površine, opsega i volumena**.
Prije izračuna aplikacija također prikazuje **skicu oblika** na canvasu, što olakšava vizualizaciju.

## Tehnologija

* **GUI**: Tkinter
* **Python**: 3.x
* **Ikona aplikacije**: `iconShapesy.png` (konvertirana i ugrađena putem Pillow biblioteke)
* **Distribucija**: PyInstaller `.exe` za Windows

## Datoteke

* Glavna skripta: `Shapesy.py`
* Svi resursi potrebni za funkcioniranje (ikone, slike) ugrađeni su unutar `.exe` datoteke pomoću PyInstaller-a
* `.exe` datoteka nalazi se u **GitHub Releases** (preporučeni način distribucije)

## Instalacija (za developere)

Ako želiš raditi s izvornim kodom:

1. Kloniraj repozitorij:

```bash
git clone https://github.com/ZekoSkok/Shapesy.git
cd Shapesy
```

2. Kreiraj virtualno okruženje i aktiviraj ga:

```bash
py -m venv venv
venv\Scripts\activate
```

3. Instaliraj potrebne pakete (ako se dodaju u budućnosti):

```bash
pip install -r requirements.txt
```

4. Pokreni aplikaciju:

```bash
py Shapesy.py
```

## Pokretanje distribuirane verzije

Ako želiš samo koristiti aplikaciju (bez Python instalacije):

1. Idi na **[Releases](https://github.com/ZekoSkok/Shapesy/releases)**
2. Preuzmi `Shapesy.exe`
3. Pokreni aplikaciju dvostrukim klikom

> ⚠️ Napomena: Aplikacija je trenutno podržana samo na **Windows OS**.
> Antivirus može prikazati upozorenje za `.exe` datoteke izrađene PyInstaller-om – ovo je normalno.

## Verzija

**v1.0.0** – inicijalna verzija s podrškom za osnovne 2D i 3D oblike i canvas prikaz.

## Licence i krediti

* Python: [https://www.python.org/](https://www.python.org/)
* Tkinter: standardni Python GUI toolkit
* Pillow: za obradu ikone
* Autor: Zvonimir Novak (ZekoSkok)

## Budući razvoj (opcionalno)

* Dodavanje više 3D oblika
* Napredniji canvas prikaz s interaktivnim rotacijama
* Verzija za macOS i Linux
