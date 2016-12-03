# Byte Buddy Annotations

This project contains [external annotations](https://wiki.eclipse.org/JDT_Core/Null_Analysis/External_Annotations) for
[Byte Buddy](http://bytebuddy.net/) version 1.4.30.

These annotations allow Eclipse to perform null analysis.

## Usage

To build the annotations JAR, run

```bash
gradle build
```

This will create the file `byte-buddy-annotations-1.4.30-r.1.jar`. Attach this file to the
Byte Buddy library entry in your build path to have Eclipse use the annotations.