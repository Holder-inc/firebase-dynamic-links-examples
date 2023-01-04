# firebase-dynamic-links-examples

## Getting Started

```
$ git clone --recursive https://github.com/Holder-inc/firebase-dynamic-links-examples.git
```

## Reproduce Example Packages

### submodule

```
$ mkdir submodules
$ git submodule add https://github.com/firebase/flutterfire.git ./submodules/flutterfire
```

### Symbolic Links

```
$ mkdir examples
$ cd examples
$ ln -sfn ../submodules/flutterfire/packages/firebase_dynamic_links/firebase_dynamic_links/example/ ./example
```

### flutter create

```
$ flutter create -i swift --org=io.flutter.plugins.firebase.dynamiclinksexample ./dynamiclinksexample_flutterfire_swift
$ flutter create -i objc --org=io.flutter.plugins.firebase.dynamiclinksexample ./dynamiclinksexample_flutterfire_objc

$ flutter create -i swift --org=com.emotion-recycle.emotion-recycle ./dynamiclinksexample_emotion_recycle_swift
$ flutter create -i objc --org=com.emotion-recycle.emotion-recycle ./dynamiclinksexample_emotion_recycle_objc
```



### Set up with Firebase

### ios via Xcode

- GoogleService-Info.plist
- Runner.entitlements
- Podfile

### flutter

- firebase_options.dart
- main.dart
