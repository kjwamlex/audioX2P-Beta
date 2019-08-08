# audioX2P
audioX2P turns music into continuous, linear haptic feedback using X2P (Extreme Experience Portable)

Original project was called TapticMusic, which was published 2 years ago.

Download ipa in Releases.

# Requirements
iPhone 8 or later (iPhone 7 is not compatible, as mentioned by Apple on WWDC 2019)

iOS 13 or later as Core Haptics is only available on iOS 13.

Music in native Music app (Apple Music not compatible)

# What is changed from TapticMusic?

- X2P rather than Bass Detection System.

X2P fully analyzes audio file and turns them into numbers that can be used to be played on Taptic Engine using Core Haptics. It optimizes its haptics for each music file so that music feels great in your hands and deliver incredible details.

- Performance and Energy

Thanks to X2P, CPU Usage is decreased by 100% (I'm not kidding.), RAM usage is 3 times less than TapticMusic, and there are zero energy impact according to Xcode while TapticMusic was constantly draining battery.

- Stability

TapticMusic almost always crashed; but audioX2P does not crash at all as it does not clear caches saved in RAM in weird ways.

- Beautiful UI

Many people in my region liked design in TapticMusic Prototype 2; however, I had to ditch that design due to copyright reasons. However, in audioX2P, as all music are imported through your Music Library, copyright is not a problem. I was able to recreate Prototype 2 UI and make modern improvements.

- Headphone requirements? Where did that come from?

This was stupid in TapticMusic. This had to be done as it live renders audio from two speakers; but in audioX2P, audio is rendered into numbers before it plays music. Headphones are not requirements anymore.

- User Experience

Everything is straightforward and easy on audioX2P. Tap. Tap. Tap. Done. TapticMusic required you to add music through Youtube and wait for a long time and gathering audio data... Disgusting. No more with audioX2P.

Thinking back, it was a correct decision to pull TapticMusic. I was mentally broken at that time that I could not think correctly - now that this is done, X2P will be used in infiniteX2D - future daily technology that's being developed in exDevelopment. Stay tuned for this as well.
