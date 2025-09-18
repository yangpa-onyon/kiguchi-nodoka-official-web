---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: about
title: Kiguchi Nodoka
title_override_in_header: Home
heading: " "
---

![Kiguchi Nodoka](/assets/images/images/kiguchi_nodoka.png)

# Kiguchi Nodoka?

Kiguchi Nodoka (機口喉歌) is an inanimate UTAU voicebank project inspired by Adachi Rei. It generates voice without a human voice actor, using only a physics-based simulation of the vocal tract.

Because the sound produced at the glottis is modeled as it resonates through the tongue, lips, and nasal cavity, changing realistically over time, Nodoka can sing with a convincing timbre, beyond a simple sequence of isolated consonants and vowels.

## stable (beta 0.2.0)

* [VCCV English voicebank download](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_EN.zip)

* [VCV Japanese voicebank download (日本語連続音)](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_JA.zip)

* [VCV Korean voicebank download (한국어 VCV)](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_KO.zip)

* [VCV toki pona voicebank download](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_TOK.zip)

  * toki pona requires a separate [phonemizer plugin](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/TokiPonaPhonemizer.dll) to be installed.

* ~~CVV Chinese voicebank download~~ Coming soon...

* ~~VCV Tagalog(Filipino) voicebank download~~ Coming soon...

* doppeltler is recommended as a resampler for all voicebank.

## preview (beta 0.3.0 preview 1)

* [VCCV English voicebank download](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.3.0_preview1/KIGUCHI_NODOKA_EN.zip)

* [VCV Japanese voicebank download (日本語連続音)](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.3.0_preview1/KIGUCHI_NODOKA_JA.zip)

* [VCV Korean voicebank download (한국어 VCV)](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.3.0_preview1/KIGUCHI_NODOKA_KO.zip)

* [VCV toki pona voicebank download](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.3.0_preview1/KIGUCHI_NODOKA_TOK.zip)

  * toki pona requires a separate [phonemizer plugin](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.3.0_preview1/TokiPonaPhonemizer.dll) to be installed.

* ~~CVV Chinese voicebank download~~ Coming soon...

* ~~VCV Tagalog(Filipino) voicebank download~~ Coming soon...

* doppeltler is recommended as a resampler for all voicebank.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Y-0FhxAVppM?si=gFeDELW0zvrx8Vuc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

(Original song: [목성은 사랑을 한다 - 상록수](https://youtu.be/YfbYaT-PiKc?feature=shared))

(ustx: [goldenriver8](https://youtu.be/Ho5hrOG2DBc?feature=shared))

# Vocal tract simulation?

Human voice production is often described by a source–filter model.

* Source: The vocal folds vibrate, producing a sound with a fundamental frequency and overtones.
* Filter: That sound passes through the tongue, lips, oral and nasal cavities—narrow, curved passages that amplify or attenuate certain frequencies, forming formants.

Many inanimate voicebanks are crafted with formant filters (e.g. Vocalizer). This works well for simple vowels, but its limits become clear as you move to languages with higher syllable complexity, especially for:

* Diphthongs where the tract shape changes smoothly over time.
* Stop consonants (p, t, k) and fricatives (s, f) with transient or turbulent characteristics.
* Consonant clusters (e.g. sp, str, znt).

As a result, most inanimate voicebanks have been tailored to languages like Japanese with relatively simple syllable structure, and their communities have largely remained within Japan and neighboring regions. Then, how is Nodoka different?

* The vocal tract is divided into a series of small tube segments, and reflection/transmission due to area changes is simulated physically.
* The glottal source (voicing, breathiness, etc) varies over time, and stops/fricative turbulence is physically injected into the tract.
* Tongue and lip positions change naturally so that formants move smoothly.

Consequently, Kiguchi Nodoka achieves clear articulation in sounds that are hard to realize with conventional methods such as diphthongs and complex consonant clusters, and it’s structurally suited to many languages. Although it’s an inanimate voicebank with no voice actor, its sound follows the cause-and-effect of the human vocal apparatus, resulting in a persuasive tone.