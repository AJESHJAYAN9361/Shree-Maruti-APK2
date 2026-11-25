SHREE MARUTI INTERNATIONAL RATE FINDER – ANDROID APP PROJECT

ഈ ZIP ഒരു Android Studio project ആണ്. HTML Rate Finder app Android WebView-ൽ offline ആയി തുറക്കാൻ തയ്യാറാക്കിയതാണ്.

APK നേരിട്ട് ഈ ചാറ്റിൽ compile ചെയ്തിട്ടില്ല. APK ഉണ്ടാക്കാൻ:
1. ZIP extract ചെയ്യുക.
2. Folder GitHub-ൽ പുതിയ repository ആയി upload ചെയ്യുക.
3. GitHub repository → Actions തുറക്കുക.
4. “Build Android APK” workflow തിരഞ്ഞെടുക്കുക.
5. “Run workflow” അമർത്തുക.
6. Build പൂർത്തിയായാൽ workflow run-ന്റെ Artifacts ഭാഗത്ത് നിന്ന്
   Shree-Maruti-Rate-Finder-APK download ചെയ്യുക.
7. ZIP extract ചെയ്ത് app-debug.apk Android ഫോണിൽ install ചെയ്യുക.

ശ്രദ്ധിക്കുക: Android ഫോണിൽ APK install ചെയ്യുമ്പോൾ “Install unknown apps” അനുമതി ആവശ്യമായി വരാം.
ഇത് DEBUG APK ആണ്; Play Store release/signing ചെയ്ത APK അല്ല.

Rate data ഈ HTML-ൽ embed ചെയ്ത October Rate Chart പതിപ്പാണ്. Excel rate chart പുതുക്കുമ്പോൾ app asset HTML-യും update ചെയ്ത് APK വീണ്ടും build ചെയ്യണം.
