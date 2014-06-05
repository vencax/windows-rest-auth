# windows-rest-auth

Inspired by [PGina](https://github.com/pgina/pgina/) and its more radical [fork by MutonUfoAI](https://github.com/MutonUfoAI/pgina) I was gradually telling myself why such complex way? I would like a CredentialProvider (CP) that sends a http request and gets JSON response with all the necessary info it needs. 

## Pros
- Simplicity. No complex other languages binding, database support, plugins, etc.
- Installabe thgrough simple script (copy to Win32/64 folder) and add few register keys.
Automatic installation is key feature.
Me as admin I don't want to go and install or manually configure it for every single machine I have.
- Easily configurable (only URL?) which can live within registers as well.

## some useful links
Because lack of documentation and examples or hands on from Micro$oft I share what I googled and consider useful:
- Few tips by [Alun Jones](http://msmvps.com/blogs/alunj/archive/2011/02/21/1788561.aspx)
- [Article iven with some code](http://blog.leetsys.com/2012/01/02/capturing-windows-7-credentials-at-logon-using-custom-credential-provider/)
how to write wrapped CP.
- [yubicoCP](https://github.com/Yubico/yubico-windows-auth)
- [Another wrapped CP provider](https://github.com/greylon/automatic-intranet-login/) project sample
- [Visual Studio 2012 Express for Windows Desktop](http://www.microsoft.com/en-us/download/details.aspx?id=34673) for actual devel.
- [SDK version list](https://developer.mozilla.org/en-US/docs/Windows_SDK_versions#Windows_7_SDK)
