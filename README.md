# Experiment 5 - Weather app (Fetch API)
Uses the free Open-Meteo geocoding and forecast APIs (no API key). Uses fetch() with async/await and error handling. Needs an internet connection.
To use Axios instead, replace each fetch(url).json() with (await axios.get(url)).data and add the Axios CDN script.


**Bootstrap (minimal):** Bootstrap 5 via CDN; uses `card`, `form-control`, `btn btn-primary` and `alert alert-danger` for error messages.
