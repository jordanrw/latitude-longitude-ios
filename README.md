Tap 1 button and receive the latitude and longitude of the iOS device

to change how specific the locaiton data is:

- (void) setUpLocation {

  ...
  
  //change the desired specifity of the location
  self.manager.desiredAccuracy = kCLLocationAccuracyBest;
  //self.manager.desiredAccuracy = kCLLocationAccuracyHundredMeters;

}
