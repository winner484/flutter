# flutter note
##  Landscape mode:
    import 'package:flutter/services.dart'
    
    @override
    Widget build(BuildContext context){
    
    // Set landscape orientation
    SystemChrome.setPreferredOrientations([
       DeviceOrientation.landscapeLeft,
       DeviceOrientation.landscapeRight,
    ]);
    
    return new MaterialApp()
    }
    
##  Potrait mode:
    import 'package:flutter/services.dart'
    
    @override
    Widget build(BuildContext context){
    
    // Set landscape orientation
    SystemChrome.setPreferredOrientations([
       DeviceOrientation.protraitDown,
       DeviceOrientation.protraitUp,
    ]);
    
    return new MaterialApp()
    }
##  StatelessWidget & StatefulWidget class $ a State class

...............................................................

## flutter AVD can damage pyaudio.
...............................................................

## go-flutter
    fengyu@fengyu-desktop:~$ flutter --version
    Flutter 1.2.1 • channel stable • https://github.com/flutter/flutter.git
    Framework • revision 8661d8aecd (4 weeks age) • 2019-02-14 19:19:53 -0800
    Engine • revision 3757390fa4
    Tools • Dart 2.1.2 (build 2.1.2-dev.0.0 0a7dcf17eb)
    
### step1:
    import 'package:flutter/foundation.dart'
    show debugDefaultTargetPlatformOverride;

    void main() {
      // Desktop platforms aren't a valid platform.
      debugDefaultTargetPlatformOverride = TargetPlatform.fuchsia;
      runApp(MyApp());
    }
### step2:
  modify localhost "ws://10.0.2.2:8765" / "ws://127.0.0.1:8765"
### step3:
  repalce /demo/lib/main.dark
  modify /demo/pubspec.yaml
### step4:
  packages get
### step5:
  done.


