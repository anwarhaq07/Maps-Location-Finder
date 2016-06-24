# Maps-Location-Finder

Create new project in Android Studio.
Select the “Google Maps Activity” as the template for the Activity and then finish creating the project:
Your new project should start with google_maps_api.xml open, but if not, you can find it in res/values. This file contains helpful comments about what you need to get started. It even has a URL! Basically all you need to do is visit this personalized link and sign up for a Google Maps API Key. It’s free to sign up if you don’t already have an account, and when you get a key from that site you come back to this file and replace YOUR_KEY_HERE with your new key.

Check for these dependencies in gradle
dependencies {
    compile fileTree(dir: 'libs', include: ['*.jar'])
    testCompile 'junit:junit:4.12'
    compile 'com.android.support:appcompat-v7:23.4.0'
    compile 'com.google.android.gms:play-services:9.0.2'
}
