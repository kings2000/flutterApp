# myappv4

A new Flutter application.

## Getting Started

Run the command to make a build for only armabi-v7a devices

`flutter build apk --debug --target-platform android-arm`

Test the apk build in NoxPlayer or LdPlayer emulator

`ndk {
            abiFilters 'armeabi-v7a'
  }
  `
  This is already added to the android graddle file.
  
