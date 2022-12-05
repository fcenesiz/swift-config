# swift-config
Some configurations for swift

## visual studio code

download extension: ``code_runner``

settings-> Code-runner:Executer Map-> Edit in settings.json

add to ``"code-runner.executorMap"``

this ``"swift": "swiftc -sdk %sdkroot% -o $fileNameWithoutExt.exe $fileName && $fileNameWithoutExt.exe"``
