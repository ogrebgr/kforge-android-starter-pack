# kforge-android-starter-pack
Base setup for Android App that uses the Forge framework (Kotlin)



Steps to use it:

1. Clone the project

2. Rename dir/package

3. Change package in the manifest

4. Open assets/logback.xml and change patter (currently `+ex %msg%n`) replacing "+ex" with desired prefix for the logcat

5. Open values/build_config.xml and `build_conf_base_url` to point to your dev server

6. Build and run the app, push the button to test the connection