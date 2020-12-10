# EduNet
MSU neural networks course for scientists

#### Требования к структуре репозитория и сервера:
* В репозитории есть две главные папки: src и out.
* `out` - папка с итогами нашей работы, а именно - блокнотами.
  * внутри out располагаются подпапки с названиями занятий, и главный блокнот в каждой подпапке,
например `out/L01_Intro/L01_Intro.ipynb` Название главного блокнота дублирует название папки.
  * помимо главного блокнота там могут быть блокноты с упражнениями (название будет начинаться с EX),
например `out/L01_Intro/EX01_Intro.ipynb`

* `src` - папка с сырыми материалами и изображениями
  * В `src` не допускается хранить блокноты. Совместная работа над ними ведётся в `out`. Git будет автоматически игнорировать блокноты в src.
  * В `src/L0X_Name/img` - следует класть изображения, относящиеся к лекции. На сервере edunet.kea.su ровно такая же структура.
  * Ссылки на изображения в блокнотах должны вести на сервер по пути: `edunet.kea.su/repo/src/L0X_Name/img/image_name.png`
  * В `src/L0X_Name/` - помимо изображений можно хранить все остальные материалы для лекций, за исключением самих блокнотов.
  
* Хранение изображений на `edunet.kea.su` приоритетнее чем хранение в репозитории. В идеале - дублирование.

#### Нейминг:
Кириллица буквы в названиях недопустима, вместо пробелов - нижние пробелы, нумерация из двух цифр, L/EX для обозначения лекционной части/заданий.
Первая буква названия лекции заглавная, остальные строчные.

#### Требования к комиту блокнота
Перед коммитом блокнота следует проверять коммит на адекватность:
* Блокнот не должен весить больше пары МБ. Если больше, то вероятно в него добавились метаданные, их можно увидеть как огромный блок изменений с непонятным текстом. Если такая пробелма возникла, пишите Андрею Маракулину (позже выясним причину и обновим инструкцию).
* Сырой код блокнота не должен быть в одну строку (при измененни блокнота не должны переписывать все его части)
* Рекомендуется редактировать блокноты локально через jupyter. Colab использовать только для импорта блокнотов, но не для экспорта
* Проверять что все ссылки работают (если коммитите готовый вариант)
* Очищать вывод ячеек перед сохранением!
