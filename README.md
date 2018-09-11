## Install

```bash
brew update
brew install gradle
```

Version Check

``` bash
gradle -v
```

see: gvm

## build.gradle

```
apply plugin: 'java'
apply plugin: 'application'

repositories {
    jcenter()
}

dependencies {
    compile 'com.google.guava:guava:22.0'
    testCompile 'junit:junit:4.12'
}

mainClassName = '[package][Class]'
```

```
gradle init --type java-application
# gradle init --type ＜TYPE＞
# ＜TYPE＞
# * 'basic'
# * 'groovy-application'
# * 'groovy-library'
# * 'java-application'
# * 'java-library'
# * 'pom'
# * 'scala-library'
```