Achievement is a system-wide mechanism for directing and rewarding users' in-game actions in a consistent manner across all games. If you are not familiar with achievements, please see [Achievements documents](https://docs.microsoft.com/en-us/windows/uwp/xbox-live/achievements-2017/achievements).

From now on, all new titles created on [Windwos Dev Center](https://dev.windows.com/) are using Data Platform 2017. For achievements, it's  [Achievements 2017](https://docs.microsoft.com/en-us/windows/uwp/xbox-live/achievements-2017/simplified-achievements) which enables game developers to use a direct calling model to unlock achievements for new Xbox Live games on Xbox One, Windows 10, Windows 10 Phone, Android, and iOS.

For how to configure achievements on Dev Center, please see [Configure Achievements 2017 on Dev Center](https://docs.microsoft.com/en-us/windows/uwp/xbox-live/achievements-2017/achievements-in-udc).

## Using the scripts

With Achievements 2017, it's very easy to unlock achievements or update completion progresses. The key API here is `UpdateAchievementAsync` method. For more information, see [Update_Achievement API](https://docs.microsoft.com/en-us/windows/uwp/xbox-live/achievements-2017/simplified-achievements#updateachievement-api).

In unity, you can take advantage of `AchievementBase` class. You will need to derive from this class and override `CalculateProgress` method to implement your achievement’s unlock logic.

