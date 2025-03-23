# TextMining
- venv virtual environment
  - `source .venv/Scripts/activate` to activate venv

## poniżej wszystkie komendy zakładają aktywny venv
instalacja 

`pip install nltk`

dalej zaimportowanie nltk i pobranie punkt_tab dla nltk
```
$ python
>>> import nltk
>>> nltk.download('punkt_tab') 
>>> exit()
```

instalacja morfeusz 2 - bindingow dla pythona 3.11 
`pip install http://download.sgjp.pl/morfeusz/20250316/Windows/64/morfeusz2-1.99.10-20250316-cp311-cp311-win_amd64.whl`

> w tym miejscu upewnić się, że wszystkie importy są w text_mining.ipynb

wygenerowanie pliku z lista uzywanych zaimportowanych bibliotek
`pip freeze requirements.txt`

## Moodle
pobieramy:
- literatura - streszczenia - oryginal
- stopwords_pl

umieszczamy w folderze ./literatura wewnatrz projektu