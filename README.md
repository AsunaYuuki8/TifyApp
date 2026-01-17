![Tify](https://cdn-icons-png.flaticon.com/64/9973/9973495.png)
## App Name: TifyApp

Short Description:
An Android music player built on Media3 ExoPlayer, using a modern MVVM architecture, Firebase Firestore for data management, and a dynamic user interface.

Main Idea:
To deliver a fast, smooth, and aesthetically pleasing music experience through gesture-based controls, a BottomSheet player, dynamic colors, and efficient image loading.

## Features

UI:
Smooth and aesthetic interface with dynamic colors.

Gestures:
Swipe left/right — playlist navigation; swipe up — open the player.

BottomSheet Player:
Expandable and collapsible bottom music player.

Notification Controls:
Media playback control from system notifications and connected devices.

Realtime Data:
Songs are fetched in real time from Firebase Firestore.

Images:
Glide/Coil for cover art, GIFs, and blurred artwork (Android 12+).
## Screenshots
![screen1](screenshots/screen1.png) ![screen2](screenshots/screen2.png)
![screen3](screenshots/screen3.png)
## Architecture & Requirement Compliance

Single Activity + Multiple Fragments:
A main Activity manages multiple Fragments, enabling a modular UI and simplified navigation.

ViewBinding:
Safe and efficient view access within Activities and Fragments.

Data Management:
Firestore is used to fetch and update song data.

Lists & Views:
RecyclerView (or Compose LazyColumn) for structured and efficient data display.
Image Loading:
Glide/Coil for fast and memory-efficient image loading.

## გამოყენებული Framework-ები და ბიბლიოთეკები
- [Media3 Exoplayer](https://developer.android.com/guide/topics/media/exoplayer)
- [Jetpack Compose (Material 3)](https://developer.android.com/jetpack/compose/designsystems/material3)
- [Dagger Hilt Dependency Injection](https://developer.android.com/training/dependency-injection/hilt-android)
- [Coroutines](https://developer.android.com/kotlin/coroutines) და [Flow](https://developer.android.com/kotlin/flow)
- [Glide](https://github.com/bumptech/glide) და [Coil](https://github.com/coil-kt/coil)
- [Firestore](https://firebase.google.com/docs/firestore)
- [Palette](https://developer.android.com/develop/ui/views/graphics/palette-colors) — ფერების გენერაცია cover art-იდან


## Task Requirements
- ✅ **Single Activity + Multiple Fragments** — აპლიკაცია იყენებს ერთ Activity-ს და რამდენიმე Fragment-ს
- ✅ **ViewBinding** — გამოყენებულია ViewBinding უსაფრთხო და ეფექტური View-ების წვდომისთვის
- ✅ **Data Management** — Firestore ინტეგრაცია მონაცემების წამოსაღებად
- ✅ **Lists & Views** — RecyclerView/Compose LazyColumn მონაცემების ჩვენებისთვის
- ✅ **Image Loading** — Glide და Coil ბიბლიოთეკები სურათების ჩასატვირთად

## დამატებითი შესაძლებლობები
- MVVM არქიტექტურა
- Dagger Hilt Dependency Injection
- Kotlin Coroutines & Flow
- Palette library — დინამიური ფერები
- CI/CD — ინტეგრაცია [Bitrise](https://bitrise.io)-თან

## Group project
