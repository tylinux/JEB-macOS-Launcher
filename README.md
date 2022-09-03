# JEB-macOS-Launcher

Installing JEB as a self-contained macOS .app (without contaminating your system with having to install Java):

> Copy from [Ghidra-OSX-Launcher](https://gist.github.com/yifanlu/e9965cdb148b550335e57899f790cad2)

## Build your own

1. Download and extract the launcher AppleScript template app below. Optionally modify `JEB.app/Info.plist` to your liking.
2. Put your `JEB` folder to  `JEB.app/jeb`.
3. use `brew install openjdk` or other method install JDK.

> Note that the template .app is just a standard AppleScript generated .app. If you don't trust the binary, you can build your own with the provided AppleScript and replace `JEB.app/Contents/Resources/Scripts/main.scpt`.
