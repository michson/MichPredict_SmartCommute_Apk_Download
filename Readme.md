📱 Transport Delay Predictor — User Guide
This guide walks you through installing, setting up, and using the Transport Delay Predictor app on your Android device.

🚀 Getting Started
Installing the App
Step 1: Allow Installation from Unknown Sources
Because this app is installed via an APK, Android needs your permission first.
Open Settings on your phone
Go to Security
On newer Android versions: Apps → Special App Access
Enable Install Unknown Apps or Unknown Sources
Choose the app you’ll use to install the APK (your browser or file manager)
Tip: On Android 8.0 and above, this permission is granted per app, not globally.
Step 2: Download & Install the APK
Download the APK file to your phone
Tap the downloaded file
Select Install
Wait for the installation to finish
Tap Open to launch the app
⚙️ First-Time Setup
Step 1: Set Up the Backend URL
When you open the app for the first time, you’ll be asked to connect to the backend API.
You’ll see the Backend Configuration screen
Enter your backend API URL
Example: http://192.168.1.100:5000
Tap Connect to test the connection
Once connected, you’ll move to onboarding
How to Find Your Backend URL
Local server
Windows: Open Command Prompt → type ipconfig → look for IPv4 Address
macOS/Linux: Open Terminal → run ifconfig or ip addr
Remote server: Use the server URL provided to you
⚠️ Your phone and server must be on the same Wi-Fi network if using a local server
Step 2: Onboarding
Swipe through the onboarding screens to learn what the app can do.
Tap Get Started (or Skip) when you’re ready.
Step 3: Create an Account
Tap Sign Up
Enter:
Full Name
Email Address
Password (minimum 6 characters)
Confirm Password
Tap Sign Up to continue
Step 4: Choose Your Role
Select how you plan to use the app:
Commuter — Plan trips and get delay predictions
Operator — Analyze delay risks and monitor transport performance
You can switch roles anytime from your profile.
📊 Using the App
Home Dashboard
Your dashboard gives you a quick overview:
Quick Stats — Total predictions and model accuracy
Best Model — The AI model currently in use
Quick Action — Start a new prediction instantly
🚍 Making a Prediction (Commuter Mode)
Tap Predict Delay from the dashboard or bottom menu
Enter trip details:
Transport type (Bus, Tram, Metro, Train)
Departure hour (0–23)
Peak hour (Yes / No)
Day of the week
Holiday (Yes / No)
Season
Weather condition
Tap Predict Delay
View your results:
Status: On Time or Delayed
Delay Probability
Visual Probability Bars
Trip Summary
📈 Analyzing Delay Risk (Operator Mode)
Operator mode includes advanced analysis tools.
Fill in standard trip details
Add advanced data:
Temperature (°C)
Humidity (%)
Wind speed (km/h)
Precipitation (mm)
Event type (Sports, Protest, Concert, etc.)
Traffic congestion index (0–100)
Origin & destination stations
Route ID
Tap Analyse Delay Risk
Review detailed insights:
SHAP visualizations (shows what influenced the prediction)
Full probability breakdown
All input parameters
🧭 Navigation Overview
Home — Dashboard and quick stats
Predict — New predictions and analyses
Profile — Account settings and preferences
👤 Profile & Settings
From the Profile tab you can:
View account details
Switch between Commuter and Operator modes
Update backend URL
Sign out
🛠️ Troubleshooting
App Can’t Connect to Backend
Possible fixes:
Double-check the backend URL (must start with http:// or https://)
Remove any trailing slash
Ensure phone and server are on the same network
Try opening the backend URL in your phone’s browser
Confirm the backend server is running
Check firewall or port restrictions (e.g., port 5000)
App Crashes or Freezes
Try the following:
Restart the app
Clear app data
Settings → Apps → Transport Delay Predictor → Storage → Clear Data
Reinstall the APK if needed
Can’t Sign In
Confirm email and password are correct
Contact the admin for password reset
Try creating a new account with a different email
Predictions Show Zero or Incorrect Values
Ensure backend is connected
Confirm backend API is running
Check network stability
Restart the app
📱 System Requirements
Android: Version 5.0 (API 21) or higher
Storage: Minimum 50 MB free space
Network: Wi-Fi or mobile data
Permissions:
Internet access
Network state access
✨ Key Features
✅ Two user modes: Commuter & Operator
✅ Fast, real-time delay predictions
✅ Advanced analytics with SHAP explanations
✅ Clean, modern user interface
✅ Secure authentication
✅ Offline access (predictions require internet)
