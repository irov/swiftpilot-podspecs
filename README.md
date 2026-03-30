# swiftpilot-podspecs

Custom CocoaPods spec repo for `PilotSDK` releases that depend on LiveKit specs from `https://github.com/livekit/podspecs.git`.

Consumer Podfile example:

```ruby
source "https://cdn.cocoapods.org/"
source "https://github.com/livekit/podspecs.git"
source "https://github.com/irov/swiftpilot-podspecs.git"

platform :ios, "13.0"

target "MyApp" do
  pod "PilotSDK", "1.0.49"
end
```