# EULA Bootstrapper Package
ClickOnce EULA Bootstrapper package

### How to install

1. Open `regedit`
2. navigate to this path: `Computer\HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Microsoft\GenericBootstrapper`
    example: `C:\Program Files (x86)\Microsoft SDKs\ClickOnce Bootstrapper\Packages`
3. take path string from property `Path`

4. copy package to path from `windows registry` to `packages` subfolder
5. replace content of `en\eula.txt` with your specific content


For more info visit MS site: [https://docs.microsoft.com/en-us/visualstudio/deployment/creating-bootstrapper-packages?view=vs-2017](https://docs.microsoft.com/en-us/visualstudio/deployment/creating-bootstrapper-packages?view=vs-2017)



Inspiration to create repository from: https://stackoverflow.com/questions/834071/clickonce-ask-for-a-license-agreement/55375658#55375658
User: https://stackoverflow.com/users/48387/shay-erlichmen
