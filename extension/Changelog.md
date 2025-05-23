# BCT Changelog

## 0.6.9
### Minor Change
- Changed saved settings location
- Fixed BF Locks to work again

## 0.6.8
### Minor Change:
- Updated dialog item icon for locks

## 0.6.7
### Minor Change:
- Updated Settings for R108

## 0.6.6
### Bugfixes:
- Fixes erroneous behaviour with nipple slots
- Update for R107Beta
- Updated to Item permissions for R105 (By Rama)
- Tailwag now works in ChatRooms

## 0.6.5
### Features:
- Show Room Slots added
- Friend list would now have an extra column (Slots) showing number of people in your friend's room and max capacity of the room

## 0.6.4
### Bugfixes:
- Updated for R104

## 0.6.3
### Bugfixes:
- Slow down of room request on login
- Fixes Activity error which made the arousal go up on using any activity on others
- Added safeguards against `sender.BCT` being unitialized (By Rama)

### Minor Change:
- Updated to ModSdk 1.2.0
- Tips available on settings page

## 0.6.2
### Bugfixes:
- Fixed a bug with BF Locks which made them unavailable to unlock in public rooms

### Changed:
- Added a reset button for all settings
- Item permissions for BF Locks are now handled in BCTweaks settings page under Best Friends

## 0.6.1
### Bugfixes:
- Update for R101
- Fixed an error with BF Lock where player wouldn't get access without Room Share enabled

## 0.6.0
### Features:
- Money Transfer added (Using /send-money command)
- Changelog as chat message added
- Preview Lock Icons now shows BF locks correctly.
- Added BCTweaks icon and Best Friends icon.
- Option to show icons only while hovering the mouse above the characters.

## 0.5.3
## Features:
- A new setting to share private rooms directly.

### Bugfixes:
- Room sharing should work more reliably now.
- Rate limit fix.

## 0.5.2
### Bugfixes:
- `TimerProcess` updated for R92

## 0.5.1
### Features:
- Change when you can add Best Friends. Now you can add any friend as Best Friend from Friendlist
- Add an option to convert High-Security Padlock to Best Friend Padlock

### Bugfixes:
- `ControllerIsActive()` instead of `ControllerActive` for R92

## 0.5.0
### Features:
- Update BCT settings button to show after "Gender"
- Change color of settings text on hover to better show it being able to be clicked
- Added API (feel free to request access to additional functions)
- Support male genitals
- Possibility for automatic erections based on arousal
- Added Best Friend Lock and Best Friend Timer Lock

### Bugfixes:
- Lovers and Owners access on BF locks wasn't correctly added 
- Timer Locks on items with extra effects didn't unlock on correct time
- Vibrators on zones that cant make you orgasm, still gave orgasm progress
- Random effects affected orgasm progress, regardless of zone