# Open Pixel Dungeon
[Pixel dungeon](https://github.com/watabou/pixel-dungeon), but modified to work in modern Android Studio

## Getting Started
You should be able to just clone/fork this repo! The [PD-Classes](https://github.com/watabou/PD-classes) util library has already been included.
Then, go to File > New > Import Project in Android Studio.

## Changes Made
- Raised gradle version and imported `google()` repository
- Merged deprecated `android.util.FloatMath` API to `java.lang.Math` API
- Fixed `Collection<? extends Item>` error (help from [this commit](https://github.com/watabou/pixel-dungeon/pull/41/commits/9c8633bd280ee9fcefe695be78649c71111b8fed))
- Imported the [PD-Classes](https://github.com/watabou/PD-classes) library

You should now be able to fork this repo and make changes to the original Pixel Dungeon!