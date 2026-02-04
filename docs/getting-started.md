# 🚀 Initial Setup

This one-time setup will get you up and running with TeachLens.

## Step 1: Activate Your License
The first time you open TeachLens, you will be prompted to enter your license key.

1.  **Find Your Key:** Your license key was sent to the email address you used during purchase. It's a long string of characters.
2.  **Enter the Key:** Copy the entire key and paste it into the activation field.
3.  **Activate:** Click the "Activate" button.

Once activated, your license is locked to your device and cannot be used on another computer.

## Step 2: Set Your Password
For enhanced security, TeachLens requires you to set up a password to protect your local data. This ensures that only you can access your assessments, student responses, and analysis results.

The first time you launch TeachLens after activating your license, you will be guided through the password creation process.

1.  **Enter Your New Password:** Choose a strong, memorable password.
2.  **Confirm Your Password:** Re-enter the same password to ensure there are no typos.
3.  **Save:** Click "Set Password" to secure the application.

From then on, you will be asked to enter this password every time you open the application.

### Forgetting Your Password
If you forget your password, you can use the "Forgot Password" link on the login screen. This will require you to re-verify your original license key to reset access.

> **Important:** Your password only protects the data on your local device. It is not stored online and cannot be recovered by TeachLens support if you lose both your password and your license key.

## Step 3: Get Your Google AI API Key
TeachLens uses Google's powerful Gemini models to generate high-quality assessment content. To use this feature, you need an API key from Google AI Studio. Your key is encrypted and stored securely and locally on your device.

1.  **Visit Google AI Studio:** Open your web browser and go to [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey).
2.  **Sign In:** Sign in with your Google account.
3.  **Create API Key:** Click on **"Create API key"**. You can create a key in a new or existing Google Cloud project. Follow the on-screen instructions.
4.  **Copy Your Key:** A new API key will be generated. It's a long string of random characters. Click the copy icon next to it.

> **Free vs. Paid Usage:** Google provides a generous **free tier** for the Gemini API which is sufficient for most teachers' day-to-day needs. If you are a heavy user and generate a very large number of assessments, you may need to enable billing on your Google Cloud project to move to a pay-as-you-go plan.

> **Important:** Treat your API key like a password. Do not share it publicly.

## Step 4: Configure TeachLens Settings
Now, let's add your new API key to TeachLens.

1.  **Navigate to Settings:** In the TeachLens app, click on the **Settings** icon in the left-hand sidebar.
2.  **Paste Your Key:** In the "Gemini API Key" field, paste the key you copied from Google AI Studio.
3.  **Select a Model (Optional):**
    *   **Gemini 1.5 Flash:** Recommended for most users. It's fast and provides a great balance of quality and cost.
    *   **Gemini 1.5 Pro:** More powerful for complex topics, but slightly slower.
4.  **Save Settings:** Click the **"Save All Settings"** button.

You are now ready to start creating assessments!
