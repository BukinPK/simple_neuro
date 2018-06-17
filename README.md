# simple_neuro
Реализация простенькой нейронки из говна и палок, для распознавания символов.

USAGE python3 neuro.py <адрес картинки (pic/<буква>t.png)>.

Вам следует дать адрес к картинке, изображение на которой вы хотите распознать.

Картинка должны быть в том же формате и размерности, что и файлы, используемые при обучении (об этом ниже).


Для обучения следует заливать картинки в строго определённом формате и названии в папку pic/input/.

В папке pic находится файл template.xcf, он для графического редактора Gimp. В нём рисуйте символы и сохраняйте в pic/input/.

Файлы в pic/input/ используются для обучения.

При сохранении следует указать символ, изображённый на картинке и индекс (не значащий ничего).

В pic/model/ находятся модели, созданные в процессе обучения.

Также, в директории pic/ присутствуют файлы формата <буква>t.png (t - значит тест), которые не включены в сет обучения (pic/input/), я их добавил, чтобы проверять на них качество работы модели.


В выдаче вы увидите отладочную информацию о степени "уверенности в своей правоте" каждого из нейронов и количество экземпляров символа используемых при создании модели в процессе обучения нейрона.
