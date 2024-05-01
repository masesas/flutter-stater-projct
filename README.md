# Flutter Stater Project Architecture

## Generator Command 😈
- If you're running with direct flutter environment just delete fvm keyword
- Run build runner (json_serializable, flutter_gen):
    ```
    fvm flutter packages pub run build_runner watch --delete-conflicting-outputs
    ```
- Run analyzer manually:
    ```
    fvm flutter analyze
    ```
- Run Generate Language
    ```
    fvm flutter gen-l10n
    ```
- Run Generate Launcher Icons
    ```
    fvm flutter pub run flutter_launcher_icons
    ```