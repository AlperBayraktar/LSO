LSO, diğer adıyla Linux Swap Operator Linux işletim sistemleri için Swap alanını yönetebileceğiniz hem GUİ, hem terminal versiyonu olan bir yazılımdır.

Yapımcılar = Kyronex14, AlperBayraktar

Emeği geçenler = efe3535

Kullanımı

sudo chmod +x lso-gui.py / lso.py

sudo python lso-gui.py / lso.py

GUI Versiyonu için:

pip install tk


------------------------------------------------------------------------------------------------------------------


LSO, also known as Linux Swap Operator, is a software with both GUI and terminal versions that you can manage the Swap area for Linux operating systems.

Devolopers = Kyronex14, AlperBayraktar

Contributors = efe3535


Usage

sudo chmod +x lso-gui.py / lso.py

sudo python lso-gui.py / lso.py

For GUI Version:

pip install tk


------------------------------------------------------------------------------------------------------------------


GUI Version Photo:

![Ekran görüntüsü_2021-06-03_13-33-19](https://user-images.githubusercontent.com/85232699/120631339-713aeb00-c470-11eb-9666-35880e352169.png)

![Ekran görüntüsü_2021-06-03_13-33-31](https://user-images.githubusercontent.com/85232699/120631353-74ce7200-c470-11eb-99de-93f5d53a7a55.png)


------------------------------------------------------------------------------------------------------------------

Son güncelleme 3.06.2021: Home menüsünde swap alanı kullanımı artık hep gözüküyor.

Kullanımı göstermek için output'ı almak gerekiyor, output için böyle bir kod kullandık:

output = os.popen(komut).read()

<hr>

Last update    3.06.2021: Now, users are able to see swap area usage everytime.

To see the usage we need to get the output, for that we used this code:

output = os.popen(command).read()

GUI:

![photo](https://user-images.githubusercontent.com/85285027/120803482-43c36f80-c54c-11eb-9e50-f8ff8c305e8e.png)
