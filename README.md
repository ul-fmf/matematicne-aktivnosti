## Matematične aktivnosti

Matematične aktivnosti za otroke in vse, ki jih veseli matematika.

Aktivnosti najdete na spletni strani [https://ul-fmf.github.io/matematicne-aktivnosti/](https://ul-fmf.github.io/matematicne-aktivnosti/).
Ta repozitorij je namenjena vsem, ki želijo prispevati vsebino.

### Tehnični nasveti

#### Kako naredimo 

Ikono za PDF lahko ustvarimo s programom [ImageMagick](https://imagemagick.org/). Na primer, takole iz datoteke `aktivnost.pdf` naredimo `aktivnost.png` velikosti do 480 × 480:

    convert 'aktivnost.pdf[0-0]' -resize 480x480 aktivnost.png

Takole lahko v ukaznem oknu na Linuxu ali MacOS naredimo vse ikone hkrati:

    cd gradivo
    for d in *pdf; do convert $d'[0--0]' -resize 480x480 "thumbnail/`basename $d .pdf`".png; done

### Ekipa

Študentke in študenti:

* Hana Čadež
* David Čadež
* Špela Plevel
* Manca Prošek
* [Urh Primožič](https://github.com/urhprimozic)
* Katarina Brdnik
* Martin Radman
* Jon Mikoš
* [Petrisa Čanji](https://github.com/petrisa-canji)

Mentorja:

* Tina Klopčič Dobrić ([Osnovna šola Vič](http://www.osvic.si))
* [Andrej Bauer](https://andrej.com/) ([Fakulteta za matematiko in fiziko](https://www.fmf.uni-lj.si/si/))
