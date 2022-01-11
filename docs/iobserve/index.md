---
sidebar: true
---

## Introduction

**[iObserve on the web](https://www.arcsecond.io/iobserve)** is the main and
most advanced Pro Tool of Arcsecond.io. iObserve main goal is to provide a
complete and detailed overview of a full night of observation for any type of
targets, for any observing site on Earth.

iObserve is the web version of a macOS app that existed for about 10 years. An
iPad version existed for a while too. However, the macOS app was a "heavy
client" app, with more than 80 000 lines of Objective-C code, containing all the
connectors to external services (Simbad, NED, JPL etc). Arcsecond.io was
originally built to overcome the limitations of the native app: only the Apple
platforms, no remote data layer to create and store user data, hard-to-maintain
connectors code, slow update deployments etc.

Today, iObserve on the web is part of a larger SPA (Single-Page Application)
written in JavaScript, based on [Vuejs3](https://v3.vuejs.org) and is available
to all modern navigators. Moreover, a multi-platform desktop app, based
on [Electronjs](https://electronjs.org), is available for download for
[macOS, Windows and Linux](https://www.arcsecond.io/downloads)!
