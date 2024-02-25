# Finding Nearby Pharmacies with Geocoding API

This endpoint demonstrates how to find pharmacies near specific coordinates using the Pharmacy Geocoding API.

## Endpoint

The endpoint for the Pharmacy Geocoding API is:

```bash
https://api.mapbox.com/geocoding/v5/mapbox.places/pharmacy.json?proximity=-79.8419,35.1849&access_token=mapbox_token
```

## Parameters

The endpoint utilizes the following parameters:

- `mapbox.places`: This specifies the Mapbox Geocoding API endpoint for searching places.

- `placeType`: This parameter is used to specify the type of place that you are searching for. In this case, it is set to pharmacy to search for pharmacies specifically. It is inserted into the URL directly after `mapbox.places/`.

- `proximity`: Specifies the longitude and latitude of the location you wish to search near. In this example, it is set to `-79.8419,35.1849`, corresponding to coordinates in North Carolina.

- `access_token`: Your Mapbox access token, required for authenticating the request.

## How it works

By utilizing the `mapbox.places` endpoint with the `pharmacy` category and providing specific geographic coordinates through the `proximity` parameter, the API retrieves information about pharmacies near the specified location. This information can then be utilized in applications to assist users in finding nearby pharmacies efficiently.
