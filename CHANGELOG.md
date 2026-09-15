# Change Log for Amazon Corretto 27

The following sections describe the changes for each release of Amazon Corretto 27.

## Corretto version: 27.0.0.35.1
Release Date: September 15, 2026

**Target Platforms<sup>1</sup>**
 
+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macos 14.0 and later, x86_64
+ macos 14.0 and later, aarch64

 **1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
 in the Amazon Corretto FAQ for supported platforms
 
 The following issues are addressed in 27.0.0.35.1:
 
 | Issue Name       | Platform | Description                                | Link                                                               |
 |------------------|----------|--------------------------------------------|--------------------------------------------------------------------|
 | Import jdk-27+35 | All      | Updates Corretto baseline to OpenJDK 27+35 | [jdk-27+35](https://github.com/openjdk/jdk/releases/tag/jdk-27+35) |
 | JDK-8388214, JDK-8391256, JDK-8390380  | All | Updates Timezone Data to tzdata2026c | [#3](https://github.com/corretto/corretto-27/pull/4)|
 | JDK-8390874 | All | MethodData::extra_data_lock memory leak | [#5](https://github.com/corretto/corretto-27/pull/5) |

 

## Corretto version: 27.0.0.34.1
Release Date: August 22, 2026

**Target Platforms<sup>1</sup>**
 
+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macos 14.0 and later, x86_64
+ macos 14.0 and later, aarch64

 **1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
 in the Amazon Corretto FAQ for supported platforms
 
 The following issues are addressed in 27.0.0.34.1:
 
 | Issue Name       | Platform | Description                                | Link                                                               |
 |------------------|----------|--------------------------------------------|--------------------------------------------------------------------|
 | Import jdk-27+34 | All      | Updates Corretto baseline to OpenJDK 27+34 | [jdk-27+34](https://github.com/openjdk/jdk/releases/tag/jdk-27+34) |

## Corretto version: 27.0.0.33.1
Release Date: August 7, 2026

**Target Platforms<sup>1</sup>**
 
+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macos 14.0 and later, x86_64
+ macos 14.0 and later, aarch64

 **1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
 in the Amazon Corretto FAQ for supported platforms
 
 The following issues are addressed in 27.0.0.33.1:
 
 | Issue Name       | Platform | Description                                | Link                                                               |
 |------------------|----------|--------------------------------------------|--------------------------------------------------------------------|
 | Import jdk-27+33 | All      | Updates Corretto baseline to OpenJDK 27+33 | [jdk-27+33](https://github.com/openjdk/jdk/releases/tag/jdk-27+33) |