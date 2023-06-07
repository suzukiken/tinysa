TinySAのデータをPC（想定ではRaspberryPi）に保存するスクリプト

http://athome.kaashoek.com/tinySA/python/
を見てTinySAのPCからの使い方を勉強して書いた。
コードの多くの部分はtinysa.pyに書かれているものを使っている。

## Preparation

python3.11 -m venv env
source env/bin/activate
python3.11 -m pip install -r requirements.tx
pip install --upgrade pip 

## Run

python3.11 save.py
