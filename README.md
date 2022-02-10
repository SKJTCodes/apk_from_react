# apk_from_react
Build An APK From REACTJS WEB APP

## Steps
npm install -g @ionic/cli
npm install @capacitor/core @capacitor/cli
npx cap init -> fill in details
npm install @capacitor/android
ionic init -> choose react
ionic build
npx cap add android -> generates android folder
open android folder using android studios
test project using android emulator
select build from menu
select Generate Signed Bundle/APK
select APK
can create new or use existing key store
choose release variant and selet V2(Full APK Signature)
finish
