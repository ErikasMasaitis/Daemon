**Užduoties aprašymas:**

Sukurti programą, kuri pasileidimo metu taptų Daemon tipo procesu.

Programos paskirtis bus stebėti nurodytą katalogą ir jame atsiradus naujų failų, tuos failus perkelti į atitinkamus katalogus.

Programa turi gebėti atskirti skirtingų tipų failus. Reikia, kad programa atskirtų šiuos tipus:

Audio failai (pvz. mp3, wav, flac)
Video failai (pvz. mkv, avi, mp4)
Foto failai (pvz. jpeg, png, svg)
Teksto arba dokumentų failai (pvz. txt, docx, pdf)
Failų tipus turi būti galima keisti. Turi būti galimybė nurodyti, kuriuos tipų failus sektis.

Skirtingų failų tipus turi perkelti į skirtingus katalogus. Pagal nutylėjimą programa turi perkelti į to vartotojo, kuris paleido programą, katalogus. Pvz. audio į Music katalogą esantį namų kataloge, dokumentus į Documents, video į Video ir foto failus į Pictures.

Jeigu failai neegzistuoja, programa turi juos sukurti.

Programai turi būti galima nurodyti kurį katalogą sekti. 

Visa informacija apie tai ką sekti ir kokius tipus sekti, turi būti konfigūracijos faile.

Visi atlikti veiksmai turi būti rašomi į atskirą failą skirtą loginimui.

**Žemiau pateikta kaip galėtų atrodyti konfigūracijos failas.**

audio_types = mp3,flac,wav
video_types = mkv,avi,mp4
photo_types = svg,jpeg,png
document_types = docx,txt,pdf

dir_to_watch = /home/user/Downloads

types_to_watch = audio,document
