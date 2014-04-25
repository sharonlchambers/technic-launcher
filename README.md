technic-launcher
================

error message i received trying to launch my technic launcher told me to post this message here:

( Please submit this report to https://github.com/TechnicPack/TechnicLauncher/issues )
    Launcher Build: 439
 
    Selected Pack: null
Stack Trace:
    Exception: NoClassDefFoundError
    Message: sun/security/x509/X509CertImpl
    Trace:
        sun.security.provider.X509Factory.engineGenerateCertificate(Unknown Source)
        java.security.cert.CertificateFactory.generateCertificate(Unknown Source)
        sun.security.pkcs.PKCS7.parseSignedData(Unknown Source)
        sun.security.pkcs.PKCS7.parse(Unknown Source)
        sun.security.pkcs.PKCS7.parse(Unknown Source)
        sun.security.pkcs.PKCS7.<init>(Unknown Source)
        sun.security.util.SignatureFileVerifier.<init>(Unknown Source)
        java.util.jar.JarVerifier.processEntry(Unknown Source)
        java.util.jar.JarVerifier.update(Unknown Source)
        java.util.jar.JarFile.initializeVerifier(Unknown Source)
        java.util.jar.JarFile.getInputStream(Unknown Source)
        sun.misc.URLClassPath$JarLoader$2.getInputStream(Unknown Source)
        sun.misc.Resource.cachedInputStream(Unknown Source)
        sun.misc.Resource.getByteBuffer(Unknown Source)
        java.net.URLClassLoader.defineClass(Unknown Source)
        java.net.URLClassLoader.access$100(Unknown Source)
        java.net.URLClassLoader$1.run(Unknown Source)
        java.net.URLClassLoader$1.run(Unknown Source)
        java.security.AccessController.doPrivileged(Native Method)
        java.net.URLClassLoader.findClass(Unknown Source)
        java.lang.ClassLoader.loadClass(Unknown Source)
        java.lang.ClassLoader.loadClass(Unknown Source)
        sun.misc.Launcher$AppClassLoader.loadClass(Unknown Source)
        java.lang.ClassLoader.loadClass(Unknown Source)
        sun.security.jca.ProviderConfig$2.run(Unknown Source)
        sun.security.jca.ProviderConfig$2.run(Unknown Source)
        java.security.AccessController.doPrivileged(Native Method)
        sun.security.jca.ProviderConfig.doLoadProvider(Unknown Source)
        sun.security.jca.ProviderConfig.getProvider(Unknown Source)
        sun.security.jca.ProviderList.getProvider(Unknown Source)
        sun.security.jca.ProviderList.getService(Unknown Source)
        sun.security.jca.GetInstance.getInstance(Unknown Source)
        javax.net.ssl.SSLContext.getInstance(Unknown Source)
        javax.net.ssl.SSLContext.getDefault(Unknown Source)
        javax.net.ssl.SSLSocketFactory.getDefault(Unknown Source)
        javax.net.ssl.HttpsURLConnection.getDefaultSSLSocketFactory(Unknown Source)
        javax.net.ssl.HttpsURLConnection.<init>(Unknown Source)
        sun.net.www.protocol.https.HttpsURLConnectionImpl.<init>(Unknown Source)
        sun.net.www.protocol.https.Handler.openConnection(Unknown Source)
        sun.net.www.protocol.https.Handler.openConnection(Unknown Source)
        java.net.URL.openConnection(Unknown Source)
        net.technicpack.launchercore.auth.AuthenticationService.postJson(AuthenticationService.java:54)
        net.technicpack.launchercore.auth.AuthenticationService.requestRefresh(AuthenticationService.java:42)
        net.technicpack.launchercore.install.user.UserModel.AttemptUserRefresh(UserModel.java:64)
        net.technicpack.launchercore.install.user.UserModel.AttemptLastUserRefresh(UserModel.java:60)
        org.spoutcraft.launcher.launcher.Launcher.startup(Launcher.java:91)
        org.spoutcraft.launcher.entrypoint.SpoutcraftLauncher.main(SpoutcraftLauncher.java:97)
        org.spoutcraft.launcher.entrypoint.Start.launch(Start.java:141)
        org.spoutcraft.launcher.entrypoint.Start.main(Start.java:46)
 
System Information:
    Operating System: Windows Vista
    Operating System Version: 6.0
    Operating System Architecture: x86
    Java version: 1.7.0_55 32 bit
    Total Memory: 29 MB
    Max Memory: 247 MB
    Memory Free: 4 MB
    CPU Cores: 2
    
