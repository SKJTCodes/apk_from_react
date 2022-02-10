# apk_from_react
Build An APK From REACTJS WEB APP

## Steps
1. npm install -g @ionic/cli
2. npm install @capacitor/core @capacitor/cli
3. npx cap init -> fill in details
4. npm install @capacitor/android
5. ionic init -> choose react
6. ionic build
7. npx cap add android -> generates android folder
8. open android folder using android studios
9. test project using android emulator
10. select build from menu
11. select Generate Signed Bundle/APK
12. select APK
13. can create new or use existing key store
14. choose release variant and selet V2(Full APK Signature)
15. finish
