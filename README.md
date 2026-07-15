### Welcome to the official Maven for A Group of Modders projects!

To use mods in this Maven, put this in your build.gradle

```gradle
repositories {
    maven {
        url = uri("https://a-group-of-modders.github.io/A.G.O.M-Maven")
    }
    mavenCentral()
}

dependencies {
    implementation "com.{usually the first contributor}:{mod name}:{version}"
}
```

For example, to use **Yet Another Mod Library** in your Gradle project, use the following

```gradle
repositories {
    maven {
        url = uri("https://a-group-of-modders.github.io/A.G.O.M-Maven")
    }
    mavenCentral()
}

dependencies {
    implementation "com.mrmodder:YetAnotherModLibrary:{version}"
}


