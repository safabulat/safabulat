## Safa Bulat

I build **a MIDI controller for iPhone that you lay out yourself**, **small native macOS software** —
desk toys and instruments that live in the menu bar, weigh a couple of megabytes and never get in your
way — and **co-op games** where the other player is the interesting part of the physics.

No frameworks, no accounts, no analytics, no network code. The sounds are synthesised at launch instead
of shipped as audio, and the landing pages are plain HTML with no external requests at all.

**[bulatapps.com](https://bulatapps.com/)** — everything in one place.

### Midiboard — iPhone, Swift + UIKit

**[Midiboard](https://midiboard.bulatapps.com/)** — an iPhone Bluetooth MIDI controller you
build yourself. *[On the App Store](https://apps.apple.com/app/id6801598625).*

Drop pads, keys, chord buttons, wheels, faders, XY pads and step sequencers onto a grid, drag each one
where your hand actually goes, save the screen, and flip between screens with one tap while the song is
running. Every other phone controller hands you someone else's idea of a surface; this one hands you the
grid.

It owns its Bluetooth peripheral rather than borrowing Apple's sheet, so the name your computer sees is
the one you typed. The whole playing surface is a single view over Core Animation layers — one view is
what makes sliding from one key to the next possible at all — and everything worth being sure about,
from note mapping to the clock's arithmetic, is pure Swift with no UIKit in it and covered by tests that
run without a simulator.

[![Midiboard](https://midiboard.bulatapps.com/img/surface.jpg)](https://midiboard.bulatapps.com/)

### Desk toys & instruments — macOS, Swift + AppKit

| | |
|---|---|
| **[Deskestra](https://deskestra.bulatapps.com/)** | A piano, drum kit, bass, guitar, kalimba, metronome and tuner in your menu bar. Plays while another app has focus. The app and the piano are free. *[On the Mac App Store](https://apps.apple.com/app/id6801593827).* |
| **[Kick Kick](https://kickkick.bulatapps.com/)** | A football goal and a ball floating over your whole desktop. Clicks fall through everywhere except on the ball. *[On the Mac App Store](https://apps.apple.com/app/id6801598144).* |
| **[Hoop Hoop](https://hoophoop.bulatapps.com/)** | The same quiet overlay, with a basketball hoop. *[On the Mac App Store](https://apps.apple.com/app/id6801598264).* |

### Games — Godot & Unity

| | |
|---|---|
| **Mind the Patient** | Co-op physics comedy: two players carry a stretcher through places a stretcher was never meant to go. *In development.* |
| **HOLMGANG** | Medieval melee battle royale with classes and parrying that costs you something. *Prototype.* |
| **Vine Out** | A colour-match puzzle — pull a tangled root out through a matching exit without trapping the ones behind it. *In development, mobile.* |
| **HADAL** | Four-player deep-sea salvage horror. *On hold.* |

### Open source

**[QuietOverlay](https://github.com/safabulat/quiet-overlay)** — the shell underneath the desk toys,
extracted. A whole-screen macOS overlay window that clicks fall straight through, except where you say
they should not, and that can never steal keyboard focus from the app you were typing in. Swift package,
macOS 13+, MIT.

### Elsewhere

- Support for every app and game above: **safabulatdev@icloud.com**
- The long version: [linkedin.com/in/safabulat](https://www.linkedin.com/in/safabulat/)

<sub>Swift · UIKit · AppKit · Core Animation · CoreBluetooth · AVAudioEngine · Godot · GDScript · Unity · C# · TypeScript · C/C++ · Python — with an embedded-systems past that never stopped counting bytes.</sub>
