# Cinnamon-Budgie-Linux-OS-14-based-19.04-Ubuntu-Pop требуется флешка на 4 гигабайта вес iso 3Гб 

Update Cinnamon-Budgie-Linux-OS-14-based-19.04-Ubuntu-Pop X64 Android + новое дополненное меню + my skel setting + Android

______________________________________________________________________________________________________________________

Скачать ISO дистрибутив Download Cinnamon Budgie OS 14 19.04 iso https://drive.google.com/open?id=1mh50LlK6ZAbK-nRcHb7h1OgLYMDLirzu + (Android https://yadi.sk/d/Cc-bpsnqtk1b9w) Wayland теперь по быстрее чем был все обновлено новое ядро которое будет есть меньше памяти https://github.com/Griggorii/linux-image-5.2.11_X86_64_zstd_versia_12_griggorii_config/blob/master/README.md версия так же исправлена и нормально загружается на ssd дисках и с компиляцией каких либо программ для разработчиков не будет ядро скомпилирует сразу даже без установки все dev инклюды для этого установлены.

______________________________________________________________________________________________________________________


Внимание насчет ssd дисков одна крупная компания забенифициарила мне крутой ssd диск в поддержку моей системы и вообщем 
картина не радужная система загружается на нём с помощью переключения tty ну т.е перебором CTRL+ALT+F2 F8 и на рандоме 
может загрузится на F6 или F7 это вот результат работы когда компания сломала lightdm споры типа это сустемд виноват или 
нет не обсуждаются так как другие дистрибутивы без д могут даже с флешки не стартануть по этому именно проработав свой 
дистрибутив я знаю что для того что бы везде стартануло в отличии от спорщиков нужен /grub/i386-pc normal.mod efiemu64.o efiemu32.o то есть это было создано не мной даже и не теми спецами , а самим компьютером далее технологию пытались законсперировать , но я уже тогда знал что я создал  впрочем если в tty забить команду после пароля 123 sudo service lightdm 
restart то тоже заходит жаль GDM3 не проработан , а то lightdm сенсор точно поддерживает я проверял на ноутбучном тачпаде , а 
он как известно некоторым что то навроде сенсора и на нажатия в GDM3 не будет работать по этому для смены окружения предпочтительнее lightdm но вы можете менеджер входа сменить с помощью команды от рут dpkg-reconfigure lightdm и выбрать GDM3 
, а там сами смотрите.

Если у вас uefi то тут инструкция впереди создается раздел типа fat32 в gparted флаги ставим efi https://github.com/Griggorii/UEFI_ESP_Linux_Griggorii_instructions_readme из папки ESP без самой папки копируем все фаилы в этот загрузочный раздел потом при установке при uefi она закончится ошибкой , но это ошибкой не будет , а всего лишь предупреждением просто из live не выходим тут же смотрим fstab куда вы установили систему и цифры переписываем как сказано в инструкции.

Chromium браузер цветовая гамма и все такое https://github.com/Griggorii/chromium_swiftshader_super_speed_griggorii_patent_revers в ридми сказано chrome://flags/
Flags особенно srgb это очень сильная вещь просто про это не пишут на телефоне тоже можно сочность так поднять.

Вращать рабочие места в Cinnamon как куб в unity зажать клавиши CTRL+ALT и стерелки вправо , влево на клавиатуре и ALT+TAB 
несколько рабочих окон перебор и верхний левый угол обзор сразу множества окон.

Система переведена на QT5CT не трогайте пока что эти настройки они уже настроены и могут упасть в сигфолт так как другие темы не 
особо готовы и щупать их безопасно только в режиме гостя. И то кому это надо для разработчиков пусть правят свои баги и испытывают на vlc , qbittorent, kdenlive. 

Если пропадает язык в окружении budgie то сделать в терминале от рута dpkg-reconfigure keyboard-configuration

Звуковые эффекты PulseEffects https://www.twitch.tv/videos/412938081 так же в моей системе есть PulseAudio Equalizer но в купе 
с PulseEffects он не будет работать так если PulseAudio Equalizer будете использовать то включайте его первым при загрузке , одновременно работать не могут так как потребляют один и тот же источник звука. В моём /etc/skel звук настроен сверх качественно вы можете включать музыкальные видео клипы и потом сравнить с windows это байтокодовые настройки и лежат они в 
home/ваш_профиль_/.config/pulse на счет systemd кто то говорит что разжирнел итд так это geoclue разжирел ищите и наказывайте 
кто его туда напихал и ещё и в зависимость.

Android cm-x86-14.1-r2.i686.rpm распаковать прямо от рута в корень / и обновить груб после перезагрузки можно загрузиться , документация на рабочем столе читать расскажет как создать data.img
Пароль для установки 123 такой же пароль имеет рут. 
Понадобиться флешка с 4 гигабайтами для того что бы образ влез , 
можно взять флешку и не стирая её закинуть туда образ программой WinSetupFromUSB_1-0 
или программой (unetbootin не помню стирает она данные или нет перед прожигом) , 
точный пример без потери данных на флешке WinSetupFromUSB_1-0 выставив галки 
как на картинке https://imgur.com/a/7NugSRA , потому что не у всех есть флешка лишняя и так этот способ даст избежать лишних затрат на флешки , 
в play market тоже есть утилиты типа DriveDroid и другие с помощью которых можно 
даже с телефона установить по кабелю с ПК и установить образ со смартфона.
Для linux я использую https://unetbootin.github.io/linux_download.html просто делаете бинарник в свойствах
исполняемым и либо запускаете от админа или в терминал в той же папке руню рутирую и закидываю в его окно бинарь 
образ указываю предварительно смонтировав флешечку которая предварительно отформатирована не меньше чем fat32

Установка два способа https://www.youtube.com/watch?v=cs4IJLdpfb8 но, на данный момент только systemback да и быстрее

Flesh card / hdd / usb hdd / sdd / vhd / vhdx minimum size memory 16 gb

Как проверить любой дистрибутив , надо открыть настройки vlc плеера если вылетит значит не годится

Systemback также поможет восстановить систему и отремонтировать grub её и ваши фаилы не пропадут 
если они лежат именно в папке home , только пропадут программы которые установили после , это очень 
удобно на днях я попытался скомпилировать и разработать свой xorg-server в итоге ни клавиатура не 
мышь не работали и с помощью systemback я восстановил систему без всяких переустановок просто подмонтировал 
свой sd раздел в /mnt и включил восстановление системных файлов.

Про интернет соединение без роутера https://www.youtube.com/watch?v=mAUXs3WLuug у вас должно быть там всё на родном языке.
step 3: save правильнее , после step 3 yes ничего не делаем и выходим из терминала.
Потом у меня ниже на панели есть network-manager апплет зайдите щёлкнув на него либо лкм или пкм (потому что я не знаю как ваша мышь работает программно или настроена) изменить соединения и удаляете созданные проводное и Автоматический Ethernet и dsl соединение.

Затем жмёте + и создать из списка выбираете DSL/PPPoE

Соединение DSL 1 , 
предковый интерфейс enp2 , 
