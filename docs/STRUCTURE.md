# Folder Files Structure

```text
root
|____ assets
      |____ fonts
      |____ html
      |____ i18n
      |____ images
|____ lib
      |____ config
            |____ routes (package: fluro)
            |____ themes (Bloc)
      |____ constants
            |____ api_path.dart
            |____ assets_path.dart
            |____ app_constants.dart
      |____ widgets (RaisedButton, FlatButton, OutlineButton, Divider, CircularLoader)
      |____ utils
            |____ helpers
                  |____ text_helper.dart
            |____ ui (animations, dialogs, ui_utils)
                  |____ filename.dart
            |____ mixins
                  |____ validation_mixins.dart
            |____ services
                  |____ local_storage_service.dart
      |____ core
            |____ auth
                  |____ forgot_password
                  |____ login
                  |____ register
            |____ walk_through
            |____ settings
      |____ modules
            |____ dashboard 
                  |____ bloc
                        |____ dashboard_bloc.dart
                        |____ dashboard_event.dart
                        |____ dashboard_state.dart
                  |____ models
                        |____ dashboard_model.dart
                  |____ repositories
                        |____ dashboard_repository.dart
                  |____ screens
                        |____ dashboard_screen.dart
            |____ user_profile 
```




References:
- [Flutter scalable folder & files structure](https://medium.com/flutter-community/flutter-scalable-folder-files-structure-8f860faafebd)