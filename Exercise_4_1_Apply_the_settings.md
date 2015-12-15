## Objectives:
* Learn how to use shared preferences to store key/value data.
* Learn how to use `SwitchCompat`

## Requirements:
* Apply some more settings to your game at [Exercise 3.2](Exercise_3_2_How_activities_and_fragments_live.md)
* `SettingsActivity` can be accessed by pressing the top-right menu button.
* The UI should look like this:


* There are two options for this game:
    + Time limit: range from 5 sec to 60 sec. The value set here will affect the time of game afterwards. Default value is 10 sec.
    + Change the value of the seekbar should update the small textview below `Time Limit` label.
    + Record highscore: if it's enabled then after the one game is finished, the score is automatically recorded else it will be discarded. Default value is enabled.

* Every previous settings should be shown when user comes to this activity.

## References:
* How to use SharedPreferences: http://developer.android.com/training/basics/data-storage/shared-preferences.html
* How to use `SwitchCompat`: https://developer.android.com/reference/android/support/v7/widget/SwitchCompat.html
