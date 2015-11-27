This is the Swing version of JarSniffer(http://jarsniffer.org) web app.

It is a tool which helps in finding the jar files in which a given Class name is present. It may be helpful in resolving the ClassNotFoundExceptions which may occur while deploying the Java Enterprise Applications containing tens of jar files.

It takes the name of a class file as input and searches in the available jar files present in your local repository of jarfiles (this is nothing but a filesystem folder which you will set in the settings panel of the tool).

Either Fully qualified class name like 'org.jfree.util.Log' or just file name like 'Log' can be given.