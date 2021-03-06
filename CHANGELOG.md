## 1.8.4
- Add a new settings entry 'autoDefaultMarkers'.
- Add support for Twig and Visual Basic.

## 1.8.3
- Added 'PowerShell' and 'PHP' to the supported languages.

## 1.8.2
- Remove 'reject' when fail to get the current editor. It happens too often and annoys other 
extension developers.

## 1.8.1
- Add *only* entry to configuration. This allows running only in some pre-defined directories.
- Also update status bar count after running ParseCurrentFile command.
- Avoid reading excluded folders (previously, they were read and then were discarded).

## 1.8.0
- Add tests.

(Changelog of **v1.8.0 - beta**)

## 1.8.0 - beta
- Add 'include' entry in user setting to specify which file extension is included.

Support for large projects:
- Read files by chunks instead of "all at once".
- Display the progress on status bar.
- Allow canceling by clicking on the status bar item.
- Forcefully display output panel once. Not show again if user closed it.


## v1.7.2
- Fix incorrect line number calculation.

## v1.7.1
- Allow Ctrl+Click on file path in output panel to jump to TODO.
- Update API, minimum support version is now vscode v1.2.

## v1.7.0
- Add support for Elixir and Shell script.
- Show debug log if devMode is true.

## v1.6.0
- Add devMode in UserSetting (currently it is useless).
- Add a proper Logger class.
- Add support for Typescript.
- Add documentation.

## v1.5.2
Add default value for user setting.

## v1.5.1
Add support for folder exclusion (in user settings).

## v1.5.0
This version contains a complete overhaul of the whole project including code re-structure and refinement.

Key points:
- Complete overhaul.
- Begin logging changelog.
