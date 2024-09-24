# base ecom expo

1. Create : 
npx create-expo-app@latest . -t 

2. Test run : 
npm run ios or npx expo run:ios

3. Build : 
npx expo prebuild

4. Install : (not working)
gem install bundler





5. Add fastlane to ios : 
cd ios bundler init bundler add fastlane bundle install 
fastlane init

6. Add fastlane to andriod : 
cd andriod bundler init bundler add fastlane bundle install
fastlane init
fastlane add_plugin increment_version_code