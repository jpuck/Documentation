# REST API: GET rule

Dit is een methode om alle metadata van een regel op te vragen. Deze methode ondersteunt geen parameters. De methode is aan te roepen met een HTTP GET request naar de volgende URL:

`https://api.copernica.com/v1/rule/$id?access_token=xxxx`

De `$id` hier moet vervangen worden door de ID van de regel waarvan je de data op wil vragen.


## Beschikbare parameters

Er zijn geen beschikbare parameters voor deze methode.


## Teruggegeven velden

Deze methode geeft een JSON regel object terug met de volgende eigenschappen:

- **name**: naam van de regel
- **description**: omschrijving van de regel
- **view**: ID van de selectie waar de regel bij hoort
- **conditions**: array van condities van de regel
- **inversed**: boolean waarde om aan te geven of de regel wel of niet geïnverteerd moet worden. Als deze op "True" staat worden er alleen profielen teruggegeven die niet aan de condities voldoen.
- **disabled**: boolean waarde om aan te geven of een regel uitgeschakeld moet worden of niet.


## Voorbeeld in PHP

Het volgende PHP script demonstreert hoe de API method te gebruiken is.

```php
// vereiste scripts
require_once('copernica_rest_api.php');

// verander dit naar je access token
$api = new CopernicaRestApi("your-access-token");

// voer het verzoek uit en print het resultaat
print_r($api->get("rule/1234"));
```

Dit voorbeeld vereist de [REST API class](rest-php).


## Meer informatie

- [Overzicht van alle API methodes](rest-api)
* [Vraag regels van een selectie op](./rest-get-view-rules)
