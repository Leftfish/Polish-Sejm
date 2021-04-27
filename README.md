### O co chodzi?

Kod jest po angielsku, bo taka konwencja, ale readme mogę napisać po polsku :) 

Sejm_poselskie_8kadencja.ipynb: służy do ściągnięcia ze strony Sejmu informacji o projektach, które ostatecznie stały się ustawami. Na tej podstawie możemy ustalić, kto wnosił jakie projekty, a w przypadku projektów poselskich - niestety dopiero po pobraniu plików PDF - odczytać nazwiska posłów i posłanek, których podpisy umożliwiły wniesienie projektu. Wymaga [requests](https://2.python-requests.org/en/master/) i [tika](https://github.com/chrismattmann/tika-python).

Sejm_ustawy_9kadencja.ipynb: służy do ściągnięcia danych nt. tego, kto jak głosował w III czytaniu ustaw w Sejmie 9 kadencji. Wymaga [requests](https://2.python-requests.org/en/master/).

### Co jest potrzebne, żeby tego użyć?

Python 3.0, Jupyter Notebook i moduły, których nie ma w standardowym Pythonie, wymienione powyżej.
