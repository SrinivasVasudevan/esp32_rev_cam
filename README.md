# ESP32 Reverse Camera

This project contains the files needed to build a reverse camera using the Freenove ESP32 Wrover.

![ESP32 Setup](esp32_setup.jpg)

## Checklists

### Sketch File Completion
- [x] Merge WiFi Access Point sketch
- [x] Merge Video Web Server sketch
- [x] Set up IP structure and constants

### Sketch File Testing
- [ ] Flash to ESP32 board
- [ ] Connect to `ESP32_ReverseCam` WiFi network
- [ ] Open `http://192.168.1.100` in browser to view stream

### Android App
- [ ] Initialize Android project
- [ ] Create layout with WebView or VideoView for stream
- [ ] Handle network permissions
- [ ] Test on physical Android device
