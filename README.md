## Add more

1. Sertings.gradle
   change `repositoriesMode.set(RepositoriesMode.PREFER_PROJECT)`

2. Pb with printenv in android studio

```
Caused by: java.io.IOException: Cannot run program “node”: error=2, No such file or directory

```

Then run:

`chmod +x /Applications/Android\ Studio.app/Contents/bin/printenv`

3. set the JDK version to 11 in gradle settigngs (View > Tools > Gradle)

4. add google() in settings.gradle

5. run `yarn react-native run-android`to generate PackageList. It resolves the android studio error
