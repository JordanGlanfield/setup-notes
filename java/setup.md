- Pretty easy to install a JDK from IntelliJ https://www.jetbrains.com/help/idea/sdk.html#add_global_sdk
- Amazon Corretto seems like a good shout. Check current LTS version https://aws.amazon.com/corretto/faqs/#support_calendar
- The JDK will be installed locally to your user profile
- Set your $JAVA_HOME environment variable to the top level folder of your JDK installation (the one above bin). If want to do this for a non-admin account can follow this https://howtodoinjava.com/java/java-security/windows-set-environment-variables-without-admin-access/
- Can update system $JAVA_HOME variable to same folder if wish ^
- Need to add %JAVA_HOME%\bin to main path variable

Running things:
- java -cp "JAR path" "Main class fully qualifed name"