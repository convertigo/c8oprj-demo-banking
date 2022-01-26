## __Banking Demo__

Convertigo 7.9.0 Mobile Builder Banking Demo.

### __Build Application__

- Import project in your Convertigo Studio.
- Build Ionic/Angular application by double-clicking **Application** in Studio treeview.
- You may build application for Android/iOS in debug mode via Test Platform or Local Build (Cordova).
- It will import the [lib_AmazonLEX](https://github.com/convertigo/c8oprj-lib-amazonlex/tree/7.7.0) Convertigo library project, for Text-To-Speech and Speech-To-Text capabilities.

### __Login__

In browser mode, the login is made with a random keypad. **Contract** number is **123456** and **password** is **040475**.

In Cordova mode, the login is made with Fingerprint plugin, but switches to Keypad if authentication fails.

### __Usage__

After a successful login, you will have Accounts number. Only **10995** is active. It uses the Temenos API to display account balances (stubbed, so no API key is necessary, but you can connect to live API using your API key, see project for symbol and disable stub mode).

You can use the **Dialogue** tab to chat with Alexa AI. Keywords are "**accounts**", "**position**" to interact with the Amazon LEX API.