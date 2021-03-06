# Modul ucitelrozvrh

Učitelský rozvrh

Název modulu v URL: `ucitelrozvrh` Příklad: `https://www.example.com/login.aspx?hx=token&pm=ucitelrozvrh&pmd=20191209`

Chová se naprosto **stejně jako modul [rozvrh](rozvrh.md)**, akorát hodiny nemají tagy `<uc>`/`<zkruc>` a v tagu `<skup>`/`<zkrskup>` je napsané jméno/zkratka třídy. Tento modul je dostupný pouze pro učitele - pokud se na něj dotáže žák, vrátí se mu prázdný rozvrh.

POZOR, v některých případech může být *zkratka* třídy velmi dlouhá a vykreslování rozvrhu s tím musí počítat! např.: `8.A In1 8.B In3` (kombinovaná skupina skupin 8.A informatika 1 a 8.B informatika 3) - struktura a délka zkratek skupin závisí na škole.

## Příklad

```xml

<?xml version="1.0" encoding="utf-8"?>
<results>
  <rozvrh>
    <typ>akt</typ>
    <kodcyklu>1</kodcyklu>
    <zkratkacyklu>L</zkratkacyklu>
    <nazevcyklu>lichý týden</nazevcyklu>
    <hodiny>
      <pocet>14</pocet>
      <hod>
        <caption>1</caption>
        <begintime>8:00</begintime>
        <endtime>8:45</endtime>
      </hod>
      <hod>
        <caption>2</caption>
        <begintime>8:55</begintime>
        <endtime>9:40</endtime>
      </hod>
      <hod>
        <caption>3</caption>
        <begintime>10:00</begintime>
        <endtime>10:45</endtime>
      </hod>
      <hod>
        <caption>4</caption>
        <begintime>10:55</begintime>
        <endtime>11:40</endtime>
      </hod>
      <hod>
        <caption>5</caption>
        <begintime>11:50</begintime>
        <endtime>12:35</endtime>
      </hod>
      <hod>
        <caption>6</caption>
        <begintime>12:45</begintime>
        <endtime>13:30</endtime>
      </hod>
      <hod>
        <caption>7</caption>
        <begintime>13:40</begintime>
        <endtime>14:25</endtime>
      </hod>
      <hod>
        <caption>8</caption>
        <begintime>14:35</begintime>
        <endtime>15:20</endtime>
      </hod>
      <hod>
        <caption>9</caption>
        <begintime>15:30</begintime>
        <endtime>16:15</endtime>
      </hod>
      <hod>
        <caption>10</caption>
        <begintime>16:25</begintime>
        <endtime>17:10</endtime>
      </hod>
      <hod>
        <caption>11</caption>
        <begintime>17:20</begintime>
        <endtime>18:05</endtime>
      </hod>
      <hod>
        <caption>12</caption>
        <begintime>18:15</begintime>
        <endtime>19:00</endtime>
      </hod>
    </hodiny>
    <dny>
      <pocet>5</pocet>
      <den>
        <zkratka>Po</zkratka>
        <datum>20191209</datum>
        <hodiny>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191209 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>105</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.B</zkrskup>
            <skup>VI.B</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>2</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191209 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>105</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>8.B</zkrskup>
            <skup>VIII.B</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>4</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191209 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>Inf</zkrpr>
            <pr>Informatika</pr>
            <zkrmist>Vyp</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.A In2 6.B In2</zkrskup>
            <skup>VI.A Informatika 6. roč. sk.2 6.B Inf2</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>6</caption>
          </hod>
          <hod>
            <idcode>20191209 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>Inf</zkrpr>
            <pr>Informatika</pr>
            <zkrmist>Vyp</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.B In1</zkrskup>
            <skup>VI.B Informatika 6.roč sk.1</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>7</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
        </hodiny>
      </den>
      <den>
        <zkratka>Út</zkratka>
        <datum>20191210</datum>
        <hodiny>
          <hod>
            <idcode>20191210 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>108</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>7.A</zkrskup>
            <skup>VII.A</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>1</caption>
          </hod>
          <hod>
            <idcode>20191210 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>104</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.A</zkrskup>
            <skup>VI.A</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>2</caption>
          </hod>
          <hod>
            <idcode>20191210 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>102</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.B</zkrskup>
            <skup>VI.B</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>3</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191210 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>Inf</zkrpr>
            <pr>Informatika</pr>
            <zkrmist>Vyp</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.A In1</zkrskup>
            <skup>VI.A Informatika 6.roč sk. 1</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>6</caption>
          </hod>
          <hod>
              <typ>X</typ>
              <zkratka></zkratka>
            </hod>
          <hod>
            <idcode>20191210 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>Inf</zkrpr>
            <pr>Informatika</pr>
            <zkrmist>Vyp</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.B In3</zkrskup>
            <skup>VI.B Informatika 6. roč. sk.3</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>8</caption>
          </hod>
          <hod>
            <idcode>20191210 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>Inf</zkrpr>
            <pr>Informatika</pr>
            <zkrmist>Vyp</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.B In3</zkrskup>
            <skup>VI.B Informatika 6. roč. sk.3</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>9</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
        </hodiny>
      </den>
      <den>
        <zkratka>St</zkratka>
        <datum>20191211</datum>
        <hodiny>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191211 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>108</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>9.B</zkrskup>
            <skup>IX.B</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>2</caption>
          </hod>
          <hod>
            <idcode>20191211 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>205</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>8.A</zkrskup>
            <skup>VIII.A</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>3</caption>
          </hod>
          <hod>
            <idcode>20191211 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>102</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>6.B</zkrskup>
            <skup>VI.B</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>4</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191211 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>Inf</zkrpr>
            <pr>Informatika</pr>
            <zkrmist>212</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>9.A In2 9.B In2</zkrskup>
            <skup>IX.A Informatika 9.roč sk. 2 IX.B(In2)</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng>změna místnosti (Vyp)</chng>
            <caption>6</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
        </hodiny>
      </den>
      <den>
        <zkratka>Čt</zkratka>
        <datum>20191212</datum>
        <hodiny>
          <hod>
            <idcode>20191212 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>103</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>8.A</zkrskup>
            <skup>VIII.A</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>1</caption>
          </hod>
          <hod>
            <idcode>20191212 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>102</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>8.B</zkrskup>
            <skup>VIII.B</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng>Změna místnosti (103)</chng>
            <caption>2</caption>
          </hod>
          <hod>
            <idcode>20191212 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>102</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>9.C</zkrskup>
            <skup>IX.C</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>3</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191212 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>212</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>8.A</zkrskup>
            <skup>VIII.A</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>5</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191212 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>Inf</zkrpr>
            <pr>Informatika</pr>
            <zkrmist>Vyp</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>8.B In3</zkrskup>
            <skup>VIII.B Informatika 8.roč sk. 3</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>8</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
        </hodiny>
      </den>
      <den>
        <zkratka>Pá</zkratka>
        <datum>20191213</datum>
        <hodiny>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191213 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>105</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>7.A</zkrskup>
            <skup>VII.A</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>2</caption>
          </hod>
          <hod>
            <idcode>20191213 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>105</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>7.B</zkrskup>
            <skup>VII.B</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>3</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <idcode>20191213 (nejake id)</idcode>
            <typ>H</typ>
            <zkrpr>M</zkrpr>
            <pr>Matematika</pr>
            <zkrmist>105</zkrmist>
            <mist></mist>
            <zkrabs></zkrabs>
            <abs></abs>
            <tema></tema>
            <zkrskup>9.C</zkrskup>
            <skup>IX.C</skup>
            <cycle>L</cycle>
            <uvol></uvol>
            <chng></chng>
            <caption>6</caption>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
          <hod>
            <typ>X</typ>
            <zkratka></zkratka>
          </hod>
        </hodiny>
      </den>
    </dny>
  </rozvrh>
  <result>01</result>
</results>

```