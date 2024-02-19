# Android build environment

## Building image

```
docker build \
-t android_gaetan \
--target complete \
--build-arg ANDROID_SDK_TOOLS_TAGGED="tagged" \
--build-arg ANDROID_SDK_TOOLS_VERSION="11076708" \
--build-arg ANDROID_SDKS="tagged" \
--build-arg NDK_VERSION="26.2.11394342" \
.
```

## Using image



## NOTES

### ANDROID_SDK_TOOLS_VERSION

Values for this build argument can be found at the bottom of this page: https://developer.android.com/studio#command-tools ("Command line tools only" section)
