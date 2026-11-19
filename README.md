# ByvAI – Home Assistant blueprinty

Hotové automatizácie z návodov na [byvai.sk](https://byvai.sk/). Importujete ich jedným klikom a v Home Assistant si len vyberiete svoje zariadenia z rozbaľovacích zoznamov – bez písania YAML.

V slovenskom Home Assistant sa blueprinty volajú **Plány** (Nastavenia → Automatizácie a scény → Plány).

## Blueprinty

### Spotrebič dokončil program – upozornenie do mobilu

Notifikácia do telefónu, keď práčka, sušička alebo umývačka dokončí program. Stačí smart zásuvka s meraním spotreby.

[![Importovať do Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fbvstudio1%2Fbyvai-blueprints%2Fblob%2Fmain%2Fautomation%2Fspotrebic-skoncil.yaml)

### Otvorené okno večer – opakované upozornenie do mobilu

Večer a v noci pripomína otvorené okno, kým ho niekto nezavrie. Hodí sa napríklad do detskej izby.

[![Importovať do Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fbvstudio1%2Fbyvai-blueprints%2Fblob%2Fmain%2Fautomation%2Fokno-otvorene.yaml)

### Svetlo podľa pohybu alebo prítomnosti (s nočným režimom)

Zapne svetlo pri pohybe alebo prítomnosti a zhasne, až keď sú všetky senzory bez detekcie. V noci svieti na nižší jas. Funguje s jedným pohybovým senzorom aj s kombináciou PIR a radaru (napríklad Aqara FP300).

[![Importovať do Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fbvstudio1%2Fbyvai-blueprints%2Fblob%2Fmain%2Fautomation%2Fsvetlo-pohyb-pritomnost.yaml)

### Pri vetraní sa nekúri

Pri otvorenom okne vypne kúrenie a po zatvorení všetkých okien ho vráti do pôvodného režimu.

[![Importovať do Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fbvstudio1%2Fbyvai-blueprints%2Fblob%2Fmain%2Fautomation%2Fvetranie-kurenie.yaml)

### Zhasni zabudnuté svetlo

Vypne svetlo, ktoré svieti dlhšie než nastavený čas.

[![Importovať do Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fbvstudio1%2Fbyvai-blueprints%2Fblob%2Fmain%2Fautomation%2Fzabudnute-svetlo.yaml)

## Ako na to

1. Kliknite na tlačidlo **Importovať do Home Assistant** pri blueprinte.
2. Zadajte adresu svojho Home Assistant a potvrďte import.
3. Kliknite na **Vytvoriť automatizáciu**, vyberte svoje zariadenia a uložte.

Potrebujete Home Assistant 2024.10 alebo novší. Pri blueprintoch s upozornením aj aplikáciu Home Assistant v telefóne.

## Návody na byvai.sk

- [Home Assistant notifikácie do mobilu](https://byvai.sk/home-assistant-notifikacie/)
- [Aqara FP300 v Home Assistant](https://byvai.sk/aqara-fp300-home-assistant/)
- [Inteligentná domácnosť v paneláku](https://byvai.sk/inteligentna-domacnost-v-panelaku/)
- [Smart domácnosť v prenájme](https://byvai.sk/smart-domacnost-v-prenajme/)
- [Home Assistant blueprint: čo to je a ktoré sa oplatia](https://byvai.sk/home-assistant-blueprint/)
