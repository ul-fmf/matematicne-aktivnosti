# Matematične aktivnosti

Matematične aktivnosti za otroke in vse, ki jih veseli matematika.

Aktivnosti najdete na spletni strani [https://ul-fmf.github.io/matematicne-aktivnosti/](https://ul-fmf.github.io/matematicne-aktivnosti/).
Ta repozitorij je namenjena vsem, ki želijo prispevati vsebino.

## Tehnični nasveti

### Kako naredimo ikono za PDF

Ikono za PDF lahko ustvarimo s programom [ImageMagick](https://imagemagick.org/). Na primer, takole iz datoteke `aktivnost.pdf` naredimo `aktivnost.png` velikosti do 256×256:

    convert 'aktivnost.pdf[0-0]' -thumbnail 256x256 aktivnost.png

Takole lahko v ukaznem oknu na Linuxu ali MacOS naredimo vse ikone hkrati:

    for d in *pdf; do convert $d'[0--0]' -thumbnail 256x256 "thumbnail/`basename $d .pdf`".png; done

### Kako naredimo spletne strani na lokalnem računalniku

Spletne strani lahko naredimo s programom [Jekyll](https://jekyllrb.com).
Več o tem piše na [Testing your GitHub Pages site locally with Jekyll](https://help.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll).
Ko imate delujoč Jekyll, naredite lokalni strežnik s stranmi z ukazom

    bundle exec jekyll serve

in obiščete spletne strani na naslovu [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

## Ekipa

Študentke in študenti:

* [Hana Čadež](https://github.com/hana47)
* [David Čadež](https://github.com/CadezDavid)
* [Špela Plevel](https://github.com/spelaplevel)
* [Manca Prošek](https://github.com/mancaprosek)
* [Urh Primožič](https://github.com/urhprimozic)
* [Katarina Brdnik](https://github.com/katarinabrdnik)
* [Martin Radman](https://github.com/MartinRadman)
* [Jon Mikoš](https://github.com/MikosJon)
* [Petrisa Čanji](https://github.com/petrisa-canji)

Mentorja:

* Tina Klopčič Dobrić ([Osnovna šola Vič](http://www.osvic.si))
* [Andrej Bauer](https://andrej.com/) ([Fakulteta za matematiko in fiziko](https://www.fmf.uni-lj.si/si/))
