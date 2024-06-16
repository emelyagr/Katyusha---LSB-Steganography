<h1>Katyusha - LSB Steganography</h1>

Katyusha - LSB Steganography — это веб-программа, реализующая метод LSB с изображениями. LSB (Least Significant Bit — «Наименее значимый бит») — это метод стеганографии, который заключается в выделении наименее значимых бит изображения-контейнера с последующей их заменой на биты сообщения таким образом, чтобы исходное изображение и стегоконтейнер не были различимы человеческому глазу. Применяется для передачи секретных сообщений. 

<h2>Использование</h2>

Пример использования: https://youtu.be/lRH7YrugOjA

1. Скачайте из релиза (Releases) программу и запустите её в любом интернет-браузере.
2. В блоке "Encode Message" нажмите кнопку "Выберите файл" и выберите любое изображение формата "*.jpeg"/"*.bmp", а затем в пустое поле введите Ваше сообщение (секретное послание).
3. Нажмите кнопку "Encode" и изображение с Вашим посланием  (стегоконтейнер) скачается на компьютер в формате "*.png".
4. Если Вы хотите передать сообщение: отправьте стегоконтейнер по сети другому пользователю любым способом, но учтите, что необходимо использовать сервисы и функции, которые при загрузке или передаче изображения не сжимают его, и целостность файла сохраняется полностью, до единого бита, в противном случае, скрытое сообщение извлечь не получится, так как биты перемешаются между собой.
5. Нажмите кнопку "Выберите файл" в блоке "Decode Message", выберите Ваш только что скачанный файл, а затем нажмите кнопку "Decode", внизу появится скрытое сообщение (послание).

<h2>Преимущества, недостатки и особенности</h2>

Преимущества программы:
1. Работоспособность.
2. Быстрая скорость шифрования (замены битов).
3. Отсутствие заимствованных библиотек.
4. Простой и приятный интерфейс.
5. Файл формата "*.html", что позволяет легко его запускать в любом интернет-браузере, без страха выполнения вредоносного кода программы исполняемого файла.
6. Простота, стиль и читабельность кода.
7. Вся программа содержится в файле формата "*.html", включая "JavaScript" код и "CSS" стиль, что позволяет легко её использовать и делиться.
8. Кроссплатформенность (программу можно использовать на мобильном устройстве, запустив её в интернет-браузере).
9. Исходное изображение и стегоконтейнер не различимы для человеческого глаза.

Недостатки программы:
1. Отсутствие возможности создания стегоконтейнера из файла изначального формата "*.png".
2. Минимальная функциональность.

(С) Емельянов Григорий Андреевич. Все права защищены. Использование кода программы без указания автора запрещено.
