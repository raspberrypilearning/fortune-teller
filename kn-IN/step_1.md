## ಪರಿಚಯ

ಭವಿಷ್ಯವನ್ನು ಓದಲು ನಿಮ್ಮ micro:bit ಅನ್ನು ನೀವು code ಮಾಡಲು ಹೊರಟಿದ್ದೀರಿ! micro:bit ಗೆ ಪ್ರಶ್ನೆಯನ್ನು ಕೇಳಿ, ಮತ್ತು ಉತ್ತರವನ್ನು ಕಂಡುಹಿಡಿಯಲು ಬಟನ್ ಒತ್ತಿರಿ!

**ಸೂಚನೆಗಳು**: ನೀವು ಇದನ್ನು ಆನ್‌ಲೈನ್‌ನಲ್ಲಿ ಓದುತ್ತಿದ್ದರೆ, micro:bit ಅನ್ನು ಪ್ರಶ್ನೆ ಕೇಳಿ ಮತ್ತು ಉತ್ತರವನ್ನು ಪಡೆಯಲು**A** ಒತ್ತಿ!

<div style="position:relative;height:0;padding-bottom:125%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_X8jUAqb9mdfj" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### ಕ್ಲಬ್ ನಾಯಕರಿಗೆ ಹೆಚ್ಚು ಮಾಹಿತಿ

ನೀವು ಈ ಯೋಜನೆಯನ್ನು ಮುದ್ರಿಸಬೇಕಾದರೆ, ದಯವಿಟ್ಟು [ಮುದ್ರಕ-ಸ್ನೇಹಿ ಆವೃತ್ತಿಯನ್ನು](https://projects.raspberrypi.org/kn-IN/projects/fortune-teller/print) ಬಳಸಿ.

--- collapse ---
---
title: ಕ್ಲಬ್ ನಾಯಕ ಟಿಪ್ಪಣಿಗಳು
---

## ಪರಿಚಯ:

ಈ ಯೋಜನೆಯಲ್ಲಿ, ಮಕ್ಕಳು 'ಭವಿಷ್ಯವಾಣಿ' ಮಾಡುವ ಮೂಲಕ ಆಯ್ಕೆಯನ್ನು ಹೇಗೆ ಬಳಸಿಕೊಳ್ಳಬೇಕೆಂದು ಕಲಿಯುತ್ತಾರೆ. ಭವಿಷ್ಯವಾಣಿ ಮ್ಯಾಜಿಕ್ 8-ಬಾಲ್ ನಂತೆ ಕೆಲಸ ಮಾಡುತ್ತದೆ ಮತ್ತು ಬಳಕೆದಾರರು ಅವರ micro:bit ಗೆ ಕೇಳುವ ಪ್ರಶ್ನೆಗೆ ಉತ್ತರವನ್ನು ನೀಡುತ್ತದೆ.

## ಸಂಪನ್ಮೂಲಗಳು

ಈ ಯೋಜನೆಗೆ [MakeCode (PXT)](http://jumpto.cc/pxt-new) ಮೈಕ್ರೋಬಿಟ್ ಎಡಿಟರ್ ಅನ್ನು ಉಪಯೋಗಿಸಿ.

ಈ ಪ್ರೋಜೆಕ್ಟಿನ ಪೂರ್ಣ ಆವೃತ್ತಿ ನಿಮಗೆ [makecode.microbit.org/#pub:18828-96734-17356-00995](https://makecode.microbit.org/#pub:18828-96734-17356-00995) ನಲ್ಲಿ ಸಿಗುತ್ತದೆ, ಹಾಗು ಸಂಕಲಿಸಲಾಗಿದೆ .hex ಫೈಲನ್ನು ಡೌನ್ಲೋಡ್ ಮಾಡಲು 'Download Project Materials' ಲಿಂಕ್ ಅನ್ನು ಒತ್ತಿರಿ. ಅಲ್ಲಿ ನಿಮಗೆ ಕೆಳಗೆ ತೋರಿಸಿದ ಫೈಲ್ಸ್ ಸಿಗುತ್ತದೆ:

* FortuneTeller.hex

## ಕಲಿಕೆ ಉದ್ದೇಶಗಳು

* ಆಯ್ಕೆ `if` block ಗಳು;
* `random` block.

ಈ ಯೋಜನೆಯು [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum) ಎಳೆಗಳಿಂದ ಕೆಳಗಿನ ಅಂಶಗಳನ್ನು ಒಳಗೊಂಡಿದೆ:

* [ಸರಳ ಪ್ರೊಗ್ರಾಂಗಳನ್ನು ರಚಿಸಲು ಮೂಲ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ರಚನೆಗಳನ್ನು ಬಳಸಿ.](https://www.raspberrypi.org/curriculum/programming/creator)

## ಸವಾಲುಗಳು

* "ಬಹು ಉತ್ತರಗಳು" - 'ಇಲ್ಲ' (No) ಮತ್ತು 'ಮತ್ತೆ ಕೇಳಿ' (Ask again) ಉತ್ತರಗಳನ್ನು ಸೇರಿಸುವ ಮೂಲಕ, `if` block ಅನ್ನು ಬಳಕೆ ಮಾಡಿ.
* "ನಿಮ್ಮ micro:bit ಅನ್ನು ಅಲ್ಲಾಡಿಸಿ" - button ಒತ್ತುವ ಬದಲು micro:bit ಅನ್ನು ಅಲ್ಲಾಡಿಸಿ.

--- /collapse ---

--- collapse ---
---
title: ಯೋಜನೆಯ ವಸ್ತುಗಳು
---

## ಕ್ಲಬ್ ನಾಯಕ ಸಂಪನ್ಮೂಲಗಳು

* [ಆನ್‌ಲೈನ್ ಪೂರ್ಣಗೊಂಡ ಪ್ರಾಜೆಕ್ಟ್](https://makecode.microbit.org/#pub:18828-96734-17356-00995)
* [.hex ಪ್ರಾಜೆಕ್ಟ್ ಫೈಲ್ ಅನ್ನು ನಿಮ್ಮ micro:bit ‌ಗೆ ವರ್ಗಾಯಿಸಲು](resources/microbit-Fortune-Teller.hex)

--- /collapse ---