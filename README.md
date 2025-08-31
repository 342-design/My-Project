Doctor Appointment Flutter project (ready)

What I included:
- Login page (uses FakeStore API for login)
- Home page with list of doctors (static)
- Appointment page (stores appointments in Firebase Cloud Firestore)
- Firebase config file placed at: android/app/google-services.json (you uploaded this)
- Package name set to: com.hassan.doctorappointment

How to open & preview the project:

Option A — VS Code (recommended)
1. Unzip this project and open the folder in VS Code.
2. Install Flutter SDK and set up Android SDK & emulator (see https://flutter.dev/docs/get-started/install).
3. In terminal, run: flutter pub get
4. Run on emulator or device: flutter run
5. Login test credentials for FakeStore API (to get token):
   username: mor_2314
   password: 83r5^_
   (or continue without login using the button)
6. App will initialize Firebase automatically (google-services.json is present).

Option B — Zapp (online)
- Zapp sometimes hides android folder; however if Zapp allows importing a full Flutter project ZIP, upload this ZIP there.
- If Zapp blocks android or google-services.json, then use VS Code for full Firebase functionality.

Notes:
- Firestore rules: make sure in Firebase console -> Firestore -> Rules you allow reads/writes while testing.
- If you face any errors, copy the terminal output and send it to me; I will help.
