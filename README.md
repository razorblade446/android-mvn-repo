# android-mvn-repo

## Repositorio Auxiliar para desarrollo Android

### Repositorio Maven

```xml
  <repositories>
    <repository>
      <id>mvn.razorblade446.co</id>
      <url>https://github.com/razorblade446/android-mvn-repo/raw/master/releases</url>
    </repository>
  </repositories>
```

### Librerías Incluidas

* Android Support Library v4 r12 *support-v4*

```xml
  <dependency>
    <groupId>com.google.android</groupId>
    <artifactId>support-v4</artifactId>
    <version>r12</version>
  </dependency>
```

* Google Cloud Messaging for Android Library (Cliente) r3 *gcm-client*

```xml
  <dependency>
    <groupId>com.google.android.gcm</groupId>
    <artifactId>gcm-client</artifactId>
    <version>r3</version>
  </dependency>
```

* Google Maps API *maps.jar* (Versiones: *17_r1*)

```xml
  <dependency>
    <groupId>com.google.android.maps</groupId>
    <artifactId>maps</artifactId>
    <version>17_r1</version>
  </dependency>
```

* Crittercism APM Android *crittercism_v3_0_7_sdkonly.jar*

```xml
  <dependency>
    <groupId>com.crittercism</groupId>
    <artifactId>crittercism-android</artifactId>
    <version>3.0.7-sdkonly</version>
  </dependency>
```