# Kakapo

This is the Kakapo monorepo. Contains [kakapo-util](kakapo-util), [kakapo-api](kakapo-api), [kakapo-crypto](kakapo-crypto), and [kakapo-client](kakapo-client) subprojects.

Looking for [kakapo-android](https://github.com/jeffisaak/kakapo-android)?

## What is Kakapo?

Kakapo is a privacy-centric social network. Kakapo's API is open, so anybody can create Kakapo clients.

## Adding to your project

In order to declare a dependency on kakapo or the subprojects, first add jitpack to your repositories:

```
repositories {
    maven { url 'https://jitpack.io' }
}
```

Then add either the individual dependencies:

```
dependencies {
    implementation 'com.github.jeffisaak.kakapo:kakapo-api:0.1.1'
    implementation 'com.github.jeffisaak.kakapo:kakapo-crypto:0.1.1'
    implementation 'com.github.jeffisaak.kakapo:kakapo-util:0.1.1'
    implementation 'com.github.jeffisaak.kakapo:kakapo-client:0.1.1'
}
```

Or all four at once:

```
dependencies {
    implementation 'com.github.jeffisaak:kakapo:0.1.1'
}
```

## API Documentation

- [API v1](API-V1.md)