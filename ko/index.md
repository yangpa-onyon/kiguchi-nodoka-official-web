---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: about
title: 키구치 노도카
title_override_in_header: 홈
heading: " "
lang: "ko"
---

![키구치 노도카](/assets/images/images/kiguchi_nodoka.png)

# 키구치 노도카?

키구치 노도카(機口喉歌)는 아다치 레이에 영감을 받아 만들어진 무생물 UTAU 음원입니다. 성우의 녹음 없이, 물리 기반 발성 기관 시뮬레이션만을 통해 목소리를 만들어냅니다.

성대에서 만들어진 소리가 혀, 입술, 비강을 지나며 공명하는 과정을 시간에 따라 실제처럼 변화시키기 때문에, 단순한 자음과 모음의 나열을 넘어 설득력 있는 음색으로 노래할 수 있는 것이 특징입니다.

* [VCV 한국어 음원 다운로드](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_KO.zip)

* [VCCV 영어 음원 다운로드](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_EN.zip)

* [연속음 일본어 음원 다운로드](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_JA.zip)

* [연속음 toki pona 음원 다운로드](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_TOK.zip)

  * toki pona는 별도의 [포네마이저 플러그인](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/TokiPonaPhonemizer.dll) 설치가 필요합니다.

* ~~CVV 중국어 음원 다운로드~~ Coming soon...

* ~~VCV 타갈로그어(필리핀어) 음원 다운로드~~ Coming soon...

* 모든 음원은 리샘플러로 doppeltler를 추천합니다.

<iframe width="560" height="315" src="https://www.youtube.com/embed/slL1QwSWpvI?si=WrZ83hVeWAhk1DkZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

(원곡: [Portal 2: End Credits Song 'Want You Gone' by Jonathan Coulton](https://youtu.be/dVVZaZ8yO6o?feature=shared))

# 발성기관 시뮬레이션?

사람의 목소리는 흔히 '소스 - 필터 모델'로 설명할 수 있습니다.

* 소스 : 성대가 진동하며 기본 진동수를 갖는 소리를 만들어 냅니다.
* 필터 : 그 소리가 혀, 입술, 구강, 비강과 같은 좁고 굽은 통로를 통과하며 여러 주파수 대역이 증폭, 감쇠되며 포먼트 주파수가 만들어집니다.

흔히 만들어지는 무생물 음원들은 Vocalizer 등의 포먼트 필터를 사용해 소리를 빚습니다. 이는 단순한 모음을 만드는 데는 유용하지만, 음절 복잡도가 높은 언어로 갈 수록 그 한계가 분명해집니다.

* 시간이 지나며 성도의 모양이 부드럽게 변하는 이중 모음
* 파열음(p, t, k 등), 마찰음(s, f 등)과 같은 순간적이거나 난류성을 띄는 특징
* 자음군(sp, str, znt 등)

그래서 그동안의 무생물 음원은 일본어 등의 음절 복잡도가 낮은 언어에 주로 맞춰져 있었고, 그 커뮤니티도 일본 및 주변국의 커뮤니티로 한정되어 있었습니다. 키구치 노도카는 이런 기존의 무생물 음원 제작 방식과는 다른 방식으로 만들어졌습니다.

* 성도 전체를 연속된 작은 관으로 나누고, 각 관의 단면적 변화에 따라 생기는 반사/전달을 물리적으로 시뮬레이션합니다.
* 성대의 소스(울림, 기식 등)를 시간에 따라 바꾸며, 파열음과 마찰성 난류를 성도에 물리적으로 주입합니다.
* 혀, 입술의 자연스러운 위치 변화를 통해 포먼트가 자연스럽게 이동하도록 합니다.
 
결과적으로 키구치 노도카는 이중모음이나 복잡한 자음군 등 기존의 방식으로 구현하기 힘들었던 발음들에서 뚜렷한 발음을 보여주며, 수많은 언어를 지원할 수 있는 구조를 갖습니다. 성우가 없는 무생물 음원이지만, 발성 기관의 원인과 결과를 따라가며 만들어진 소리로 설득력 있는 음색을 얻을 수 있습니다.