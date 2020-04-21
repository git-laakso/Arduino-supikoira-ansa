# Arduino-supikoira-ansa
Arduino Mega 2560 &amp; Arduino Uno R3 suunnattu supikoira-ansa valvonnalla ja hälytyksellä. Projekti on tehty Flowcode 8:lla, ja muunnettu C kielelle.

# Tilat
Ohjelma lukee kolmea tilaa:
A) Valvonta / LED vilkkuu tasaisesti ja äänen ulostuloa ei ole aktivoitu <br>
B) Hälytys / LED palaa tasaisesti ja äänen ulostulo aktivoidaan <br>
C) Idle / Sulkee LED:in, sekä äänen ulostulon <br>

# Toiminta
Luukkuun kytketään NC kytkin(Kytkentä A), jonka sulkeutuessa ohjelma siirtyy valvontatilasta hälytykseen(Tila B). <br>
Hälytyksestä päästään Idle tilaan(Tila B), painamalla nappia (Kytkentä B). <br>
Idle tilasta päästään takaisin valvontatilaan, painamalla nappia (Kytkentä C) tilaan (Tila A).

# Kytkentä
![Simple-Alarm-Wiring-Mega_bb](https://user-images.githubusercontent.com/52996898/79853653-fe3bf580-83d0-11ea-8ad8-a59bfde9761d.png)

# FlowCode 8 näkymä
![flow](https://user-images.githubusercontent.com/52996898/79854002-730f2f80-83d1-11ea-8fa9-406e179db03f.PNG)

# Ulkoinen linkki projektiin
<a Href="https://www.dropbox.com/home/Home/Arduino/Simple-Alarm-S2-W-LED">Ulkoinen linkki projektiin</a>
