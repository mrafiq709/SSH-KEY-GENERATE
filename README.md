# SSH-KEY-GENERATE
ssh key generation windwos

Generate ssh key:
---------------------
    Downloade openssl: https://code.google.com/archive/p/openssl-for-windows/downloads
    
    Here: "C:\Users\your_pc_user_name\Downloads\bin\openssl" is your downloaded openssl bin folder location
    
    1. Open CMD
    2. Go to C:\Program Files\Java\jdk1.8.0_211\bin
    3. Enter bellow command:
    keytool -exportcert -alias androiddebugkey -keystore C:\Users\your_pc_user_name\.android\debug.keystore | C:\Users\your_pc_user_name\Downloads\bin\openssl sha1 -binary | C:\Users\your_pc_user_name\Downloads\bin\openssl base64
    4. Enter keystore password

Genreted Key:
-------------
    "Bmce+9aHdOoVtE7fS3B07tfj7Bc=" like this one.
