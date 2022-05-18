# Morphology

Sekko, due to it being a logical (monoparsing) language, must necessarily have a self-segregating morphology (SSM). An SSM scheme is a system where words are constructed in such a way that word boundaries can be unambiguously determined using only the forms of the words themselves. 

While there are a variety of SSM schemes out there, Sekko uses an arbitrary classification of sounds along with a **A+B+** word form. All words contain one or more A components, followed by one or more B components. A word boundary is defined as when a series of **B** sequences makes contact with an **A** component.

Sekko categorizes sounds as either **A**, **B**, or **C**. **A** and **B** sounds behave as described above. **C** sounds, however, will morph into the sound that immediately precedes them. Therefore, a sequence `ACCACBCCC` will be interpreted as `AAAAABBBB`.

- **A** sounds: **p t k b d g s z h**
- **B** sounds: **i o m q**
- **C** sounds: **a e u n l r x**

The speech stream **baqpakketexoiambanauelromepi** `ACBACAACACCBBCBACCCCCCCCBBBCAB`  can be unambiguously parsed as **baq pakketexoiam banauelrome pi** `ACB ACAACACCBBCB ACCCCCCCBBBC AB`.

Word derivation is usually a priori. However, a posteriori derivation from languages with contrastive vowel and consonant length is permitted (e.g. Finnish, Japanese, Hindi, Latin, etc.).



