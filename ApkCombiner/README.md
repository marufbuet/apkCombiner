ApkCombiner
=======================
Combining multiple Android apps to one by inter-app analysis.

How to use it:

export PATH=$PATH:$ANDROID_SDK/build-tools/android-4.4

./runApkCombiner.sh $ANDROID_PLATFORM_PATH app1.apk app2.apk ...
```

After the execution, 
there should be an apk named app1-ac-app2.apk in the current directory.
Analyzing the new generated app to indirectly perform inter-app analysis.
