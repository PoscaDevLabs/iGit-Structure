# Tutorial
Here’s how you can make your own IPA file without a Mac or iPad

# Step One:
Fork this repository. On your screen you should see Fork click it and fork the repository.
# Step Two: 
replace every blank file with your own code. The only files are Info.plist App.swift (in Sources) and build.yml (in .github/workflows) and you can replace everything in them with your code.
# Step Three: 
once done, go to the actions tab (or click the more button and tap actions) and click build AppName. Once completed it’ll show you a check mark to download your IPA file go to actions tab the title (you cannot tap anything else except for the title) click Artifacts then download the zip.

# Extracting the ZIP:
# iPadOS or iOS:
double tap the zip then you should see an IPA file.
# Windows:
right click the zip file then click extract or extract with… if you’ve installed another zip extractor
# Android (Samsung):
long hold down the zip then click extract.


# NOTES:
You must know swift or have swift code to do this and proper YAML code if you mess a thing up it may not work or your app will be broken.

