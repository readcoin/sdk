# READCOIN SDK

### Requirements
1. Android 21 above
2. DevKey register from readcoin

### SETUP

1. Add this line to app's **build.gradle**
```
implementation "io.gitlab.ikaros0503:readcoin-sdk:1.0.4"
```

2. Add this line to ***AndroidManifest.xml***

```
<meta-data android:name="in.readcoin.sdk.Key"
  android:value="{your dev key}" />
```

3. Init sdk
```
 SdkHelper.init(context: Context, createWalletIfEmpty: Boolean, [callback: SdkHelper.InitializeCallback])
```

4. Init publisher repository
```
ReadCoinRepository.create()
```

### Using wallet activity
To use wallet activity, register our wallet activity to your **AndroidManifest.xml**
```
<activity android:name="com.ss.readcoin.sdk.views.activities.wallet.WalletActivity"></activity>
```

### Javadocs
[Javadocs](https://readcoin.github.io/sdk/index.html)

