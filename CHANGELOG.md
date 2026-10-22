# Change Log for Amazon Corretto 27

The following sections describe the changes for each release of Amazon Corretto 27.

## Corretto version: 27.0.1.0.10
Release Date: October 20, 2026

**Target Platforms**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macOS 15.0 and later, x86_64
+ macOS 15.0 and later, aarch64

**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 27.0.1.0.10:

| Issue Name | Platform | Description | Link |
|------------|----------|-------------|------|
| Import jdk-27.0.1+9 | All | Updates Corretto baseline to OpenJDK 27.0.1+9 | [jdk-27.0.1+9](https://github.com/openjdk/jdk27u/releases/tag/jdk-27.0.1+9) |
| Align Corretto versioning to match openjdk | Linux | Align Corretto versioning to match openjdk | [#15](https://github.com/corretto/corretto-27/pull/15) |
| Update timezone data to 2026e | All | Update timezone data to 2026e | [#14](https://github.com/corretto/corretto-27/pull/14) |
| JDK-8389846 | All | GenShen: ShenandoahScanRemembered::process_clusters may miss dirty cards when use write table | [#12](https://github.com/corretto/corretto-27/pull/12) |
| JDK-8391646 | All | Shenandoah: Mach node analysis should not strip extra bits | [#11](https://github.com/corretto/corretto-27/pull/11) |
| JDK-8392730 | All | CLDRConverter interprets usesMetazone UTC timestamps in the build host default timezone | [#8](https://github.com/corretto/corretto-27/pull/8) |
| Update Timezone Data to tzdata2026d and related fixes | All | Update Timezone Data to tzdata2026d and related fixes | [#7](https://github.com/corretto/corretto-27/pull/7) |


The following CVEs are addressed in 27.0.1.0.10

| CVE | CVSS | Component |
|-----|------|-----------|
| CVE-2026-91415 | 7.0 | client-libs/2d |
| CVE-2026-91398 | 6.8 | core-libs/java.net |
| CVE-2026-113470 | 6.8 | security-libs/java.security |
| CVE-2026-87294 | 6.5 | security-libs/java.security |
| CVE-2026-83395 | 6.5 | core-libs/java.net |
| CVE-2026-91394 | 5.9 | core-libs/java.net |
| CVE-2026-83387 | 5.9 | core-libs/java.sql |
| CVE-2026-91462 | 5.9 | security-libs/org.ietf.jgss |
| CVE-2026-83374 | 5.9 | security-libs/java.security |
| CVE-2026-87291 | 5.3 | core-libs/java.net |
| CVE-2026-91332 | 5.3 | core-libs/java.net |
| CVE-2026-91451 | 5.3 | core-libs/java.net |
| CVE-2026-91373 | 5.3 | security-libs/javax.net.ssl |
| CVE-2026-83380 | 5.3 | security-libs/javax.security |
| CVE-2026-83400 | 5.3 | xml/jaxp |
| CVE-2026-91463 | 5.3 | security-libs/org.ietf.jgss |
| CVE-2026-91464 | 5.3 | security-libs/org.ietf.jgss |
| CVE-2026-91453 | 5.3 | core-libs/java.net |
| CVE-2026-91452 | 5.3 | core-libs/java.net |
| CVE-2026-91418 | 5.3 | client-libs/javax.imageio |
| CVE-2026-91487 | 4.8 | hotspot/compiler |
| CVE-2026-83381 | 4.8 | security-libs/java.security |
| CVE-2026-91374 | 4.8 | core-svc/tools |
| CVE-2026-91375 | 4.7 | tools/jlink |
| CVE-2026-91379 | 4.7 | tools/jshell |
| CVE-2026-91380 | 4.0 | core-libs/java.util |
| CVE-2026-83378 | 4.8 | hotspot/compiler |
| CVE-2026-87255 | 3.7 | hotspot/compiler |
| CVE-2026-91409 | 3.7 | core-libs/java.net |
| CVE-2026-91333 | 3.7 | security-libs/java.security |
| CVE-2026-91334 | 3.7 | client-libs/javax.imageio |
| CVE-2026-87290 | 5.9 | xml/jaxp |
| CVE-2026-87367 | 3.7 | xml/jaxp |
| CVE-2026-87292 | 3.7 | core-libs/java.net |
| CVE-2026-83376 | 3.7 | security-libs/javax.net.ssl |
| CVE-2026-91461 | 3.7 | security-libs/java.security |
| CVE-2026-91397 | 3.6 | core-svc |
| CVE-2026-91400 | 3.1 | client-libs/javax.sound |
| CVE-2026-91335 | 2.6 | client-libs/java.awt |

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