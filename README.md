# pyenv

### Tricks

If the regular `pyenv install python-version` is not working, try below:
```bash 
SDKROOT=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.14.sdk MACOSX_DEPLOYMENT_TARGET=10.14 pyenv install 3.8.6
```
