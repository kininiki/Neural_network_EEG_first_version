# Neural_network_EEG_first_version
Искусственная нейронная сеть прямого распространения, предсказывающая баллы интеллекта человека (тест Равена) по показателям ЭЭГ.

ВНИМАНИЕ!!! Все файлы представлены в формате IPYNB, то есть подлежат открытию с помощью приложения Jupyter Notebook или ему подобных.

Для получения базы данных по ЭЭГ респондентов (обращение к файлам которой пристутствует в работе) обратитесь к автору!!! Также можете заменить данные автора на свои.

С помощью программы format_csv можно преобразовать сырые данные, полученные предварительно в формате csv, в более подходящий вид (без запятых/в виде массива данных/в виде столбца и т.д.), а также сохранить в виде бинарного файла (при необходимости).

Программа Neural_example предоставляет возможность проверить работу искусственной нейронной сети на урезанном наборе данных. Для получения полной базы данных по ЭЭГ респондентов следует обратиться к автору.

С помощью программы pirson_spearman можно посчитать коэффициенты корреляции Спирмена и Пирсона для тестовой выборки.

В файле neural_helpmas содержатся вспомогательные функции для преобразования файлов/массивов, которые могут быть полезными при работе.
