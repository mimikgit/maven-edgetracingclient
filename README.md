# EdgeTracingClient

EdgeTracingClient service library can help you interact with the following mimik services:

 * contact tracing

## Requirements

EdgeTracingClient works on Android 8.0+ (API level 26+) and Java 8+

## Installation

To install it, declare the mimik maven repository in your project-level `build.gradle` file:

```
allprojects {
    repositories {
        maven {
            url "https://s3-us-west-2.amazonaws.com/mimik-android-repo"
        }
    }
}
```

Declare the dependency in your module-level `build.gradle` file:

```
dependencies {
    implementation 'com.mimik.edgesdk-android-client:edgetracingclient:0.1.+'
}
```

## Author

mimik
```
https://github.com/mimikgit/maven-EdgeTracingClient
```

## License

edgeEngine is available under the MIT license. See the LICENSE file for more info.
