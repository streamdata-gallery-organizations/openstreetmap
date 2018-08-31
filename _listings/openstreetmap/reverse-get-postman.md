{
  "info": {
    "name": "OpenStreetMap OSM - Reverse",
    "_postman_id": "75320a81-524b-4195-9bbb-1c9847534bff",
    "description": "[Full description of the service:](http://wiki.openstreetmap.org/wiki/Nominatim#Reverse_Geocoding)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Maps",
      "item": [
        {
          "id": "034ae66a-c6e3-45d7-9db7-bd3ce570b5db",
          "name": "LookupGet",
          "request": {
            "url": "http:// http://nominatim.openstreetmap.org/lookup?format=%7B%7D&osm_ids=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "[Full description of the service:](http://wiki.openstreetmap.org/wiki/Nominatim#Address_lookup)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "774e5f4c-b56c-43e6-8fdf-22a8a7cbd28d"
            }
          ]
        },
        {
          "id": "a2158003-dbc2-474d-b9fd-7c1bb4fffa66",
          "name": "ReverseGet",
          "request": {
            "url": "http:// http://nominatim.openstreetmap.org/reverse?format=%7B%7D&lat=%7B%7D&lon=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "[Full description of the service:](http://wiki.openstreetmap.org/wiki/Nominatim#Reverse_Geocoding)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8284a49b-bfe2-4551-aea6-ef66da0c1c36"
            }
          ]
        }
      ]
    }
  ]
}