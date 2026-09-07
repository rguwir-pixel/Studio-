# App Studio Complete

A Java/XML Android project implementing an AIDE-style project workspace.

Included:
- AIDE-style home/project menu
- New Android App template
- Open File
- Import Project Folder using Android Storage Access Framework
- Java/XML text editor
- Tabs
- Save
- Undo / Redo
- Basic error checker
- Safe Auto Fix
- Auto Fix + re-check workflow
- Project categories: Android, Mobile Game, Java, C/C++, Native Android, Website, JavaScript
- Gradle project structure

Important:
This is a native Android project manager/editor. An Android app cannot safely compile arbitrary imported Gradle projects by itself unless a compatible Gradle/Android SDK toolchain is bundled and maintained. The BUILD action therefore performs the editor-side scan/fix workflow and leaves the actual Gradle/APK compilation to the project's Gradle environment (for example AIDE/Android Studio).

Open the project in AIDE/Android Studio and build it.
