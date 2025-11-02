Vedic Kundali - Android Demo Project
===================================

This ZIP contains a minimal Android Studio project skeleton for a Vedic Kundali app.
It is a demo/skeleton and **does not** include the Swiss Ephemeris binaries required
for precise astronomical calculations.

What to do after download:
1. Open this project in Android Studio (File -> Open).
2. Add the Swiss Ephemeris Java port jar (swisseph.jar) to `app/libs/` if you need accurate positions.
   - Download Swiss Ephemeris Java port and place the jar in app/libs/.
   - Place ephemeris files in `app/src/main/assets/ephe/`.
3. Build the app: Build -> Build Bundle(s) / APK(s) -> Build APK(s).
4. The debug APK will be available at `app/build/outputs/apk/debug/app-debug.apk`.

If you want a downloadable .apk without Android Studio, push this project to a GitHub repo
and use the provided GitHub Actions workflow (in .github/workflows/) to build APK artifacts.

Notes:
- This project includes a small curated `lalkitab.json` in assets.
- To enable full Ashtakoota matchmaking and divisional charts, I can provide the full modules
  and instructions to add Swiss Ephemeris integration.

