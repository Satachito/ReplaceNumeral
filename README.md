# ReplaceNumeral

For the use case, visit our awesome calculator site, https://slip.828.tokyo/

Replace all numerals in the world into Arabic numerals.

#install

```
npm i @satachito/replace-numeral
```

# Usage

```
import ReplaceNumeral from './_.js'
console.log( ReplaceNumeral( '０１２３４５６７８９０１２３４５６７８９' ) )
01234567890123456789
console.log( ReplaceNumeral( '𐒠𐒡𐒢𐒣𐒤𐒥𐒦𐒧𐒨𐒩𐒠𐒡𐒢𐒣𐒤𐒥𐒦𐒧𐒨𐒩' ) )
01234567890123456789
```

# Accurate listings

https://util.unicode.org/UnicodeJsps/list-unicodeset.jsp?a=[:Numeric_Type=Decimal:]

```
000030: 0123456789
000660: ٠١٢٣٤٥٦٧٨٩
0006f0: ۰۱۲۳۴۵۶۷۸۹
0007c0: ߀߁߂߃߄߅߆߇߈߉
000966: ०१२३४५६७८९
0009e6: ০১২৩৪৫৬৭৮৯
000a66: ੦੧੨੩੪੫੬੭੮੯
000ae6: ૦૧૨૩૪૫૬૭૮૯
000b66: ୦୧୨୩୪୫୬୭୮୯
000be6: ௦௧௨௩௪௫௬௭௮௯
000c66: ౦౧౨౩౪౫౬౭౮౯
000ce6: ೦೧೨೩೪೫೬೭೮೯
000d66: ൦൧൨൩൪൫൬൭൮൯
000de6: ෦෧෨෩෪෫෬෭෮෯
000e50: ๐๑๒๓๔๕๖๗๘๙
000ed0: ໐໑໒໓໔໕໖໗໘໙
000f20: ༠༡༢༣༤༥༦༧༨༩
001040: ၀၁၂၃၄၅၆၇၈၉
001090: ႐႑႒႓႔႕႖႗႘႙
0017e0: ០១២៣៤៥៦៧៨៩
001810: ᠐᠑᠒᠓᠔᠕᠖᠗᠘᠙
001946: ᥆᥇᥈᥉᥊᥋᥌᥍᥎᥏
0019d0: ᧐᧑᧒᧓᧔᧕᧖᧗᧘᧙
001a80: ᪀᪁᪂᪃᪄᪅᪆᪇᪈᪉
001a90: ᪐᪑᪒᪓᪔᪕᪖᪗᪘᪙
001b50: ᭐᭑᭒᭓᭔᭕᭖᭗᭘᭙
001bb0: ᮰᮱᮲᮳᮴᮵᮶᮷᮸᮹
001c40: ᱀᱁᱂᱃᱄᱅᱆᱇᱈᱉
001c50: ᱐᱑᱒᱓᱔᱕᱖᱗᱘᱙
00a620: ꘠꘡꘢꘣꘤꘥꘦꘧꘨꘩
00a8d0: ꣐꣑꣒꣓꣔꣕꣖꣗꣘꣙
00a900: ꤀꤁꤂꤃꤄꤅꤆꤇꤈꤉
00a9d0: ꧐꧑꧒꧓꧔꧕꧖꧗꧘꧙
00a9f0: ꧰꧱꧲꧳꧴꧵꧶꧷꧸꧹
00aa50: ꩐꩑꩒꩓꩔꩕꩖꩗꩘꩙
00abf0: ꯰꯱꯲꯳꯴꯵꯶꯷꯸꯹
00ff10: ０１２３４５６７８９
0104a0: 𐒠𐒡𐒢𐒣𐒤𐒥𐒦𐒧𐒨𐒩
010d30: 𐴰𐴱𐴲𐴳𐴴𐴵𐴶𐴷𐴸𐴹
011066: 𑁦𑁧𑁨𑁩𑁪𑁫𑁬𑁭𑁮𑁯
0110f0: 𑃰𑃱𑃲𑃳𑃴𑃵𑃶𑃷𑃸𑃹
011136: 𑄶𑄷𑄸𑄹𑄺𑄻𑄼𑄽𑄾𑄿
0111d0: 𑇐𑇑𑇒𑇓𑇔𑇕𑇖𑇗𑇘𑇙
0112f0: 𑋰𑋱𑋲𑋳𑋴𑋵𑋶𑋷𑋸𑋹
011450: 𑑐𑑑𑑒𑑓𑑔𑑕𑑖𑑗𑑘𑑙
0114d0: 𑓐𑓑𑓒𑓓𑓔𑓕𑓖𑓗𑓘𑓙
011650: 𑙐𑙑𑙒𑙓𑙔𑙕𑙖𑙗𑙘𑙙
0116c0: 𑛀𑛁𑛂𑛃𑛄𑛅𑛆𑛇𑛈𑛉
011730: 𑜰𑜱𑜲𑜳𑜴𑜵𑜶𑜷𑜸𑜹
0118e0: 𑣠𑣡𑣢𑣣𑣤𑣥𑣦𑣧𑣨𑣩
011950: 𑥐𑥑𑥒𑥓𑥔𑥕𑥖𑥗𑥘𑥙
011c50: 𑱐𑱑𑱒𑱓𑱔𑱕𑱖𑱗𑱘𑱙
011d50: 𑵐𑵑𑵒𑵓𑵔𑵕𑵖𑵗𑵘𑵙
011da0: 𑶠𑶡𑶢𑶣𑶤𑶥𑶦𑶧𑶨𑶩
016a60: 𖩠𖩡𖩢𖩣𖩤𖩥𖩦𖩧𖩨𖩩
016ac0: 𖫀𖫁𖫂𖫃𖫄𖫅𖫆𖫇𖫈𖫉
016b50: 𖭐𖭑𖭒𖭓𖭔𖭕𖭖𖭗𖭘𖭙
01d7ce: 𝟎𝟏𝟐𝟑𝟒𝟓𝟔𝟕𝟖𝟗
01d7d8: 𝟘𝟙𝟚𝟛𝟜𝟝𝟞𝟟𝟠𝟡
01d7e2: 𝟢𝟣𝟤𝟥𝟦𝟧𝟨𝟩𝟪𝟫
01d7ec: 𝟬𝟭𝟮𝟯𝟰𝟱𝟲𝟳𝟴𝟵
01d7f6: 𝟶𝟷𝟸𝟹𝟺𝟻𝟼𝟽𝟾𝟿
01e140: 𞅀𞅁𞅂𞅃𞅄𞅅𞅆𞅇𞅈𞅉
01e2f0: 𞋰𞋱𞋲𞋳𞋴𞋵𞋶𞋷𞋸𞋹
01e950: 𞥐𞥑𞥒𞥓𞥔𞥕𞥖𞥗𞥘𞥙
01fbf0: 🯰🯱🯲🯳🯴🯵🯶🯷🯸🯹
```
