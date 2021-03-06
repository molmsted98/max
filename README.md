[![Build Status](https://img.shields.io/github/workflow/status/pardom/max/CD)](https://github.com/pardom/max/actions?query=workflow%3ACD)
[![Maven Central](https://img.shields.io/maven-central/v/com.michaelpardo.max/navigator.svg)](#download)
[![Sonatype Nexus (Snapshots)](https://img.shields.io/nexus/s/https/oss.sonatype.org/com.michaelpardo.max/navigator.svg)](#download)
[![License](https://img.shields.io/github/license/pardom/max.svg)](LICENSE.md)

Max 🛸
=========

[Max][trimaxion] is a suite of libraries which build upon each other to provide:
 * [Uri][uri] - An [RFC 3986][rfc3986] URI implementation.
 * [Matcher][matcher] - path matching and value extraction.
 * [Router][router] - a [Uri] routing DSL and dispatcher.
 * [Navigator][navigator] - a navigation stack of [Uri][uri]s.

Download
--------

```kotlin
dependencies {
    implementation("com.michaelpardo.max:uri:<version>")
    implementation("com.michaelpardo.max:navigator:<version>")
    implementation("com.michaelpardo.max:navigator:<version>")
    implementation("com.michaelpardo.max:router:<version>")
    implementation("com.michaelpardo.max:matcher:<version>")
}
```

Snapshots of the development version are available in [Sonatype's `snapshots` repository][snapshots].

[trimaxion]: http://aliens.wikia.com/wiki/Trimaxion_Drone_Ship
[rfc3986]: https://tools.ietf.org/html/rfc3986
[uri]: uri
[matcher]: matcher
[router]: router
[navigator]: navigator
[snapshots]: https://oss.sonatype.org/content/repositories/snapshots/
