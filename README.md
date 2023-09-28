# GPX File Processing Script

This shell script processes GPX files and extracts latitude and longitude coordinates to create new track files.

## Prerequisites

Before using this script, make sure you have the following:

- GPX files in the `raw_gpx` and `new_tracks` folder.
- Bash shell environment.

## Usage

1. Place your GPX files in the `raw_gpx` folder.

2. Run the script:

   ```bash
   ./generate_gpx.sh
   ```

3. The script will process each GPX file in the `raw_gpx` folder, extract latitude and longitude coordinates, and create corresponding track files in the `new_tracks` folder.

4. You can find the extracted coordinates in the `new_tracks` folder.

## Example

For each GPX file, the script extracts coordinates in the following format:

```plaintext
lat="14.6558441" lon="121.0295923"
```

## Notes

- For educational purposes only.
- A personalized script


## Useful link

- https://www.groovypost.com/howto/export-google-maps-route-data/
- https://mapstogpx.com/
- https://www.google.com/maps/
