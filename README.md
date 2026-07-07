<div align="center">

# SmartIPTV-IT

Playlist IPTV italiana ottimizzata per [Smart IPTV](https://siptv.app).

[![Playlist](https://img.shields.io/badge/playlist-M3U-blue)](iptv-it.m3u)
[![Country](https://img.shields.io/badge/country-IT-green)](iptv-it.m3u)
[![Smart IPTV](https://img.shields.io/badge/player-Smart%20IPTV-orange)](https://siptv.app)

</div>

## Playlist

Il file principale e' [`iptv-it.m3u`](iptv-it.m3u).

La playlist raccoglie canali italiani in chiaro e stream live pubblici, organizzati per gruppo:

| Gruppo | Esempi |
| --- | --- |
| Rai | Rai 1, Rai 2, Rai News 24 |
| Mediaset | Canale 5, Italia 1, Iris |
| Discovery | NOVE, Real Time, DMAX |
| Sky | TV8, Cielo |
| Radio | RTL 102.5, Radio Italia TV |
| Altro | TV2000, QVC, Sportitalia |

Se preferisci una lista unica senza categorie, puoi disabilitare la divisione per gruppi durante il caricamento della playlist dal portale web di Smart IPTV.

## Metadata

Le entry sono curate per funzionare bene con Smart IPTV e includono, dove disponibili:

| Campo | Uso |
| --- | --- |
| `tvg-id` | identificativo EPG |
| `tvg-chno` | numero canale, preferendo la LCN DTT italiana e usando Tivusat come fallback quando manca una LCN terrestre attuale |
| `tvg-logo` | logo del canale |
| `tvg-country` | paese |
| `tvg-language` | lingua |
| `group-title` | categoria nell'app |

## Uso

Carica la playlist dal portale ufficiale Smart IPTV:

```text
https://siptv.app/mylist/
```

Dopo un aggiornamento della playlist puo' essere necessario ricaricarla dall'app o riavviare Smart IPTV sul dispositivo.

## Note

La disponibilita' degli stream puo' cambiare nel tempo
Questo repository non ospita flussi video: contiene solo una playlist con URL remoti.

## Crediti

Gran parte del lavoro originale sui canali e sui loghi proviene dai progetti:

- [Tundrak/IPTV-Italia](https://github.com/Tundrak/IPTV-Italia)
- [pasq96/IPTV-Italia](https://github.com/pasq96/IPTV-Italia)

Crediti ai rispettivi autori.
