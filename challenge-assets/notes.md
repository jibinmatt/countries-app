/*

{
  "name": "India",
  "topLevelDomain": [".in"],
  "alpha2Code": "IN",
  "alpha3Code": "IND",
  "callingCodes": ["91"],
  "capital": "New Delhi",
  "altSpellings": ["IN", "Bhārat", "Republic of India", "Bharat Ganrajya"],
  "subregion": "Southern Asia",
  "region": "Asia",
  "population": 1380004385,
  "latlng": [20, 77],
  "demonym": "Indian",
  "area": 3287590,
  "gini": 35.7,
  "timezones": ["UTC+05:30"],
  "borders": ["AFG", "BGD", "BTN", "MMR", "CHN", "NPL", "PAK", "LKA"],
  "nativeName": "भारत",
  "numericCode": "356",
  "flags": {
    "svg": "<https://flagcdn.com/in.svg>",
    "png": "<https://flagcdn.com/w320/in.png>"
  },
  "currencies": [
    {
      "code": "INR",
      "name": "Indian rupee",
      "symbol": "₹"
    }
  ],
  "languages": [
    {
      "iso639_1": "hi",
      "iso639_2": "hin",
      "name": "Hindi",
      "nativeName": "हिन्दी"
    },
    {
      "iso639_1": "en",
      "iso639_2": "eng",
      "name": "English",
      "nativeName": "English"
    }
  ],
  "translations": {
    "br": "India",
    "pt": "Índia",
    "nl": "India",
    "hr": "Indija",
    "fa": "هند",
    "de": "Indien",
    "es": "India",
    "fr": "Inde",
    "ja": "インド",
    "it": "India",
    "hu": "India"
  },
  "flag": "<https://flagcdn.com/in.svg>",
  "regionalBlocs": [
    {
      "acronym": "SAARC",
      "name": "South Asian Association for Regional Cooperation"
    }
  ],
  "cioc": "IND",
  "independent": true
}

*/

## Functional and Non-functional requirements

key data to use -
  "name"
  "nativeName"
  "population"
  "region"
  "subregion"
  "capital"
  "topLevelDomain"
  "currencies" : [{"name"}]
  "languages" : [...{"name"}]
  "borders" : [...{alpha3code->name}]

- pulling data from .json file, through multiple heirarchies

- formatting population with commas

- border countries displaying buttons to go to respective countries' view

- light/dark mode toggle

- responsive mobile layout

- search function

- display "img", "name", "population", "region", "capital" in a card, in a responsive grid layout

- filter dropdown to filter through region

- back button in detail view

- use {<https://restcountries.com> api} mainly but use the data.json file if the api goes down
