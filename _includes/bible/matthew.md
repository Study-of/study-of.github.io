{% assign biblegateway = site.data.settings['biblegateway'] %}
{% assign chapter = include.chapter %}
{% assign verse = include.verses | split: '-' %}
{% assign search = 'Matthew+' + chapter + ':' + include.verses %}
>
**21** Ye have heard that it was said of them of old time, Thou shalt not kill; and whosoever shall kill shall be in danger of the judgment:
**22** But I say unto you, That whosoever is angry with his brother without a cause shall be in danger of the judgment: and whosoever shall say to his brother, {% include tooltip.html name="raca" %}, shall be in danger of the council: but whosoever shall say, Thou fool, shall be in danger of hell fire.
**23** Therefore if thou bring thy gift to the altar, and there rememberest that thy brother hath ought against thee;
**24** Leave there thy gift before the altar, and go thy way; first be reconciled to thy brother, and then come and offer thy gift.
**25** Agree with thine adversary quickly, whiles thou art in the way with him; lest at any time the adversary deliver thee to the judge, and the judge deliver thee to the officer, and thou be cast into prison.
**26** Verily I say unto thee, Thou shalt by no means come out thence, till thou hast paid the uttermost farthing.
[Matthew {{include.chapter}}:{{include.verses}}]({{biblegateway}}{{search}})
