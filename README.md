(С) Емельянов Григорий Андреевич. Все права защищены. Использование кода программы без указания автора запрещено.

Katyusha — LSB Steganography

Katyusha — LSB Steganography — это веб-программа, реализующая метод LSB с изображениями. LSB (Least Significant Bit — «Наименее значимый бит») — это метод стеганографии, который заключается в выделении наименее значимых бит изображения-контейнера с последующей их заменой на биты сообщения. Применяется для передачи секретных сообщений. 

Пример использования: https://youtu.be/lRH7YrugOjA

1. Скачайте из релиза (releases) программу и запустите её в любом интернет-браузере.
2. В блоке "Encode Message" нажмите кнопку "Выберите файл" и выберите любое изображение формата "*.jpeg", а затем в пустое поле введите Ваше сообщение (секретное послание).
3. Нажмите кнопку "Encode" и изображение с Вашим посланием  (стегоконтейнер) скачается на компьютер в формате "*.png".
4. Если Вы хотите передать сообщение: отправьте стегоконтейнер по сети другому пользователю любым способом, но учтите, что необходимо использовать сервисы и функции, которые при загрузке или передаче изображения не сжимают его, и целостность файла сохраняется полностью, до единого бита, в противном случае, скрытое сообщение извлечь не получится, так как биты перемешаются между собой.
5. Нажмите кнопку "Выберите файл" в блоке "Decode Message", выберите Ваш только что скачанный файл, а затем нажмите кнопку "Decode", внизу появится скрытое сообщение (послание).
