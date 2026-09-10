<div align="center">

<img src="https://raw.githubusercontent.com/MelismaApp/melisma/main/docs/branding/icon-light.jpg" width="96" alt="" />

# Melisma

**Word-by-word karaoke lyrics for whatever your phone is already playing.**

Spotify, YouTube Music, Apple Music, SoundCloud, a local player — anything that plays audio.
No login, no account, and it works out of the box.

[**Download the app →**](https://github.com/MelismaApp/melisma/releases/latest)

</div>

![Melisma in Cinema view](https://raw.githubusercontent.com/MelismaApp/melisma/main/docs/cinema-landscape.png)

Android makes every music app publish a *media session* — the track, the artwork, and a live
playhead. Melisma reads that, looks the words up, and draws them syllable by syllable as they are
sung. Nothing to connect, no service to sign into, and four of its lyrics sources need no account at
all.

| Repository | |
|---|---|
| **[melisma](https://github.com/MelismaApp/melisma)** | The Android app. Kotlin, Jetpack Compose, one canvas for the whole page. |
| **[melisma-server](https://github.com/MelismaApp/melisma-server)** | Optional. A caching server that sits in front of the free lyrics sources, so an endpoint run by volunteers is asked once per song instead of once per listener per play. |

| | | |
|---|---|---|
| <img src="https://raw.githubusercontent.com/MelismaApp/melisma/main/docs/renderer-active-line.png" alt="A line filling mid-word" /> | <img src="https://raw.githubusercontent.com/MelismaApp/melisma/main/docs/furigana.png" alt="Furigana printed over kanji" /> | <img src="https://raw.githubusercontent.com/MelismaApp/melisma/main/docs/popup-lyrics.png" alt="Lyrics in a floating window" /> |
| Each syllable fills as it is sung | Furigana over kanji, from a real dictionary | A floating window over other apps |

### Where the name comes from

A **melisma** is one syllable sung across several notes — the held note that ripples rather than
sitting still. It is the thing this renderer draws letter by letter, and the thing a printed lyric
sheet cannot show you.

### Credit and licence

Melisma is a port of [**Spicy Lyrics**](https://github.com/Spikerko/spicy-lyrics) by Spikerko — its
look, its motion and its lyric model, read onto Android. Spicy Lyrics is **AGPL-3.0**, so Melisma is
too. The word-by-word lyrics that arrive with no account come from the
[**AMLL TTML Database**](https://github.com/amll-dev/amll-ttml-db), hand-timed by its contributors
and dedicated to the public domain.

Lyrics belong to their writers and publishers. None of the sources are affiliated with this project.
