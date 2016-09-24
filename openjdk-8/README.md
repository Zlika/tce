# OpenJDK-8 for Tiny Core Linux
Build script to generate OpenJDK-8 extensions for Tiny Core Linux:
* openjdk-8-jdk.tcz: Java 8 SDK
* openjdk-8-jre.tcz: Java 8 Runtime with full JRE
* openjdk-8-jre-compact1.tcz: Java 8 Runtime with Compact 1 JRE profile
* openjdk-8-jre-compact2.tcz: Java 8 Runtime with Compact 2 JRE profile
* openjdk-8-jre-compact3.tcz: Java 8 Runtime with Compact 3 JRE profile
* openjdk-8-doc.tcz: man pages

For x86, the JDK/JRE packages only include the Minimal VM (smallest footprint with nearly same performance as Client VM).
For ARM, the JDK/JRE packages only include the Zero VM (slowest but currently only OpenJDK VM available)
