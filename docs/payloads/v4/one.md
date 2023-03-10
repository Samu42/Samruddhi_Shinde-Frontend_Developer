# Get one payload

**Method** : `GET`

**URL** : `https://api.spacexdata.com/v4/payloads/:id`

**URL Parameters** : `id=[string]` where `id` is the ID of the payload

**Auth required** : `False`

## Success Response

**Code** : `200 OK`

**Content example** :

```json
{
    "dragon": {
        "capsule": null,
        "mass_returned_kg": null,
        "mass_returned_lbs": null,
        "flight_time_sec": null,
        "manifest": null,
        "water_landing": null,
        "land_landing": null
    },
    "name": "Tintin A & B",
    "type": "Satellite",
    "reused": false,
    "launch": "5eb87d14ffd86e000604b361",
    "customers": [
        "SpaceX"
    ],
    "norad_ids": [
        43216,
        43217
    ],
    "nationalities": [
        "United States"
    ],
    "manufacturers": [
        "SpaceX"
    ],
    "mass_kg": 800,
    "mass_lbs": 1763.7,
    "orbit": "SSO",
    "reference_system": "geocentric",
    "regime": "low-earth",
    "longitude": null,
    "semi_major_axis_km": 6737.42,
    "eccentricity": 0.0012995,
    "periapsis_km": 350.53,
    "apoapsis_km": 368.04,
    "inclination_deg": 97.4444,
    "period_min": 91.727,
    "lifespan_years": 1,
    "epoch": "2020-06-13T13:46:31.000Z",
    "mean_motion": 15.69864906,
    "raan": 176.6734,
    "arg_of_pericenter": 174.2326,
    "mean_anomaly": 185.9087,
    "id": "5eb0e4c6b6c3bb0006eeb21e"
}
```

## Error Responses

**Code** : `404 NOT FOUND`

**Content** : `Not Found`
