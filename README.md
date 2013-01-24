# Apk/Zip signing tool pulled out of the AOSP

## Source

The code is taken as is from build/tools/signapk/SignApk.java from the git 
repo at: https://android.googlesource.com/platform/build
and is just here for convenient access along with a prebuilt jarfile.

## Usage

Eg.

    java -jar prebuilt/aospsign.jar -w key-name.x509.pem key-name.pk8 unsigned.zip signed.zip
