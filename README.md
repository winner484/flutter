# flutter
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
