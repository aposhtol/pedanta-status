# Pedanta — stanje usluge

Javna stranica stanja za [Pedantu](https://pedanta.app), na GitHub Pages — izvan poslužitelja Pedante, pa radi i kad
on ne radi.

- **Uživo:** preglednik posjetitelja svake minute pita `https://pedanta.app/api/status` (javno, bez prijave, bez
  podataka škola) i pokazuje „radi”, „baza ne odgovara” ili „ne javlja se”, uz obavijesti objavljene u aplikaciji.
- **Zapisi o smetnjama:** `obavijesti.json` — za vrijeme kad je cijeli poslužitelj nedostupan. Uređuje se skriptom
  `scripts/status-obavijest.sh` u repozitoriju Pedante.

Stranica ne učitava ništa izvana i ne prati posjetitelje.
