
# EnDeu

EnDeu is a highly ergonomic English/German keyboard layout for standard ISO keyboards or 3×6 columnar staggered keyboards. It scores well in layout analyzer statistics, but the typing feel is even better in practice. Unlike many modern layouts optimized primarily for English, EnDeu maintains consistent ergonomic performance across both English and German. It is also a strong basis for adaptation to other European languages such as Dutch, French and Spanish.

This layout is an alternative to [anymak:END](https://github.com/rpnfan/Anymak). It is based on the same proven principles, with the following differences:

The default shift key position from a standard keyboard is kept unchanged. This allows more keys to be used for characters, which brings both advantages and disadvantages compared to anymak:END.

**Advantages over anymak:END**

* Keeping shift in its default position improves certain analyzer statistics, such as same-finger-bigrams.
* The layout includes all German diacritics on the base layer, rather than requiring access via a separate layer. This is arguably the more significant difference in everyday use.

**Disadvantages over anymak:END**

* The shift key remains in its standard position, which requires an unergonomic stretch of the pinky — or lifting the hand entirely. In contrast, anymak:END avoids the ISO shift key positions altogether. One-shot shift can be used with EnDeu to mitigate this. Note that EnDeu requires an ISO keyboard and cannot be meaningfully adapted to an ANSI keyboard. If you primarily use ANSI keyboards, English is likely your main language, and anymak:END is the suggested layout in that case.
* anymak:END places a one-shot layer key on both the left and right hand. In EnDeu, the right-hand layer key position is used for "ß", which removes that option. One workaround: place the less frequently used "ß" on the B-key (QWERTY) or #-key (QWERTZ) position, freeing that key for a one-shot layer switch. (Swiss users can recover that position directly, since "ß" is not used in Swiss German.)

Whether you prefer anymak:END or EnDeu comes down to personal preference. Both layouts feel great, with somewhat different strengths and trade-offs — though overall they are very similar. The most practical differences are the placement of the shift keys and the umlauts. EnDeu can and should be complemented with extra symbol, navigation and shortcut layers. See the [Spacemak](https://github.com/rpnfan/Spacemak) ideas for that.

## Layout Overview

The layout can be used directly on an ISO keyboard. The finger positions are symmetrical for left and right hand. On the left hand: "qhk" is the pinky column, ".aä" the ring finger column, and so on. See also the finger columns on a columnar staggered keyboard below. For both keyboard types the hand positions are identical and symmetrical.

### ISO Keyboard Layout

<img width="1403" height="387" alt="image" src="https://github.com/user-attachments/assets/13a60867-f2a0-445e-9e83-371ab98a0da0" />

### Split Columnar Staggered Layout

This is how the layout looks on a columnar staggered split keyboard, shown here with J and ß swapped. This is a minor variation — neither version is objectively better, so choose whichever you prefer.

<img width="1430" height="391" alt="image" src="https://github.com/user-attachments/assets/64434a40-cb5c-48f5-aa0f-dc0a169c5d3e" />

## Statistics

The screenshots below are taken from the Cyanophage analyzer and give a first impression of how the layout performs. Note upfront that no analyzer fully captures real-world typing feel. For example, the layout could be tweaked to slightly reduce same-finger-bigrams (SFBs) by swapping M and W — but the current positions were chosen deliberately for comfort. Try typing "will", "much", "poland" and "wc" with both variants and decide based on your preference, or based on whether you prefer the more frequent "m" or the slightly less frequent "w" on the stronger middle finger.

Also worth noting: [analyzers sometimes cannot fully describe a layout](https://rpnfan.github.io/keyboard-heaven/deep-dive/keyboard-layout-analyzers/). For anymak:END, most analyzers do not account for the easy reach of the shift and symbol layer keys — if they did, the numbers would be even better. The practical benefit of one-shot layer keys is similarly invisible to analyzers. On the other hand, the extra effort to access umlauts on a symbol layer is also not factored in, which would slightly increase effort metrics for that layout.

**Comparison with Graphite and Gallium**

Graphite and Gallium are modern layouts with a growing following — and for good reason, as they are well-balanced and widely enjoyed. EnDeu shares that goal of balance across all layout parameters. Compared to Graphite, EnDeu places slightly less emphasis on minimizing same-finger-bigrams, while still keeping them low. The remaining SFBs on EnDeu fall mostly on the strong index and middle fingers, moving from the top row back to the home row — which makes them relatively comfortable. On keyboards with U-shaped keycaps such as [MCC](https://kbd.news/MCC-keycap-profile-962.html) for Choc switches, the finger can even rake smoothly between rows.

Another difference is that high-frequency keys are placed on the stronger index and middle fingers where possible. This is one reason "e" sits on the middle finger rather than the weaker ring finger position it occupies in Graphite and Gallium. All three layouts largely avoid awkward movements such as scissors, redirects, SFBs and large stretches, and perform similarly in those respects.

Hand alternation — avoiding long same-hand sequences — is one of the most important characteristics of a comfortable layout. Again, all three layouts perform closely here.

Where EnDeu stands out is in two areas. First, for a high-alternation layout it achieves a relatively high rate of inward rolls: 27.7% for English, compared to 21.7% for Graphite. This is on the high side for standard keyboard layouts and is something you are likely to feel and appreciate while typing. Second, EnDeu is genuinely optimized for multiple languages simultaneously, offering roughly equivalent comfort across several European languages — not just English. Note that despite the multilingual approach. EnDeu is a great option for English only use as well.

**Try it and trust your fingers**

Layout analyzers are valuable for development and initial comparison, but after narrowing down to two or three candidates, the best approach is to try them with a handful of real words. Using a [website to try out layouts](https://www.reddit.com/r/KeyboardLayouts/comments/1r1eegt/try_out_keyboard_layouts_a_systematic_approach/) is highly recommended and will help you find the layout that best fits your use case, hand size and keyboard type.

### EnDeu — English
https://cyanophage.github.io/playground.html?layout=q.ouyvdclf%5Chaei%2Cgtrnsjk%2F-%3Bxbpmwz%27%5E&mode=ergo&lan=english&thumb=l
<img width="1516" height="1160" alt="image" src="https://github.com/user-attachments/assets/8b206ea2-980c-43b4-a1f8-1b9ea1b88baa" />

### Graphite — English
https://cyanophage.github.io/playground.html?layout=bldwz%27fouj%3Bnrtsgyhaei%2Cqxmcvkp.-%2F%5C%5E&mode=ergo&lan=english&thumb=l
<img width="1813" height="1383" alt="image" src="https://github.com/user-attachments/assets/4d84476d-6ef2-40b9-8c37-d3a7267e9643" />

### anymak:END — English
https://cyanophage.github.io/playground.html?layout=qkouyvdclfjhaei%2Cgtrns%3B%3Dz%27.xbpmw%2F%5C-&mode=ergo&lan=english&thumb=l
<img width="1813" height="1383" alt="image" src="https://github.com/user-attachments/assets/35b9a9dc-a741-4226-a35c-7d02c9e78f00" />

### EnDeu — German
https://cyanophage.github.io/playground.html?layout=q.ouyvdclf%C3%9Fhaei%2Cgtrnsjk%C3%A4%C3%B6%C3%BCxbpmwz%27%5E&mode=ergo&lan=german&thumb=l
<img width="1494" height="1152" alt="image" src="https://github.com/user-attachments/assets/f8ca55b4-c846-47ed-bbba-a9ab38da8955" />

### Graphite — German
Diacritics have been added here for comparison. The original Graphite layout does not include diacritics, and the statistics do not shift dramatically when they are added — regardless of how optimally they are placed. That said, in real-world typing the umlaut positions matter: even low-frequency characters become a source of frustration when they sit in awkward spots and break the typing flow.

https://cyanophage.github.io/playground.html?layout=bldwz%27fouj%C3%B6nrtsgyhaei%2Cqxmcvkp.%C3%BC%C3%A4%C3%9F%5E&mode=ergo&lan=german&thumb=l
<img width="1813" height="1383" alt="image" src="https://github.com/user-attachments/assets/4caa7eec-85a6-4bb2-aadf-e00a74fbd6a0" />

### anymak:END — German
Note that the Cyanophage analyzer cannot exactly represent how anymak:END is set up, since it does not account for one-shot shift, layer keys, or diacritics on an extra layer. The screenshot below is therefore an approximation, with umlauts placed on the base layer. Because umlauts are relatively infrequent, the statistics are close to the real layout — though they would be marginally better if the analyzer reflected the actual key positions.

https://cyanophage.github.io/playground.html?layout=qkouyvdclfjhaei%2Cgtrns%C3%9F%C3%B6z%27.xbpmw%C3%A4%3D%C3%BC&mode=ergo&lan=german&thumb=l
<img width="1813" height="1383" alt="image" src="https://github.com/user-attachments/assets/a8b5706a-3500-4448-b17a-2f44612bb031" />

## Statistics for other European languages

As a bonus, here are stats for a few other languages, showing that a slightly adapted EnDeu works well for Dutch, French and Spanish too. The layouts below are drafts — diacritics need to be added and fine-tuned for each language.

### EnNed — Dutch
https://cyanophage.github.io/playground.html?layout=q%3Bouyvdclf%5Chaei%2Cgtrns%2Fkj%27.xbpmwz-%5Eback&mode=ergo&lan=dutch&thumb=l
<img width="1503" height="1150" alt="image" src="https://github.com/user-attachments/assets/901088be-21f5-4d78-815e-f7d963ec25d3" />

The relatively high same-finger-bigram count here falls on the strong index and middle fingers (UI and OE), which in practice are comfortable to type and should not discourage you from trying the layout.

For Dutch and English combined, [this Gallium variant](https://www.reddit.com/r/KeyboardLayouts/comments/1oazi45/comment/nzq8ho1/?context=1) is also worth considering. It and EnNed have somewhat different strengths — the Gallium variant may have a slight edge for Dutch, while EnNed may perform a little better for English. Both are solid choices for the combination.

### EnFranç — French
https://cyanophage.github.io/playground.html?layout=qxouyvdclfjhaei.gtsrn%C3%A0k%C3%A7%C3%A8%C3%A9%2Cbpmwz%27%5E&mode=ergo&lan=french&thumb=l
<img width="1524" height="1178" alt="image" src="https://github.com/user-attachments/assets/9f91e970-fa05-476a-a7cf-d8f90c60d1c0" />

If French is your primary language with English as a second, [Optimot](https://optimot.fr/) is worth a look. The layout shown here is an alternative that performs well for both languages simultaneously. It should be considered a draft — since French/English is not my primary language combination, it has not been fully fine-tuned or tested. With some optimization of the diacritics and minor adjustments, it could be an excellent option, potentially surpassing Optimot especially for English. If you would like to develop a final version and want input or collaboration, feel free to open an issue on GitHub.

### EnEspan — Spanish
https://cyanophage.github.io/playground.html?layout=q.ouyvdclfjhaei%2Cgtrns%2Fk-%5C%C3%B1xbpmwz%27%5E&mode=ergo&lan=spanish&thumb=l
<img width="1813" height="1383" alt="image" src="https://github.com/user-attachments/assets/6a034304-2c05-4868-aa8e-e3d3f55ef8e1" />
