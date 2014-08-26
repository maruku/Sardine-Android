Sardine-Android
===============

WebDav lib for android

fork from https://github.com/aflx/Sardine-Android

Changes
- Change default auth scheme from Basic to Digest
- Add len parameter for put api when using InputStream
- Fix getcontentlength and change XML type to String
- Done't add "Expect" http header because lighthttpd will return 417 error