# Privacy Policy for TurboFitness

**Last updated:** May 6, 2026

TurboFitness is a personal fitness and nutrition tracking application developed by Ethan Tanous. This policy explains how the app handles your data.

## Summary

TurboFitness stores all your data locally on your device. The app does not have a backend server, does not collect analytics, and does not share your data with third parties. The only network requests the app makes are to public food databases for food lookups.

## Data Stored on Your Device

The app stores the following information locally on your device using AsyncStorage. This data never leaves your device:

- Profile information you provide during onboarding (age, sex, height, weight, activity level, goals)
- Food log entries, including foods, meals, and serving counts
- Exercise log entries
- Weight history
- App preferences and settings

You can delete all this data at any time by uninstalling the app.

## HealthKit Data (Optional)

If you grant permission, the app reads the following data from Apple HealthKit to improve calorie tracking accuracy:

- Daily step count
- Active energy burned
- Workouts

This data is read only and used only on your device for calorie calculations. The app does not write data to HealthKit and does not transmit HealthKit data anywhere. You can revoke HealthKit permissions at any time in iOS Settings → Privacy & Security → Health.

## Camera (Optional)

If you grant permission, the camera is used solely to scan barcodes for food lookup. No images are stored or transmitted. You can revoke camera permission at any time in iOS Settings.

## Network Requests to Third Parties

When you search for foods or scan a barcode, the app sends queries to the following public APIs:

- **USDA FoodData Central** ([fdc.nal.usda.gov](https://fdc.nal.usda.gov)) — for food search and nutrient data
- **Open Food Facts** ([openfoodfacts.org](https://openfoodfacts.org)) — for barcode lookups

These requests contain only the search term or barcode you submit. They do not include any personal information, account identifiers, or device identifiers from the app. Each service has its own privacy policy linked above.

## Children's Privacy

The app is not directed at children under 13. The app does not knowingly collect any data from children.

## Changes to This Policy

This policy may be updated as the app evolves. The "Last updated" date at the top reflects the most recent change.
