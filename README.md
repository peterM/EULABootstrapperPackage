# EULA Bootstrapper Package
ClickOnce EULA Bootstrapper package

### How to install

1. Open `regedit`
2. navigate to this path: `Computer\HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Microsoft\GenericBootstrapper`
3. take path string from property `Path`

4. copy package to path from `windows registry` to `packages` subfolder
5. replace content of `en\eula.txt` with your specific content


For more info visit MS site: [https://docs.microsoft.com/en-us/visualstudio/deployment/creating-bootstrapper-packages?view=vs-2017](https://docs.microsoft.com/en-us/visualstudio/deployment/creating-bootstrapper-packages?view=vs-2017)