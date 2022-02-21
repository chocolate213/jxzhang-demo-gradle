## Demos with Gradle

## Building Java Applications Sample

> https://docs.gradle.org/current/samples/sample_building_java_applications.html

### Publish a Build Scan

The best way to learn more about what your build is doing behind the scenes, is to publish a build scan. To do so, just run Gradle with the `--scan` flag.

``` bash
$ ./gradlew build --scan

BUILD SUCCESSFUL in 0s
7 actionable tasks: 7 executed

Publishing a build scan to scans.gradle.com requires accepting the Gradle Terms of Service defined at https://gradle.com/terms-of-service.
Do you accept these terms? [yes, no] yes

Gradle Terms of Service accepted.

Publishing build scan...
https://gradle.com/s/5u4w3gxeurtd2
```
### Creating a multi-project build

> https://docs.gradle.org/current/userguide/multi_project_builds.html#sec:creating_multi_project_builds
