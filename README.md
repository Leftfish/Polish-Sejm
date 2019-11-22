### O co chodzi?

Kod jest po angielsku, bo taka konwencja, ale readme mogę napisać po polsku :) Kawałek kodu, który umieszczam w tym repozytorium, służy do ściągnięcia ze strony Sejmu informacji o projektach, które ostatecznie stały się ustawami. Na tej podstawie możemy ustalić, kto wnosił jakie projekty, a w przypadku projektów poselskich - niestety dopiero po pobraniu plików PDF - odczytać nazwiska posłów i posłanek, których podpisy umożliwiły wniesienie projektu.

### Co jest potrzebne, żeby tego użyć?

Python 3.0, Jupyter Notebook i dwa moduły, których nie ma w standardowym Pythonie, czyli [requests](https://2.python-requests.org/en/master/) i [tika](https://github.com/chrismattmann/tika-python). Ten pierwszy służy do komunikacji z serwerem Sejmu, a drugi zawiera fantastczny parser plików PDF.
