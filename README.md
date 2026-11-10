Maggie

what actually happens in those few seconds?
it listens: the mics pick up your voice and turn the audio into data.
it wakes up: the esp32-s3 catches the wake word (or a button press), so it knows you're talking to it and not just someone nearby.
off to the cloud: the chip is too small to run heavy ai locally, so it shoots your recording over wi-fi to the xiaozhi servers.
the brain does its thing: the servers do the heavy lifting—running stt (speech-to-text), pinging the ai model for a response, and converting that answer back into tts audio.
it talks back: the hardware receives the audio stream, the amp boosts it, and the speaker plays it right next to your ear.
so basically, the hardware is just a mic, a speaker, and a wi-fi link packed into a sick enclosure. all the actual intelligence lives in the cloud.


what my design actually adds ?
on its own, the base software is just a talking box. my project turns it into a physical wearable companion on your shoulder. here's what i am designing and building from scratch:
the aesthetics: character design, overall shape, and how the eyes look.
kinematics: how it physically moves (turning head, eye expressions).
the mount: how it actually attaches to you with magnets ( Maggie,s base has a magnet and will design a shoulder stand which would be magnetic as well so it stays comfortable.
vibe & expressions: syncing leds or a small display to its current state (listening, thinking, speaking) so it feels alive.
