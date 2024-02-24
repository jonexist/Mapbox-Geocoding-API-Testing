# Finding Nearby Pharmacies with Geocoding API

This endpoint demonstrates how to find pharmacies near specific coordinates using the Pharmacy Geocoding API.

## Endpoint

The endpoint for the Pharmacy Geocoding API is:

```bash
https://api.mapbox.com/geocoding/v5/mapbox.places/pharmacy.json?proximity=-79.8419,35.1849&access_token=mapbox_token
```

## Parameters

The endpoint utilizes the following parameters:

- `proximity`: Specifies the longitude and latitude of the location you wish to search near. In this example, it is set to `-79.8419,35.1849`, corresponding to coordinates in North Carolina.

- `access_token`: Your Mapbox access token, required for authenticating the request.
