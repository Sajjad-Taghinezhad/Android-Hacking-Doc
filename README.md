# Documents 

### Create Key for signing apps 
    keytool -genkey -v -keystore my-keystore.keystore -alias name_alias -keyalg RSA -validity 10000

### Sign app
    jarsigner -verbose -keystore <path of my-keystore.keystore> <path of apk>  name_alias
