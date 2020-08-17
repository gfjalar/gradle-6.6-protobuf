# Protobuf failing on Gradle 6.6

It seems zinc setup in Gradle 6.0+ leaks `protobuf-java` to `compileClasspath`.

This repo showcases the minimal setup in which the issue occurs.

### Build Scans

- [5.6.4](https://scans.gradle.com/s/jxuyvhipfxxck)
- [6.6](https://scans.gradle.com/s/f7nralo66empe)
