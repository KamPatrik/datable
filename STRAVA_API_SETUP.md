# 🔑 Strava API Setup Guide

## Why Do I Need My Own API Credentials?

Strava's API policy allows **only ONE user per API application**. This means everyone using this app needs their own Strava API credentials. Don't worry - it's **FREE** and takes only **2 minutes**! 🎉

---

## 📋 Step-by-Step Instructions

### Step 1: Go to Strava API Settings
Visit: **https://www.strava.com/settings/api**

(You'll need to be logged into your Strava account)

---

### Step 2: Create a New Application

Click the **"Create an App"** button (or use an existing one if you have it)

---

### Step 3: Fill in the Application Details

Enter the following information:

- **Application Name**: `My Datable App` (or any name you like)
- **Category**: `Data Analysis`
- **Club**: Leave blank
- **Website**: `https://kampatrik.github.io/datable/`
- **Authorization Callback Domain**: `kampatrik.github.io` *(no https://, just the domain)*
- **Application Description**: `Personal activity tracker` (optional)

---

### Step 4: Click "Create"

After clicking Create, Strava will show you your application details.

---

### Step 5: Copy Your Credentials

You'll see two important values:

- **Client ID**: A number (e.g., `105945`)
- **Client Secret**: A long string of letters and numbers (e.g., `4a765020553c25ab1f555cc5a35e94ba6b985b09`)

**Copy both of these!** 📋

---

### Step 6: Enter Credentials in Datable

1. Go to **Settings** in the Datable app
2. Find the **"Strava API Credentials"** section
3. Paste your **Client ID**
4. Paste your **Client Secret**
5. Click **"Save API Credentials"**

---

### Step 7: Connect to Strava

Now you can click **"Connect with Strava"** and authorize the app!

---

## 🔒 Security & Privacy

- **Your credentials are stored in YOUR Firebase account**
- They are encrypted and protected by Firebase security rules
- Only YOU can access them (tied to your user account)
- They sync across all your devices - enter once, use everywhere!
- They are only used to authenticate with Strava's API
- You can delete them anytime from Settings

---

## ❓ Troubleshooting

### "Authorization Callback Domain Mismatch"
Make sure you entered **exactly**: `kampatrik.github.io` (no `https://`, no trailing `/`)

### "Invalid Client ID or Secret"
- Double-check you copied the entire Client Secret (it's long!)
- Make sure there are no extra spaces before or after
- Try copying again from Strava

### "Strava Redirecting to localhost"
- Go to https://www.strava.com/settings/apps
- Click "Revoke Access" on your app
- Clear browser cache
- Try connecting again with the new credentials

---

## 🎉 That's It!

You're all set! Your Datable app will now work with YOUR Strava data using YOUR API credentials.

**Happy tracking!** 🏃‍♂️🚴‍♀️

---

**Questions?** Check the main README.md or open an issue on GitHub.
