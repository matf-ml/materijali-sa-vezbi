# Vezbe 01 - uvod

## Python

### Jupyter notebook
[Jupyter notebook](https://jupyter.org/) je open source veb aplikacija koja omogućava interaktivno pisanje i pokretanje Python koda.
Instalira se kao python paket koristeći `pip`.

Najpre, potrebno je instalirati pip za python 3. U zavisnosti od sistema koji koristite varira i instalacija.
Za Ubuntu sledi primer instaliranja.

Ubuntu:
```bash
sudo apt-get install python-pip3
```

Potom instalirati jupyter paket.

```bash
sudo pip3 install jupyter
```

Dalje je potrebno pozicionirati se u direktorijum koji želite da bude koreni direktorijum za jupyter pre početka rada, na primer:

```bash
cd /home/vi/
mkdir jupyter-test
cd jupyter-test
jupyter notebook
```
Naredba `jupyter notebook` će pokrenuti jupyter server u konzoli gde je ukucana i istovremenmo pokrenuti podrazumevani
veb pregledač koji će povezati na (verovatno) na `localhost:8888`.


