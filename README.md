<h1 align="center">Учебный проект по работе с Maven</h1>

<h2>Что было сделано?</h2>

<h3>1. Подключены зависимоти:</h3><br>
         :white_check_mark:org.apache.commons: commons-lang3: 3.12.0<br>
         :white_check_mark:org.openjfx: javafx-controls: 18.0.1<br>
         :white_check_mark:com.javarush: desktop-game-engine:1.0 (Из библиотеки lib в локальный репозиторий)<br>
         :white_check_mark:org.junit.jupiter: junit-jupiter-engine: 5.8.2 (с scope test)<br>

<h3>2. Добавлены плагины и resources:</h3><br>
         :white_check_mark:maven-install-plugin (Для установки зависимоти javarush: desktop-game-engine:1.0 из библиотеки lib)<br>
         :white_check_mark:maven-jar-plugin (Для конфигурации MANIFEST.MF)<br>
         :white_check_mark:maven-dependency-plugin (Для копирования зависимостей)<br>
         :white_check_mark:maven-surefire-plugin (Для отключения StrangeTest)<br>
         :white_check_mark:Доблена секция “resources”, в которой указано, что собранные JAR-зависимости это ресурс, чтоб плагин maven-jar-plugin сложил их внутрь JAR-файла в папку lib/<br>
