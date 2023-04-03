## Umbrel Community App Store Template

This repository is an Umbrel Community App Store trying to set up a XMR miner. Please feel free to review and make additions and edits as you feel right [Official Umbrel App Store](https://github.com/getumbrel/umbrel-apps).



### Technical Details

This is an app store dedicated to XMR fans who love the tech behind it and want to contribute to its enhancement. 
- `id` - XMRD; I call it the XMRDocker umbrel market place
- `name` - XMRD.


### Testing

To test your community app store, you can add this repository through the Umbrel user interface as shown in the following demo:


https://user-images.githubusercontent.com/10330103/197889452-e5cd7e96-3233-4a09-b475-94b754adc7a3.mp4


Alternatively, you can use the Umbrel CLI as described below.

To add an app store:
```
sudo ~/umbrel/scripts/repo add https://github.com/getumbrel/umbrel-community-app-store.git

sudo ~/umbrel/scripts/repo update
```

To install an app from the app store
```
sudo ~/umbrel/scripts/app install sparkles-hello-world
```

To remove an app store:
```
sudo ~/umbrel/scripts/repo remove https://github.com/getumbrel/umbrel-community-app-store.git
```
