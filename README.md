# RDProject 
 convert jks to p12 file above code
 give path of jks and p12 file the name and extension
 if error of key tool is there 
 
 with password
  [comment]: <> ( keytool -importkeystore -srckeystore C:\Users\baps\AndroidStudioProjects\RDProject\keys\filename.jks -destkeystore C:\Users\baps\AndroidStudioProjects\RDProject\keys\filename.p12 -srcstoretype JKS -deststoretype PKCS12 -deststorepass 123456)

 without password
  [comment]: <> (keytool -importkeystore -srckeystore C:\Users\baps\AndroidStudioProjects\RDProject\keys\keyStore.jks -srcstoretype JKS -deststoretype PKCS12 -destkeystore C:\Users\baps\AndroidStudioProjects\RDProject\keys\filename.p12)