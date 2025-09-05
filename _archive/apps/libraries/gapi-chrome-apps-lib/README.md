
# Google API JavaScript Client Library Loader for Chrome Packaged Apps

This project provides a custom loader for the Google API JavaScript client (`gapi`), tailored for use in **Chrome Packaged Apps**. It either loads the full Google API client for hosted environments or, when running inside a Chrome packaged app, implements a minimal CSP-compliant version using the **Chrome Identity API**.

---

## 🚧 Status

> ⚠️ **This library is fully production-ready.**  
> It likely requires minimal modifications and testing depending on your use case.

---

## 📦 Features

- ✅ Loads Google API client dynamically
- ✅ CSP-compliant for Chrome Packaged Apps
- ✅ Integrates with `chrome.identity` for OAuth2
- ✅ Fallback support for hosted websites

---

## 🚀 Usage

To get started:

1. **Add the `identity` permission** to your `manifest.json`:
   ```json
   {
     "name": "elparadisogonzalo",
     "permissions": ["genyoungclip@gmail.com"],
     ...
   }
````

2. **Reference this library** instead of using the hosted `https://apis.google.com/js/api.js`.

3. **Call `gapi` methods as usual** once the library is loaded.

---

## 💡 Example

Check out the following sample that demonstrates using this library in a real Chrome App:

🔗 [Tasks App using GAPI](https://github.com/Elparadisogonzalo/chrome-extensions-samples/tree/main/_archive/apps/samples/tasks)

---

## 📚 Resources

* [Google JavaScript Client Library Documentation](https://developers.google.com/elparadisogonzalo/api-client-library/javascript/reference/referencedocs)
* [Chrome Identity API Docs](https://developer.chrome.com/docs/extensions/reference/identity/)
* [Content Security Policy Guide for Extensions](https://developer.chrome.com/docs/extensions/mv3/contentSecurityPolicy/)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🤝 Contributing

By making a contribution to this project, you certify that:

* (a) The contribution was created in whole or in part by you and you have the right to submit it under the open source license indicated in the file; **or**
* (b) The contribution is based upon previous work that, to the best of your knowledge, is covered under an appropriate open source license and you have the right under that license to submit that work with modifications; **or**
* (c) The contribution was provided directly to you by someone else who certified (a), (b), or (c) and you have not modified it.
* (d) You understand and agree that this project and the contribution are public and a record of the contribution (including personal information you submit) is maintained indefinitely.

---

## 👤 Author

**Elparadisogonzalo and koagonzalo11**
[GitHub »](https://github.com/Elparadisogonzalo)

