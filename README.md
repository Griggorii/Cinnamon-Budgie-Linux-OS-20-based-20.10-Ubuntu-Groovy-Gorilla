# Cinnamon-Budgie-Linux-OS-20-based-20.10-Ubuntu-Groovy-Gorilla требуется флешка на 4 гигабайта вес iso чуть более 2Гб если после инсталяции вы выделяли впереди 100 Мб и более под efi раздел и выдаст ошибку то система всё равно будет рабочей только надо перезагрузить и успеть вытащить флешку.

Update Cinnamon-Budgie-Linux-OS-20-based-20.10-Ubuntu-Groovy-Gorilla X64 Android + новое дополненное меню + my skel setting + Android

1)OS20 Groovy Gorilla 20.10                    2) OS19 Disco Dingo 19.04
______________________________________________________________________________________________________________________

1) Ubuntu 20.10 Groovy Gorilla X64 2Гб https://drive.google.com/file/d/1O2t73w5JsITPasc8k0cQZuycVo1G-8Jt/view?usp=sharing 08.07.2020

Wayland fast ! Install iso autologin replace lightdm to gdm3 command:

sudo dpkg-reconfigure lightdm

Replace passwd root 123

----------------------------------------------------------------------------------------------------------------------------
2) Cinnamon Budgie OS19 19.04 iso 3Гб https://yadi.sk/d/mz7GqVMUg258Pg update 23.03.2019 



---------------------------------------------------------------------------------------------------------------------------

+ Если кому надо вот в придачу Android 

Android 8: https://yadi.sk/d/u7McqXikcZC6Lw

Android 7.1: https://yadi.sk/d/rlrR6hdaBz0mWA android 7 https://www.youtube.com/watch?v=ua_QQNJtKE8

После установки если опять заидёт в root там можно сменить пароль сразу в терминале это команда passwd не перезагружаясь выйдите верхнем самом правом углу нажмите на значек и выбирите budgie / cinnamon или что захотите , а по центру экрана увидите если там стоит воити как гость то нажмите и поменяйте на своего пользователя , cinnamon  или окружение которое до этого знали.

Для тех кто будет программировать на системе что бы не бояться что она поломается там установлен timeshift

После того что какие проблемы то читать в Читать.txt

Понадобиться флешка с 4 гигабайтами для того что бы образ влез , 
можно взять флешку и не стирая её закинуть туда образ программой Ultra ISO , WinSetupFromUSB_1-0 
или программой (unetbootin не помню стирает она данные или нет перед прожигом) , 
точный пример без потери данных на флешке WinSetupFromUSB_1-0 выставив галки 
как на картинке https://imgur.com/a/7NugSRA , потому что не у всех есть флешка лишняя и так этот способ даст избежать лишних затрат на флешки , 
в play market тоже есть утилиты типа DriveDroid и другие с помощью которых можно 
даже с телефона установить по кабелю с ПК и установить образ со смартфона.
Для linux я использую https://unetbootin.github.io/linux_download.html просто делаете бинарник в свойствах
исполняемым и либо запускаете от админа или в терминал в той же папке руню рутирую и закидываю в его окно бинарь 
образ указываю предварительно смонтировав флешечку которая предварительно отформатирована не меньше чем fat32

Установка 

Flesh card / hdd / usb hdd / sdd / vhd / vhdx minimum size memory 16 gb

Как проверить любой дистрибутив , надо открыть настройки vlc плеера если вылетит значит не годится

Systemback также поможет восстановить систему и отремонтировать grub

Про интернет соединение без роутера https://www.youtube.com/watch?v=mAUXs3WLuug у вас должно быть там всё на родном языке.
step 3: save правильнее , после step 3 yes ничего не делаем и выходим из терминала.
Потом у меня ниже на панели есть network-manager апплет зайдите щёлкнув на него либо лкм или пкм (потому что я не знаю как ваша мышь работает программно или настроена) изменить соединения и удаляете созданные проводное и Автоматический Ethernet и dsl соединение.

Затем жмёте + и создать из списка выбираете DSL/PPPoE

Соединение DSL 1 , 
предковый интерфейс enp2 , 

___________________________________________________________________________________________________________

just test html ignore

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">

<html>
<head>
  <title>
    Exported Tracer Data for VisualVM at Thu Feb 27 23:27:48 IRKT 2020
  </title>
</head>

<body>
  <table border="1" summary="Exported Tracer Data for VisualVM at Thu Feb 27 23:27:48 IRKT 2020">
    <thead>
      <tr>
        <td>Time [ms]</td>
        <td>CPU usage [%]</td>
        <td>GC activity [%]</td>
        <td>Size [B]</td>
        <td>Used [B]</td>
        <td>Size [B]</td>
        <td>Used [B]</td>
        <td>Total loaded</td>
        <td>Shared loaded</td>
        <td>Live</td>
        <td>Daemon</td>
        <td>Compiler activity [%]</td>
        <td>PS MarkSweep [runs/s]</td>
        <td>PS Scavenge [runs/s]</td>
        <td>PS MarkSweep [B]</td>
        <td>PS Scavenge [B]</td>
        <td>Pending Finalizers Count</td>
        <td>mapped</td>
        <td>direct</td>
        <td>mapped [B]</td>
        <td>direct [B]</td>
        <td>mapped [B]</td>
        <td>direct [B]</td>
        <td>Collections.sort</td>
        <td>Arrays.sort</td>
        <td>Collections.sort [%]</td>
        <td>Arrays.sort [%]</td>
        <td>Set.toArray</td>
        <td>List.toArray</td>
        <td>Queue.toArray</td>
        <td>Arrays.asList</td>
        <td>Set.toArray [%]</td>
        <td>List.toArray [%]</td>
        <td>Queue.toArray [%]</td>
        <td>Arrays.asList [%]</td>
        <td>Collections.binarySearch</td>
        <td>Arrays.binarySearch</td>
        <td>Collections.binarySearch [%]</td>
        <td>Arrays.binarySearch [%]</td>
        <td>Set.contains</td>
        <td>Set.containsAll</td>
        <td>List.contains</td>
        <td>List.containsAll</td>
        <td>List.indexOf</td>
        <td>List.lastIndexOf</td>
        <td>Queue.contains</td>
        <td>Queue.containsAll</td>
        <td>Set.contains [%]</td>
        <td>Set.containsAll [%]</td>
        <td>List.contains [%]</td>
        <td>List.containsAll [%]</td>
        <td>List.indexOf [%]</td>
        <td>List.lastIndexOf [%]</td>
        <td>Queue.contains [%]</td>
        <td>Queue.containsAll [%]</td>
        <td>Map.get</td>
        <td>Map.containsKey</td>
        <td>Map.containsValue</td>
        <td>Map.get [%]</td>
        <td>Map.containsKey [%]</td>
        <td>Map.containsValue [%]</td>
        <td>HashMap</td>
        <td>WeakHashMap</td>
        <td>IdentityHashMap</td>
        <td>HashMap [%]</td>
        <td>WeakHashMap [%]</td>
        <td>IdentityHashMap [%]</td>
        <td>Available</td>
        <td>Used</td>
        <td>Reading rate [kB/s]</td>
        <td>Writing rate [kB/s]</td>
        <td>Reading rate [kB/s]</td>
        <td>Writing rate [kB/s]</td>
        <td>dispatchEvent</td>
        <td>invokeAndWait</td>
        <td>invokeLater</td>
        <td>dispatchEvent [%]</td>
        <td>invokeAndWait [%]</td>
        <td>paint</td>
        <td>update</td>
        <td>repaint</td>
        <td>paint [%]</td>
        <td>update [%]</td>
        <td>paintComponent</td>
        <td>paintBorder</td>
        <td>paintChildren</td>
        <td>paint [%]</td>
        <td>update [%]</td>
        <td>paintComponent [%]</td>
        <td>paintBorder [%]</td>
        <td>paintChildren [%]</td>
        <td>getPreferredSize [%]</td>
        <td>getMinimumSize [%]</td>
        <td>getMaximumSize [%]</td>
        <td>preferredLayoutSize</td>
        <td>minimumLayoutSize</td>
        <td>layoutContainer</td>
        <td>preferredLayoutSize [%]</td>
        <td>minimumLayoutSize [%]</td>
        <td>layoutContainer [%]</td>
        <td>actionPerformed</td>
        <td>stateChanged</td>
        <td>propertyChange</td>
        <td>actionPerformed [%]</td>
        <td>stateChanged [%]</td>
        <td>propertyChange [%]</td>
        <td>processComponentEvent</td>
        <td>processFocusEvent</td>
        <td>processKeyEvent</td>
        <td>processMouseEvent</td>
        <td>processMouseMotionEvent</td>
        <td>processMouseWheelEvent</td>
        <td>processInputMethodEvent</td>
        <td>processHierarchyEvent</td>
        <td>processComponentEvent [%]</td>
        <td>processFocusEvent [%]</td>
        <td>processKeyEvent [%]</td>
        <td>processMouseEvent [%]</td>
        <td>processMouseMotionEvent [%]</td>
        <td>processMouseWheelEvent [%]</td>
        <td>processInputMethodEvent [%]</td>
        <td>processHierarchyEvent [%]</td>
        <td>File Read Count</td>
        <td>File Write Count</td>
        <td>File Read Bytes</td>
        <td>File Write Bytes</td>
        <td>File Read Size</td>
        <td>File Write Size</td>
        <td>totalTime [Ticks]</td>
        <td>loadedClasses</td>
        <td>sharedLoadedClasses</td>
        <td>sharedUnloadedClasses</td>
        <td>unloadedClasses</td>
        <td>started</td>
        <td>compilerThread.0.compiles</td>
        <td>compilerThread.0.time [Ticks]</td>
        <td>compilerThread.1.compiles</td>
        <td>compilerThread.1.time [Ticks]</td>
        <td>compilerThread.2.compiles</td>
        <td>compilerThread.2.time [Ticks]</td>
        <td>lastSize [B]</td>
        <td>nmethodCodeSize [B]</td>
        <td>osrBytes [B]</td>
        <td>nmethodSize [B]</td>
        <td>osrCompiles</td>
        <td>osrTime [Ticks]</td>
        <td>standardBytes [B]</td>
        <td>standardCompiles</td>
        <td>standardTime [Ticks]</td>
        <td>totalBailouts</td>
        <td>totalCompiles</td>
        <td>totalInvalidates</td>
        <td>appClassBytes [B]</td>
        <td>appClassLoadCount</td>
        <td>appClassLoadTime [Ticks]</td>
        <td>appClassLoadTime.self [Ticks]</td>
        <td>classInitTime [Ticks]</td>
        <td>classInitTime.self [Ticks]</td>
        <td>classLinkedTime [Ticks]</td>
        <td>classLinkedTime.self [Ticks]</td>
        <td>classVerifyTime [Ticks]</td>
        <td>classVerifyTime.self [Ticks]</td>
        <td>defineAppClassTime [Ticks]</td>
        <td>defineAppClassTime.self [Ticks]</td>
        <td>initializedClasses</td>
        <td>defineAppClasses [Ticks]</td>
        <td>isUnsyncloadClassSet</td>
        <td>jniDefineClassNoLockCalls</td>
        <td>jvmDefineClassNoLockCalls</td>
        <td>jvmFindLoadedClassNoLockCalls</td>
        <td>linkedClasses</td>
        <td>loadInstanceClassFailRate</td>
        <td>loadedBytes [B]</td>
        <td>lookupSysClassTime [Ticks]</td>
        <td>methodBytes [B]</td>
        <td>nonSystemLoaderLockContentionRate</td>
        <td>parseClassTime [Ticks]</td>
        <td>parseClassTime.self [Ticks]</td>
        <td>sharedClassLoadTime [Ticks]</td>
        <td>sharedLoadedBytes [B]</td>
        <td>sharedUnloadedBytes [B]</td>
        <td>sysClassBytes [B]</td>
        <td>sysClassLoadTime [Ticks]</td>
        <td>systemLoaderLockContentionRate</td>
        <td>unsafeDefineClassCalls</td>
        <td>time [Ticks]</td>
        <td>unloadedBytes [B]</td>
        <td>verifiedClasses</td>
        <td>collector.0.invocations</td>
        <td>collector.0.lastEntryTime [Ticks]</td>
        <td>collector.0.lastExitTime [Ticks]</td>
        <td>collector.0.time [Ticks]</td>
        <td>collector.1.invocations</td>
        <td>collector.1.lastEntryTime [Ticks]</td>
        <td>collector.1.lastExitTime [Ticks]</td>
        <td>collector.1.time [Ticks]</td>
        <td>compressedclassspace.capacity [B]</td>
        <td>compressedclassspace.maxCapacity [B]</td>
        <td>compressedclassspace.used [B]</td>
        <td>generation.0.space.0.capacity [B]</td>
        <td>generation.0.capacity [B]</td>
        <td>generation.0.space.0.used [B]</td>
        <td>generation.0.space.1.capacity [B]</td>
        <td>generation.0.space.1.used [B]</td>
        <td>generation.0.space.2.capacity [B]</td>
        <td>generation.0.space.2.used [B]</td>
        <td>generation.1.capacity [B]</td>
        <td>generation.1.space.0.capacity [B]</td>
        <td>generation.1.space.0.used [B]</td>
        <td>metaspace.capacity [B]</td>
        <td>metaspace.maxCapacity [B]</td>
        <td>metaspace.used [B]</td>
        <td>policy.avgBaseFootprint [B]</td>
        <td>policy.avgMajorIntervalTime [Ticks]</td>
        <td>policy.avgMajorPauseTime [Ticks]</td>
        <td>policy.avgMinorIntervalTime [Ticks]</td>
        <td>policy.avgMinorPauseTime [Ticks]</td>
        <td>policy.avgOldLive [B]</td>
        <td>policy.avgPretenuredPaddedAvg [B]</td>
        <td>policy.avgPromotedAvg [B]</td>
        <td>policy.avgPromotedDev [B]</td>
        <td>policy.avgPromotedPaddedAvg [B]</td>
        <td>policy.avgSurvivedAvg [B]</td>
        <td>policy.avgSurvivedDev [B]</td>
        <td>policy.avgSurvivedPaddedAvg [B]</td>
        <td>policy.avgYoungLive [B]</td>
        <td>policy.boundaryMoved [B]</td>
        <td>policy.changeOldGenForMajPauses</td>
        <td>policy.changeOldGenForMinPauses</td>
        <td>policy.changeYoungGenForMajPauses</td>
        <td>policy.changeYoungGenForMinPauses</td>
        <td>policy.decreaseForFootprint</td>
        <td>policy.decrementTenuringThresholdForGcCost</td>
        <td>policy.decrementTenuringThresholdForSurvivorLimit</td>
        <td>policy.desiredSurvivorSize [B]</td>
        <td>policy.edenSize [B]</td>
        <td>policy.freeSpace [B]</td>
        <td>policy.fullFollowsScavenge [B]</td>
        <td>policy.gcTimeLimitExceeded</td>
        <td>policy.increaseOldGenForThroughput</td>
        <td>policy.increaseYoungGenForThroughput</td>
        <td>policy.incrementTenuringThresholdForGcCost</td>
        <td>policy.liveSpace [B]</td>
        <td>policy.liveAtLastFullGc [B]</td>
        <td>policy.majorGcCost [Ticks]</td>
        <td>policy.minorGcCost [Ticks]</td>
        <td>policy.minorPauseTime [Ticks]</td>
        <td>policy.mutatorCost [Ticks]</td>
        <td>policy.oldCapacity [B]</td>
        <td>policy.oldEdenSize [B]</td>
        <td>policy.oldPromoSize [B]</td>
        <td>policy.promoSize [B]</td>
        <td>policy.promoted [B]</td>
        <td>policy.scavengeSkipped [B]</td>
        <td>policy.survivorOverflowed</td>
        <td>policy.survived [B]</td>
        <td>policy.youngCapacity [B]</td>
        <td>tlab.alloc [B]</td>
        <td>tlab.fastWaste [B]</td>
        <td>tlab.gcWaste [B]</td>
        <td>tlab.maxFastWaste [B]</td>
        <td>tlab.maxGcWaste [B]</td>
        <td>tlab.maxSlowWaste [B]</td>
        <td>tlab.slowWaste [B]</td>
        <td>hrt.ticks [Ticks]</td>
        <td>overflow [B]</td>
        <td>size [B]</td>
        <td>timestamp [Ticks]</td>
        <td>used [B]</td>
        <td>_sync_ContendedLockAttempts</td>
        <td>_sync_Deflations</td>
        <td>_sync_EmptyNotifications</td>
        <td>_sync_FailedSpins</td>
        <td>_sync_Inflations</td>
        <td>_sync_FutileWakeups</td>
        <td>_sync_MonExtant</td>
        <td>_sync_MonInCirculation</td>
        <td>_sync_MonScavenged</td>
        <td>_sync_Notifications</td>
        <td>_sync_Parks</td>
        <td>_sync_PrivateA</td>
        <td>_sync_PrivateB</td>
        <td>_sync_SlowEnter</td>
        <td>_sync_SlowExit</td>
        <td>_sync_SlowNotify</td>
        <td>_sync_SlowNotifyAll</td>
        <td>_sync_SuccessfulSpins</td>
        <td>applicationTime [Ticks]</td>
        <td>interruptedBeforeIO</td>
        <td>interruptedDuringIO</td>
        <td>safepointSyncTime [Ticks]</td>
        <td>safepointTime [Ticks]</td>
        <td>safepoints</td>
        <td>threadInterruptSignaled</td>
        <td>vmOperationTime [Ticks]</td>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>23:25:47.684, 27.02.2020</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>160 956 416</td>
        <td>85 269 992</td>
        <td>90 570 752</td>
        <td>84 982 280</td>
        <td>12 054</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>43 562 576</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>148</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5</td>
        <td>5 543</td>
        <td>156</td>
        <td>2 635</td>
        <td>0,0</td>
        <td>9,5</td>
        <td>0,0</td>
        <td>12,5</td>
        <td>6 602</td>
        <td>571</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>365 076</td>
        <td>66</td>
        <td>2 117</td>
        <td>0</td>
        <td>75 096</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>249,1</td>
        <td>0,0</td>
        <td>5,8</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 146 828</td>
        <td>495 472</td>
        <td>0</td>
        <td>566,5</td>
        <td>158,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>24</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>28.50</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>11</td>
        <td>0</td>
        <td>11</td>
        <td>0,9</td>
        <td>0,0</td>
        <td>5 718</td>
        <td>140</td>
        <td>3 880</td>
        <td>199,7</td>
        <td>160,3</td>
        <td>253</td>
        <td>261</td>
        <td>311</td>
        <td>117,0</td>
        <td>42,9</td>
        <td>51,4</td>
        <td>0,3</td>
        <td>73,2</td>
        <td>8,6</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>329</td>
        <td>75</td>
        <td>556</td>
        <td>13,5</td>
        <td>1,4</td>
        <td>159,9</td>
        <td>193</td>
        <td>72</td>
        <td>1 015</td>
        <td>30,8</td>
        <td>1,8</td>
        <td>10,1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>370</td>
        <td>0</td>
        <td>37</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>263</td>
        <td>39 691 872</td>
        <td>166 048</td>
        <td>73 622 760</td>
        <td>0</td>
        <td>0</td>
        <td>4 238 891</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 818 757</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 347 760</td>
        <td>0</td>
        <td>11 386 258</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 603 128</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 060 400</td>
        <td>58 720 256</td>
        <td>82 837 504</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>4 308 096</td>
        <td>12 058 624</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 340 624</td>
        <td>91 095 040</td>
        <td>1 149 239 296</td>
        <td>85 500 056</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>321 911</td>
        <td>479 393</td>
        <td>1 760 092</td>
        <td>5 732 055</td>
        <td>1 983 221</td>
        <td>11 681 718</td>
        <td>5 576 858</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>58 720 256</td>
        <td>89 653 248</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>299 539 584</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>49 152</td>
        <td>0</td>
        <td>0</td>
        <td>4 308 096</td>
        <td>65 011 712</td>
        <td>6 665 505</td>
        <td>10</td>
        <td>12 331</td>
        <td>9</td>
        <td>7 281</td>
        <td>377</td>
        <td>664</td>
        <td>0</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
      </tr>
      <tr>
        <td>23:25:50.756, 27.02.2020</td>
        <td>79,7</td>
        <td>0,4</td>
        <td>168 296 448</td>
        <td>56 648 720</td>
        <td>91 095 040</td>
        <td>85 500 056</td>
        <td>12 192</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>214,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>52 749 280</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>274</td>
        <td>0,0</td>
        <td>34,1</td>
        <td>5</td>
        <td>7 972</td>
        <td>189</td>
        <td>4 050</td>
        <td>0,0</td>
        <td>9,8</td>
        <td>0,0</td>
        <td>12,7</td>
        <td>6 602</td>
        <td>571</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>566 334</td>
        <td>66</td>
        <td>5 811</td>
        <td>0</td>
        <td>81 316</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>273,2</td>
        <td>0,0</td>
        <td>7,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 969 486</td>
        <td>960 819</td>
        <td>0</td>
        <td>608,3</td>
        <td>180,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>24</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.36</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>12</td>
        <td>0</td>
        <td>12</td>
        <td>1,9</td>
        <td>0,0</td>
        <td>5 718</td>
        <td>142</td>
        <td>3 906</td>
        <td>199,7</td>
        <td>162,0</td>
        <td>290</td>
        <td>305</td>
        <td>339</td>
        <td>116,9</td>
        <td>42,9</td>
        <td>52,0</td>
        <td>0,3</td>
        <td>73,2</td>
        <td>8,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>356</td>
        <td>93</td>
        <td>637</td>
        <td>13,7</td>
        <td>1,5</td>
        <td>160,5</td>
        <td>198</td>
        <td>74</td>
        <td>1 123</td>
        <td>30,8</td>
        <td>1,8</td>
        <td>10,2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>370</td>
        <td>0</td>
        <td>37</td>
        <td>2148833519</td>
        <td>51</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>47</td>
        <td>11848</td>
        <td>43</td>
        <td>7705</td>
        <td>463</td>
        <td>75536</td>
        <td>141</td>
        <td>39 886 624</td>
        <td>166 048</td>
        <td>73 953 544</td>
        <td>0</td>
        <td>0</td>
        <td>4 256 917</td>
        <td>541</td>
        <td>2139571306</td>
        <td>0</td>
        <td>538</td>
        <td>0</td>
        <td>18 821 419</td>
        <td>60</td>
        <td>6527267</td>
        <td>2432909</td>
        <td>1158931</td>
        <td>1150913</td>
        <td>1844017</td>
        <td>1026159</td>
        <td>807685</td>
        <td>795870</td>
        <td>8202405</td>
        <td>150193</td>
        <td>56</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>60</td>
        <td>51</td>
        <td>0</td>
        <td>32 358 952</td>
        <td>0</td>
        <td>11 387 490</td>
        <td>0</td>
        <td>191576215</td>
        <td>191411056</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 603 128</td>
        <td>0</td>
        <td>0</td>
        <td>43</td>
        <td>196967103</td>
        <td>211 824</td>
        <td>51</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 060 400</td>
        <td>58 720 256</td>
        <td>82 837 504</td>
        <td>23 310 640</td>
        <td>12 058 624</td>
        <td>4 308 096</td>
        <td>12 058 624</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 340 624</td>
        <td>91 095 040</td>
        <td>1 149 239 296</td>
        <td>85 500 056</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>321 911</td>
        <td>479 393</td>
        <td>1 760 092</td>
        <td>5 732 055</td>
        <td>1 983 221</td>
        <td>11 681 718</td>
        <td>5 576 858</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>58 720 256</td>
        <td>89 653 248</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>299 539 584</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>49 152</td>
        <td>0</td>
        <td>0</td>
        <td>4 308 096</td>
        <td>65 011 712</td>
        <td>6 665 505</td>
        <td>10</td>
        <td>12 331</td>
        <td>9</td>
        <td>7 281</td>
        <td>377</td>
        <td>664</td>
        <td>1122230043</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>129</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>17</td>
        <td>8</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>120</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>606654107</td>
        <td>0</td>
        <td>0</td>
        <td>17156965</td>
        <td>19697827</td>
        <td>12</td>
        <td>0</td>
        <td>466693</td>
      </tr>
      <tr>
        <td>23:25:50.989, 27.02.2020</td>
        <td>68,9</td>
        <td>0,0</td>
        <td>168 296 448</td>
        <td>79 959 360</td>
        <td>91 095 040</td>
        <td>85 500 056</td>
        <td>12 203</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>206,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>52 749 280</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>274</td>
        <td>0,0</td>
        <td>34,1</td>
        <td>5</td>
        <td>7 972</td>
        <td>189</td>
        <td>4 050</td>
        <td>0,0</td>
        <td>9,8</td>
        <td>0,0</td>
        <td>12,7</td>
        <td>6 602</td>
        <td>571</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>566 334</td>
        <td>66</td>
        <td>5 811</td>
        <td>0</td>
        <td>81 316</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>273,2</td>
        <td>0,0</td>
        <td>7,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 969 486</td>
        <td>960 819</td>
        <td>0</td>
        <td>608,3</td>
        <td>180,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>24</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.36</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>12</td>
        <td>0</td>
        <td>12</td>
        <td>1,9</td>
        <td>0,0</td>
        <td>5 718</td>
        <td>142</td>
        <td>3 906</td>
        <td>199,7</td>
        <td>162,0</td>
        <td>290</td>
        <td>305</td>
        <td>339</td>
        <td>116,9</td>
        <td>42,9</td>
        <td>52,0</td>
        <td>0,3</td>
        <td>73,2</td>
        <td>8,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>356</td>
        <td>93</td>
        <td>637</td>
        <td>13,7</td>
        <td>1,5</td>
        <td>160,5</td>
        <td>198</td>
        <td>74</td>
        <td>1 123</td>
        <td>30,8</td>
        <td>1,8</td>
        <td>10,2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>370</td>
        <td>0</td>
        <td>37</td>
        <td>3928126096</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>61</td>
        <td>15473</td>
        <td>17</td>
        <td>2921</td>
        <td>561</td>
        <td>94675</td>
        <td>59</td>
        <td>39 962 976</td>
        <td>166 558</td>
        <td>74 110 136</td>
        <td>8</td>
        <td>24155991</td>
        <td>4 268 579</td>
        <td>631</td>
        <td>3938518513</td>
        <td>0</td>
        <td>646</td>
        <td>0</td>
        <td>18 821 419</td>
        <td>8</td>
        <td>888008</td>
        <td>885380</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 358 952</td>
        <td>0</td>
        <td>11 387 490</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 603 128</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>885380</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 060 400</td>
        <td>58 720 256</td>
        <td>82 837 504</td>
        <td>29 800 320</td>
        <td>12 058 624</td>
        <td>4 308 096</td>
        <td>12 058 624</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 340 624</td>
        <td>91 095 040</td>
        <td>1 149 239 296</td>
        <td>85 500 056</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>321 911</td>
        <td>479 393</td>
        <td>1 760 092</td>
        <td>5 732 055</td>
        <td>1 983 221</td>
        <td>11 681 718</td>
        <td>5 576 858</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>58 720 256</td>
        <td>89 653 248</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>299 539 584</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>49 152</td>
        <td>0</td>
        <td>0</td>
        <td>4 308 096</td>
        <td>65 011 712</td>
        <td>6 665 505</td>
        <td>10</td>
        <td>12 331</td>
        <td>9</td>
        <td>7 281</td>
        <td>377</td>
        <td>664</td>
        <td>918128336</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
      </tr>
      <tr>
        <td>23:25:51.099, 27.02.2020</td>
        <td>76,9</td>
        <td>0,0</td>
        <td>168 296 448</td>
        <td>86 449 040</td>
        <td>91 095 040</td>
        <td>85 500 056</td>
        <td>12 203</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>392,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>52 749 280</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>274</td>
        <td>0,0</td>
        <td>34,1</td>
        <td>5</td>
        <td>7 972</td>
        <td>189</td>
        <td>4 050</td>
        <td>0,0</td>
        <td>9,8</td>
        <td>0,0</td>
        <td>12,7</td>
        <td>6 602</td>
        <td>571</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>566 334</td>
        <td>66</td>
        <td>5 811</td>
        <td>0</td>
        <td>81 316</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>273,2</td>
        <td>0,0</td>
        <td>7,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 969 486</td>
        <td>960 819</td>
        <td>0</td>
        <td>608,3</td>
        <td>180,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>24</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.36</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>12</td>
        <td>0</td>
        <td>12</td>
        <td>1,9</td>
        <td>0,0</td>
        <td>5 718</td>
        <td>142</td>
        <td>3 906</td>
        <td>199,7</td>
        <td>162,0</td>
        <td>290</td>
        <td>305</td>
        <td>339</td>
        <td>116,9</td>
        <td>42,9</td>
        <td>52,0</td>
        <td>0,3</td>
        <td>73,2</td>
        <td>8,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>356</td>
        <td>93</td>
        <td>637</td>
        <td>13,7</td>
        <td>1,5</td>
        <td>160,5</td>
        <td>198</td>
        <td>74</td>
        <td>1 123</td>
        <td>30,8</td>
        <td>1,8</td>
        <td>10,2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>370</td>
        <td>0</td>
        <td>37</td>
        <td>1423114261</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>36</td>
        <td>7720</td>
        <td>0</td>
        <td>0</td>
        <td>315</td>
        <td>57981</td>
        <td>10</td>
        <td>40 045 856</td>
        <td>166 558</td>
        <td>74 301 456</td>
        <td>0</td>
        <td>0</td>
        <td>4 281 637</td>
        <td>360</td>
        <td>1423114261</td>
        <td>0</td>
        <td>360</td>
        <td>0</td>
        <td>18 821 419</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 358 952</td>
        <td>0</td>
        <td>11 387 490</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 603 128</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 060 400</td>
        <td>58 720 256</td>
        <td>82 837 504</td>
        <td>36 649 344</td>
        <td>12 058 624</td>
        <td>4 308 096</td>
        <td>12 058 624</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 340 624</td>
        <td>91 095 040</td>
        <td>1 149 239 296</td>
        <td>85 500 056</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>321 911</td>
        <td>479 393</td>
        <td>1 760 092</td>
        <td>5 732 055</td>
        <td>1 983 221</td>
        <td>11 681 718</td>
        <td>5 576 858</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>58 720 256</td>
        <td>89 653 248</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>299 539 584</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>49 152</td>
        <td>0</td>
        <td>0</td>
        <td>4 308 096</td>
        <td>65 011 712</td>
        <td>6 665 505</td>
        <td>10</td>
        <td>12 331</td>
        <td>9</td>
        <td>7 281</td>
        <td>377</td>
        <td>664</td>
        <td>904277414</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>9</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
      </tr>
      <tr>
        <td>23:25:51.641, 27.02.2020</td>
        <td>47,6</td>
        <td>0,0</td>
        <td>168 296 448</td>
        <td>99 486 344</td>
        <td>91 095 040</td>
        <td>85 500 056</td>
        <td>12 203</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>177,6</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>52 749 280</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>295</td>
        <td>0,0</td>
        <td>34,1</td>
        <td>5</td>
        <td>9 468</td>
        <td>262</td>
        <td>4 588</td>
        <td>0,0</td>
        <td>10,0</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>6 602</td>
        <td>571</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>665 127</td>
        <td>66</td>
        <td>7 681</td>
        <td>0</td>
        <td>86 556</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>286,6</td>
        <td>0,0</td>
        <td>7,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 433 120</td>
        <td>1 190 560</td>
        <td>0</td>
        <td>637,1</td>
        <td>191,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>25</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>4.42</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>30</td>
        <td>0</td>
        <td>24</td>
        <td>58,8</td>
        <td>0,0</td>
        <td>14 511</td>
        <td>144</td>
        <td>4 000</td>
        <td>253,1</td>
        <td>162,5</td>
        <td>290</td>
        <td>305</td>
        <td>339</td>
        <td>116,9</td>
        <td>42,9</td>
        <td>52,0</td>
        <td>0,3</td>
        <td>73,2</td>
        <td>8,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>356</td>
        <td>93</td>
        <td>637</td>
        <td>13,7</td>
        <td>1,5</td>
        <td>160,5</td>
        <td>198</td>
        <td>74</td>
        <td>1 123</td>
        <td>30,8</td>
        <td>1,8</td>
        <td>10,2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>4</td>
        <td>122</td>
        <td>4 096</td>
        <td>4 529</td>
        <td>1 024</td>
        <td>37</td>
        <td>1734348458</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25</td>
        <td>6909</td>
        <td>1</td>
        <td>1015</td>
        <td>69</td>
        <td>457857</td>
        <td>15</td>
        <td>40 149 600</td>
        <td>166 914</td>
        <td>74 543 424</td>
        <td>1</td>
        <td>8222227</td>
        <td>4 302 325</td>
        <td>92</td>
        <td>1726126231</td>
        <td>0</td>
        <td>94</td>
        <td>0</td>
        <td>18 821 419</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 358 952</td>
        <td>0</td>
        <td>11 387 490</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 603 128</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 060 400</td>
        <td>58 720 256</td>
        <td>82 837 504</td>
        <td>44 896 680</td>
        <td>12 058 624</td>
        <td>4 308 096</td>
        <td>12 058 624</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 340 624</td>
        <td>91 095 040</td>
        <td>1 149 239 296</td>
        <td>85 500 056</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>321 911</td>
        <td>479 393</td>
        <td>1 760 092</td>
        <td>5 732 055</td>
        <td>1 983 221</td>
        <td>11 681 718</td>
        <td>5 576 858</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>58 720 256</td>
        <td>89 653 248</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>299 539 584</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>49 152</td>
        <td>0</td>
        <td>0</td>
        <td>4 308 096</td>
        <td>65 011 712</td>
        <td>6 665 505</td>
        <td>10</td>
        <td>12 331</td>
        <td>9</td>
        <td>7 281</td>
        <td>377</td>
        <td>664</td>
        <td>991032335</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>5</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>19</td>
        <td>23</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>983452584</td>
        <td>0</td>
        <td>0</td>
        <td>138235</td>
        <td>834005</td>
        <td>1</td>
        <td>0</td>
        <td>205225</td>
      </tr>
      <tr>
        <td>23:25:52.641, 27.02.2020</td>
        <td>15,7</td>
        <td>0,0</td>
        <td>168 296 448</td>
        <td>108 367 008</td>
        <td>91 095 040</td>
        <td>85 500 056</td>
        <td>12 203</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>52,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>52 749 280</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>297</td>
        <td>0,0</td>
        <td>34,2</td>
        <td>5</td>
        <td>9 879</td>
        <td>286</td>
        <td>4 643</td>
        <td>0,0</td>
        <td>10,1</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>6 602</td>
        <td>571</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>674 645</td>
        <td>66</td>
        <td>7 771</td>
        <td>0</td>
        <td>88 120</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>288,7</td>
        <td>0,0</td>
        <td>7,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 487 083</td>
        <td>1 209 017</td>
        <td>0</td>
        <td>641,9</td>
        <td>193,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>25</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>15</td>
        <td>0</td>
        <td>14</td>
        <td>11,3</td>
        <td>0,0</td>
        <td>16 704</td>
        <td>146</td>
        <td>4 036</td>
        <td>262,2</td>
        <td>162,4</td>
        <td>403</td>
        <td>416</td>
        <td>532</td>
        <td>117,7</td>
        <td>43,0</td>
        <td>64,5</td>
        <td>0,4</td>
        <td>123,7</td>
        <td>8,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>356</td>
        <td>93</td>
        <td>638</td>
        <td>13,7</td>
        <td>1,5</td>
        <td>160,6</td>
        <td>202</td>
        <td>82</td>
        <td>1 309</td>
        <td>31,0</td>
        <td>1,8</td>
        <td>10,4</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>2,8</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>529713391</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>3301</td>
        <td>11</td>
        <td>4387</td>
        <td>46</td>
        <td>12258</td>
        <td>521</td>
        <td>40 395 872</td>
        <td>167 459</td>
        <td>74 990 368</td>
        <td>0</td>
        <td>5176270</td>
        <td>4 317 260</td>
        <td>67</td>
        <td>524013688</td>
        <td>0</td>
        <td>68</td>
        <td>0</td>
        <td>18 821 419</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>6964</td>
        <td>5511</td>
        <td>352804</td>
        <td>268248</td>
        <td>81058</td>
        <td>78000</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>32 367 792</td>
        <td>0</td>
        <td>11 388 282</td>
        <td>0</td>
        <td>7432429</td>
        <td>7429125</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 603 128</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>7780886</td>
        <td>211 824</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 060 400</td>
        <td>58 720 256</td>
        <td>82 837 504</td>
        <td>58 300 032</td>
        <td>12 058 624</td>
        <td>4 308 096</td>
        <td>12 058 624</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 340 624</td>
        <td>91 095 040</td>
        <td>1 149 239 296</td>
        <td>85 500 056</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>321 911</td>
        <td>479 393</td>
        <td>1 760 092</td>
        <td>5 732 055</td>
        <td>1 983 221</td>
        <td>11 681 718</td>
        <td>5 576 858</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>58 720 256</td>
        <td>89 653 248</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>299 539 584</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>49 152</td>
        <td>0</td>
        <td>0</td>
        <td>4 308 096</td>
        <td>65 011 712</td>
        <td>6 665 505</td>
        <td>10</td>
        <td>12 331</td>
        <td>9</td>
        <td>7 281</td>
        <td>377</td>
        <td>664</td>
        <td>1040402168</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>987979750</td>
        <td>0</td>
        <td>0</td>
        <td>262349</td>
        <td>749235</td>
        <td>0</td>
        <td>0</td>
        <td>160166</td>
      </tr>
      <tr>
        <td>23:25:53.641, 27.02.2020</td>
        <td>32,8</td>
        <td>0,1</td>
        <td>173 015 040</td>
        <td>63 887 928</td>
        <td>91 357 184</td>
        <td>85 637 408</td>
        <td>12 212</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>93,5</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>58 581 936</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>304</td>
        <td>0,0</td>
        <td>34,2</td>
        <td>5</td>
        <td>10 230</td>
        <td>310</td>
        <td>4 697</td>
        <td>0,0</td>
        <td>10,1</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>6 602</td>
        <td>621</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>684 151</td>
        <td>66</td>
        <td>7 870</td>
        <td>0</td>
        <td>89 725</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>289,6</td>
        <td>0,0</td>
        <td>7,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 541 261</td>
        <td>1 227 436</td>
        <td>0</td>
        <td>645,3</td>
        <td>194,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>25</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>3.24</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>99</td>
        <td>0</td>
        <td>15</td>
        <td>33,7</td>
        <td>0,0</td>
        <td>19 014</td>
        <td>148</td>
        <td>4 132</td>
        <td>281,2</td>
        <td>163,7</td>
        <td>512</td>
        <td>528</td>
        <td>665</td>
        <td>124,8</td>
        <td>43,4</td>
        <td>74,3</td>
        <td>0,5</td>
        <td>131,2</td>
        <td>9,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>386</td>
        <td>123</td>
        <td>736</td>
        <td>14,0</td>
        <td>1,7</td>
        <td>161,8</td>
        <td>206</td>
        <td>84</td>
        <td>1 417</td>
        <td>31,0</td>
        <td>1,9</td>
        <td>10,5</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>16</td>
        <td>36</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0,9</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>90</td>
        <td>0</td>
        <td>3 321</td>
        <td>0</td>
        <td>36</td>
        <td>959412508</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>4345</td>
        <td>10</td>
        <td>4006</td>
        <td>99</td>
        <td>27578</td>
        <td>79</td>
        <td>40 755 040</td>
        <td>168 961</td>
        <td>75 623 312</td>
        <td>2</td>
        <td>21985144</td>
        <td>4 348 108</td>
        <td>122</td>
        <td>938429885</td>
        <td>1</td>
        <td>124</td>
        <td>0</td>
        <td>18 821 419</td>
        <td>4</td>
        <td>221171</td>
        <td>220189</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>32 367 792</td>
        <td>0</td>
        <td>11 388 282</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 603 128</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>220189</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>2128366584</td>
        <td>2127201452</td>
        <td>7523252</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 071 816</td>
        <td>58 720 256</td>
        <td>87 556 096</td>
        <td>11 452 944</td>
        <td>11 534 336</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>4 389 072</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 397 968</td>
        <td>91 357 184</td>
        <td>1 151 336 448</td>
        <td>85 637 408</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>314</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>295 456</td>
        <td>455 263</td>
        <td>1 661 247</td>
        <td>5 597 757</td>
        <td>1 905 767</td>
        <td>11 315 059</td>
        <td>5 458 079</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 534 336</td>
        <td>64 487 424</td>
        <td>95 420 416</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 420 800</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>4 389 072</td>
        <td>70 778 880</td>
        <td>7 295 590</td>
        <td>938</td>
        <td>85 551</td>
        <td>760</td>
        <td>70 350</td>
        <td>9 099</td>
        <td>13 964</td>
        <td>986090547</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>6</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>17</td>
        <td>23</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1360106394</td>
        <td>0</td>
        <td>0</td>
        <td>3382555</td>
        <td>11764420</td>
        <td>3</td>
        <td>0</td>
        <td>7685598</td>
      </tr>
      <tr>
        <td>23:25:54.731, 27.02.2020</td>
        <td>50,8</td>
        <td>0,0</td>
        <td>173 015 040</td>
        <td>89 037 296</td>
        <td>91 357 184</td>
        <td>85 637 408</td>
        <td>12 250</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>139,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>58 581 936</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>308</td>
        <td>0,0</td>
        <td>34,6</td>
        <td>7</td>
        <td>10 365</td>
        <td>335</td>
        <td>4 913</td>
        <td>0,0</td>
        <td>10,1</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>6 602</td>
        <td>649</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>694 097</td>
        <td>66</td>
        <td>7 973</td>
        <td>0</td>
        <td>91 168</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>291,0</td>
        <td>0,0</td>
        <td>7,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 583 220</td>
        <td>1 246 909</td>
        <td>0</td>
        <td>648,2</td>
        <td>195,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>7.14</td>
        <td>0.23</td>
        <td>0.00</td>
        <td>37</td>
        <td>0</td>
        <td>11</td>
        <td>23,2</td>
        <td>0,0</td>
        <td>20 717</td>
        <td>148</td>
        <td>4 436</td>
        <td>293,4</td>
        <td>163,7</td>
        <td>532</td>
        <td>553</td>
        <td>690</td>
        <td>125,0</td>
        <td>44,4</td>
        <td>75,6</td>
        <td>0,5</td>
        <td>131,1</td>
        <td>9,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>386</td>
        <td>123</td>
        <td>737</td>
        <td>14,0</td>
        <td>1,7</td>
        <td>161,8</td>
        <td>211</td>
        <td>88</td>
        <td>1 599</td>
        <td>31,0</td>
        <td>2,0</td>
        <td>10,8</td>
        <td>10</td>
        <td>3</td>
        <td>0</td>
        <td>26</td>
        <td>108</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>1,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>148</td>
        <td>0</td>
        <td>5 462</td>
        <td>0</td>
        <td>36</td>
        <td>1370865799</td>
        <td>34</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>3204</td>
        <td>20</td>
        <td>4463</td>
        <td>99</td>
        <td>21394</td>
        <td>24</td>
        <td>41 091 968</td>
        <td>169 208</td>
        <td>76 288 544</td>
        <td>0</td>
        <td>3593198</td>
        <td>4 389 076</td>
        <td>134</td>
        <td>1367272601</td>
        <td>0</td>
        <td>135</td>
        <td>0</td>
        <td>18 828 444</td>
        <td>10</td>
        <td>18766054</td>
        <td>4758035</td>
        <td>2850286</td>
        <td>2845057</td>
        <td>1743485</td>
        <td>1334485</td>
        <td>400120</td>
        <td>391808</td>
        <td>14005175</td>
        <td>2431227</td>
        <td>38</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>36</td>
        <td>0</td>
        <td>32 428 776</td>
        <td>11960490</td>
        <td>11 408 610</td>
        <td>0</td>
        <td>260177963</td>
        <td>260153031</td>
        <td>6349</td>
        <td>0</td>
        <td>0</td>
        <td>15 670 710</td>
        <td>271983618</td>
        <td>0</td>
        <td>0</td>
        <td>283867407</td>
        <td>211 824</td>
        <td>36</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 071 816</td>
        <td>58 720 256</td>
        <td>87 556 096</td>
        <td>33 193 200</td>
        <td>11 534 336</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>4 389 072</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 397 968</td>
        <td>91 357 184</td>
        <td>1 151 336 448</td>
        <td>85 637 408</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>295 456</td>
        <td>455 263</td>
        <td>1 661 247</td>
        <td>5 597 757</td>
        <td>1 905 767</td>
        <td>11 315 059</td>
        <td>5 458 079</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 534 336</td>
        <td>64 487 424</td>
        <td>95 420 416</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 420 800</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>4 389 072</td>
        <td>70 778 880</td>
        <td>7 295 590</td>
        <td>938</td>
        <td>85 551</td>
        <td>760</td>
        <td>70 350</td>
        <td>9 099</td>
        <td>13 964</td>
        <td>972735783</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>41</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>3</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>15</td>
        <td>56</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>879311997</td>
        <td>0</td>
        <td>0</td>
        <td>2234215</td>
        <td>4464371</td>
        <td>5</td>
        <td>0</td>
        <td>947324</td>
      </tr>
      <tr>
        <td>23:25:55.642, 27.02.2020</td>
        <td>38,3</td>
        <td>0,0</td>
        <td>173 015 040</td>
        <td>103 997 024</td>
        <td>91 357 184</td>
        <td>85 637 408</td>
        <td>12 250</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>137,5</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>58 581 936</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>311</td>
        <td>0,0</td>
        <td>35,0</td>
        <td>12</td>
        <td>11 346</td>
        <td>487</td>
        <td>6 414</td>
        <td>0,0</td>
        <td>10,3</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>6 602</td>
        <td>1 000</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>707 222</td>
        <td>66</td>
        <td>8 068</td>
        <td>0</td>
        <td>91 723</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>293,2</td>
        <td>0,0</td>
        <td>7,6</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 670 401</td>
        <td>1 269 695</td>
        <td>0</td>
        <td>654,1</td>
        <td>197,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>6.56</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>64</td>
        <td>0</td>
        <td>23</td>
        <td>65,6</td>
        <td>0,0</td>
        <td>23 415</td>
        <td>152</td>
        <td>4 498</td>
        <td>308,3</td>
        <td>163,6</td>
        <td>587</td>
        <td>609</td>
        <td>767</td>
        <td>132,0</td>
        <td>46,7</td>
        <td>88,6</td>
        <td>0,6</td>
        <td>144,8</td>
        <td>9,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>405</td>
        <td>141</td>
        <td>751</td>
        <td>14,1</td>
        <td>35,7</td>
        <td>162,0</td>
        <td>216</td>
        <td>90</td>
        <td>1 641</td>
        <td>31,1</td>
        <td>2,0</td>
        <td>12,4</td>
        <td>25</td>
        <td>5</td>
        <td>0</td>
        <td>26</td>
        <td>108</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>1,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>232</td>
        <td>0</td>
        <td>8 567</td>
        <td>0</td>
        <td>36</td>
        <td>1343578743</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15</td>
        <td>3336</td>
        <td>12</td>
        <td>4960</td>
        <td>68</td>
        <td>16683</td>
        <td>312</td>
        <td>41 300 704</td>
        <td>169 208</td>
        <td>76 697 592</td>
        <td>0</td>
        <td>0</td>
        <td>4 419 876</td>
        <td>95</td>
        <td>1343578743</td>
        <td>0</td>
        <td>95</td>
        <td>0</td>
        <td>18 829 780</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1287</td>
        <td>841</td>
        <td>86944</td>
        <td>80355</td>
        <td>6094</td>
        <td>5597</td>
        <td>4072617</td>
        <td>51851</td>
        <td>1</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>32 430 360</td>
        <td>0</td>
        <td>11 408 786</td>
        <td>0</td>
        <td>4020054</td>
        <td>4019264</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 670 710</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>4157910</td>
        <td>211 824</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 597 568</td>
        <td>1 073 741 824</td>
        <td>14 071 816</td>
        <td>58 720 256</td>
        <td>87 556 096</td>
        <td>50 563 264</td>
        <td>11 534 336</td>
        <td>0</td>
        <td>12 058 624</td>
        <td>4 389 072</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 397 968</td>
        <td>91 357 184</td>
        <td>1 151 336 448</td>
        <td>85 637 408</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>295 456</td>
        <td>455 263</td>
        <td>1 661 247</td>
        <td>5 597 757</td>
        <td>1 905 767</td>
        <td>11 315 059</td>
        <td>5 458 079</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 534 336</td>
        <td>64 487 424</td>
        <td>95 420 416</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 420 800</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>58 720 256</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>4 389 072</td>
        <td>70 778 880</td>
        <td>7 295 590</td>
        <td>938</td>
        <td>85 551</td>
        <td>760</td>
        <td>70 350</td>
        <td>9 099</td>
        <td>13 964</td>
        <td>1025702454</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>772532683</td>
        <td>0</td>
        <td>0</td>
        <td>1049641</td>
        <td>1521208</td>
        <td>2</td>
        <td>0</td>
        <td>101681</td>
      </tr>
      <tr>
        <td>23:25:56.642, 27.02.2020</td>
        <td>14,1</td>
        <td>0,0</td>
        <td>173 015 040</td>
        <td>113 325 392</td>
        <td>91 357 184</td>
        <td>85 637 408</td>
        <td>12 251</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>36,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>58 581 936</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>312</td>
        <td>0,0</td>
        <td>35,0</td>
        <td>12</td>
        <td>11 652</td>
        <td>511</td>
        <td>6 468</td>
        <td>0,0</td>
        <td>10,3</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>6 602</td>
        <td>1 000</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>717 173</td>
        <td>66</td>
        <td>8 160</td>
        <td>0</td>
        <td>92 026</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>294,1</td>
        <td>0,0</td>
        <td>7,6</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 720 659</td>
        <td>1 289 024</td>
        <td>0</td>
        <td>658,1</td>
        <td>198,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.36</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>30</td>
        <td>0</td>
        <td>14</td>
        <td>10,1</td>
        <td>0,0</td>
        <td>25 589</td>
        <td>154</td>
        <td>4 526</td>
        <td>317,6</td>
        <td>163,8</td>
        <td>604</td>
        <td>626</td>
        <td>792</td>
        <td>132,0</td>
        <td>47,3</td>
        <td>90,5</td>
        <td>0,6</td>
        <td>151,6</td>
        <td>9,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>405</td>
        <td>141</td>
        <td>752</td>
        <td>14,1</td>
        <td>35,7</td>
        <td>162,1</td>
        <td>221</td>
        <td>94</td>
        <td>1 645</td>
        <td>31,1</td>
        <td>2,1</td>
        <td>12,4</td>
        <td>25</td>
        <td>5</td>
        <td>0</td>
        <td>28</td>
        <td>158</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>1,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>368</td>
        <td>0</td>
        <td>36</td>
        <td>359539471</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>696</td>
        <td>12</td>
        <td>4331</td>
        <td>36</td>
        <td>9504</td>
        <td>47</td>
        <td>41 429 984</td>
        <td>169 208</td>
        <td>76 943 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 436 943</td>
        <td>53</td>
        <td>359539471</td>
        <td>0</td>
        <td>53</td>
        <td>0</td>
        <td>18 829 780</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 430 360</td>
        <td>0</td>
        <td>11 408 786</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 670 710</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>3868554226</td>
        <td>3882210435</td>
        <td>20771004</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 092 896</td>
        <td>63 963 136</td>
        <td>85 983 232</td>
        <td>984 048</td>
        <td>9 961 472</td>
        <td>4 783 248</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 479 888</td>
        <td>91 750 400</td>
        <td>1 151 336 448</td>
        <td>85 857 968</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>690</td>
        <td>2</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>274 104</td>
        <td>428 954</td>
        <td>1 560 967</td>
        <td>5 516 306</td>
        <td>1 788 496</td>
        <td>10 881 796</td>
        <td>5 390 596</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>63 963 136</td>
        <td>94 896 128</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 353 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>64 487 424</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>81 920</td>
        <td>0</td>
        <td>0</td>
        <td>4 783 248</td>
        <td>70 254 592</td>
        <td>7 291 141</td>
        <td>741</td>
        <td>125 775</td>
        <td>320</td>
        <td>109 691</td>
        <td>7 618</td>
        <td>15 055</td>
        <td>994402479</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>4</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>17</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1276999289</td>
        <td>0</td>
        <td>0</td>
        <td>368081</td>
        <td>21907991</td>
        <td>1</td>
        <td>0</td>
        <td>21029944</td>
      </tr>
      <tr>
        <td>23:25:57.643, 27.02.2020</td>
        <td>12,2</td>
        <td>0,5</td>
        <td>171 442 176</td>
        <td>64 986 800</td>
        <td>91 750 400</td>
        <td>85 857 968</td>
        <td>12 251</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>26,6</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>58 244 160</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>313</td>
        <td>0,0</td>
        <td>35,1</td>
        <td>12</td>
        <td>11 955</td>
        <td>535</td>
        <td>6 522</td>
        <td>0,0</td>
        <td>10,3</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>6 602</td>
        <td>1 000</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>727 111</td>
        <td>66</td>
        <td>8 249</td>
        <td>0</td>
        <td>92 326</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>296,5</td>
        <td>0,0</td>
        <td>7,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 770 442</td>
        <td>1 308 332</td>
        <td>0</td>
        <td>664,0</td>
        <td>200,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>19</td>
        <td>0</td>
        <td>14</td>
        <td>8,0</td>
        <td>0,0</td>
        <td>27 763</td>
        <td>156</td>
        <td>4 554</td>
        <td>322,7</td>
        <td>164,7</td>
        <td>619</td>
        <td>640</td>
        <td>815</td>
        <td>132,0</td>
        <td>47,3</td>
        <td>91,8</td>
        <td>0,6</td>
        <td>156,6</td>
        <td>9,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>405</td>
        <td>141</td>
        <td>753</td>
        <td>14,1</td>
        <td>35,7</td>
        <td>162,1</td>
        <td>225</td>
        <td>96</td>
        <td>1 649</td>
        <td>31,1</td>
        <td>2,1</td>
        <td>12,4</td>
        <td>25</td>
        <td>5</td>
        <td>0</td>
        <td>28</td>
        <td>160</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>1,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>271568119</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1678</td>
        <td>5</td>
        <td>2488</td>
        <td>39</td>
        <td>10904</td>
        <td>17</td>
        <td>41 568 992</td>
        <td>172 106</td>
        <td>77 187 736</td>
        <td>1</td>
        <td>14347619</td>
        <td>4 448 222</td>
        <td>46</td>
        <td>257220500</td>
        <td>0</td>
        <td>47</td>
        <td>0</td>
        <td>18 829 780</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 430 360</td>
        <td>0</td>
        <td>11 408 786</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 670 710</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 092 896</td>
        <td>63 963 136</td>
        <td>85 983 232</td>
        <td>8 154 512</td>
        <td>9 961 472</td>
        <td>4 783 248</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 479 888</td>
        <td>91 750 400</td>
        <td>1 151 336 448</td>
        <td>85 857 968</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>274 104</td>
        <td>428 954</td>
        <td>1 560 967</td>
        <td>5 516 306</td>
        <td>1 788 496</td>
        <td>10 881 796</td>
        <td>5 390 596</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>63 963 136</td>
        <td>94 896 128</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 353 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>64 487 424</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>81 920</td>
        <td>0</td>
        <td>0</td>
        <td>4 783 248</td>
        <td>70 254 592</td>
        <td>7 291 141</td>
        <td>741</td>
        <td>125 775</td>
        <td>320</td>
        <td>109 691</td>
        <td>7 618</td>
        <td>15 055</td>
        <td>975825315</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>697575267</td>
        <td>0</td>
        <td>0</td>
        <td>151135</td>
        <td>650766</td>
        <td>1</td>
        <td>0</td>
        <td>215059</td>
      </tr>
      <tr>
        <td>23:25:58.644, 27.02.2020</td>
        <td>5,9</td>
        <td>0,0</td>
        <td>171 442 176</td>
        <td>74 003 040</td>
        <td>91 750 400</td>
        <td>85 857 968</td>
        <td>12 251</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>8,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>58 244 160</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>316</td>
        <td>0,0</td>
        <td>35,1</td>
        <td>12</td>
        <td>12 255</td>
        <td>559</td>
        <td>6 578</td>
        <td>0,0</td>
        <td>10,3</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>6 602</td>
        <td>1 000</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>737 083</td>
        <td>66</td>
        <td>8 338</td>
        <td>0</td>
        <td>93 889</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>296,6</td>
        <td>0,0</td>
        <td>7,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 820 757</td>
        <td>1 327 723</td>
        <td>0</td>
        <td>665,8</td>
        <td>200,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>16</td>
        <td>0</td>
        <td>15</td>
        <td>7,4</td>
        <td>0,0</td>
        <td>29 937</td>
        <td>158</td>
        <td>4 582</td>
        <td>332,1</td>
        <td>165,2</td>
        <td>634</td>
        <td>654</td>
        <td>838</td>
        <td>131,9</td>
        <td>47,3</td>
        <td>93,3</td>
        <td>0,6</td>
        <td>161,6</td>
        <td>9,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>405</td>
        <td>141</td>
        <td>754</td>
        <td>14,1</td>
        <td>35,7</td>
        <td>162,0</td>
        <td>229</td>
        <td>98</td>
        <td>1 741</td>
        <td>31,1</td>
        <td>2,1</td>
        <td>12,5</td>
        <td>25</td>
        <td>5</td>
        <td>0</td>
        <td>28</td>
        <td>166</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>1,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>151978348</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>19223</td>
        <td>2</td>
        <td>1341</td>
        <td>14</td>
        <td>5196</td>
        <td>2 027</td>
        <td>41 645 696</td>
        <td>172 218</td>
        <td>77 322 280</td>
        <td>0</td>
        <td>1110077</td>
        <td>4 455 560</td>
        <td>22</td>
        <td>150868271</td>
        <td>0</td>
        <td>23</td>
        <td>0</td>
        <td>18 829 780</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 430 360</td>
        <td>0</td>
        <td>11 408 786</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 670 710</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 092 896</td>
        <td>63 963 136</td>
        <td>85 983 232</td>
        <td>21 070 328</td>
        <td>9 961 472</td>
        <td>4 783 248</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 479 888</td>
        <td>91 750 400</td>
        <td>1 151 336 448</td>
        <td>85 857 968</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>274 104</td>
        <td>428 954</td>
        <td>1 560 967</td>
        <td>5 516 306</td>
        <td>1 788 496</td>
        <td>10 881 796</td>
        <td>5 390 596</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>63 963 136</td>
        <td>94 896 128</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 353 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>64 487 424</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>81 920</td>
        <td>0</td>
        <td>0</td>
        <td>4 783 248</td>
        <td>70 254 592</td>
        <td>7 291 141</td>
        <td>741</td>
        <td>125 775</td>
        <td>320</td>
        <td>109 691</td>
        <td>7 618</td>
        <td>15 055</td>
        <td>1034248531</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>981732760</td>
        <td>0</td>
        <td>0</td>
        <td>139426</td>
        <td>661840</td>
        <td>0</td>
        <td>0</td>
        <td>160955</td>
      </tr>
      <tr>
        <td>23:25:59.921, 27.02.2020</td>
        <td>52,2</td>
        <td>0,0</td>
        <td>171 442 176</td>
        <td>120 121 568</td>
        <td>91 750 400</td>
        <td>85 857 968</td>
        <td>12 257</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>129,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>62 349 264</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>318</td>
        <td>0,0</td>
        <td>35,4</td>
        <td>12</td>
        <td>12 607</td>
        <td>583</td>
        <td>6 777</td>
        <td>0,0</td>
        <td>10,4</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 000</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>747 072</td>
        <td>66</td>
        <td>13 135</td>
        <td>0</td>
        <td>102 812</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>299,1</td>
        <td>0,0</td>
        <td>8,3</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>2 886 581</td>
        <td>1 347 371</td>
        <td>0</td>
        <td>672,9</td>
        <td>202,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.12</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>45</td>
        <td>0</td>
        <td>9</td>
        <td>549,9</td>
        <td>0,0</td>
        <td>32 153</td>
        <td>245</td>
        <td>15 168</td>
        <td>337,8</td>
        <td>181,0</td>
        <td>741</td>
        <td>758</td>
        <td>965</td>
        <td>132,4</td>
        <td>50,4</td>
        <td>97,6</td>
        <td>0,7</td>
        <td>174,9</td>
        <td>11,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>616</td>
        <td>141</td>
        <td>971</td>
        <td>16,4</td>
        <td>35,7</td>
        <td>166,4</td>
        <td>236</td>
        <td>110</td>
        <td>11 489</td>
        <td>33,2</td>
        <td>2,2</td>
        <td>15,3</td>
        <td>25</td>
        <td>7</td>
        <td>0</td>
        <td>42</td>
        <td>202</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>3,7</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>2,3</td>
        <td>1,6</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>127</td>
        <td>0</td>
        <td>127</td>
        <td>1233719781</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>21</td>
        <td>6188</td>
        <td>14</td>
        <td>4234</td>
        <td>165</td>
        <td>40187</td>
        <td>390</td>
        <td>42 389 248</td>
        <td>173 454</td>
        <td>78 611 520</td>
        <td>2</td>
        <td>31301959</td>
        <td>4 522 165</td>
        <td>199</td>
        <td>1202417821</td>
        <td>0</td>
        <td>201</td>
        <td>0</td>
        <td>18 832 091</td>
        <td>1</td>
        <td>5623609</td>
        <td>396854</td>
        <td>21318</td>
        <td>20727</td>
        <td>280779</td>
        <td>172985</td>
        <td>106094</td>
        <td>104535</td>
        <td>5429924</td>
        <td>35983</td>
        <td>4</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>32 438 160</td>
        <td>391958</td>
        <td>11 412 306</td>
        <td>0</td>
        <td>15095131</td>
        <td>14852657</td>
        <td>623</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>11275685</td>
        <td>0</td>
        <td>0</td>
        <td>15974995</td>
        <td>211 824</td>
        <td>6</td>
        <td>0</td>
        <td>2531479889</td>
        <td>2528795629</td>
        <td>13661033</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>63 963 136</td>
        <td>89 128 960</td>
        <td>1 896 360</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>6 339 776</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 537 232</td>
        <td>91 750 400</td>
        <td>1 151 336 448</td>
        <td>86 033 160</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>276</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>252 430</td>
        <td>405 565</td>
        <td>1 469 127</td>
        <td>5 598 653</td>
        <td>1 683 759</td>
        <td>10 649 930</td>
        <td>5 485 514</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 448 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>63 963 136</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>6 339 776</td>
        <td>74 973 184</td>
        <td>8 024 475</td>
        <td>103</td>
        <td>19 828</td>
        <td>49</td>
        <td>11 756</td>
        <td>1 568</td>
        <td>3 394</td>
        <td>977018247</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>20</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>3</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>34</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1203318321</td>
        <td>0</td>
        <td>0</td>
        <td>3325934</td>
        <td>18417974</td>
        <td>4</td>
        <td>0</td>
        <td>14235017</td>
      </tr>
      <tr>
        <td>23:26:00.643, 27.02.2020</td>
        <td>57,2</td>
        <td>0,6</td>
        <td>174 587 904</td>
        <td>79 598 224</td>
        <td>91 750 400</td>
        <td>86 033 160</td>
        <td>12 258</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>231,5</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>62 349 264</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>322</td>
        <td>0,0</td>
        <td>35,4</td>
        <td>12</td>
        <td>15 525</td>
        <td>607</td>
        <td>6 837</td>
        <td>0,0</td>
        <td>10,6</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 025</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>757 566</td>
        <td>66</td>
        <td>70 915</td>
        <td>0</td>
        <td>192 853</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>299,8</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>3 108 800</td>
        <td>1 367 239</td>
        <td>0</td>
        <td>693,4</td>
        <td>203,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>1.80</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>50</td>
        <td>0</td>
        <td>31</td>
        <td>122,3</td>
        <td>0,0</td>
        <td>45 548</td>
        <td>373</td>
        <td>27 219</td>
        <td>390,3</td>
        <td>190,5</td>
        <td>741</td>
        <td>758</td>
        <td>965</td>
        <td>132,4</td>
        <td>50,4</td>
        <td>97,6</td>
        <td>0,7</td>
        <td>174,9</td>
        <td>11,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>616</td>
        <td>141</td>
        <td>971</td>
        <td>16,4</td>
        <td>35,7</td>
        <td>166,4</td>
        <td>236</td>
        <td>110</td>
        <td>11 489</td>
        <td>33,2</td>
        <td>2,2</td>
        <td>15,3</td>
        <td>25</td>
        <td>7</td>
        <td>0</td>
        <td>42</td>
        <td>202</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>3,7</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>2,3</td>
        <td>1,6</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>50</td>
        <td>0</td>
        <td>1 846</td>
        <td>0</td>
        <td>36</td>
        <td>2340693118</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>2324</td>
        <td>29</td>
        <td>6846</td>
        <td>118</td>
        <td>31022</td>
        <td>73</td>
        <td>42 645 952</td>
        <td>174 208</td>
        <td>79 195 776</td>
        <td>2</td>
        <td>14026149</td>
        <td>4 554 797</td>
        <td>153</td>
        <td>2326666969</td>
        <td>0</td>
        <td>156</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>4</td>
        <td>2593162</td>
        <td>410770</td>
        <td>720</td>
        <td>545</td>
        <td>84521</td>
        <td>29116</td>
        <td>55106</td>
        <td>54815</td>
        <td>2181176</td>
        <td>23478</td>
        <td>1</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>0</td>
        <td>32 439 232</td>
        <td>0</td>
        <td>11 412 482</td>
        <td>0</td>
        <td>2157496</td>
        <td>2157046</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2675772</td>
        <td>211 824</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>63 963 136</td>
        <td>89 128 960</td>
        <td>25 113 872</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>6 339 776</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 537 232</td>
        <td>91 750 400</td>
        <td>1 151 336 448</td>
        <td>86 033 160</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>252 430</td>
        <td>405 565</td>
        <td>1 469 127</td>
        <td>5 598 653</td>
        <td>1 683 759</td>
        <td>10 649 930</td>
        <td>5 485 514</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 448 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>63 963 136</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>6 339 776</td>
        <td>74 973 184</td>
        <td>8 024 475</td>
        <td>103</td>
        <td>19 828</td>
        <td>49</td>
        <td>11 756</td>
        <td>1 568</td>
        <td>3 394</td>
        <td>1052153166</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>685620071</td>
        <td>0</td>
        <td>0</td>
        <td>3297475</td>
        <td>3772941</td>
        <td>1</td>
        <td>0</td>
        <td>110535</td>
      </tr>
      <tr>
        <td>23:26:01.644, 27.02.2020</td>
        <td>12,4</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>89 954 456</td>
        <td>91 750 400</td>
        <td>86 033 160</td>
        <td>12 258</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>24,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>62 349 264</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>325</td>
        <td>0,0</td>
        <td>35,5</td>
        <td>12</td>
        <td>16 069</td>
        <td>631</td>
        <td>6 899</td>
        <td>0,0</td>
        <td>10,7</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 050</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>768 045</td>
        <td>66</td>
        <td>71 029</td>
        <td>0</td>
        <td>196 196</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>302,1</td>
        <td>0,0</td>
        <td>14,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>3 180 331</td>
        <td>1 387 229</td>
        <td>0</td>
        <td>699,3</td>
        <td>204,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.36</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>86</td>
        <td>0</td>
        <td>17</td>
        <td>10,7</td>
        <td>0,0</td>
        <td>47 827</td>
        <td>375</td>
        <td>27 261</td>
        <td>400,3</td>
        <td>190,9</td>
        <td>1 114</td>
        <td>1 117</td>
        <td>1 466</td>
        <td>139,7</td>
        <td>51,1</td>
        <td>111,1</td>
        <td>1,1</td>
        <td>211,7</td>
        <td>13,6</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>643</td>
        <td>156</td>
        <td>1 286</td>
        <td>16,7</td>
        <td>35,9</td>
        <td>169,8</td>
        <td>245</td>
        <td>130</td>
        <td>11 732</td>
        <td>35,1</td>
        <td>2,6</td>
        <td>15,9</td>
        <td>28</td>
        <td>8</td>
        <td>0</td>
        <td>51</td>
        <td>266</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>2,6</td>
        <td>1,6</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>370</td>
        <td>0</td>
        <td>37</td>
        <td>247043716</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1678</td>
        <td>7</td>
        <td>3259</td>
        <td>29</td>
        <td>8604</td>
        <td>26</td>
        <td>42 714 976</td>
        <td>174 208</td>
        <td>79 312 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 562 064</td>
        <td>39</td>
        <td>247043716</td>
        <td>0</td>
        <td>39</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 439 232</td>
        <td>0</td>
        <td>11 412 482</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>63 963 136</td>
        <td>89 128 960</td>
        <td>32 734 792</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>6 339 776</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 537 232</td>
        <td>91 750 400</td>
        <td>1 151 336 448</td>
        <td>86 033 160</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>252 430</td>
        <td>405 565</td>
        <td>1 469 127</td>
        <td>5 598 653</td>
        <td>1 683 759</td>
        <td>10 649 930</td>
        <td>5 485 514</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 448 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>63 963 136</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>6 339 776</td>
        <td>74 973 184</td>
        <td>8 024 475</td>
        <td>103</td>
        <td>19 828</td>
        <td>49</td>
        <td>11 756</td>
        <td>1 568</td>
        <td>3 394</td>
        <td>967432193</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>949879037</td>
        <td>0</td>
        <td>0</td>
        <td>275543</td>
        <td>718471</td>
        <td>1</td>
        <td>0</td>
        <td>158737</td>
      </tr>
      <tr>
        <td>23:26:02.644, 27.02.2020</td>
        <td>34,5</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>117 331 672</td>
        <td>91 750 400</td>
        <td>86 033 160</td>
        <td>12 258</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>98,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>62 349 264</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>326</td>
        <td>0,0</td>
        <td>35,5</td>
        <td>12</td>
        <td>17 676</td>
        <td>655</td>
        <td>6 953</td>
        <td>0,0</td>
        <td>10,8</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 050</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>779 558</td>
        <td>66</td>
        <td>71 149</td>
        <td>0</td>
        <td>198 921</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>303,3</td>
        <td>0,0</td>
        <td>14,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>3 335 605</td>
        <td>1 408 212</td>
        <td>0</td>
        <td>709,2</td>
        <td>205,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>83</td>
        <td>0</td>
        <td>46</td>
        <td>71,1</td>
        <td>0,0</td>
        <td>65 880</td>
        <td>377</td>
        <td>27 429</td>
        <td>467,0</td>
        <td>190,8</td>
        <td>1 331</td>
        <td>1 315</td>
        <td>1 744</td>
        <td>140,9</td>
        <td>51,7</td>
        <td>117,1</td>
        <td>1,1</td>
        <td>223,6</td>
        <td>13,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>647</td>
        <td>156</td>
        <td>1 304</td>
        <td>16,7</td>
        <td>35,8</td>
        <td>169,6</td>
        <td>249</td>
        <td>142</td>
        <td>11 736</td>
        <td>35,1</td>
        <td>2,8</td>
        <td>15,9</td>
        <td>29</td>
        <td>8</td>
        <td>0</td>
        <td>58</td>
        <td>340</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>2,7</td>
        <td>1,8</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1003844349</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>19</td>
        <td>6258</td>
        <td>18</td>
        <td>5488</td>
        <td>74</td>
        <td>19894</td>
        <td>12</td>
        <td>43 065 376</td>
        <td>174 918</td>
        <td>79 945 128</td>
        <td>1</td>
        <td>6535372</td>
        <td>4 594 187</td>
        <td>111</td>
        <td>997308976</td>
        <td>0</td>
        <td>112</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 439 232</td>
        <td>0</td>
        <td>11 412 482</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>63 963 136</td>
        <td>89 128 960</td>
        <td>62 120 816</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>6 339 776</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 537 232</td>
        <td>91 750 400</td>
        <td>1 151 336 448</td>
        <td>86 033 160</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>252 430</td>
        <td>405 565</td>
        <td>1 469 127</td>
        <td>5 598 653</td>
        <td>1 683 759</td>
        <td>10 649 930</td>
        <td>5 485 514</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 448 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>63 963 136</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>6 339 776</td>
        <td>74 973 184</td>
        <td>8 024 475</td>
        <td>103</td>
        <td>19 828</td>
        <td>49</td>
        <td>11 756</td>
        <td>1 568</td>
        <td>3 394</td>
        <td>1016790020</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>1</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1030160358</td>
        <td>0</td>
        <td>0</td>
        <td>150556</td>
        <td>532097</td>
        <td>2</td>
        <td>0</td>
        <td>68345</td>
      </tr>
      <tr>
        <td>23:26:03.808, 27.02.2020</td>
        <td>46,8</td>
        <td>0,3</td>
        <td>173 539 328</td>
        <td>99 990 816</td>
        <td>91 750 400</td>
        <td>86 092 336</td>
        <td>12 258</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>129,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>63 836 552</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>327</td>
        <td>0,0</td>
        <td>35,5</td>
        <td>12</td>
        <td>18 627</td>
        <td>679</td>
        <td>7 007</td>
        <td>0,0</td>
        <td>10,9</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 050</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>789 797</td>
        <td>66</td>
        <td>133 573</td>
        <td>0</td>
        <td>261 687</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>304,2</td>
        <td>0,0</td>
        <td>22,8</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>3 417 536</td>
        <td>1 427 917</td>
        <td>0</td>
        <td>713,7</td>
        <td>206,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>41</td>
        <td>0</td>
        <td>60</td>
        <td>49,1</td>
        <td>0,0</td>
        <td>72 517</td>
        <td>636</td>
        <td>30 661</td>
        <td>490,9</td>
        <td>192,7</td>
        <td>1 791</td>
        <td>1 720</td>
        <td>2 371</td>
        <td>143,5</td>
        <td>52,5</td>
        <td>127,6</td>
        <td>1,4</td>
        <td>273,4</td>
        <td>13,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>659</td>
        <td>156</td>
        <td>1 347</td>
        <td>16,7</td>
        <td>35,9</td>
        <td>170,2</td>
        <td>254</td>
        <td>156</td>
        <td>11 740</td>
        <td>35,2</td>
        <td>2,8</td>
        <td>15,9</td>
        <td>36</td>
        <td>8</td>
        <td>0</td>
        <td>62</td>
        <td>388</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>2,7</td>
        <td>2,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1261710433</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15</td>
        <td>4254</td>
        <td>10</td>
        <td>3104</td>
        <td>54</td>
        <td>15688</td>
        <td>196</td>
        <td>43 317 088</td>
        <td>192 651</td>
        <td>80 467 312</td>
        <td>5</td>
        <td>449828966</td>
        <td>4 625 261</td>
        <td>75</td>
        <td>811881467</td>
        <td>0</td>
        <td>80</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 439 232</td>
        <td>0</td>
        <td>11 412 482</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>2358345269</td>
        <td>2357564311</td>
        <td>14056956</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>67 108 864</td>
        <td>88 080 384</td>
        <td>46 438 256</td>
        <td>9 961 472</td>
        <td>6 384 440</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 619 152</td>
        <td>91 750 400</td>
        <td>1 151 336 448</td>
        <td>86 092 336</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>128</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>235 381</td>
        <td>380 353</td>
        <td>1 376 441</td>
        <td>5 677 232</td>
        <td>1 586 103</td>
        <td>10 435 543</td>
        <td>5 575 406</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>67 108 864</td>
        <td>98 041 856</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 538 112</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 157 440</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>81 920</td>
        <td>0</td>
        <td>0</td>
        <td>6 384 440</td>
        <td>74 973 184</td>
        <td>8 000 559</td>
        <td>107</td>
        <td>112 336</td>
        <td>44</td>
        <td>79 372</td>
        <td>728</td>
        <td>2 812</td>
        <td>982824043</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>6</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1141493776</td>
        <td>0</td>
        <td>0</td>
        <td>172832</td>
        <td>14908120</td>
        <td>2</td>
        <td>0</td>
        <td>14205432</td>
      </tr>
      <tr>
        <td>23:26:04.708, 27.02.2020</td>
        <td>67,4</td>
        <td>0,3</td>
        <td>174 587 904</td>
        <td>90 577 888</td>
        <td>92 012 544</td>
        <td>86 115 224</td>
        <td>12 258</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>156,4</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>66 911 328</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>330</td>
        <td>0,0</td>
        <td>35,5</td>
        <td>12</td>
        <td>22 718</td>
        <td>703</td>
        <td>7 063</td>
        <td>0,0</td>
        <td>11,2</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 050</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>801 535</td>
        <td>66</td>
        <td>259 223</td>
        <td>0</td>
        <td>409 252</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>305,6</td>
        <td>0,0</td>
        <td>38,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>3 674 348</td>
        <td>1 449 170</td>
        <td>0</td>
        <td>732,6</td>
        <td>207,6</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>433</td>
        <td>0</td>
        <td>379</td>
        <td>100,3</td>
        <td>0,0</td>
        <td>83 459</td>
        <td>1 223</td>
        <td>59 895</td>
        <td>521,4</td>
        <td>213,4</td>
        <td>1 963</td>
        <td>1 876</td>
        <td>2 593</td>
        <td>144,4</td>
        <td>52,6</td>
        <td>129,3</td>
        <td>1,5</td>
        <td>302,5</td>
        <td>18,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>1 190</td>
        <td>156</td>
        <td>1 740</td>
        <td>21,5</td>
        <td>35,8</td>
        <td>173,8</td>
        <td>259</td>
        <td>158</td>
        <td>13 574</td>
        <td>35,5</td>
        <td>2,9</td>
        <td>16,6</td>
        <td>36</td>
        <td>8</td>
        <td>0</td>
        <td>68</td>
        <td>424</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>2,8</td>
        <td>2,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1611837845</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>2449</td>
        <td>24</td>
        <td>5513</td>
        <td>35</td>
        <td>10809</td>
        <td>159</td>
        <td>43 526 048</td>
        <td>192 651</td>
        <td>80 900 920</td>
        <td>0</td>
        <td>0</td>
        <td>4 659 033</td>
        <td>70</td>
        <td>1611837845</td>
        <td>0</td>
        <td>70</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 439 232</td>
        <td>0</td>
        <td>11 412 482</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>1665786422</td>
        <td>1662555629</td>
        <td>15790185</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>67 108 864</td>
        <td>89 128 960</td>
        <td>36 659 752</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>6 524 632</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 676 496</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 115 224</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>217 579</td>
        <td>358 339</td>
        <td>1 292 598</td>
        <td>5 761 972</td>
        <td>1 503 759</td>
        <td>10 273 250</td>
        <td>5 670 329</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>68 681 728</td>
        <td>99 614 720</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 633 056</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>67 108 864</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>6 524 632</td>
        <td>77 594 624</td>
        <td>8 500 299</td>
        <td>1 112</td>
        <td>94 296</td>
        <td>1 056</td>
        <td>41 851</td>
        <td>845</td>
        <td>1 305</td>
        <td>1042877468</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>9</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1024969698</td>
        <td>0</td>
        <td>0</td>
        <td>468342</td>
        <td>17593504</td>
        <td>4</td>
        <td>0</td>
        <td>16358347</td>
      </tr>
      <tr>
        <td>23:26:06.003, 27.02.2020</td>
        <td>47,0</td>
        <td>0,2</td>
        <td>174 587 904</td>
        <td>113 687 688</td>
        <td>92 012 544</td>
        <td>86 124 640</td>
        <td>12 258</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>136,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>65 257 440</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>333</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>26 166</td>
        <td>727</td>
        <td>7 119</td>
        <td>0,0</td>
        <td>11,5</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 050</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>812 506</td>
        <td>66</td>
        <td>259 346</td>
        <td>0</td>
        <td>474 875</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>306,5</td>
        <td>0,0</td>
        <td>38,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>3 971 807</td>
        <td>1 469 660</td>
        <td>0</td>
        <td>751,3</td>
        <td>208,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>38</td>
        <td>0</td>
        <td>19</td>
        <td>71,8</td>
        <td>0,0</td>
        <td>94 547</td>
        <td>1 449</td>
        <td>88 329</td>
        <td>556,4</td>
        <td>231,7</td>
        <td>2 308</td>
        <td>2 196</td>
        <td>3 086</td>
        <td>145,4</td>
        <td>53,3</td>
        <td>135,3</td>
        <td>1,6</td>
        <td>357,2</td>
        <td>23,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>1 904</td>
        <td>156</td>
        <td>2 788</td>
        <td>26,0</td>
        <td>35,9</td>
        <td>183,8</td>
        <td>268</td>
        <td>166</td>
        <td>54 983</td>
        <td>36,3</td>
        <td>3,0</td>
        <td>24,0</td>
        <td>36</td>
        <td>8</td>
        <td>0</td>
        <td>82</td>
        <td>454</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>7,1</td>
        <td>82,9</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1360938817</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>28</td>
        <td>7729</td>
        <td>30</td>
        <td>9117</td>
        <td>23</td>
        <td>6766</td>
        <td>26</td>
        <td>43 760 896</td>
        <td>198 220</td>
        <td>81 388 488</td>
        <td>2</td>
        <td>249149088</td>
        <td>4 699 954</td>
        <td>79</td>
        <td>1111789729</td>
        <td>0</td>
        <td>81</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 439 232</td>
        <td>0</td>
        <td>11 412 482</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>949342586</td>
        <td>949206553</td>
        <td>10491843</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>67 108 864</td>
        <td>89 128 960</td>
        <td>60 920 832</td>
        <td>10 485 760</td>
        <td>8 294 136</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>52 758 416</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 124 640</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>204 015</td>
        <td>334 713</td>
        <td>1 208 155</td>
        <td>6 015 188</td>
        <td>1 581 278</td>
        <td>10 759 023</td>
        <td>5 932 709</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 895 424</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 681 728</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>81 920</td>
        <td>0</td>
        <td>0</td>
        <td>8 294 136</td>
        <td>77 594 624</td>
        <td>8 390 650</td>
        <td>17</td>
        <td>103 341</td>
        <td>10</td>
        <td>38 237</td>
        <td>735</td>
        <td>1 281</td>
        <td>1001733696</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>863029050</td>
        <td>0</td>
        <td>0</td>
        <td>91040</td>
        <td>10945753</td>
        <td>1</td>
        <td>0</td>
        <td>10604607</td>
      </tr>
      <tr>
        <td>23:26:06.645, 27.02.2020</td>
        <td>22,6</td>
        <td>0,4</td>
        <td>174 587 904</td>
        <td>70 696 528</td>
        <td>92 012 544</td>
        <td>86 128 920</td>
        <td>12 258</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>39,8</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>67 052 512</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>336</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>30 369</td>
        <td>751</td>
        <td>7 175</td>
        <td>0,0</td>
        <td>11,9</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 050</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>824 388</td>
        <td>66</td>
        <td>259 676</td>
        <td>0</td>
        <td>560 743</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>307,7</td>
        <td>0,0</td>
        <td>38,6</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>4 394 278</td>
        <td>1 491 061</td>
        <td>0</td>
        <td>775,4</td>
        <td>209,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>34</td>
        <td>0</td>
        <td>24</td>
        <td>99,2</td>
        <td>0,0</td>
        <td>109 892</td>
        <td>2 073</td>
        <td>133 733</td>
        <td>599,8</td>
        <td>256,4</td>
        <td>2 308</td>
        <td>2 196</td>
        <td>3 086</td>
        <td>145,4</td>
        <td>53,3</td>
        <td>135,3</td>
        <td>1,6</td>
        <td>357,2</td>
        <td>23,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>1 904</td>
        <td>156</td>
        <td>2 788</td>
        <td>26,0</td>
        <td>35,9</td>
        <td>183,8</td>
        <td>268</td>
        <td>166</td>
        <td>54 983</td>
        <td>36,3</td>
        <td>3,0</td>
        <td>24,0</td>
        <td>36</td>
        <td>8</td>
        <td>0</td>
        <td>82</td>
        <td>454</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>7,1</td>
        <td>82,9</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>416103882</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15</td>
        <td>4337</td>
        <td>12</td>
        <td>3822</td>
        <td>36</td>
        <td>9019</td>
        <td>85</td>
        <td>43 839 776</td>
        <td>198 220</td>
        <td>81 524 192</td>
        <td>0</td>
        <td>0</td>
        <td>4 711 212</td>
        <td>66</td>
        <td>416103882</td>
        <td>0</td>
        <td>66</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 439 232</td>
        <td>0</td>
        <td>11 412 482</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>1235445547</td>
        <td>1234235037</td>
        <td>19518071</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>67 108 864</td>
        <td>89 128 960</td>
        <td>16 161 736</td>
        <td>11 534 336</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>7 990 040</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 118 864</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 128 920</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>219 660</td>
        <td>315 322</td>
        <td>1 165 628</td>
        <td>6 212 673</td>
        <td>1 600 887</td>
        <td>11 015 334</td>
        <td>6 138 442</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 534 336</td>
        <td>67 633 152</td>
        <td>98 566 144</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 101 152</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 157 440</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>360 448</td>
        <td>0</td>
        <td>0</td>
        <td>7 990 040</td>
        <td>78 118 912</td>
        <td>8 448 498</td>
        <td>67</td>
        <td>50 186</td>
        <td>50</td>
        <td>26 631</td>
        <td>604</td>
        <td>1 040</td>
        <td>990245563</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>6</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>19</td>
        <td>24</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>871051079</td>
        <td>0</td>
        <td>0</td>
        <td>191057</td>
        <td>20385925</td>
        <td>3</td>
        <td>0</td>
        <td>19722551</td>
      </tr>
      <tr>
        <td>23:26:07.741, 27.02.2020</td>
        <td>42,0</td>
        <td>0,2</td>
        <td>174 587 904</td>
        <td>88 957 864</td>
        <td>92 012 544</td>
        <td>86 136 240</td>
        <td>12 258</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>82,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 785 344</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>339</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>33 207</td>
        <td>775</td>
        <td>7 231</td>
        <td>0,0</td>
        <td>12,1</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 050</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>835 196</td>
        <td>66</td>
        <td>362 040</td>
        <td>0</td>
        <td>706 614</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>308,9</td>
        <td>0,0</td>
        <td>47,8</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>4 649 566</td>
        <td>1 511 388</td>
        <td>0</td>
        <td>787,8</td>
        <td>210,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>232</td>
        <td>0</td>
        <td>228</td>
        <td>83,3</td>
        <td>0,0</td>
        <td>120 871</td>
        <td>2 706</td>
        <td>160 787</td>
        <td>636,3</td>
        <td>267,0</td>
        <td>2 476</td>
        <td>2 354</td>
        <td>3 307</td>
        <td>146,4</td>
        <td>53,3</td>
        <td>137,8</td>
        <td>1,7</td>
        <td>384,9</td>
        <td>26,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>2 517</td>
        <td>156</td>
        <td>3 228</td>
        <td>28,6</td>
        <td>35,8</td>
        <td>187,3</td>
        <td>274</td>
        <td>172</td>
        <td>76 230</td>
        <td>36,3</td>
        <td>3,0</td>
        <td>26,8</td>
        <td>36</td>
        <td>8</td>
        <td>0</td>
        <td>82</td>
        <td>466</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>7,1</td>
        <td>120,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>810737387</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>2850</td>
        <td>10</td>
        <td>3286</td>
        <td>16</td>
        <td>5916</td>
        <td>5</td>
        <td>43 961 344</td>
        <td>198 220</td>
        <td>81 804 600</td>
        <td>0</td>
        <td>0</td>
        <td>4 737 437</td>
        <td>35</td>
        <td>810737387</td>
        <td>0</td>
        <td>35</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 439 232</td>
        <td>0</td>
        <td>11 412 482</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>1009100195</td>
        <td>1006594794</td>
        <td>9342262</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>66 584 576</td>
        <td>89 128 960</td>
        <td>32 173 680</td>
        <td>11 534 336</td>
        <td>6 229 720</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 202 704</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 136 240</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>206 079</td>
        <td>296 012</td>
        <td>1 094 118</td>
        <td>6 214 377</td>
        <td>1 442 332</td>
        <td>10 541 376</td>
        <td>6 147 570</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 110 304</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>67 633 152</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>83 840</td>
        <td>0</td>
        <td>0</td>
        <td>6 229 720</td>
        <td>78 643 200</td>
        <td>8 404 084</td>
        <td>26</td>
        <td>130 319</td>
        <td>16</td>
        <td>103 332</td>
        <td>414</td>
        <td>882</td>
        <td>970184433</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>4</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1015582239</td>
        <td>0</td>
        <td>0</td>
        <td>124714</td>
        <td>9869728</td>
        <td>1</td>
        <td>0</td>
        <td>9470208</td>
      </tr>
      <tr>
        <td>23:26:08.645, 27.02.2020</td>
        <td>39,9</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>112 459 448</td>
        <td>92 012 544</td>
        <td>86 136 240</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>25,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 785 344</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>342</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>36 929</td>
        <td>799</td>
        <td>7 287</td>
        <td>0,0</td>
        <td>12,3</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 050</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>847 280</td>
        <td>66</td>
        <td>448 944</td>
        <td>0</td>
        <td>796 174</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>309,7</td>
        <td>0,0</td>
        <td>56,3</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>4 859 424</td>
        <td>1 532 997</td>
        <td>0</td>
        <td>798,6</td>
        <td>211,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>318</td>
        <td>0</td>
        <td>242</td>
        <td>61,6</td>
        <td>0,0</td>
        <td>136 291</td>
        <td>2 921</td>
        <td>165 791</td>
        <td>679,5</td>
        <td>267,3</td>
        <td>2 713</td>
        <td>2 566</td>
        <td>3 623</td>
        <td>148,1</td>
        <td>53,5</td>
        <td>142,4</td>
        <td>1,7</td>
        <td>441,2</td>
        <td>29,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 063</td>
        <td>156</td>
        <td>3 797</td>
        <td>31,2</td>
        <td>35,9</td>
        <td>190,8</td>
        <td>285</td>
        <td>178</td>
        <td>80 063</td>
        <td>37,2</td>
        <td>3,1</td>
        <td>27,4</td>
        <td>36</td>
        <td>8</td>
        <td>0</td>
        <td>90</td>
        <td>478</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>120,8</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>261835741</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>4170</td>
        <td>0</td>
        <td>0</td>
        <td>41</td>
        <td>10696</td>
        <td>43</td>
        <td>44 123 680</td>
        <td>201 642</td>
        <td>82 088 624</td>
        <td>1</td>
        <td>27007934</td>
        <td>4 749 841</td>
        <td>53</td>
        <td>234827807</td>
        <td>0</td>
        <td>54</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4320</td>
        <td>3584</td>
        <td>156596</td>
        <td>115389</td>
        <td>39998</td>
        <td>38205</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>4664937</td>
        <td>4663218</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>4820398</td>
        <td>211 824</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 095 656</td>
        <td>66 584 576</td>
        <td>89 128 960</td>
        <td>55 273 808</td>
        <td>11 534 336</td>
        <td>6 229 720</td>
        <td>11 010 048</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 202 704</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 136 240</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>206 079</td>
        <td>296 012</td>
        <td>1 094 118</td>
        <td>6 214 377</td>
        <td>1 442 332</td>
        <td>10 541 376</td>
        <td>6 147 570</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11 010 048</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 110 304</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>67 633 152</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>83 840</td>
        <td>0</td>
        <td>0</td>
        <td>6 229 720</td>
        <td>78 643 200</td>
        <td>8 404 084</td>
        <td>26</td>
        <td>130 319</td>
        <td>16</td>
        <td>103 332</td>
        <td>414</td>
        <td>882</td>
        <td>1012086318</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>11</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>16</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>41</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1028001554</td>
        <td>0</td>
        <td>0</td>
        <td>97528</td>
        <td>339462</td>
        <td>1</td>
        <td>0</td>
        <td>73816</td>
      </tr>
      <tr>
        <td>23:26:09.645, 27.02.2020</td>
        <td>25,0</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>124 710 104</td>
        <td>92 012 544</td>
        <td>86 136 240</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>163,4</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>66 430 952</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>349</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>37 902</td>
        <td>823</td>
        <td>7 341</td>
        <td>0,0</td>
        <td>12,4</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>857 956</td>
        <td>66</td>
        <td>449 075</td>
        <td>0</td>
        <td>798 559</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>311,1</td>
        <td>0,0</td>
        <td>56,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>4 959 151</td>
        <td>1 553 135</td>
        <td>0</td>
        <td>805,6</td>
        <td>212,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>2.16</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>216</td>
        <td>0</td>
        <td>19</td>
        <td>21,9</td>
        <td>0,0</td>
        <td>141 088</td>
        <td>2 923</td>
        <td>165 980</td>
        <td>697,7</td>
        <td>267,8</td>
        <td>2 988</td>
        <td>2 815</td>
        <td>4 023</td>
        <td>149,7</td>
        <td>53,7</td>
        <td>147,9</td>
        <td>1,8</td>
        <td>468,6</td>
        <td>29,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 069</td>
        <td>156</td>
        <td>3 820</td>
        <td>31,1</td>
        <td>35,8</td>
        <td>190,6</td>
        <td>289</td>
        <td>188</td>
        <td>80 067</td>
        <td>37,5</td>
        <td>3,2</td>
        <td>27,4</td>
        <td>39</td>
        <td>8</td>
        <td>0</td>
        <td>90</td>
        <td>672</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>4,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>122,9</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>60</td>
        <td>0</td>
        <td>2 213</td>
        <td>0</td>
        <td>36</td>
        <td>1645763069</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>2109</td>
        <td>9</td>
        <td>2598</td>
        <td>46</td>
        <td>14749</td>
        <td>20</td>
        <td>44 294 336</td>
        <td>201 642</td>
        <td>82 517 400</td>
        <td>0</td>
        <td>0</td>
        <td>4 787 679</td>
        <td>62</td>
        <td>1645763069</td>
        <td>0</td>
        <td>62</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>2243856395</td>
        <td>2246284643</td>
        <td>12091582</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>87 556 096</td>
        <td>4 088 936</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>5 767 168</td>
        <td>5 607 064</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 978 984</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 188 760</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>206</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>263 101</td>
        <td>317 731</td>
        <td>1 216 294</td>
        <td>6 153 646</td>
        <td>1 352 757</td>
        <td>10 211 919</td>
        <td>6 093 520</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>66 584 576</td>
        <td>97 517 568</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 056 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>776 280</td>
        <td>0</td>
        <td>0</td>
        <td>5 607 064</td>
        <td>77 594 624</td>
        <td>8 309 094</td>
        <td>98</td>
        <td>63 927</td>
        <td>62</td>
        <td>35 143</td>
        <td>5 110</td>
        <td>7 634</td>
        <td>1004279712</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1184512070</td>
        <td>0</td>
        <td>0</td>
        <td>220598</td>
        <td>12939582</td>
        <td>1</td>
        <td>0</td>
        <td>12270458</td>
      </tr>
      <tr>
        <td>23:26:10.645, 27.02.2020</td>
        <td>30,7</td>
        <td>0,3</td>
        <td>173 015 040</td>
        <td>69 613 264</td>
        <td>92 012 544</td>
        <td>86 188 760</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>13,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 430 952</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>350</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>38 215</td>
        <td>847</td>
        <td>7 395</td>
        <td>0,0</td>
        <td>12,4</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>868 437</td>
        <td>66</td>
        <td>449 166</td>
        <td>0</td>
        <td>798 861</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>312,3</td>
        <td>0,0</td>
        <td>56,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 011 630</td>
        <td>1 573 320</td>
        <td>0</td>
        <td>810,4</td>
        <td>213,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>27</td>
        <td>0</td>
        <td>17</td>
        <td>7,4</td>
        <td>0,0</td>
        <td>143 306</td>
        <td>2 925</td>
        <td>166 012</td>
        <td>702,7</td>
        <td>267,7</td>
        <td>3 226</td>
        <td>3 056</td>
        <td>4 392</td>
        <td>152,0</td>
        <td>54,1</td>
        <td>151,5</td>
        <td>2,0</td>
        <td>474,1</td>
        <td>29,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 925</td>
        <td>31,4</td>
        <td>36,1</td>
        <td>191,7</td>
        <td>294</td>
        <td>196</td>
        <td>80 173</td>
        <td>37,6</td>
        <td>3,3</td>
        <td>27,4</td>
        <td>48</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>4,4</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>45099311</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>4221</td>
        <td>14</td>
        <td>3220</td>
        <td>19</td>
        <td>44 316 864</td>
        <td>201 642</td>
        <td>82 555 488</td>
        <td>0</td>
        <td>0</td>
        <td>4 789 108</td>
        <td>29</td>
        <td>45099311</td>
        <td>0</td>
        <td>29</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>87 556 096</td>
        <td>12 741 704</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>5 767 168</td>
        <td>5 607 064</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 978 984</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 188 760</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>263 101</td>
        <td>317 731</td>
        <td>1 216 294</td>
        <td>6 153 646</td>
        <td>1 352 757</td>
        <td>10 211 919</td>
        <td>6 093 520</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>66 584 576</td>
        <td>97 517 568</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 056 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>776 280</td>
        <td>0</td>
        <td>0</td>
        <td>5 607 064</td>
        <td>77 594 624</td>
        <td>8 309 094</td>
        <td>98</td>
        <td>63 927</td>
        <td>62</td>
        <td>35 143</td>
        <td>5 110</td>
        <td>7 634</td>
        <td>1007910039</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>20</td>
        <td>22</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>737124916</td>
        <td>0</td>
        <td>0</td>
        <td>41921</td>
        <td>291330</td>
        <td>1</td>
        <td>0</td>
        <td>76871</td>
      </tr>
      <tr>
        <td>23:26:11.646, 27.02.2020</td>
        <td>18,9</td>
        <td>0,0</td>
        <td>173 015 040</td>
        <td>79 620 144</td>
        <td>92 012 544</td>
        <td>86 188 760</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>154,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 430 952</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>353</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>38 527</td>
        <td>871</td>
        <td>7 451</td>
        <td>0,0</td>
        <td>12,5</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>878 968</td>
        <td>66</td>
        <td>449 257</td>
        <td>0</td>
        <td>800 426</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>312,9</td>
        <td>0,0</td>
        <td>56,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 064 776</td>
        <td>1 593 608</td>
        <td>0</td>
        <td>812,5</td>
        <td>213,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>43</td>
        <td>0</td>
        <td>15</td>
        <td>7,5</td>
        <td>0,0</td>
        <td>145 525</td>
        <td>2 927</td>
        <td>166 044</td>
        <td>709,0</td>
        <td>267,8</td>
        <td>3 268</td>
        <td>3 097</td>
        <td>4 457</td>
        <td>152,1</td>
        <td>54,1</td>
        <td>153,3</td>
        <td>2,0</td>
        <td>478,7</td>
        <td>29,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 927</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>191,5</td>
        <td>299</td>
        <td>200</td>
        <td>80 265</td>
        <td>37,6</td>
        <td>3,3</td>
        <td>27,4</td>
        <td>53</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>4,4</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1543114365</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>4060</td>
        <td>11</td>
        <td>3242</td>
        <td>16</td>
        <td>4650</td>
        <td>137</td>
        <td>44 414 752</td>
        <td>201 642</td>
        <td>82 824 760</td>
        <td>0</td>
        <td>0</td>
        <td>4 815 671</td>
        <td>29</td>
        <td>1543114365</td>
        <td>0</td>
        <td>29</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>87 556 096</td>
        <td>22 909 072</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>5 767 168</td>
        <td>5 607 064</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 978 984</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 188 760</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>263 101</td>
        <td>317 731</td>
        <td>1 216 294</td>
        <td>6 153 646</td>
        <td>1 352 757</td>
        <td>10 211 919</td>
        <td>6 093 520</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>66 584 576</td>
        <td>97 517 568</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 056 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>776 280</td>
        <td>0</td>
        <td>0</td>
        <td>5 607 064</td>
        <td>77 594 624</td>
        <td>8 309 094</td>
        <td>98</td>
        <td>63 927</td>
        <td>62</td>
        <td>35 143</td>
        <td>5 110</td>
        <td>7 634</td>
        <td>1007502536</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1001693823</td>
        <td>0</td>
        <td>0</td>
        <td>184372</td>
        <td>626657</td>
        <td>1</td>
        <td>0</td>
        <td>166223</td>
      </tr>
      <tr>
        <td>23:26:12.646, 27.02.2020</td>
        <td>10,7</td>
        <td>0,0</td>
        <td>173 015 040</td>
        <td>88 535 728</td>
        <td>92 012 544</td>
        <td>86 188 760</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>35,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 430 952</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>354</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>38 838</td>
        <td>895</td>
        <td>7 505</td>
        <td>0,0</td>
        <td>12,5</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>889 460</td>
        <td>66</td>
        <td>449 348</td>
        <td>0</td>
        <td>800 728</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>314,0</td>
        <td>0,0</td>
        <td>56,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 117 338</td>
        <td>1 613 804</td>
        <td>0</td>
        <td>815,8</td>
        <td>214,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>39</td>
        <td>0</td>
        <td>15</td>
        <td>9,4</td>
        <td>0,0</td>
        <td>147 743</td>
        <td>2 929</td>
        <td>166 076</td>
        <td>717,0</td>
        <td>267,9</td>
        <td>3 310</td>
        <td>3 138</td>
        <td>4 522</td>
        <td>152,3</td>
        <td>54,1</td>
        <td>154,7</td>
        <td>2,0</td>
        <td>485,2</td>
        <td>29,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 929</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>191,6</td>
        <td>303</td>
        <td>204</td>
        <td>80 269</td>
        <td>37,7</td>
        <td>3,4</td>
        <td>27,4</td>
        <td>89</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>351914894</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>1065</td>
        <td>2</td>
        <td>417</td>
        <td>13</td>
        <td>3153</td>
        <td>10</td>
        <td>44 540 512</td>
        <td>201 642</td>
        <td>83 074 112</td>
        <td>0</td>
        <td>0</td>
        <td>4 830 419</td>
        <td>19</td>
        <td>351914894</td>
        <td>0</td>
        <td>19</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>87 556 096</td>
        <td>32 198 480</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>5 767 168</td>
        <td>5 607 064</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 978 984</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 188 760</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>263 101</td>
        <td>317 731</td>
        <td>1 216 294</td>
        <td>6 153 646</td>
        <td>1 352 757</td>
        <td>10 211 919</td>
        <td>6 093 520</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>66 584 576</td>
        <td>97 517 568</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 056 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>776 280</td>
        <td>0</td>
        <td>0</td>
        <td>5 607 064</td>
        <td>77 594 624</td>
        <td>8 309 094</td>
        <td>98</td>
        <td>63 927</td>
        <td>62</td>
        <td>35 143</td>
        <td>5 110</td>
        <td>7 634</td>
        <td>1002301572</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>998117925</td>
        <td>0</td>
        <td>0</td>
        <td>171693</td>
        <td>1230638</td>
        <td>2</td>
        <td>0</td>
        <td>651013</td>
      </tr>
      <tr>
        <td>23:26:13.646, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>173 015 040</td>
        <td>98 400 296</td>
        <td>92 012 544</td>
        <td>86 188 760</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>2,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 430 952</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>355</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>39 124</td>
        <td>919</td>
        <td>7 559</td>
        <td>0,0</td>
        <td>12,5</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>899 923</td>
        <td>66</td>
        <td>449 439</td>
        <td>0</td>
        <td>801 030</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>314,5</td>
        <td>0,0</td>
        <td>56,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 169 336</td>
        <td>1 633 967</td>
        <td>0</td>
        <td>817,8</td>
        <td>215,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,5</td>
        <td>0,0</td>
        <td>149 961</td>
        <td>2 931</td>
        <td>166 108</td>
        <td>720,1</td>
        <td>267,6</td>
        <td>3 352</td>
        <td>3 179</td>
        <td>4 587</td>
        <td>152,5</td>
        <td>54,1</td>
        <td>155,8</td>
        <td>2,0</td>
        <td>489,0</td>
        <td>29,4</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 931</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>191,4</td>
        <td>307</td>
        <td>208</td>
        <td>80 276</td>
        <td>37,7</td>
        <td>3,4</td>
        <td>27,5</td>
        <td>89</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25284566</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>546</td>
        <td>0</td>
        <td>340</td>
        <td>14</td>
        <td>28930</td>
        <td>33</td>
        <td>44 559 616</td>
        <td>201 642</td>
        <td>83 104 776</td>
        <td>0</td>
        <td>0</td>
        <td>4 832 685</td>
        <td>16</td>
        <td>25284566</td>
        <td>0</td>
        <td>16</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>87 556 096</td>
        <td>40 660 856</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>5 767 168</td>
        <td>5 607 064</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 978 984</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 188 760</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>263 101</td>
        <td>317 731</td>
        <td>1 216 294</td>
        <td>6 153 646</td>
        <td>1 352 757</td>
        <td>10 211 919</td>
        <td>6 093 520</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>66 584 576</td>
        <td>97 517 568</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 056 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>776 280</td>
        <td>0</td>
        <td>0</td>
        <td>5 607 064</td>
        <td>77 594 624</td>
        <td>8 309 094</td>
        <td>98</td>
        <td>63 927</td>
        <td>62</td>
        <td>35 143</td>
        <td>5 110</td>
        <td>7 634</td>
        <td>981948449</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>9</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>979509466</td>
        <td>0</td>
        <td>0</td>
        <td>166261</td>
        <td>423194</td>
        <td>0</td>
        <td>0</td>
        <td>83490</td>
      </tr>
      <tr>
        <td>23:26:14.646, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>173 015 040</td>
        <td>108 330 160</td>
        <td>92 012 544</td>
        <td>86 188 760</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>1,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 430 952</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>356</td>
        <td>0,0</td>
        <td>35,7</td>
        <td>12</td>
        <td>39 408</td>
        <td>943</td>
        <td>7 613</td>
        <td>0,0</td>
        <td>12,5</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>910 392</td>
        <td>66</td>
        <td>449 530</td>
        <td>0</td>
        <td>801 332</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>316,3</td>
        <td>0,0</td>
        <td>56,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 221 358</td>
        <td>1 654 140</td>
        <td>0</td>
        <td>820,9</td>
        <td>216,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>5,2</td>
        <td>0,0</td>
        <td>152 179</td>
        <td>2 933</td>
        <td>166 140</td>
        <td>726,6</td>
        <td>267,9</td>
        <td>3 394</td>
        <td>3 220</td>
        <td>4 652</td>
        <td>152,7</td>
        <td>54,1</td>
        <td>156,8</td>
        <td>2,0</td>
        <td>492,6</td>
        <td>29,6</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 933</td>
        <td>31,4</td>
        <td>36,1</td>
        <td>192,1</td>
        <td>311</td>
        <td>212</td>
        <td>80 280</td>
        <td>37,7</td>
        <td>3,7</td>
        <td>27,5</td>
        <td>89</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>13129822</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>356</td>
        <td>1</td>
        <td>403</td>
        <td>14</td>
        <td>2739</td>
        <td>4</td>
        <td>44 593 472</td>
        <td>201 642</td>
        <td>83 158 168</td>
        <td>0</td>
        <td>0</td>
        <td>4 834 123</td>
        <td>15</td>
        <td>13129822</td>
        <td>0</td>
        <td>15</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>87 556 096</td>
        <td>52 110 544</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>5 767 168</td>
        <td>5 607 064</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 978 984</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 188 760</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>263 101</td>
        <td>317 731</td>
        <td>1 216 294</td>
        <td>6 153 646</td>
        <td>1 352 757</td>
        <td>10 211 919</td>
        <td>6 093 520</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>66 584 576</td>
        <td>97 517 568</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 056 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>776 280</td>
        <td>0</td>
        <td>0</td>
        <td>5 607 064</td>
        <td>77 594 624</td>
        <td>8 309 094</td>
        <td>98</td>
        <td>63 927</td>
        <td>62</td>
        <td>35 143</td>
        <td>5 110</td>
        <td>7 634</td>
        <td>1017811738</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1029049658</td>
        <td>0</td>
        <td>0</td>
        <td>133685</td>
        <td>476597</td>
        <td>2</td>
        <td>0</td>
        <td>84982</td>
      </tr>
      <tr>
        <td>23:26:15.647, 27.02.2020</td>
        <td>2,4</td>
        <td>0,0</td>
        <td>173 015 040</td>
        <td>118 221 832</td>
        <td>92 012 544</td>
        <td>86 188 760</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,6</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 430 952</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>357</td>
        <td>0,0</td>
        <td>35,6</td>
        <td>12</td>
        <td>39 692</td>
        <td>967</td>
        <td>7 667</td>
        <td>0,0</td>
        <td>12,5</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>920 861</td>
        <td>66</td>
        <td>449 621</td>
        <td>0</td>
        <td>801 634</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>316,2</td>
        <td>0,0</td>
        <td>56,3</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 273 382</td>
        <td>1 674 313</td>
        <td>0</td>
        <td>822,4</td>
        <td>216,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,2</td>
        <td>0,0</td>
        <td>154 397</td>
        <td>2 935</td>
        <td>166 172</td>
        <td>731,3</td>
        <td>267,9</td>
        <td>3 436</td>
        <td>3 261</td>
        <td>4 717</td>
        <td>152,9</td>
        <td>54,2</td>
        <td>157,8</td>
        <td>2,0</td>
        <td>496,4</td>
        <td>29,6</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 935</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>191,9</td>
        <td>316</td>
        <td>216</td>
        <td>80 284</td>
        <td>37,7</td>
        <td>3,7</td>
        <td>27,5</td>
        <td>89</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>6839835</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>500</td>
        <td>1</td>
        <td>1097</td>
        <td>3</td>
        <td>2185</td>
        <td>27</td>
        <td>44 595 488</td>
        <td>201 642</td>
        <td>83 161 992</td>
        <td>0</td>
        <td>0</td>
        <td>4 834 323</td>
        <td>6</td>
        <td>6839835</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>87 556 096</td>
        <td>60 490 416</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>5 767 168</td>
        <td>5 607 064</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>53 978 984</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 188 760</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>263 101</td>
        <td>317 731</td>
        <td>1 216 294</td>
        <td>6 153 646</td>
        <td>1 352 757</td>
        <td>10 211 919</td>
        <td>6 093 520</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>66 584 576</td>
        <td>97 517 568</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>300 056 224</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>776 280</td>
        <td>0</td>
        <td>0</td>
        <td>5 607 064</td>
        <td>77 594 624</td>
        <td>8 309 094</td>
        <td>98</td>
        <td>63 927</td>
        <td>62</td>
        <td>35 143</td>
        <td>5 110</td>
        <td>7 634</td>
        <td>981251753</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>964903575</td>
        <td>0</td>
        <td>0</td>
        <td>80761</td>
        <td>343174</td>
        <td>0</td>
        <td>0</td>
        <td>99860</td>
      </tr>
      <tr>
        <td>23:26:16.647, 27.02.2020</td>
        <td>4,2</td>
        <td>0,2</td>
        <td>174 587 904</td>
        <td>62 426 464</td>
        <td>92 012 544</td>
        <td>86 216 208</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>2,2</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>66 667 576</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>358</td>
        <td>0,0</td>
        <td>35,7</td>
        <td>12</td>
        <td>39 978</td>
        <td>991</td>
        <td>7 721</td>
        <td>0,0</td>
        <td>12,5</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>931 330</td>
        <td>66</td>
        <td>449 712</td>
        <td>0</td>
        <td>801 936</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>318,3</td>
        <td>0,0</td>
        <td>56,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 325 400</td>
        <td>1 694 486</td>
        <td>0</td>
        <td>826,5</td>
        <td>218,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,3</td>
        <td>0,0</td>
        <td>156 615</td>
        <td>2 937</td>
        <td>166 204</td>
        <td>737,0</td>
        <td>268,0</td>
        <td>3 478</td>
        <td>3 302</td>
        <td>4 782</td>
        <td>153,2</td>
        <td>54,2</td>
        <td>159,1</td>
        <td>2,0</td>
        <td>500,7</td>
        <td>29,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 937</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,0</td>
        <td>320</td>
        <td>220</td>
        <td>80 288</td>
        <td>37,7</td>
        <td>3,8</td>
        <td>27,5</td>
        <td>89</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>21634898</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>445</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1724</td>
        <td>162</td>
        <td>44 610 976</td>
        <td>201 642</td>
        <td>83 187 096</td>
        <td>0</td>
        <td>0</td>
        <td>4 835 746</td>
        <td>6</td>
        <td>21634898</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>6783995191</td>
        <td>6782592728</td>
        <td>11410676</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>89 128 960</td>
        <td>5 593 888</td>
        <td>10 485 760</td>
        <td>5 189 240</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 313 808</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 216 208</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>1263</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>270 275</td>
        <td>292 414</td>
        <td>1 147 519</td>
        <td>6 057 205</td>
        <td>1 304 278</td>
        <td>9 970 040</td>
        <td>6 003 091</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 965 824</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>66 584 576</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>334 824</td>
        <td>0</td>
        <td>0</td>
        <td>5 189 240</td>
        <td>77 070 336</td>
        <td>8 314 250</td>
        <td>53</td>
        <td>88 679</td>
        <td>18</td>
        <td>64 925</td>
        <td>4 017</td>
        <td>7 845</td>
        <td>1013648232</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1013238443</td>
        <td>0</td>
        <td>0</td>
        <td>247752</td>
        <td>12162379</td>
        <td>2</td>
        <td>0</td>
        <td>11621079</td>
      </tr>
      <tr>
        <td>23:26:17.687, 27.02.2020</td>
        <td>4,2</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>71 888 616</td>
        <td>92 012 544</td>
        <td>86 216 208</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>7,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 667 576</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>360</td>
        <td>0,0</td>
        <td>35,7</td>
        <td>12</td>
        <td>40 264</td>
        <td>1 015</td>
        <td>7 776</td>
        <td>0,0</td>
        <td>12,6</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>941 805</td>
        <td>66</td>
        <td>449 803</td>
        <td>0</td>
        <td>802 238</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>320,4</td>
        <td>0,0</td>
        <td>56,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 377 433</td>
        <td>1 714 671</td>
        <td>0</td>
        <td>828,3</td>
        <td>220,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,5</td>
        <td>0,0</td>
        <td>158 833</td>
        <td>2 939</td>
        <td>166 236</td>
        <td>742,7</td>
        <td>268,3</td>
        <td>3 520</td>
        <td>3 343</td>
        <td>4 847</td>
        <td>153,3</td>
        <td>54,2</td>
        <td>160,3</td>
        <td>2,1</td>
        <td>504,6</td>
        <td>29,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 939</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>191,8</td>
        <td>324</td>
        <td>224</td>
        <td>80 292</td>
        <td>37,7</td>
        <td>3,8</td>
        <td>27,4</td>
        <td>89</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>79530867</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>540</td>
        <td>3</td>
        <td>2211</td>
        <td>8</td>
        <td>2415</td>
        <td>161</td>
        <td>44 637 792</td>
        <td>201 642</td>
        <td>83 232 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 839 262</td>
        <td>14</td>
        <td>79530867</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>89 128 960</td>
        <td>17 211 848</td>
        <td>10 485 760</td>
        <td>5 189 240</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 313 808</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 216 208</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>270 275</td>
        <td>292 414</td>
        <td>1 147 519</td>
        <td>6 057 205</td>
        <td>1 304 278</td>
        <td>9 970 040</td>
        <td>6 003 091</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 965 824</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>66 584 576</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>334 824</td>
        <td>0</td>
        <td>0</td>
        <td>5 189 240</td>
        <td>77 070 336</td>
        <td>8 314 250</td>
        <td>53</td>
        <td>88 679</td>
        <td>18</td>
        <td>64 925</td>
        <td>4 017</td>
        <td>7 845</td>
        <td>1012037090</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>7</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>948339767</td>
        <td>0</td>
        <td>0</td>
        <td>50422</td>
        <td>276818</td>
        <td>0</td>
        <td>0</td>
        <td>86972</td>
      </tr>
      <tr>
        <td>23:26:18.647, 27.02.2020</td>
        <td>3,1</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>82 401 128</td>
        <td>92 012 544</td>
        <td>86 216 208</td>
        <td>12 264</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 667 576</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>363</td>
        <td>0,0</td>
        <td>35,9</td>
        <td>12</td>
        <td>40 572</td>
        <td>1 039</td>
        <td>7 974</td>
        <td>0,0</td>
        <td>12,6</td>
        <td>0,0</td>
        <td>13,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>952 344</td>
        <td>66</td>
        <td>449 894</td>
        <td>0</td>
        <td>803 805</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>322,1</td>
        <td>0,0</td>
        <td>56,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 435 247</td>
        <td>1 735 238</td>
        <td>0</td>
        <td>832,9</td>
        <td>221,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>40</td>
        <td>0</td>
        <td>16</td>
        <td>34,5</td>
        <td>0,0</td>
        <td>161 051</td>
        <td>2 941</td>
        <td>166 268</td>
        <td>748,9</td>
        <td>268,0</td>
        <td>3 562</td>
        <td>3 384</td>
        <td>4 912</td>
        <td>154,0</td>
        <td>54,2</td>
        <td>162,0</td>
        <td>2,1</td>
        <td>511,5</td>
        <td>29,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 941</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,1</td>
        <td>328</td>
        <td>228</td>
        <td>80 387</td>
        <td>37,8</td>
        <td>3,9</td>
        <td>27,5</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8142434</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>563</td>
        <td>2</td>
        <td>938</td>
        <td>4</td>
        <td>1646</td>
        <td>10</td>
        <td>44 640 832</td>
        <td>201 642</td>
        <td>83 237 552</td>
        <td>0</td>
        <td>0</td>
        <td>4 839 472</td>
        <td>5</td>
        <td>8142434</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 444 656</td>
        <td>0</td>
        <td>11 413 010</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 677 006</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>89 128 960</td>
        <td>27 084 016</td>
        <td>10 485 760</td>
        <td>5 189 240</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 313 808</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 216 208</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>270 275</td>
        <td>292 414</td>
        <td>1 147 519</td>
        <td>6 057 205</td>
        <td>1 304 278</td>
        <td>9 970 040</td>
        <td>6 003 091</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 965 824</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>66 584 576</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>334 824</td>
        <td>0</td>
        <td>0</td>
        <td>5 189 240</td>
        <td>77 070 336</td>
        <td>8 314 250</td>
        <td>53</td>
        <td>88 679</td>
        <td>18</td>
        <td>64 925</td>
        <td>4 017</td>
        <td>7 845</td>
        <td>996137012</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1045259842</td>
        <td>0</td>
        <td>0</td>
        <td>60888</td>
        <td>303408</td>
        <td>1</td>
        <td>0</td>
        <td>100542</td>
      </tr>
      <tr>
        <td>23:26:19.648, 27.02.2020</td>
        <td>14,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>98 084 480</td>
        <td>92 012 544</td>
        <td>86 216 208</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>41,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 667 576</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>365</td>
        <td>0,0</td>
        <td>35,9</td>
        <td>17</td>
        <td>41 280</td>
        <td>1 189</td>
        <td>9 331</td>
        <td>0,0</td>
        <td>12,7</td>
        <td>0,0</td>
        <td>13,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>965 755</td>
        <td>66</td>
        <td>449 985</td>
        <td>0</td>
        <td>804 107</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>323,2</td>
        <td>0,0</td>
        <td>56,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 501 378</td>
        <td>1 758 349</td>
        <td>0</td>
        <td>836,1</td>
        <td>222,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>6,8</td>
        <td>0,0</td>
        <td>163 269</td>
        <td>2 943</td>
        <td>166 300</td>
        <td>756,6</td>
        <td>268,4</td>
        <td>3 604</td>
        <td>3 425</td>
        <td>4 977</td>
        <td>154,3</td>
        <td>54,3</td>
        <td>163,8</td>
        <td>2,1</td>
        <td>515,6</td>
        <td>29,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 943</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,1</td>
        <td>333</td>
        <td>232</td>
        <td>80 394</td>
        <td>37,8</td>
        <td>4,0</td>
        <td>27,5</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>422639178</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>1870</td>
        <td>6</td>
        <td>1720</td>
        <td>36</td>
        <td>8502</td>
        <td>5</td>
        <td>44 824 928</td>
        <td>201 642</td>
        <td>83 558 384</td>
        <td>0</td>
        <td>0</td>
        <td>4 853 446</td>
        <td>49</td>
        <td>422639178</td>
        <td>0</td>
        <td>49</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2674</td>
        <td>2203</td>
        <td>175659</td>
        <td>154051</td>
        <td>20784</td>
        <td>19875</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>360932</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>6814992</td>
        <td>6813640</td>
        <td>1436</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>4257737</td>
        <td>0</td>
        <td>2</td>
        <td>7350385</td>
        <td>211 824</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>89 128 960</td>
        <td>38 581 432</td>
        <td>10 485 760</td>
        <td>5 189 240</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 313 808</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 216 208</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>270 275</td>
        <td>292 414</td>
        <td>1 147 519</td>
        <td>6 057 205</td>
        <td>1 304 278</td>
        <td>9 970 040</td>
        <td>6 003 091</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 965 824</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>66 584 576</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>334 824</td>
        <td>0</td>
        <td>0</td>
        <td>5 189 240</td>
        <td>77 070 336</td>
        <td>8 314 250</td>
        <td>53</td>
        <td>88 679</td>
        <td>18</td>
        <td>64 925</td>
        <td>4 017</td>
        <td>7 845</td>
        <td>959996815</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>4</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1226091817</td>
        <td>0</td>
        <td>0</td>
        <td>522843</td>
        <td>1454467</td>
        <td>5</td>
        <td>0</td>
        <td>190393</td>
      </tr>
      <tr>
        <td>23:26:20.648, 27.02.2020</td>
        <td>3,4</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>107 523 888</td>
        <td>92 012 544</td>
        <td>86 216 208</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>3,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 667 576</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>366</td>
        <td>0,0</td>
        <td>35,9</td>
        <td>17</td>
        <td>41 565</td>
        <td>1 213</td>
        <td>9 388</td>
        <td>0,0</td>
        <td>12,7</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>976 224</td>
        <td>66</td>
        <td>450 078</td>
        <td>0</td>
        <td>804 411</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>323,7</td>
        <td>0,0</td>
        <td>56,4</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 553 437</td>
        <td>1 778 522</td>
        <td>0</td>
        <td>838,4</td>
        <td>222,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>1.08</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>19</td>
        <td>0</td>
        <td>16</td>
        <td>6,9</td>
        <td>0,0</td>
        <td>165 487</td>
        <td>2 945</td>
        <td>166 332</td>
        <td>763,0</td>
        <td>268,4</td>
        <td>3 646</td>
        <td>3 466</td>
        <td>5 042</td>
        <td>154,4</td>
        <td>54,2</td>
        <td>164,8</td>
        <td>2,1</td>
        <td>520,3</td>
        <td>29,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 945</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,0</td>
        <td>338</td>
        <td>236</td>
        <td>80 398</td>
        <td>37,8</td>
        <td>4,0</td>
        <td>27,5</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>30</td>
        <td>0</td>
        <td>1 109</td>
        <td>0</td>
        <td>36</td>
        <td>33455530</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>638</td>
        <td>1</td>
        <td>606</td>
        <td>4</td>
        <td>1219</td>
        <td>53</td>
        <td>44 842 112</td>
        <td>202 280</td>
        <td>83 587 528</td>
        <td>2</td>
        <td>3674577</td>
        <td>4 854 696</td>
        <td>5</td>
        <td>29780952</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>89 128 960</td>
        <td>48 020 840</td>
        <td>10 485 760</td>
        <td>5 189 240</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 313 808</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 216 208</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>270 275</td>
        <td>292 414</td>
        <td>1 147 519</td>
        <td>6 057 205</td>
        <td>1 304 278</td>
        <td>9 970 040</td>
        <td>6 003 091</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 965 824</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>66 584 576</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>334 824</td>
        <td>0</td>
        <td>0</td>
        <td>5 189 240</td>
        <td>77 070 336</td>
        <td>8 314 250</td>
        <td>53</td>
        <td>88 679</td>
        <td>18</td>
        <td>64 925</td>
        <td>4 017</td>
        <td>7 845</td>
        <td>1005449700</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>785015229</td>
        <td>0</td>
        <td>0</td>
        <td>98022</td>
        <td>406504</td>
        <td>1</td>
        <td>0</td>
        <td>145153</td>
      </tr>
      <tr>
        <td>23:26:21.648, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>117 664 360</td>
        <td>92 012 544</td>
        <td>86 216 208</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 667 576</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>367</td>
        <td>0,0</td>
        <td>35,9</td>
        <td>17</td>
        <td>41 851</td>
        <td>1 237</td>
        <td>9 442</td>
        <td>0,0</td>
        <td>12,7</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>986 693</td>
        <td>66</td>
        <td>450 169</td>
        <td>0</td>
        <td>804 713</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>325,2</td>
        <td>0,0</td>
        <td>56,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 605 474</td>
        <td>1 798 695</td>
        <td>0</td>
        <td>841,5</td>
        <td>223,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,7</td>
        <td>0,0</td>
        <td>167 706</td>
        <td>2 947</td>
        <td>166 364</td>
        <td>768,1</td>
        <td>268,4</td>
        <td>3 688</td>
        <td>3 507</td>
        <td>5 107</td>
        <td>155,1</td>
        <td>54,4</td>
        <td>166,3</td>
        <td>2,1</td>
        <td>525,3</td>
        <td>29,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 947</td>
        <td>31,4</td>
        <td>36,1</td>
        <td>192,4</td>
        <td>342</td>
        <td>240</td>
        <td>80 402</td>
        <td>37,9</td>
        <td>4,0</td>
        <td>27,5</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8322276</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1615</td>
        <td>5</td>
        <td>1580</td>
        <td>157</td>
        <td>44 847 584</td>
        <td>202 280</td>
        <td>83 597 248</td>
        <td>0</td>
        <td>0</td>
        <td>4 855 009</td>
        <td>6</td>
        <td>8322276</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 098 920</td>
        <td>66 584 576</td>
        <td>89 128 960</td>
        <td>62 467 160</td>
        <td>10 485 760</td>
        <td>5 189 240</td>
        <td>10 485 760</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 313 808</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 216 208</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>270 275</td>
        <td>292 414</td>
        <td>1 147 519</td>
        <td>6 057 205</td>
        <td>1 304 278</td>
        <td>9 970 040</td>
        <td>6 003 091</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 965 824</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>66 584 576</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>334 824</td>
        <td>0</td>
        <td>0</td>
        <td>5 189 240</td>
        <td>77 070 336</td>
        <td>8 314 250</td>
        <td>53</td>
        <td>88 679</td>
        <td>18</td>
        <td>64 925</td>
        <td>4 017</td>
        <td>7 845</td>
        <td>1037299169</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>985352382</td>
        <td>0</td>
        <td>0</td>
        <td>94523</td>
        <td>543455</td>
        <td>0</td>
        <td>0</td>
        <td>152939</td>
      </tr>
      <tr>
        <td>23:26:22.649, 27.02.2020</td>
        <td>3,4</td>
        <td>0,2</td>
        <td>173 539 328</td>
        <td>61 960 864</td>
        <td>92 012 544</td>
        <td>86 233 824</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 411 760</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>368</td>
        <td>0,0</td>
        <td>35,9</td>
        <td>17</td>
        <td>42 143</td>
        <td>1 261</td>
        <td>9 496</td>
        <td>0,0</td>
        <td>12,7</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>997 162</td>
        <td>66</td>
        <td>450 260</td>
        <td>0</td>
        <td>805 015</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>326,1</td>
        <td>0,0</td>
        <td>56,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 657 522</td>
        <td>1 818 868</td>
        <td>0</td>
        <td>843,6</td>
        <td>224,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>5,6</td>
        <td>0,0</td>
        <td>169 924</td>
        <td>2 949</td>
        <td>166 396</td>
        <td>773,3</td>
        <td>268,5</td>
        <td>3 730</td>
        <td>3 548</td>
        <td>5 172</td>
        <td>155,1</td>
        <td>54,3</td>
        <td>167,2</td>
        <td>2,2</td>
        <td>528,8</td>
        <td>29,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 949</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,2</td>
        <td>346</td>
        <td>244</td>
        <td>80 406</td>
        <td>37,9</td>
        <td>4,1</td>
        <td>27,5</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2171985</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>325</td>
        <td>156</td>
        <td>44 852 416</td>
        <td>202 280</td>
        <td>83 604 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 855 398</td>
        <td>1</td>
        <td>2171985</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>5951084079</td>
        <td>5951218555</td>
        <td>11318893</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>66 584 576</td>
        <td>88 080 384</td>
        <td>6 280 200</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>5 198 216</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 477 648</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 233 824</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>755</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>259 633</td>
        <td>272 750</td>
        <td>1 077 886</td>
        <td>5 971 306</td>
        <td>1 251 159</td>
        <td>9 724 785</td>
        <td>5 922 603</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 885 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>163 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 198 216</td>
        <td>77 070 336</td>
        <td>8 313 445</td>
        <td>63</td>
        <td>137 340</td>
        <td>36</td>
        <td>102 344</td>
        <td>1 115</td>
        <td>3 616</td>
        <td>993638717</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>996072222</td>
        <td>0</td>
        <td>0</td>
        <td>185437</td>
        <td>12058215</td>
        <td>1</td>
        <td>0</td>
        <td>11554937</td>
      </tr>
      <tr>
        <td>23:26:23.649, 27.02.2020</td>
        <td>3,4</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>72 034 640</td>
        <td>92 012 544</td>
        <td>86 233 824</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>1,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 411 760</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>370</td>
        <td>0,0</td>
        <td>35,9</td>
        <td>17</td>
        <td>42 429</td>
        <td>1 285</td>
        <td>9 551</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 007 637</td>
        <td>66</td>
        <td>450 351</td>
        <td>0</td>
        <td>805 317</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>327,4</td>
        <td>0,0</td>
        <td>56,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 709 555</td>
        <td>1 839 053</td>
        <td>0</td>
        <td>848,2</td>
        <td>225,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>8,8</td>
        <td>0,0</td>
        <td>172 142</td>
        <td>2 951</td>
        <td>166 428</td>
        <td>779,0</td>
        <td>268,9</td>
        <td>3 772</td>
        <td>3 589</td>
        <td>5 237</td>
        <td>155,5</td>
        <td>54,4</td>
        <td>169,1</td>
        <td>2,2</td>
        <td>534,4</td>
        <td>29,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 951</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,3</td>
        <td>351</td>
        <td>248</td>
        <td>80 410</td>
        <td>37,9</td>
        <td>4,1</td>
        <td>27,5</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11238145</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>1170</td>
        <td>1</td>
        <td>407</td>
        <td>7</td>
        <td>2209</td>
        <td>19</td>
        <td>44 869 312</td>
        <td>202 280</td>
        <td>83 631 960</td>
        <td>0</td>
        <td>0</td>
        <td>4 856 240</td>
        <td>7</td>
        <td>11238145</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>66 584 576</td>
        <td>88 080 384</td>
        <td>16 641 424</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>5 198 216</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 477 648</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 233 824</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>259 633</td>
        <td>272 750</td>
        <td>1 077 886</td>
        <td>5 971 306</td>
        <td>1 251 159</td>
        <td>9 724 785</td>
        <td>5 922 603</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 885 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>163 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 198 216</td>
        <td>77 070 336</td>
        <td>8 313 445</td>
        <td>63</td>
        <td>137 340</td>
        <td>36</td>
        <td>102 344</td>
        <td>1 115</td>
        <td>3 616</td>
        <td>1003698458</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>1</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1297921556</td>
        <td>0</td>
        <td>0</td>
        <td>244994</td>
        <td>824565</td>
        <td>2</td>
        <td>0</td>
        <td>169310</td>
      </tr>
      <tr>
        <td>23:26:24.649, 27.02.2020</td>
        <td>5,2</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>81 953 808</td>
        <td>92 012 544</td>
        <td>86 233 824</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>9,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 411 760</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>372</td>
        <td>0,0</td>
        <td>35,9</td>
        <td>17</td>
        <td>42 715</td>
        <td>1 309</td>
        <td>9 606</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 018 134</td>
        <td>66</td>
        <td>450 442</td>
        <td>0</td>
        <td>806 882</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>328,8</td>
        <td>0,0</td>
        <td>56,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 762 173</td>
        <td>1 859 297</td>
        <td>0</td>
        <td>850,8</td>
        <td>226,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>7,0</td>
        <td>0,0</td>
        <td>174 360</td>
        <td>2 953</td>
        <td>166 460</td>
        <td>787,1</td>
        <td>269,2</td>
        <td>3 814</td>
        <td>3 630</td>
        <td>5 302</td>
        <td>155,6</td>
        <td>54,3</td>
        <td>170,5</td>
        <td>2,2</td>
        <td>538,5</td>
        <td>29,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 953</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,2</td>
        <td>355</td>
        <td>252</td>
        <td>80 502</td>
        <td>37,9</td>
        <td>4,2</td>
        <td>27,6</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>104135895</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>446</td>
        <td>3</td>
        <td>796</td>
        <td>6</td>
        <td>2250</td>
        <td>38</td>
        <td>44 915 712</td>
        <td>202 996</td>
        <td>83 711 800</td>
        <td>1</td>
        <td>29726141</td>
        <td>4 859 841</td>
        <td>9</td>
        <td>74409754</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>66 584 576</td>
        <td>88 080 384</td>
        <td>22 277 944</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>5 198 216</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 477 648</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 233 824</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>259 633</td>
        <td>272 750</td>
        <td>1 077 886</td>
        <td>5 971 306</td>
        <td>1 251 159</td>
        <td>9 724 785</td>
        <td>5 922 603</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 885 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>163 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 198 216</td>
        <td>77 070 336</td>
        <td>8 313 445</td>
        <td>63</td>
        <td>137 340</td>
        <td>36</td>
        <td>102 344</td>
        <td>1 115</td>
        <td>3 616</td>
        <td>967169480</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>4</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>2</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>721231827</td>
        <td>0</td>
        <td>0</td>
        <td>167538</td>
        <td>760019</td>
        <td>2</td>
        <td>0</td>
        <td>157631</td>
      </tr>
      <tr>
        <td>23:26:25.649, 27.02.2020</td>
        <td>12,9</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>91 491 672</td>
        <td>92 012 544</td>
        <td>86 233 824</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>49,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 411 760</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>373</td>
        <td>0,0</td>
        <td>35,9</td>
        <td>17</td>
        <td>43 004</td>
        <td>1 333</td>
        <td>9 660</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 028 609</td>
        <td>66</td>
        <td>450 533</td>
        <td>0</td>
        <td>807 184</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>329,9</td>
        <td>0,0</td>
        <td>56,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 814 234</td>
        <td>1 879 480</td>
        <td>0</td>
        <td>854,6</td>
        <td>227,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>9,9</td>
        <td>0,0</td>
        <td>176 578</td>
        <td>2 955</td>
        <td>166 492</td>
        <td>796,5</td>
        <td>269,2</td>
        <td>3 856</td>
        <td>3 671</td>
        <td>5 367</td>
        <td>156,3</td>
        <td>54,4</td>
        <td>173,4</td>
        <td>2,2</td>
        <td>545,8</td>
        <td>29,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 955</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,4</td>
        <td>359</td>
        <td>256</td>
        <td>80 506</td>
        <td>38,0</td>
        <td>4,3</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>495411414</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>323</td>
        <td>1</td>
        <td>722</td>
        <td>3</td>
        <td>1679</td>
        <td>36</td>
        <td>44 942 688</td>
        <td>202 996</td>
        <td>83 781 936</td>
        <td>0</td>
        <td>0</td>
        <td>4 866 597</td>
        <td>8</td>
        <td>495411414</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>66 584 576</td>
        <td>88 080 384</td>
        <td>32 435 784</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>5 198 216</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 477 648</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 233 824</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>259 633</td>
        <td>272 750</td>
        <td>1 077 886</td>
        <td>5 971 306</td>
        <td>1 251 159</td>
        <td>9 724 785</td>
        <td>5 922 603</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 885 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>163 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 198 216</td>
        <td>77 070 336</td>
        <td>8 313 445</td>
        <td>63</td>
        <td>137 340</td>
        <td>36</td>
        <td>102 344</td>
        <td>1 115</td>
        <td>3 616</td>
        <td>1008882894</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>971530764</td>
        <td>0</td>
        <td>0</td>
        <td>104383</td>
        <td>419623</td>
        <td>0</td>
        <td>0</td>
        <td>130227</td>
      </tr>
      <tr>
        <td>23:26:26.650, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>101 558 992</td>
        <td>92 012 544</td>
        <td>86 233 824</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>1,1</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 411 760</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>374</td>
        <td>0,0</td>
        <td>36,0</td>
        <td>17</td>
        <td>43 288</td>
        <td>1 357</td>
        <td>9 714</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 039 078</td>
        <td>66</td>
        <td>450 624</td>
        <td>0</td>
        <td>807 486</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>330,4</td>
        <td>0,0</td>
        <td>56,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 866 262</td>
        <td>1 899 653</td>
        <td>0</td>
        <td>856,2</td>
        <td>228,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>6,2</td>
        <td>0,0</td>
        <td>178 796</td>
        <td>2 957</td>
        <td>166 524</td>
        <td>802,1</td>
        <td>269,3</td>
        <td>3 898</td>
        <td>3 712</td>
        <td>5 432</td>
        <td>156,5</td>
        <td>54,4</td>
        <td>174,5</td>
        <td>2,2</td>
        <td>550,3</td>
        <td>29,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 957</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,4</td>
        <td>363</td>
        <td>260</td>
        <td>80 510</td>
        <td>38,1</td>
        <td>4,3</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12913230</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>427</td>
        <td>1</td>
        <td>831</td>
        <td>2</td>
        <td>1268</td>
        <td>178</td>
        <td>44 947 488</td>
        <td>202 996</td>
        <td>83 789 856</td>
        <td>0</td>
        <td>0</td>
        <td>4 867 180</td>
        <td>5</td>
        <td>12913230</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>66 584 576</td>
        <td>88 080 384</td>
        <td>42 503 040</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>5 198 216</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 477 648</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 233 824</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>259 633</td>
        <td>272 750</td>
        <td>1 077 886</td>
        <td>5 971 306</td>
        <td>1 251 159</td>
        <td>9 724 785</td>
        <td>5 922 603</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 885 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>163 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 198 216</td>
        <td>77 070 336</td>
        <td>8 313 445</td>
        <td>63</td>
        <td>137 340</td>
        <td>36</td>
        <td>102 344</td>
        <td>1 115</td>
        <td>3 616</td>
        <td>999069508</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>996320461</td>
        <td>0</td>
        <td>0</td>
        <td>209387</td>
        <td>545028</td>
        <td>1</td>
        <td>0</td>
        <td>95384</td>
      </tr>
      <tr>
        <td>23:26:27.650, 27.02.2020</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>110 973 536</td>
        <td>92 012 544</td>
        <td>86 233 824</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>5,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 411 760</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>375</td>
        <td>0,0</td>
        <td>36,0</td>
        <td>17</td>
        <td>43 575</td>
        <td>1 381</td>
        <td>9 768</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 049 541</td>
        <td>66</td>
        <td>450 715</td>
        <td>0</td>
        <td>807 788</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>332,0</td>
        <td>0,0</td>
        <td>56,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 918 278</td>
        <td>1 919 816</td>
        <td>0</td>
        <td>860,1</td>
        <td>229,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>11,9</td>
        <td>0,0</td>
        <td>181 014</td>
        <td>2 959</td>
        <td>166 556</td>
        <td>813,5</td>
        <td>269,3</td>
        <td>3 940</td>
        <td>3 753</td>
        <td>5 497</td>
        <td>156,8</td>
        <td>54,5</td>
        <td>175,7</td>
        <td>2,2</td>
        <td>560,5</td>
        <td>29,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 959</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,5</td>
        <td>368</td>
        <td>264</td>
        <td>80 514</td>
        <td>38,1</td>
        <td>4,4</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>55702824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>612</td>
        <td>1</td>
        <td>418</td>
        <td>7</td>
        <td>2334</td>
        <td>16</td>
        <td>44 977 920</td>
        <td>202 996</td>
        <td>83 838 008</td>
        <td>0</td>
        <td>0</td>
        <td>4 869 800</td>
        <td>9</td>
        <td>55702824</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>66 584 576</td>
        <td>88 080 384</td>
        <td>52 152 704</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>5 198 216</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 477 648</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 233 824</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>259 633</td>
        <td>272 750</td>
        <td>1 077 886</td>
        <td>5 971 306</td>
        <td>1 251 159</td>
        <td>9 724 785</td>
        <td>5 922 603</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 885 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>163 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 198 216</td>
        <td>77 070 336</td>
        <td>8 313 445</td>
        <td>63</td>
        <td>137 340</td>
        <td>36</td>
        <td>102 344</td>
        <td>1 115</td>
        <td>3 616</td>
        <td>1006159989</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1003409888</td>
        <td>0</td>
        <td>0</td>
        <td>81731</td>
        <td>282373</td>
        <td>1</td>
        <td>0</td>
        <td>76360</td>
      </tr>
      <tr>
        <td>23:26:28.651, 27.02.2020</td>
        <td>4,4</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>121 103 736</td>
        <td>92 012 544</td>
        <td>86 233 824</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>7,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 411 760</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>376</td>
        <td>0,0</td>
        <td>36,0</td>
        <td>17</td>
        <td>43 861</td>
        <td>1 405</td>
        <td>9 822</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 060 016</td>
        <td>66</td>
        <td>450 806</td>
        <td>0</td>
        <td>808 090</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>333,0</td>
        <td>0,0</td>
        <td>56,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>5 970 322</td>
        <td>1 939 999</td>
        <td>0</td>
        <td>862,9</td>
        <td>230,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>7,4</td>
        <td>0,0</td>
        <td>183 232</td>
        <td>2 961</td>
        <td>166 588</td>
        <td>820,4</td>
        <td>269,3</td>
        <td>3 982</td>
        <td>3 794</td>
        <td>5 562</td>
        <td>157,5</td>
        <td>54,4</td>
        <td>177,7</td>
        <td>2,2</td>
        <td>564,6</td>
        <td>29,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 961</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,3</td>
        <td>372</td>
        <td>268</td>
        <td>80 518</td>
        <td>38,1</td>
        <td>4,4</td>
        <td>27,6</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>77879113</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>212</td>
        <td>0</td>
        <td>25990</td>
        <td>188</td>
        <td>44 988 320</td>
        <td>202 996</td>
        <td>83 858 368</td>
        <td>0</td>
        <td>0</td>
        <td>4 871 512</td>
        <td>2</td>
        <td>77802836</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>66 584 576</td>
        <td>88 080 384</td>
        <td>62 276 256</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>10 485 760</td>
        <td>5 198 216</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 477 648</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 233 824</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>259 633</td>
        <td>272 750</td>
        <td>1 077 886</td>
        <td>5 971 306</td>
        <td>1 251 159</td>
        <td>9 724 785</td>
        <td>5 922 603</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 157 440</td>
        <td>99 090 432</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 885 312</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>163 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 198 216</td>
        <td>77 070 336</td>
        <td>8 313 445</td>
        <td>63</td>
        <td>137 340</td>
        <td>36</td>
        <td>102 344</td>
        <td>1 115</td>
        <td>3 616</td>
        <td>981538103</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>981435802</td>
        <td>0</td>
        <td>0</td>
        <td>204333</td>
        <td>626644</td>
        <td>1</td>
        <td>0</td>
        <td>102152</td>
      </tr>
      <tr>
        <td>23:26:29.651, 27.02.2020</td>
        <td>3,9</td>
        <td>0,1</td>
        <td>174 063 616</td>
        <td>64 835 168</td>
        <td>92 012 544</td>
        <td>86 241 152</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,4</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>66 642 688</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>377</td>
        <td>0,0</td>
        <td>36,0</td>
        <td>17</td>
        <td>44 147</td>
        <td>1 429</td>
        <td>9 876</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 070 491</td>
        <td>66</td>
        <td>450 897</td>
        <td>0</td>
        <td>808 392</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>334,9</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 022 374</td>
        <td>1 960 182</td>
        <td>0</td>
        <td>866,9</td>
        <td>231,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>7,9</td>
        <td>0,0</td>
        <td>185 450</td>
        <td>2 963</td>
        <td>166 620</td>
        <td>825,7</td>
        <td>269,3</td>
        <td>4 024</td>
        <td>3 835</td>
        <td>5 627</td>
        <td>157,9</td>
        <td>54,5</td>
        <td>179,4</td>
        <td>2,3</td>
        <td>570,7</td>
        <td>30,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 963</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,6</td>
        <td>376</td>
        <td>272</td>
        <td>80 522</td>
        <td>38,1</td>
        <td>4,5</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8428117</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>722</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1222</td>
        <td>5</td>
        <td>44 990 944</td>
        <td>202 996</td>
        <td>83 862 872</td>
        <td>0</td>
        <td>0</td>
        <td>4 871 754</td>
        <td>6</td>
        <td>8436717</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>6474538122</td>
        <td>6471008931</td>
        <td>8124391</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 604 672</td>
        <td>6 472 824</td>
        <td>9 961 472</td>
        <td>5 107 336</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 510 416</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 241 152</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>668</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>236 949</td>
        <td>265 891</td>
        <td>1 034 624</td>
        <td>5 884 909</td>
        <td>1 203 800</td>
        <td>9 496 312</td>
        <td>5 841 076</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 681 728</td>
        <td>99 614 720</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 803 808</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 157 440</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 107 336</td>
        <td>76 546 048</td>
        <td>8 411 117</td>
        <td>26</td>
        <td>42 325</td>
        <td>11</td>
        <td>25 853</td>
        <td>1 809</td>
        <td>3 639</td>
        <td>1022641186</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1009653883</td>
        <td>0</td>
        <td>0</td>
        <td>79022</td>
        <td>8806481</td>
        <td>2</td>
        <td>0</td>
        <td>8353210</td>
      </tr>
      <tr>
        <td>23:26:30.651, 27.02.2020</td>
        <td>2,4</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>74 486 480</td>
        <td>92 012 544</td>
        <td>86 241 152</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 642 688</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>380</td>
        <td>0,0</td>
        <td>36,0</td>
        <td>17</td>
        <td>44 440</td>
        <td>1 453</td>
        <td>9 932</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 080 994</td>
        <td>66</td>
        <td>450 988</td>
        <td>0</td>
        <td>809 957</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>335,3</td>
        <td>0,0</td>
        <td>56,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 075 029</td>
        <td>1 980 438</td>
        <td>0</td>
        <td>867,5</td>
        <td>232,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>5,3</td>
        <td>0,0</td>
        <td>187 668</td>
        <td>2 965</td>
        <td>166 652</td>
        <td>832,5</td>
        <td>269,6</td>
        <td>4 066</td>
        <td>3 876</td>
        <td>5 692</td>
        <td>158,1</td>
        <td>54,5</td>
        <td>180,5</td>
        <td>2,3</td>
        <td>574,6</td>
        <td>30,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 965</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,6</td>
        <td>380</td>
        <td>276</td>
        <td>80 614</td>
        <td>38,2</td>
        <td>4,5</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2837595</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1134</td>
        <td>182</td>
        <td>44 999 296</td>
        <td>202 996</td>
        <td>83 875 440</td>
        <td>0</td>
        <td>0</td>
        <td>4 872 222</td>
        <td>4</td>
        <td>2837595</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 604 672</td>
        <td>16 971 920</td>
        <td>9 961 472</td>
        <td>5 107 336</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 510 416</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 241 152</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>236 949</td>
        <td>265 891</td>
        <td>1 034 624</td>
        <td>5 884 909</td>
        <td>1 203 800</td>
        <td>9 496 312</td>
        <td>5 841 076</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 681 728</td>
        <td>99 614 720</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 803 808</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 157 440</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 107 336</td>
        <td>76 546 048</td>
        <td>8 411 117</td>
        <td>26</td>
        <td>42 325</td>
        <td>11</td>
        <td>25 853</td>
        <td>1 809</td>
        <td>3 639</td>
        <td>1005977651</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1004011942</td>
        <td>0</td>
        <td>0</td>
        <td>140741</td>
        <td>407399</td>
        <td>1</td>
        <td>0</td>
        <td>89296</td>
      </tr>
      <tr>
        <td>23:26:31.651, 27.02.2020</td>
        <td>1,9</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>84 054 928</td>
        <td>92 012 544</td>
        <td>86 241 152</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 642 688</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>381</td>
        <td>0,0</td>
        <td>36,0</td>
        <td>17</td>
        <td>44 726</td>
        <td>1 477</td>
        <td>9 986</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 091 463</td>
        <td>66</td>
        <td>451 079</td>
        <td>0</td>
        <td>810 259</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>336,6</td>
        <td>0,0</td>
        <td>56,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 127 062</td>
        <td>2 000 611</td>
        <td>0</td>
        <td>870,3</td>
        <td>233,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,2</td>
        <td>0,0</td>
        <td>189 887</td>
        <td>2 967</td>
        <td>166 684</td>
        <td>837,3</td>
        <td>269,6</td>
        <td>4 108</td>
        <td>3 917</td>
        <td>5 757</td>
        <td>158,4</td>
        <td>54,5</td>
        <td>181,6</td>
        <td>2,3</td>
        <td>578,3</td>
        <td>30,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 967</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,5</td>
        <td>385</td>
        <td>280</td>
        <td>80 618</td>
        <td>38,2</td>
        <td>4,5</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9963380</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>367</td>
        <td>1</td>
        <td>402</td>
        <td>5</td>
        <td>1736</td>
        <td>63</td>
        <td>45 021 312</td>
        <td>202 996</td>
        <td>83 908 656</td>
        <td>0</td>
        <td>0</td>
        <td>4 873 834</td>
        <td>6</td>
        <td>9963380</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 604 672</td>
        <td>27 692 824</td>
        <td>9 961 472</td>
        <td>5 107 336</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 510 416</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 241 152</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>236 949</td>
        <td>265 891</td>
        <td>1 034 624</td>
        <td>5 884 909</td>
        <td>1 203 800</td>
        <td>9 496 312</td>
        <td>5 841 076</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 681 728</td>
        <td>99 614 720</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 803 808</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 157 440</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 107 336</td>
        <td>76 546 048</td>
        <td>8 411 117</td>
        <td>26</td>
        <td>42 325</td>
        <td>11</td>
        <td>25 853</td>
        <td>1 809</td>
        <td>3 639</td>
        <td>1005955217</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1003238402</td>
        <td>0</td>
        <td>0</td>
        <td>39736</td>
        <td>219238</td>
        <td>1</td>
        <td>0</td>
        <td>65373</td>
      </tr>
      <tr>
        <td>23:26:32.651, 27.02.2020</td>
        <td>1,9</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>93 774 744</td>
        <td>92 012 544</td>
        <td>86 241 152</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 642 688</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>382</td>
        <td>0,0</td>
        <td>36,0</td>
        <td>17</td>
        <td>45 015</td>
        <td>1 501</td>
        <td>10 040</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 101 920</td>
        <td>66</td>
        <td>451 170</td>
        <td>0</td>
        <td>810 561</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>337,6</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 179 068</td>
        <td>2 020 764</td>
        <td>0</td>
        <td>873,1</td>
        <td>234,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>4,9</td>
        <td>0,0</td>
        <td>192 105</td>
        <td>2 969</td>
        <td>166 716</td>
        <td>841,8</td>
        <td>269,6</td>
        <td>4 150</td>
        <td>3 958</td>
        <td>5 822</td>
        <td>158,6</td>
        <td>54,6</td>
        <td>182,6</td>
        <td>2,3</td>
        <td>581,9</td>
        <td>30,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 969</td>
        <td>31,4</td>
        <td>36,1</td>
        <td>192,9</td>
        <td>389</td>
        <td>284</td>
        <td>80 622</td>
        <td>38,2</td>
        <td>4,6</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>6189687</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>1498</td>
        <td>42</td>
        <td>45 028 384</td>
        <td>202 996</td>
        <td>83 919 232</td>
        <td>0</td>
        <td>0</td>
        <td>4 874 558</td>
        <td>4</td>
        <td>6189687</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 604 672</td>
        <td>36 160 520</td>
        <td>9 961 472</td>
        <td>5 107 336</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 510 416</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 241 152</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>236 949</td>
        <td>265 891</td>
        <td>1 034 624</td>
        <td>5 884 909</td>
        <td>1 203 800</td>
        <td>9 496 312</td>
        <td>5 841 076</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 681 728</td>
        <td>99 614 720</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 803 808</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 157 440</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 107 336</td>
        <td>76 546 048</td>
        <td>8 411 117</td>
        <td>26</td>
        <td>42 325</td>
        <td>11</td>
        <td>25 853</td>
        <td>1 809</td>
        <td>3 639</td>
        <td>989140662</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>987328249</td>
        <td>0</td>
        <td>0</td>
        <td>40958</td>
        <td>243349</td>
        <td>0</td>
        <td>0</td>
        <td>70932</td>
      </tr>
      <tr>
        <td>23:26:33.652, 27.02.2020</td>
        <td>3,4</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>103 436 568</td>
        <td>92 012 544</td>
        <td>86 241 152</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>4,5</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 642 688</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>383</td>
        <td>0,0</td>
        <td>36,0</td>
        <td>17</td>
        <td>45 299</td>
        <td>1 525</td>
        <td>10 094</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 112 395</td>
        <td>66</td>
        <td>451 261</td>
        <td>0</td>
        <td>810 863</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>337,5</td>
        <td>0,0</td>
        <td>56,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 231 112</td>
        <td>2 040 947</td>
        <td>0</td>
        <td>873,7</td>
        <td>234,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>8,2</td>
        <td>0,0</td>
        <td>194 323</td>
        <td>2 971</td>
        <td>166 748</td>
        <td>849,6</td>
        <td>269,7</td>
        <td>4 192</td>
        <td>3 999</td>
        <td>5 887</td>
        <td>158,9</td>
        <td>54,6</td>
        <td>184,0</td>
        <td>2,3</td>
        <td>588,2</td>
        <td>30,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 971</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,7</td>
        <td>393</td>
        <td>288</td>
        <td>80 626</td>
        <td>38,2</td>
        <td>4,6</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>46081080</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>465</td>
        <td>0</td>
        <td>0</td>
        <td>1 407</td>
        <td>45 032 704</td>
        <td>202 996</td>
        <td>83 927 992</td>
        <td>0</td>
        <td>0</td>
        <td>4 875 965</td>
        <td>1</td>
        <td>46081080</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 604 672</td>
        <td>47 979 376</td>
        <td>9 961 472</td>
        <td>5 107 336</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 510 416</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 241 152</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>236 949</td>
        <td>265 891</td>
        <td>1 034 624</td>
        <td>5 884 909</td>
        <td>1 203 800</td>
        <td>9 496 312</td>
        <td>5 841 076</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 681 728</td>
        <td>99 614 720</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 803 808</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 157 440</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 107 336</td>
        <td>76 546 048</td>
        <td>8 411 117</td>
        <td>26</td>
        <td>42 325</td>
        <td>11</td>
        <td>25 853</td>
        <td>1 809</td>
        <td>3 639</td>
        <td>1016473154</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1014057358</td>
        <td>0</td>
        <td>0</td>
        <td>139943</td>
        <td>420993</td>
        <td>1</td>
        <td>0</td>
        <td>110593</td>
      </tr>
      <tr>
        <td>23:26:34.652, 27.02.2020</td>
        <td>3,4</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>113 743 352</td>
        <td>92 012 544</td>
        <td>86 241 152</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>3,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 642 688</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>384</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>45 590</td>
        <td>1 549</td>
        <td>10 148</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 122 864</td>
        <td>66</td>
        <td>451 352</td>
        <td>0</td>
        <td>811 165</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>338,9</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 283 160</td>
        <td>2 061 120</td>
        <td>0</td>
        <td>876,0</td>
        <td>235,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>11,0</td>
        <td>0,0</td>
        <td>196 541</td>
        <td>2 973</td>
        <td>166 780</td>
        <td>858,2</td>
        <td>269,5</td>
        <td>4 234</td>
        <td>4 040</td>
        <td>5 952</td>
        <td>159,5</td>
        <td>54,6</td>
        <td>185,8</td>
        <td>2,3</td>
        <td>596,8</td>
        <td>30,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 973</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,8</td>
        <td>397</td>
        <td>292</td>
        <td>80 630</td>
        <td>38,3</td>
        <td>4,7</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>33410466</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>275</td>
        <td>0</td>
        <td>398</td>
        <td>0</td>
        <td>0</td>
        <td>889</td>
        <td>45 036 192</td>
        <td>202 996</td>
        <td>83 935 920</td>
        <td>0</td>
        <td>0</td>
        <td>4 876 854</td>
        <td>0</td>
        <td>33410466</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 604 672</td>
        <td>57 266 544</td>
        <td>9 961 472</td>
        <td>5 107 336</td>
        <td>9 961 472</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 510 416</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 241 152</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>236 949</td>
        <td>265 891</td>
        <td>1 034 624</td>
        <td>5 884 909</td>
        <td>1 203 800</td>
        <td>9 496 312</td>
        <td>5 841 076</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>68 681 728</td>
        <td>99 614 720</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 803 808</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 157 440</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 107 336</td>
        <td>76 546 048</td>
        <td>8 411 117</td>
        <td>26</td>
        <td>42 325</td>
        <td>11</td>
        <td>25 853</td>
        <td>1 809</td>
        <td>3 639</td>
        <td>991055390</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1021578554</td>
        <td>0</td>
        <td>0</td>
        <td>164790</td>
        <td>615574</td>
        <td>1</td>
        <td>0</td>
        <td>118761</td>
      </tr>
      <tr>
        <td>23:26:35.652, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>123 597 304</td>
        <td>92 012 544</td>
        <td>86 241 152</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>4,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>66 642 688</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>385</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>45 877</td>
        <td>1 573</td>
        <td>10 202</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 133 333</td>
        <td>66</td>
        <td>451 443</td>
        <td>0</td>
        <td>811 467</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>340,6</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 335 202</td>
        <td>2 081 293</td>
        <td>0</td>
        <td>881,6</td>
        <td>236,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,9</td>
        <td>0,0</td>
        <td>198 759</td>
        <td>2 975</td>
        <td>166 812</td>
        <td>866,5</td>
        <td>269,9</td>
        <td>4 276</td>
        <td>4 081</td>
        <td>6 017</td>
        <td>159,8</td>
        <td>54,6</td>
        <td>187,0</td>
        <td>2,3</td>
        <td>602,1</td>
        <td>30,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 975</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,8</td>
        <td>402</td>
        <td>296</td>
        <td>80 634</td>
        <td>38,3</td>
        <td>4,7</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>40862998</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>835</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1 577</td>
        <td>45 041 728</td>
        <td>202 996</td>
        <td>83 950 704</td>
        <td>0</td>
        <td>0</td>
        <td>4 878 530</td>
        <td>1</td>
        <td>40862998</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>6937775304</td>
        <td>6938620759</td>
        <td>8791478</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 080 384</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>5 067 144</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 543 184</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 248 608</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>643</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>216 532</td>
        <td>257 677</td>
        <td>989 565</td>
        <td>5 803 133</td>
        <td>1 157 019</td>
        <td>9 274 192</td>
        <td>5 763 683</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 726 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 681 728</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 067 144</td>
        <td>78 118 912</td>
        <td>8 517 139</td>
        <td>20</td>
        <td>112 508</td>
        <td>7</td>
        <td>65 133</td>
        <td>786</td>
        <td>1 979</td>
        <td>999744315</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1263075322</td>
        <td>0</td>
        <td>0</td>
        <td>228054</td>
        <td>9709396</td>
        <td>1</td>
        <td>0</td>
        <td>9027841</td>
      </tr>
      <tr>
        <td>23:26:36.652, 27.02.2020</td>
        <td>3,2</td>
        <td>0,1</td>
        <td>173 539 328</td>
        <td>66 150 696</td>
        <td>92 012 544</td>
        <td>86 248 608</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>2,5</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>68 164 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>386</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>46 161</td>
        <td>1 597</td>
        <td>10 256</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>0,0</td>
        <td>14,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 143 790</td>
        <td>66</td>
        <td>451 534</td>
        <td>0</td>
        <td>811 769</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>341,5</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 387 187</td>
        <td>2 101 446</td>
        <td>0</td>
        <td>882,7</td>
        <td>237,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,1</td>
        <td>0,0</td>
        <td>200 977</td>
        <td>2 977</td>
        <td>166 844</td>
        <td>870,9</td>
        <td>270,2</td>
        <td>4 318</td>
        <td>4 122</td>
        <td>6 082</td>
        <td>160,0</td>
        <td>54,6</td>
        <td>188,0</td>
        <td>2,4</td>
        <td>604,6</td>
        <td>30,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 977</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,6</td>
        <td>406</td>
        <td>300</td>
        <td>80 638</td>
        <td>38,3</td>
        <td>4,7</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25951622</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>358</td>
        <td>0</td>
        <td>560</td>
        <td>6</td>
        <td>2347</td>
        <td>16</td>
        <td>45 060 352</td>
        <td>202 996</td>
        <td>83 982 328</td>
        <td>0</td>
        <td>0</td>
        <td>4 881 139</td>
        <td>7</td>
        <td>25951622</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 080 384</td>
        <td>8 709 832</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>5 067 144</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 543 184</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 248 608</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>216 532</td>
        <td>257 677</td>
        <td>989 565</td>
        <td>5 803 133</td>
        <td>1 157 019</td>
        <td>9 274 192</td>
        <td>5 763 683</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 726 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 681 728</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 067 144</td>
        <td>78 118 912</td>
        <td>8 517 139</td>
        <td>20</td>
        <td>112 508</td>
        <td>7</td>
        <td>65 133</td>
        <td>786</td>
        <td>1 979</td>
        <td>987332761</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>681759479</td>
        <td>0</td>
        <td>0</td>
        <td>66669</td>
        <td>250887</td>
        <td>0</td>
        <td>0</td>
        <td>69431</td>
      </tr>
      <tr>
        <td>23:26:37.653, 27.02.2020</td>
        <td>3,9</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>75 374 288</td>
        <td>92 012 544</td>
        <td>86 248 608</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>5,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 164 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>389</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>46 451</td>
        <td>1 621</td>
        <td>10 312</td>
        <td>0,0</td>
        <td>13,0</td>
        <td>0,0</td>
        <td>14,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 154 293</td>
        <td>66</td>
        <td>451 625</td>
        <td>0</td>
        <td>813 334</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>342,8</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 439 816</td>
        <td>2 121 702</td>
        <td>0</td>
        <td>887,1</td>
        <td>238,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,4</td>
        <td>0,0</td>
        <td>203 195</td>
        <td>2 979</td>
        <td>166 876</td>
        <td>876,8</td>
        <td>270,2</td>
        <td>4 360</td>
        <td>4 163</td>
        <td>6 147</td>
        <td>160,5</td>
        <td>54,7</td>
        <td>189,7</td>
        <td>2,4</td>
        <td>609,7</td>
        <td>30,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 979</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,9</td>
        <td>410</td>
        <td>304</td>
        <td>80 730</td>
        <td>38,3</td>
        <td>4,8</td>
        <td>27,8</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>52797615</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>384</td>
        <td>1</td>
        <td>451</td>
        <td>6</td>
        <td>1835</td>
        <td>23</td>
        <td>45 086 976</td>
        <td>202 996</td>
        <td>84 026 024</td>
        <td>0</td>
        <td>0</td>
        <td>4 883 662</td>
        <td>9</td>
        <td>52797615</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 080 384</td>
        <td>18 579 360</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>5 067 144</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 543 184</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 248 608</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>216 532</td>
        <td>257 677</td>
        <td>989 565</td>
        <td>5 803 133</td>
        <td>1 157 019</td>
        <td>9 274 192</td>
        <td>5 763 683</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 726 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 681 728</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 067 144</td>
        <td>78 118 912</td>
        <td>8 517 139</td>
        <td>20</td>
        <td>112 508</td>
        <td>7</td>
        <td>65 133</td>
        <td>786</td>
        <td>1 979</td>
        <td>1007621804</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1004668843</td>
        <td>0</td>
        <td>0</td>
        <td>84850</td>
        <td>342313</td>
        <td>1</td>
        <td>0</td>
        <td>99098</td>
      </tr>
      <tr>
        <td>23:26:38.653, 27.02.2020</td>
        <td>5,4</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>85 385 192</td>
        <td>92 012 544</td>
        <td>86 248 608</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>9,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 164 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>390</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>46 735</td>
        <td>1 645</td>
        <td>10 366</td>
        <td>0,0</td>
        <td>13,1</td>
        <td>0,0</td>
        <td>14,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 164 762</td>
        <td>66</td>
        <td>451 716</td>
        <td>0</td>
        <td>813 636</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>343,2</td>
        <td>0,0</td>
        <td>56,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 491 844</td>
        <td>2 141 875</td>
        <td>0</td>
        <td>889,5</td>
        <td>239,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>6,8</td>
        <td>0,0</td>
        <td>205 413</td>
        <td>2 981</td>
        <td>166 908</td>
        <td>882,9</td>
        <td>270,3</td>
        <td>4 402</td>
        <td>4 204</td>
        <td>6 212</td>
        <td>160,9</td>
        <td>54,7</td>
        <td>191,4</td>
        <td>2,4</td>
        <td>614,0</td>
        <td>30,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 981</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,9</td>
        <td>414</td>
        <td>308</td>
        <td>80 734</td>
        <td>38,4</td>
        <td>4,9</td>
        <td>27,8</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>96216187</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>454</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>2354</td>
        <td>197</td>
        <td>45 105 152</td>
        <td>202 996</td>
        <td>84 068 496</td>
        <td>0</td>
        <td>0</td>
        <td>4 888 057</td>
        <td>9</td>
        <td>96216187</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 080 384</td>
        <td>25 774 864</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>5 067 144</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 543 184</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 248 608</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>216 532</td>
        <td>257 677</td>
        <td>989 565</td>
        <td>5 803 133</td>
        <td>1 157 019</td>
        <td>9 274 192</td>
        <td>5 763 683</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 726 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 681 728</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 067 144</td>
        <td>78 118 912</td>
        <td>8 517 139</td>
        <td>20</td>
        <td>112 508</td>
        <td>7</td>
        <td>65 133</td>
        <td>786</td>
        <td>1 979</td>
        <td>969625135</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1013301081</td>
        <td>0</td>
        <td>0</td>
        <td>71135</td>
        <td>395119</td>
        <td>1</td>
        <td>0</td>
        <td>120111</td>
      </tr>
      <tr>
        <td>23:26:39.653, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>95 358 144</td>
        <td>92 012 544</td>
        <td>86 248 608</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 164 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>391</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>47 021</td>
        <td>1 669</td>
        <td>10 420</td>
        <td>0,0</td>
        <td>13,1</td>
        <td>0,0</td>
        <td>14,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 175 231</td>
        <td>66</td>
        <td>451 807</td>
        <td>0</td>
        <td>813 938</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>345,0</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 543 876</td>
        <td>2 162 048</td>
        <td>0</td>
        <td>893,3</td>
        <td>240,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>7,1</td>
        <td>0,0</td>
        <td>207 631</td>
        <td>2 983</td>
        <td>166 940</td>
        <td>887,6</td>
        <td>270,1</td>
        <td>4 444</td>
        <td>4 245</td>
        <td>6 277</td>
        <td>161,2</td>
        <td>54,7</td>
        <td>193,0</td>
        <td>2,4</td>
        <td>618,9</td>
        <td>30,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 983</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,0</td>
        <td>419</td>
        <td>312</td>
        <td>80 738</td>
        <td>38,4</td>
        <td>4,9</td>
        <td>27,8</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5535659</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>431</td>
        <td>1</td>
        <td>525</td>
        <td>600</td>
        <td>45 116 896</td>
        <td>202 996</td>
        <td>84 086 568</td>
        <td>0</td>
        <td>0</td>
        <td>4 888 734</td>
        <td>3</td>
        <td>5535659</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 080 384</td>
        <td>38 674 400</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>5 067 144</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 543 184</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 248 608</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>216 532</td>
        <td>257 677</td>
        <td>989 565</td>
        <td>5 803 133</td>
        <td>1 157 019</td>
        <td>9 274 192</td>
        <td>5 763 683</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 726 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 681 728</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 067 144</td>
        <td>78 118 912</td>
        <td>8 517 139</td>
        <td>20</td>
        <td>112 508</td>
        <td>7</td>
        <td>65 133</td>
        <td>786</td>
        <td>1 979</td>
        <td>1029853863</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>978088988</td>
        <td>0</td>
        <td>0</td>
        <td>69939</td>
        <td>454437</td>
        <td>0</td>
        <td>0</td>
        <td>162684</td>
      </tr>
      <tr>
        <td>23:26:40.653, 27.02.2020</td>
        <td>2,9</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>104 996 144</td>
        <td>92 012 544</td>
        <td>86 248 608</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,1</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 164 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>392</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>47 309</td>
        <td>1 693</td>
        <td>10 474</td>
        <td>0,0</td>
        <td>13,1</td>
        <td>0,0</td>
        <td>14,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 185 700</td>
        <td>66</td>
        <td>451 898</td>
        <td>0</td>
        <td>814 240</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>346,3</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 595 908</td>
        <td>2 182 221</td>
        <td>0</td>
        <td>895,9</td>
        <td>241,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,0</td>
        <td>0,0</td>
        <td>209 849</td>
        <td>2 985</td>
        <td>166 972</td>
        <td>896,8</td>
        <td>270,7</td>
        <td>4 486</td>
        <td>4 286</td>
        <td>6 342</td>
        <td>161,4</td>
        <td>54,7</td>
        <td>194,5</td>
        <td>2,4</td>
        <td>622,0</td>
        <td>30,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 985</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>192,8</td>
        <td>423</td>
        <td>316</td>
        <td>80 742</td>
        <td>38,4</td>
        <td>5,0</td>
        <td>27,7</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1526661</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>473</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>469</td>
        <td>176</td>
        <td>45 121 568</td>
        <td>202 996</td>
        <td>84 092 824</td>
        <td>0</td>
        <td>0</td>
        <td>4 888 910</td>
        <td>1</td>
        <td>1526661</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 080 384</td>
        <td>45 385 816</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>5 067 144</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 543 184</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 248 608</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>216 532</td>
        <td>257 677</td>
        <td>989 565</td>
        <td>5 803 133</td>
        <td>1 157 019</td>
        <td>9 274 192</td>
        <td>5 763 683</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 726 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 681 728</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 067 144</td>
        <td>78 118 912</td>
        <td>8 517 139</td>
        <td>20</td>
        <td>112 508</td>
        <td>7</td>
        <td>65 133</td>
        <td>786</td>
        <td>1 979</td>
        <td>973835925</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>4</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1022408242</td>
        <td>0</td>
        <td>0</td>
        <td>123229</td>
        <td>422476</td>
        <td>1</td>
        <td>0</td>
        <td>109632</td>
      </tr>
      <tr>
        <td>23:26:41.654, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>115 173 824</td>
        <td>92 012 544</td>
        <td>86 248 608</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 164 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>393</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>47 593</td>
        <td>1 717</td>
        <td>10 528</td>
        <td>0,0</td>
        <td>13,1</td>
        <td>0,0</td>
        <td>14,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 196 169</td>
        <td>66</td>
        <td>451 989</td>
        <td>0</td>
        <td>814 542</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>347,1</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 647 941</td>
        <td>2 202 394</td>
        <td>0</td>
        <td>899,5</td>
        <td>242,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,5</td>
        <td>0,0</td>
        <td>212 068</td>
        <td>2 987</td>
        <td>167 004</td>
        <td>899,7</td>
        <td>270,5</td>
        <td>4 528</td>
        <td>4 327</td>
        <td>6 407</td>
        <td>161,9</td>
        <td>54,8</td>
        <td>195,9</td>
        <td>2,4</td>
        <td>626,2</td>
        <td>30,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 987</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,1</td>
        <td>427</td>
        <td>320</td>
        <td>80 746</td>
        <td>38,4</td>
        <td>5,0</td>
        <td>27,8</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>7798034</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>565</td>
        <td>0</td>
        <td>574</td>
        <td>14</td>
        <td>45 122 560</td>
        <td>202 996</td>
        <td>84 095 960</td>
        <td>0</td>
        <td>0</td>
        <td>4 889 155</td>
        <td>1</td>
        <td>7798034</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>68 157 440</td>
        <td>88 080 384</td>
        <td>58 805 488</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>9 961 472</td>
        <td>5 067 144</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 543 184</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 248 608</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>216 532</td>
        <td>257 677</td>
        <td>989 565</td>
        <td>5 803 133</td>
        <td>1 157 019</td>
        <td>9 274 192</td>
        <td>5 763 683</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 206 016</td>
        <td>100 139 008</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 726 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>68 681 728</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 067 144</td>
        <td>78 118 912</td>
        <td>8 517 139</td>
        <td>20</td>
        <td>112 508</td>
        <td>7</td>
        <td>65 133</td>
        <td>786</td>
        <td>1 979</td>
        <td>1033432599</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>9</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>981362032</td>
        <td>0</td>
        <td>0</td>
        <td>279699</td>
        <td>637674</td>
        <td>0</td>
        <td>0</td>
        <td>147510</td>
      </tr>
      <tr>
        <td>23:26:42.654, 27.02.2020</td>
        <td>13,2</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>124 443 896</td>
        <td>92 012 544</td>
        <td>86 248 608</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>40,1</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 164 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>394</td>
        <td>0,0</td>
        <td>36,1</td>
        <td>17</td>
        <td>47 877</td>
        <td>1 741</td>
        <td>10 582</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 206 638</td>
        <td>66</td>
        <td>452 080</td>
        <td>0</td>
        <td>814 844</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>349,1</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 699 969</td>
        <td>2 222 567</td>
        <td>0</td>
        <td>902,7</td>
        <td>243,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>7,9</td>
        <td>0,0</td>
        <td>214 286</td>
        <td>2 989</td>
        <td>167 036</td>
        <td>906,8</td>
        <td>270,7</td>
        <td>4 570</td>
        <td>4 368</td>
        <td>6 472</td>
        <td>162,2</td>
        <td>54,8</td>
        <td>197,7</td>
        <td>2,5</td>
        <td>631,5</td>
        <td>30,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 989</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,1</td>
        <td>431</td>
        <td>324</td>
        <td>80 750</td>
        <td>38,5</td>
        <td>5,1</td>
        <td>27,8</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>405358899</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>368</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>410</td>
        <td>11</td>
        <td>45 159 616</td>
        <td>202 996</td>
        <td>84 226 472</td>
        <td>0</td>
        <td>0</td>
        <td>4 896 924</td>
        <td>2</td>
        <td>405358899</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>7078963914</td>
        <td>7077593184</td>
        <td>7536390</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 604 672</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 575 952</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 258 048</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>500</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>198 158</td>
        <td>248 446</td>
        <td>943 498</td>
        <td>5 752 472</td>
        <td>1 086 912</td>
        <td>9 013 210</td>
        <td>5 716 967</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 730 304</td>
        <td>100 663 296</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 679 680</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>77 594 624</td>
        <td>8 516 938</td>
        <td>15</td>
        <td>45 351</td>
        <td>7</td>
        <td>22 112</td>
        <td>412</td>
        <td>1 853</td>
        <td>962607613</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>15</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1310950965</td>
        <td>0</td>
        <td>0</td>
        <td>1135277</td>
        <td>9546588</td>
        <td>2</td>
        <td>0</td>
        <td>7876233</td>
      </tr>
      <tr>
        <td>23:26:43.654, 27.02.2020</td>
        <td>3,7</td>
        <td>0,1</td>
        <td>174 063 616</td>
        <td>67 221 928</td>
        <td>92 012 544</td>
        <td>86 258 048</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>4,0</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>67 895 296</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>395</td>
        <td>0,0</td>
        <td>36,2</td>
        <td>17</td>
        <td>48 165</td>
        <td>1 765</td>
        <td>10 636</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 217 101</td>
        <td>66</td>
        <td>452 170</td>
        <td>0</td>
        <td>815 145</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>350,5</td>
        <td>0,0</td>
        <td>56,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 751 869</td>
        <td>2 242 730</td>
        <td>0</td>
        <td>907,1</td>
        <td>245,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,3</td>
        <td>0,0</td>
        <td>216 484</td>
        <td>2 991</td>
        <td>167 066</td>
        <td>909,7</td>
        <td>270,7</td>
        <td>4 598</td>
        <td>4 395</td>
        <td>6 516</td>
        <td>162,2</td>
        <td>54,9</td>
        <td>198,7</td>
        <td>2,5</td>
        <td>635,3</td>
        <td>30,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 991</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,1</td>
        <td>436</td>
        <td>328</td>
        <td>80 754</td>
        <td>38,5</td>
        <td>5,1</td>
        <td>27,9</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>39581971</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>428</td>
        <td>0</td>
        <td>0</td>
        <td>184</td>
        <td>45 163 104</td>
        <td>202 996</td>
        <td>84 232 520</td>
        <td>0</td>
        <td>0</td>
        <td>4 897 795</td>
        <td>2</td>
        <td>39581971</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 604 672</td>
        <td>7 349 456</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 575 952</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 258 048</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>198 158</td>
        <td>248 446</td>
        <td>943 498</td>
        <td>5 752 472</td>
        <td>1 086 912</td>
        <td>9 013 210</td>
        <td>5 716 967</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 730 304</td>
        <td>100 663 296</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 679 680</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>77 594 624</td>
        <td>8 516 938</td>
        <td>15</td>
        <td>45 351</td>
        <td>7</td>
        <td>22 112</td>
        <td>412</td>
        <td>1 853</td>
        <td>1010119967</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>700018585</td>
        <td>0</td>
        <td>0</td>
        <td>57063</td>
        <td>363465</td>
        <td>1</td>
        <td>0</td>
        <td>107169</td>
      </tr>
      <tr>
        <td>23:26:44.654, 27.02.2020</td>
        <td>4,2</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>76 706 576</td>
        <td>92 012 544</td>
        <td>86 258 048</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>7,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>67 895 296</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>398</td>
        <td>0,0</td>
        <td>36,2</td>
        <td>17</td>
        <td>48 453</td>
        <td>1 789</td>
        <td>10 692</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 227 604</td>
        <td>66</td>
        <td>452 261</td>
        <td>0</td>
        <td>816 710</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>351,7</td>
        <td>0,0</td>
        <td>56,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 804 499</td>
        <td>2 262 986</td>
        <td>0</td>
        <td>909,8</td>
        <td>246,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,0</td>
        <td>0,0</td>
        <td>218 702</td>
        <td>2 993</td>
        <td>167 098</td>
        <td>918,9</td>
        <td>271,2</td>
        <td>4 640</td>
        <td>4 436</td>
        <td>6 581</td>
        <td>162,6</td>
        <td>54,8</td>
        <td>200,2</td>
        <td>2,5</td>
        <td>639,2</td>
        <td>30,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 993</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,0</td>
        <td>440</td>
        <td>332</td>
        <td>80 846</td>
        <td>38,5</td>
        <td>5,2</td>
        <td>27,9</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>77128626</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>596</td>
        <td>1</td>
        <td>1000</td>
        <td>4</td>
        <td>23971</td>
        <td>22</td>
        <td>45 199 136</td>
        <td>205 044</td>
        <td>84 296 312</td>
        <td>1</td>
        <td>68025728</td>
        <td>4 898 285</td>
        <td>4</td>
        <td>9102897</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 604 672</td>
        <td>21 184 840</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 575 952</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 258 048</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>198 158</td>
        <td>248 446</td>
        <td>943 498</td>
        <td>5 752 472</td>
        <td>1 086 912</td>
        <td>9 013 210</td>
        <td>5 716 967</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 730 304</td>
        <td>100 663 296</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 679 680</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>77 594 624</td>
        <td>8 516 938</td>
        <td>15</td>
        <td>45 351</td>
        <td>7</td>
        <td>22 112</td>
        <td>412</td>
        <td>1 853</td>
        <td>1032763805</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>997196539</td>
        <td>0</td>
        <td>0</td>
        <td>180311</td>
        <td>590958</td>
        <td>1</td>
        <td>0</td>
        <td>110978</td>
      </tr>
      <tr>
        <td>23:26:45.654, 27.02.2020</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>86 645 592</td>
        <td>92 012 544</td>
        <td>86 258 048</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>67 895 296</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>399</td>
        <td>0,0</td>
        <td>36,2</td>
        <td>17</td>
        <td>48 737</td>
        <td>1 813</td>
        <td>10 746</td>
        <td>0,0</td>
        <td>13,2</td>
        <td>0,0</td>
        <td>14,1</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 238 073</td>
        <td>66</td>
        <td>452 352</td>
        <td>0</td>
        <td>817 012</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>352,7</td>
        <td>0,0</td>
        <td>56,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 856 528</td>
        <td>2 283 159</td>
        <td>0</td>
        <td>913,5</td>
        <td>247,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,6</td>
        <td>0,0</td>
        <td>220 920</td>
        <td>2 995</td>
        <td>167 130</td>
        <td>922,9</td>
        <td>271,0</td>
        <td>4 682</td>
        <td>4 477</td>
        <td>6 646</td>
        <td>163,2</td>
        <td>55,0</td>
        <td>201,8</td>
        <td>2,5</td>
        <td>643,5</td>
        <td>30,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 995</td>
        <td>31,4</td>
        <td>36,1</td>
        <td>193,4</td>
        <td>444</td>
        <td>336</td>
        <td>80 850</td>
        <td>38,6</td>
        <td>5,2</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>7267818</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1582</td>
        <td>54</td>
        <td>45 203 584</td>
        <td>205 044</td>
        <td>84 303 352</td>
        <td>0</td>
        <td>0</td>
        <td>4 898 590</td>
        <td>5</td>
        <td>7267818</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 604 672</td>
        <td>26 773 120</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 575 952</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 258 048</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>198 158</td>
        <td>248 446</td>
        <td>943 498</td>
        <td>5 752 472</td>
        <td>1 086 912</td>
        <td>9 013 210</td>
        <td>5 716 967</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 730 304</td>
        <td>100 663 296</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 679 680</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>77 594 624</td>
        <td>8 516 938</td>
        <td>15</td>
        <td>45 351</td>
        <td>7</td>
        <td>22 112</td>
        <td>412</td>
        <td>1 853</td>
        <td>958279811</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>988539431</td>
        <td>0</td>
        <td>0</td>
        <td>128926</td>
        <td>497604</td>
        <td>1</td>
        <td>0</td>
        <td>144095</td>
      </tr>
      <tr>
        <td>23:26:46.655, 27.02.2020</td>
        <td>3,6</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>96 305 712</td>
        <td>92 012 544</td>
        <td>86 258 048</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>1,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>67 895 296</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>400</td>
        <td>0,0</td>
        <td>36,2</td>
        <td>17</td>
        <td>49 023</td>
        <td>1 837</td>
        <td>10 800</td>
        <td>0,0</td>
        <td>13,3</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 248 542</td>
        <td>66</td>
        <td>452 443</td>
        <td>0</td>
        <td>817 314</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>354,3</td>
        <td>0,0</td>
        <td>56,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 908 555</td>
        <td>2 303 332</td>
        <td>0</td>
        <td>916,4</td>
        <td>248,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>8,0</td>
        <td>0,0</td>
        <td>223 138</td>
        <td>2 997</td>
        <td>167 162</td>
        <td>930,2</td>
        <td>271,0</td>
        <td>4 724</td>
        <td>4 518</td>
        <td>6 711</td>
        <td>163,4</td>
        <td>54,9</td>
        <td>203,8</td>
        <td>2,5</td>
        <td>648,8</td>
        <td>30,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 997</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,3</td>
        <td>448</td>
        <td>340</td>
        <td>80 854</td>
        <td>38,6</td>
        <td>5,3</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>14940791</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>712</td>
        <td>2</td>
        <td>1060</td>
        <td>10</td>
        <td>45 241 152</td>
        <td>206 165</td>
        <td>84 365 352</td>
        <td>0</td>
        <td>7529224</td>
        <td>4 899 495</td>
        <td>2</td>
        <td>7411567</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 604 672</td>
        <td>36 671 552</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 575 952</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 258 048</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>198 158</td>
        <td>248 446</td>
        <td>943 498</td>
        <td>5 752 472</td>
        <td>1 086 912</td>
        <td>9 013 210</td>
        <td>5 716 967</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 730 304</td>
        <td>100 663 296</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 679 680</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>77 594 624</td>
        <td>8 516 938</td>
        <td>15</td>
        <td>45 351</td>
        <td>7</td>
        <td>22 112</td>
        <td>412</td>
        <td>1 853</td>
        <td>996013973</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>991659415</td>
        <td>0</td>
        <td>0</td>
        <td>108260</td>
        <td>312086</td>
        <td>0</td>
        <td>0</td>
        <td>76747</td>
      </tr>
      <tr>
        <td>23:26:47.655, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>106 071 144</td>
        <td>92 012 544</td>
        <td>86 258 048</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>1,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>67 895 296</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>401</td>
        <td>0,0</td>
        <td>36,2</td>
        <td>17</td>
        <td>49 307</td>
        <td>1 861</td>
        <td>10 854</td>
        <td>0,0</td>
        <td>13,3</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 259 011</td>
        <td>66</td>
        <td>452 534</td>
        <td>0</td>
        <td>817 616</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>355,6</td>
        <td>0,0</td>
        <td>56,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>6 960 578</td>
        <td>2 323 505</td>
        <td>0</td>
        <td>920,8</td>
        <td>249,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,3</td>
        <td>0,0</td>
        <td>225 356</td>
        <td>2 999</td>
        <td>167 194</td>
        <td>936,0</td>
        <td>271,0</td>
        <td>4 766</td>
        <td>4 559</td>
        <td>6 776</td>
        <td>163,8</td>
        <td>55,0</td>
        <td>205,4</td>
        <td>2,5</td>
        <td>653,0</td>
        <td>30,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>3 999</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,3</td>
        <td>453</td>
        <td>344</td>
        <td>80 858</td>
        <td>38,6</td>
        <td>5,3</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10796647</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>427</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>836</td>
        <td>124</td>
        <td>45 259 808</td>
        <td>206 165</td>
        <td>84 399 912</td>
        <td>0</td>
        <td>0</td>
        <td>4 900 740</td>
        <td>2</td>
        <td>10796647</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 604 672</td>
        <td>46 675 408</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 575 952</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 258 048</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>198 158</td>
        <td>248 446</td>
        <td>943 498</td>
        <td>5 752 472</td>
        <td>1 086 912</td>
        <td>9 013 210</td>
        <td>5 716 967</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 730 304</td>
        <td>100 663 296</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 679 680</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>77 594 624</td>
        <td>8 516 938</td>
        <td>15</td>
        <td>45 351</td>
        <td>7</td>
        <td>22 112</td>
        <td>412</td>
        <td>1 853</td>
        <td>1008695932</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1006008720</td>
        <td>0</td>
        <td>0</td>
        <td>68566</td>
        <td>312019</td>
        <td>1</td>
        <td>0</td>
        <td>91897</td>
      </tr>
      <tr>
        <td>23:26:48.655, 27.02.2020</td>
        <td>2,9</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>115 715 360</td>
        <td>92 012 544</td>
        <td>86 258 048</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>1,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>67 895 296</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>402</td>
        <td>0,0</td>
        <td>36,2</td>
        <td>17</td>
        <td>49 590</td>
        <td>1 885</td>
        <td>10 908</td>
        <td>0,0</td>
        <td>13,3</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 269 486</td>
        <td>66</td>
        <td>452 624</td>
        <td>0</td>
        <td>817 917</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>356,7</td>
        <td>0,0</td>
        <td>56,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 012 506</td>
        <td>2 343 688</td>
        <td>0</td>
        <td>923,8</td>
        <td>250,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,0</td>
        <td>0,0</td>
        <td>227 554</td>
        <td>3 001</td>
        <td>167 224</td>
        <td>939,7</td>
        <td>270,7</td>
        <td>4 794</td>
        <td>4 586</td>
        <td>6 820</td>
        <td>163,6</td>
        <td>54,9</td>
        <td>206,1</td>
        <td>2,5</td>
        <td>657,1</td>
        <td>30,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 001</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,2</td>
        <td>457</td>
        <td>348</td>
        <td>80 862</td>
        <td>38,7</td>
        <td>5,3</td>
        <td>27,9</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9985739</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>452</td>
        <td>2</td>
        <td>830</td>
        <td>48</td>
        <td>45 274 848</td>
        <td>206 165</td>
        <td>84 425 096</td>
        <td>0</td>
        <td>0</td>
        <td>4 901 618</td>
        <td>4</td>
        <td>9985739</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 604 672</td>
        <td>56 568 784</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>9 437 184</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 575 952</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 258 048</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>198 158</td>
        <td>248 446</td>
        <td>943 498</td>
        <td>5 752 472</td>
        <td>1 086 912</td>
        <td>9 013 210</td>
        <td>5 716 967</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>69 730 304</td>
        <td>100 663 296</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 679 680</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 206 016</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>77 594 624</td>
        <td>8 516 938</td>
        <td>15</td>
        <td>45 351</td>
        <td>7</td>
        <td>22 112</td>
        <td>412</td>
        <td>1 853</td>
        <td>1001445090</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>999024071</td>
        <td>0</td>
        <td>0</td>
        <td>138901</td>
        <td>387138</td>
        <td>0</td>
        <td>0</td>
        <td>91447</td>
      </tr>
      <tr>
        <td>23:26:49.656, 27.02.2020</td>
        <td>3,9</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>125 489 328</td>
        <td>92 012 544</td>
        <td>86 258 048</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>2,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>67 895 296</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>403</td>
        <td>0,0</td>
        <td>36,2</td>
        <td>17</td>
        <td>49 876</td>
        <td>1 909</td>
        <td>10 962</td>
        <td>0,0</td>
        <td>13,3</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 279 955</td>
        <td>66</td>
        <td>452 715</td>
        <td>0</td>
        <td>818 219</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>358,4</td>
        <td>0,0</td>
        <td>56,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 064 529</td>
        <td>2 363 861</td>
        <td>0</td>
        <td>926,9</td>
        <td>252,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,6</td>
        <td>0,0</td>
        <td>229 772</td>
        <td>3 003</td>
        <td>167 256</td>
        <td>949,7</td>
        <td>271,3</td>
        <td>4 836</td>
        <td>4 627</td>
        <td>6 885</td>
        <td>164,2</td>
        <td>55,0</td>
        <td>207,8</td>
        <td>2,6</td>
        <td>662,3</td>
        <td>30,3</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 003</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,4</td>
        <td>461</td>
        <td>352</td>
        <td>80 866</td>
        <td>38,7</td>
        <td>5,4</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>28627995</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>462</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1891</td>
        <td>19</td>
        <td>45 314 464</td>
        <td>206 165</td>
        <td>84 492 640</td>
        <td>0</td>
        <td>0</td>
        <td>4 903 691</td>
        <td>5</td>
        <td>28627995</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>6908699039</td>
        <td>6912287013</td>
        <td>10924404</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 080 384</td>
        <td>922 608</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 633 296</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 271 008</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>371</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>184 078</td>
        <td>236 273</td>
        <td>892 900</td>
        <td>5 706 877</td>
        <td>1 019 257</td>
        <td>8 764 649</td>
        <td>5 674 922</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 254 592</td>
        <td>101 187 584</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 637 632</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 730 304</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>78 643 200</td>
        <td>8 659 764</td>
        <td>331</td>
        <td>53 251</td>
        <td>313</td>
        <td>20 826</td>
        <td>1 673</td>
        <td>2 454</td>
        <td>1036049285</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>14</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1294770237</td>
        <td>0</td>
        <td>0</td>
        <td>243997</td>
        <td>12038598</td>
        <td>1</td>
        <td>0</td>
        <td>11240067</td>
      </tr>
      <tr>
        <td>23:26:50.655, 27.02.2020</td>
        <td>4,4</td>
        <td>0,2</td>
        <td>173 539 328</td>
        <td>66 971 424</td>
        <td>92 012 544</td>
        <td>86 271 008</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>1,3</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>69 148 672</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>404</td>
        <td>0,0</td>
        <td>36,3</td>
        <td>17</td>
        <td>50 160</td>
        <td>1 933</td>
        <td>11 016</td>
        <td>0,0</td>
        <td>13,3</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 290 424</td>
        <td>66</td>
        <td>452 806</td>
        <td>0</td>
        <td>818 521</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>360,0</td>
        <td>0,0</td>
        <td>56,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 116 558</td>
        <td>2 384 034</td>
        <td>0</td>
        <td>930,8</td>
        <td>253,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>6,8</td>
        <td>0,0</td>
        <td>231 990</td>
        <td>3 005</td>
        <td>167 288</td>
        <td>953,5</td>
        <td>271,4</td>
        <td>4 878</td>
        <td>4 668</td>
        <td>6 950</td>
        <td>164,5</td>
        <td>55,1</td>
        <td>209,2</td>
        <td>2,6</td>
        <td>666,7</td>
        <td>30,4</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 005</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,4</td>
        <td>465</td>
        <td>356</td>
        <td>80 870</td>
        <td>38,7</td>
        <td>5,4</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>13223115</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>523</td>
        <td>1</td>
        <td>407</td>
        <td>6</td>
        <td>2183</td>
        <td>23</td>
        <td>45 332 416</td>
        <td>206 165</td>
        <td>84 520 424</td>
        <td>0</td>
        <td>0</td>
        <td>4 904 626</td>
        <td>7</td>
        <td>13223115</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 080 384</td>
        <td>7 933 408</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 633 296</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 271 008</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>184 078</td>
        <td>236 273</td>
        <td>892 900</td>
        <td>5 706 877</td>
        <td>1 019 257</td>
        <td>8 764 649</td>
        <td>5 674 922</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 254 592</td>
        <td>101 187 584</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 637 632</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 730 304</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>78 643 200</td>
        <td>8 659 764</td>
        <td>331</td>
        <td>53 251</td>
        <td>313</td>
        <td>20 826</td>
        <td>1 673</td>
        <td>2 454</td>
        <td>962046770</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>14</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>679737530</td>
        <td>0</td>
        <td>0</td>
        <td>160329</td>
        <td>525728</td>
        <td>1</td>
        <td>0</td>
        <td>141430</td>
      </tr>
      <tr>
        <td>23:26:51.656, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>76 794 096</td>
        <td>92 012 544</td>
        <td>86 271 008</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 148 672</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>407</td>
        <td>0,0</td>
        <td>36,3</td>
        <td>17</td>
        <td>50 449</td>
        <td>1 957</td>
        <td>11 072</td>
        <td>0,0</td>
        <td>13,3</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 300 921</td>
        <td>66</td>
        <td>452 896</td>
        <td>0</td>
        <td>820 085</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>361,7</td>
        <td>0,0</td>
        <td>56,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 169 069</td>
        <td>2 404 280</td>
        <td>0</td>
        <td>935,4</td>
        <td>254,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,1</td>
        <td>0,0</td>
        <td>234 189</td>
        <td>3 007</td>
        <td>167 318</td>
        <td>956,3</td>
        <td>271,2</td>
        <td>4 906</td>
        <td>4 695</td>
        <td>6 994</td>
        <td>164,5</td>
        <td>55,1</td>
        <td>210,3</td>
        <td>2,6</td>
        <td>670,2</td>
        <td>30,4</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 007</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,3</td>
        <td>470</td>
        <td>360</td>
        <td>80 962</td>
        <td>38,8</td>
        <td>5,5</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11736927</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>2051</td>
        <td>59</td>
        <td>45 347 808</td>
        <td>206 165</td>
        <td>84 545 600</td>
        <td>0</td>
        <td>0</td>
        <td>4 905 047</td>
        <td>6</td>
        <td>11736927</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 080 384</td>
        <td>18 358 024</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 633 296</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 271 008</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>184 078</td>
        <td>236 273</td>
        <td>892 900</td>
        <td>5 706 877</td>
        <td>1 019 257</td>
        <td>8 764 649</td>
        <td>5 674 922</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 254 592</td>
        <td>101 187 584</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 637 632</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 730 304</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>78 643 200</td>
        <td>8 659 764</td>
        <td>331</td>
        <td>53 251</td>
        <td>313</td>
        <td>20 826</td>
        <td>1 673</td>
        <td>2 454</td>
        <td>1005928021</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1002173212</td>
        <td>0</td>
        <td>0</td>
        <td>52938</td>
        <td>385170</td>
        <td>1</td>
        <td>0</td>
        <td>122140</td>
      </tr>
      <tr>
        <td>23:26:52.656, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>86 530 896</td>
        <td>92 012 544</td>
        <td>86 271 008</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>0,6</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 148 672</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>408</td>
        <td>0,0</td>
        <td>36,3</td>
        <td>17</td>
        <td>50 735</td>
        <td>1 981</td>
        <td>11 126</td>
        <td>0,0</td>
        <td>13,4</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 311 396</td>
        <td>66</td>
        <td>452 987</td>
        <td>0</td>
        <td>820 387</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>363,1</td>
        <td>0,0</td>
        <td>56,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 221 112</td>
        <td>2 424 463</td>
        <td>0</td>
        <td>938,8</td>
        <td>256,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,0</td>
        <td>0,0</td>
        <td>236 407</td>
        <td>3 009</td>
        <td>167 350</td>
        <td>965,8</td>
        <td>271,7</td>
        <td>4 948</td>
        <td>4 736</td>
        <td>7 059</td>
        <td>164,7</td>
        <td>55,1</td>
        <td>211,6</td>
        <td>2,6</td>
        <td>674,5</td>
        <td>30,4</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 009</td>
        <td>31,4</td>
        <td>36,1</td>
        <td>193,7</td>
        <td>474</td>
        <td>364</td>
        <td>80 966</td>
        <td>38,8</td>
        <td>5,5</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3333272</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>506</td>
        <td>1</td>
        <td>496</td>
        <td>1</td>
        <td>289</td>
        <td>52</td>
        <td>45 348 672</td>
        <td>206 165</td>
        <td>84 547 296</td>
        <td>0</td>
        <td>0</td>
        <td>4 905 138</td>
        <td>3</td>
        <td>3333272</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 080 384</td>
        <td>28 138 640</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 633 296</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 271 008</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>184 078</td>
        <td>236 273</td>
        <td>892 900</td>
        <td>5 706 877</td>
        <td>1 019 257</td>
        <td>8 764 649</td>
        <td>5 674 922</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 254 592</td>
        <td>101 187 584</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 637 632</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 730 304</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>78 643 200</td>
        <td>8 659 764</td>
        <td>331</td>
        <td>53 251</td>
        <td>313</td>
        <td>20 826</td>
        <td>1 673</td>
        <td>2 454</td>
        <td>1007624546</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1004920074</td>
        <td>0</td>
        <td>0</td>
        <td>51778</td>
        <td>333543</td>
        <td>1</td>
        <td>0</td>
        <td>111823</td>
      </tr>
      <tr>
        <td>23:26:53.657, 27.02.2020</td>
        <td>2,9</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>96 123 896</td>
        <td>92 012 544</td>
        <td>86 271 008</td>
        <td>12 267</td>
        <td>0</td>
        <td>47</td>
        <td>37</td>
        <td>1,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 148 672</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>409</td>
        <td>0,0</td>
        <td>36,3</td>
        <td>17</td>
        <td>51 019</td>
        <td>2 005</td>
        <td>11 180</td>
        <td>0,0</td>
        <td>13,4</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 321 871</td>
        <td>66</td>
        <td>453 078</td>
        <td>0</td>
        <td>820 689</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>364,8</td>
        <td>0,0</td>
        <td>56,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 273 155</td>
        <td>2 444 646</td>
        <td>0</td>
        <td>942,2</td>
        <td>257,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,5</td>
        <td>0,0</td>
        <td>238 625</td>
        <td>3 011</td>
        <td>167 382</td>
        <td>969,7</td>
        <td>271,5</td>
        <td>4 990</td>
        <td>4 777</td>
        <td>7 124</td>
        <td>165,0</td>
        <td>55,1</td>
        <td>212,9</td>
        <td>2,6</td>
        <td>679,1</td>
        <td>30,4</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 011</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,6</td>
        <td>478</td>
        <td>368</td>
        <td>80 970</td>
        <td>38,8</td>
        <td>5,6</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>21487278</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>723</td>
        <td>2</td>
        <td>1397</td>
        <td>55</td>
        <td>45 363 584</td>
        <td>206 710</td>
        <td>84 571 600</td>
        <td>0</td>
        <td>6047334</td>
        <td>4 905 849</td>
        <td>3</td>
        <td>15439943</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 080 384</td>
        <td>37 731 680</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 633 296</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 271 008</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>184 078</td>
        <td>236 273</td>
        <td>892 900</td>
        <td>5 706 877</td>
        <td>1 019 257</td>
        <td>8 764 649</td>
        <td>5 674 922</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 254 592</td>
        <td>101 187 584</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 637 632</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 730 304</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>78 643 200</td>
        <td>8 659 764</td>
        <td>331</td>
        <td>53 251</td>
        <td>313</td>
        <td>20 826</td>
        <td>1 673</td>
        <td>2 454</td>
        <td>993680596</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>991198306</td>
        <td>0</td>
        <td>0</td>
        <td>169726</td>
        <td>521383</td>
        <td>0</td>
        <td>0</td>
        <td>122602</td>
      </tr>
      <tr>
        <td>23:26:54.657, 27.02.2020</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>106 111 992</td>
        <td>92 012 544</td>
        <td>86 271 008</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>1,1</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 148 672</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>410</td>
        <td>0,0</td>
        <td>36,3</td>
        <td>17</td>
        <td>51 302</td>
        <td>2 029</td>
        <td>11 234</td>
        <td>0,0</td>
        <td>13,4</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 332 340</td>
        <td>66</td>
        <td>453 168</td>
        <td>0</td>
        <td>820 990</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>366,7</td>
        <td>0,0</td>
        <td>57,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 325 067</td>
        <td>2 464 819</td>
        <td>0</td>
        <td>946,8</td>
        <td>259,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>6,4</td>
        <td>0,0</td>
        <td>240 823</td>
        <td>3 013</td>
        <td>167 412</td>
        <td>973,5</td>
        <td>271,2</td>
        <td>5 018</td>
        <td>4 804</td>
        <td>7 168</td>
        <td>165,0</td>
        <td>55,2</td>
        <td>214,0</td>
        <td>2,6</td>
        <td>683,7</td>
        <td>30,4</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 013</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,6</td>
        <td>482</td>
        <td>372</td>
        <td>80 974</td>
        <td>38,9</td>
        <td>5,6</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4902632</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>1211</td>
        <td>4</td>
        <td>1962</td>
        <td>12</td>
        <td>45 366 528</td>
        <td>206 710</td>
        <td>84 576 912</td>
        <td>0</td>
        <td>0</td>
        <td>4 906 108</td>
        <td>5</td>
        <td>4902632</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 080 384</td>
        <td>47 970 360</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 633 296</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 271 008</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>184 078</td>
        <td>236 273</td>
        <td>892 900</td>
        <td>5 706 877</td>
        <td>1 019 257</td>
        <td>8 764 649</td>
        <td>5 674 922</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 254 592</td>
        <td>101 187 584</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 637 632</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 730 304</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>78 643 200</td>
        <td>8 659 764</td>
        <td>331</td>
        <td>53 251</td>
        <td>313</td>
        <td>20 826</td>
        <td>1 673</td>
        <td>2 454</td>
        <td>1002684945</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>14</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1024736353</td>
        <td>0</td>
        <td>0</td>
        <td>422463</td>
        <td>1066008</td>
        <td>2</td>
        <td>0</td>
        <td>175605</td>
      </tr>
      <tr>
        <td>23:26:55.657, 27.02.2020</td>
        <td>6,9</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>115 770 008</td>
        <td>92 012 544</td>
        <td>86 271 008</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>16,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 148 672</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>411</td>
        <td>0,0</td>
        <td>36,3</td>
        <td>17</td>
        <td>51 588</td>
        <td>2 053</td>
        <td>11 288</td>
        <td>0,0</td>
        <td>13,4</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 342 809</td>
        <td>66</td>
        <td>453 259</td>
        <td>0</td>
        <td>821 294</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>368,0</td>
        <td>0,0</td>
        <td>57,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 377 097</td>
        <td>2 484 992</td>
        <td>0</td>
        <td>948,6</td>
        <td>259,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,8</td>
        <td>0,0</td>
        <td>243 041</td>
        <td>3 015</td>
        <td>167 444</td>
        <td>982,5</td>
        <td>271,8</td>
        <td>5 060</td>
        <td>4 845</td>
        <td>7 233</td>
        <td>165,1</td>
        <td>55,2</td>
        <td>215,4</td>
        <td>2,6</td>
        <td>687,3</td>
        <td>30,4</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 015</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,5</td>
        <td>487</td>
        <td>376</td>
        <td>80 978</td>
        <td>38,9</td>
        <td>5,7</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>167164738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1178</td>
        <td>0</td>
        <td>646</td>
        <td>1</td>
        <td>728</td>
        <td>47</td>
        <td>45 387 584</td>
        <td>206 710</td>
        <td>84 625 288</td>
        <td>0</td>
        <td>0</td>
        <td>4 910 245</td>
        <td>4</td>
        <td>167164738</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>69 206 016</td>
        <td>88 080 384</td>
        <td>57 619 720</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>9 437 184</td>
        <td>5 296 520</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 633 296</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 271 008</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>184 078</td>
        <td>236 273</td>
        <td>892 900</td>
        <td>5 706 877</td>
        <td>1 019 257</td>
        <td>8 764 649</td>
        <td>5 674 922</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 254 592</td>
        <td>101 187 584</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 637 632</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>69 730 304</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>57 344</td>
        <td>0</td>
        <td>0</td>
        <td>5 296 520</td>
        <td>78 643 200</td>
        <td>8 659 764</td>
        <td>331</td>
        <td>53 251</td>
        <td>313</td>
        <td>20 826</td>
        <td>1 673</td>
        <td>2 454</td>
        <td>998729221</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>970408380</td>
        <td>0</td>
        <td>0</td>
        <td>153091</td>
        <td>529058</td>
        <td>0</td>
        <td>0</td>
        <td>154829</td>
      </tr>
      <tr>
        <td>23:26:56.658, 27.02.2020</td>
        <td>3,9</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>125 186 288</td>
        <td>92 012 544</td>
        <td>86 271 008</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>1,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 148 672</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>412</td>
        <td>0,0</td>
        <td>36,3</td>
        <td>17</td>
        <td>51 871</td>
        <td>2 077</td>
        <td>11 342</td>
        <td>0,0</td>
        <td>13,5</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 353 173</td>
        <td>66</td>
        <td>453 349</td>
        <td>0</td>
        <td>821 595</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>369,5</td>
        <td>0,0</td>
        <td>56,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 428 765</td>
        <td>2 505 011</td>
        <td>0</td>
        <td>953,8</td>
        <td>261,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>7,6</td>
        <td>0,0</td>
        <td>245 239</td>
        <td>3 017</td>
        <td>167 474</td>
        <td>987,4</td>
        <td>271,6</td>
        <td>5 088</td>
        <td>4 872</td>
        <td>7 277</td>
        <td>165,5</td>
        <td>55,3</td>
        <td>217,2</td>
        <td>2,7</td>
        <td>692,5</td>
        <td>30,5</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 017</td>
        <td>31,4</td>
        <td>36,1</td>
        <td>193,9</td>
        <td>491</td>
        <td>380</td>
        <td>80 982</td>
        <td>39,0</td>
        <td>5,8</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>19540103</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>546</td>
        <td>0</td>
        <td>584</td>
        <td>0</td>
        <td>510</td>
        <td>19</td>
        <td>45 396 992</td>
        <td>206 710</td>
        <td>84 638 560</td>
        <td>0</td>
        <td>0</td>
        <td>4 911 005</td>
        <td>2</td>
        <td>19540103</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>6969599678</td>
        <td>6967777807</td>
        <td>9222103</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>88 604 672</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>4 968 840</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 772 560</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 281 632</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>276</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>179 598</td>
        <td>216 678</td>
        <td>829 633</td>
        <td>5 633 073</td>
        <td>983 755</td>
        <td>8 584 338</td>
        <td>5 604 314</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 567 040</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 254 592</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>139 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 968 840</td>
        <td>78 118 912</td>
        <td>8 653 933</td>
        <td>13</td>
        <td>65 835</td>
        <td>9</td>
        <td>36 895</td>
        <td>580</td>
        <td>1 465</td>
        <td>999083662</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>14</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1311136305</td>
        <td>0</td>
        <td>0</td>
        <td>352438</td>
        <td>10318346</td>
        <td>1</td>
        <td>0</td>
        <td>9497296</td>
      </tr>
      <tr>
        <td>23:26:57.658, 27.02.2020</td>
        <td>3,7</td>
        <td>0,2</td>
        <td>174 063 616</td>
        <td>66 241 360</td>
        <td>92 012 544</td>
        <td>86 281 632</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>0,2</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>69 394 432</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>413</td>
        <td>0,0</td>
        <td>36,4</td>
        <td>17</td>
        <td>52 155</td>
        <td>2 101</td>
        <td>11 396</td>
        <td>0,0</td>
        <td>13,5</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 363 537</td>
        <td>66</td>
        <td>453 440</td>
        <td>0</td>
        <td>821 897</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>371,7</td>
        <td>0,0</td>
        <td>57,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 480 549</td>
        <td>2 525 030</td>
        <td>0</td>
        <td>958,0</td>
        <td>263,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,4</td>
        <td>0,0</td>
        <td>247 457</td>
        <td>3 019</td>
        <td>167 506</td>
        <td>991,9</td>
        <td>271,9</td>
        <td>5 130</td>
        <td>4 913</td>
        <td>7 342</td>
        <td>165,5</td>
        <td>55,3</td>
        <td>218,1</td>
        <td>2,7</td>
        <td>696,1</td>
        <td>30,5</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 019</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,7</td>
        <td>495</td>
        <td>384</td>
        <td>80 986</td>
        <td>39,0</td>
        <td>5,8</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2652807</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>982</td>
        <td>38</td>
        <td>45 399 744</td>
        <td>206 710</td>
        <td>84 643 008</td>
        <td>0</td>
        <td>0</td>
        <td>4 911 186</td>
        <td>2</td>
        <td>2652807</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>88 604 672</td>
        <td>9 651 520</td>
        <td>8 912 896</td>
        <td>4 968 840</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 772 560</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 281 632</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>179 598</td>
        <td>216 678</td>
        <td>829 633</td>
        <td>5 633 073</td>
        <td>983 755</td>
        <td>8 584 338</td>
        <td>5 604 314</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 567 040</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 254 592</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>139 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 968 840</td>
        <td>78 118 912</td>
        <td>8 653 933</td>
        <td>13</td>
        <td>65 835</td>
        <td>9</td>
        <td>36 895</td>
        <td>580</td>
        <td>1 465</td>
        <td>1012758374</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>679129976</td>
        <td>0</td>
        <td>0</td>
        <td>41155</td>
        <td>224958</td>
        <td>1</td>
        <td>0</td>
        <td>72843</td>
      </tr>
      <tr>
        <td>23:26:58.658, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>76 453 536</td>
        <td>92 012 544</td>
        <td>86 281 632</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>2,6</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 394 432</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>416</td>
        <td>0,0</td>
        <td>36,4</td>
        <td>17</td>
        <td>52 445</td>
        <td>2 125</td>
        <td>11 452</td>
        <td>0,0</td>
        <td>13,5</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 373 935</td>
        <td>66</td>
        <td>453 531</td>
        <td>0</td>
        <td>823 462</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>373,0</td>
        <td>0,0</td>
        <td>57,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 532 943</td>
        <td>2 545 132</td>
        <td>0</td>
        <td>959,4</td>
        <td>264,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>5,3</td>
        <td>0,0</td>
        <td>249 675</td>
        <td>3 021</td>
        <td>167 538</td>
        <td>994,8</td>
        <td>271,7</td>
        <td>5 172</td>
        <td>4 954</td>
        <td>7 407</td>
        <td>165,9</td>
        <td>55,3</td>
        <td>219,5</td>
        <td>2,7</td>
        <td>699,5</td>
        <td>30,5</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 021</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,8</td>
        <td>499</td>
        <td>388</td>
        <td>81 078</td>
        <td>39,0</td>
        <td>5,9</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>24147592</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>38782</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>1977</td>
        <td>76</td>
        <td>45 422 304</td>
        <td>206 710</td>
        <td>84 682 584</td>
        <td>0</td>
        <td>0</td>
        <td>4 912 615</td>
        <td>3</td>
        <td>24147592</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>88 604 672</td>
        <td>19 503 816</td>
        <td>8 912 896</td>
        <td>4 968 840</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 772 560</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 281 632</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>179 598</td>
        <td>216 678</td>
        <td>829 633</td>
        <td>5 633 073</td>
        <td>983 755</td>
        <td>8 584 338</td>
        <td>5 604 314</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 567 040</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 254 592</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>139 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 968 840</td>
        <td>78 118 912</td>
        <td>8 653 933</td>
        <td>13</td>
        <td>65 835</td>
        <td>9</td>
        <td>36 895</td>
        <td>580</td>
        <td>1 465</td>
        <td>1001169762</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>997635623</td>
        <td>0</td>
        <td>0</td>
        <td>173283</td>
        <td>567625</td>
        <td>0</td>
        <td>0</td>
        <td>151097</td>
      </tr>
      <tr>
        <td>23:26:59.658, 27.02.2020</td>
        <td>3,9</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>85 848 640</td>
        <td>92 012 544</td>
        <td>86 281 632</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>2,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 394 432</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>417</td>
        <td>0,0</td>
        <td>36,4</td>
        <td>17</td>
        <td>52 728</td>
        <td>2 149</td>
        <td>11 506</td>
        <td>0,0</td>
        <td>13,5</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 384 299</td>
        <td>66</td>
        <td>453 621</td>
        <td>0</td>
        <td>823 763</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>374,6</td>
        <td>0,0</td>
        <td>57,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 584 610</td>
        <td>2 565 151</td>
        <td>0</td>
        <td>964,1</td>
        <td>266,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,9</td>
        <td>0,0</td>
        <td>251 873</td>
        <td>3 023</td>
        <td>167 568</td>
        <td>002,0</td>
        <td>272,0</td>
        <td>5 200</td>
        <td>4 981</td>
        <td>7 451</td>
        <td>165,7</td>
        <td>55,3</td>
        <td>220,8</td>
        <td>2,7</td>
        <td>702,5</td>
        <td>30,5</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 023</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,6</td>
        <td>504</td>
        <td>392</td>
        <td>81 082</td>
        <td>39,0</td>
        <td>5,9</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>27814823</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>519</td>
        <td>6</td>
        <td>2829</td>
        <td>85</td>
        <td>45 461 888</td>
        <td>206 710</td>
        <td>84 753 960</td>
        <td>0</td>
        <td>0</td>
        <td>4 914 771</td>
        <td>7</td>
        <td>27814823</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>88 604 672</td>
        <td>29 945 976</td>
        <td>8 912 896</td>
        <td>4 968 840</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 772 560</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 281 632</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>179 598</td>
        <td>216 678</td>
        <td>829 633</td>
        <td>5 633 073</td>
        <td>983 755</td>
        <td>8 584 338</td>
        <td>5 604 314</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 567 040</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 254 592</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>139 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 968 840</td>
        <td>78 118 912</td>
        <td>8 653 933</td>
        <td>13</td>
        <td>65 835</td>
        <td>9</td>
        <td>36 895</td>
        <td>580</td>
        <td>1 465</td>
        <td>1008661913</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1005779431</td>
        <td>0</td>
        <td>0</td>
        <td>143614</td>
        <td>493721</td>
        <td>1</td>
        <td>0</td>
        <td>136407</td>
      </tr>
      <tr>
        <td>23:27:00.659, 27.02.2020</td>
        <td>4,2</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>95 709 864</td>
        <td>92 012 544</td>
        <td>86 281 632</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>3,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 394 432</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>418</td>
        <td>0,0</td>
        <td>36,4</td>
        <td>17</td>
        <td>53 012</td>
        <td>2 173</td>
        <td>11 560</td>
        <td>0,0</td>
        <td>13,5</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 394 663</td>
        <td>66</td>
        <td>453 712</td>
        <td>0</td>
        <td>824 065</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>375,9</td>
        <td>0,0</td>
        <td>57,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 636 393</td>
        <td>2 585 170</td>
        <td>0</td>
        <td>968,0</td>
        <td>267,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,6</td>
        <td>0,0</td>
        <td>254 091</td>
        <td>3 025</td>
        <td>167 600</td>
        <td>006,8</td>
        <td>272,0</td>
        <td>5 242</td>
        <td>5 022</td>
        <td>7 516</td>
        <td>166,2</td>
        <td>55,4</td>
        <td>222,6</td>
        <td>2,7</td>
        <td>706,5</td>
        <td>30,6</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 025</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,9</td>
        <td>508</td>
        <td>396</td>
        <td>81 086</td>
        <td>39,1</td>
        <td>6,0</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>29524735</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>400</td>
        <td>0</td>
        <td>477</td>
        <td>1</td>
        <td>1090</td>
        <td>2</td>
        <td>45 468 320</td>
        <td>206 710</td>
        <td>84 764 904</td>
        <td>0</td>
        <td>0</td>
        <td>4 915 455</td>
        <td>2</td>
        <td>29524735</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>88 604 672</td>
        <td>39 458 080</td>
        <td>8 912 896</td>
        <td>4 968 840</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 772 560</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 281 632</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>179 598</td>
        <td>216 678</td>
        <td>829 633</td>
        <td>5 633 073</td>
        <td>983 755</td>
        <td>8 584 338</td>
        <td>5 604 314</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 567 040</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 254 592</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>139 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 968 840</td>
        <td>78 118 912</td>
        <td>8 653 933</td>
        <td>13</td>
        <td>65 835</td>
        <td>9</td>
        <td>36 895</td>
        <td>580</td>
        <td>1 465</td>
        <td>996004520</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>992838000</td>
        <td>0</td>
        <td>0</td>
        <td>2359402</td>
        <td>2709696</td>
        <td>0</td>
        <td>0</td>
        <td>146296</td>
      </tr>
      <tr>
        <td>23:27:01.659, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>105 105 016</td>
        <td>92 012 544</td>
        <td>86 281 632</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>3,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 394 432</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>419</td>
        <td>0,0</td>
        <td>36,4</td>
        <td>17</td>
        <td>53 297</td>
        <td>2 197</td>
        <td>11 614</td>
        <td>0,0</td>
        <td>13,6</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 405 027</td>
        <td>66</td>
        <td>453 802</td>
        <td>0</td>
        <td>824 366</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>377,8</td>
        <td>0,0</td>
        <td>57,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 688 069</td>
        <td>2 605 189</td>
        <td>0</td>
        <td>971,6</td>
        <td>268,6</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,5</td>
        <td>0,0</td>
        <td>256 290</td>
        <td>3 027</td>
        <td>167 630</td>
        <td>009,6</td>
        <td>271,8</td>
        <td>5 270</td>
        <td>5 049</td>
        <td>7 560</td>
        <td>166,2</td>
        <td>55,4</td>
        <td>223,8</td>
        <td>2,7</td>
        <td>710,1</td>
        <td>30,6</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 027</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,9</td>
        <td>512</td>
        <td>400</td>
        <td>81 090</td>
        <td>39,1</td>
        <td>6,0</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>31079941</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>920</td>
        <td>0</td>
        <td>829</td>
        <td>2</td>
        <td>1464</td>
        <td>49</td>
        <td>45 479 488</td>
        <td>206 710</td>
        <td>84 783 512</td>
        <td>0</td>
        <td>0</td>
        <td>4 916 347</td>
        <td>6</td>
        <td>31079941</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>88 604 672</td>
        <td>48 853 408</td>
        <td>8 912 896</td>
        <td>4 968 840</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 772 560</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 281 632</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>179 598</td>
        <td>216 678</td>
        <td>829 633</td>
        <td>5 633 073</td>
        <td>983 755</td>
        <td>8 584 338</td>
        <td>5 604 314</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 567 040</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 254 592</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>139 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 968 840</td>
        <td>78 118 912</td>
        <td>8 653 933</td>
        <td>13</td>
        <td>65 835</td>
        <td>9</td>
        <td>36 895</td>
        <td>580</td>
        <td>1 465</td>
        <td>1000100930</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>994600996</td>
        <td>0</td>
        <td>0</td>
        <td>144822</td>
        <td>520604</td>
        <td>0</td>
        <td>0</td>
        <td>153130</td>
      </tr>
      <tr>
        <td>23:27:02.659, 27.02.2020</td>
        <td>6,2</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>114 959 864</td>
        <td>92 012 544</td>
        <td>86 281 632</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>10,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 394 432</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>420</td>
        <td>0,0</td>
        <td>36,5</td>
        <td>17</td>
        <td>53 581</td>
        <td>2 221</td>
        <td>11 668</td>
        <td>0,0</td>
        <td>13,6</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 415 391</td>
        <td>66</td>
        <td>453 893</td>
        <td>0</td>
        <td>824 668</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>379,5</td>
        <td>0,0</td>
        <td>57,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 739 855</td>
        <td>2 625 208</td>
        <td>0</td>
        <td>975,4</td>
        <td>270,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>6,8</td>
        <td>0,0</td>
        <td>258 508</td>
        <td>3 029</td>
        <td>167 662</td>
        <td>017,7</td>
        <td>272,1</td>
        <td>5 312</td>
        <td>5 090</td>
        <td>7 625</td>
        <td>166,6</td>
        <td>55,5</td>
        <td>225,2</td>
        <td>2,7</td>
        <td>714,7</td>
        <td>30,6</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 029</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,0</td>
        <td>516</td>
        <td>404</td>
        <td>81 094</td>
        <td>39,2</td>
        <td>6,1</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>103447718</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>519</td>
        <td>1</td>
        <td>521</td>
        <td>2</td>
        <td>650</td>
        <td>11</td>
        <td>45 490 400</td>
        <td>211 702</td>
        <td>84 805 288</td>
        <td>1</td>
        <td>95983501</td>
        <td>4 916 673</td>
        <td>3</td>
        <td>7464217</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>88 604 672</td>
        <td>55 218 464</td>
        <td>8 912 896</td>
        <td>4 968 840</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 772 560</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 281 632</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>179 598</td>
        <td>216 678</td>
        <td>829 633</td>
        <td>5 633 073</td>
        <td>983 755</td>
        <td>8 584 338</td>
        <td>5 604 314</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 567 040</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 254 592</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>139 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 968 840</td>
        <td>78 118 912</td>
        <td>8 653 933</td>
        <td>13</td>
        <td>65 835</td>
        <td>9</td>
        <td>36 895</td>
        <td>580</td>
        <td>1 465</td>
        <td>969754065</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>16</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1017998759</td>
        <td>0</td>
        <td>0</td>
        <td>72494</td>
        <td>417594</td>
        <td>1</td>
        <td>0</td>
        <td>139886</td>
      </tr>
      <tr>
        <td>23:27:03.659, 27.02.2020</td>
        <td>2,4</td>
        <td>0,0</td>
        <td>174 063 616</td>
        <td>124 708 424</td>
        <td>92 012 544</td>
        <td>86 281 632</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>0,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 394 432</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>421</td>
        <td>0,0</td>
        <td>36,5</td>
        <td>17</td>
        <td>53 864</td>
        <td>2 245</td>
        <td>11 722</td>
        <td>0,0</td>
        <td>13,6</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 425 761</td>
        <td>66</td>
        <td>453 983</td>
        <td>0</td>
        <td>824 969</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>380,8</td>
        <td>0,0</td>
        <td>57,1</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 791 542</td>
        <td>2 645 237</td>
        <td>0</td>
        <td>978,2</td>
        <td>271,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,2</td>
        <td>0,0</td>
        <td>260 706</td>
        <td>3 031</td>
        <td>167 692</td>
        <td>022,6</td>
        <td>272,1</td>
        <td>5 340</td>
        <td>5 117</td>
        <td>7 669</td>
        <td>166,4</td>
        <td>55,4</td>
        <td>225,7</td>
        <td>2,7</td>
        <td>718,1</td>
        <td>30,6</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 031</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>193,8</td>
        <td>521</td>
        <td>408</td>
        <td>81 098</td>
        <td>39,2</td>
        <td>6,1</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11960658</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>1228</td>
        <td>2</td>
        <td>824</td>
        <td>0</td>
        <td>0</td>
        <td>79</td>
        <td>45 492 544</td>
        <td>211 702</td>
        <td>84 809 520</td>
        <td>0</td>
        <td>0</td>
        <td>4 917 325</td>
        <td>3</td>
        <td>11960658</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>88 604 672</td>
        <td>64 967 024</td>
        <td>8 912 896</td>
        <td>4 968 840</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>54 772 560</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 281 632</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>179 598</td>
        <td>216 678</td>
        <td>829 633</td>
        <td>5 633 073</td>
        <td>983 755</td>
        <td>8 584 338</td>
        <td>5 604 314</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>70 778 880</td>
        <td>101 711 872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 567 040</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 254 592</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>139 264</td>
        <td>0</td>
        <td>0</td>
        <td>4 968 840</td>
        <td>78 118 912</td>
        <td>8 653 933</td>
        <td>13</td>
        <td>65 835</td>
        <td>9</td>
        <td>36 895</td>
        <td>580</td>
        <td>1 465</td>
        <td>1008241971</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1005548336</td>
        <td>0</td>
        <td>0</td>
        <td>83096</td>
        <td>277053</td>
        <td>1</td>
        <td>0</td>
        <td>68401</td>
      </tr>
      <tr>
        <td>23:27:04.659, 27.02.2020</td>
        <td>2,9</td>
        <td>0,1</td>
        <td>174 587 904</td>
        <td>64 983 416</td>
        <td>92 012 544</td>
        <td>86 282 880</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>1,2</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>70 192 488</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>422</td>
        <td>0,0</td>
        <td>36,5</td>
        <td>17</td>
        <td>54 149</td>
        <td>2 269</td>
        <td>11 776</td>
        <td>0,0</td>
        <td>13,6</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 436 125</td>
        <td>66</td>
        <td>454 073</td>
        <td>0</td>
        <td>825 270</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>382,1</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 843 209</td>
        <td>2 665 256</td>
        <td>0</td>
        <td>980,6</td>
        <td>272,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,1</td>
        <td>0,0</td>
        <td>262 904</td>
        <td>3 033</td>
        <td>167 722</td>
        <td>026,2</td>
        <td>271,8</td>
        <td>5 368</td>
        <td>5 144</td>
        <td>7 713</td>
        <td>166,7</td>
        <td>55,6</td>
        <td>227,8</td>
        <td>2,7</td>
        <td>723,6</td>
        <td>30,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 033</td>
        <td>31,4</td>
        <td>36,1</td>
        <td>194,2</td>
        <td>525</td>
        <td>412</td>
        <td>81 102</td>
        <td>39,3</td>
        <td>6,2</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,5</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12583612</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>335</td>
        <td>1</td>
        <td>831</td>
        <td>3</td>
        <td>1135</td>
        <td>46</td>
        <td>45 503 168</td>
        <td>211 735</td>
        <td>84 825 152</td>
        <td>0</td>
        <td>3041414</td>
        <td>4 918 003</td>
        <td>4</td>
        <td>9542198</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>6841794954</td>
        <td>6839295381</td>
        <td>6559866</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>89 128 960</td>
        <td>9 475 224</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>4 734 992</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>55 068 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 282 880</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>202</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>191 235</td>
        <td>205 483</td>
        <td>807 687</td>
        <td>5 543 265</td>
        <td>966 206</td>
        <td>8 441 886</td>
        <td>5 517 382</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 480 096</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>295 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 734 992</td>
        <td>79 167 488</td>
        <td>8 800 022</td>
        <td>16</td>
        <td>81 648</td>
        <td>7</td>
        <td>44 488</td>
        <td>811</td>
        <td>1 507</td>
        <td>1030138464</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>984563217</td>
        <td>0</td>
        <td>0</td>
        <td>210474</td>
        <td>7377312</td>
        <td>2</td>
        <td>0</td>
        <td>6747029</td>
      </tr>
      <tr>
        <td>23:27:05.660, 27.02.2020</td>
        <td>3,4</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>74 733 376</td>
        <td>92 012 544</td>
        <td>86 282 880</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>0,6</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 192 488</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>425</td>
        <td>0,0</td>
        <td>36,5</td>
        <td>17</td>
        <td>54 437</td>
        <td>2 293</td>
        <td>11 832</td>
        <td>0,0</td>
        <td>13,6</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 446 523</td>
        <td>66</td>
        <td>454 164</td>
        <td>0</td>
        <td>825 572</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>382,6</td>
        <td>0,0</td>
        <td>57,1</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 895 083</td>
        <td>2 685 358</td>
        <td>0</td>
        <td>983,0</td>
        <td>273,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,1</td>
        <td>0,0</td>
        <td>265 122</td>
        <td>3 035</td>
        <td>167 754</td>
        <td>033,8</td>
        <td>272,1</td>
        <td>5 410</td>
        <td>5 185</td>
        <td>7 778</td>
        <td>166,8</td>
        <td>55,5</td>
        <td>228,8</td>
        <td>2,8</td>
        <td>727,2</td>
        <td>30,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 035</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,1</td>
        <td>529</td>
        <td>416</td>
        <td>81 106</td>
        <td>39,3</td>
        <td>6,2</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2238483</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>308</td>
        <td>12</td>
        <td>45 506 464</td>
        <td>211 735</td>
        <td>84 830 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 918 175</td>
        <td>2</td>
        <td>2238483</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>89 128 960</td>
        <td>15 113 088</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>4 734 992</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>55 068 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 282 880</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>191 235</td>
        <td>205 483</td>
        <td>807 687</td>
        <td>5 543 265</td>
        <td>966 206</td>
        <td>8 441 886</td>
        <td>5 517 382</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 480 096</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>295 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 734 992</td>
        <td>79 167 488</td>
        <td>8 800 022</td>
        <td>16</td>
        <td>81 648</td>
        <td>7</td>
        <td>44 488</td>
        <td>811</td>
        <td>1 507</td>
        <td>977012951</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 280</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1010944567</td>
        <td>0</td>
        <td>0</td>
        <td>180649</td>
        <td>562539</td>
        <td>1</td>
        <td>0</td>
        <td>158926</td>
      </tr>
      <tr>
        <td>23:27:06.660, 27.02.2020</td>
        <td>2,4</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>84 186 424</td>
        <td>92 012 544</td>
        <td>86 282 880</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 192 488</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>426</td>
        <td>0,0</td>
        <td>36,5</td>
        <td>17</td>
        <td>54 722</td>
        <td>2 317</td>
        <td>11 886</td>
        <td>0,0</td>
        <td>13,7</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 456 887</td>
        <td>66</td>
        <td>454 254</td>
        <td>0</td>
        <td>825 875</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>384,1</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 946 762</td>
        <td>2 705 377</td>
        <td>0</td>
        <td>986,6</td>
        <td>274,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>5,7</td>
        <td>0,0</td>
        <td>267 320</td>
        <td>3 037</td>
        <td>167 784</td>
        <td>037,0</td>
        <td>271,9</td>
        <td>5 438</td>
        <td>5 212</td>
        <td>7 822</td>
        <td>166,8</td>
        <td>55,6</td>
        <td>229,7</td>
        <td>2,8</td>
        <td>731,5</td>
        <td>30,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 037</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,1</td>
        <td>533</td>
        <td>420</td>
        <td>81 110</td>
        <td>39,3</td>
        <td>6,3</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>45 506 464</td>
        <td>211 735</td>
        <td>84 830 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 918 175</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>89 128 960</td>
        <td>24 760 376</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>4 734 992</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>55 068 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 282 880</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>191 235</td>
        <td>205 483</td>
        <td>807 687</td>
        <td>5 543 265</td>
        <td>966 206</td>
        <td>8 441 886</td>
        <td>5 517 382</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 480 096</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>295 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 734 992</td>
        <td>79 167 488</td>
        <td>8 800 022</td>
        <td>16</td>
        <td>81 648</td>
        <td>7</td>
        <td>44 488</td>
        <td>811</td>
        <td>1 507</td>
        <td>999391623</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>996872623</td>
        <td>0</td>
        <td>0</td>
        <td>138826</td>
        <td>505599</td>
        <td>0</td>
        <td>0</td>
        <td>142792</td>
      </tr>
      <tr>
        <td>23:27:07.660, 27.02.2020</td>
        <td>1,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>94 042 088</td>
        <td>92 012 544</td>
        <td>86 282 880</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 192 488</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>427</td>
        <td>0,0</td>
        <td>36,5</td>
        <td>17</td>
        <td>55 008</td>
        <td>2 341</td>
        <td>11 940</td>
        <td>0,0</td>
        <td>13,7</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 467 146</td>
        <td>66</td>
        <td>454 345</td>
        <td>0</td>
        <td>826 177</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>384,6</td>
        <td>0,0</td>
        <td>57,1</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>7 998 305</td>
        <td>2 725 242</td>
        <td>0</td>
        <td>988,2</td>
        <td>274,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,4</td>
        <td>0,0</td>
        <td>269 538</td>
        <td>3 039</td>
        <td>167 816</td>
        <td>046,0</td>
        <td>272,4</td>
        <td>5 480</td>
        <td>5 253</td>
        <td>7 887</td>
        <td>166,8</td>
        <td>55,5</td>
        <td>230,5</td>
        <td>2,8</td>
        <td>734,7</td>
        <td>30,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 039</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,0</td>
        <td>538</td>
        <td>424</td>
        <td>81 114</td>
        <td>39,3</td>
        <td>6,3</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>45 506 464</td>
        <td>211 735</td>
        <td>84 830 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 918 175</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>89 128 960</td>
        <td>34 849 352</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>4 734 992</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>55 068 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 282 880</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>191 235</td>
        <td>205 483</td>
        <td>807 687</td>
        <td>5 543 265</td>
        <td>966 206</td>
        <td>8 441 886</td>
        <td>5 517 382</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 480 096</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>295 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 734 992</td>
        <td>79 167 488</td>
        <td>8 800 022</td>
        <td>16</td>
        <td>81 648</td>
        <td>7</td>
        <td>44 488</td>
        <td>811</td>
        <td>1 507</td>
        <td>990537822</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>987622609</td>
        <td>0</td>
        <td>0</td>
        <td>123938</td>
        <td>346705</td>
        <td>0</td>
        <td>0</td>
        <td>90579</td>
      </tr>
      <tr>
        <td>23:27:08.660, 27.02.2020</td>
        <td>2,9</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>103 097 712</td>
        <td>92 012 544</td>
        <td>86 282 880</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 192 488</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>428</td>
        <td>0,0</td>
        <td>36,5</td>
        <td>17</td>
        <td>55 293</td>
        <td>2 365</td>
        <td>11 994</td>
        <td>0,0</td>
        <td>13,7</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 477 405</td>
        <td>66</td>
        <td>454 435</td>
        <td>0</td>
        <td>826 478</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>386,5</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 049 739</td>
        <td>2 745 107</td>
        <td>0</td>
        <td>992,3</td>
        <td>276,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>7,6</td>
        <td>0,0</td>
        <td>271 736</td>
        <td>3 041</td>
        <td>167 846</td>
        <td>051,1</td>
        <td>272,2</td>
        <td>5 508</td>
        <td>5 280</td>
        <td>7 931</td>
        <td>167,0</td>
        <td>55,6</td>
        <td>232,1</td>
        <td>2,8</td>
        <td>741,0</td>
        <td>30,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 041</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,2</td>
        <td>542</td>
        <td>428</td>
        <td>81 118</td>
        <td>39,3</td>
        <td>6,4</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3760201</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>1190</td>
        <td>11</td>
        <td>45 512 064</td>
        <td>211 735</td>
        <td>84 840 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 918 458</td>
        <td>2</td>
        <td>3760201</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>89 128 960</td>
        <td>43 853 240</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>4 734 992</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>55 068 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 282 880</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>191 235</td>
        <td>205 483</td>
        <td>807 687</td>
        <td>5 543 265</td>
        <td>966 206</td>
        <td>8 441 886</td>
        <td>5 517 382</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 480 096</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>295 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 734 992</td>
        <td>79 167 488</td>
        <td>8 800 022</td>
        <td>16</td>
        <td>81 648</td>
        <td>7</td>
        <td>44 488</td>
        <td>811</td>
        <td>1 507</td>
        <td>992461785</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>990050730</td>
        <td>0</td>
        <td>0</td>
        <td>97182</td>
        <td>301345</td>
        <td>0</td>
        <td>0</td>
        <td>76029</td>
      </tr>
      <tr>
        <td>23:27:09.660, 27.02.2020</td>
        <td>2,9</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>112 839 032</td>
        <td>92 012 544</td>
        <td>86 282 880</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 192 488</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>429</td>
        <td>0,0</td>
        <td>36,6</td>
        <td>17</td>
        <td>55 576</td>
        <td>2 389</td>
        <td>12 048</td>
        <td>0,0</td>
        <td>13,7</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 487 664</td>
        <td>66</td>
        <td>454 525</td>
        <td>0</td>
        <td>826 779</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>387,8</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 101 165</td>
        <td>2 764 972</td>
        <td>0</td>
        <td>995,1</td>
        <td>277,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,8</td>
        <td>0,0</td>
        <td>273 934</td>
        <td>3 043</td>
        <td>167 876</td>
        <td>056,4</td>
        <td>272,2</td>
        <td>5 536</td>
        <td>5 307</td>
        <td>7 975</td>
        <td>167,0</td>
        <td>55,6</td>
        <td>233,8</td>
        <td>2,9</td>
        <td>744,7</td>
        <td>30,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 043</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,2</td>
        <td>546</td>
        <td>432</td>
        <td>81 122</td>
        <td>39,4</td>
        <td>6,4</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3498123</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>260</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1164</td>
        <td>37</td>
        <td>45 518 176</td>
        <td>211 735</td>
        <td>84 850 544</td>
        <td>0</td>
        <td>0</td>
        <td>4 918 752</td>
        <td>4</td>
        <td>3498123</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>89 128 960</td>
        <td>55 067 968</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>4 734 992</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>55 068 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 282 880</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>191 235</td>
        <td>205 483</td>
        <td>807 687</td>
        <td>5 543 265</td>
        <td>966 206</td>
        <td>8 441 886</td>
        <td>5 517 382</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 480 096</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>295 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 734 992</td>
        <td>79 167 488</td>
        <td>8 800 022</td>
        <td>16</td>
        <td>81 648</td>
        <td>7</td>
        <td>44 488</td>
        <td>811</td>
        <td>1 507</td>
        <td>1029952762</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1026485171</td>
        <td>0</td>
        <td>0</td>
        <td>52483</td>
        <td>374477</td>
        <td>1</td>
        <td>0</td>
        <td>118424</td>
      </tr>
      <tr>
        <td>23:27:10.661, 27.02.2020</td>
        <td>2,4</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>122 397 048</td>
        <td>92 012 544</td>
        <td>86 282 880</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>1,6</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 192 488</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>430</td>
        <td>0,0</td>
        <td>36,6</td>
        <td>17</td>
        <td>55 864</td>
        <td>2 413</td>
        <td>12 102</td>
        <td>0,0</td>
        <td>13,8</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 497 929</td>
        <td>66</td>
        <td>454 615</td>
        <td>0</td>
        <td>827 080</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>388,8</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 152 627</td>
        <td>2 784 847</td>
        <td>0</td>
        <td>998,0</td>
        <td>278,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>9,7</td>
        <td>0,0</td>
        <td>276 132</td>
        <td>3 045</td>
        <td>167 906</td>
        <td>063,7</td>
        <td>271,9</td>
        <td>5 564</td>
        <td>5 334</td>
        <td>8 019</td>
        <td>166,8</td>
        <td>55,6</td>
        <td>234,5</td>
        <td>2,9</td>
        <td>752,3</td>
        <td>30,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 045</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,1</td>
        <td>550</td>
        <td>436</td>
        <td>81 126</td>
        <td>39,3</td>
        <td>6,4</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>19497824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>558</td>
        <td>0</td>
        <td>581</td>
        <td>3</td>
        <td>1161</td>
        <td>88</td>
        <td>45 528 992</td>
        <td>211 735</td>
        <td>84 866 096</td>
        <td>0</td>
        <td>0</td>
        <td>4 919 304</td>
        <td>5</td>
        <td>19497824</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>70 254 592</td>
        <td>89 128 960</td>
        <td>64 061 584</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>4 734 992</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>55 068 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 282 880</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>191 235</td>
        <td>205 483</td>
        <td>807 687</td>
        <td>5 543 265</td>
        <td>966 206</td>
        <td>8 441 886</td>
        <td>5 517 382</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 480 096</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>70 778 880</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>295 952</td>
        <td>0</td>
        <td>0</td>
        <td>4 734 992</td>
        <td>79 167 488</td>
        <td>8 800 022</td>
        <td>16</td>
        <td>81 648</td>
        <td>7</td>
        <td>44 488</td>
        <td>811</td>
        <td>1 507</td>
        <td>989393482</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>14</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>988264627</td>
        <td>0</td>
        <td>0</td>
        <td>192143</td>
        <td>567711</td>
        <td>1</td>
        <td>0</td>
        <td>94973</td>
      </tr>
      <tr>
        <td>23:27:11.661, 27.02.2020</td>
        <td>3,4</td>
        <td>0,1</td>
        <td>174 587 904</td>
        <td>62 953 904</td>
        <td>92 012 544</td>
        <td>86 290 128</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>2,3</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>70 328 320</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>431</td>
        <td>0,0</td>
        <td>36,6</td>
        <td>17</td>
        <td>56 147</td>
        <td>2 437</td>
        <td>12 156</td>
        <td>0,0</td>
        <td>13,8</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 508 188</td>
        <td>66</td>
        <td>454 705</td>
        <td>0</td>
        <td>827 381</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>389,8</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 204 062</td>
        <td>2 804 712</td>
        <td>0</td>
        <td>999,3</td>
        <td>279,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,2</td>
        <td>0,0</td>
        <td>278 331</td>
        <td>3 047</td>
        <td>167 936</td>
        <td>070,2</td>
        <td>272,6</td>
        <td>5 592</td>
        <td>5 361</td>
        <td>8 063</td>
        <td>166,2</td>
        <td>55,4</td>
        <td>234,2</td>
        <td>2,9</td>
        <td>753,1</td>
        <td>30,7</td>
        <td>0,0</td>
        <td>33,8</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 047</td>
        <td>31,2</td>
        <td>35,8</td>
        <td>193,3</td>
        <td>555</td>
        <td>440</td>
        <td>81 130</td>
        <td>39,2</td>
        <td>6,4</td>
        <td>28,0</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,8</td>
        <td>123,7</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>20669379</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>1520</td>
        <td>113</td>
        <td>45 536 960</td>
        <td>211 735</td>
        <td>84 879 512</td>
        <td>0</td>
        <td>0</td>
        <td>4 920 497</td>
        <td>5</td>
        <td>20669379</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>7139061093</td>
        <td>7138420832</td>
        <td>6017313</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>4 601 448</td>
        <td>8 912 896</td>
        <td>3 211 264</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 518 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 290 128</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>202</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>317 114</td>
        <td>298 225</td>
        <td>1 211 791</td>
        <td>5 310 065</td>
        <td>1 079 466</td>
        <td>8 548 464</td>
        <td>5 286 770</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 249 504</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>1 450 000</td>
        <td>0</td>
        <td>0</td>
        <td>3 211 264</td>
        <td>79 167 488</td>
        <td>8 779 905</td>
        <td>15</td>
        <td>63 731</td>
        <td>7</td>
        <td>30 887</td>
        <td>2 651</td>
        <td>3 658</td>
        <td>994699542</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>986187348</td>
        <td>0</td>
        <td>0</td>
        <td>176674</td>
        <td>6703095</td>
        <td>1</td>
        <td>0</td>
        <td>6209397</td>
      </tr>
      <tr>
        <td>23:27:12.661, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>72 388 000</td>
        <td>92 012 544</td>
        <td>86 290 128</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 328 320</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>434</td>
        <td>0,0</td>
        <td>36,6</td>
        <td>17</td>
        <td>56 434</td>
        <td>2 461</td>
        <td>12 212</td>
        <td>0,0</td>
        <td>13,8</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 518 481</td>
        <td>66</td>
        <td>454 795</td>
        <td>0</td>
        <td>828 945</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>391,2</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 256 097</td>
        <td>2 824 660</td>
        <td>0</td>
        <td>003,7</td>
        <td>280,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,0</td>
        <td>0,0</td>
        <td>280 529</td>
        <td>3 049</td>
        <td>167 966</td>
        <td>073,6</td>
        <td>272,3</td>
        <td>5 620</td>
        <td>5 388</td>
        <td>8 107</td>
        <td>167,9</td>
        <td>55,9</td>
        <td>237,7</td>
        <td>2,9</td>
        <td>765,1</td>
        <td>31,0</td>
        <td>0,0</td>
        <td>34,2</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 049</td>
        <td>31,5</td>
        <td>36,2</td>
        <td>195,3</td>
        <td>559</td>
        <td>444</td>
        <td>81 222</td>
        <td>39,6</td>
        <td>6,6</td>
        <td>28,3</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>125,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>113</td>
        <td>45 536 960</td>
        <td>211 735</td>
        <td>84 879 512</td>
        <td>0</td>
        <td>0</td>
        <td>4 920 497</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>15 883 312</td>
        <td>8 912 896</td>
        <td>3 211 264</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 518 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 290 128</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>317 114</td>
        <td>298 225</td>
        <td>1 211 791</td>
        <td>5 310 065</td>
        <td>1 079 466</td>
        <td>8 548 464</td>
        <td>5 286 770</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 249 504</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>1 450 000</td>
        <td>0</td>
        <td>0</td>
        <td>3 211 264</td>
        <td>79 167 488</td>
        <td>8 779 905</td>
        <td>15</td>
        <td>63 731</td>
        <td>7</td>
        <td>30 887</td>
        <td>2 651</td>
        <td>3 658</td>
        <td>1024352482</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1020758429</td>
        <td>0</td>
        <td>0</td>
        <td>161023</td>
        <td>438458</td>
        <td>1</td>
        <td>0</td>
        <td>111517</td>
      </tr>
      <tr>
        <td>23:27:13.661, 27.02.2020</td>
        <td>1,9</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>82 298 936</td>
        <td>92 012 544</td>
        <td>86 290 128</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,1</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 328 320</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>435</td>
        <td>0,0</td>
        <td>36,6</td>
        <td>17</td>
        <td>56 719</td>
        <td>2 485</td>
        <td>12 266</td>
        <td>0,0</td>
        <td>13,8</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 528 740</td>
        <td>66</td>
        <td>454 885</td>
        <td>0</td>
        <td>829 246</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>392,4</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 307 523</td>
        <td>2 844 525</td>
        <td>0</td>
        <td>007,0</td>
        <td>281,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,4</td>
        <td>0,0</td>
        <td>282 727</td>
        <td>3 051</td>
        <td>167 996</td>
        <td>080,8</td>
        <td>272,6</td>
        <td>5 648</td>
        <td>5 415</td>
        <td>8 151</td>
        <td>167,0</td>
        <td>55,7</td>
        <td>237,2</td>
        <td>2,9</td>
        <td>765,7</td>
        <td>30,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 051</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,4</td>
        <td>563</td>
        <td>448</td>
        <td>81 226</td>
        <td>39,5</td>
        <td>6,6</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>560433</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>231</td>
        <td>32</td>
        <td>45 537 728</td>
        <td>211 735</td>
        <td>84 880 760</td>
        <td>0</td>
        <td>0</td>
        <td>4 920 529</td>
        <td>0</td>
        <td>560433</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>25 783 112</td>
        <td>8 912 896</td>
        <td>3 211 264</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 518 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 290 128</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>317 114</td>
        <td>298 225</td>
        <td>1 211 791</td>
        <td>5 310 065</td>
        <td>1 079 466</td>
        <td>8 548 464</td>
        <td>5 286 770</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 249 504</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>1 450 000</td>
        <td>0</td>
        <td>0</td>
        <td>3 211 264</td>
        <td>79 167 488</td>
        <td>8 779 905</td>
        <td>15</td>
        <td>63 731</td>
        <td>7</td>
        <td>30 887</td>
        <td>2 651</td>
        <td>3 658</td>
        <td>997180443</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>994465927</td>
        <td>0</td>
        <td>0</td>
        <td>43128</td>
        <td>285409</td>
        <td>0</td>
        <td>0</td>
        <td>87285</td>
      </tr>
      <tr>
        <td>23:27:14.662, 27.02.2020</td>
        <td>2,2</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>91 735 744</td>
        <td>92 012 544</td>
        <td>86 290 128</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 328 320</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>436</td>
        <td>0,0</td>
        <td>36,6</td>
        <td>17</td>
        <td>57 010</td>
        <td>2 509</td>
        <td>12 320</td>
        <td>0,0</td>
        <td>13,8</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 539 000</td>
        <td>66</td>
        <td>454 975</td>
        <td>0</td>
        <td>829 547</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>393,8</td>
        <td>0,0</td>
        <td>57,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 359 055</td>
        <td>2 864 391</td>
        <td>0</td>
        <td>008,5</td>
        <td>282,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>7,8</td>
        <td>0,0</td>
        <td>284 925</td>
        <td>3 053</td>
        <td>168 026</td>
        <td>086,1</td>
        <td>272,4</td>
        <td>5 676</td>
        <td>5 442</td>
        <td>8 195</td>
        <td>167,0</td>
        <td>55,7</td>
        <td>238,4</td>
        <td>3,0</td>
        <td>771,8</td>
        <td>30,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 053</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,4</td>
        <td>567</td>
        <td>452</td>
        <td>81 230</td>
        <td>39,5</td>
        <td>6,6</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1218831</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25500</td>
        <td>157</td>
        <td>45 541 056</td>
        <td>211 735</td>
        <td>84 886 080</td>
        <td>0</td>
        <td>0</td>
        <td>4 920 686</td>
        <td>0</td>
        <td>1218831</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>34 364 592</td>
        <td>8 912 896</td>
        <td>3 211 264</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 518 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 290 128</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>317 114</td>
        <td>298 225</td>
        <td>1 211 791</td>
        <td>5 310 065</td>
        <td>1 079 466</td>
        <td>8 548 464</td>
        <td>5 286 770</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 249 504</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>1 450 000</td>
        <td>0</td>
        <td>0</td>
        <td>3 211 264</td>
        <td>79 167 488</td>
        <td>8 779 905</td>
        <td>15</td>
        <td>63 731</td>
        <td>7</td>
        <td>30 887</td>
        <td>2 651</td>
        <td>3 658</td>
        <td>992831006</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1008419329</td>
        <td>0</td>
        <td>0</td>
        <td>129538</td>
        <td>507966</td>
        <td>1</td>
        <td>0</td>
        <td>92722</td>
      </tr>
      <tr>
        <td>23:27:15.662, 27.02.2020</td>
        <td>2,4</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>101 347 248</td>
        <td>92 012 544</td>
        <td>86 290 128</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 328 320</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>437</td>
        <td>0,0</td>
        <td>36,6</td>
        <td>17</td>
        <td>57 293</td>
        <td>2 533</td>
        <td>12 374</td>
        <td>0,0</td>
        <td>13,8</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 549 253</td>
        <td>66</td>
        <td>455 065</td>
        <td>0</td>
        <td>829 848</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>394,1</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 410 468</td>
        <td>2 884 246</td>
        <td>0</td>
        <td>010,3</td>
        <td>282,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,7</td>
        <td>0,0</td>
        <td>287 123</td>
        <td>3 055</td>
        <td>168 056</td>
        <td>095,6</td>
        <td>272,9</td>
        <td>5 704</td>
        <td>5 469</td>
        <td>8 239</td>
        <td>167,0</td>
        <td>55,7</td>
        <td>239,7</td>
        <td>3,0</td>
        <td>775,7</td>
        <td>30,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 055</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,4</td>
        <td>572</td>
        <td>456</td>
        <td>81 234</td>
        <td>39,5</td>
        <td>6,7</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8234924</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>328</td>
        <td>1 270</td>
        <td>45 563 712</td>
        <td>211 735</td>
        <td>84 924 072</td>
        <td>0</td>
        <td>0</td>
        <td>4 921 956</td>
        <td>0</td>
        <td>8234924</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>43 695 832</td>
        <td>8 912 896</td>
        <td>3 211 264</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 518 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 290 128</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>317 114</td>
        <td>298 225</td>
        <td>1 211 791</td>
        <td>5 310 065</td>
        <td>1 079 466</td>
        <td>8 548 464</td>
        <td>5 286 770</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 249 504</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>1 450 000</td>
        <td>0</td>
        <td>0</td>
        <td>3 211 264</td>
        <td>79 167 488</td>
        <td>8 779 905</td>
        <td>15</td>
        <td>63 731</td>
        <td>7</td>
        <td>30 887</td>
        <td>2 651</td>
        <td>3 658</td>
        <td>973297166</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>953669800</td>
        <td>0</td>
        <td>0</td>
        <td>103544</td>
        <td>365744</td>
        <td>0</td>
        <td>0</td>
        <td>103416</td>
      </tr>
      <tr>
        <td>23:27:16.662, 27.02.2020</td>
        <td>9,4</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>110 743 488</td>
        <td>92 012 544</td>
        <td>86 290 128</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>28,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 328 320</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>438</td>
        <td>0,0</td>
        <td>36,6</td>
        <td>17</td>
        <td>57 588</td>
        <td>2 557</td>
        <td>12 428</td>
        <td>0,0</td>
        <td>13,9</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 559 514</td>
        <td>66</td>
        <td>455 155</td>
        <td>0</td>
        <td>830 149</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>397,1</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 461 946</td>
        <td>2 904 113</td>
        <td>0</td>
        <td>014,8</td>
        <td>284,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>13,6</td>
        <td>0,0</td>
        <td>289 321</td>
        <td>3 057</td>
        <td>168 086</td>
        <td>104,5</td>
        <td>272,4</td>
        <td>5 732</td>
        <td>5 496</td>
        <td>8 283</td>
        <td>166,9</td>
        <td>55,7</td>
        <td>240,8</td>
        <td>3,1</td>
        <td>786,6</td>
        <td>30,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 057</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,3</td>
        <td>576</td>
        <td>460</td>
        <td>81 238</td>
        <td>39,5</td>
        <td>6,7</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>285295045</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>735</td>
        <td>2</td>
        <td>789</td>
        <td>0</td>
        <td>0</td>
        <td>20</td>
        <td>45 578 720</td>
        <td>217 844</td>
        <td>84 957 032</td>
        <td>1</td>
        <td>277896104</td>
        <td>4 922 068</td>
        <td>2</td>
        <td>7398941</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>53 085 088</td>
        <td>8 912 896</td>
        <td>3 211 264</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 518 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 290 128</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>317 114</td>
        <td>298 225</td>
        <td>1 211 791</td>
        <td>5 310 065</td>
        <td>1 079 466</td>
        <td>8 548 464</td>
        <td>5 286 770</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 249 504</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>1 450 000</td>
        <td>0</td>
        <td>0</td>
        <td>3 211 264</td>
        <td>79 167 488</td>
        <td>8 779 905</td>
        <td>15</td>
        <td>63 731</td>
        <td>7</td>
        <td>30 887</td>
        <td>2 651</td>
        <td>3 658</td>
        <td>1017930937</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1014348023</td>
        <td>0</td>
        <td>0</td>
        <td>154833</td>
        <td>531698</td>
        <td>1</td>
        <td>0</td>
        <td>148650</td>
      </tr>
      <tr>
        <td>23:27:17.662, 27.02.2020</td>
        <td>2,9</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>120 582 328</td>
        <td>92 012 544</td>
        <td>86 290 128</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>1,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 328 320</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>439</td>
        <td>0,0</td>
        <td>36,7</td>
        <td>17</td>
        <td>57 876</td>
        <td>2 581</td>
        <td>12 482</td>
        <td>0,0</td>
        <td>13,9</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 569 774</td>
        <td>66</td>
        <td>455 245</td>
        <td>0</td>
        <td>830 450</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>399,2</td>
        <td>0,0</td>
        <td>57,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 513 398</td>
        <td>2 923 979</td>
        <td>0</td>
        <td>018,9</td>
        <td>285,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,2</td>
        <td>0,0</td>
        <td>291 519</td>
        <td>3 059</td>
        <td>168 116</td>
        <td>114,6</td>
        <td>273,0</td>
        <td>5 760</td>
        <td>5 523</td>
        <td>8 327</td>
        <td>167,0</td>
        <td>55,7</td>
        <td>241,9</td>
        <td>3,1</td>
        <td>792,5</td>
        <td>30,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 059</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,5</td>
        <td>580</td>
        <td>464</td>
        <td>81 242</td>
        <td>39,6</td>
        <td>6,7</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10457699</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>334</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>1721</td>
        <td>208</td>
        <td>45 592 992</td>
        <td>217 844</td>
        <td>84 979 048</td>
        <td>0</td>
        <td>0</td>
        <td>4 923 144</td>
        <td>3</td>
        <td>10457699</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>60 852 552</td>
        <td>8 912 896</td>
        <td>3 211 264</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 518 512</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 290 128</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>317 114</td>
        <td>298 225</td>
        <td>1 211 791</td>
        <td>5 310 065</td>
        <td>1 079 466</td>
        <td>8 548 464</td>
        <td>5 286 770</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 249 504</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>1 450 000</td>
        <td>0</td>
        <td>0</td>
        <td>3 211 264</td>
        <td>79 167 488</td>
        <td>8 779 905</td>
        <td>15</td>
        <td>63 731</td>
        <td>7</td>
        <td>30 887</td>
        <td>2 651</td>
        <td>3 658</td>
        <td>977318643</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1025810403</td>
        <td>0</td>
        <td>0</td>
        <td>63039</td>
        <td>241665</td>
        <td>1</td>
        <td>0</td>
        <td>64301</td>
      </tr>
      <tr>
        <td>23:27:18.663, 27.02.2020</td>
        <td>2,2</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>130 372 976</td>
        <td>92 012 544</td>
        <td>86 290 128</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>1,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 204 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>440</td>
        <td>0,0</td>
        <td>36,7</td>
        <td>17</td>
        <td>58 159</td>
        <td>2 605</td>
        <td>12 536</td>
        <td>0,0</td>
        <td>13,9</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 580 033</td>
        <td>66</td>
        <td>455 335</td>
        <td>0</td>
        <td>830 751</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>400,0</td>
        <td>0,0</td>
        <td>57,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 564 829</td>
        <td>2 943 844</td>
        <td>0</td>
        <td>020,9</td>
        <td>286,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>7,1</td>
        <td>0,0</td>
        <td>293 717</td>
        <td>3 061</td>
        <td>168 146</td>
        <td>119,2</td>
        <td>272,7</td>
        <td>5 788</td>
        <td>5 550</td>
        <td>8 371</td>
        <td>167,0</td>
        <td>55,7</td>
        <td>242,6</td>
        <td>3,1</td>
        <td>798,5</td>
        <td>30,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 061</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,5</td>
        <td>584</td>
        <td>468</td>
        <td>81 246</td>
        <td>39,6</td>
        <td>6,8</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10525974</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1901</td>
        <td>89</td>
        <td>45 611 872</td>
        <td>217 844</td>
        <td>85 007 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 924 222</td>
        <td>5</td>
        <td>10525974</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>7652817143</td>
        <td>7655749113</td>
        <td>8902078</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>2 160 544</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>3 276 800</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 551 280</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 295 848</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>295</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>288 681</td>
        <td>293 992</td>
        <td>1 170 659</td>
        <td>5 106 738</td>
        <td>1 154 513</td>
        <td>8 570 279</td>
        <td>5 085 773</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 048 480</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>3 276 800</td>
        <td>80 216 064</td>
        <td>8 913 863</td>
        <td>30</td>
        <td>110 016</td>
        <td>10</td>
        <td>39 307</td>
        <td>562</td>
        <td>1 900</td>
        <td>1036535360</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1263131859</td>
        <td>0</td>
        <td>0</td>
        <td>388137</td>
        <td>10090810</td>
        <td>2</td>
        <td>0</td>
        <td>9167666</td>
      </tr>
      <tr>
        <td>23:27:19.663, 27.02.2020</td>
        <td>3,2</td>
        <td>0,2</td>
        <td>174 587 904</td>
        <td>69 425 016</td>
        <td>92 012 544</td>
        <td>86 295 848</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 204 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>441</td>
        <td>0,0</td>
        <td>36,7</td>
        <td>17</td>
        <td>58 446</td>
        <td>2 629</td>
        <td>12 590</td>
        <td>0,0</td>
        <td>13,9</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 590 286</td>
        <td>66</td>
        <td>455 425</td>
        <td>0</td>
        <td>831 052</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>400,7</td>
        <td>0,0</td>
        <td>57,2</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 616 244</td>
        <td>2 963 699</td>
        <td>0</td>
        <td>023,3</td>
        <td>287,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>5,1</td>
        <td>0,0</td>
        <td>295 915</td>
        <td>3 063</td>
        <td>168 176</td>
        <td>121,9</td>
        <td>272,5</td>
        <td>5 816</td>
        <td>5 577</td>
        <td>8 415</td>
        <td>167,0</td>
        <td>55,8</td>
        <td>243,5</td>
        <td>3,1</td>
        <td>802,3</td>
        <td>31,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 063</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,6</td>
        <td>589</td>
        <td>472</td>
        <td>81 250</td>
        <td>39,6</td>
        <td>6,8</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3342539</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>324</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>443</td>
        <td>66</td>
        <td>45 613 632</td>
        <td>217 844</td>
        <td>85 010 496</td>
        <td>0</td>
        <td>0</td>
        <td>4 924 373</td>
        <td>2</td>
        <td>3342539</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>13 979 248</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>3 276 800</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 551 280</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 295 848</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>288 681</td>
        <td>293 992</td>
        <td>1 170 659</td>
        <td>5 106 738</td>
        <td>1 154 513</td>
        <td>8 570 279</td>
        <td>5 085 773</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 048 480</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>3 276 800</td>
        <td>80 216 064</td>
        <td>8 913 863</td>
        <td>30</td>
        <td>110 016</td>
        <td>10</td>
        <td>39 307</td>
        <td>562</td>
        <td>1 900</td>
        <td>1007275898</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>710614678</td>
        <td>0</td>
        <td>0</td>
        <td>142423</td>
        <td>396175</td>
        <td>1</td>
        <td>0</td>
        <td>95862</td>
      </tr>
      <tr>
        <td>23:27:20.663, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>79 125 592</td>
        <td>92 012 544</td>
        <td>86 295 848</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>1,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 204 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>444</td>
        <td>0,0</td>
        <td>36,7</td>
        <td>17</td>
        <td>58 733</td>
        <td>2 653</td>
        <td>12 646</td>
        <td>0,0</td>
        <td>13,9</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 600 579</td>
        <td>66</td>
        <td>455 515</td>
        <td>0</td>
        <td>831 353</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>402,9</td>
        <td>0,0</td>
        <td>57,4</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 667 753</td>
        <td>2 983 647</td>
        <td>0</td>
        <td>028,4</td>
        <td>288,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,0</td>
        <td>0,0</td>
        <td>298 113</td>
        <td>3 065</td>
        <td>168 206</td>
        <td>129,4</td>
        <td>272,8</td>
        <td>5 844</td>
        <td>5 604</td>
        <td>8 459</td>
        <td>166,9</td>
        <td>55,7</td>
        <td>244,3</td>
        <td>3,2</td>
        <td>805,9</td>
        <td>30,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 065</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,4</td>
        <td>593</td>
        <td>476</td>
        <td>81 254</td>
        <td>39,6</td>
        <td>6,8</td>
        <td>28,1</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>13361629</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>454</td>
        <td>0</td>
        <td>0</td>
        <td>204</td>
        <td>45 614 848</td>
        <td>217 844</td>
        <td>85 012 384</td>
        <td>0</td>
        <td>0</td>
        <td>4 924 577</td>
        <td>0</td>
        <td>13361629</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>22 584 192</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>3 276 800</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 551 280</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 295 848</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>288 681</td>
        <td>293 992</td>
        <td>1 170 659</td>
        <td>5 106 738</td>
        <td>1 154 513</td>
        <td>8 570 279</td>
        <td>5 085 773</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 048 480</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>3 276 800</td>
        <td>80 216 064</td>
        <td>8 913 863</td>
        <td>30</td>
        <td>110 016</td>
        <td>10</td>
        <td>39 307</td>
        <td>562</td>
        <td>1 900</td>
        <td>988757703</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>985764050</td>
        <td>0</td>
        <td>0</td>
        <td>139088</td>
        <td>510146</td>
        <td>0</td>
        <td>0</td>
        <td>141486</td>
      </tr>
      <tr>
        <td>23:27:21.663, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>88 725 896</td>
        <td>92 012 544</td>
        <td>86 295 848</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,5</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 204 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>445</td>
        <td>0,0</td>
        <td>36,7</td>
        <td>17</td>
        <td>59 016</td>
        <td>2 677</td>
        <td>12 700</td>
        <td>0,0</td>
        <td>14,0</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 610 838</td>
        <td>66</td>
        <td>455 605</td>
        <td>0</td>
        <td>831 654</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>404,0</td>
        <td>0,0</td>
        <td>57,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 719 188</td>
        <td>3 003 512</td>
        <td>0</td>
        <td>029,9</td>
        <td>289,6</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,8</td>
        <td>0,0</td>
        <td>300 312</td>
        <td>3 067</td>
        <td>168 236</td>
        <td>133,5</td>
        <td>272,5</td>
        <td>5 872</td>
        <td>5 631</td>
        <td>8 503</td>
        <td>167,0</td>
        <td>55,8</td>
        <td>245,7</td>
        <td>3,2</td>
        <td>811,7</td>
        <td>31,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 067</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,6</td>
        <td>597</td>
        <td>480</td>
        <td>81 258</td>
        <td>39,7</td>
        <td>6,9</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5866171</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>441</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>511</td>
        <td>19</td>
        <td>45 624 064</td>
        <td>217 844</td>
        <td>85 028 048</td>
        <td>0</td>
        <td>0</td>
        <td>4 925 207</td>
        <td>2</td>
        <td>5866171</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>32 906 560</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>3 276 800</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 551 280</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 295 848</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>288 681</td>
        <td>293 992</td>
        <td>1 170 659</td>
        <td>5 106 738</td>
        <td>1 154 513</td>
        <td>8 570 279</td>
        <td>5 085 773</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 048 480</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>3 276 800</td>
        <td>80 216 064</td>
        <td>8 913 863</td>
        <td>30</td>
        <td>110 016</td>
        <td>10</td>
        <td>39 307</td>
        <td>562</td>
        <td>1 900</td>
        <td>1009423960</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1006900411</td>
        <td>0</td>
        <td>0</td>
        <td>206046</td>
        <td>469408</td>
        <td>1</td>
        <td>0</td>
        <td>98630</td>
      </tr>
      <tr>
        <td>23:27:22.664, 27.02.2020</td>
        <td>2,9</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>98 328 424</td>
        <td>92 012 544</td>
        <td>86 295 848</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>0,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 204 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>446</td>
        <td>0,0</td>
        <td>36,7</td>
        <td>17</td>
        <td>59 301</td>
        <td>2 701</td>
        <td>12 754</td>
        <td>0,0</td>
        <td>14,0</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 621 097</td>
        <td>66</td>
        <td>455 695</td>
        <td>0</td>
        <td>831 955</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>405,0</td>
        <td>0,0</td>
        <td>57,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 770 619</td>
        <td>3 023 377</td>
        <td>0</td>
        <td>034,1</td>
        <td>291,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>18</td>
        <td>0</td>
        <td>16</td>
        <td>6,5</td>
        <td>0,0</td>
        <td>302 510</td>
        <td>3 069</td>
        <td>168 266</td>
        <td>139,5</td>
        <td>272,6</td>
        <td>5 900</td>
        <td>5 658</td>
        <td>8 547</td>
        <td>167,0</td>
        <td>55,8</td>
        <td>247,1</td>
        <td>3,2</td>
        <td>816,2</td>
        <td>31,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 069</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,7</td>
        <td>601</td>
        <td>484</td>
        <td>81 262</td>
        <td>39,7</td>
        <td>6,9</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4141594</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>513</td>
        <td>0</td>
        <td>0</td>
        <td>87</td>
        <td>45 624 480</td>
        <td>217 844</td>
        <td>85 028 944</td>
        <td>0</td>
        <td>0</td>
        <td>4 925 294</td>
        <td>1</td>
        <td>4141594</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>43 125 480</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>3 276 800</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 551 280</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 295 848</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>288 681</td>
        <td>293 992</td>
        <td>1 170 659</td>
        <td>5 106 738</td>
        <td>1 154 513</td>
        <td>8 570 279</td>
        <td>5 085 773</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 048 480</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>3 276 800</td>
        <td>80 216 064</td>
        <td>8 913 863</td>
        <td>30</td>
        <td>110 016</td>
        <td>10</td>
        <td>39 307</td>
        <td>562</td>
        <td>1 900</td>
        <td>1003747220</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1000825162</td>
        <td>0</td>
        <td>0</td>
        <td>90080</td>
        <td>555453</td>
        <td>1</td>
        <td>0</td>
        <td>185052</td>
      </tr>
      <tr>
        <td>23:27:23.670, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>108 252 080</td>
        <td>92 012 544</td>
        <td>86 295 848</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>1,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 204 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>447</td>
        <td>0,0</td>
        <td>36,8</td>
        <td>17</td>
        <td>59 584</td>
        <td>2 725</td>
        <td>12 808</td>
        <td>0,0</td>
        <td>14,0</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 631 356</td>
        <td>66</td>
        <td>455 785</td>
        <td>0</td>
        <td>832 256</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>407,5</td>
        <td>0,0</td>
        <td>57,4</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 822 044</td>
        <td>3 043 242</td>
        <td>0</td>
        <td>038,2</td>
        <td>292,6</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>17</td>
        <td>0</td>
        <td>15</td>
        <td>6,4</td>
        <td>0,0</td>
        <td>304 708</td>
        <td>3 071</td>
        <td>168 296</td>
        <td>149,7</td>
        <td>273,1</td>
        <td>5 928</td>
        <td>5 685</td>
        <td>8 591</td>
        <td>166,9</td>
        <td>55,8</td>
        <td>248,1</td>
        <td>3,3</td>
        <td>820,0</td>
        <td>31,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 071</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,5</td>
        <td>606</td>
        <td>488</td>
        <td>81 266</td>
        <td>39,7</td>
        <td>7,0</td>
        <td>28,2</td>
        <td>98</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,1</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,2</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>12431382</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>610</td>
        <td>0</td>
        <td>466</td>
        <td>1</td>
        <td>663</td>
        <td>415</td>
        <td>45 632 800</td>
        <td>217 844</td>
        <td>85 041 968</td>
        <td>0</td>
        <td>0</td>
        <td>4 925 901</td>
        <td>3</td>
        <td>12431382</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>52 657 648</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>3 276 800</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 551 280</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 295 848</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>288 681</td>
        <td>293 992</td>
        <td>1 170 659</td>
        <td>5 106 738</td>
        <td>1 154 513</td>
        <td>8 570 279</td>
        <td>5 085 773</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 048 480</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>3 276 800</td>
        <td>80 216 064</td>
        <td>8 913 863</td>
        <td>30</td>
        <td>110 016</td>
        <td>10</td>
        <td>39 307</td>
        <td>562</td>
        <td>1 900</td>
        <td>1000881751</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>998369027</td>
        <td>0</td>
        <td>0</td>
        <td>46728</td>
        <td>288309</td>
        <td>0</td>
        <td>0</td>
        <td>87941</td>
      </tr>
      <tr>
        <td>23:27:24.664, 27.02.2020</td>
        <td>11,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>119 366 192</td>
        <td>92 012 544</td>
        <td>86 295 848</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>32,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 204 864</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>449</td>
        <td>0,0</td>
        <td>37,4</td>
        <td>17</td>
        <td>59 900</td>
        <td>2 749</td>
        <td>13 257</td>
        <td>0,0</td>
        <td>14,0</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 100</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 641 972</td>
        <td>66</td>
        <td>455 875</td>
        <td>0</td>
        <td>832 559</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>407,4</td>
        <td>0,0</td>
        <td>57,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 883 952</td>
        <td>3 064 015</td>
        <td>0</td>
        <td>040,0</td>
        <td>293,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>66</td>
        <td>0</td>
        <td>15</td>
        <td>36,6</td>
        <td>0,0</td>
        <td>306 906</td>
        <td>3 073</td>
        <td>168 326</td>
        <td>154,7</td>
        <td>272,9</td>
        <td>5 956</td>
        <td>5 712</td>
        <td>8 635</td>
        <td>167,0</td>
        <td>55,8</td>
        <td>249,4</td>
        <td>3,3</td>
        <td>827,0</td>
        <td>31,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 073</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,8</td>
        <td>610</td>
        <td>492</td>
        <td>81 273</td>
        <td>39,8</td>
        <td>7,0</td>
        <td>28,2</td>
        <td>107</td>
        <td>8</td>
        <td>0</td>
        <td>134</td>
        <td>902</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>328476901</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1619</td>
        <td>3</td>
        <td>2177</td>
        <td>19</td>
        <td>4980</td>
        <td>27</td>
        <td>45 780 352</td>
        <td>220 555</td>
        <td>85 296 544</td>
        <td>1</td>
        <td>160289649</td>
        <td>4 934 177</td>
        <td>27</td>
        <td>168187252</td>
        <td>0</td>
        <td>28</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>59 538 112</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>3 276 800</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 551 280</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 295 848</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>288 681</td>
        <td>293 992</td>
        <td>1 170 659</td>
        <td>5 106 738</td>
        <td>1 154 513</td>
        <td>8 570 279</td>
        <td>5 085 773</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 048 480</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>3 276 800</td>
        <td>80 216 064</td>
        <td>8 913 863</td>
        <td>30</td>
        <td>110 016</td>
        <td>10</td>
        <td>39 307</td>
        <td>562</td>
        <td>1 900</td>
        <td>968725870</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>14</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1038248880</td>
        <td>0</td>
        <td>0</td>
        <td>317090</td>
        <td>1010392</td>
        <td>3</td>
        <td>0</td>
        <td>122018</td>
      </tr>
      <tr>
        <td>23:27:25.847, 27.02.2020</td>
        <td>18,8</td>
        <td>0,1</td>
        <td>173 539 328</td>
        <td>93 502 272</td>
        <td>92 012 544</td>
        <td>86 312 728</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>28,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>69 869 272</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>457</td>
        <td>0,0</td>
        <td>37,5</td>
        <td>22</td>
        <td>60 681</td>
        <td>2 899</td>
        <td>14 614</td>
        <td>0,0</td>
        <td>14,2</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 655 207</td>
        <td>66</td>
        <td>455 969</td>
        <td>0</td>
        <td>834 127</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>410,4</td>
        <td>0,0</td>
        <td>57,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>8 953 919</td>
        <td>3 086 854</td>
        <td>0</td>
        <td>045,7</td>
        <td>294,6</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>103</td>
        <td>0</td>
        <td>16</td>
        <td>21,6</td>
        <td>0,0</td>
        <td>309 254</td>
        <td>3 075</td>
        <td>168 980</td>
        <td>170,2</td>
        <td>272,8</td>
        <td>5 992</td>
        <td>5 749</td>
        <td>8 683</td>
        <td>168,0</td>
        <td>57,2</td>
        <td>253,2</td>
        <td>3,3</td>
        <td>831,3</td>
        <td>31,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>3 099</td>
        <td>186</td>
        <td>4 075</td>
        <td>31,3</td>
        <td>36,0</td>
        <td>194,8</td>
        <td>614</td>
        <td>496</td>
        <td>81 277</td>
        <td>39,8</td>
        <td>7,1</td>
        <td>28,2</td>
        <td>152</td>
        <td>8</td>
        <td>0</td>
        <td>144</td>
        <td>916</td>
        <td>3</td>
        <td>0</td>
        <td>5</td>
        <td>5,6</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>12,9</td>
        <td>124,4</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>283221337</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>4089</td>
        <td>7</td>
        <td>2662</td>
        <td>33</td>
        <td>12521</td>
        <td>19</td>
        <td>45 932 512</td>
        <td>220 555</td>
        <td>85 571 344</td>
        <td>0</td>
        <td>0</td>
        <td>4 948 673</td>
        <td>51</td>
        <td>283221337</td>
        <td>0</td>
        <td>51</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>77953</td>
        <td>77754</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>77754</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>5474127275</td>
        <td>5471888829</td>
        <td>5336285</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>88 080 384</td>
        <td>36 812 416</td>
        <td>7 864 320</td>
        <td>4 645 160</td>
        <td>8 388 608</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>56 616 816</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 312 728</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>266 368</td>
        <td>284 674</td>
        <td>1 120 393</td>
        <td>5 060 580</td>
        <td>1 080 604</td>
        <td>8 302 393</td>
        <td>5 041 712</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 004 448</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>65 536</td>
        <td>0</td>
        <td>0</td>
        <td>4 645 160</td>
        <td>80 216 064</td>
        <td>8 783 131</td>
        <td>52</td>
        <td>63 313</td>
        <td>36</td>
        <td>30 550</td>
        <td>421</td>
        <td>1 798</td>
        <td>1007004101</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>4</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>813998698</td>
        <td>0</td>
        <td>0</td>
        <td>236180</td>
        <td>6307412</td>
        <td>2</td>
        <td>0</td>
        <td>5571793</td>
      </tr>
      <tr>
        <td>23:27:26.935, 27.02.2020</td>
        <td>32,2</td>
        <td>0,2</td>
        <td>174 587 904</td>
        <td>65 172 456</td>
        <td>92 012 544</td>
        <td>86 321 168</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>40,9</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>73 710 624</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>460</td>
        <td>0,0</td>
        <td>37,5</td>
        <td>22</td>
        <td>64 884</td>
        <td>2 923</td>
        <td>14 670</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 666 793</td>
        <td>66</td>
        <td>643 676</td>
        <td>0</td>
        <td>1 065 615</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>411,5</td>
        <td>0,0</td>
        <td>73,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>9 249 304</td>
        <td>3 108 099</td>
        <td>0</td>
        <td>062,8</td>
        <td>296,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>450</td>
        <td>0</td>
        <td>832</td>
        <td>94,6</td>
        <td>0,0</td>
        <td>320 315</td>
        <td>4 306</td>
        <td>198 830</td>
        <td>210,1</td>
        <td>285,4</td>
        <td>6 401</td>
        <td>6 141</td>
        <td>9 238</td>
        <td>179,8</td>
        <td>59,4</td>
        <td>272,2</td>
        <td>3,5</td>
        <td>871,4</td>
        <td>37,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>4 370</td>
        <td>216</td>
        <td>5 036</td>
        <td>38,2</td>
        <td>36,2</td>
        <td>200,4</td>
        <td>628</td>
        <td>534</td>
        <td>97 492</td>
        <td>40,7</td>
        <td>7,4</td>
        <td>30,5</td>
        <td>153</td>
        <td>8</td>
        <td>0</td>
        <td>188</td>
        <td>1 020</td>
        <td>17</td>
        <td>0</td>
        <td>5</td>
        <td>6,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>15,6</td>
        <td>143,6</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>405284433</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>3347</td>
        <td>11</td>
        <td>4399</td>
        <td>9</td>
        <td>2410</td>
        <td>571</td>
        <td>46 035 040</td>
        <td>221 202</td>
        <td>85 770 296</td>
        <td>1</td>
        <td>22986326</td>
        <td>4 964 739</td>
        <td>29</td>
        <td>382298107</td>
        <td>0</td>
        <td>31</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>1488284920</td>
        <td>1488730103</td>
        <td>11914056</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>8 869 976</td>
        <td>8 912 896</td>
        <td>4 325 928</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 059 184</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 321 168</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>255 820</td>
        <td>265 976</td>
        <td>1 053 749</td>
        <td>5 139 879</td>
        <td>1 094 172</td>
        <td>8 422 396</td>
        <td>5 124 596</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 827 456</td>
        <td>102 760 448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 087 328</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 325 928</td>
        <td>80 216 064</td>
        <td>8 954 587</td>
        <td>5</td>
        <td>94 893</td>
        <td>4</td>
        <td>30 231</td>
        <td>619</td>
        <td>1 192</td>
        <td>1008906863</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>9</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>15</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1315231123</td>
        <td>0</td>
        <td>0</td>
        <td>205367</td>
        <td>12781334</td>
        <td>2</td>
        <td>0</td>
        <td>12114023</td>
      </tr>
      <tr>
        <td>23:27:27.710, 27.02.2020</td>
        <td>25,9</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>129 268 312</td>
        <td>92 012 544</td>
        <td>86 321 168</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>20,5</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>73 710 624</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>463</td>
        <td>0,0</td>
        <td>37,5</td>
        <td>22</td>
        <td>69 317</td>
        <td>2 947</td>
        <td>14 726</td>
        <td>0,0</td>
        <td>14,7</td>
        <td>0,0</td>
        <td>14,3</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 678 945</td>
        <td>66</td>
        <td>1 047 935</td>
        <td>0</td>
        <td>1 472 615</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>411,6</td>
        <td>0,0</td>
        <td>108,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>9 516 306</td>
        <td>3 129 906</td>
        <td>0</td>
        <td>075,0</td>
        <td>296,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>1 513</td>
        <td>0</td>
        <td>1 116</td>
        <td>101,8</td>
        <td>0,0</td>
        <td>341 948</td>
        <td>5 398</td>
        <td>210 062</td>
        <td>255,6</td>
        <td>286,8</td>
        <td>6 401</td>
        <td>6 141</td>
        <td>9 238</td>
        <td>179,8</td>
        <td>59,4</td>
        <td>272,2</td>
        <td>3,5</td>
        <td>871,4</td>
        <td>37,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>4 370</td>
        <td>216</td>
        <td>5 036</td>
        <td>38,2</td>
        <td>36,2</td>
        <td>200,4</td>
        <td>628</td>
        <td>534</td>
        <td>97 492</td>
        <td>40,7</td>
        <td>7,4</td>
        <td>30,5</td>
        <td>153</td>
        <td>8</td>
        <td>0</td>
        <td>188</td>
        <td>1 020</td>
        <td>17</td>
        <td>0</td>
        <td>5</td>
        <td>6,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>15,6</td>
        <td>143,6</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>209380509</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1648</td>
        <td>3</td>
        <td>1593</td>
        <td>17</td>
        <td>4269</td>
        <td>63</td>
        <td>46 098 112</td>
        <td>221 202</td>
        <td>85 897 432</td>
        <td>0</td>
        <td>0</td>
        <td>4 972 890</td>
        <td>26</td>
        <td>209380509</td>
        <td>0</td>
        <td>26</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>1168190112</td>
        <td>1168382335</td>
        <td>9180106</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>88 080 384</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>0</td>
        <td>4 718 592</td>
        <td>4 325 928</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 083 760</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 327 080</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>232 697</td>
        <td>260 188</td>
        <td>1 013 264</td>
        <td>5 058 484</td>
        <td>1 058 010</td>
        <td>8 232 517</td>
        <td>5 044 729</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>71 303 168</td>
        <td>102 236 160</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 007 456</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 827 456</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 325 928</td>
        <td>80 216 064</td>
        <td>8 911 558</td>
        <td>118</td>
        <td>77 741</td>
        <td>117</td>
        <td>32 592</td>
        <td>578</td>
        <td>1 213</td>
        <td>984394841</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>9</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>15</td>
        <td>18</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1158449284</td>
        <td>0</td>
        <td>0</td>
        <td>209435</td>
        <td>9926655</td>
        <td>2</td>
        <td>0</td>
        <td>9352601</td>
      </tr>
      <tr>
        <td>23:27:28.791, 27.02.2020</td>
        <td>21,5</td>
        <td>0,1</td>
        <td>173 539 328</td>
        <td>125 032 856</td>
        <td>92 012 544</td>
        <td>86 327 080</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>31,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 278 592</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>465</td>
        <td>0,0</td>
        <td>37,6</td>
        <td>22</td>
        <td>73 515</td>
        <td>2 971</td>
        <td>14 781</td>
        <td>0,0</td>
        <td>15,0</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 692 935</td>
        <td>66</td>
        <td>1 206 369</td>
        <td>0</td>
        <td>1 635 265</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>414,4</td>
        <td>0,0</td>
        <td>122,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>9 811 293</td>
        <td>3 153 545</td>
        <td>0</td>
        <td>092,5</td>
        <td>298,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>459</td>
        <td>0</td>
        <td>440</td>
        <td>84,3</td>
        <td>0,0</td>
        <td>366 301</td>
        <td>5 824</td>
        <td>214 464</td>
        <td>317,3</td>
        <td>287,7</td>
        <td>6 761</td>
        <td>6 459</td>
        <td>9 690</td>
        <td>180,9</td>
        <td>59,6</td>
        <td>276,2</td>
        <td>3,6</td>
        <td>924,2</td>
        <td>39,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>4 881</td>
        <td>216</td>
        <td>5 272</td>
        <td>40,8</td>
        <td>36,2</td>
        <td>201,3</td>
        <td>644</td>
        <td>542</td>
        <td>99 644</td>
        <td>43,6</td>
        <td>7,4</td>
        <td>30,7</td>
        <td>153</td>
        <td>8</td>
        <td>0</td>
        <td>188</td>
        <td>1 022</td>
        <td>17</td>
        <td>0</td>
        <td>5</td>
        <td>5,9</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>15,6</td>
        <td>144,8</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>318029448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>2251</td>
        <td>5</td>
        <td>2701</td>
        <td>4</td>
        <td>18649</td>
        <td>1 206</td>
        <td>46 152 416</td>
        <td>223 845</td>
        <td>86 005 312</td>
        <td>0</td>
        <td>105342659</td>
        <td>4 979 499</td>
        <td>16</td>
        <td>212686788</td>
        <td>0</td>
        <td>17</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>1009714454</td>
        <td>1007662842</td>
        <td>4446034</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>4 472 984</td>
        <td>8 388 608</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 124 720</td>
        <td>92 012 544</td>
        <td>1 151 336 448</td>
        <td>86 336 080</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>213 525</td>
        <td>251 424</td>
        <td>967 800</td>
        <td>4 999 934</td>
        <td>1 004 904</td>
        <td>8 014 649</td>
        <td>4 987 555</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>74 448 896</td>
        <td>105 381 888</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>298 950 272</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>71 303 168</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>40 960</td>
        <td>0</td>
        <td>0</td>
        <td>4 472 984</td>
        <td>79 691 776</td>
        <td>8 912 803</td>
        <td>3</td>
        <td>51 297</td>
        <td>2</td>
        <td>30 817</td>
        <td>402</td>
        <td>1 216</td>
        <td>1022485324</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1002501537</td>
        <td>0</td>
        <td>0</td>
        <td>175433</td>
        <td>5168782</td>
        <td>1</td>
        <td>0</td>
        <td>4648205</td>
      </tr>
      <tr>
        <td>23:27:29.732, 27.02.2020</td>
        <td>25,7</td>
        <td>0,2</td>
        <td>173 539 328</td>
        <td>74 918 896</td>
        <td>92 274 688</td>
        <td>86 343 496</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>22,4</td>
        <td>0</td>
        <td>2</td>
        <td>15 312 968</td>
        <td>71 278 592</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>468</td>
        <td>0,0</td>
        <td>37,6</td>
        <td>22</td>
        <td>77 563</td>
        <td>2 995</td>
        <td>14 837</td>
        <td>0,0</td>
        <td>15,2</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 705 077</td>
        <td>66</td>
        <td>1 468 579</td>
        <td>0</td>
        <td>1 900 216</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>414,1</td>
        <td>0,0</td>
        <td>149,0</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 045 884</td>
        <td>3 175 342</td>
        <td>0</td>
        <td>101,5</td>
        <td>298,2</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>880</td>
        <td>0</td>
        <td>1 284</td>
        <td>92,5</td>
        <td>0,0</td>
        <td>383 428</td>
        <td>7 090</td>
        <td>221 288</td>
        <td>353,2</td>
        <td>289,5</td>
        <td>7 003</td>
        <td>6 681</td>
        <td>9 988</td>
        <td>181,1</td>
        <td>59,8</td>
        <td>276,5</td>
        <td>3,7</td>
        <td>972,1</td>
        <td>40,8</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5 156</td>
        <td>216</td>
        <td>5 621</td>
        <td>42,4</td>
        <td>36,2</td>
        <td>203,6</td>
        <td>654</td>
        <td>544</td>
        <td>100 740</td>
        <td>44,3</td>
        <td>7,4</td>
        <td>30,9</td>
        <td>153</td>
        <td>8</td>
        <td>0</td>
        <td>188</td>
        <td>1 052</td>
        <td>17</td>
        <td>0</td>
        <td>5</td>
        <td>6,0</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>15,6</td>
        <td>145,4</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>223362338</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1541</td>
        <td>4</td>
        <td>1399</td>
        <td>8</td>
        <td>3051</td>
        <td>2 643</td>
        <td>46 212 320</td>
        <td>226 488</td>
        <td>86 120 888</td>
        <td>1</td>
        <td>84970604</td>
        <td>4 984 500</td>
        <td>14</td>
        <td>138391733</td>
        <td>0</td>
        <td>15</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>703505089</td>
        <td>703566860</td>
        <td>5144273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>88 080 384</td>
        <td>13 296 616</td>
        <td>7 864 320</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>4 472 984</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 149 296</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 343 496</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>194 632</td>
        <td>243 286</td>
        <td>924 491</td>
        <td>4 947 239</td>
        <td>951 839</td>
        <td>7 802 759</td>
        <td>4 936 098</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>7 864 320</td>
        <td>72 351 744</td>
        <td>103 284 736</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>298 898 816</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>74 448 896</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 472 984</td>
        <td>79 691 776</td>
        <td>8 926 794</td>
        <td>4</td>
        <td>81 573</td>
        <td>3</td>
        <td>71 652</td>
        <td>413</td>
        <td>977</td>
        <td>955793171</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>4</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>814034156</td>
        <td>0</td>
        <td>0</td>
        <td>127916</td>
        <td>5678554</td>
        <td>2</td>
        <td>0</td>
        <td>5302243</td>
      </tr>
      <tr>
        <td>23:27:30.665, 27.02.2020</td>
        <td>20,5</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>85 366 696</td>
        <td>92 274 688</td>
        <td>86 343 496</td>
        <td>12 267</td>
        <td>0</td>
        <td>45</td>
        <td>35</td>
        <td>52,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 278 592</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>471</td>
        <td>0,0</td>
        <td>37,6</td>
        <td>22</td>
        <td>80 295</td>
        <td>3 019</td>
        <td>14 893</td>
        <td>0,0</td>
        <td>15,4</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 715 898</td>
        <td>66</td>
        <td>1 589 690</td>
        <td>0</td>
        <td>2 023 350</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>415,0</td>
        <td>0,0</td>
        <td>159,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 209 143</td>
        <td>3 195 818</td>
        <td>0</td>
        <td>111,5</td>
        <td>299,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>573</td>
        <td>0</td>
        <td>24</td>
        <td>37,8</td>
        <td>0,0</td>
        <td>392 699</td>
        <td>7 094</td>
        <td>223 092</td>
        <td>376,5</td>
        <td>289,5</td>
        <td>7 317</td>
        <td>6 968</td>
        <td>10 415</td>
        <td>181,9</td>
        <td>61,0</td>
        <td>280,8</td>
        <td>3,8</td>
        <td>017,8</td>
        <td>43,7</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5 669</td>
        <td>216</td>
        <td>6 250</td>
        <td>44,9</td>
        <td>36,2</td>
        <td>206,4</td>
        <td>662</td>
        <td>559</td>
        <td>102 736</td>
        <td>45,8</td>
        <td>7,5</td>
        <td>31,1</td>
        <td>153</td>
        <td>8</td>
        <td>0</td>
        <td>214</td>
        <td>1 088</td>
        <td>17</td>
        <td>0</td>
        <td>5</td>
        <td>5,9</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>15,7</td>
        <td>145,3</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>527267922</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>2632</td>
        <td>3</td>
        <td>1643</td>
        <td>8</td>
        <td>3537</td>
        <td>13</td>
        <td>46 264 768</td>
        <td>226 488</td>
        <td>86 236 368</td>
        <td>0</td>
        <td>0</td>
        <td>4 997 593</td>
        <td>17</td>
        <td>527267922</td>
        <td>0</td>
        <td>17</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>88 080 384</td>
        <td>25 490 464</td>
        <td>7 864 320</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>4 472 984</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 149 296</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 343 496</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>194 632</td>
        <td>243 286</td>
        <td>924 491</td>
        <td>4 947 239</td>
        <td>951 839</td>
        <td>7 802 759</td>
        <td>4 936 098</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>7 864 320</td>
        <td>72 351 744</td>
        <td>103 284 736</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>298 898 816</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>74 448 896</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 472 984</td>
        <td>79 691 776</td>
        <td>8 926 794</td>
        <td>4</td>
        <td>81 573</td>
        <td>3</td>
        <td>71 652</td>
        <td>413</td>
        <td>977</td>
        <td>1018164761</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>14</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>854663126</td>
        <td>0</td>
        <td>0</td>
        <td>139038</td>
        <td>607638</td>
        <td>1</td>
        <td>0</td>
        <td>173356</td>
      </tr>
      <tr>
        <td>23:27:31.665, 27.02.2020</td>
        <td>12,2</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>98 342 432</td>
        <td>92 274 688</td>
        <td>86 343 496</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>31,7</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 278 592</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>472</td>
        <td>0,0</td>
        <td>37,6</td>
        <td>22</td>
        <td>80 650</td>
        <td>3 043</td>
        <td>14 947</td>
        <td>0,0</td>
        <td>15,4</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 726 157</td>
        <td>66</td>
        <td>1 589 791</td>
        <td>0</td>
        <td>2 024 957</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>416,5</td>
        <td>0,0</td>
        <td>159,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 266 462</td>
        <td>3 215 683</td>
        <td>0</td>
        <td>115,0</td>
        <td>300,1</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>46</td>
        <td>0</td>
        <td>16</td>
        <td>22,0</td>
        <td>0,0</td>
        <td>395 096</td>
        <td>7 096</td>
        <td>223 204</td>
        <td>400,0</td>
        <td>290,1</td>
        <td>7 504</td>
        <td>7 156</td>
        <td>10 676</td>
        <td>186,4</td>
        <td>61,7</td>
        <td>287,6</td>
        <td>3,8</td>
        <td>022,4</td>
        <td>44,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5 699</td>
        <td>246</td>
        <td>6 354</td>
        <td>45,1</td>
        <td>36,4</td>
        <td>207,5</td>
        <td>667</td>
        <td>574</td>
        <td>102 848</td>
        <td>46,0</td>
        <td>7,6</td>
        <td>31,2</td>
        <td>154</td>
        <td>8</td>
        <td>0</td>
        <td>243</td>
        <td>1 310</td>
        <td>17</td>
        <td>0</td>
        <td>5</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>15,8</td>
        <td>146,2</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>312353369</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>1087</td>
        <td>0</td>
        <td>343</td>
        <td>18</td>
        <td>7113</td>
        <td>3 039</td>
        <td>46 348 768</td>
        <td>226 488</td>
        <td>86 407 520</td>
        <td>0</td>
        <td>0</td>
        <td>5 005 887</td>
        <td>23</td>
        <td>312353369</td>
        <td>0</td>
        <td>23</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>88 080 384</td>
        <td>37 207 848</td>
        <td>7 864 320</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>4 472 984</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 149 296</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 343 496</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>194 632</td>
        <td>243 286</td>
        <td>924 491</td>
        <td>4 947 239</td>
        <td>951 839</td>
        <td>7 802 759</td>
        <td>4 936 098</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>7 864 320</td>
        <td>72 351 744</td>
        <td>103 284 736</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>298 898 816</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>74 448 896</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 472 984</td>
        <td>79 691 776</td>
        <td>8 926 794</td>
        <td>4</td>
        <td>81 573</td>
        <td>3</td>
        <td>71 652</td>
        <td>413</td>
        <td>977</td>
        <td>987919909</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1029982481</td>
        <td>0</td>
        <td>0</td>
        <td>131621</td>
        <td>743711</td>
        <td>1</td>
        <td>0</td>
        <td>118642</td>
      </tr>
      <tr>
        <td>23:27:32.665, 27.02.2020</td>
        <td>2,4</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>106 245 064</td>
        <td>92 274 688</td>
        <td>86 343 496</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>1,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 278 592</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>473</td>
        <td>0,0</td>
        <td>37,6</td>
        <td>22</td>
        <td>80 743</td>
        <td>3 067</td>
        <td>15 001</td>
        <td>0,0</td>
        <td>15,4</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 736 002</td>
        <td>66</td>
        <td>1 589 884</td>
        <td>0</td>
        <td>2 025 050</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>417,8</td>
        <td>0,0</td>
        <td>159,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 304 083</td>
        <td>3 235 138</td>
        <td>0</td>
        <td>116,6</td>
        <td>300,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>12</td>
        <td>0</td>
        <td>12</td>
        <td>0,5</td>
        <td>0,0</td>
        <td>395 096</td>
        <td>7 098</td>
        <td>223 232</td>
        <td>397,6</td>
        <td>289,8</td>
        <td>7 549</td>
        <td>7 200</td>
        <td>10 732</td>
        <td>193,9</td>
        <td>62,4</td>
        <td>295,8</td>
        <td>3,9</td>
        <td>021,5</td>
        <td>44,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5 710</td>
        <td>246</td>
        <td>6 404</td>
        <td>45,0</td>
        <td>36,3</td>
        <td>207,8</td>
        <td>672</td>
        <td>582</td>
        <td>102 854</td>
        <td>46,1</td>
        <td>8,0</td>
        <td>31,1</td>
        <td>154</td>
        <td>8</td>
        <td>0</td>
        <td>252</td>
        <td>1 312</td>
        <td>17</td>
        <td>0</td>
        <td>27</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>16,1</td>
        <td>146,1</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,3</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>10683121</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>659</td>
        <td>2</td>
        <td>966</td>
        <td>10</td>
        <td>3213</td>
        <td>1</td>
        <td>46 370 848</td>
        <td>226 488</td>
        <td>86 446 880</td>
        <td>0</td>
        <td>0</td>
        <td>5 007 130</td>
        <td>12</td>
        <td>10683121</td>
        <td>0</td>
        <td>12</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>88 080 384</td>
        <td>46 368 360</td>
        <td>7 864 320</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>4 472 984</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 149 296</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 343 496</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>194 632</td>
        <td>243 286</td>
        <td>924 491</td>
        <td>4 947 239</td>
        <td>951 839</td>
        <td>7 802 759</td>
        <td>4 936 098</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>7 864 320</td>
        <td>72 351 744</td>
        <td>103 284 736</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>298 898 816</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>74 448 896</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 472 984</td>
        <td>79 691 776</td>
        <td>8 926 794</td>
        <td>4</td>
        <td>81 573</td>
        <td>3</td>
        <td>71 652</td>
        <td>413</td>
        <td>977</td>
        <td>1024719160</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>12</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>974412438</td>
        <td>0</td>
        <td>0</td>
        <td>137056</td>
        <td>495846</td>
        <td>1</td>
        <td>0</td>
        <td>138812</td>
      </tr>
      <tr>
        <td>23:27:33.665, 27.02.2020</td>
        <td>13,4</td>
        <td>0,0</td>
        <td>173 539 328</td>
        <td>119 111 000</td>
        <td>92 274 688</td>
        <td>86 343 496</td>
        <td>12 267</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>27,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>71 278 592</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>474</td>
        <td>0,0</td>
        <td>37,6</td>
        <td>22</td>
        <td>80 915</td>
        <td>3 091</td>
        <td>15 055</td>
        <td>0,0</td>
        <td>15,5</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 745 944</td>
        <td>66</td>
        <td>1 590 059</td>
        <td>0</td>
        <td>2 025 225</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>418,8</td>
        <td>0,0</td>
        <td>159,5</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 360 986</td>
        <td>3 254 735</td>
        <td>0</td>
        <td>121,8</td>
        <td>301,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>189</td>
        <td>0</td>
        <td>15</td>
        <td>11,7</td>
        <td>0,0</td>
        <td>397 992</td>
        <td>7 100</td>
        <td>223 658</td>
        <td>409,9</td>
        <td>289,9</td>
        <td>8 024</td>
        <td>7 675</td>
        <td>11 381</td>
        <td>197,9</td>
        <td>63,1</td>
        <td>300,8</td>
        <td>4,2</td>
        <td>024,0</td>
        <td>44,1</td>
        <td>0,0</td>
        <td>34,1</td>
        <td>5 711</td>
        <td>246</td>
        <td>6 453</td>
        <td>45,1</td>
        <td>36,4</td>
        <td>208,5</td>
        <td>676</td>
        <td>592</td>
        <td>102 858</td>
        <td>46,2</td>
        <td>8,1</td>
        <td>31,2</td>
        <td>155</td>
        <td>8</td>
        <td>0</td>
        <td>252</td>
        <td>1 432</td>
        <td>17</td>
        <td>0</td>
        <td>27</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>16,2</td>
        <td>147,1</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,3</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>274938029</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>2649</td>
        <td>3</td>
        <td>2047</td>
        <td>28</td>
        <td>9145</td>
        <td>2 624</td>
        <td>46 454 304</td>
        <td>226 488</td>
        <td>86 592 016</td>
        <td>0</td>
        <td>0</td>
        <td>5 017 131</td>
        <td>38</td>
        <td>274938029</td>
        <td>0</td>
        <td>38</td>
        <td>0</td>
        <td>18 833 273</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 449 032</td>
        <td>0</td>
        <td>11 415 562</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 100 736</td>
        <td>71 303 168</td>
        <td>88 080 384</td>
        <td>58 757 840</td>
        <td>7 864 320</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>4 472 984</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 149 296</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 343 496</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>194 632</td>
        <td>243 286</td>
        <td>924 491</td>
        <td>4 947 239</td>
        <td>951 839</td>
        <td>7 802 759</td>
        <td>4 936 098</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>7 864 320</td>
        <td>72 351 744</td>
        <td>103 284 736</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>298 898 816</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>74 448 896</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>4 472 984</td>
        <td>79 691 776</td>
        <td>8 926 794</td>
        <td>4</td>
        <td>81 573</td>
        <td>3</td>
        <td>71 652</td>
        <td>413</td>
        <td>977</td>
        <td>987844442</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>985003920</td>
        <td>0</td>
        <td>0</td>
        <td>242542</td>
        <td>586238</td>
        <td>0</td>
        <td>0</td>
        <td>130768</td>
      </tr>
      <tr>
        <td>23:27:34.665, 27.02.2020</td>
        <td>20,4</td>
        <td>0,1</td>
        <td>174 587 904</td>
        <td>67 581 848</td>
        <td>92 274 688</td>
        <td>86 385 064</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>54,5</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>68 717 120</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>475</td>
        <td>0,0</td>
        <td>37,6</td>
        <td>22</td>
        <td>81 505</td>
        <td>3 115</td>
        <td>15 109</td>
        <td>0,0</td>
        <td>15,5</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 756 523</td>
        <td>66</td>
        <td>1 590 229</td>
        <td>0</td>
        <td>2 025 948</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>420,2</td>
        <td>0,0</td>
        <td>159,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 448 130</td>
        <td>3 274 969</td>
        <td>0</td>
        <td>127,7</td>
        <td>303,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>169</td>
        <td>0</td>
        <td>16</td>
        <td>36,4</td>
        <td>0,0</td>
        <td>403 561</td>
        <td>7 102</td>
        <td>223 976</td>
        <td>433,4</td>
        <td>289,6</td>
        <td>8 530</td>
        <td>8 179</td>
        <td>12 102</td>
        <td>200,6</td>
        <td>66,5</td>
        <td>309,4</td>
        <td>4,5</td>
        <td>034,4</td>
        <td>44,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5 724</td>
        <td>246</td>
        <td>6 503</td>
        <td>45,1</td>
        <td>36,3</td>
        <td>208,2</td>
        <td>680</td>
        <td>600</td>
        <td>102 864</td>
        <td>46,1</td>
        <td>8,3</td>
        <td>31,1</td>
        <td>155</td>
        <td>8</td>
        <td>0</td>
        <td>261</td>
        <td>1 550</td>
        <td>17</td>
        <td>0</td>
        <td>49</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>16,4</td>
        <td>147,2</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,4</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>543702821</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>2052</td>
        <td>4</td>
        <td>60248</td>
        <td>18</td>
        <td>7767</td>
        <td>551</td>
        <td>46 572 832</td>
        <td>228 123</td>
        <td>86 825 064</td>
        <td>0</td>
        <td>149844691</td>
        <td>5 032 159</td>
        <td>28</td>
        <td>393858129</td>
        <td>0</td>
        <td>29</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>1551075</td>
        <td>195202</td>
        <td>524</td>
        <td>393</td>
        <td>85237</td>
        <td>22285</td>
        <td>62764</td>
        <td>62524</td>
        <td>1355613</td>
        <td>34319</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>1321134</td>
        <td>1320757</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1635483</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>4941440124</td>
        <td>4943343432</td>
        <td>6749466</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 827 456</td>
        <td>89 128 960</td>
        <td>5 814 768</td>
        <td>7 864 320</td>
        <td>5 977 032</td>
        <td>8 388 608</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 247 600</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 385 064</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>673</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>185 001</td>
        <td>227 625</td>
        <td>867 878</td>
        <td>5 050 218</td>
        <td>949 337</td>
        <td>7 898 230</td>
        <td>5 040 191</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>72 876 032</td>
        <td>103 809 024</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 002 912</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 351 744</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>98 304</td>
        <td>0</td>
        <td>0</td>
        <td>5 977 032</td>
        <td>79 167 488</td>
        <td>8 629 238</td>
        <td>29</td>
        <td>62 330</td>
        <td>16</td>
        <td>21 752</td>
        <td>1 939</td>
        <td>3 835</td>
        <td>1001111485</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>18</td>
        <td>19</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1027536590</td>
        <td>0</td>
        <td>0</td>
        <td>1052550</td>
        <td>9533577</td>
        <td>5</td>
        <td>0</td>
        <td>7089276</td>
      </tr>
      <tr>
        <td>23:27:35.666, 27.02.2020</td>
        <td>6,4</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>77 883 640</td>
        <td>92 274 688</td>
        <td>86 385 064</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>4,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 717 120</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>477</td>
        <td>0,0</td>
        <td>37,6</td>
        <td>22</td>
        <td>82 029</td>
        <td>3 139</td>
        <td>15 164</td>
        <td>0,0</td>
        <td>15,5</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 766 894</td>
        <td>66</td>
        <td>1 590 329</td>
        <td>0</td>
        <td>2 026 602</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>420,7</td>
        <td>0,0</td>
        <td>159,3</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 519 205</td>
        <td>3 295 001</td>
        <td>0</td>
        <td>130,9</td>
        <td>303,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.36</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>148</td>
        <td>0</td>
        <td>16</td>
        <td>9,5</td>
        <td>0,0</td>
        <td>405 878</td>
        <td>7 104</td>
        <td>224 034</td>
        <td>444,3</td>
        <td>290,6</td>
        <td>8 975</td>
        <td>8 623</td>
        <td>12 702</td>
        <td>207,1</td>
        <td>68,8</td>
        <td>319,1</td>
        <td>4,7</td>
        <td>042,9</td>
        <td>44,2</td>
        <td>0,0</td>
        <td>34,1</td>
        <td>5 725</td>
        <td>246</td>
        <td>6 541</td>
        <td>45,2</td>
        <td>36,4</td>
        <td>208,8</td>
        <td>687</td>
        <td>620</td>
        <td>102 973</td>
        <td>46,7</td>
        <td>8,4</td>
        <td>32,0</td>
        <td>155</td>
        <td>8</td>
        <td>0</td>
        <td>303</td>
        <td>1 790</td>
        <td>17</td>
        <td>0</td>
        <td>67</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>17,8</td>
        <td>147,8</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,4</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>369</td>
        <td>0</td>
        <td>36</td>
        <td>50063573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>1482</td>
        <td>1</td>
        <td>1179</td>
        <td>3</td>
        <td>1859</td>
        <td>249</td>
        <td>46 606 208</td>
        <td>228 123</td>
        <td>86 880 864</td>
        <td>0</td>
        <td>0</td>
        <td>5 034 553</td>
        <td>7</td>
        <td>50063573</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 827 456</td>
        <td>89 128 960</td>
        <td>16 105 488</td>
        <td>7 864 320</td>
        <td>5 977 032</td>
        <td>8 388 608</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 247 600</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 385 064</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>185 001</td>
        <td>227 625</td>
        <td>867 878</td>
        <td>5 050 218</td>
        <td>949 337</td>
        <td>7 898 230</td>
        <td>5 040 191</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>72 876 032</td>
        <td>103 809 024</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 002 912</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 351 744</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>98 304</td>
        <td>0</td>
        <td>0</td>
        <td>5 977 032</td>
        <td>79 167 488</td>
        <td>8 629 238</td>
        <td>29</td>
        <td>62 330</td>
        <td>16</td>
        <td>21 752</td>
        <td>1 939</td>
        <td>3 835</td>
        <td>996746785</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>957481699</td>
        <td>0</td>
        <td>0</td>
        <td>201262</td>
        <td>709045</td>
        <td>0</td>
        <td>0</td>
        <td>208638</td>
      </tr>
      <tr>
        <td>23:27:36.998, 27.02.2020</td>
        <td>21,0</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>118 676 088</td>
        <td>92 274 688</td>
        <td>86 385 064</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>48,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>68 717 120</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>479</td>
        <td>0,0</td>
        <td>37,7</td>
        <td>22</td>
        <td>82 552</td>
        <td>3 163</td>
        <td>15 221</td>
        <td>0,0</td>
        <td>15,6</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 777 505</td>
        <td>66</td>
        <td>1 590 452</td>
        <td>0</td>
        <td>2 028 541</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>423,0</td>
        <td>0,0</td>
        <td>159,6</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 590 577</td>
        <td>3 315 314</td>
        <td>0</td>
        <td>135,7</td>
        <td>305,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>72</td>
        <td>0</td>
        <td>17</td>
        <td>20,3</td>
        <td>0,0</td>
        <td>410 444</td>
        <td>7 106</td>
        <td>224 237</td>
        <td>459,8</td>
        <td>290,3</td>
        <td>9 192</td>
        <td>8 829</td>
        <td>12 987</td>
        <td>209,7</td>
        <td>69,5</td>
        <td>327,1</td>
        <td>4,8</td>
        <td>054,1</td>
        <td>45,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5 938</td>
        <td>246</td>
        <td>6 781</td>
        <td>46,3</td>
        <td>36,4</td>
        <td>210,6</td>
        <td>697</td>
        <td>646</td>
        <td>113 630</td>
        <td>46,9</td>
        <td>8,6</td>
        <td>33,7</td>
        <td>155</td>
        <td>9</td>
        <td>0</td>
        <td>342</td>
        <td>2 016</td>
        <td>17</td>
        <td>0</td>
        <td>76</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>37,2</td>
        <td>147,8</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,6</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>498763872</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>1807</td>
        <td>2</td>
        <td>1211</td>
        <td>4</td>
        <td>1699</td>
        <td>2 240</td>
        <td>46 695 808</td>
        <td>231 413</td>
        <td>87 081 560</td>
        <td>1</td>
        <td>98227104</td>
        <td>5 048 386</td>
        <td>9</td>
        <td>400536768</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 827 456</td>
        <td>89 128 960</td>
        <td>55 451 456</td>
        <td>7 864 320</td>
        <td>5 977 032</td>
        <td>8 388 608</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 247 600</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 385 064</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>185 001</td>
        <td>227 625</td>
        <td>867 878</td>
        <td>5 050 218</td>
        <td>949 337</td>
        <td>7 898 230</td>
        <td>5 040 191</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>72 876 032</td>
        <td>103 809 024</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 002 912</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 351 744</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>98 304</td>
        <td>0</td>
        <td>0</td>
        <td>5 977 032</td>
        <td>79 167 488</td>
        <td>8 629 238</td>
        <td>29</td>
        <td>62 330</td>
        <td>16</td>
        <td>21 752</td>
        <td>1 939</td>
        <td>3 835</td>
        <td>996961004</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>8</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>763458981</td>
        <td>0</td>
        <td>0</td>
        <td>1128733</td>
        <td>1304765</td>
        <td>0</td>
        <td>0</td>
        <td>56786</td>
      </tr>
      <tr>
        <td>23:27:37.666, 27.02.2020</td>
        <td>11,1</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>133 763 064</td>
        <td>92 274 688</td>
        <td>86 385 064</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>19,4</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>70 403 064</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>480</td>
        <td>0,0</td>
        <td>37,7</td>
        <td>22</td>
        <td>84 768</td>
        <td>3 187</td>
        <td>15 275</td>
        <td>0,0</td>
        <td>15,8</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 788 609</td>
        <td>66</td>
        <td>1 590 560</td>
        <td>0</td>
        <td>2 071 103</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>423,3</td>
        <td>0,0</td>
        <td>159,4</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 829 924</td>
        <td>3 336 073</td>
        <td>0</td>
        <td>150,3</td>
        <td>306,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>53</td>
        <td>0</td>
        <td>18</td>
        <td>55,9</td>
        <td>0,0</td>
        <td>421 412</td>
        <td>7 319</td>
        <td>248 405</td>
        <td>485,7</td>
        <td>301,2</td>
        <td>9 192</td>
        <td>8 829</td>
        <td>12 987</td>
        <td>209,7</td>
        <td>69,5</td>
        <td>327,1</td>
        <td>4,8</td>
        <td>054,1</td>
        <td>45,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5 938</td>
        <td>246</td>
        <td>6 781</td>
        <td>46,3</td>
        <td>36,4</td>
        <td>210,6</td>
        <td>697</td>
        <td>646</td>
        <td>113 630</td>
        <td>46,9</td>
        <td>8,6</td>
        <td>33,7</td>
        <td>155</td>
        <td>9</td>
        <td>0</td>
        <td>342</td>
        <td>2 016</td>
        <td>17</td>
        <td>0</td>
        <td>76</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>37,2</td>
        <td>147,8</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,6</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>187333399</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>516</td>
        <td>1</td>
        <td>1070</td>
        <td>0</td>
        <td>0</td>
        <td>66</td>
        <td>46 712 992</td>
        <td>234 056</td>
        <td>87 142 648</td>
        <td>1</td>
        <td>107930909</td>
        <td>5 050 407</td>
        <td>2</td>
        <td>79402490</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>1</td>
        <td>4703583479</td>
        <td>4706119389</td>
        <td>12285658</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 827 456</td>
        <td>89 128 960</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>7 368 656</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 280 368</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 399 928</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>119</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>169 779</td>
        <td>218 562</td>
        <td>825 467</td>
        <td>5 282 062</td>
        <td>1 063 062</td>
        <td>8 471 251</td>
        <td>5 273 038</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>72 876 032</td>
        <td>103 809 024</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 235 744</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>7 368 656</td>
        <td>80 216 064</td>
        <td>8 838 910</td>
        <td>19</td>
        <td>124 483</td>
        <td>10</td>
        <td>102 929</td>
        <td>575</td>
        <td>1 469</td>
        <td>1012587008</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>1</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>20</td>
        <td>21</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1859106672</td>
        <td>0</td>
        <td>0</td>
        <td>246699</td>
        <td>13722474</td>
        <td>2</td>
        <td>0</td>
        <td>12717069</td>
      </tr>
      <tr>
        <td>23:27:38.666, 27.02.2020</td>
        <td>4,4</td>
        <td>0,1</td>
        <td>174 587 904</td>
        <td>74 508 768</td>
        <td>92 274 688</td>
        <td>86 399 928</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>1,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 403 064</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>481</td>
        <td>0,0</td>
        <td>37,7</td>
        <td>22</td>
        <td>85 067</td>
        <td>3 211</td>
        <td>15 329</td>
        <td>0,0</td>
        <td>15,8</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 798 975</td>
        <td>66</td>
        <td>1 590 650</td>
        <td>0</td>
        <td>2 071 404</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>425,4</td>
        <td>0,0</td>
        <td>159,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 881 997</td>
        <td>3 356 094</td>
        <td>0</td>
        <td>155,2</td>
        <td>307,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>51</td>
        <td>0</td>
        <td>16</td>
        <td>6,3</td>
        <td>0,0</td>
        <td>423 610</td>
        <td>7 321</td>
        <td>248 435</td>
        <td>495,3</td>
        <td>302,2</td>
        <td>9 327</td>
        <td>8 960</td>
        <td>13 216</td>
        <td>210,7</td>
        <td>69,6</td>
        <td>330,2</td>
        <td>4,8</td>
        <td>081,1</td>
        <td>45,2</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>5 938</td>
        <td>246</td>
        <td>6 789</td>
        <td>46,2</td>
        <td>36,3</td>
        <td>210,3</td>
        <td>703</td>
        <td>652</td>
        <td>115 903</td>
        <td>46,8</td>
        <td>8,7</td>
        <td>34,0</td>
        <td>155</td>
        <td>9</td>
        <td>0</td>
        <td>346</td>
        <td>2 064</td>
        <td>17</td>
        <td>0</td>
        <td>76</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>40,3</td>
        <td>147,7</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,6</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18830407</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>878</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>2917</td>
        <td>135</td>
        <td>46 733 792</td>
        <td>234 056</td>
        <td>87 174 536</td>
        <td>0</td>
        <td>0</td>
        <td>5 051 619</td>
        <td>9</td>
        <td>18830407</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 827 456</td>
        <td>89 128 960</td>
        <td>12 956 416</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>7 368 656</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 280 368</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 399 928</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>169 779</td>
        <td>218 562</td>
        <td>825 467</td>
        <td>5 282 062</td>
        <td>1 063 062</td>
        <td>8 471 251</td>
        <td>5 273 038</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>72 876 032</td>
        <td>103 809 024</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 235 744</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>7 368 656</td>
        <td>80 216 064</td>
        <td>8 838 910</td>
        <td>19</td>
        <td>124 483</td>
        <td>10</td>
        <td>102 929</td>
        <td>575</td>
        <td>1 469</td>
        <td>1013847939</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>14</td>
        <td>16</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>709772890</td>
        <td>0</td>
        <td>0</td>
        <td>236463</td>
        <td>624125</td>
        <td>1</td>
        <td>0</td>
        <td>148032</td>
      </tr>
      <tr>
        <td>23:27:39.666, 27.02.2020</td>
        <td>14,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>108 794 120</td>
        <td>92 274 688</td>
        <td>86 399 928</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>16,8</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 403 064</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>484</td>
        <td>0,0</td>
        <td>37,7</td>
        <td>22</td>
        <td>85 686</td>
        <td>3 235</td>
        <td>15 385</td>
        <td>0,0</td>
        <td>15,8</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 809 373</td>
        <td>66</td>
        <td>1 606 265</td>
        <td>0</td>
        <td>2 089 000</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>425,8</td>
        <td>0,0</td>
        <td>161,8</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>10 959 561</td>
        <td>3 376 196</td>
        <td>0</td>
        <td>157,5</td>
        <td>307,8</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>158</td>
        <td>0</td>
        <td>17</td>
        <td>40,1</td>
        <td>0,0</td>
        <td>432 477</td>
        <td>7 532</td>
        <td>251 611</td>
        <td>513,5</td>
        <td>302,2</td>
        <td>9 475</td>
        <td>9 096</td>
        <td>13 418</td>
        <td>211,7</td>
        <td>71,7</td>
        <td>334,3</td>
        <td>4,9</td>
        <td>092,1</td>
        <td>45,3</td>
        <td>0,0</td>
        <td>34,1</td>
        <td>5 938</td>
        <td>246</td>
        <td>6 791</td>
        <td>46,2</td>
        <td>36,3</td>
        <td>210,6</td>
        <td>708</td>
        <td>660</td>
        <td>115 995</td>
        <td>47,0</td>
        <td>8,8</td>
        <td>34,1</td>
        <td>155</td>
        <td>9</td>
        <td>0</td>
        <td>376</td>
        <td>2 207</td>
        <td>17</td>
        <td>0</td>
        <td>76</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>40,4</td>
        <td>148,0</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,6</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>169503360</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>2314</td>
        <td>1</td>
        <td>456</td>
        <td>10</td>
        <td>2943</td>
        <td>4</td>
        <td>46 770 944</td>
        <td>234 056</td>
        <td>87 242 280</td>
        <td>0</td>
        <td>0</td>
        <td>5 055 525</td>
        <td>13</td>
        <td>169503360</td>
        <td>0</td>
        <td>13</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 827 456</td>
        <td>89 128 960</td>
        <td>44 145 096</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>7 368 656</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 280 368</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 399 928</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>169 779</td>
        <td>218 562</td>
        <td>825 467</td>
        <td>5 282 062</td>
        <td>1 063 062</td>
        <td>8 471 251</td>
        <td>5 273 038</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>72 876 032</td>
        <td>103 809 024</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 235 744</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>7 368 656</td>
        <td>80 216 064</td>
        <td>8 838 910</td>
        <td>19</td>
        <td>124 483</td>
        <td>10</td>
        <td>102 929</td>
        <td>575</td>
        <td>1 469</td>
        <td>961585723</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>3</td>
        <td>8</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>1</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>9</td>
        <td>11</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1114263080</td>
        <td>0</td>
        <td>0</td>
        <td>184770</td>
        <td>515484</td>
        <td>2</td>
        <td>0</td>
        <td>68260</td>
      </tr>
      <tr>
        <td>23:27:40.667, 27.02.2020</td>
        <td>10,2</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>121 783 192</td>
        <td>92 274 688</td>
        <td>86 399 928</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>20,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 403 064</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>485</td>
        <td>0,0</td>
        <td>37,7</td>
        <td>22</td>
        <td>88 537</td>
        <td>3 259</td>
        <td>15 439</td>
        <td>0,0</td>
        <td>16,0</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 820 466</td>
        <td>66</td>
        <td>1 653 484</td>
        <td>0</td>
        <td>2 137 191</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>427,5</td>
        <td>0,0</td>
        <td>166,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>11 118 688</td>
        <td>3 396 936</td>
        <td>0</td>
        <td>166,2</td>
        <td>308,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>96</td>
        <td>0</td>
        <td>18</td>
        <td>34,0</td>
        <td>0,0</td>
        <td>441 376</td>
        <td>7 536</td>
        <td>251 799</td>
        <td>541,6</td>
        <td>302,0</td>
        <td>9 574</td>
        <td>9 193</td>
        <td>13 574</td>
        <td>211,6</td>
        <td>71,6</td>
        <td>335,7</td>
        <td>4,9</td>
        <td>114,7</td>
        <td>46,9</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>6 149</td>
        <td>246</td>
        <td>7 225</td>
        <td>47,6</td>
        <td>36,3</td>
        <td>212,5</td>
        <td>712</td>
        <td>666</td>
        <td>116 535</td>
        <td>47,1</td>
        <td>8,9</td>
        <td>34,2</td>
        <td>155</td>
        <td>9</td>
        <td>0</td>
        <td>388</td>
        <td>2 417</td>
        <td>17</td>
        <td>0</td>
        <td>76</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>40,4</td>
        <td>149,3</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,6</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>200983677</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>570</td>
        <td>1</td>
        <td>744</td>
        <td>7</td>
        <td>3667</td>
        <td>22</td>
        <td>46 814 112</td>
        <td>234 056</td>
        <td>87 332 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 063 470</td>
        <td>12</td>
        <td>200983677</td>
        <td>0</td>
        <td>12</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 827 456</td>
        <td>89 128 960</td>
        <td>59 952 552</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>8 388 608</td>
        <td>7 368 656</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 280 368</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 399 928</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>169 779</td>
        <td>218 562</td>
        <td>825 467</td>
        <td>5 282 062</td>
        <td>1 063 062</td>
        <td>8 471 251</td>
        <td>5 273 038</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>72 876 032</td>
        <td>103 809 024</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 235 744</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>32 768</td>
        <td>0</td>
        <td>0</td>
        <td>7 368 656</td>
        <td>80 216 064</td>
        <td>8 838 910</td>
        <td>19</td>
        <td>124 483</td>
        <td>10</td>
        <td>102 929</td>
        <td>575</td>
        <td>1 469</td>
        <td>1033507948</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>877958861</td>
        <td>0</td>
        <td>0</td>
        <td>44362</td>
        <td>291507</td>
        <td>0</td>
        <td>0</td>
        <td>92219</td>
      </tr>
      <tr>
        <td>23:27:41.667, 27.02.2020</td>
        <td>4,2</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>132 787 136</td>
        <td>92 274 688</td>
        <td>86 399 928</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>1,9</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>70 403 064</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>486</td>
        <td>0,0</td>
        <td>37,8</td>
        <td>22</td>
        <td>88 957</td>
        <td>3 283</td>
        <td>15 495</td>
        <td>0,0</td>
        <td>16,0</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 830 627</td>
        <td>66</td>
        <td>1 653 598</td>
        <td>0</td>
        <td>2 137 778</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>427,9</td>
        <td>0,0</td>
        <td>166,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>11 180 185</td>
        <td>3 416 756</td>
        <td>0</td>
        <td>170,1</td>
        <td>310,0</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>60</td>
        <td>0</td>
        <td>15</td>
        <td>12,3</td>
        <td>0,0</td>
        <td>443 787</td>
        <td>7 538</td>
        <td>252 024</td>
        <td>554,5</td>
        <td>302,3</td>
        <td>9 742</td>
        <td>9 350</td>
        <td>13 808</td>
        <td>214,3</td>
        <td>72,1</td>
        <td>341,6</td>
        <td>5,0</td>
        <td>127,9</td>
        <td>47,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>6 151</td>
        <td>246</td>
        <td>7 243</td>
        <td>47,6</td>
        <td>36,4</td>
        <td>212,9</td>
        <td>718</td>
        <td>690</td>
        <td>116 555</td>
        <td>47,2</td>
        <td>9,0</td>
        <td>34,2</td>
        <td>155</td>
        <td>9</td>
        <td>0</td>
        <td>402</td>
        <td>2 547</td>
        <td>17</td>
        <td>0</td>
        <td>85</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>40,5</td>
        <td>149,3</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,7</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>19466358</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>439</td>
        <td>0</td>
        <td>326</td>
        <td>7</td>
        <td>3152</td>
        <td>61</td>
        <td>46 843 872</td>
        <td>234 056</td>
        <td>87 380 568</td>
        <td>0</td>
        <td>0</td>
        <td>5 065 134</td>
        <td>8</td>
        <td>19466358</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>3964641388</td>
        <td>3964653914</td>
        <td>8392616</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>6 179 312</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 304 944</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 413 640</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>250</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>155 261</td>
        <td>209 773</td>
        <td>784 580</td>
        <td>5 371 787</td>
        <td>1 037 508</td>
        <td>8 484 314</td>
        <td>5 363 665</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 827 456</td>
        <td>102 760 448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 326 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>6 179 312</td>
        <td>80 740 352</td>
        <td>8 949 469</td>
        <td>58</td>
        <td>143 128</td>
        <td>33</td>
        <td>111 352</td>
        <td>2 218</td>
        <td>3 933</td>
        <td>986947895</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>7</td>
        <td>0</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>14</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1296477776</td>
        <td>0</td>
        <td>0</td>
        <td>369200</td>
        <td>9588992</td>
        <td>2</td>
        <td>0</td>
        <td>8644045</td>
      </tr>
      <tr>
        <td>23:27:42.667, 27.02.2020</td>
        <td>7,2</td>
        <td>0,2</td>
        <td>174 587 904</td>
        <td>67 954 568</td>
        <td>92 274 688</td>
        <td>86 413 640</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>6,2</td>
        <td>0</td>
        <td>1</td>
        <td>15 312 968</td>
        <td>72 992 224</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>487</td>
        <td>0,0</td>
        <td>37,7</td>
        <td>22</td>
        <td>89 044</td>
        <td>3 307</td>
        <td>15 549</td>
        <td>0,0</td>
        <td>16,0</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 840 569</td>
        <td>66</td>
        <td>1 653 691</td>
        <td>0</td>
        <td>2 137 871</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>429,7</td>
        <td>0,0</td>
        <td>166,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>11 216 837</td>
        <td>3 436 353</td>
        <td>0</td>
        <td>173,0</td>
        <td>311,3</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>161</td>
        <td>0</td>
        <td>14</td>
        <td>6,1</td>
        <td>0,0</td>
        <td>443 881</td>
        <td>7 540</td>
        <td>252 092</td>
        <td>556,4</td>
        <td>302,8</td>
        <td>9 904</td>
        <td>9 502</td>
        <td>13 991</td>
        <td>215,8</td>
        <td>74,6</td>
        <td>345,7</td>
        <td>5,1</td>
        <td>127,1</td>
        <td>47,0</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>6 154</td>
        <td>246</td>
        <td>7 270</td>
        <td>47,5</td>
        <td>36,3</td>
        <td>212,8</td>
        <td>724</td>
        <td>721</td>
        <td>116 577</td>
        <td>47,3</td>
        <td>9,2</td>
        <td>34,2</td>
        <td>157</td>
        <td>11</td>
        <td>0</td>
        <td>413</td>
        <td>2 573</td>
        <td>17</td>
        <td>0</td>
        <td>86</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>40,6</td>
        <td>149,2</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>63445282</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>1103</td>
        <td>1</td>
        <td>591</td>
        <td>7</td>
        <td>3409</td>
        <td>14</td>
        <td>46 853 920</td>
        <td>234 056</td>
        <td>87 397 840</td>
        <td>0</td>
        <td>0</td>
        <td>5 066 371</td>
        <td>10</td>
        <td>63445282</td>
        <td>0</td>
        <td>10</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>7 251 568</td>
        <td>8 912 896</td>
        <td>6 179 312</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 304 944</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 413 640</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>155 261</td>
        <td>209 773</td>
        <td>784 580</td>
        <td>5 371 787</td>
        <td>1 037 508</td>
        <td>8 484 314</td>
        <td>5 363 665</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 827 456</td>
        <td>102 760 448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 326 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>6 179 312</td>
        <td>80 740 352</td>
        <td>8 949 469</td>
        <td>58</td>
        <td>143 128</td>
        <td>33</td>
        <td>111 352</td>
        <td>2 218</td>
        <td>3 933</td>
        <td>1008891780</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>15</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>678200319</td>
        <td>0</td>
        <td>0</td>
        <td>140636</td>
        <td>411558</td>
        <td>1</td>
        <td>0</td>
        <td>102645</td>
      </tr>
      <tr>
        <td>23:27:43.668, 27.02.2020</td>
        <td>5,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>75 791 936</td>
        <td>92 274 688</td>
        <td>86 413 640</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>3,3</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>72 992 224</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>490</td>
        <td>0,0</td>
        <td>37,8</td>
        <td>22</td>
        <td>89 137</td>
        <td>3 331</td>
        <td>15 605</td>
        <td>0,0</td>
        <td>16,0</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 850 545</td>
        <td>66</td>
        <td>1 653 784</td>
        <td>0</td>
        <td>2 139 227</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>431,4</td>
        <td>0,0</td>
        <td>166,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>11 254 117</td>
        <td>3 456 033</td>
        <td>0</td>
        <td>176,2</td>
        <td>312,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>151</td>
        <td>0</td>
        <td>12</td>
        <td>4,7</td>
        <td>0,0</td>
        <td>444 029</td>
        <td>7 542</td>
        <td>252 166</td>
        <td>557,1</td>
        <td>302,8</td>
        <td>9 954</td>
        <td>9 556</td>
        <td>14 080</td>
        <td>216,8</td>
        <td>75,7</td>
        <td>347,8</td>
        <td>5,1</td>
        <td>128,3</td>
        <td>47,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>6 154</td>
        <td>246</td>
        <td>7 272</td>
        <td>47,6</td>
        <td>36,3</td>
        <td>213,1</td>
        <td>730</td>
        <td>737</td>
        <td>116 685</td>
        <td>47,4</td>
        <td>9,2</td>
        <td>34,3</td>
        <td>157</td>
        <td>11</td>
        <td>0</td>
        <td>440</td>
        <td>2 645</td>
        <td>17</td>
        <td>0</td>
        <td>86</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>40,7</td>
        <td>149,4</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>31870207</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>901</td>
        <td>6</td>
        <td>41190</td>
        <td>1</td>
        <td>46 897 472</td>
        <td>234 056</td>
        <td>87 467 800</td>
        <td>0</td>
        <td>0</td>
        <td>5 069 076</td>
        <td>8</td>
        <td>31870207</td>
        <td>0</td>
        <td>8</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>15 329 032</td>
        <td>8 912 896</td>
        <td>6 179 312</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 304 944</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 413 640</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>155 261</td>
        <td>209 773</td>
        <td>784 580</td>
        <td>5 371 787</td>
        <td>1 037 508</td>
        <td>8 484 314</td>
        <td>5 363 665</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 827 456</td>
        <td>102 760 448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 326 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>6 179 312</td>
        <td>80 740 352</td>
        <td>8 949 469</td>
        <td>58</td>
        <td>143 128</td>
        <td>33</td>
        <td>111 352</td>
        <td>2 218</td>
        <td>3 933</td>
        <td>1001668705</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>998097353</td>
        <td>0</td>
        <td>0</td>
        <td>214234</td>
        <td>554574</td>
        <td>0</td>
        <td>0</td>
        <td>115004</td>
      </tr>
      <tr>
        <td>23:27:44.668, 27.02.2020</td>
        <td>3,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>83 382 112</td>
        <td>92 274 688</td>
        <td>86 413 640</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>0,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>72 992 224</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>491</td>
        <td>0,0</td>
        <td>37,8</td>
        <td>22</td>
        <td>89 226</td>
        <td>3 355</td>
        <td>15 659</td>
        <td>0,0</td>
        <td>16,0</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,2</td>
        <td>1 860 487</td>
        <td>66</td>
        <td>1 653 879</td>
        <td>0</td>
        <td>2 139 322</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>432,4</td>
        <td>0,0</td>
        <td>166,7</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>11 290 973</td>
        <td>3 475 630</td>
        <td>0</td>
        <td>178,0</td>
        <td>313,9</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>117</td>
        <td>0</td>
        <td>13</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>444 118</td>
        <td>7 544</td>
        <td>252 222</td>
        <td>554,8</td>
        <td>302,6</td>
        <td>10 049</td>
        <td>9 651</td>
        <td>14 230</td>
        <td>216,7</td>
        <td>75,7</td>
        <td>347,7</td>
        <td>5,2</td>
        <td>127,5</td>
        <td>47,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>6 154</td>
        <td>246</td>
        <td>7 274</td>
        <td>47,5</td>
        <td>36,3</td>
        <td>212,9</td>
        <td>734</td>
        <td>755</td>
        <td>116 705</td>
        <td>47,4</td>
        <td>9,4</td>
        <td>34,3</td>
        <td>157</td>
        <td>11</td>
        <td>0</td>
        <td>486</td>
        <td>2 835</td>
        <td>17</td>
        <td>0</td>
        <td>86</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>40,9</td>
        <td>149,4</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>4755414</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>3</td>
        <td>1462</td>
        <td>84</td>
        <td>46 902 592</td>
        <td>234 056</td>
        <td>87 475 360</td>
        <td>0</td>
        <td>0</td>
        <td>5 069 438</td>
        <td>3</td>
        <td>4755414</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>23 751 840</td>
        <td>8 912 896</td>
        <td>6 179 312</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 304 944</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 413 640</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>155 261</td>
        <td>209 773</td>
        <td>784 580</td>
        <td>5 371 787</td>
        <td>1 037 508</td>
        <td>8 484 314</td>
        <td>5 363 665</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 827 456</td>
        <td>102 760 448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 326 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>6 179 312</td>
        <td>80 740 352</td>
        <td>8 949 469</td>
        <td>58</td>
        <td>143 128</td>
        <td>33</td>
        <td>111 352</td>
        <td>2 218</td>
        <td>3 933</td>
        <td>1009848198</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>2</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>12</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1029819642</td>
        <td>0</td>
        <td>0</td>
        <td>304227</td>
        <td>968049</td>
        <td>2</td>
        <td>0</td>
        <td>175701</td>
      </tr>
      <tr>
        <td>23:27:45.668, 27.02.2020</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>90 152 904</td>
        <td>92 274 688</td>
        <td>86 413 640</td>
        <td>12 268</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>2,2</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>72 992 224</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>492</td>
        <td>0,0</td>
        <td>37,9</td>
        <td>22</td>
        <td>89 309</td>
        <td>3 379</td>
        <td>15 713</td>
        <td>0,0</td>
        <td>16,1</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 870 429</td>
        <td>66</td>
        <td>1 653 968</td>
        <td>0</td>
        <td>2 139 411</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>434,3</td>
        <td>0,0</td>
        <td>166,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>11 326 341</td>
        <td>3 495 227</td>
        <td>0</td>
        <td>181,7</td>
        <td>315,4</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>23</td>
        <td>0</td>
        <td>13</td>
        <td>1,5</td>
        <td>0,0</td>
        <td>444 123</td>
        <td>7 546</td>
        <td>252 270</td>
        <td>557,7</td>
        <td>302,9</td>
        <td>10 105</td>
        <td>9 708</td>
        <td>14 320</td>
        <td>217,2</td>
        <td>75,9</td>
        <td>348,4</td>
        <td>5,2</td>
        <td>129,8</td>
        <td>47,2</td>
        <td>0,0</td>
        <td>34,1</td>
        <td>6 154</td>
        <td>246</td>
        <td>7 276</td>
        <td>47,6</td>
        <td>36,4</td>
        <td>213,4</td>
        <td>739</td>
        <td>766</td>
        <td>116 719</td>
        <td>47,5</td>
        <td>9,5</td>
        <td>34,3</td>
        <td>157</td>
        <td>11</td>
        <td>0</td>
        <td>508</td>
        <td>3 009</td>
        <td>17</td>
        <td>0</td>
        <td>86</td>
        <td>6,3</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>41,1</td>
        <td>149,8</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>21509635</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>284</td>
        <td>0</td>
        <td>566</td>
        <td>0</td>
        <td>594</td>
        <td>987</td>
        <td>46 906 368</td>
        <td>234 056</td>
        <td>87 483 384</td>
        <td>0</td>
        <td>0</td>
        <td>5 070 528</td>
        <td>2</td>
        <td>21509635</td>
        <td>0</td>
        <td>2</td>
        <td>0</td>
        <td>18 834 239</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 450 032</td>
        <td>0</td>
        <td>11 415 738</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 680 573</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>30 351 376</td>
        <td>8 912 896</td>
        <td>6 179 312</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 304 944</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 413 640</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>155 261</td>
        <td>209 773</td>
        <td>784 580</td>
        <td>5 371 787</td>
        <td>1 037 508</td>
        <td>8 484 314</td>
        <td>5 363 665</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 827 456</td>
        <td>102 760 448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 326 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>6 179 312</td>
        <td>80 740 352</td>
        <td>8 949 469</td>
        <td>58</td>
        <td>143 128</td>
        <td>33</td>
        <td>111 352</td>
        <td>2 218</td>
        <td>3 933</td>
        <td>999088566</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>6</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>10</td>
        <td>10</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>972259432</td>
        <td>0</td>
        <td>0</td>
        <td>761613</td>
        <td>1047579</td>
        <td>0</td>
        <td>0</td>
        <td>89886</td>
      </tr>
      <tr>
        <td>23:27:46.668, 27.02.2020</td>
        <td>5,2</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>98 846 440</td>
        <td>92 274 688</td>
        <td>86 413 640</td>
        <td>12 270</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>8,4</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>72 992 224</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>493</td>
        <td>0,0</td>
        <td>37,9</td>
        <td>22</td>
        <td>89 391</td>
        <td>3 403</td>
        <td>15 767</td>
        <td>0,0</td>
        <td>16,1</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 880 371</td>
        <td>66</td>
        <td>1 654 059</td>
        <td>0</td>
        <td>2 139 509</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>435,5</td>
        <td>0,0</td>
        <td>166,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>11 361 487</td>
        <td>3 514 824</td>
        <td>0</td>
        <td>184,0</td>
        <td>316,5</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.00</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>19</td>
        <td>0</td>
        <td>13</td>
        <td>2,7</td>
        <td>0,0</td>
        <td>444 197</td>
        <td>7 548</td>
        <td>252 318</td>
        <td>559,2</td>
        <td>302,9</td>
        <td>10 107</td>
        <td>9 710</td>
        <td>14 324</td>
        <td>216,8</td>
        <td>76,2</td>
        <td>348,2</td>
        <td>5,2</td>
        <td>127,6</td>
        <td>47,1</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>6 155</td>
        <td>246</td>
        <td>7 279</td>
        <td>47,5</td>
        <td>36,3</td>
        <td>213,0</td>
        <td>744</td>
        <td>770</td>
        <td>116 728</td>
        <td>47,9</td>
        <td>9,5</td>
        <td>34,3</td>
        <td>157</td>
        <td>11</td>
        <td>0</td>
        <td>508</td>
        <td>3 009</td>
        <td>17</td>
        <td>0</td>
        <td>86</td>
        <td>6,2</td>
        <td>1,4</td>
        <td>0,0</td>
        <td>41,0</td>
        <td>149,5</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,8</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>84571721</td>
        <td>2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>623</td>
        <td>2</td>
        <td>1401</td>
        <td>10</td>
        <td>4408</td>
        <td>1 470</td>
        <td>46 931 872</td>
        <td>234 056</td>
        <td>87 527 416</td>
        <td>0</td>
        <td>0</td>
        <td>5 073 506</td>
        <td>13</td>
        <td>84571721</td>
        <td>0</td>
        <td>13</td>
        <td>0</td>
        <td>18 835 428</td>
        <td>2</td>
        <td>3371015</td>
        <td>387119</td>
        <td>1991</td>
        <td>1532</td>
        <td>264407</td>
        <td>154848</td>
        <td>108523</td>
        <td>107803</td>
        <td>2982616</td>
        <td>30310</td>
        <td>2</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>2</td>
        <td>2</td>
        <td>0</td>
        <td>32 457 280</td>
        <td>42584</td>
        <td>11 416 266</td>
        <td>0</td>
        <td>6347609</td>
        <td>6346389</td>
        <td>644</td>
        <td>0</td>
        <td>0</td>
        <td>15 681 388</td>
        <td>3462495</td>
        <td>0</td>
        <td>0</td>
        <td>7070189</td>
        <td>211 824</td>
        <td>2</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>35 362 184</td>
        <td>8 912 896</td>
        <td>6 179 312</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 304 944</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 413 640</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>155 261</td>
        <td>209 773</td>
        <td>784 580</td>
        <td>5 371 787</td>
        <td>1 037 508</td>
        <td>8 484 314</td>
        <td>5 363 665</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 827 456</td>
        <td>102 760 448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 326 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>6 179 312</td>
        <td>80 740 352</td>
        <td>8 949 469</td>
        <td>58</td>
        <td>143 128</td>
        <td>33</td>
        <td>111 352</td>
        <td>2 218</td>
        <td>3 933</td>
        <td>963627367</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>0</td>
        <td>3</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>13</td>
        <td>13</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1010812256</td>
        <td>0</td>
        <td>0</td>
        <td>176109</td>
        <td>529543</td>
        <td>1</td>
        <td>0</td>
        <td>146400</td>
      </tr>
      <tr>
        <td>23:27:47.669, 27.02.2020</td>
        <td>3,2</td>
        <td>0,0</td>
        <td>174 587 904</td>
        <td>105 721 496</td>
        <td>92 274 688</td>
        <td>86 413 640</td>
        <td>12 270</td>
        <td>0</td>
        <td>46</td>
        <td>36</td>
        <td>0,0</td>
        <td>0</td>
        <td>0</td>
        <td>15 312 968</td>
        <td>72 992 224</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>108 959</td>
        <td>0</td>
        <td>108 959</td>
        <td>1</td>
        <td>494</td>
        <td>0,0</td>
        <td>37,9</td>
        <td>22</td>
        <td>89 482</td>
        <td>3 427</td>
        <td>15 823</td>
        <td>0,0</td>
        <td>16,1</td>
        <td>0,0</td>
        <td>14,4</td>
        <td>6 602</td>
        <td>1 150</td>
        <td>1,1</td>
        <td>4,3</td>
        <td>1 890 316</td>
        <td>66</td>
        <td>1 654 160</td>
        <td>0</td>
        <td>2 139 660</td>
        <td>0</td>
        <td>14</td>
        <td>0</td>
        <td>437,0</td>
        <td>0,0</td>
        <td>166,9</td>
        <td>0,0</td>
        <td>0,1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>11 399 343</td>
        <td>3 534 424</td>
        <td>0</td>
        <td>185,1</td>
        <td>317,7</td>
        <td>0,0</td>
        <td>0</td>
        <td>26</td>
        <td>1</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>0,0</td>
        <td>1 048 576</td>
        <td>199</td>
        <td>0.00</td>
        <td>0.72</td>
        <td>0.19</td>
        <td>0.00</td>
        <td>19</td>
        <td>0</td>
        <td>12</td>
        <td>4,9</td>
        <td>0,0</td>
        <td>444 293</td>
        <td>7 550</td>
        <td>252 450</td>
        <td>558,0</td>
        <td>302,6</td>
        <td>10 218</td>
        <td>9 827</td>
        <td>14 483</td>
        <td>217,2</td>
        <td>78,6</td>
        <td>351,0</td>
        <td>5,3</td>
        <td>128,9</td>
        <td>47,4</td>
        <td>0,0</td>
        <td>34,0</td>
        <td>6 165</td>
        <td>246</td>
        <td>7 283</td>
        <td>47,8</td>
        <td>36,3</td>
        <td>213,4</td>
        <td>750</td>
        <td>795</td>
        <td>116 808</td>
        <td>49,7</td>
        <td>9,9</td>
        <td>34,4</td>
        <td>157</td>
        <td>15</td>
        <td>0</td>
        <td>514</td>
        <td>3 009</td>
        <td>17</td>
        <td>0</td>
        <td>86</td>
        <td>6,2</td>
        <td>1,5</td>
        <td>0,0</td>
        <td>43,4</td>
        <td>149,7</td>
        <td>0,3</td>
        <td>0,0</td>
        <td>0,8</td>
        <td>0</td>
        <td>20</td>
        <td>0</td>
        <td>740</td>
        <td>0</td>
        <td>37</td>
        <td>1839500</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>713</td>
        <td>0</td>
        <td>525</td>
        <td>42</td>
        <td>46 932 608</td>
        <td>234 056</td>
        <td>87 528 552</td>
        <td>0</td>
        <td>0</td>
        <td>5 073 548</td>
        <td>0</td>
        <td>1839500</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>18 835 428</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>32 457 280</td>
        <td>0</td>
        <td>11 416 266</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 681 388</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>211 824</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>15 728 640</td>
        <td>1 073 741 824</td>
        <td>14 101 272</td>
        <td>71 303 168</td>
        <td>89 128 960</td>
        <td>42 237 240</td>
        <td>8 912 896</td>
        <td>6 179 312</td>
        <td>8 912 896</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>85 458 944</td>
        <td>57 304 944</td>
        <td>92 274 688</td>
        <td>1 151 336 448</td>
        <td>86 413 640</td>
        <td>268 435 456</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>25 527 278</td>
        <td>17</td>
        <td>155 261</td>
        <td>209 773</td>
        <td>784 580</td>
        <td>5 371 787</td>
        <td>1 037 508</td>
        <td>8 484 314</td>
        <td>5 363 665</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>8 912 896</td>
        <td>71 827 456</td>
        <td>102 760 448</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>5</td>
        <td>1</td>
        <td>299 326 400</td>
        <td>49 969 648</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>85 458 944</td>
        <td>72 876 032</td>
        <td>30 932 992</td>
        <td>30 932 992</td>
        <td>24 576</td>
        <td>0</td>
        <td>0</td>
        <td>6 179 312</td>
        <td>80 740 352</td>
        <td>8 949 469</td>
        <td>58</td>
        <td>143 128</td>
        <td>33</td>
        <td>111 352</td>
        <td>2 218</td>
        <td>3 933</td>
        <td>997123735</td>
        <td>0</td>
        <td>32 768</td>
        <td>0</td>
        <td>19 272</td>
        <td>6</td>
        <td>4</td>
        <td>0</td>
        <td>0</td>
        <td>4</td>
        <td>0</td>
        <td>1 408</td>
        <td>0</td>
        <td>0</td>
        <td>11</td>
        <td>18</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>993945032</td>
        <td>0</td>
        <td>0</td>
        <td>250686</td>
        <td>822003</td>
        <td>0</td>
        <td>0</td>
        <td>244976</td>
      </tr>
    </tbody>
  </table>
</body>
</html>

