---
layout: post.njk
title: Mass Spectrometry Music
description: Converting spectra data into sound
date: 2026-03-14
tags: posts
---

> In 1999, Cyril Smith, a Stanford professor of physics, played the (cacophonic) music of thyroxin during a convention, but the performance was immediately suspended because many people in the audience suddenly experienced tachycardia [rapid heartbeat]. What happened? The music had reproduced one of the effects of an excess of thyroid hormone: thyroxin overdose.
>
> — Reported in *The Basic Code of the Universe* by Massimo Citro (citing C. Smith, International Conference, Hidden Properties of Water, The Polyclinic, Medical and Surgical Department, Napoli, 1999.)

I had stumbled across this on X a few years back, and ever since then I have been interested in this idea of converting hormones, and other chemical data into sound. To this day I am not quite sure how Dr. Smith made that sound, and the idea warrants skepticism, but I do find it to be an interesting way of experimenting with audio. I ended up building a pretty neat (at least I think) web application around this concept. I'll briefly discuss the journey and some of the more interesting details.

I'm no expert in DSP or chemistry, but I know my way around building some basic python scripts and using DSP related tools like max/msp. Naturally, that is where this project started.

In my research I had come across mass spectrometry data, which had similarity to my own understanding of additive synthesis. The spectrometry data being just a list of m/z values and intensities - this complemented perfectly with my understanding of audio - just a bunch of sine waves which are just frequencies and volumes. The commonality being they both are just two columns of data. All I had to do was convert the spectrometry data into audio data. Early experiments with this were rather manual, but this was the foundation of what eventually became...

[Mass Spectrum to Audio Converter](https://mass-spectrum-to-audio-converter.onrender.com/)

*English Suite No. 3 in G minor Prelude (BWV 808)* — Johann Sebastian Bach

<audio controls>
  <source src="/audio/english_suite_no_3_oxytocin.mp3" type="audio/mpeg">
</audio>
<p class="attribution">Based on a MIDI sequence by Gary Bricault. Original source: <a href="http://www.jsbach.net/midi/midi_english_suites.html" target="_blank" rel="noopener noreferrer">jsbach.net</a></p>

*Concerto in F "in the Italian Manner" for Solo Keyboard (first mvmt.), BWV 971* — Johann Sebastian Bach

<audio controls>
  <source src="/audio/concerto_in_f_oxytocin.mp3" type="audio/mpeg">
</audio>
<p class="attribution">Based on a MIDI sequence by T.L. Hubeart Jr. Original source: <a href="http://www.jsbach.net/midi/midi_solo_keyboard.html" target="_blank" rel="noopener noreferrer">jsbach.net</a></p>

Above are two tracks made via oxytocin mass spectrum data. I chose some Bach pieces, as I thought the harpsichord-like character of the sound was fitting.

One of these days I plan to release an album centered around this concept. The process has been a bit challenging, as the restrictions I have set for the album (using spectrum-generated sounds as the primary sound source) are quite limiting. Below are a few tracks that I like so far.

*Iridin*

<audio controls>
  <source src="/audio/Iridin.mp3" type="audio/mpeg">
</audio>

*Adenosine*

<audio controls>
  <source src="/audio/Adenosine.mp3" type="audio/mpeg">
</audio>

*Thyroxin*

<audio controls>
  <source src="/audio/Thyroxin.mp3" type="audio/mpeg">
</audio>

I don't think I'll be causing tachycardia (at least I hope not), but the idea has proved to be a useful framework for artistic exploration.

> Everything vibrates and emits elastic waves that can be translated into sound, so everything plays music with those little bells that are molecules... Each substance has its own sound.
>
> — Massimo Citro, *The Basic Code of the Universe*