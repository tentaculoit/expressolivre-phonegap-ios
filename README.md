expressolivre-phonegap-ios
==========================

Repositório do projeto IOS no Phonegap para o Expresso Livre Mobile

http://www.securitylearn.net/2012/12/26/build-ipa-file-using-xcode-without-provisioning-profile/

Crie um certificado utilizando o assistente do KeyChain

Edite
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Info.plist
Substitua as 3 ocorrências (defaultproperties, runtimerequirements, overrideproperties) do XCiPhoneOSCodeSignContext por XCCodeSignContext

Restart o Xcode

Mude o certificado do projeto no Xcode (Build Settings).

Rode o build no Xcode. Vai criar um .app no diretório abaixo.

/Users/[user name]/Library/Developer/Xcode/DerivedData/[your app]/Build/Products/Debug-iphoneos/

Use o iPhone Configuration Utility para enviar o aplicativo pro iPhone
