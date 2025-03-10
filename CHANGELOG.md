7.30
-----


7.29
-----

* New Features:
    *   Onboarding flow for new users
        ([#645](https://github.com/Automattic/pocket-casts-android/pull/645)).
    *   Display gravatar on profile screen
        ([#644](https://github.com/Automattic/pocket-casts-android/pull/644)).
* Bug Fixes:
    *   Fixed podcast date format
        ([#477](https://github.com/Automattic/pocket-casts-android/pull/477)).
    *   Fix unable to permanently change "Skip back time" setting
        ([#632](https://github.com/Automattic/pocket-casts-android/pull/632)).
    *   Included deep link support for share links
        ([#526](https://github.com/Automattic/pocket-casts-android/pull/526)).

7.28
-----
*   Bug Fixes:
    *   Fixed effects bottomsheet flickering to the expanded state while being dragged
        ([#575](https://github.com/Automattic/pocket-casts-android/pull/575)).
    *   Fixed miniplayer play icon animation on theme change
        ([#527](https://github.com/Automattic/pocket-casts-android/pull/527)).
    *   Fixed talkback issues
        ([#630](https://github.com/Automattic/pocket-casts-android/pull/630)).
    *   Fixed skip forward/ backward buttons not showing in media notification while casting
        ([#630](https://github.com/Automattic/pocket-casts-android/pull/630)).
    *   Fix media notification controls configuration to support 3 icons
        ([#641](https://github.com/Automattic/pocket-casts-android/pull/641)).

7.27
-----

*   New Features:
    * Add End of Year stats
        ([#410](https://github.com/Automattic/pocket-casts-android/issues/410)).  
    * Support Android 13 per-app language preferences
        ([#519](https://github.com/Automattic/pocket-casts-android/pull/519)).
*   Bug Fixes:
    *   Fixed some layout issues in the EpisodeFragment
        ([#459](https://github.com/Automattic/pocket-casts-android/pull/459)).
    *   Fixed RTL support for notes
        ([#514](https://github.com/Automattic/pocket-casts-android/pull/514)).
    *   Allowed customization of actions through Settings in Media Notification Control for Android 13 users.
        ([#499](https://github.com/Automattic/pocket-casts-android/pull/540)).
    *   Fixed small "Go to Podcast" icon in Landscape
        ([#547](https://github.com/Automattic/pocket-casts-android/pull/547)).
    *   Added option to open player automatically when user start playing podcast.
        ([#23](https://github.com/Automattic/pocket-casts-android/pull/550))

7.26
-----

*   New Features:
    *   Added Tasker integration with "Play Filter" and "Control Playback" actions.
        ([#431](https://github.com/Automattic/pocket-casts-android/pull/431)).
    *   Import OPML from a URL
        ([#482](https://github.com/Automattic/pocket-casts-android/pull/482)).
    *   Redesign of the fullscreen player share option
        ([#451](https://github.com/Automattic/pocket-casts-android/pull/451)).
    *   Redesign of the fullscreen player long press option
        ([#483](https://github.com/Automattic/pocket-casts-android/pull/483)).
    *   Updated select filters title & hide podcast setting filter option when applicable
        ([#494](https://github.com/Automattic/pocket-casts-android/pull/494)).
*   Bug Fixes:
    *   Fixed Help & Feedback buttons being hidden when using text zoom.
        ([#446](https://github.com/Automattic/pocket-casts-android/pull/446)).
    *   Fixed when system bar didn't disappear on full screen video player
        ([#461](https://github.com/Automattic/pocket-casts-android/pull/461)).
    *   Fixed When no podcasts were selected for a filter, change the chip to 'All Your Podcasts'
        ([#460](https://github.com/Automattic/pocket-casts-android/pull/460)).
    *   Fixed background color for screens using the compose theme
        ([#432](https://github.com/Automattic/pocket-casts-android/pull/432)).
    *   Fixed full screen video player not closing the first time in landscape mode
        ([#464](https://github.com/Automattic/pocket-casts-android/pull/464)).
    *   Added ability to set playback effects in Tasker "Control Playback" action.
        ([#509](https://github.com/Automattic/pocket-casts-android/pull/509)).
    *   Fixed crashes with Tasker plugin actions when using minified code.
        ([#543](https://github.com/Automattic/pocket-casts-android/pull/543)).
    *   Fixed auto subscribe issue.
        ([#545](https://github.com/Automattic/pocket-casts-android/pull/545)).

7.25
-----

*   Bug Fixes:
    *   Allow Discover feed collection titles to wrap.
        ([#335](https://github.com/Automattic/pocket-casts-android/pull/335)).
    *   Allow select text in show notes from episode details view.
        ([#372](https://github.com/Automattic/pocket-casts-android/pull/372)).
    *   Added Automotive OS setting to show played episodes.
        ([#389](https://github.com/Automattic/pocket-casts-android/pull/389)).
    *   Added new episode lists to Automotive OS. Starred, Listening History, and Files.
        ([#403](https://github.com/Automattic/pocket-casts-android/pull/403)).
    *   Fixed skip backwards settings
        ([#425](https://github.com/Automattic/pocket-casts-android/pull/425)).

7.24.2
-----

*   New Features:
    *   Added a Halloween icon.
        ([#415](https://github.com/Automattic/pocket-casts-android/pull/415)).

*   Bug Fixes:
    *   Add missing POST_NOTIFICATIONS permission for Android 13
        ([#330](https://github.com/Automattic/pocket-casts-android/pull/436)).

7.24
-----

*   Bug Fixes:
    *   Fix Mini Player long press mark as played button.
        ([#330](https://github.com/Automattic/pocket-casts-android/pull/330)).
    *   Fix Filters tab not always displaying the list of filters when it should.
        ([#342](https://github.com/Automattic/pocket-casts-android/pull/342)).
    *   Add a helpful alert if the user is signed out in the background.
        ([#340](https://github.com/Automattic/pocket-casts-android/pull/340)).
    *   Fix in-app logs not updating appropriately.
    *   ([#395](https://github.com/Automattic/pocket-casts-android/pull/395)).
*   Health:
    *   Migrate app to Android 13 by targeting the SDK version 33.
        ([#312](https://github.com/Automattic/pocket-casts-android/pull/312)).

7.23.0
-----

*   Bug Fixes:
    *   Fix custom video file not opening in full-screen mode.
        ([#304](https://github.com/Automattic/pocket-casts-android/pull/304)).

7.22.0
-----

*   Bug Fixes:
    *   Fix playing on Chromecast always shows buffering.
        ([#254](https://github.com/Automattic/pocket-casts-android/pull/254)).
    *   Fix Plus subscription confirm button not always working.
        ([#284](https://github.com/Automattic/pocket-casts-android/pull/284)).


7.21.1
-----

*   Bug Fixes:
    *   Fix Chromecast not taking over playback after connection.
        ([#308](https://github.com/Automattic/pocket-casts-android/pull/308)).
    *   Fix the discover artwork scaling issue.
        ([#308](https://github.com/Automattic/pocket-casts-android/pull/308)).

7.21.0
-----

*   Bug Fixes:    
    *   Fix the mini player's play icon showing the wrong icon.
        ([#208](https://github.com/Automattic/pocket-casts-android/pull/208)).
    *   Fix dark theme background color.
        ([#206](https://github.com/Automattic/pocket-casts-android/issues/206)).
    *   Fix embedded artwork not showing on player screen.
        ([#16](https://github.com/Automattic/pocket-casts-android/issues/16)).
    *   Fix long podcast website links overflowing.
        ([#230](https://github.com/Automattic/pocket-casts-android/issues/230)).
    *   Add a confirmation prompt for "End playback & clear Up Next" to prevent accidental actions.
        ([#237](https://github.com/Automattic/pocket-casts-android/issues/237)).
    *   Improve the mini player long press dialog.
        ([#240](https://github.com/Automattic/pocket-casts-android/issues/240)).
    *   Fix OPML import failing with invalid XML characters.
        ([#51](https://github.com/Automattic/pocket-casts-android/issues/51)).
    *   Fix the listening stats not being sent to the server correctly.
        ([#238](https://github.com/Automattic/pocket-casts-android/issues/238)).
    *   Fix tapping on the cast notification.
        ([#26](https://github.com/Automattic/pocket-casts-android/issues/26)).
    *   Fix episode row buffering state.
        ([#53](https://github.com/Automattic/pocket-casts-android/issues/53)).

7.20.3
-----

*   Bug Fixes:
    *   Fixes folder mapping at the time of folders full sync.
        ([#214](https://github.com/Automattic/pocket-casts-android/pull/214)).

7.20.2
-----

*   Bug Fixes:    
    *   Fix OPML import.
    *   Fix podcasts and folders rearrange crash.
        ([#200](https://github.com/Automattic/pocket-casts-android/issues/200)).

7.20.1
-----

*   New Features:
    *   Add localizations for English (UK), Arabic, and Norwegian.
*   Bug Fixes:
    *   Fix an issue where the podcasts order was being changed after migrating to the latest version.

7.20.0
-----

*   New Features:
    *   Folders!
*   Health:
    *   Remove old notification events
        ([#3303](https://github.com/shiftyjelly/pocketcasts-android/pull/3303)).
    *   Add extra logs to help track playback issues
        ([#3304](https://github.com/shiftyjelly/pocketcasts-android/pull/3304)).
    *   Split the app into modules ready for the Wear OS app
        ([#3313](https://github.com/shiftyjelly/pocketcasts-android/pull/3313)).
    *   Migrate to non-transitive R classes
        ([#3314](https://github.com/shiftyjelly/pocketcasts-android/issues/3314)).
    *   Improve speed of Automotive app
        ([#3330](https://github.com/shiftyjelly/pocketcasts-android/pull/3330)).
*   Bug Fixes:    
    *   Import latest localizations.
    *   Up Next total time duration is no longer limited to 596h 31m.
    *   Fix video player out of memory issues
        ([#3339](https://github.com/shiftyjelly/pocketcasts-android/pull/3339)).
    *   Fix Android Auto playback speed not working
        ([#3366](https://github.com/shiftyjelly/pocketcasts-android/issues/3366)).
    *   Fix the podcast page going blank when sharing
        ([#3324](https://github.com/shiftyjelly/pocketcasts-android/issues/3324)).
    *   Fix sign in and create email invalid state with white space
        ([#3306](https://github.com/shiftyjelly/pocketcasts-android/issues/3306)).
    *   Fix playback starting when disconnecting from bluetooth and can't be stopped
        ([#3311](https://github.com/shiftyjelly/pocketcasts-android/issues/3311)).
    *   Improve the search failed error message
        ([#3300](https://github.com/shiftyjelly/pocketcasts-android/pull/3300)).
    *   Fix status bar color issue
        ([#3299](https://github.com/shiftyjelly/pocketcasts-android/pull/3299)).
    *   Fix progress bar issue when playback is paused
        ([#3295](https://github.com/shiftyjelly/pocketcasts-android/issues/3295)).
    *   Fix discover single episode colors
        ([#3288](https://github.com/shiftyjelly/pocketcasts-android/issues/3288)).    
    *   Fix podcast website url
        ([#3290](https://github.com/shiftyjelly/pocketcasts-android/issues/3290)).
    *   Fix localizations
        ([#3277](https://github.com/shiftyjelly/pocketcasts-android/pull/3277)).
    *   Improve warning when streaming will use metered data 
        ([#3246](https://github.com/shiftyjelly/pocketcasts-android/pull/3426)).
    *   Fix crash when switching to podcast without chapters 
        ([#3450](https://github.com/shiftyjelly/pocketcasts-android/pull/3450)).
    *   Improve sharing a list of podcasts
        ([#97](https://github.com/shiftyjelly/pocketcasts-android/pull/97)).
    *   Fix displaying previous show notes briefly when switching episodes.
        ([#35](https://github.com/Automattic/pocket-casts-android/pull/35)).
    *   Fix same chapter click behaviour 
        ([#59](https://github.com/Automattic/pocket-casts-android/pull/59)).
    *   Replace duration with time left on episode screen from listening history  
        ([#83](https://github.com/Automattic/pocket-casts-android/pull/83)).
    *   Fix back navigation for full screen player 'Rearrange Actions' page
        ([#76](https://github.com/Automattic/pocket-casts-android/pull/76)).
    *   Prevent video player controls from getting stuck on the screen
        ([#77](https://github.com/Automattic/pocket-casts-android/pull/77)).
    *   Fix showing paused downloads as in progress
        ([#113](https://github.com/Automattic/pocket-casts-android/pull/113)).
    *   Fix issues with discover feed state when scrolling through the feed
        ([#120](https://github.com/Automattic/pocket-casts-android/pull/120)).
    *   Improve manage downloads screen
        ([#117](https://github.com/Automattic/pocket-casts-android/pull/117)).

7.19.2 (2022-02-11)
-----

*   New Features:
    *   Add support for episode lists in the discover section.
    *   Add two new localizations French (Canada) and Spanish (Mexico).
*   Health:
    *   Migrate app to Android 12 by targeting the SDK version 31.
*   Bug Fixes:    
    *   Import latest localizations.
    *   Fix localization layout
        ([#3173](https://github.com/shiftyjelly/pocketcasts-android/pull/3173)).
    *   Fix user file colors can't be changes
        ([#3136](https://github.com/shiftyjelly/pocketcasts-android/issues/3136)).
    *   Fix podcast search view requiring a double tap to open the keyboard.
    *   Fix while playing a cloud file it jumps back with a refresh
        ([#3140](https://github.com/shiftyjelly/pocketcasts-android/issues/3140)).
    *   Fix unsubscribing from a podcast doesn't remove it from a filter
        ([#3150](https://github.com/shiftyjelly/pocketcasts-android/issues/3150)).
    *   Fix full screen video player media controls not hiding automatically
        ([#3148](https://github.com/shiftyjelly/pocketcasts-android/issues/3148)).
    *   Fix create account next button not working when using 1Password
        ([#3167](https://github.com/shiftyjelly/pocketcasts-android/issues/3167)).
        
