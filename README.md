# This project aims to try how to upload an stub Android library to Bintray's maven repo.

## StubLib
### How to specify dependency through build.gradle?

```
repositories {
    maven {
        url "https://dl.bintray.com/dannysuen/maven"
    }
}

dependencies {
	...

    compile 'me.dannysuen.stublib:stublib:1.0.1'
}
```