# UTF-8

UTF-8 (8-bit Unicode Transformation Format) 是一種針對 [[Unicode]] 的可變長度字元編碼，也是一種字首碼。

它可以用一至四個位元組對 [[Unicode]] 字元集中的所有有效編碼點進行編碼，屬於 [[Unicode]] 標準的一部分。

是[[World Wide Web|全球資訊網]]的最主要的編碼形式。

_如果希望在 [[HTML Introduction|HTML]] 中顯示任何這些字符，可以使用 [[HTML Introduction|HTML]] 實體。如果[[Character|字元]]沒有 [[HTML Introduction|HTML]] 實體，則可以使用十進位 (dec) 或十六進位 (hex) 引用。_

| Character codes                                         | Decimal       | Hexadecimal |
| ------------------------------------------------------- | ------------- | ----------- |
| [[#C0 Controls and Basic Latin]]                        | 0-127         | 0000-007F   |
| [[#C1 Controls and Latin-1 Supplement]]                 | 128-255       | 0080-00FF   |
| [[#Latin Extended-A]]                                   | 256-383       | 0100-017F   |
| [[# Latin Extended-B]]                                  | 384-591       | 0180-024F   |
| [[# Latin IPA]]                                         | 592-685       | 0250-02AD   |
| [[#Spacing Modifiers]]                                  | 688-767       | 02B0-02FF   |
| [[# Diacritical Marks]]                                 | 768-879       | 0300-036F   |
| [[# Greek and Coptic]]                                  | 880-1023      | 0370-03FF   |
| [[# Cyrillic Basic]]                                    | 1024-1279     | 0400-04FF   |
| [[# Cyrillic Supplement]]                               | 1280-1327     | 0500-052F   |
| [[# General Punctuation]]                               | 8192-8303     | 2000-206F   |
| [[# Currency Symbols]]                                  | 8352-8399     | 20A0-20CF   |
| [[# Letterlike Symbols]]                                | 8448-8527     | 2100-214F   |
| [[# Number Forms]]                                      | 8528-8591     | 2150-218F   |
| [[# Arrows]]                                            | 8592-8703     | 2190-21FF   |
| [[# Mathematical Operators]]                            | 8704-8959     | 2200-22FF   |
| [[# Box Drawings]]                                      | 9472-9599     | 2500-257F   |
| [[# Block Elements]]                                    | 9600-9631     | 2580-259F   |
| [[# Geometric Shapes]]                                  | 9632-9727     | 25A0-25FF   |
| [[# Miscellaneous Symbols]]                             | 9728-9983     | 2600-26FF   |
| [[# Dingbats]]                                          | 9984-10175    | 2700-27BF   |
| [[# UTF-8 Math Symbols A\|Misc Mathematical Symbols A]] | 10176-10223   | 27C0-27EF   |
| [[# Supplemental Arrows A]]                             | 10224-10239   | 27F0-27FF   |
| [[# Braille]]                                           | 10240-10495   | 2800-28FF   |
| [[# Supplemental Arrows B]]                             | 10496-10623   | 2900-297F   |
| [[# UTF-8 Math Symbols B\|Misc Mathematical Symbols B]] | 10624-10751   | 2980-29FF   |
| [[# Supplemental Math Operators]]                       | 10752-11007   | 2A00-2AFF   |
| [[# Misc Symbols and Arrows]]                           | 11008-11263   | 2B00-2BFF   |
| [[# Miscellaneous Technical]]                           | 8960-9215     | 2300-23FF   |
| [[# Enclosed Alphanumerics]]                            | 9312-9471     | 2460-24FF   |
| [[# Tiles and Playing Cards\|Tiles and Cards]]          | 126976-127231 | 1F000-1F0FF |

## C0 Controls and Basic Latin

### Basic Latin

Hex 0000-007F / Decimal 0-127.

_此字元集與原始 [[ASCII]] 字元集相同。_

| Char | Dec | Hex  | Entity   | Name                   |
| ---- | --- | ---- | -------- | ---------------------- |
|      | 32  | 0020 |          | SPACE                  |
| !    | 33  | 0021 |          | EXCLAMATION MARK       |
| "    | 34  | 0022 | `&quot;` | QUOTATION MARK         |
| \#   | 35  | 0023 |          | NUMBER SIGN            |
| $    | 36  | 0024 |          | DOLLAR SIGN            |
| %    | 37  | 0025 |          | PERCENT SIGN           |
| &    | 38  | 0026 | `&amp;`  | AMPERSAND              |
| '    | 39  | 0027 |          | APOSTROPHE             |
| (    | 40  | 0028 |          | LEFT PARENTHESIS       |
| )    | 41  | 0029 |          | RIGHT PARENTHESIS      |
| \*   | 42  | 002A |          | ASTERISK               |
| \+   | 43  | 002B |          | PLUS SIGN              |
| ,    | 44  | 002C |          | COMMA                  |
| \-   | 45  | 002D |          | HYPHEN-MINUS           |
| .    | 46  | 002E |          | FULL STOP              |
| /    | 47  | 002F |          | SOLIDUS                |
| 0    | 48  | 0030 |          | DIGIT ZERO             |
| 1    | 49  | 0031 |          | DIGIT ONE              |
| 2    | 50  | 0032 |          | DIGIT TWO              |
| 3    | 51  | 0033 |          | DIGIT THREE            |
| 4    | 52  | 0034 |          | DIGIT FOUR             |
| 5    | 53  | 0035 |          | DIGIT FIVE             |
| 6    | 54  | 0036 |          | DIGIT SIX              |
| 7    | 55  | 0037 |          | DIGIT SEVEN            |
| 8    | 56  | 0038 |          | DIGIT EIGHT            |
| 9    | 57  | 0039 |          | DIGIT NINE             |
| :    | 58  | 003A |          | COLON                  |
| ;    | 59  | 003B |          | SEMICOLON              |
| <    | 60  | 003C | `&lt;`   | LESS-THAN SIGN         |
| =    | 61  | 003D |          | EQUALS SIGN            |
| \>   | 62  | 003E | `&gt;`   | GREATER-THAN SIGN      |
| ?    | 63  | 003F |          | QUESTION MARK          |
| @    | 64  | 0040 |          | COMMERCIAL AT          |
| A    | 65  | 0041 |          | LATIN CAPITAL LETTER A |
| B    | 66  | 0042 |          | LATIN CAPITAL LETTER B |
| C    | 67  | 0043 |          | LATIN CAPITAL LETTER C |
| D    | 68  | 0044 |          | LATIN CAPITAL LETTER D |
| E    | 69  | 0045 |          | LATIN CAPITAL LETTER E |
| F    | 70  | 0046 |          | LATIN CAPITAL LETTER F |
| G    | 71  | 0047 |          | LATIN CAPITAL LETTER G |
| H    | 72  | 0048 |          | LATIN CAPITAL LETTER H |
| I    | 73  | 0049 |          | LATIN CAPITAL LETTER I |
| J    | 74  | 004A |          | LATIN CAPITAL LETTER J |
| K    | 75  | 004B |          | LATIN CAPITAL LETTER K |
| L    | 76  | 004C |          | LATIN CAPITAL LETTER L |
| M    | 77  | 004D |          | LATIN CAPITAL LETTER M |
| N    | 78  | 004E |          | LATIN CAPITAL LETTER N |
| O    | 79  | 004F |          | LATIN CAPITAL LETTER O |
| P    | 80  | 0050 |          | LATIN CAPITAL LETTER P |
| Q    | 81  | 0051 |          | LATIN CAPITAL LETTER Q |
| R    | 82  | 0052 |          | LATIN CAPITAL LETTER R |
| S    | 83  | 0053 |          | LATIN CAPITAL LETTER S |
| T    | 84  | 0054 |          | LATIN CAPITAL LETTER T |
| U    | 85  | 0055 |          | LATIN CAPITAL LETTER U |
| V    | 86  | 0056 |          | LATIN CAPITAL LETTER V |
| W    | 87  | 0057 |          | LATIN CAPITAL LETTER W |
| X    | 88  | 0058 |          | LATIN CAPITAL LETTER X |
| Y    | 89  | 0059 |          | LATIN CAPITAL LETTER Y |
| Z    | 90  | 005A |          | LATIN CAPITAL LETTER Z |
| [    | 91  | 005B |          | LEFT SQUARE BRACKET    |
| \    | 92  | 005C |          | REVERSE SOLIDUS        |
| ]    | 93  | 005D |          | RIGHT SQUARE BRACKET   |
| ^    | 94  | 005E |          | CIRCUMFLEX ACCENT      |
| _    | 95  | 005F |          | LOW LINE               |
| `    | 96  | 0060 |          | GRAVE ACCENT           |
| a    | 97  | 0061 |          | LATIN SMALL LETTER A   |
| b    | 98  | 0062 |          | LATIN SMALL LETTER B   |
| c    | 99  | 0063 |          | LATIN SMALL LETTER C   |
| d    | 100 | 0064 |          | LATIN SMALL LETTER D   |
| e    | 101 | 0065 |          | LATIN SMALL LETTER E   |
| f    | 102 | 0066 |          | LATIN SMALL LETTER F   |
| g    | 103 | 0067 |          | LATIN SMALL LETTER G   |
| h    | 104 | 0068 |          | LATIN SMALL LETTER H   |
| i    | 105 | 0069 |          | LATIN SMALL LETTER I   |
| j    | 106 | 006A |          | LATIN SMALL LETTER J   |
| k    | 107 | 006B |          | LATIN SMALL LETTER K   |
| l    | 108 | 006C |          | LATIN SMALL LETTER L   |
| m    | 109 | 006D |          | LATIN SMALL LETTER M   |
| n    | 110 | 006E |          | LATIN SMALL LETTER N   |
| o    | 111 | 006F |          | LATIN SMALL LETTER O   |
| p    | 112 | 0070 |          | LATIN SMALL LETTER P   |
| q    | 113 | 0071 |          | LATIN SMALL LETTER Q   |
| r    | 114 | 0072 |          | LATIN SMALL LETTER R   |
| s    | 115 | 0073 |          | LATIN SMALL LETTER S   |
| t    | 116 | 0074 |          | LATIN SMALL LETTER T   |
| u    | 117 | 0075 |          | LATIN SMALL LETTER U   |
| v    | 118 | 0076 |          | LATIN SMALL LETTER V   |
| w    | 119 | 0077 |          | LATIN SMALL LETTER W   |
| x    | 120 | 0078 |          | LATIN SMALL LETTER X   |
| y    | 121 | 0079 |          | LATIN SMALL LETTER Y   |
| z    | 122 | 007A |          | LATIN SMALL LETTER Z   |
| {    | 123 | 007B |          | LEFT CURLY BRACKET     |
| \|   | 124 | 007C |          | VERTICAL LINE          |
| }    | 125 | 007D |          | RIGHT CURLY BRACKET    |
| ~    | 126 | 007E |          | TILDE                  |

### C0 Controls

range: `00` - `31` and `127`.

控制字元符號，例如：

- Tab
- 換行 (line feed)
- 回車 (carriage return)

| Char | Number | Description            |
| ---- | ------ | ---------------------- |
| NUL  | 00     | null character         |
| SOH  | 01     | start of header        |
| STX  | 02     | start of text          |
| ETX  | 03     | end of text            |
| EOT  | 04     | end of transmission    |
| ENQ  | 05     | enquiry                |
| ACK  | 06     | acknowledge            |
| BEL  | 07     | bell (ring)            |
| BS   | 08     | backspace              |
| HT   | 09     | horizontal tab         |
| LF   | 10     | line feed              |
| VT   | 11     | vertical tab           |
| FF   | 12     | form feed              |
| CR   | 13     | carriage return        |
| SO   | 14     | shift out              |
| SI   | 15     | shift in               |
| DLE  | 16     | data link escape       |
| DC1  | 17     | device control 1       |
| DC2  | 18     | device control 2       |
| DC3  | 19     | device control 3       |
| DC4  | 20     | device control 4       |
| NAK  | 21     | negative acknowledge   |
| SYN  | 22     | synchronize            |
| ETB  | 23     | end transmission block |
| CAN  | 24     | cancel                 |
| EM   | 25     | end of medium          |
| SUB  | 26     | substitute             |
| ESC  | 27     | escape                 |
| FS   | 28     | file separator         |
| GS   | 29     | group separator        |
| RS   | 30     | record separator       |
| US   | 31     | unit separator         |
| DEL  | 127    | delete (rubout)        |

## C1 Controls and Latin-1 Supplement

### Latin-1 Supplement

Hex 0080-00FF / Decimal 128-255.

| Char | Dec | Hex  | Entity     | Name                                       |
| ---- | --- | ---- | ---------- | ------------------------------------------ |
|      | 160 | 00A0 | `&nbsp;`   | NO-BREAK SPACE                             |
| ¡    | 161 | 00A1 | `&iexcl;`  | INVERTED EXCLAMATION MARK                  |
| ¢    | 162 | 00A2 | `&cent;`   | CENT SIGN                                  |
| £    | 163 | 00A3 | `&pound;`  | POUND SIGN                                 |
| ¤    | 164 | 00A4 | `&curren;` | CURRENCY SIGN                              |
| ¥    | 165 | 00A5 | `&yen;`    | YEN SIGN                                   |
| ¦    | 166 | 00A6 | `&brvbar;` | BROKEN BAR                                 |
| §    | 167 | 00A7 | `&sect;`   | SECTION SIGN                               |
| ¨    | 168 | 00A8 | `&uml;`    | DIAERESIS                                  |
| ©    | 169 | 00A9 | `&copy;`   | COPYRIGHT SIGN                             |
| ª    | 170 | 00AA | `&ordf;`   | FEMININE ORDINAL INDICATOR                 |
| «    | 171 | 00AB | `&laquo;`  | LEFT-POINTING DOUBLE ANGLE QUOTATION MARK  |
| ¬    | 172 | 00AC | `&not;`    | NOT SIGN                                   |
| ­    | 173 | 00AD | `&shy;`    | SOFT HYPHEN                                |
| ®    | 174 | 00AE | `&reg;`    | REGISTERED SIGN                            |
| ¯    | 175 | 00AF | `&macr;`   | MACRON                                     |
| °    | 176 | 00B0 | `&deg;`    | DEGREE SIGN                                |
| ±    | 177 | 00B1 | `&plusmn;` | PLUS-MINUS SIGN                            |
| ²    | 178 | 00B2 | `&sup2;`   | SUPERSCRIPT TWO                            |
| ³    | 179 | 00B3 | `&sup3;`   | SUPERSCRIPT THREE                          |
| ´    | 180 | 00B4 | `&acute;`  | ACUTE ACCENT                               |
| µ    | 181 | 00B5 | `&micro;`  | MICRO SIGN                                 |
| ¶    | 182 | 00B6 | `&para;`   | PILCROW SIGN                               |
| ·    | 183 | 00B7 | `&middot;` | MIDDLE DOT                                 |
| ¸    | 184 | 00B8 | `&cedil;`  | CEDILLA                                    |
| ¹    | 185 | 00B9 | `&sup1;`   | SUPERSCRIPT ONE                            |
| º    | 186 | 00BA | `&ordm;`   | MASCULINE ORDINAL INDICATOR                |
| »    | 187 | 00BB | `&raquo;`  | RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK |
| ¼    | 188 | 00BC | `&frac14;` | VULGAR FRACTION ONE QUARTER                |
| ½    | 189 | 00BD | `&frac12;` | VULGAR FRACTION ONE HALF                   |
| ¾    | 190 | 00BE | `&frac34;` | VULGAR FRACTION THREE QUARTERS             |
| ¿    | 191 | 00BF | `&iquest;` | INVERTED QUESTION MARK                     |
| À    | 192 | 00C0 | `&Agrave;` | LATIN CAPITAL LETTER A WITH GRAVE          |
| Á    | 193 | 00C1 | `&Aacute;` | LATIN CAPITAL LETTER A WITH ACUTE          |
| Â    | 194 | 00C2 | `&Acirc;`  | LATIN CAPITAL LETTER A WITH CIRCUMFLEX     |
| Ã    | 195 | 00C3 | `&Atilde;` | LATIN CAPITAL LETTER A WITH TILDE          |
| Ä    | 196 | 00C4 | `&Auml;`   | LATIN CAPITAL LETTER A WITH DIAERESIS      |
| Å    | 197 | 00C5 | `&Aring;`  | LATIN CAPITAL LETTER A WITH RING ABOVE     |
| Æ    | 198 | 00C6 | `&AElig;`  | LATIN CAPITAL LETTER AE                    |
| Ç    | 199 | 00C7 | `&Ccedil;` | LATIN CAPITAL LETTER C WITH CEDILLA        |
| È    | 200 | 00C8 | `&Egrave;` | LATIN CAPITAL LETTER E WITH GRAVE          |
| É    | 201 | 00C9 | `&Eacute;` | LATIN CAPITAL LETTER E WITH ACUTE          |
| Ê    | 202 | 00CA | `&Ecirc;`  | LATIN CAPITAL LETTER E WITH CIRCUMFLEX     |
| Ë    | 203 | 00CB | `&Euml;`   | LATIN CAPITAL LETTER E WITH DIAERESIS      |
| Ì    | 204 | 00CC | `&Igrave;` | LATIN CAPITAL LETTER I WITH GRAVE          |
| Í    | 205 | 00CD | `&Iacute;` | LATIN CAPITAL LETTER I WITH ACUTE          |
| Î    | 206 | 00CE | `&Icirc;`  | LATIN CAPITAL LETTER I WITH CIRCUMFLEX     |
| Ï    | 207 | 00CF | `&Iuml;`   | LATIN CAPITAL LETTER I WITH DIAERESIS      |
| Ð    | 208 | 00D0 | `&ETH;`    | LATIN CAPITAL LETTER ETH                   |
| Ñ    | 209 | 00D1 | `&Ntilde;` | LATIN CAPITAL LETTER N WITH TILDE          |
| Ò    | 210 | 00D2 | `&Ograve;` | LATIN CAPITAL LETTER O WITH GRAVE          |
| Ó    | 211 | 00D3 | `&Oacute;` | LATIN CAPITAL LETTER O WITH ACUTE          |
| Ô    | 212 | 00D4 | `&Ocirc;`  | LATIN CAPITAL LETTER O WITH CIRCUMFLEX     |
| Õ    | 213 | 00D5 | `&Otilde;` | LATIN CAPITAL LETTER O WITH TILDE          |
| Ö    | 214 | 00D6 | `&Ouml;`   | LATIN CAPITAL LETTER O WITH DIAERESIS      |
| ×    | 215 | 00D7 | `&times;`  | MULTIPLICATION SIGN                        |
| Ø    | 216 | 00D8 | `&Oslash;` | LATIN CAPITAL LETTER O WITH STROKE         |
| Ù    | 217 | 00D9 | `&Ugrave;` | LATIN CAPITAL LETTER U WITH GRAVE          |
| Ú    | 218 | 00DA | `&Uacute;` | LATIN CAPITAL LETTER U WITH ACUTE          |
| Û    | 219 | 00DB | `&Ucirc;`  | LATIN CAPITAL LETTER U WITH CIRCUMFLEX     |
| Ü    | 220 | 00DC | `&Uuml;`   | LATIN CAPITAL LETTER U WITH DIAERESIS      |
| Ý    | 221 | 00DD | `&Yacute;` | LATIN CAPITAL LETTER Y WITH ACUTE          |
| Þ    | 222 | 00DE | `&THORN;`  | LATIN CAPITAL LETTER THORN                 |
| ß    | 223 | 00DF | `&szlig;`  | LATIN SMALL LETTER SHARP S                 |
| à    | 224 | 00E0 | `&agrave;` | LATIN SMALL LETTER A WITH GRAVE            |
| á    | 225 | 00E1 | `&aacute;` | LATIN SMALL LETTER A WITH ACUTE            |
| â    | 226 | 00E2 | `&acirc;`  | LATIN SMALL LETTER A WITH CIRCUMFLEX       |
| ã    | 227 | 00E3 | `&atilde;` | LATIN SMALL LETTER A WITH TILDE            |
| ä    | 228 | 00E4 | `&auml;`   | LATIN SMALL LETTER A WITH DIAERESIS        |
| å    | 229 | 00E5 | `&aring;`  | LATIN SMALL LETTER A WITH RING ABOVE       |
| æ    | 230 | 00E6 | `&aelig;`  | LATIN SMALL LETTER AE                      |
| ç    | 231 | 00E7 | `&ccedil;` | LATIN SMALL LETTER C WITH CEDILLA          |
| è    | 232 | 00E8 | `&egrave;` | LATIN SMALL LETTER E WITH GRAVE            |
| é    | 233 | 00E9 | `&eacute;` | LATIN SMALL LETTER E WITH ACUTE            |
| ê    | 234 | 00EA | `&ecirc;`  | LATIN SMALL LETTER E WITH CIRCUMFLEX       |
| ë    | 235 | 00EB | `&euml;`   | LATIN SMALL LETTER E WITH DIAERESIS        |
| ì    | 236 | 00EC | `&igrave;` | LATIN SMALL LETTER I WITH GRAVE            |
| í    | 237 | 00ED | `&iacute;` | LATIN SMALL LETTER I WITH ACUTE            |
| î    | 238 | 00EE | `&icirc;`  | LATIN SMALL LETTER I WITH CIRCUMFLEX       |
| ï    | 239 | 00EF | `&iuml;`   | LATIN SMALL LETTER I WITH DIAERESIS        |
| ð    | 240 | 00F0 | `&eth;`    | LATIN SMALL LETTER ETH                     |
| ñ    | 241 | 00F1 | `&ntilde;` | LATIN SMALL LETTER N WITH TILDE            |
| ò    | 242 | 00F2 | `&ograve;` | LATIN SMALL LETTER O WITH GRAVE            |
| ó    | 243 | 00F3 | `&oacute;` | LATIN SMALL LETTER O WITH ACUTE            |
| ô    | 244 | 00F4 | `&ocirc;`  | LATIN SMALL LETTER O WITH CIRCUMFLEX       |
| õ    | 245 | 00F5 | `&otilde;` | LATIN SMALL LETTER O WITH TILDE            |
| ö    | 246 | 00F6 | `&ouml;`   | LATIN SMALL LETTER O WITH DIAERESIS        |
| ÷    | 247 | 00F7 | `&divide;` | DIVISION SIGN                              |
| ø    | 248 | 00F8 | `&oslash;` | LATIN SMALL LETTER O WITH STROKE           |
| ù    | 249 | 00F9 | `&ugrave;` | LATIN SMALL LETTER U WITH GRAVE            |
| ú    | 250 | 00FA | `&uacute;` | LATIN SMALL LETTER U WITH ACUTE            |
| û    | 251 | 00FB | `&ucirc;`  | LATIN SMALL LETTER U WITH CIRCUMFLEX       |
| ü    | 252 | 00FC | `&uuml;`   | LATIN SMALL LETTER U WITH DIAERESIS        |
| ý    | 253 | 00FD | `&yacute;` | LATIN SMALL LETTER Y WITH ACUTE            |
| þ    | 254 | 00FE | `&thorn;`  | LATIN SMALL LETTER THORN                   |
| ÿ    | 255 | 00FF | `&yuml;`   | LATIN SMALL LETTER Y WITH DIAERESIS        |

### C1 Controls

這些控製字元最初是為了控制硬體設備而設計的。

控製字元不應顯示在 [[HTML Introduction|HTML]] 中。

但是，由於它們被定義為 Windows 使用的 ANSI 字元集中的字符，因此如果您使用的是 Windows，則可能會顯示它們。

Char | Dec | Hex | Control
--- | --- | --- | ---
€ | 128 | 0080 | CONTROL
 | 129 | 0081 | CONTROL
‚ | 130 | 0082 | BREAK PERMITTED HERE
ƒ | 131 | 0083 | NO BREAK HERE
„ | 132 | 0084 | INDEX
… | 133 | 0085 | NEXT LINE (NEL)
† | 134 | 0086 | START OF SELECTED AREA
‡ | 135 | 0087 | END OF SELECTED AREA
ˆ | 136 | 0088 | CHARACTER TABULATION SET
‰ | 137 | 0089 | CHARACTER TABULATION WITH JUSTIFICATION
Š | 138 | 008A | LINE TABULATION SET
‹ | 139 | 008B | PARTIAL LINE FORWARD
Œ | 140 | 008C | PARTIAL LINE BACKWARD
 | 141 | 008D | REVERSE LINE FEED
Ž | 142 | 008E | SINGLE SHIFT TWO
 | 143 | 008F | SINGLE SHIFT THREE
 | 144 | 0090 | DEVICE CONTROL STRING
‘ | 145 | 0091 | PRIVATE USE ONE
’ | 146 | 0092 | PRIVATE USE TWO
“ | 147 | 0093 | SET TRANSMIT STATE
” | 148 | 0094 | CANCEL CHARACTER
• | 149 | 0095 | MESSAGE WAITING
– | 150 | 0096 | START OF GUARDED AREA
— | 151 | 0097 | END OF GUARDED AREA
˜ | 152 | 0098 | START OF STRING
™ | 153 | 0099 | CONTROL
š | 154 | 009A | SINGLE CHARACTER INTRODUCER
› | 155 | 009B | CONTROL SEQUENCE INTRODUCER
œ | 156 | 009C | STRING TERMINATOR
 | 157 | 009D | OPERATING SYSTEM COMMAND
ž | 158 | 009E | PRIVACY MESSAGE
Ÿ | 159 | 009F | APPLICATION PROGRAM COMMAND

## Latin Extended-A

Hex 0100-017F / Decimal 256-383.

Char | Dec | Hex | Entity | Name
--- | --- | --- | --- | ---
Ā | 256 | 0100 | `&Amacr;` | LATIN CAPITAL LETTER A WITH MACRON
ā | 257 | 0101 | `&amacr;` | LATIN SMALL LETTER A WITH MACRON
Ă | 258 | 0102 | `&Abreve;` | LATIN CAPITAL LETTER A WITH BREVE
ă | 259 | 0103 | `&abreve;` | LATIN SMALL LETTER A WITH BREVE
Ą | 260 | 0104 | `&Aogon;` | LATIN CAPITAL LETTER A WITH OGONEK
ą | 261 | 0105 | `&aogon;` | LATIN SMALL LETTER A WITH OGONEK
Ć | 262 | 0106 | `&Cacute;` | LATIN CAPITAL LETTER C WITH ACUTE
ć | 263 | 0107 | `&cacute;` | LATIN SMALL LETTER C WITH ACUTE
Ĉ | 264 | 0108 | `&Ccirc;` | LATIN CAPITAL LETTER C WITH CIRCUMFLEX
ĉ | 265 | 0109 | `&ccirc;` | LATIN SMALL LETTER C WITH CIRCUMFLEX
Ċ | 266 | 010A | `&Cdot;` | LATIN CAPITAL LETTER C WITH DOT ABOVE
ċ | 267 | 010B | `&cdot;` | LATIN SMALL LETTER C WITH DOT ABOVE
Č | 268 | 010C | `&Ccaron;` | LATIN CAPITAL LETTER C WITH CARON
č | 269 | 010D | `&ccaron;` | LATIN SMALL LETTER C WITH CARON
Ď | 270 | 010E | `&Dcaron;` | LATIN CAPITAL LETTER D WITH CARON
ď | 271 | 010F | `&dcaron;` | LATIN SMALL LETTER D WITH CARON
Đ | 272 | 0110 | `&Dstrok;` | LATIN CAPITAL LETTER D WITH STROKE
đ | 273 | 0111 | `&dstrok;` | LATIN SMALL LETTER D WITH STROKE
Ē | 274 | 0112 | `&Emacr;` | LATIN CAPITAL LETTER E WITH MACRON
ē | 275 | 0113 | `&emacr;` | LATIN SMALL LETTER E WITH MACRON
Ĕ | 276 | 0114 |   | LATIN CAPITAL LETTER E WITH BREVE
ĕ | 277 | 0115 |   | LATIN SMALL LETTER E WITH BREVE
Ė | 278 | 0116 | `&Edot;` | LATIN CAPITAL LETTER E WITH DOT ABOVE
ė | 279 | 0117 | `&edot;` | LATIN SMALL LETTER E WITH DOT ABOVE
Ę | 280 | 0118 | `&Eogon;` | LATIN CAPITAL LETTER E WITH OGONEK
ę | 281 | 0119 | `&eogon;` | LATIN SMALL LETTER E WITH OGONEK
Ě | 282 | 011A | `&Ecaron;` | LATIN CAPITAL LETTER E WITH CARON
ě | 283 | 011B | `&ecaron;` | LATIN SMALL LETTER E WITH CARON
Ĝ | 284 | 011C | `&Gcirc;` | LATIN CAPITAL LETTER G WITH CIRCUMFLEX
ĝ | 285 | 011D | `&gcirc;` | LATIN SMALL LETTER G WITH CIRCUMFLEX
Ğ | 286 | 011E | `&Gbreve;` | LATIN CAPITAL LETTER G WITH BREVE
ğ | 287 | 011F | `&gbreve;` | LATIN SMALL LETTER G WITH BREVE
Ġ | 288 | 0120 | `&Gdot;` | LATIN CAPITAL LETTER G WITH DOT ABOVE
ġ | 289 | 0121 | `&gdot;` | LATIN SMALL LETTER G WITH DOT ABOVE
Ģ | 290 | 0122 | `&Gcedil;` | LATIN CAPITAL LETTER G WITH CEDILLA
ģ | 291 | 0123 | `&gcedil;` | LATIN SMALL LETTER G WITH CEDILLA
Ĥ | 292 | 0124 | `&Hcirc;` | LATIN CAPITAL LETTER H WITH CIRCUMFLEX
ĥ | 293 | 0125 | `&hcirc;` | LATIN SMALL LETTER H WITH CIRCUMFLEX
Ħ | 294 | 0126 | `&Hstrok;` | LATIN CAPITAL LETTER H WITH STROKE
ħ | 295 | 0127 | `&hstrok;` | LATIN SMALL LETTER H WITH STROKE
Ĩ | 296 | 0128 | `&Itilde;` | LATIN CAPITAL LETTER I WITH TILDE
ĩ | 297 | 0129 | `&itilde;` | LATIN SMALL LETTER I WITH TILDE
Ī | 298 | 012A | `&Imacr;` | LATIN CAPITAL LETTER I WITH MACRON
ī | 299 | 012B | `&imacr;` | LATIN SMALL LETTER I WITH MACRON
Ĭ | 300 | 012C |   | LATIN CAPITAL LETTER I WITH BREVE
ĭ | 301 | 012D |   | LATIN SMALL LETTER I WITH BREVE
Į | 302 | 012E | `&Iogon;` | LATIN CAPITAL LETTER I WITH OGONEK
į | 303 | 012F | `&iogon;` | LATIN SMALL LETTER I WITH OGONEK
İ | 304 | 0130 | `&Idot;` | LATIN CAPITAL LETTER I WITH DOT ABOVE
ı | 305 | 0131 | `&inodot;` | LATIN SMALL LETTER DOTLESS I
Ĳ | 306 | 0132 | `&IJlog;` | LATIN CAPITAL LIGATURE IJ
ĳ | 307 | 0133 | `&ijlig;` | LATIN SMALL LIGATURE IJ
Ĵ | 308 | 0134 | `&Jcirc;` | LATIN CAPITAL LETTER J WITH CIRCUMFLEX
ĵ | 309 | 0135 | `&jcirc;` | LATIN SMALL LETTER J WITH CIRCUMFLEX
Ķ | 310 | 0136 | `&Kcedil;` | LATIN CAPITAL LETTER K WITH CEDILLA
ķ | 311 | 0137 | `&kcedli;` | LATIN SMALL LETTER K WITH CEDILLA
ĸ | 312 | 0138 | `&kgreen;` | LATIN SMALL LETTER KRA
Ĺ | 313 | 0139 | `&Lacute;` | LATIN CAPITAL LETTER L WITH ACUTE
ĺ | 314 | 013A | `&lacute;` | LATIN SMALL LETTER L WITH ACUTE
Ļ | 315 | 013B | `&Lcedil;` | LATIN CAPITAL LETTER L WITH CEDILLA
ļ | 316 | 013C | `&lcedil;` | LATIN SMALL LETTER L WITH CEDILLA
Ľ | 317 | 013D | `&Lcaron;` | LATIN CAPITAL LETTER L WITH CARON
ľ | 318 | 013E | `&lcaron;` | LATIN SMALL LETTER L WITH CARON
Ŀ | 319 | 013F | `&Lmodot;` | LATIN CAPITAL LETTER L WITH MIDDLE DOT
ŀ | 320 | 0140 | `&lmidot;` | LATIN SMALL LETTER L WITH MIDDLE DOT
Ł | 321 | 0141 | `&Lstrok;` | LATIN CAPITAL LETTER L WITH STROKE
ł | 322 | 0142 | `&lstrok;` | LATIN SMALL LETTER L WITH STROKE
Ń | 323 | 0143 | `&Nacute;` | LATIN CAPITAL LETTER N WITH ACUTE
ń | 324 | 0144 | `&nacute;` | LATIN SMALL LETTER N WITH ACUTE
Ņ | 325 | 0145 | `&Ncedil;` | LATIN CAPITAL LETTER N WITH CEDILLA
ņ | 326 | 0146 | `&ncedil;` | LATIN SMALL LETTER N WITH CEDILLA
Ň | 327 | 0147 | `&Ncaron;` | LATIN CAPITAL LETTER N WITH CARON
ň | 328 | 0148 | `&ncaron;` | LATIN SMALL LETTER N WITH CARON
ŉ | 329 | 0149 | `&napos;` | LATIN SMALL LETTER N PRECEDED BY APOSTROPHE
Ŋ | 330 | 014A | `&ENG;` | LATIN CAPITAL LETTER ENG
ŋ | 331 | 014B | `&eng;` | LATIN SMALL LETTER ENG
Ō | 332 | 014C | `&Omacr;` | LATIN CAPITAL LETTER O WITH MACRON
ō | 333 | 014D | `&omacr;` | LATIN SMALL LETTER O WITH MACRON
Ŏ | 334 | 014E |   | LATIN CAPITAL LETTER O WITH BREVE
ŏ | 335 | 014F |   | LATIN SMALL LETTER O WITH BREVE
Ő | 336 | 0150 | `&Odblac;` | LATIN CAPITAL LETTER O WITH DOUBLE ACUTE
ő | 337 | 0151 | `&odblac;` | LATIN SMALL LETTER O WITH DOUBLE ACUTE
Œ | 338 | 0152 | `&OElig;` | LATIN CAPITAL LIGATURE OE
œ | 339 | 0153 | `&oelig;` | LATIN SMALL LIGATURE OE
Ŕ | 340 | 0154 | `&Racute;` | LATIN CAPITAL LETTER R WITH ACUTE
ŕ | 341 | 0155 | `&racute;` | LATIN SMALL LETTER R WITH ACUTE
Ŗ | 342 | 0156 | `&Rcedil;` | LATIN CAPITAL LETTER R WITH CEDILLA
ŗ | 343 | 0157 | `&rcedil;` | LATIN SMALL LETTER R WITH CEDILLA
Ř | 344 | 0158 | `&Rcaron;` | LATIN CAPITAL LETTER R WITH CARON
ř | 345 | 0159 | `&rcaron;` | LATIN SMALL LETTER R WITH CARON
Ś | 346 | 015A | `&Sacute;` | LATIN CAPITAL LETTER S WITH ACUTE
ś | 347 | 015B | `&sacute;` | LATIN SMALL LETTER S WITH ACUTE
Ŝ | 348 | 015C | `&Scirc;` | LATIN CAPITAL LETTER S WITH CIRCUMFLEX
ŝ | 349 | 015D | `&scirc;` | LATIN SMALL LETTER S WITH CIRCUMFLEX
Ş | 350 | 015E | `&Scedil;` | LATIN CAPITAL LETTER S WITH CEDILLA
ş | 351 | 015F | `&scedil;` | LATIN SMALL LETTER S WITH CEDILLA
Š | 352 | 0160 | `&Scaron;` | LATIN CAPITAL LETTER S WITH CARON
š | 353 | 0161 | `&scaron;` | LATIN SMALL LETTER S WITH CARON
Ţ | 354 | 0162 | `&Tcedil;` | LATIN CAPITAL LETTER T WITH CEDILLA
ţ | 355 | 0163 | `&tcedil;` | LATIN SMALL LETTER T WITH CEDILLA
Ť | 356 | 0164 | `&Tcaron;` | LATIN CAPITAL LETTER T WITH CARON
ť | 357 | 0165 | `&tcaron;` | LATIN SMALL LETTER T WITH CARON
Ŧ | 358 | 0166 | `&Tstrok;` | LATIN CAPITAL LETTER T WITH STROKE
ŧ | 359 | 0167 | `&tstrok;` | LATIN SMALL LETTER T WITH STROKE
Ũ | 360 | 0168 | `&Utilde;` | LATIN CAPITAL LETTER U WITH TILDE
ũ | 361 | 0169 | `&utilde;` | LATIN SMALL LETTER U WITH TILDE
Ū | 362 | 016A | `&Umacr;` | LATIN CAPITAL LETTER U WITH MACRON
ū | 363 | 016B | `&umacr;` | LATIN SMALL LETTER U WITH MACRON
Ŭ | 364 | 016C | `&Ubreve;` | LATIN CAPITAL LETTER U WITH BREVE
ŭ | 365 | 016D | `&ubreve;` | LATIN SMALL LETTER U WITH BREVE
Ů | 366 | 016E | `&Uring;` | LATIN CAPITAL LETTER U WITH RING ABOVE
ů | 367 | 016F | `&uring;` | LATIN SMALL LETTER U WITH RING ABOVE
Ű | 368 | 0170 | `&Udblac;` | LATIN CAPITAL LETTER U WITH DOUBLE ACUTE
ű | 369 | 0171 | `&udblac;` | LATIN SMALL LETTER U WITH DOUBLE ACUTE
Ų | 370 | 0172 | `&Uogon;` | LATIN CAPITAL LETTER U WITH OGONEK
ų | 371 | 0173 | `&uogon;` | LATIN SMALL LETTER U WITH OGONEK
Ŵ | 372 | 0174 | `&Wcirc;` | LATIN CAPITAL LETTER W WITH CIRCUMFLEX
ŵ | 373 | 0175 | `&wcirc;` | LATIN SMALL LETTER W WITH CIRCUMFLEX
Ŷ | 374 | 0176 | `&Ycirc;` | LATIN CAPITAL LETTER Y WITH CIRCUMFLEX
ŷ | 375 | 0177 | `&ycirc;` | LATIN SMALL LETTER Y WITH CIRCUMFLEX
Ÿ | 376 | 0178 | `&Yuml;` | LATIN CAPITAL LETTER Y WITH DIAERESIS
Ź | 377 | 0179 | `&Zacute;` | LATIN CAPITAL LETTER Z WITH ACUTE
ź | 378 | 017A | `&zacute;` | LATIN SMALL LETTER Z WITH ACUTE
Ż | 379 | 017B | `&Zdot;` | LATIN CAPITAL LETTER Z WITH DOT ABOVE
ż | 380 | 017C | `&zdot;` | LATIN SMALL LETTER Z WITH DOT ABOVE
Ž | 381 | 017D | `&Zcaron;` | LATIN CAPITAL LETTER Z WITH CARON
ž | 382 | 017E | `&zcaron;` | LATIN SMALL LETTER Z WITH CARON
ſ | 383 | 017F |   | LATIN SMALL LETTER LONG S

## Latin Extended-B

Hex 0180-024F / Decimal 384-591.

| Char | Dec | Hex  | Entity     | Name                                                  |
| ---- | --- | ---- | ---------- | ----------------------------------------------------- |
| ƀ    | 384 | 0180 |            | LATIN SMALL LETTER B WITH STROKE                      |
| Ɓ    | 385 | 0181 |            | LATIN CAPITAL LETTER B WITH HOOK                      |
| Ƃ    | 386 | 0182 |            | LATIN CAPITAL LETTER B WITH TOPBAR                    |
| ƃ    | 387 | 0183 |            | LATIN SMALL LETTER B WITH TOPBAR                      |
| Ƅ    | 388 | 0184 |            | LATIN CAPITAL LETTER TONE SIX                         |
| ƅ    | 389 | 0185 |            | LATIN SMALL LETTER TONE SIX                           |
| Ɔ    | 390 | 0186 |            | LATIN CAPITAL LETTER OPEN O                           |
| Ƈ    | 391 | 0187 |            | LATIN CAPITAL LETTER C WITH HOOK                      |
| ƈ    | 392 | 0188 |            | LATIN SMALL LETTER C WITH HOOK                        |
| Ɖ    | 393 | 0189 |            | LATIN CAPITAL LETTER AFRICAN D                        |
| Ɗ    | 394 | 018A |            | LATIN CAPITAL LETTER D WITH HOOK                      |
| Ƌ    | 395 | 018B |            | LATIN CAPITAL LETTER D WITH TOPBAR                    |
| ƌ    | 396 | 018C |            | LATIN SMALL LETTER D WITH TOPBAR                      |
| ƍ    | 397 | 018D |            | LATIN SMALL LETTER TURNED DELTA                       |
| Ǝ    | 398 | 018E |            | LATIN CAPITAL LETTER REVERSED E                       |
| Ə    | 399 | 018F |            | LATIN CAPITAL LETTER SCHWA                            |
| Ɛ    | 400 | 0190 |            | LATIN CAPITAL LETTER OPEN E                           |
| Ƒ    | 401 | 0191 |            | LATIN CAPITAL LETTER F WITH HOOK                      |
| ƒ    | 402 | 0192 | `&fnof;`   | LATIN SMALL LETTER F WITH HOOK                        |
| Ɠ    | 403 | 0193 |            | LATIN CAPITAL LETTER G WITH HOOK                      |
| Ɣ    | 404 | 0194 |            | LATIN CAPITAL LETTER GAMMA                            |
| ƕ    | 405 | 0195 |            | LATIN SMALL LETTER HV                                 |
| Ɩ    | 406 | 0196 |            | LATIN CAPITAL LETTER IOTA                             |
| Ɨ    | 407 | 0197 |            | LATIN CAPITAL LETTER I WITH STROKE                    |
| Ƙ    | 408 | 0198 |            | LATIN CAPITAL LETTER K WITH HOOK                      |
| ƙ    | 409 | 0199 |            | LATIN SMALL LETTER K WITH HOOK                        |
| ƚ    | 410 | 019A |            | LATIN SMALL LETTER L WITH BAR                         |
| ƛ    | 411 | 019B |            | LATIN SMALL LETTER LAMBDA WITH STROKE                 |
| Ɯ    | 412 | 019C |            | LATIN CAPITAL LETTER TURNED M                         |
| Ɲ    | 413 | 019D |            | LATIN CAPITAL LETTER N WITH LEFT HOOK                 |
| ƞ    | 414 | 019E |            | LATIN SMALL LETTER N WITH LONG RIGHT LEG              |
| Ɵ    | 415 | 019F |            | LATIN CAPITAL LETTER O WITH MIDDLE TILDE              |
| Ơ    | 416 | 01A0 |            | LATIN CAPITAL LETTER O WITH HORN                      |
| ơ    | 417 | 01A1 |            | LATIN SMALL LETTER O WITH HORN                        |
| Ƣ    | 418 | 01A2 |            | LATIN CAPITAL LETTER OI                               |
| ƣ    | 419 | 01A3 |            | LATIN SMALL LETTER OI                                 |
| Ƥ    | 420 | 01A4 |            | LATIN CAPITAL LETTER P WITH HOOK                      |
| ƥ    | 421 | 01A5 |            | LATIN SMALL LETTER P WITH HOOK                        |
| Ʀ    | 422 | 01A6 |            | LATIN LETTER YR                                       |
| Ƨ    | 423 | 01A7 |            | LATIN CAPITAL LETTER TONE TWO                         |
| ƨ    | 424 | 01A8 |            | LATIN SMALL LETTER TONE TWO                           |
| Ʃ    | 425 | 01A9 |            | LATIN CAPITAL LETTER ESH                              |
| ƪ    | 426 | 01AA |            | LATIN LETTER REVERSED ESH LOOP                        |
| ƫ    | 427 | 01AB |            | LATIN SMALL LETTER T WITH PALATAL HOOK                |
| Ƭ    | 428 | 01AC |            | LATIN CAPITAL LETTER T WITH HOOK                      |
| ƭ    | 429 | 01AD |            | LATIN SMALL LETTER T WITH HOOK                        |
| Ʈ    | 430 | 01AE |            | LATIN CAPITAL LETTER T WITH RETROFLEX HOOK            |
| Ư    | 431 | 01AF |            | LATIN CAPITAL LETTER U WITH HORN                      |
| ư    | 432 | 01B0 |            | LATIN SMALL LETTER U WITH HORN                        |
| Ʊ    | 433 | 01B1 |            | LATIN CAPITAL LETTER UPSILON                          |
| Ʋ    | 434 | 01B2 |            | LATIN CAPITAL LETTER V WITH HOOK                      |
| Ƴ    | 435 | 01B3 |            | LATIN CAPITAL LETTER Y WITH HOOK                      |
| ƴ    | 436 | 01B4 |            | LATIN SMALL LETTER Y WITH HOOK                        |
| Ƶ    | 437 | 01B5 | `&imped;`  | LATIN CAPITAL LETTER Z WITH STROKE                    |
| ƶ    | 438 | 01B6 |            | LATIN SMALL LETTER Z WITH STROKE                      |
| Ʒ    | 439 | 01B7 |            | LATIN CAPITAL LETTER EZH                              |
| Ƹ    | 440 | 01B8 |            | LATIN CAPITAL LETTER EZH REVERSED                     |
| ƹ    | 441 | 01B9 |            | LATIN SMALL LETTER EZH REVERSED                       |
| ƺ    | 442 | 01BA |            | LATIN SMALL LETTER EZH WITH TAIL                      |
| ƻ    | 443 | 01BB |            | LATIN LETTER TWO WITH STROKE                          |
| Ƽ    | 444 | 01BC |            | LATIN CAPITAL LETTER TONE FIVE                        |
| ƽ    | 445 | 01BD |            | LATIN SMALL LETTER TONE FIVE                          |
| ƾ    | 446 | 01BE |            | LATIN LETTER INVERTED GLOTTAL STOP WITH STROKE        |
| ƿ    | 447 | 01BF |            | LATIN LETTER WYNN                                     |
| ǀ    | 448 | 01C0 |            | LATIN LETTER DENTAL CLICK                             |
| ǁ    | 449 | 01C1 |            | LATIN LETTER LATERAL CLICK                            |
| ǂ    | 450 | 01C2 |            | LATIN LETTER ALVEOLAR CLICK                           |
| ǃ    | 451 | 01C3 |            | LATIN LETTER RETROFLEX CLICK                          |
| Ǆ    | 452 | 01C4 |            | LATIN CAPITAL LETTER DZ WITH CARON                    |
| ǅ    | 453 | 01C5 |            | LATIN CAPITAL LETTER D WITH SMALL LETTER Z WITH CARON |
| ǆ    | 454 | 01C6 |            | LATIN SMALL LETTER DZ WITH CARON                      |
| Ǉ    | 455 | 01C7 |            | LATIN CAPITAL LETTER LJ                               |
| ǈ    | 456 | 01C8 |            | LATIN CAPITAL LETTER L WITH SMALL LETTER J            |
| ǉ    | 457 | 01C9 |            | LATIN SMALL LETTER LJ                                 |
| Ǌ    | 458 | 01CA |            | LATIN CAPITAL LETTER NJ                               |
| ǋ    | 459 | 01CB |            | LATIN CAPITAL LETTER N WITH SMALL LETTER J            |
| ǌ    | 460 | 01CC |            | LATIN SMALL LETTER NJ                                 |
| Ǎ    | 461 | 01CD |            | LATIN CAPITAL LETTER A WITH CARON                     |
| ǎ    | 462 | 01CE |            | LATIN SMALL LETTER A WITH CARON                       |
| Ǐ    | 463 | 01CF |            | LATIN CAPITAL LETTER I WITH CARON                     |
| ǐ    | 464 | 01D0 |            | LATIN SMALL LETTER I WITH CARON                       |
| Ǒ    | 465 | 01D1 |            | LATIN CAPITAL LETTER O WITH CARON                     |
| ǒ    | 466 | 01D2 |            | LATIN SMALL LETTER O WITH CARON                       |
| Ǔ    | 467 | 01D3 |            | LATIN CAPITAL LETTER U WITH CARON                     |
| ǔ    | 468 | 01D4 |            | LATIN SMALL LETTER U WITH CARON                       |
| Ǖ    | 469 | 01D5 |            | LATIN CAPITAL LETTER U WITH DIAERESIS AND MACRON      |
| ǖ    | 470 | 01D6 |            | LATIN SMALL LETTER U WITH DIAERESIS AND MACRON        |
| Ǘ    | 471 | 01D7 |            | LATIN CAPITAL LETTER U WITH DIAERESIS AND ACUTE       |
| ǘ    | 472 | 01D8 |            | LATIN SMALL LETTER U WITH DIAERESIS AND ACUTE         |
| Ǚ    | 473 | 01D9 |            | LATIN CAPITAL LETTER U WITH DIAERESIS AND CARON       |
| ǚ    | 474 | 01DA |            | LATIN SMALL LETTER U WITH DIAERESIS AND CARON         |
| Ǜ    | 475 | 01DB |            | LATIN CAPITAL LETTER U WITH DIAERESIS AND GRAVE       |
| ǜ    | 476 | 01DC |            | LATIN SMALL LETTER U WITH DIAERESIS AND GRAVE         |
| ǝ    | 477 | 01DD |            | LATIN SMALL LETTER TURNED E                           |
| Ǟ    | 478 | 01DE |            | LATIN CAPITAL LETTER A WITH DIAERESIS AND MACRON      |
| ǟ    | 479 | 01DF |            | LATIN SMALL LETTER A WITH DIAERESIS AND MACRON        |
| Ǡ    | 480 | 01E0 |            | LATIN CAPITAL LETTER A WITH DOT ABOVE AND MACRON      |
| ǡ    | 481 | 01E1 |            | LATIN SMALL LETTER A WITH DOT ABOVE AND MACRON        |
| Ǣ    | 482 | 01E2 |            | LATIN CAPITAL LETTER AE WITH MACRON                   |
| ǣ    | 483 | 01E3 |            | LATIN SMALL LETTER AE WITH MACRON                     |
| Ǥ    | 484 | 01E4 |            | LATIN CAPITAL LETTER G WITH STROKE                    |
| ǥ    | 485 | 01E5 |            | LATIN SMALL LETTER G WITH STROKE                      |
| Ǧ    | 486 | 01E6 |            | LATIN CAPITAL LETTER G WITH CARON                     |
| ǧ    | 487 | 01E7 |            | LATIN SMALL LETTER G WITH CARON                       |
| Ǩ    | 488 | 01E8 |            | LATIN CAPITAL LETTER K WITH CARON                     |
| ǩ    | 489 | 01E9 |            | LATIN SMALL LETTER K WITH CARON                       |
| Ǫ    | 490 | 01EA |            | LATIN CAPITAL LETTER O WITH OGONEK                    |
| ǫ    | 491 | 01EB |            | LATIN SMALL LETTER O WITH OGONEK                      |
| Ǭ    | 492 | 01EC |            | LATIN CAPITAL LETTER O WITH OGONEK AND MACRON         |
| ǭ    | 493 | 01ED |            | LATIN SMALL LETTER O WITH OGONEK AND MACRON           |
| Ǯ    | 494 | 01EE |            | LATIN CAPITAL LETTER EZH WITH CARON                   |
| ǯ    | 495 | 01EF |            | LATIN SMALL LETTER EZH WITH CARON                     |
| ǰ    | 496 | 01F0 |            | LATIN SMALL LETTER J WITH CARON                       |
| Ǳ    | 497 | 01F1 |            | LATIN CAPITAL LETTER DZ                               |
| ǲ    | 498 | 01F2 |            | LATIN CAPITAL LETTER D WITH SMALL LETTER Z            |
| ǳ    | 499 | 01F3 |            | LATIN SMALL LETTER DZ                                 |
| Ǵ    | 500 | 01F4 |            | LATIN CAPITAL LETTER G WITH ACUTE                     |
| ǵ    | 501 | 01F5 | `&gacute;` | LATIN SMALL LETTER G WITH ACUTE                       |
| Ƕ    | 502 | 01F6 |            | LATIN CAPITAL LETTER HWAIR                            |
| Ƿ    | 503 | 01F7 |            | LATIN CAPITAL LETTER WYNN                             |
| Ǹ    | 504 | 01F8 |            | LATIN CAPITAL LETTER N WITH GRAVE                     |
| ǹ    | 505 | 01F9 |            | LATIN SMALL LETTER N WITH GRAVE                       |
| Ǻ    | 506 | 01FA |            | LATIN CAPITAL LETTER A WITH RING ABOVE AND ACUTE      |
| ǻ    | 507 | 01FB |            | LATIN SMALL LETTER A WITH RING ABOVE AND ACUTE        |
| Ǽ    | 508 | 01FC |            | LATIN CAPITAL LETTER AE WITH ACUTE                    |
| ǽ    | 509 | 01FD |            | LATIN SMALL LETTER AE WITH ACUTE                      |
| Ǿ    | 510 | 01FE |            | LATIN CAPITAL LETTER O WITH STROKE AND ACUTE          |
| ǿ    | 511 | 01FF |            | LATIN SMALL LETTER O WITH STROKE AND ACUTE            |
| Ȁ    | 512 | 0200 |            | LATIN CAPITAL LETTER A WITH DOUBLE GRAVE              |
| ȁ    | 513 | 0201 |            | LATIN SMALL LETTER A WITH DOUBLE GRAVE                |
| Ȃ    | 514 | 0202 |            | LATIN CAPITAL LETTER A WITH INVERTED BREVE            |
| ȃ    | 515 | 0203 |            | LATIN SMALL LETTER A WITH INVERTED BREVE              |
| Ȅ    | 516 | 0204 |            | LATIN CAPITAL LETTER E WITH DOUBLE GRAVE              |
| ȅ    | 517 | 0205 |            | LATIN SMALL LETTER E WITH DOUBLE GRAVE                |
| Ȇ    | 518 | 0206 |            | LATIN CAPITAL LETTER E WITH INVERTED BREVE            |
| ȇ    | 519 | 0207 |            | LATIN SMALL LETTER E WITH INVERTED BREVE              |
| Ȉ    | 520 | 0208 |            | LATIN CAPITAL LETTER I WITH DOUBLE GRAVE              |
| ȉ    | 521 | 0209 |            | LATIN SMALL LETTER I WITH DOUBLE GRAVE                |
| Ȋ    | 522 | 020A |            | LATIN CAPITAL LETTER I WITH INVERTED BREVE            |
| ȋ    | 523 | 020B |            | LATIN SMALL LETTER I WITH INVERTED BREVE              |
| Ȍ    | 524 | 020C |            | LATIN CAPITAL LETTER O WITH DOUBLE GRAVE              |
| ȍ    | 525 | 020D |            | LATIN SMALL LETTER O WITH DOUBLE GRAVE                |
| Ȏ    | 526 | 020E |            | LATIN CAPITAL LETTER O WITH INVERTED BREVE            |
| ȏ    | 527 | 020F |            | LATIN SMALL LETTER O WITH INVERTED BREVE              |
| Ȑ    | 528 | 0210 |            | LATIN CAPITAL LETTER R WITH DOUBLE GRAVE              |
| ȑ    | 529 | 0211 |            | LATIN SMALL LETTER R WITH DOUBLE GRAVE                |
| Ȓ    | 530 | 0212 |            | LATIN CAPITAL LETTER R WITH INVERTED BREVE            |
| ȓ    | 531 | 0213 |            | LATIN SMALL LETTER R WITH INVERTED BREVE              |
| Ȕ    | 532 | 0214 |            | LATIN CAPITAL LETTER U WITH DOUBLE GRAVE              |
| ȕ    | 533 | 0215 |            | LATIN SMALL LETTER U WITH DOUBLE GRAVE                |
| Ȗ    | 534 | 0216 |            | LATIN CAPITAL LETTER U WITH INVERTED BREVE            |
| ȗ    | 535 | 0217 |            | LATIN SMALL LETTER U WITH INVERTED BREVE              |
| Ș    | 536 | 0218 |            | LATIN CAPITAL LETTER S WITH COMMA BELOW               |
| ș    | 537 | 0219 |            | LATIN SMALL LETTER S WITH COMMA BELOW                 |
| Ț    | 538 | 021A |            | LATIN CAPITAL LETTER T WITH COMMA BELOW               |
| ț    | 539 | 021B |            | LATIN SMALL LETTER T WITH COMMA BELOW                 |
| Ȝ    | 540 | 021C |            | LATIN CAPITAL LETTER YOGH                             |
| ȝ    | 541 | 021D |            | LATIN SMALL LETTER YOGH                               |
| Ȟ    | 542 | 021E |            | LATIN CAPITAL LETTER H WITH CARON                     |
| ȟ    | 543 | 021F |            | LATIN SMALL LETTER H WITH CARON                       |
| Ƞ    | 544 | 0220 |            | LATIN CAPITAL LETTER N WITH LONG RIGHT LEG            |
| ȡ    | 545 | 0221 |            | LATIN SMALL LETTER D WITH CURL                        |
| Ȣ    | 546 | 0222 |            | LATIN CAPITAL LETTER OU                               |
| ȣ    | 547 | 0223 |            | LATIN SMALL LETTER OU                                 |
| Ȥ    | 548 | 0224 |            | LATIN CAPITAL LETTER Z WITH HOOK                      |
| ȥ    | 549 | 0225 |            | LATIN SMALL LETTER Z WITH HOOK                        |
| Ȧ    | 550 | 0226 |            | LATIN CAPITAL LETTER A WITH DOT ABOVE                 |
| ȧ    | 551 | 0227 |            | LATIN SMALL LETTER A WITH DOT ABOVE                   |
| Ȩ    | 552 | 0228 |            | LATIN CAPITAL LETTER E WITH CEDILLA                   |
| ȩ    | 553 | 0229 |            | LATIN SMALL LETTER E WITH CEDILLA                     |
| Ȫ    | 554 | 022A |            | LATIN CAPITAL LETTER O WITH DIAERESIS AND MACRON      |
| ȫ    | 555 | 022B |            | LATIN SMALL LETTER O WITH DIAERESIS AND MACRON        |
| Ȭ    | 556 | 022C |            | LATIN CAPITAL LETTER O WITH TILDE AND MACRON          |
| ȭ    | 557 | 022D |            | LATIN SMALL LETTER O WITH TILDE AND MACRON            |
| Ȯ    | 558 | 022E |            | LATIN CAPITAL LETTER O WITH DOT ABOVE                 |
| ȯ    | 559 | 022F |            | LATIN SMALL LETTER O WITH DOT ABOVE                   |
| Ȱ    | 560 | 0230 |            | LATIN CAPITAL LETTER O WITH DOT ABOVE AND MACRON      |
| ȱ    | 561 | 0231 |            | LATIN SMALL LETTER O WITH DOT ABOVE AND MACRON        |
| Ȳ    | 562 | 0232 |            | LATIN CAPITAL LETTER Y WITH MACRON                    |
| ȳ    | 563 | 0233 |            | LATIN SMALL LETTER Y WITH MACRON                      |
| ȴ    | 564 | 0234 |            | LATIN SMALL LETTER L WITH CURL                        |
| ȵ    | 565 | 0235 |            | LATIN SMALL LETTER N WITH CURL                        |
| ȶ    | 566 | 0236 |            | LATIN SMALL LETTER T WITH CURL                        |
| ȷ    | 567 | 0237 | `&jmath;`  | LATIN SMALL LETTER DOTLESS J                          |
| ȸ    | 568 | 0238 |            | LATIN SMALL LETTER DB DIGRAPH                         |
| ȹ    | 569 | 0239 |            | LATIN SMALL LETTER QP DIGRAPH                         |
| Ⱥ    | 570 | 023A |            | LATIN CAPITAL LETTER A WITH STROKE                    |
| Ȼ    | 571 | 023B |            | LATIN CAPITAL LETTER C WITH STROKE                    |
| ȼ    | 572 | 023C |            | LATIN SMALL LETTER C WITH STROKE                      |
| Ƚ    | 573 | 023D |            | LATIN CAPITAL LETTER L WITH BAR                       |
| Ⱦ    | 574 | 023E |            | LATIN CAPITAL LETTER T WITH DIAGONAL STROKE           |
| ȿ    | 575 | 023F |            | LATIN SMALL LETTER S WITH SWASH TAIL                  |
| ɀ    | 576 | 0240 |            | LATIN SMALL LETTER Z WITH SWASH TAIL                  |
| Ɂ    | 577 | 0241 |            | LATIN CAPITAL LETTER GLOTTAL STOP                     |
| ɂ    | 578 | 0242 |            | LATIN SMALL LETTER GLOTTAL STOP                       |
| Ƀ    | 579 | 0243 |            | LATIN CAPITAL LETTER B WITH STROKE                    |
| Ʉ    | 580 | 0244 |            | LATIN CAPITAL LETTER U BAR                            |
| Ʌ    | 581 | 0245 |            | LATIN CAPITAL LETTER TURNED V                         |
| Ɇ    | 582 | 0246 |            | LATIN CAPITAL LETTER E WITH STROKE                    |
| ɇ    | 583 | 0247 |            | LATIN SMALL LETTER E WITH STROKE                      |
| Ɉ    | 584 | 0248 |            | LATIN CAPITAL LETTER J WITH STROKE                    |
| ɉ    | 585 | 0249 |            | LATIN SMALL LETTER J WITH STROKE                      |
| Ɋ    | 586 | 024A |            | LATIN CAPITAL LETTER SMALL Q WITH HOOK TAIL           |
| ɋ    | 587 | 024B |            | LATIN SMALL LETTER Q WITH HOOK TAIL                   |
| Ɍ    | 588 | 024C |            | LATIN CAPITAL LETTER R WITH STROKE                    |
| ɍ    | 589 | 024D |            | LATIN SMALL LETTER R WITH STROKE                      |
| Ɏ    | 590 | 024E |            | LATIN CAPITAL LETTER Y WITH STROKE                    |
| ɏ    | 591 | 024F |            | LATIN SMALL LETTER Y WITH STROKE                      |

## Latin IPA

Hex 0250-02AD / Dec 592-685.

Char | Dec | Hex | Name
--- | --- | --- | ---
ɐ | 592 | 0250 | LATIN SMALL LETTER TURNED A
ɑ | 593 | 0251 | LATIN SMALL LETTER ALPHA
ɒ | 594 | 0252 | LATIN SMALL LETTER TURNED ALPHA
ɓ | 595 | 0253 | LATIN SMALL LETTER B WITH HOOK
ɔ | 596 | 0254 | LATIN SMALL LETTER OPEN O
ɕ | 597 | 0255 | LATIN SMALL LETTER C WITH CURL
ɖ | 598 | 0256 | LATIN SMALL LETTER D WITH TAIL
ɗ | 599 | 0257 | LATIN SMALL LETTER D WITH HOOK
ɘ | 600 | 0258 | LATIN SMALL LETTER REVERSED E
ə | 601 | 0259 | LATIN SMALL LETTER SCHWA
ɚ | 602 | 025A | LATIN SMALL LETTER SCHWA WITH HOOK
ɛ | 603 | 025B | LATIN SMALL LETTER OPEN E
ɜ | 604 | 025C | LATIN SMALL LETTER REVERSED OPEN E
ɝ | 605 | 025D | LATIN SMALL LETTER REVERSED OPEN E WITH HOOK
ɞ | 606 | 025E | LATIN SMALL LETTER CLOSED REVERSED OPEN E
ɟ | 607 | 025F | LATIN SMALL LETTER DOTLESS J WITH STROKE
ɠ | 608 | 0260 | LATIN SMALL LETTER G WITH HOOK
ɡ | 609 | 0261 | LATIN SMALL LETTER SCRIPT G
ɢ | 610 | 0262 | LATIN LETTER SMALL CAPITAL G
ɣ | 611 | 0263 | LATIN SMALL LETTER GAMMA
ɤ | 612 | 0264 | LATIN SMALL LETTER RAMS HORN
ɥ | 613 | 0265 | LATIN SMALL LETTER TURNED H
ɦ | 614 | 0266 | LATIN SMALL LETTER H WITH HOOK
ɧ | 615 | 0267 | LATIN SMALL LETTER HENG WITH HOOK
ɨ | 616 | 0268 | LATIN SMALL LETTER I WITH STROKE
ɩ | 617 | 0269 | LATIN SMALL LETTER IOTA
ɪ | 618 | 026A | LATIN LETTER SMALL CAPITAL I
ɫ | 619 | 026B | LATIN SMALL LETTER L WITH MIDDLE TILDE
ɬ | 620 | 026C | LATIN SMALL LETTER L WITH BELT
ɭ | 621 | 026D | LATIN SMALL LETTER L WITH RETROFLEX HOOK
ɮ | 622 | 026E | LATIN SMALL LETTER LEZH
ɯ | 623 | 026F | LATIN SMALL LETTER TURNED M
ɰ | 624 | 0270 | LATIN SMALL LETTER TURNED M WITH LONG LEG
ɱ | 625 | 0271 | LATIN SMALL LETTER M WITH HOOK
ɲ | 626 | 0272 | LATIN SMALL LETTER N WITH LEFT HOOK
ɳ | 627 | 0273 | LATIN SMALL LETTER N WITH RETROFLEX HOOK
ɴ | 628 | 0274 | LATIN LETTER SMALL CAPITAL N
ɵ | 629 | 0275 | LATIN SMALL LETTER BARRED O
ɶ | 630 | 0276 | LATIN LETTER SMALL CAPITAL OE
ɷ | 631 | 0277 | LATIN SMALL LETTER CLOSED OMEGA
ɸ | 632 | 0278 | LATIN SMALL LETTER PHI
ɹ | 633 | 0279 | LATIN SMALL LETTER TURNED R
ɺ | 634 | 027A | LATIN SMALL LETTER TURNED R WITH LONG LEG
ɻ | 635 | 027B | LATIN SMALL LETTER TURNED R WITH HOOK
ɼ | 636 | 027C | LATIN SMALL LETTER R WITH LONG LEG
ɽ | 637 | 027D | LATIN SMALL LETTER R WITH TAIL
ɾ | 638 | 027E | LATIN SMALL LETTER R WITH FISHHOOK
ɿ | 639 | 027F | LATIN SMALL LETTER REVERSED R WITH FISHHOOK
ʀ | 640 | 0280 | LATIN LETTER SMALL CAPITAL R
ʁ | 641 | 0281 | LATIN LETTER SMALL CAPITAL INVERTED R
ʂ | 642 | 0282 | LATIN SMALL LETTER S WITH HOOK
ʃ | 643 | 0283 | LATIN SMALL LETTER ESH
ʄ | 644 | 0284 | LATIN SMALL LETTER DOTLESS J WITH STROKE AND HOOK
ʅ | 645 | 0285 | LATIN SMALL LETTER SQUAT REVERSED ESH
ʆ | 646 | 0286 | LATIN SMALL LETTER ESH WITH CURL
ʇ | 647 | 0287 | LATIN SMALL LETTER TURNED T
ʈ | 648 | 0288 | LATIN SMALL LETTER T WITH RETROFLEX HOOK
ʉ | 649 | 0289 | LATIN SMALL LETTER U BAR
ʊ | 650 | 028A | LATIN SMALL LETTER UPSILON
ʋ | 651 | 028B | LATIN SMALL LETTER V WITH HOOK
ʌ | 652 | 028C | LATIN SMALL LETTER TURNED V
ʍ | 653 | 028D | LATIN SMALL LETTER TURNED W
ʎ | 654 | 028E | LATIN SMALL LETTER TURNED Y
ʏ | 655 | 028F | LATIN LETTER SMALL CAPITAL Y
ʐ | 656 | 0290 | LATIN SMALL LETTER Z WITH RETROFLEX HOOK
ʑ | 657 | 0291 | LATIN SMALL LETTER Z WITH CURL
ʒ | 658 | 0292 | LATIN SMALL LETTER EZH
ʓ | 659 | 0293 | LATIN SMALL LETTER EZH WITH CURL
ʔ | 660 | 0294 | LATIN LETTER GLOTTAL STOP
ʕ | 661 | 0295 | LATIN LETTER PHARYNGEAL VOICED FRICATIVE
ʖ | 662 | 0296 | LATIN LETTER INVERTED GLOTTAL STOP
ʗ | 663 | 0297 | LATIN LETTER STRETCHED C
ʘ | 664 | 0298 | LATIN LETTER BILABIAL CLICK
ʙ | 665 | 0299 | LATIN LETTER SMALL CAPITAL B
ʚ | 666 | 029A | LATIN SMALL LETTER CLOSED OPEN E
ʛ | 667 | 029B | LATIN LETTER SMALL CAPITAL G WITH HOOK
ʜ | 668 | 029C | LATIN LETTER SMALL CAPITAL H
ʝ | 669 | 029D | LATIN SMALL LETTER J WITH CROSSED-TAIL
ʞ | 670 | 029E | LATIN SMALL LETTER TURNED K
ʟ | 671 | 029F | LATIN LETTER SMALL CAPITAL L
ʠ | 672 | 02A0 | LATIN SMALL LETTER Q WITH HOOK
ʡ | 673 | 02A1 | LATIN LETTER GLOTTAL STOP WITH STROKE
ʢ | 674 | 02A2 | LATIN LETTER REVERSED GLOTTAL STOP WITH STROKE
ʣ | 675 | 02A3 | LATIN SMALL LETTER DZ DIGRAPH
ʤ | 676 | 02A4 | LATIN SMALL LETTER DEZH DIGRAPH
ʥ | 677 | 02A5 | LATIN SMALL LETTER DZ DIGRAPH WITH CURL
ʦ | 678 | 02A6 | LATIN SMALL LETTER TS DIGRAPH
ʧ | 679 | 02A7 | LATIN SMALL LETTER TESH DIGRAPH
ʨ | 680 | 02A8 | LATIN SMALL LETTER TC DIGRAPH WITH CURL
ʩ | 681 | 02A9 | LATIN SMALL LETTER FENG DIGRAPH
ʪ | 682 | 02AA | LATIN SMALL LETTER LS DIGRAPH
ʫ | 683 | 02AB | LATIN SMALL LETTER LZ DIGRAPH
ʬ | 684 | 02AC | LATIN LETTER BILABIAL PERCUSSIVE
ʭ | 685 | 02AD | LATIN LETTER BIDENTAL PERCUSSIVE

## Spacing Modifiers

Hex 02B0-02FF / Decimal 688-767.

Char | Dec | Hex | Entity | Name
--- | --- | --- | --- | ---
ʰ | 688 | 02B0 |   | MODIFIER LETTER SMALL H
ʱ | 689 | 02B1 |   | MODIFIER LETTER SMALL H WITH HOOK
ʲ | 690 | 02B2 |   | MODIFIER LETTER SMALL J
ʳ | 691 | 02B3 |   | MODIFIER LETTER SMALL R
ʴ | 692 | 02B4 |   | MODIFIER LETTER SMALL TURNED R
ʵ | 693 | 02B5 |   | MODIFIER LETTER SMALL TURNED R WITH HOOK
ʶ | 694 | 02B6 |   | MODIFIER LETTER SMALL CAPITAL INVERTED R
ʷ | 695 | 02B7 |   | MODIFIER LETTER SMALL W
ʸ | 696 | 02B8 |   | MODIFIER LETTER SMALL Y
ʹ | 697 | 02B9 |   | MODIFIER LETTER PRIME
ʺ | 698 | 02BA |   | MODIFIER LETTER DOUBLE PRIME
ʻ | 699 | 02BB |   | MODIFIER LETTER TURNED COMMA
ʼ | 700 | 02BC |   | MODIFIER LETTER APOSTROPHE
ʽ | 701 | 02BD |   | MODIFIER LETTER REVERSED COMMA
ʾ | 702 | 02BE |   | MODIFIER LETTER RIGHT HALF RING
ʿ | 703 | 02BF |   | MODIFIER LETTER LEFT HALF RING
ˀ | 704 | 02C0 |   | MODIFIER LETTER GLOTTAL STOP
ˁ | 705 | 02C1 |   | MODIFIER LETTER REVERSED GLOTTAL STOP
˂ | 706 | 02C2 |   | MODIFIER LETTER LEFT ARROWHEAD
˃ | 707 | 02C3 |   | MODIFIER LETTER RIGHT ARROWHEAD
˄ | 708 | 02C4 |   | MODIFIER LETTER UP ARROWHEAD
˅ | 709 | 02C5 |   | MODIFIER LETTER DOWN ARROWHEAD
ˆ | 710 | 02C6 | `&circ;` | MODIFIER LETTER CIRCUMFLEX ACCENT
ˇ | 711 | 02C7 |   | CARON
ˈ | 712 | 02C8 |   | MODIFIER LETTER VERTICAL LINE
ˉ | 713 | 02C9 |   | MODIFIER LETTER MACRON
ˊ | 714 | 02CA |   | MODIFIER LETTER ACUTE ACCENT
ˋ | 715 | 02CB |   | MODIFIER LETTER GRAVE ACCENT
ˌ | 716 | 02CC |   | MODIFIER LETTER LOW VERTICAL LINE
ˍ | 717 | 02CD |   | MODIFIER LETTER LOW MACRON
ˎ | 718 | 02CE |   | MODIFIER LETTER LOW GRAVE ACCENT
ˏ | 719 | 02CF |   | MODIFIER LETTER LOW ACUTE ACCENT
ː | 720 | 02D0 |   | MODIFIER LETTER TRIANGULAR COLON
ˑ | 721 | 02D1 |   | MODIFIER LETTER HALF TRIANGULAR COLON
˒ | 722 | 02D2 |   | MODIFIER LETTER CENTRED RIGHT HALF RING
˓ | 723 | 02D3 |   | MODIFIER LETTER CENTRED LEFT HALF RING
˔ | 724 | 02D4 |   | MODIFIER LETTER UP TACK
˕ | 725 | 02D5 |   | MODIFIER LETTER DOWN TACK
˖ | 726 | 02D6 |   | MODIFIER LETTER PLUS SIGN
˗ | 727 | 02D7 |   | MODIFIER LETTER MINUS SIGN
˘ | 728 | 02D8 |   | BREVE
˙ | 729 | 02D9 |   | DOT ABOVE
˚ | 730 | 02DA |   | RING ABOVE
˛ | 731 | 02DB |   | OGONEK
˜ | 732 | 02DC | &tilde; | SMALL TILDE
˝ | 733 | 02DD |   | DOUBLE ACUTE ACCENT
˞ | 734 | 02DE |   | MODIFIER LETTER RHOTIC HOOK
˟ | 735 | 02DF |   | MODIFIER LETTER CROSS ACCENT
ˠ | 736 | 02E0 |   | MODIFIER LETTER SMALL GAMMA
ˡ | 737 | 02E1 |   | MODIFIER LETTER SMALL L
ˢ | 738 | 02E2 |   | MODIFIER LETTER SMALL S
ˣ | 739 | 02E3 |   | MODIFIER LETTER SMALL X
ˤ | 740 | 02E4 |   | MODIFIER LETTER SMALL REVERSED GLOTTAL STOP
˥ | 741 | 02E5 |   | MODIFIER LETTER EXTRA-HIGH TONE BAR
˦ | 742 | 02E6 |   | MODIFIER LETTER HIGH TONE BAR
˧ | 743 | 02E7 |   | MODIFIER LETTER MID TONE BAR
˨ | 744 | 02E8 |   | MODIFIER LETTER LOW TONE BAR
˩ | 745 | 02E9 |   | MODIFIER LETTER EXTRA-LOW TONE BAR
˪ | 746 | 02EA |   | MODIFIER LETTER YIN DEPARTING TONE MARK
˫ | 747 | 02EB |   | MODIFIER LETTER YANG DEPARTING TONE MARK
ˬ | 748 | 02EC |   | MODIFIER LETTER VOICING
˭ | 749 | 02ED |   | MODIFIER LETTER UNASPIRATED
ˮ | 750 | 02EE |   | MODIFIER LETTER DOUBLE APOSTROPHE
˯ | 751 | 02EF |   | MODIFIER LETTER LOW DOWN ARROWHEAD
˰ | 752 | 02F0 |   | MODIFIER LETTER LOW UP ARROWHEAD
˱ | 753 | 02F1 |   | MODIFIER LETTER LOW LEFT ARROWHEAD
˲ | 754 | 02F2 |   | MODIFIER LETTER LOW RIGHT ARROWHEAD
˳ | 755 | 02F3 |   | MODIFIER LETTER LOW RING
˴ | 756 | 02F4 |   | MODIFIER LETTER MIDDLE GRAVE ACCENT
˵ | 757 | 02F5 |   | MODIFIER LETTER MIDDLE DOUBLE GRAVE ACCENT
˶ | 758 | 02F6 |   | MODIFIER LETTER MIDDLE DOUBLE ACUTE ACCENT
˷ | 759 | 02F7 |   | MODIFIER LETTER LOW TILDE
˸ | 760 | 02F8 |   | MODIFIER LETTER RAISED COLON
˹ | 761 | 02F9 |   | MODIFIER LETTER BEGIN HIGH TONE
˺ | 762 | 02FA |   | MODIFIER LETTER END HIGH TONE
˻ | 763 | 02FB |   | MODIFIER LETTER BEGIN LOW TONE
˼ | 764 | 02FC |   | MODIFIER LETTER END LOW TONE
˽ | 765 | 02FD |   | MODIFIER LETTER SHELF
˾ | 766 | 02FE |   | MODIFIER LETTER OPEN SHELF
˿ | 767 | 02FF |   | MODIFIER LETTER LOW LEFT ARROW

## Diacritical Marks

Hex 0300-036F / Decimal 768-879.

Char | Dec | Hex | Name
--- | --- | --- | ---
ò | 768 | 0300 | GRAVE ACCENT
ó | 769 | 0301 | ACUTE ACCENT
ô | 770 | 0302 | CIRCUMFLEX ACCENT
õ | 771 | 0303 | TILDE
ō | 772 | 0304 | MACRON
o̅ | 773 | 0305 | OVERLINE
ŏ | 774 | 0306 | BREVE
ȯ | 775 | 0307 | DOT ABOVE
ö | 776 | 0308 | DIAERESIS
ỏ | 777 | 0309 | HOOK ABOVE
o̊ | 778 | 030A | RING ABOVE
ő | 779 | 030B | DOUBLE ACUTE ACCENT
ǒ | 780 | 030C | CARON
o̍ | 781 | 030D | VERTICAL LINE ABOVE
o̎ | 782 | 030E | DOUBLE VERTICAL LINE ABOVE
ȍ | 783 | 030F | DOUBLE GRAVE ACCENT
o̐ | 784 | 0310 | CANDRABINDU
ȏ | 785 | 0311 | INVERTED BREVE
o̒ | 786 | 0312 | TURNED COMMA ABOVE
o̓ | 787 | 0313 | COMMA ABOVE
o̔ | 788 | 0314 | REVERSED COMMA ABOVE
o̕ | 789 | 0315 | COMMA ABOVE RIGHT
o̖ | 790 | 0316 | GRAVE ACCENT BELOW
o̗ | 791 | 0317 | ACUTE ACCENT BELOW
o̘ | 792 | 0318 | LEFT TACK BELOW
o̙ | 793 | 0319 | RIGHT TACK BELOW
o̚ | 794 | 031A | LEFT ANGLE ABOVE
ơ | 795 | 031B | HORN
o̜ | 796 | 031C | LEFT HALF RING BELOW
o̝ | 797 | 031D | UP TACK BELOW
o̞ | 798 | 031E | DOWN TACK BELOW
o̟ | 799 | 031F | PLUS SIGN BELOW
o̠ | 800 | 0320 | MINUS SIGN BELOW
o̡ | 801 | 0321 | PALATALIZED HOOK BELOW
o̢ | 802 | 0322 | RETROFLEX HOOK BELOW
ọ | 803 | 0323 | DOT BELOW
o̤ | 804 | 0324 | DIAERESIS BELOW
o̥ | 805 | 0325 | RING BELOW
o̦ | 806 | 0326 | COMMA BELOW
o̧ | 807 | 0327 | CEDILLA
ǫ | 808 | 0328 | OGONEK
o̩ | 809 | 0329 | VERTICAL LINE BELOW
o̪ | 810 | 032A | BRIDGE BELOW
o̫ | 811 | 032B | INVERTED DOUBLE ARCH BELOW
o̬ | 812 | 032C | CARON BELOW
o̭ | 813 | 032D | CIRCUMFLEX ACCENT BELOW
o̮ | 814 | 032E | BREVE BELOW
o̯ | 815 | 032F | INVERTED BREVE BELOW
o̰ | 816 | 0330 | TILDE BELOW
o̱ | 817 | 0331 | MACRON BELOW
o̲ | 818 | 0332 | LOW LINE
o̳ | 819 | 0333 | DOUBLE LOW LINE
o̴ | 820 | 0334 | TILDE OVERLAY
o̵ | 821 | 0335 | SHORT STROKE OVERLAY
o̶ | 822 | 0336 | LONG STROKE OVERLAY
o̷ | 823 | 0337 | SHORT SOLIDUS OVERLAY
o̸ | 824 | 0338 | LONG SOLIDUS OVERLAY
o̹ | 825 | 0339 | RIGHT HALF RING BELOW
o̺ | 826 | 033A | INVERTED BRIDGE BELOW
o̻ | 827 | 033B | SQUARE BELOW
o̼ | 828 | 033C | SEAGULL BELOW
o̽ | 829 | 033D | X ABOVE
o̾ | 830 | 033E | VERTICAL TILDE
o̿ | 831 | 033F | DOUBLE OVERLINE
ò | 832 | 0340 | GRAVE TONE MARK
ó | 833 | 0341 | ACUTE TONE MARK
o͂ | 834 | 0342 | GREEK PERISPOMENI (combined with theta)
o̓ | 835 | 0343 | GREEK KORONIS (combined with theta)
ö́ | 836 | 0344 | GREEK DIALYTIKA TONOS (combined with theta)
oͅ | 837 | 0345 | GREEK YPOGEGRAMMENI (combined with theta)
o͆ | 838 | 0346 | BRIDGE ABOVE
o͇ | 839 | 0347 | EQUALS SIGN BELOW
o͈ | 840 | 0348 | DOUBLE VERTICAL LINE BELOW
o͉ | 841 | 0349 | LEFT ANGLE BELOW
o͊ | 842 | 034A | NOT TILDE ABOVE
o͋ | 843 | 034B | HOMOTHETIC ABOVE
o͌ | 844 | 034C | ALMOST EQUAL TO ABOVE
o͍ | 845 | 034D | LEFT RIGHT ARROW BELOW
o͎ | 846 | 034E | UPWARDS ARROW BELOW
o͏ | 847 | 034F | GRAPHEME JOINER
o͐ | 848 | 0350 | RIGHT ARROWHEAD ABOVE
o͑ | 849 | 0351 | LEFT HALF RING ABOVE
o͒ | 850 | 0352 | FERMATA
o͓ | 851 | 0353 | X BELOW
o͔ | 852 | 0354 | LEFT ARROWHEAD BELOW
o͕ | 853 | 0355 | RIGHT ARROWHEAD BELOW
o͖ | 854 | 0356 | RIGHT ARROWHEAD AND UP ARROWHEAD BELOW
o͗ | 855 | 0357 | RIGHT HALF RING ABOVE
o͘ | 856 | 0358 | DOT ABOVE RIGHT
o͙ | 857 | 0359 | ASTERISK BELOW
o͚ | 858 | 035A | DOUBLE RING BELOW
o͛ | 859 | 035B | ZIGZAG ABOVE
͜o | 860 | 035C | DOUBLE BREVE BELOW
͝o | 861 | 035D | DOUBLE BREVE
͞o | 862 | 035E | DOUBLE MACRON
͟o | 863 | 035F | DOUBLE MACRON BELOW
͠o | 864 | 0360 | DOUBLE TILDE
͡o | 865 | 0361 | DOUBLE INVERTED BREVE
͢o | 866 | 0362 | DOUBLE RIGHTWARDS ARROW BELOW
oͣ | 867 | 0363 | LATIN SMALL LETTER A
oͤ | 868 | 0364 | LATIN SMALL LETTER E
oͥ | 869 | 0365 | LATIN SMALL LETTER I
oͦ | 870 | 0366 | LATIN SMALL LETTER O
oͧ | 871 | 0367 | LATIN SMALL LETTER U
oͨ | 872 | 0368 | LATIN SMALL LETTER C
oͩ | 873 | 0369 | LATIN SMALL LETTER D
oͪ | 874 | 036A | LATIN SMALL LETTER H
oͫ | 875 | 036B | LATIN SMALL LETTER M
oͬ | 876 | 036C | LATIN SMALL LETTER R
oͭ | 877 | 036D | LATIN SMALL LETTER T
oͮ | 878 | 036E | LATIN SMALL LETTER V
oͯ | 879 | 036F | LATIN SMALL LETTER X

## Greek and Coptic

Hex 0370-03FF / Decimal 880-1023.

Char | Dec | Hex | Entity | Name
--- | --- | --- | --- | ---
Ͱ | 880 | 0370 |   | CAPITAL LETTER HETA
ͱ | 881 | 0371 |   | SMALL LETTER HETA
Ͳ | 882 | 0372 |   | CAPITAL LETTER ARCHAIC SAMPI
ͳ | 883 | 0373 |   | SMALL LETTER ARCHAIC SAMPI
ʹ | 884 | 0374 |   | NUMERAL SIGN
͵ | 885 | 0375 |   | LOWER NUMERAL SIGN
Ͷ | 886 | 0376 |   | CAPITAL LETTER PAMPHYLIAN DIGAMMA
ͷ | 887 | 0377 |   | SMALL LETTER PAMPHYLIAN DIGAMMA
ͺ | 890 | 037A |   | YPOGEGRAMMENI
ͻ | 891 | 037B |   | SMALL REVERSED LUNATE SIGMA SYMBOL
ͼ | 892 | 037C |   | SMALL DOTTED LUNATE SIGMA SYMBOL
ͽ | 893 | 037D |   | SMALL REVERSED DOTTED LUNATE SIGMA SYMBOL
; | 894 | 037E |   | QUESTION MARK
΄ | 900 | 0384 |   | TONOS
΅ | 901 | 0385 |   | DIALYTIKA TONOS
Ά | 902 | 0386 |   | CAPITAL LETTER ALPHA WITH TONOS
· | 903 | 0387 |   | ANO TELEIA
Έ | 904 | 0388 |   | CAPITAL LETTER EPSILON WITH TONOS
Ή | 905 | 0389 |   | CAPITAL LETTER ETA WITH TONOS
Ί | 906 | 038A |   | CAPITAL LETTER IOTA WITH TONOS
Ό | 908 | 038C |   | CAPITAL LETTER OMICRON WITH TONOS
Ύ | 910 | 038E |   | CAPITAL LETTER UPSILON WITH TONOS
Ώ | 911 | 038F |   | CAPITAL LETTER OMEGA WITH TONOS
ΐ | 912 | 0390 |   | SMALL LETTER IOTA WITH DIALYTIKA AND TONOS
Α | 913 | 0391 | `&Alpha;` | CAPITAL LETTER ALPHA
Β | 914 | 0392 | `&Beta;` | CAPITAL LETTER BETA
Γ | 915 | 0393 | `&Gamma;` | CAPITAL LETTER GAMMA
Δ | 916 | 0394 | `&Delta;` | CAPITAL LETTER DELTA
Ε | 917 | 0395 | `&Epsilon;` | CAPITAL LETTER EPSILON
Ζ | 918 | 0396 | `&Zeta;` | CAPITAL LETTER ZETA
Η | 919 | 0397 | `&Eta;` | CAPITAL LETTER ETA
Θ | 920 | 0398 | `&Theta;` | CAPITAL LETTER THETA
Ι | 921 | 0399 | `&Iota;` | CAPITAL LETTER IOTA
Κ | 922 | 039A | `&Kappa;` | CAPITAL LETTER KAPPA
Λ | 923 | 039B | `&Lambda;` | CAPITAL LETTER LAMBDA
Μ | 924 | 039C | `&Mu;` | CAPITAL LETTER MU
Ν | 925 | 039D | `&Nu;` | CAPITAL LETTER NU
Ξ | 926 | 039E | `&Xi;` | CAPITAL LETTER XI
Ο | 927 | 039F | `&Omicron;` | CAPITAL LETTER OMICRON
Π | 928 | 03A0 | `&Pi;` | CAPITAL LETTER PI
Ρ | 929 | 03A1 | `&Rho;` | CAPITAL LETTER RHO
Σ | 931 | 03A3 | `&Sigma;` | CAPITAL LETTER SIGMA
Τ | 932 | 03A4 | `&Tau;` | CAPITAL LETTER TAU
Υ | 933 | 03A5 | `&Upsilon;` | CAPITAL LETTER UPSILON
Φ | 934 | 03A6 | `&Phi;` | CAPITAL LETTER PHI
Χ | 935 | 03A7 | `&Chi;` | CAPITAL LETTER CHI
Ψ | 936 | 03A8 | `&Psi;` | CAPITAL LETTER PSI
Ω | 937 | 03A9 | `&Omega;` | CAPITAL LETTER OMEGA
Ϊ | 938 | 03AA |   | CAPITAL LETTER IOTA WITH DIALYTIKA
Ϋ | 939 | 03AB |   | CAPITAL LETTER UPSILON WITH DIALYTIKA
ά | 940 | 03AC |   | SMALL LETTER ALPHA WITH TONOS
έ | 941 | 03AD |   | SMALL LETTER EPSILON WITH TONOS
ή | 942 | 03AE |   | SMALL LETTER ETA WITH TONOS
ί | 943 | 03AF |   | SMALL LETTER IOTA WITH TONOS
ΰ | 944 | 03B0 |   | SMALL LETTER UPSILON WITH DIALYTIKA AND TONOS
α | 945 | 03B1 | `&alpha;` | SMALL LETTER ALPHA
β | 946 | 03B2 | `&beta;` | SMALL LETTER BETA
γ | 947 | 03B3 | `&gamma;` | SMALL LETTER GAMMA
δ | 948 | 03B4 | `&delta;` | SMALL LETTER DELTA
ε | 949 | 03B5 | `&epsilon;` | SMALL LETTER EPSILON
ζ | 950 | 03B6 | `&zeta;` | SMALL LETTER ZETA
η | 951 | 03B7 | `&eta;` | SMALL LETTER ETA
θ | 952 | 03B8 | `&theta;` | SMALL LETTER THETA
ι | 953 | 03B9 | `&iota;` | SMALL LETTER IOTA
κ | 954 | 03BA | `&kappa;` | SMALL LETTER KAPPA
λ | 955 | 03BB | `&lambda;` | SMALL LETTER LAMBDA
μ | 956 | 03BC | `&mu;` | SMALL LETTER MU
ν | 957 | 03BD | `&nu;` | SMALL LETTER NU
ξ | 958 | 03BE | `&xi;` | SMALL LETTER XI
ο | 959 | 03BF | `&omicron;` | SMALL LETTER OMICRON
π | 960 | 03C0 | `&pi;` | SMALL LETTER PI
ρ | 961 | 03C1 | `&rho;` | SMALL LETTER RHO
ς | 962 | 03C2 | `&sigmaf;` | SMALL LETTER FINAL SIGMA
σ | 963 | 03C3 | `&sigma;` | SMALL LETTER SIGMA
τ | 964 | 03C4 | `&tau;` | SMALL LETTER TAU
υ | 965 | 03C5 | `&upsilon;` | SMALL LETTER UPSILON
φ | 966 | 03C6 | `&phi;` | SMALL LETTER PHI
χ | 967 | 03C7 | `&chi;` | SMALL LETTER CHI
ψ | 968 | 03C8 | `&psi;` | SMALL LETTER PSI
ω | 969 | 03C9 | `&omega;` | SMALL LETTER OMEGA
ϊ | 970 | 03CA |   | SMALL LETTER IOTA WITH DIALYTIKA
ϋ | 971 | 03CB |   | SMALL LETTER UPSILON WITH DIALYTIKA
ό | 972 | 03CC |   | SMALL LETTER OMICRON WITH TONOS
ύ | 973 | 03CD |   | SMALL LETTER UPSILON WITH TONOS
ώ | 974 | 03CE |   | SMALL LETTER OMEGA WITH TONOS
Ϗ | 975 | 03CF |   | CAPITAL KAI SYMBOL
ϐ | 976 | 03D0 |   | BETA SYMBOL
ϑ | 977 | 03D1 | `&thetasym;` | THETA SYMBOL
ϒ | 978 | 03D2 | `&upsih;` | UPSILON WITH HOOK SYMBOL
ϓ | 979 | 03D3 |   | UPSILON WITH ACUTE AND HOOK SYMBOL
ϔ | 980 | 03D4 |   | UPSILON WITH DIAERESIS AND HOOK SYMBOL
ϕ | 981 | 03D5 | `&straightphi;` | PHI SYMBOL
ϖ | 982 | 03D6 | `&piv;` | PI SYMBOL
ϗ | 983 | 03D7 |   | KAI SYMBOL
Ϙ | 984 | 03D8 |   | LETTER ARCHAIC KOPPA
ϙ | 985 | 03D9 |   | SMALL LETTER ARCHAIC KOPPA
Ϛ | 986 | 03DA |   | LETTER STIGMA
ϛ | 987 | 03DB |   | SMALL LETTER STIGMA
Ϝ | 988 | 03DC | `&Gammad;` | LETTER DIGAMMA
ϝ | 989 | 03DD | `&gammad;` | SMALL LETTER DIGAMMA
Ϟ | 990 | 03DE |   | LETTER KOPPA
ϟ | 991 | 03DF |   | SMALL LETTER KOPPA
Ϡ | 992 | 03E0 |   | LETTER SAMPI
ϡ | 993 | 03E1 |   | SMALL LETTER SAMPI
Ϣ | 994 | 03E2 |   | COPTIC CAPITAL LETTER SHEI
ϣ | 995 | 03E3 |   | COPTIC SMALL LETTER SHEI
Ϥ | 996 | 03E4 |   | COPTIC CAPITAL LETTER FEI
ϥ | 997 | 03E5 |   | COPTIC SMALL LETTER FEI
Ϧ | 998 | 03E6 |   | COPTIC CAPITAL LETTER KHEI
ϧ | 999 | 03E7 |   | COPTIC SMALL LETTER KHEI
Ϩ | 1000 | 03E8 |   | COPTIC CAPITAL LETTER HORI
ϩ | 1001 | 03E9 |   | COPTIC SMALL LETTER HORI
Ϫ | 1002 | 03EA |   | COPTIC CAPITAL LETTER GANGIA
ϫ | 1003 | 03EB |   | COPTIC SMALL LETTER GANGIA
Ϭ | 1004 | 03EC |   | COPTIC CAPITAL LETTER SHIMA
ϭ | 1005 | 03ED |   | COPTIC SMALL LETTER SHIMA
Ϯ | 1006 | 03EE |   | COPTIC CAPITAL LETTER DEI
ϯ | 1007 | 03EF |   | COPTIC SMALL LETTER DEI
ϰ | 1008 | 03F0 |  `&varkappa;` | KAPPA SYMBOL
ϱ | 1009 | 03F1 |  `&varrho;` | RHO SYMBOL
ϲ | 1010 | 03F2 |   | LUNATE SIGMA SYMBOL
ϳ | 1011 | 03F3 |   | LETTER YOT
ϴ | 1012 | 03F4 |   | CAPITAL THETA SYMBOL
ϵ | 1013 | 03F5 |  `&straightepsilon;` | LUNATE EPSILON SYMBOL
϶ | 1014 | 03F6 |  `&backepsilon;` | REVERSED LUNATE EPSILON SYMBOL
Ϸ | 1015 | 03F7 |   | CAPITAL LETTER SHO
ϸ | 1016 | 03F8 |   | SMALL LETTER SHO
Ϲ | 1017 | 03F9 |   | CAPITAL LUNATE SIGMA SYMBOL
Ϻ | 1018 | 03FA |   | CAPITAL LETTER SAN
ϻ | 1019 | 03FB |   | SMALL LETTER SAN
ϼ | 1020 | 03FC |   | RHO WITH STROKE SYMBOL
Ͻ | 1021 | 03FD |   | CAPITAL REVERSED LUNATE SIGMA SYMBOL
Ͼ | 1022 | 03FE |   | CAPITAL DOTTED LUNATE SIGMA SYMBOL
Ͽ | 1023 | 03FF |   | CAPITAL REVERSED DOTTED LUNATE SIGMA SYMBOL

## Cyrillic Basic

Cyrillic / Slavonic / Slavic

西里爾字母是用於俄語、保加利亞語、塞爾維亞語、烏克蘭語和其他斯拉夫語言的字母表。

西里爾字母是在保加利亞第一帝國時期創建的。它源自於希臘安色爾字母，是東正教使用的字母。

Hex 0400-04FF / Decimal 1024-1279.

Char | Dec | Hex | Name
--- | --- | --- | ---
Ѐ | 1024 | 0400 | CAPITAL LETTER IE WITH GRAVE
Ё | 1025 | 0401 | CAPITAL LETTER IO
Ђ | 1026 | 0402 | CAPITAL LETTER DJE
Ѓ | 1027 | 0403 | CAPITAL LETTER GJE
Є | 1028 | 0404 | CAPITAL LETTER UKRAINIAN IE
Ѕ | 1029 | 0405 | CAPITAL LETTER DZE
І | 1030 | 0406 | CAPITAL LETTER BYELORUSSIAN-UKRAINIAN I
Ї | 1031 | 0407 | CAPITAL LETTER YI
Ј | 1032 | 0408 | CAPITAL LETTER JE
Љ | 1033 | 0409 | CAPITAL LETTER LJE
Њ | 1034 | 040A | CAPITAL LETTER NJE
Ћ | 1035 | 040B | CAPITAL LETTER TSHE
Ќ | 1036 | 040C | CAPITAL LETTER KJE
Ѝ | 1037 | 040D | CAPITAL LETTER I WITH GRAVE
Ў | 1038 | 040E | CAPITAL LETTER SHORT U
Џ | 1039 | 040F | CAPITAL LETTER DZHE
А | 1040 | 0410 | CAPITAL LETTER A
Б | 1041 | 0411 | CAPITAL LETTER BE
В | 1042 | 0412 | CAPITAL LETTER VE
Г | 1043 | 0413 | CAPITAL LETTER GHE
Д | 1044 | 0414 | CAPITAL LETTER DE
Е | 1045 | 0415 | CAPITAL LETTER IE
Ж | 1046 | 0416 | CAPITAL LETTER ZHE
З | 1047 | 0417 | CAPITAL LETTER ZE
И | 1048 | 0418 | CAPITAL LETTER I
Й | 1049 | 0419 | CAPITAL LETTER SHORT I
К | 1050 | 041A | CAPITAL LETTER KA
Л | 1051 | 041B | CAPITAL LETTER EL
М | 1052 | 041C | CAPITAL LETTER EM
Н | 1053 | 041D | CAPITAL LETTER EN
О | 1054 | 041E | CAPITAL LETTER O
П | 1055 | 041F | CAPITAL LETTER PE
Р | 1056 | 0420 | CAPITAL LETTER ER
С | 1057 | 0421 | CAPITAL LETTER ES
Т | 1058 | 0422 | CAPITAL LETTER TE
У | 1059 | 0423 | CAPITAL LETTER U
Ф | 1060 | 0424 | CAPITAL LETTER EF
Х | 1061 | 0425 | CAPITAL LETTER HA
Ц | 1062 | 0426 | CAPITAL LETTER TSE
Ч | 1063 | 0427 | CAPITAL LETTER CHE
Ш | 1064 | 0428 | CAPITAL LETTER SHA
Щ | 1065 | 0429 | CAPITAL LETTER SHCHA
Ъ | 1066 | 042A | CAPITAL LETTER HARD SIGN
Ы | 1067 | 042B | CAPITAL LETTER YERU
Ь | 1068 | 042C | CAPITAL LETTER SOFT SIGN
Э | 1069 | 042D | CAPITAL LETTER E
Ю | 1070 | 042E | CAPITAL LETTER YU
Я | 1071 | 042F | CAPITAL LETTER YA
а | 1072 | 0430 | SMALL LETTER A
б | 1073 | 0431 | SMALL LETTER BE
в | 1074 | 0432 | SMALL LETTER VE
г | 1075 | 0433 | SMALL LETTER GHE
д | 1076 | 0434 | SMALL LETTER DE
е | 1077 | 0435 | SMALL LETTER IE
ж | 1078 | 0436 | SMALL LETTER ZHE
з | 1079 | 0437 | SMALL LETTER ZE
и | 1080 | 0438 | SMALL LETTER I
й | 1081 | 0439 | SMALL LETTER SHORT I
к | 1082 | 043A | SMALL LETTER KA
л | 1083 | 043B | SMALL LETTER EL
м | 1084 | 043C | SMALL LETTER EM
н | 1085 | 043D | SMALL LETTER EN
о | 1086 | 043E | SMALL LETTER O
п | 1087 | 043F | SMALL LETTER PE
р | 1088 | 0440 | SMALL LETTER ER
с | 1089 | 0441 | SMALL LETTER ES
т | 1090 | 0442 | SMALL LETTER TE
у | 1091 | 0443 | SMALL LETTER U
ф | 1092 | 0444 | SMALL LETTER EF
х | 1093 | 0445 | SMALL LETTER HA
ц | 1094 | 0446 | SMALL LETTER TSE
ч | 1095 | 0447 | SMALL LETTER CHE
ш | 1096 | 0448 | SMALL LETTER SHA
щ | 1097 | 0449 | SMALL LETTER SHCHA
ъ | 1098 | 044A | SMALL LETTER HARD SIGN
ы | 1099 | 044B | SMALL LETTER YERU
ь | 1100 | 044C | SMALL LETTER SOFT SIGN
э | 1101 | 044D | SMALL LETTER E
ю | 1102 | 044E | SMALL LETTER YU
я | 1103 | 044F | SMALL LETTER YA
ѐ | 1104 | 0450 | SMALL LETTER IE WITH GRAVE
ё | 1105 | 0451 | SMALL LETTER IO
ђ | 1106 | 0452 | SMALL LETTER DJE
ѓ | 1107 | 0453 | SMALL LETTER GJE
є | 1108 | 0454 | SMALL LETTER UKRAINIAN IE
ѕ | 1109 | 0455 | SMALL LETTER DZE
і | 1110 | 0456 | SMALL LETTER BYELORUSSIAN-UKRAINIAN I
ї | 1111 | 0457 | SMALL LETTER YI
ј | 1112 | 0458 | SMALL LETTER JE
љ | 1113 | 0459 | SMALL LETTER LJE
њ | 1114 | 045A | SMALL LETTER NJE
ћ | 1115 | 045B | SMALL LETTER TSHE
ќ | 1116 | 045C | SMALL LETTER KJE
ѝ | 1117 | 045D | SMALL LETTER I WITH GRAVE
ў | 1118 | 045E | SMALL LETTER SHORT U
џ | 1119 | 045F | SMALL LETTER DZHE
Ѡ | 1120 | 0460 | CAPITAL LETTER OMEGA
ѡ | 1121 | 0461 | SMALL LETTER OMEGA
Ѣ | 1122 | 0462 | CAPITAL LETTER YAT
ѣ | 1123 | 0463 | SMALL LETTER YAT
Ѥ | 1124 | 0464 | CAPITAL LETTER IOTIFIED E
ѥ | 1125 | 0465 | SMALL LETTER IOTIFIED E
Ѧ | 1126 | 0466 | CAPITAL LETTER LITTLE YUS
ѧ | 1127 | 0467 | SMALL LETTER LITTLE YUS
Ѩ | 1128 | 0468 | CAPITAL LETTER IOTIFIED LITTLE YUS
ѩ | 1129 | 0469 | SMALL LETTER IOTIFIED LITTLE YUS
Ѫ | 1130 | 046A | CAPITAL LETTER BIG YUS
ѫ | 1131 | 046B | SMALL LETTER BIG YUS
Ѭ | 1132 | 046C | CAPITAL LETTER IOTIFIED BIG YUS
ѭ | 1133 | 046D | SMALL LETTER IOTIFIED BIG YUS
Ѯ | 1134 | 046E | CAPITAL LETTER KSI
ѯ | 1135 | 046F | SMALL LETTER KSI
Ѱ | 1136 | 0470 | CAPITAL LETTER PSI
ѱ | 1137 | 0471 | SMALL LETTER PSI
Ѳ | 1138 | 0472 | CAPITAL LETTER FITA
ѳ | 1139 | 0473 | SMALL LETTER FITA
Ѵ | 1140 | 0474 | CAPITAL LETTER IZHITSA
ѵ | 1141 | 0475 | SMALL LETTER IZHITSA
Ѷ | 1142 | 0476 | CAPITAL LETTER IZHITSA WITH DOUBLE GRAVE ACCENT
ѷ | 1143 | 0477 | SMALL LETTER IZHITSA WITH DOUBLE GRAVE ACCENT
Ѹ | 1144 | 0478 | CAPITAL LETTER UK
ѹ | 1145 | 0479 | SMALL LETTER UK
Ѻ | 1146 | 047A | CAPITAL LETTER ROUND OMEGA
ѻ | 1147 | 047B | SMALL LETTER ROUND OMEGA
Ѽ | 1148 | 047C | CAPITAL LETTER OMEGA WITH TITLO
ѽ | 1149 | 047D | SMALL LETTER OMEGA WITH TITLO
Ѿ | 1150 | 047E | CAPITAL LETTER OT
ѿ | 1151 | 047F | SMALL LETTER OT
Ҁ | 1152 | 0480 | CAPITAL LETTER KOPPA
ҁ | 1153 | 0481 | SMALL LETTER KOPPA
҂ | 1154 | 0482 | THOUSANDS SIGN
о҃ | 1155 | 0483 | COMBINING CYRILLIC TITLO (combined with о)
о҄ | 1156 | 0484 | COMBINING CYRILLIC PALATALIZATION (combined with о)
о҅ | 1157 | 0485 | COMBINING CYRILLIC DASIA PNEUMATA (combined with о)
о҆ | 1158 | 0486 | COMBINING CYRILLIC PSILI PNEUMATA (combined with о)
о҇ | 1159 | 0487 | COMBINING CYRILLIC POKRYTIE (combined with о)
о҈ | 1160 | 0488 | COMBINING CYRILLIC HUNDRED THOUSANDS SIGN (combined with о)
о҉ | 1161 | 0489 | COMBINING CYRILLIC MILLIONS SIGN (combined with о)
Ҋ | 1162 | 048A | CAPITAL LETTER SHORT I WITH TAIL
ҋ | 1163 | 048B | SMALL LETTER SHORT I WITH TAIL
Ҍ | 1164 | 048C | CAPITAL LETTER SEMISOFT SIGN
ҍ | 1165 | 048D | SMALL LETTER SEMISOFT SIGN
Ҏ | 1166 | 048E | CAPITAL LETTER ER WITH TICK
ҏ | 1167 | 048F | SMALL LETTER ER WITH TICK
Ґ | 1168 | 0490 | CAPITAL LETTER GHE WITH UPTURN
ґ | 1169 | 0491 | SMALL LETTER GHE WITH UPTURN
Ғ | 1170 | 0492 | CAPITAL LETTER GHE WITH STROKE
ғ | 1171 | 0493 | SMALL LETTER GHE WITH STROKE
Ҕ | 1172 | 0494 | CAPITAL LETTER GHE WITH MIDDLE HOOK
ҕ | 1173 | 0495 | SMALL LETTER GHE WITH MIDDLE HOOK
Җ | 1174 | 0496 | CAPITAL LETTER ZHE WITH DESCENDER
җ | 1175 | 0497 | SMALL LETTER ZHE WITH DESCENDER
Ҙ | 1176 | 0498 | CAPITAL LETTER ZE WITH DESCENDER
ҙ | 1177 | 0499 | SMALL LETTER ZE WITH DESCENDER
Қ | 1178 | 049A | CAPITAL LETTER KA WITH DESCENDER
қ | 1179 | 049B | SMALL LETTER KA WITH DESCENDER
Ҝ | 1180 | 049C | CAPITAL LETTER KA WITH VERTICAL STROKE
ҝ | 1181 | 049D | SMALL LETTER KA WITH VERTICAL STROKE
Ҟ | 1182 | 049E | CAPITAL LETTER KA WITH STROKE
ҟ | 1183 | 049F | SMALL LETTER KA WITH STROKE
Ҡ | 1184 | 04A0 | CAPITAL LETTER BASHKIR KA
ҡ | 1185 | 04A1 | SMALL LETTER BASHKIR KA
Ң | 1186 | 04A2 | CAPITAL LETTER EN WITH DESCENDER
ң | 1187 | 04A3 | SMALL LETTER EN WITH DESCENDER
Ҥ | 1188 | 04A4 | CAPITAL LIGATURE EN GHE
ҥ | 1189 | 04A5 | SMALL LIGATURE EN GHE
Ҧ | 1190 | 04A6 | CAPITAL LETTER PE WITH MIDDLE HOOK
ҧ | 1191 | 04A7 | SMALL LETTER PE WITH MIDDLE HOOK
Ҩ | 1192 | 04A8 | CAPITAL LETTER ABKHASIAN HA
ҩ | 1193 | 04A9 | SMALL LETTER ABKHASIAN HA
Ҫ | 1194 | 04AA | CAPITAL LETTER ES WITH DESCENDER
ҫ | 1195 | 04AB | SMALL LETTER ES WITH DESCENDER
Ҭ | 1196 | 04AC | CAPITAL LETTER TE WITH DESCENDER
ҭ | 1197 | 04AD | SMALL LETTER TE WITH DESCENDER
Ү | 1198 | 04AE | CAPITAL LETTER STRAIGHT U
ү | 1199 | 04AF | SMALL LETTER STRAIGHT U
Ұ | 1200 | 04B0 | CAPITAL LETTER STRAIGHT U WITH STROKE
ұ | 1201 | 04B1 | SMALL LETTER STRAIGHT U WITH STROKE
Ҳ | 1202 | 04B2 | CAPITAL LETTER HA WITH DESCENDER
ҳ | 1203 | 04B3 | SMALL LETTER HA WITH DESCENDER
Ҵ | 1204 | 04B4 | CAPITAL LIGATURE TE TSE
ҵ | 1205 | 04B5 | SMALL LIGATURE TE TSE
Ҷ | 1206 | 04B6 | CAPITAL LETTER CHE WITH DESCENDER
ҷ | 1207 | 04B7 | SMALL LETTER CHE WITH DESCENDER
Ҹ | 1208 | 04B8 | CAPITAL LETTER CHE WITH VERTICAL STROKE
ҹ | 1209 | 04B9 | SMALL LETTER CHE WITH VERTICAL STROKE
Һ | 1210 | 04BA | CAPITAL LETTER SHHA
һ | 1211 | 04BB | SMALL LETTER SHHA
Ҽ | 1212 | 04BC | CAPITAL LETTER ABKHASIAN CHE
ҽ | 1213 | 04BD | SMALL LETTER ABKHASIAN CHE
Ҿ | 1214 | 04BE | CAPITAL LETTER ABKHASIAN CHE WITH DESCENDER
ҿ | 1215 | 04BF | SMALL LETTER ABKHASIAN CHE WITH DESCENDER
Ӏ | 1216 | 04C0 | LETTER PALOCHKA
Ӂ | 1217 | 04C1 | CAPITAL LETTER ZHE WITH BREVE
ӂ | 1218 | 04C2 | SMALL LETTER ZHE WITH BREVE
Ӄ | 1219 | 04C3 | CAPITAL LETTER KA WITH HOOK
ӄ | 1220 | 04C4 | SMALL LETTER KA WITH HOOK
Ӆ | 1221 | 04C5 | CAPITAL LETTER EL WITH TAIL
ӆ | 1222 | 04C6 | SMALL LETTER EL WITH TAIL
Ӈ | 1223 | 04C7 | CAPITAL LETTER EN WITH HOOK
ӈ | 1224 | 04C8 | SMALL LETTER EN WITH HOOK
Ӊ | 1225 | 04C9 | CAPITAL LETTER EN WITH TAIL
ӊ | 1226 | 04CA | SMALL LETTER EN WITH TAIL
Ӌ | 1227 | 04CB | CAPITAL LETTER KHAKASSIAN CHE
ӌ | 1228 | 04CC | SMALL LETTER KHAKASSIAN CHE
Ӎ | 1229 | 04CD | CAPITAL LETTER EM WITH TAIL
ӎ | 1230 | 04CE | SMALL LETTER EM WITH TAIL
ӏ | 1231 | 04CF | SMALL LETTER PALOCHKA
Ӑ | 1232 | 04D0 | CAPITAL LETTER A WITH BREVE
ӑ | 1233 | 04D1 | SMALL LETTER A WITH BREVE
Ӓ | 1234 | 04D2 | CAPITAL LETTER A WITH DIAERESIS
ӓ | 1235 | 04D3 | SMALL LETTER A WITH DIAERESIS
Ӕ | 1236 | 04D4 | CAPITAL LIGATURE A IE
ӕ | 1237 | 04D5 | SMALL LIGATURE A IE
Ӗ | 1238 | 04D6 | CAPITAL LETTER IE WITH BREVE
ӗ | 1239 | 04D7 | SMALL LETTER IE WITH BREVE
Ә | 1240 | 04D8 | CAPITAL LETTER SCHWA
ә | 1241 | 04D9 | SMALL LETTER SCHWA
Ӛ | 1242 | 04DA | CAPITAL LETTER SCHWA WITH DIAERESIS
ӛ | 1243 | 04DB | SMALL LETTER SCHWA WITH DIAERESIS
Ӝ | 1244 | 04DC | CAPITAL LETTER ZHE WITH DIAERESIS
ӝ | 1245 | 04DD | SMALL LETTER ZHE WITH DIAERESIS
Ӟ | 1246 | 04DE | CAPITAL LETTER ZE WITH DIAERESIS
ӟ | 1247 | 04DF | SMALL LETTER ZE WITH DIAERESIS
Ӡ | 1248 | 04E0 | CAPITAL LETTER ABKHASIAN DZE
ӡ | 1249 | 04E1 | SMALL LETTER ABKHASIAN DZE
Ӣ | 1250 | 04E2 | CAPITAL LETTER I WITH MACRON
ӣ | 1251 | 04E3 | SMALL LETTER I WITH MACRON
Ӥ | 1252 | 04E4 | CAPITAL LETTER I WITH DIAERESIS
ӥ | 1253 | 04E5 | SMALL LETTER I WITH DIAERESIS
Ӧ | 1254 | 04E6 | CAPITAL LETTER O WITH DIAERESIS
ӧ | 1255 | 04E7 | SMALL LETTER O WITH DIAERESIS
Ө | 1256 | 04E8 | CAPITAL LETTER BARRED O
ө | 1257 | 04E9 | SMALL LETTER BARRED O
Ӫ | 1258 | 04EA | CAPITAL LETTER BARRED O WITH DIAERESIS
ӫ | 1259 | 04EB | SMALL LETTER BARRED O WITH DIAERESIS
Ӭ | 1260 | 04EC | CAPITAL LETTER E WITH DIAERESIS
ӭ | 1261 | 04ED | SMALL LETTER E WITH DIAERESIS
Ӯ | 1262 | 04EE | CAPITAL LETTER U WITH MACRON
ӯ | 1263 | 04EF | SMALL LETTER U WITH MACRON
Ӱ | 1264 | 04F0 | CAPITAL LETTER U WITH DIAERESIS
ӱ | 1265 | 04F1 | SMALL LETTER U WITH DIAERESIS
Ӳ | 1266 | 04F2 | CAPITAL LETTER U WITH DOUBLE ACUTE
ӳ | 1267 | 04F3 | SMALL LETTER U WITH DOUBLE ACUTE
Ӵ | 1268 | 04F4 | CAPITAL LETTER CHE WITH DIAERESIS
ӵ | 1269 | 04F5 | SMALL LETTER CHE WITH DIAERESIS
Ӷ | 1270 | 04F6 | CAPITAL LETTER GHE WITH DESCENDER
ӷ | 1271 | 04F7 | SMALL LETTER GHE WITH DESCENDER
Ӹ | 1272 | 04F8 | CAPITAL LETTER YERU WITH DIAERESIS
ӹ | 1273 | 04F9 | SMALL LETTER YERU WITH DIAERESIS
Ӻ | 1274 | 04FA | CAPITAL LETTER GHE WITH STROKE AND HOOK
ӻ | 1275 | 04FB | SMALL LETTER GHE WITH STROKE AND HOOK
Ӽ | 1276 | 04FC | CAPITAL LETTER HA WITH HOOK
ӽ | 1277 | 04FD | SMALL LETTER HA WITH HOOK
Ӿ | 1278 | 04FE | CAPITAL LETTER HA WITH STROKE
ӿ | 1279 | 04FF | SMALL LETTER HA WITH STROKE

## Cyrillic Supplement

Hex 0500-052F / Decimal 1280-1327.

Char | Dec | Hex | Name
--- | --- | --- | ---
Ԁ | 1280 | 0500 | CAPITAL LETTER KOMI DE
ԁ | 1281 | 0501 | SMALL LETTER KOMI DE
Ԃ | 1282 | 0502 | CAPITAL LETTER KOMI DJE
ԃ | 1283 | 0503 | SMALL LETTER KOMI DJE
Ԅ | 1284 | 0504 | CAPITAL LETTER KOMI ZJE
ԅ | 1285 | 0505 | SMALL LETTER KOMI ZJE
Ԇ | 1286 | 0506 | CAPITAL LETTER KOMI DZJE
ԇ | 1287 | 0507 | SMALL LETTER KOMI DZJE
Ԉ | 1288 | 0508 | CAPITAL LETTER KOMI LJE
ԉ | 1289 | 0509 | SMALL LETTER KOMI LJE
Ԋ | 1290 | 050A | CAPITAL LETTER KOMI NJE
ԋ | 1291 | 050B | SMALL LETTER KOMI NJE
Ԍ | 1292 | 050C | CAPITAL LETTER KOMI SJE
ԍ | 1293 | 050D | SMALL LETTER KOMI SJE
Ԏ | 1294 | 050E | CAPITAL LETTER KOMI TJE
ԏ | 1295 | 050F | SMALL LETTER KOMI TJE
Ԕ | 1300 | 0514 | CAPITAL LETTER LHA
ԕ | 1301 | 0515 | SMALL LETTER LHA
Ԗ | 1302 | 0516 | CAPITAL LETTER RHA
ԗ | 1303 | 0517 | SMALL LETTER RHA
Ԙ | 1304 | 0518 | CAPITAL LETTER YAE
ԙ | 1305 | 0519 | SMALL LETTER YAE
Ԛ | 1306 | 051A | CAPITAL LETTER QA
ԛ | 1307 | 051B | SMALL LETTER QA
Ԝ | 1308 | 051C | CAPITAL LETTER WE
ԝ | 1309 | 051D | SMALL LETTER WE
Ԟ | 1310 | 051E | CAPITAL LETTER ALEUT KA
ԟ | 1311 | 051F | SMALL LETTER ALEUT KA
Ԡ | 1312 | 0520 | CAPITAL LETTER EL WITH MIDDLE HOOK
ԡ | 1313 | 0521 | SMALL LETTER EL WITH MIDDLE HOOK
Ԣ | 1314 | 0522 | CAPITAL LETTER EN WITH MIDDLE HOOK
ԣ | 1315 | 0523 | SMALL LETTER EN WITH MIDDLE HOOK
Ԥ | 1316 | 0524 | CAPITAL LETTER PE WITH DESCENDER
ԥ | 1317 | 0525 | SMALL LETTER PE WITH DESCENDER
Ԧ | 1318 | 0526 | CAPITAL LETTER SHHA WITH DESCENDER
ԧ | 1319 | 0527 | SMALL LETTER SHHA WITH DESCENDER
Ԩ | 1320 | 0528 | 
ԩ | 1321 | 0529 | 
Ԫ | 1322 | 052A | 
ԫ | 1323 | 052B | 
Ԭ | 1324 | 052C | 
ԭ | 1325 | 052D | 
Ԯ | 1326 | 052E | 
ԯ | 1327 | 052F | 

## General Punctuation

Hex 2000-206F / Decimal 8192-8303.

| Char | Dec  | Hex  | Entity     | Name                                       |
| ---- | ---- | ---- | ---------- | ------------------------------------------ |
|      | 8192 | 2000 |            | EN QUAD                                    |
|      | 8193 | 2001 |            | EM QUAD                                    |
|      | 8194 | 2002 | `&ensp;`   | EN SPACE                                   |
|      | 8195 | 2003 | `&emsp;`   | EM SPACE                                   |
|      | 8196 | 2004 |            | THREE-PER-EM SPACE                         |
|      | 8197 | 2005 |            | FOUR-PER-EM SPACE                          |
|      | 8198 | 2006 |            | SIX-PER-EM SPACE                           |
|      | 8199 | 2007 |            | FIGURE SPACE                               |
|      | 8200 | 2008 |            | PUNCTUATION SPACE                          |
|      | 8201 | 2009 | `&thinsp;` | THIN SPACE                                 |
|      | 8202 | 200A |            | HAIR SPACE                                 |
| ​    | 8203 | 200B |            | ZERO WIDTH SPACE                           |
| ‌    | 8204 | 200C | `&zwnj;`   | ZERO WIDTH NON-JOINER                      |
| ‍    | 8205 | 200D | `&zwj;`    | ZERO WIDTH JOINER                          |
| ‎    | 8206 | 200E | `&lrm;`    | LEFT-TO-RIGHT MARK                         |
| ‏    | 8207 | 200F | `&rlm;`    | RIGHT-TO-LEFT MARK                         |
| ‐    | 8208 | 2010 |            | HYPHEN                                     |
| ‑    | 8209 | 2011 |            | NON-BREAKING HYPHEN                        |
| ‒    | 8210 | 2012 |            | FIGURE DASH                                |
| –    | 8211 | 2013 | `&ndash;`  | EN DASH                                    |
| —    | 8212 | 2014 | `&mdash;`  | EM DASH                                    |
| ―    | 8213 | 2015 |            | HORIZONTAL BAR                             |
| ‖    | 8214 | 2016 |            | DOUBLE VERTICAL LINE                       |
| ‗    | 8215 | 2017 |            | DOUBLE LOW LINE                            |
| ‘    | 8216 | 2018 | `&lsquo;`  | LEFT SINGLE QUOTATION MARK                 |
| ’    | 8217 | 2019 | `&rsquo;`  | RIGHT SINGLE QUOTATION MARK                |
| ‚    | 8218 | 201A | `&sbquo;`  | SINGLE LOW-9 QUOTATION MARK                |
| ‛    | 8219 | 201B |            | SINGLE HIGH-REVERSED-9 QUOTATION MARK      |
| “    | 8220 | 201C | `&ldquo;`  | LEFT DOUBLE QUOTATION MARK                 |
| ”    | 8221 | 201D | `&rdquo;`  | RIGHT DOUBLE QUOTATION MARK                |
| „    | 8222 | 201E | `&bdquo;`  | DOUBLE LOW-9 QUOTATION MARK                |
| ‟    | 8223 | 201F |            | DOUBLE HIGH-REVERSED-9 QUOTATION MARK      |
| †    | 8224 | 2020 | `&dagger;` | DAGGER                                     |
| ‡    | 8225 | 2021 | `&Dagger;` | DOUBLE DAGGER                              |
| •    | 8226 | 2022 | `&bull;`   | BULLET                                     |
| ‣    | 8227 | 2023 |            | TRIANGULAR BULLET                          |
| ․    | 8228 | 2024 |            | ONE DOT LEADER                             |
| ‥    | 8229 | 2025 |            | TWO DOT LEADER                             |
| …    | 8230 | 2026 | `&hellip;` | HORIZONTAL ELLIPSIS                        |
| ‧    | 8231 | 2027 |            | HYPHENATION POINT                          |
|      | 8232 | 2028 |            | LINE SEPARATOR                             |
|      | 8233 | 2029 |            | PARAGRAPH SEPARATOR                        |
| ‪    | 8234 | 202A |            | LEFT-TO-RIGHT EMBEDDING                    |
| ‫    | 8235 | 202B |            | RIGHT-TO-LEFT EMBEDDING                    |
| ‬    | 8236 | 202C |            | POP DIRECTIONAL FORMATTING                 |
| ‭    | 8237 | 202D |            | LEFT-TO-RIGHT OVERRIDE                     |
| ‮    | 8238 | 202E |            | RIGHT-TO-LEFT OVERRIDE                     |
|      | 8239 | 202F |            | NARROW NON-BREAK SPACE                     |
| ‰    | 8240 | 2030 | `&permil;` | PER MILLE SIGN                             |
| ‱    | 8241 | 2031 |            | PER TEN THOUSAND SIGN                      |
| ′    | 8242 | 2032 | `&prime;`  | PRIME                                      |
| ″    | 8243 | 2033 | `&Prime;`  | DOUBLE PRIME                               |
| ‴    | 8244 | 2034 |            | TRIPLE PRIME                               |
| ‵    | 8245 | 2035 |            | REVERSED PRIME                             |
| ‶    | 8246 | 2036 |            | REVERSED DOUBLE PRIME                      |
| ‷    | 8247 | 2037 |            | REVERSED TRIPLE PRIME                      |
| ‸    | 8248 | 2038 |            | CARET                                      |
| ‹    | 8249 | 2039 | `&lsaquo;` | SINGLE LEFT-POINTING ANGLE QUOTATION MARK  |
| ›    | 8250 | 203A | `&rsaquo;` | SINGLE RIGHT-POINTING ANGLE QUOTATION MARK |
| ※    | 8251 | 203B |            | REFERENCE MARK                             |
| ‼    | 8252 | 203C |            | DOUBLE EXCLAMATION MARK                    |
| ‽    | 8253 | 203D |            | INTERROBANG                                |
| ‾    | 8254 | 203E | `&oline;`  | OVERLINE                                   |
| ‿    | 8255 | 203F |            | UNDERTIE                                   |
| ⁀    | 8256 | 2040 |            | CHARACTER TIE                              |
| ⁁    | 8257 | 2041 |            | CARET INSERTION POINT                      |
| ⁂    | 8258 | 2042 |            | ASTERISM                                   |
| ⁃    | 8259 | 2043 |            | HYPHEN BULLET                              |
| ⁄    | 8260 | 2044 | `&frasl;`  | FRACTION SLASH                             |
| ⁅    | 8261 | 2045 |            | LEFT SQUARE BRACKET WITH QUILL             |
| ⁆    | 8262 | 2046 |            | RIGHT SQUARE BRACKET WITH QUILL            |
| ⁇    | 8263 | 2047 |            | DOUBLE QUESTION MARK                       |
| ⁈    | 8264 | 2048 |            | QUESTION EXCLAMATION MARK                  |
| ⁉    | 8265 | 2049 |            | EXCLAMATION QUESTION MARK                  |
| ⁊    | 8266 | 204A |            | TIRONIAN SIGN ET                           |
| ⁋    | 8267 | 204B |            | REVERSED PILCROW SIGN                      |
| ⁌    | 8268 | 204C |            | BLACK LEFTWARDS BULLET                     |
| ⁍    | 8269 | 204D |            | BLACK RIGHTWARDS BULLET                    |
| ⁎    | 8270 | 204E |            | LOW ASTERISK                               |
| ⁏    | 8271 | 204F |            | REVERSED SEMICOLON                         |
| ⁐    | 8272 | 2050 |            | CLOSE UP                                   |
| ⁑    | 8273 | 2051 |            | TWO ASTERISKS ALIGNED VERTICALLY           |
| ⁒    | 8274 | 2052 |            | COMMERCIAL MINUS SIGN                      |
| ⁓    | 8275 | 2053 |            | SWUNG DASH                                 |
| ⁔    | 8276 | 2054 |            | INVERTED UNDERTIE                          |
| ⁕    | 8277 | 2055 |            | FLOWER PUNCTUATION MARK                    |
| ⁖    | 8278 | 2056 |            | THREE DOT PUNCTUATION                      |
| ⁗    | 8279 | 2057 |            | QUADRUPLE PRIME                            |
| ⁘    | 8280 | 2058 |            | FOUR DOT PUNCTUATION                       |
| ⁙    | 8281 | 2059 |            | FIVE DOT PUNCTUATION                       |
| ⁚    | 8282 | 205A |            | TWO DOT PUNCTUATION                        |
| ⁛    | 8283 | 205B |            | FOUR DOT MARK                              |
| ⁜    | 8284 | 205C |            | DOTTED CROSS                               |
| ⁝    | 8285 | 205D |            | TRICOLON                                   |
| ⁞    | 8286 | 205E |            | VERTICAL FOUR DOTS                         |
|      | 8287 | 205F |            | MEDIUM MATHEMATICAL SPACE                  |
| ⁠    | 8288 | 2060 |            | WORD JOINER                                |
| ⁡    | 8289 | 2061 |            | FUNCTION APPLICATION                       |
| ⁢    | 8290 | 2062 |            | INVISIBLE TIMES                            |
| ⁣    | 8291 | 2063 |            | INVISIBLE SEPARATOR                        |
| ⁤    | 8292 | 2064 |            | INVISIBLE PLUS                             |
| ⁦    | 8294 | 2066 |            | LEFT-TO-RIGHT ISOLATE                      |
| ⁧    | 8295 | 2067 |            | RIGHT-TO-LEFT ISOLATE                      |
| ⁨    | 8296 | 2068 |            | FIRST STRONG ISOLATE                       |
| ⁩    | 8297 | 2069 |            | POP DIRECTIONAL ISOLATE                    |
| ⁪    | 8298 | 206A |            | INHIBIT SYMMETRIC SWAPPING                 |
| ⁫    | 8299 | 206B |            | ACTIVATE SYMMETRIC SWAPPING                |
| ⁬    | 8300 | 206C |            | INHIBIT ARABIC FORM SHAPING                |
| ⁭    | 8301 | 206D |            | ACTIVATE ARABIC FORM SHAPING               |
| ⁮    | 8302 | 206E |            | NATIONAL DIGIT SHAPES                      |
| ⁯    | 8303 | 206F |            | NOMINAL DIGIT SHAPES                       |

## Currency Symbols

Hex 20A0-20CF / Decimal 8352-8399.

Char | Dec | Hex | Entity | Name
--- | --- | --- | --- | ---
₠ | 8352 | 20A0 |   | EURO-CURRENCY SIGN
₡ | 8353 | 20A1 |   | COLON SIGN
₢ | 8354 | 20A2 |   | CRUZEIRO SIGN
₣ | 8355 | 20A3 |   | FRENCH FRANC SIGN
₤ | 8356 | 20A4 |   | LIRA SIGN
₥ | 8357 | 20A5 |   | MILL SIGN
₦ | 8358 | 20A6 |   | NAIRA SIGN
₧ | 8359 | 20A7 |   | PESETA SIGN
₨ | 8360 | 20A8 |   | RUPEE SIGN
₩ | 8361 | 20A9 |   | WON SIGN
₪ | 8362 | 20AA |   | NEW SHEQEL SIGN
₫ | 8363 | 20AB |   | DONG SIGN
€ | 8364 | 20AC | `&euro;` | EURO SIGN
₭ | 8365 | 20AD |   | KIP SIGN
₮ | 8366 | 20AE |   | TUGRIK SIGN
₯ | 8367 | 20AF |   | DRACHMA SIGN
₰ | 8368 | 20B0 |   | GERMAN PENNY SYMBOL
₱ | 8369 | 20B1 |   | PESO SIGN
₲ | 8370 | 20B2 |   | GUARANI SIGN
₳ | 8371 | 20B3 |   | AUSTRAL SIGN
₴ | 8372 | 20B4 |   | HRYVNIA SIGN
₵ | 8373 | 20B5 |   | CEDI SIGN
₶ | 8374 | 20B6 |   | LIVRE TOURNOIS SIGN
₷ | 8375 | 20B7 |   | SPESMILO SIGN
₸ | 8376 | 20B8 |   | TENGE SIGN
₹ | 8377 | 20B9 |   | INDIAN RUPEE SIGN
₺ | 8378 | 20BA |   | TURKISH LIRA SIGN
₻ | 8379 | 20BB |   | NORDIC MARK SIGN
₼ | 8380 | 20BC |   | MANAT SIGN
₽ | 8381 | 20BD |   | RUBLE SIGN
₾ | 8382 | 20BE |   | LARI SIGN
₿ | 8383 | 20BF |   | BITCOIN SIGN

## Letterlike Symbols

Hex 2100-214F / Decimal 8448-8527.

Char | Dec | Hex | Entity | Name
--- | --- | --- | --- | ---
℀ | 8448 | 2100 |   | ACCOUNT OF
℁ | 8449 | 2101 |   | ADDRESSED TO THE SUBJECT
ℂ | 8450 | 2102 |   | DOUBLE-STRUCK CAPITAL C
℃ | 8451 | 2103 |   | DEGREE CELSIUS
℄ | 8452 | 2104 |   | CENTRE LINE SYMBOL
℅ | 8453 | 2105 |   | CARE OF
℆ | 8454 | 2106 |   | CADA UNA
ℇ | 8455 | 2107 |   | EULER CONSTANT
℈ | 8456 | 2108 |   | SCRUPLE
℉ | 8457 | 2109 |   | DEGREE FAHRENHEIT
ℊ | 8458 | 210A |   | SCRIPT SMALL G
ℋ | 8459 | 210B |   | SCRIPT CAPITAL H
ℌ | 8460 | 210C |   | BLACK-LETTER CAPITAL H
ℍ | 8461 | 210D |   | DOUBLE-STRUCK CAPITAL H
ℎ | 8462 | 210E |   | PLANCK CONSTANT
ℏ | 8463 | 210F |   | PLANCK CONSTANT OVER TWO PI
ℐ | 8464 | 2110 |   | SCRIPT CAPITAL I
ℑ | 8465 | 2111 | `&image;` | BLACK-LETTER CAPITAL I
ℒ | 8466 | 2112 |   | SCRIPT CAPITAL L
ℓ | 8467 | 2113 |   | SCRIPT SMALL L
℔ | 8468 | 2114 |   | L B BAR SYMBOL
ℕ | 8469 | 2115 |   | DOUBLE-STRUCK CAPITAL N
№ | 8470 | 2116 |   | NUMERO SIGN
℗ | 8471 | 2117 |   | SOUND RECORDING COPYRIGHT
℘ | 8472 | 2118 | `&weierp;` | SCRIPT CAPITAL P
ℙ | 8473 | 2119 |   | DOUBLE-STRUCK CAPITAL P
ℚ | 8474 | 211A |   | DOUBLE-STRUCK CAPITAL Q
ℛ | 8475 | 211B |   | SCRIPT CAPITAL R
ℜ | 8476 | 211C | `&real;` | BLACK-LETTER CAPITAL R
ℝ | 8477 | 211D |   | DOUBLE-STRUCK CAPITAL R
℞ | 8478 | 211E |   | PRESCRIPTION TAKE
℟ | 8479 | 211F |   | RESPONSE
℠ | 8480 | 2120 |   | SERVICE MARK
℡ | 8481 | 2121 |   | TELEPHONE SIGN
™ | 8482 | 2122 | `&trade;` | TRADE MARK SIGN
℣ | 8483 | 2123 |   | VERSICLE
ℤ | 8484 | 2124 |   | DOUBLE-STRUCK CAPITAL Z
℥ | 8485 | 2125 |   | OUNCE SIGN
Ω | 8486 | 2126 | `&ohm;` | OHM SIGN
℧ | 8487 | 2127 | `&mho;` | INVERTED OHM SIGN
ℨ | 8488 | 2128 |   | BLACK-LETTER CAPITAL Z
℩ | 8489 | 2129 |   | TURNED GREEK SMALL LETTER IOTA
K | 8490 | 212A |   | KELVIN SIGN
Å | 8491 | 212B |   | ANGSTROM SIGN
ℬ | 8492 | 212C |   | SCRIPT CAPITAL B
ℭ | 8493 | 212D |   | BLACK-LETTER CAPITAL C
℮ | 8494 | 212E |   | ESTIMATED SYMBOL
ℯ | 8495 | 212F |   | SCRIPT SMALL E
ℰ | 8496 | 2130 |   | SCRIPT CAPITAL E
ℱ | 8497 | 2131 |   | SCRIPT CAPITAL F
Ⅎ | 8498 | 2132 |   | TURNED CAPITAL F
ℳ | 8499 | 2133 |   | SCRIPT CAPITAL M
ℴ | 8500 | 2134 |   | SCRIPT SMALL O
ℵ | 8501 | 2135 | `&alefsym;` | ALEF SYMBOL
ℶ | 8502 | 2136 |   | BET SYMBOL
ℷ | 8503 | 2137 |   | GIMEL SYMBOL
ℸ | 8504 | 2138 |   | DALET SYMBOL
ℹ | 8505 | 2139 |   | INFORMATION SOURCE
℺ | 8506 | 213A |   | ROTATED CAPITAL Q
℻ | 8507 | 213B |   | FACSIMILE SIGN
ℼ | 8508 | 213C |   | DOUBLE-STRUCK SMALL PI
ℽ | 8509 | 213D |   | DOUBLE-STRUCK SMALL GAMMA
ℾ | 8510 | 213E |   | DOUBLE-STRUCK CAPITAL GAMMA
ℿ | 8511 | 213F |   | DOUBLE-STRUCK CAPITAL PI
⅀ | 8512 | 2140 |   | DOUBLE-STRUCK N-ARY SUMMATION
⅁ | 8513 | 2141 |   | TURNED SANS-SERIF CAPITAL G
⅂ | 8514 | 2142 |   | TURNED SANS-SERIF CAPITAL L
⅃ | 8515 | 2143 |   | REVERSED SANS-SERIF CAPITAL L
⅄ | 8516 | 2144 |   | TURNED SANS-SERIF CAPITAL Y
ⅅ | 8517 | 2145 |   | DOUBLE-STRUCK ITALIC CAPITAL D
ⅆ | 8518 | 2146 |   | DOUBLE-STRUCK ITALIC SMALL D
ⅇ | 8519 | 2147 |   | DOUBLE-STRUCK ITALIC SMALL E
ⅈ | 8520 | 2148 |   | DOUBLE-STRUCK ITALIC SMALL I
ⅉ | 8521 | 2149 |   | DOUBLE-STRUCK ITALIC SMALL J
⅊ | 8522 | 214A |   | PROPERTY LINE
⅋ | 8523 | 214B |   | TURNED AMPERSAND
⅌ | 8524 | 214C |   | PER SIGN
⅍ | 8525 | 214D |   | AKTIESELSKAB
ⅎ | 8526 | 214E |   | TURNED SMALL F
⅏ | 8527 | 214F |   | SYMBOL FOR SAMARITAN SOURCE

## Number Forms

Hex 2150-218B / Decimal 8528-8587.

Char | Dec | Hex | Entity | Name
--- | --- | --- | --- | ---
⅐ | 8528 | 2150 |  | VULGAR FRACTION ONE SEVENTH
⅑ | 8529 | 2151 |  | VULGAR FRACTION ONE NINTH
⅒ | 8530 | 2152 |  | VULGAR FRACTION ONE TENTH
⅓ | 8531 | 2153 | `&frac13;` | VULGAR FRACTION ONE THIRD
⅔ | 8532 | 2154 | `&frac23;` | VULGAR FRACTION TWO THIRDS
⅕ | 8533 | 2155 | `&frac15;` | VULGAR FRACTION ONE FIFTH
⅖ | 8534 | 2156 | `&frac25;` | VULGAR FRACTION TWO FIFTHS
⅗ | 8535 | 2157 | `&frac35;` | VULGAR FRACTION THREE FIFTHS
⅘ | 8536 | 2158 | `&frac45;` | VULGAR FRACTION FOUR FIFTHS
⅙ | 8537 | 2159 | `&frac16;` | VULGAR FRACTION ONE SIXTH
⅚ | 8538 | 215A | `&frac56;` | VULGAR FRACTION FIVE SIXTHS
⅛ | 8539 | 215B | `&frac18;` | VULGAR FRACTION ONE EIGHTH
⅜ | 8540 | 215C | `&frac38;` | VULGAR FRACTION THREE EIGHTHS
⅝ | 8541 | 215D | `&frac58;` | VULGAR FRACTION FIVE EIGHTHS
⅞ | 8542 | 215E | `&frac78;` | VULGAR FRACTION SEVEN EIGHTHS
⅟ | 8543 | 215F |  | FRACTION NUMERATOR ONE
Ⅰ | 8544 | 2160 |  | ROMAN NUMERAL ONE
Ⅱ | 8545 | 2161 |  | ROMAN NUMERAL TWO
Ⅲ | 8546 | 2162 |  | ROMAN NUMERAL THREE
Ⅳ | 8547 | 2163 |  | ROMAN NUMERAL FOUR
Ⅴ | 8548 | 2164 |  | ROMAN NUMERAL FIVE
Ⅵ | 8549 | 2165 |  | ROMAN NUMERAL SIX
Ⅶ | 8550 | 2166 |  | ROMAN NUMERAL SEVEN
Ⅷ | 8551 | 2167 |  | ROMAN NUMERAL EIGHT
Ⅸ | 8552 | 2168 |  | ROMAN NUMERAL NINE
Ⅹ | 8553 | 2169 |  | ROMAN NUMERAL TEN
Ⅺ | 8554 | 216A |  | ROMAN NUMERAL ELEVEN
Ⅻ | 8555 | 216B |  | ROMAN NUMERAL TWELVE
Ⅼ | 8556 | 216C |  | ROMAN NUMERAL FIFTY
Ⅽ | 8557 | 216D |  | ROMAN NUMERAL ONE HUNDRED
Ⅾ | 8558 | 216E |  | ROMAN NUMERAL FIVE HUNDRED
Ⅿ | 8559 | 216F |  | ROMAN NUMERAL ONE THOUSAND
ⅰ | 8560 | 2170 |  | SMALL ROMAN NUMERAL ONE
ⅱ | 8561 | 2171 |  | SMALL ROMAN NUMERAL TWO
ⅲ | 8562 | 2172 |  | SMALL ROMAN NUMERAL THREE
ⅳ | 8563 | 2173 |  | SMALL ROMAN NUMERAL FOUR
ⅴ | 8564 | 2174 |  | SMALL ROMAN NUMERAL FIVE
ⅵ | 8565 | 2175 |  | SMALL ROMAN NUMERAL SIX
ⅶ | 8566 | 2176 |  | SMALL ROMAN NUMERAL SEVEN
ⅷ | 8567 | 2177 |  | SMALL ROMAN NUMERAL EIGHT
ⅸ | 8568 | 2178 |  | SMALL ROMAN NUMERAL NINE
ⅹ | 8569 | 2179 |  | SMALL ROMAN NUMERAL TEN
ⅺ | 8570 | 217A |  | SMALL ROMAN NUMERAL ELEVEN
ⅻ | 8571 | 217B |  | SMALL ROMAN NUMERAL TWELVE
ⅼ | 8572 | 217C |  | SMALL ROMAN NUMERAL FIFTY
ⅽ | 8573 | 217D |  | SMALL ROMAN NUMERAL ONE HUNDRED
ⅾ | 8574 | 217E |  | SMALL ROMAN NUMERAL FIVE HUNDRED
ⅿ | 8575 | 217F |  | SMALL ROMAN NUMERAL ONE THOUSAND
ↀ | 8576 | 2180 |  | ROMAN NUMERAL ONE THOUSAND C D
ↁ | 8577 | 2181 |  | ROMAN NUMERAL FIVE THOUSAND
ↂ | 8578 | 2182 |  | ROMAN NUMERAL TEN THOUSAND
Ↄ | 8579 | 2183 |  | ROMAN NUMERAL REVERSED ONE HUNDRED
ↄ | 8580 | 2184 |  | LATIN SMALL LETTER REVERSED C
ↅ | 8581 | 2185 |  | ROMAN NUMERAL SIX LATE FORM
ↆ | 8582 | 2186 |  | ROMAN NUMERAL FIFTY EARLY FORM
ↇ | 8583 | 2187 |  | ROMAN NUMERAL FIFTY THOUSAND
ↈ | 8584 | 2188 |  | ROMAN NUMERAL ONE HUNDRED THOUSAND
↉ | 8585 | 2189 |  | VULGAR FRACTION ZERO THIRDS
↊ | 8586 | 218A |  | TURNED DIGIT TWO
↋ | 8587 | 218B |  | TURNED DIGIT THREE

## Arrows

Hex 2190-21FF / Decimal 8592-8703.

| Char | Dec  | Hex  | Entity    | Name                                                |
| ---- | ---- | ---- | --------- | --------------------------------------------------- |
| ←    | 8592 | 2190 | `&larr;`  | LEFTWARDS ARROW                                     |
| ↑    | 8593 | 2191 | `&uarr;`  | UPWARDS ARROW                                       |
| →    | 8594 | 2192 | `&rarr;`  | RIGHTWARDS ARROW                                    |
| ↓    | 8595 | 2193 | `&darr;`  | DOWNWARDS ARROW                                     |
| ↔    | 8596 | 2194 | `&harr;`  | LEFT RIGHT ARROW                                    |
| ↕    | 8597 | 2195 |           | UP DOWN ARROW                                       |
| ↖    | 8598 | 2196 |           | NORTH WEST ARROW                                    |
| ↗    | 8599 | 2197 |           | NORTH EAST ARROW                                    |
| ↘    | 8600 | 2198 |           | SOUTH EAST ARROW                                    |
| ↙    | 8601 | 2199 |           | SOUTH WEST ARROW                                    |
| ↚    | 8602 | 219A |           | LEFTWARDS ARROW WITH STROKE                         |
| ↛    | 8603 | 219B |           | RIGHTWARDS ARROW WITH STROKE                        |
| ↜    | 8604 | 219C |           | LEFTWARDS WAVE ARROW                                |
| ↝    | 8605 | 219D |           | RIGHTWARDS WAVE ARROW                               |
| ↞    | 8606 | 219E |           | LEFTWARDS TWO HEADED ARROW                          |
| ↟    | 8607 | 219F |           | UPWARDS TWO HEADED ARROW                            |
| ↠    | 8608 | 21A0 |           | RIGHTWARDS TWO HEADED ARROW                         |
| ↡    | 8609 | 21A1 |           | DOWNWARDS TWO HEADED ARROW                          |
| ↢    | 8610 | 21A2 |           | LEFTWARDS ARROW WITH TAIL                           |
| ↣    | 8611 | 21A3 |           | RIGHTWARDS ARROW WITH TAIL                          |
| ↤    | 8612 | 21A4 |           | LEFTWARDS ARROW FROM BAR                            |
| ↥    | 8613 | 21A5 |           | UPWARDS ARROW FROM BAR                              |
| ↦    | 8614 | 21A6 |           | RIGHTWARDS ARROW FROM BAR                           |
| ↧    | 8615 | 21A7 |           | DOWNWARDS ARROW FROM BAR                            |
| ↨    | 8616 | 21A8 |           | UP DOWN ARROW WITH BASE                             |
| ↩    | 8617 | 21A9 |           | LEFTWARDS ARROW WITH HOOK                           |
| ↪    | 8618 | 21AA |           | RIGHTWARDS ARROW WITH HOOK                          |
| ↫    | 8619 | 21AB |           | LEFTWARDS ARROW WITH LOOP                           |
| ↬    | 8620 | 21AC |           | RIGHTWARDS ARROW WITH LOOP                          |
| ↭    | 8621 | 21AD |           | LEFT RIGHT WAVE ARROW                               |
| ↮    | 8622 | 21AE |           | LEFT RIGHT ARROW WITH STROKE                        |
| ↯    | 8623 | 21AF |           | DOWNWARDS ZIGZAG ARROW                              |
| ↰    | 8624 | 21B0 |           | UPWARDS ARROW WITH TIP LEFTWARDS                    |
| ↱    | 8625 | 21B1 |           | UPWARDS ARROW WITH TIP RIGHTWARDS                   |
| ↲    | 8626 | 21B2 |           | DOWNWARDS ARROW WITH TIP LEFTWARDS                  |
| ↳    | 8627 | 21B3 |           | DOWNWARDS ARROW WITH TIP RIGHTWARDS                 |
| ↴    | 8628 | 21B4 |           | RIGHTWARDS ARROW WITH CORNER DOWNWARDS              |
| ↵    | 8629 | 21B5 | `&crarr;` | DOWNWARDS ARROW WITH CORNER LEFTWARDS               |
| ↶    | 8630 | 21B6 |           | ANTICLOCKWISE TOP SEMICIRCLE ARROW                  |
| ↷    | 8631 | 21B7 |           | CLOCKWISE TOP SEMICIRCLE ARROW                      |
| ↸    | 8632 | 21B8 |           | NORTH WEST ARROW TO LONG BAR                        |
| ↹    | 8633 | 21B9 |           | LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR |
| ↺    | 8634 | 21BA |           | ANTICLOCKWISE OPEN CIRCLE ARROW                     |
| ↻    | 8635 | 21BB |           | CLOCKWISE OPEN CIRCLE ARROW                         |
| ↼    | 8636 | 21BC |           | LEFTWARDS HARPOON WITH BARB UPWARDS                 |
| ↽    | 8637 | 21BD |           | LEFTWARDS HARPOON WITH BARB DOWNWARDS               |
| ↾    | 8638 | 21BE |           | UPWARDS HARPOON WITH BARB RIGHTWARDS                |
| ↿    | 8639 | 21BF |           | UPWARDS HARPOON WITH BARB LEFTWARDS                 |
| ⇀    | 8640 | 21C0 |           | RIGHTWARDS HARPOON WITH BARB UPWARDS                |
| ⇁    | 8641 | 21C1 |           | RIGHTWARDS HARPOON WITH BARB DOWNWARDS              |
| ⇂    | 8642 | 21C2 |           | DOWNWARDS HARPOON WITH BARB RIGHTWARDS              |
| ⇃    | 8643 | 21C3 |           | DOWNWARDS HARPOON WITH BARB LEFTWARDS               |
| ⇄    | 8644 | 21C4 |           | RIGHTWARDS ARROW OVER LEFTWARDS ARROW               |
| ⇅    | 8645 | 21C5 |           | UPWARDS ARROW LEFTWARDS OF DOWNWARDS ARROW          |
| ⇆    | 8646 | 21C6 |           | LEFTWARDS ARROW OVER RIGHTWARDS ARROW               |
| ⇇    | 8647 | 21C7 |           | LEFTWARDS PAIRED ARROWS                             |
| ⇈    | 8648 | 21C8 |           | UPWARDS PAIRED ARROWS                               |
| ⇉    | 8649 | 21C9 |           | RIGHTWARDS PAIRED ARROWS                            |
| ⇊    | 8650 | 21CA |           | DOWNWARDS PAIRED ARROWS                             |
| ⇋    | 8651 | 21CB |           | LEFTWARDS HARPOON OVER RIGHTWARDS HARPOON           |
| ⇌    | 8652 | 21CC |           | RIGHTWARDS HARPOON OVER LEFTWARDS HARPOON           |
| ⇍    | 8653 | 21CD |           | LEFTWARDS DOUBLE ARROW WITH STROKE                  |
| ⇎    | 8654 | 21CE |           | LEFT RIGHT DOUBLE ARROW WITH STROKE                 |
| ⇏    | 8655 | 21CF |           | RIGHTWARDS DOUBLE ARROW WITH STROKE                 |
| ⇐    | 8656 | 21D0 | `&lArr;`  | LEFTWARDS DOUBLE ARROW                              |
| ⇑    | 8657 | 21D1 | `&uArr;`  | UPWARDS DOUBLE ARROW                                |
| ⇒    | 8658 | 21D2 | `&rArr;`  | RIGHTWARDS DOUBLE ARROW                             |
| ⇓    | 8659 | 21D3 | `&dArr;`  | DOWNWARDS DOUBLE ARROW                              |
| ⇔    | 8660 | 21D4 | `&hArr;`  | LEFT RIGHT DOUBLE ARROW                             |
| ⇕    | 8661 | 21D5 |           | UP DOWN DOUBLE ARROW                                |
| ⇖    | 8662 | 21D6 |           | NORTH WEST DOUBLE ARROW                             |
| ⇗    | 8663 | 21D7 |           | NORTH EAST DOUBLE ARROW                             |
| ⇘    | 8664 | 21D8 |           | SOUTH EAST DOUBLE ARROW                             |
| ⇙    | 8665 | 21D9 |           | SOUTH WEST DOUBLE ARROW                             |
| ⇚    | 8666 | 21DA |           | LEFTWARDS TRIPLE ARROW                              |
| ⇛    | 8667 | 21DB |           | RIGHTWARDS TRIPLE ARROW                             |
| ⇜    | 8668 | 21DC |           | LEFTWARDS SQUIGGLE ARROW                            |
| ⇝    | 8669 | 21DD |           | RIGHTWARDS SQUIGGLE ARROW                           |
| ⇞    | 8670 | 21DE |           | UPWARDS ARROW WITH DOUBLE STROKE                    |
| ⇟    | 8671 | 21DF |           | DOWNWARDS ARROW WITH DOUBLE STROKE                  |
| ⇠    | 8672 | 21E0 |           | LEFTWARDS DASHED ARROW                              |
| ⇡    | 8673 | 21E1 |           | UPWARDS DASHED ARROW                                |
| ⇢    | 8674 | 21E2 |           | RIGHTWARDS DASHED ARROW                             |
| ⇣    | 8675 | 21E3 |           | DOWNWARDS DASHED ARROW                              |
| ⇤    | 8676 | 21E4 |           | LEFTWARDS ARROW TO BAR                              |
| ⇥    | 8677 | 21E5 |           | RIGHTWARDS ARROW TO BAR                             |
| ⇦    | 8678 | 21E6 |           | LEFTWARDS WHITE ARROW                               |
| ⇧    | 8679 | 21E7 |           | UPWARDS WHITE ARROW                                 |
| ⇨    | 8680 | 21E8 |           | RIGHTWARDS WHITE ARROW                              |
| ⇩    | 8681 | 21E9 |           | DOWNWARDS WHITE ARROW                               |
| ⇪    | 8682 | 21EA |           | UPWARDS WHITE ARROW FROM BAR                        |
| ⇫    | 8683 | 21EB |           | UPWARDS WHITE ARROW ON PEDESTAL                     |
| ⇬    | 8684 | 21EC |           | UPWARDS WHITE ARROW ON PEDESTAL WITH HORIZONTAL BAR |
| ⇭    | 8685 | 21ED |           | UPWARDS WHITE ARROW ON PEDESTAL WITH VERTICAL BAR   |
| ⇮    | 8686 | 21EE |           | UPWARDS WHITE DOUBLE ARROW                          |
| ⇯    | 8687 | 21EF |           | UPWARDS WHITE DOUBLE ARROW ON PEDESTAL              |
| ⇰    | 8688 | 21F0 |           | RIGHTWARDS WHITE ARROW FROM WALL                    |
| ⇱    | 8689 | 21F1 |           | NORTH WEST ARROW TO CORNER                          |
| ⇲    | 8690 | 21F2 |           | SOUTH EAST ARROW TO CORNER                          |
| ⇳    | 8691 | 21F3 |           | UP DOWN WHITE ARROW                                 |
| ⇴    | 8692 | 21F4 |           | RIGHT ARROW WITH SMALL CIRCLE                       |
| ⇵    | 8693 | 21F5 |           | DOWNWARDS ARROW LEFTWARDS OF UPWARDS ARROW          |
| ⇶    | 8694 | 21F6 |           | THREE RIGHTWARDS ARROWS                             |
| ⇷    | 8695 | 21F7 |           | LEFTWARDS ARROW WITH VERTICAL STROKE                |
| ⇸    | 8696 | 21F8 |           | RIGHTWARDS ARROW WITH VERTICAL STROKE               |
| ⇹    | 8697 | 21F9 |           | LEFT RIGHT ARROW WITH VERTICAL STROKE               |
| ⇺    | 8698 | 21FA |           | LEFTWARDS ARROW WITH DOUBLE VERTICAL STROKE         |
| ⇻    | 8699 | 21FB |           | RIGHTWARDS ARROW WITH DOUBLE VERTICAL STROKE        |
| ⇼    | 8700 | 21FC |           | LEFT RIGHT ARROW WITH DOUBLE VERTICAL STROKE        |
| ⇽    | 8701 | 21FD |           | LEFTWARDS OPEN-HEADED ARROW                         |
| ⇾    | 8702 | 21FE |           | RIGHTWARDS OPEN-HEADED ARROW                        |
| ⇿    | 8703 | 21FF |           | LEFT RIGHT OPEN-HEADED ARROW                        |

| Char | Dec  | Hex  | Entity    | Name                                  |
| ---- | ---- | ---- | --------- | ------------------------------------- |
| ←    | 8592 | 2190 | `&larr;`  | LEFTWARDS ARROW                       |
| ↑    | 8593 | 2191 | `&uarr;`  | UPWARDS ARROW                         |
| →    | 8594 | 2192 | `&rarr;`  | RIGHTWARDS ARROW                      |
| ↓    | 8595 | 2193 | `&darr;`  | DOWNWARDS ARROW                       |
| ↔    | 8596 | 2194 | `&harr;`  | LEFT RIGHT ARROW                      |
| ↵    | 8629 | 21B5 | `&crarr;` | DOWNWARDS ARROW WITH CORNER LEFTWARDS |
| ⇐    | 8656 | 21D0 | `&lArr;`  | LEFTWARDS DOUBLE ARROW                |
| ⇑    | 8657 | 21D1 | `&uArr;`  | UPWARDS DOUBLE ARROW                  |
| ⇒    | 8658 | 21D2 | `&rArr;`  | RIGHTWARDS DOUBLE ARROW               |
| ⇓    | 8659 | 21D3 | `&dArr;`  | DOWNWARDS DOUBLE ARROW                |
| ⇔    | 8660 | 21D4 | `&hArr;`  | LEFT RIGHT DOUBLE ARROW               |

### Supplemental Arrows A

Hex27F0-27FF / Dec 10224-10239.

Char | Dec | Hex | Name
--- | --- | --- | ---
⟰ | 10224 | 27F0 | 
⟱ | 10225 | 27F1 | 
⟲ | 10226 | 27F2 | 
⟳ | 10227 | 27F3 | 
⟴ | 10228 | 27F4 | 
⟵ | 10229 | 27F5 | 
⟶ | 10230 | 27F6 | 
⟷ | 10231 | 27F7 | 
⟸ | 10232 | 27F8 | 
⟹ | 10233 | 27F9 | 
⟺ | 10234 | 27FA | 
⟻ | 10235 | 27FB | 
⟼ | 10236 | 27FC | 
⟽ | 10237 | 27FD | 
⟾ | 10238 | 27FE | 
⟿ | 10239 | 27FF | 

### Supplemental Arrows B

Hex 2900-297F / Dec 10496-10623.

Char | Dec | Hex | Name
--- | --- | --- | ---
⤀ | 10496 | 2900 | 
⤁ | 10497 | 2901 | 
⤂ | 10498 | 2902 | 
⤃ | 10499 | 2903 | 
⤄ | 10500 | 2904 | 
⤅ | 10501 | 2905 | 
⤆ | 10502 | 2906 | 
⤇ | 10503 | 2907 | 
⤈ | 10504 | 2908 | 
⤉ | 10505 | 2909 | 
⤊ | 10506 | 290A | 
⤋ | 10507 | 290B | 
⤌ | 10508 | 290C | 
⤍ | 10509 | 290D | 
⤎ | 10510 | 290E | 
⤏ | 10511 | 290F | 
⤐ | 10512 | 2910 | 
⤑ | 10513 | 2911 | 
⤒ | 10514 | 2912 | 
⤓ | 10515 | 2913 | 
⤔ | 10516 | 2914 | 
⤕ | 10517 | 2915 | 
⤖ | 10518 | 2916 | 
⤗ | 10519 | 2917 | 
⤘ | 10520 | 2918 | 
⤙ | 10521 | 2919 | 
⤚ | 10522 | 291A | 
⤛ | 10523 | 291B | 
⤜ | 10524 | 291C | 
⤝ | 10525 | 291D | 
⤞ | 10526 | 291E | 
⤟ | 10527 | 291F | 
⤠ | 10528 | 2920 | 
⤡ | 10529 | 2921 | 
⤢ | 10530 | 2922 | 
⤣ | 10531 | 2923 | 
⤤ | 10532 | 2924 | 
⤥ | 10533 | 2925 | 
⤦ | 10534 | 2926 | 
⤧ | 10535 | 2927 | 
⤨ | 10536 | 2928 | 
⤩ | 10537 | 2929 | 
⤪ | 10538 | 292A | 
⤫ | 10539 | 292B | 
⤬ | 10540 | 292C | 
⤭ | 10541 | 292D | 
⤮ | 10542 | 292E | 
⤯ | 10543 | 292F | 
⤰ | 10544 | 2930 | 
⤱ | 10545 | 2931 | 
⤲ | 10546 | 2932 | 
⤳ | 10547 | 2933 | 
⤴ | 10548 | 2934 | 
⤵ | 10549 | 2935 | 
⤶ | 10550 | 2936 | 
⤷ | 10551 | 2937 | 
⤸ | 10552 | 2938 | 
⤹ | 10553 | 2939 | 
⤺ | 10554 | 293A | 
⤻ | 10555 | 293B | 
⤼ | 10556 | 293C | 
⤽ | 10557 | 293D | 
⤾ | 10558 | 293E | 
⤿ | 10559 | 293F | 
⥀ | 10560 | 2940 | 
⥁ | 10561 | 2941 | 
⥂ | 10562 | 2942 | 
⥃ | 10563 | 2943 | 
⥄ | 10564 | 2944 | 
⥅ | 10565 | 2945 | 
⥆ | 10566 | 2946 | 
⥇ | 10567 | 2947 | 
⥈ | 10568 | 2948 | 
⥉ | 10569 | 2949 | 
⥊ | 10570 | 294A | 
⥋ | 10571 | 294B | 
⥌ | 10572 | 294C | 
⥍ | 10573 | 294D | 
⥎ | 10574 | 294E | 
⥏ | 10575 | 294F | 
⥐ | 10576 | 2950 | 
⥑ | 10577 | 2951 | 
⥒ | 10578 | 2952 | 
⥓ | 10579 | 2953 | 
⥔ | 10580 | 2954 | 
⥕ | 10581 | 2955 | 
⥖ | 10582 | 2956 | 
⥗ | 10583 | 2957 | 
⥘ | 10584 | 2958 | 
⥙ | 10585 | 2959 | 
⥚ | 10586 | 295A | 
⥛ | 10587 | 295B | 
⥜ | 10588 | 295C | 
⥝ | 10589 | 295D | 
⥞ | 10590 | 295E | 
⥟ | 10591 | 295F | 
⥠ | 10592 | 2960 | 
⥡ | 10593 | 2961 | 
⥢ | 10594 | 2962 | 
⥣ | 10595 | 2963 | 
⥤ | 10596 | 2964 | 
⥥ | 10597 | 2965 | 
⥦ | 10598 | 2966 | 
⥧ | 10599 | 2967 | 
⥨ | 10600 | 2968 | 
⥩ | 10601 | 2969 | 
⥪ | 10602 | 296A | 
⥫ | 10603 | 296B | 
⥬ | 10604 | 296C | 
⥭ | 10605 | 296D | 
⥮ | 10606 | 296E | 
⥯ | 10607 | 296F | 
⥰ | 10608 | 2970 | 
⥱ | 10609 | 2971 | 
⥲ | 10610 | 2972 | 
⥳ | 10611 | 2973 | 
⥴ | 10612 | 2974 | 
⥵ | 10613 | 2975 | 
⥶ | 10614 | 2976 | 
⥷ | 10615 | 2977 | 
⥸ | 10616 | 2978 | 
⥹ | 10617 | 2979 | 
⥺ | 10618 | 297A | 
⥻ | 10619 | 297B | 
⥼ | 10620 | 297C | 
⥽ | 10621 | 297D | 
⥾ | 10622 | 297E | 
⥿ | 10623 | 297F | 

### Misc Symbols and Arrows

Hex 2B00-2BFF / Ddec 11008-11263.

Char | Dec | Hex
--- | --- | ---
⬀ | 11008 | 2B00
⬁ | 11009 | 2B01
⬂ | 11010 | 2B02
⬃ | 11011 | 2B03
⬄ | 11012 | 2B04
⬅ | 11013 | 2B05
⬆ | 11014 | 2B06
⬇ | 11015 | 2B07
⬈ | 11016 | 2B08
⬉ | 11017 | 2B09
⬊ | 11018 | 2B0A
⬋ | 11019 | 2B0B
⬌ | 11020 | 2B0C
⬍ | 11021 | 2B0D
⬎ | 11022 | 2B0E
⬏ | 11023 | 2B0F
⬐ | 11024 | 2B10
⬑ | 11025 | 2B11
⬒ | 11026 | 2B12
⬓ | 11027 | 2B13
⬔ | 11028 | 2B14
⬕ | 11029 | 2B15
⬖ | 11030 | 2B16
⬗ | 11031 | 2B17
⬘ | 11032 | 2B18
⬙ | 11033 | 2B19
⬚ | 11034 | 2B1A
⬛ | 11035 | 2B1B
⬜ | 11036 | 2B1C
⬝ | 11037 | 2B1D
⬞ | 11038 | 2B1E
⬟ | 11039 | 2B1F
⬠ | 11040 | 2B20
⬡ | 11041 | 2B21
⬢ | 11042 | 2B22
⬣ | 11043 | 2B23
⬤ | 11044 | 2B24
⬥ | 11045 | 2B25
⬦ | 11046 | 2B26
⬧ | 11047 | 2B27
⬨ | 11048 | 2B28
⬩ | 11049 | 2B29
⬪ | 11050 | 2B2A
⬫ | 11051 | 2B2B
⬬ | 11052 | 2B2C
⬭ | 11053 | 2B2D
⬮ | 11054 | 2B2E
⬯ | 11055 | 2B2F
⬰ | 11056 | 2B30
⬱ | 11057 | 2B31
⬲ | 11058 | 2B32
⬳ | 11059 | 2B33
⬴ | 11060 | 2B34
⬵ | 11061 | 2B35
⬶ | 11062 | 2B36
⬷ | 11063 | 2B37
⬸ | 11064 | 2B38
⬹ | 11065 | 2B39
⬺ | 11066 | 2B3A
⬻ | 11067 | 2B3B
⬼ | 11068 | 2B3C
⬽ | 11069 | 2B3D
⬾ | 11070 | 2B3E
⬿ | 11071 | 2B3F
⭀ | 11072 | 2B40
⭁ | 11073 | 2B41
⭂ | 11074 | 2B42
⭃ | 11075 | 2B43
⭄ | 11076 | 2B44
⭅ | 11077 | 2B45
⭆ | 11078 | 2B46
⭇ | 11079 | 2B47
⭈ | 11080 | 2B48
⭉ | 11081 | 2B49
⭊ | 11082 | 2B4A
⭋ | 11083 | 2B4B
⭌ | 11084 | 2B4C
⭍ | 11085 | 2B4D
⭎ | 11086 | 2B4E
⭏ | 11087 | 2B4F
⭐ | 11088 | 2B50
⭑ | 11089 | 2B51
⭒ | 11090 | 2B52
⭓ | 11091 | 2B53
⭔ | 11092 | 2B54
⭕ | 11093 | 2B55
⭖ | 11094 | 2B56
⭗ | 11095 | 2B57
⭘ | 11096 | 2B58
⭙ | 11097 | 2B59
⭚ | 11098 | 2B5A
⭛ | 11099 | 2B5B
⭜ | 11100 | 2B5C
⭝ | 11101 | 2B5D
⭞ | 11102 | 2B5E
⭟ | 11103 | 2B5F
⭠ | 11104 | 2B60
⭡ | 11105 | 2B61
⭢ | 11106 | 2B62
⭣ | 11107 | 2B63
⭤ | 11108 | 2B64
⭥ | 11109 | 2B65
⭦ | 11110 | 2B66
⭧ | 11111 | 2B67
⭨ | 11112 | 2B68
⭩ | 11113 | 2B69
⭪ | 11114 | 2B6A
⭫ | 11115 | 2B6B
⭬ | 11116 | 2B6C
⭭ | 11117 | 2B6D
⭮ | 11118 | 2B6E
⭯ | 11119 | 2B6F
⭰ | 11120 | 2B70
⭱ | 11121 | 2B71
⭲ | 11122 | 2B72
⭳ | 11123 | 2B73
⭴ | 11124 | 2B74
⭵ | 11125 | 2B75
⭶ | 11126 | 2B76
⭷ | 11127 | 2B77
⭸ | 11128 | 2B78
⭹ | 11129 | 2B79
⭺ | 11130 | 2B7A
⭻ | 11131 | 2B7B
⭼ | 11132 | 2B7C
⭽ | 11133 | 2B7D
⭾ | 11134 | 2B7E
⭿ | 11135 | 2B7F
⮀ | 11136 | 2B80
⮁ | 11137 | 2B81
⮂ | 11138 | 2B82
⮃ | 11139 | 2B83
⮄ | 11140 | 2B84
⮅ | 11141 | 2B85
⮆ | 11142 | 2B86
⮇ | 11143 | 2B87
⮈ | 11144 | 2B88
⮉ | 11145 | 2B89
⮊ | 11146 | 2B8A
⮋ | 11147 | 2B8B
⮌ | 11148 | 2B8C
⮍ | 11149 | 2B8D
⮎ | 11150 | 2B8E
⮏ | 11151 | 2B8F
⮐ | 11152 | 2B90
⮑ | 11153 | 2B91
⮒ | 11154 | 2B92
⮓ | 11155 | 2B93
⮔ | 11156 | 2B94
⮕ | 11157 | 2B95
⮖ | 11158 | 2B96
⮗ | 11159 | 2B97
⮘ | 11160 | 2B98
⮙ | 11161 | 2B99
⮚ | 11162 | 2B9A
⮛ | 11163 | 2B9B
⮜ | 11164 | 2B9C
⮝ | 11165 | 2B9D
⮞ | 11166 | 2B9E
⮟ | 11167 | 2B9F
⮠ | 11168 | 2BA0
⮡ | 11169 | 2BA1
⮢ | 11170 | 2BA2
⮣ | 11171 | 2BA3
⮤ | 11172 | 2BA4
⮥ | 11173 | 2BA5
⮦ | 11174 | 2BA6
⮧ | 11175 | 2BA7
⮨ | 11176 | 2BA8
⮩ | 11177 | 2BA9
⮪ | 11178 | 2BAA
⮫ | 11179 | 2BAB
⮬ | 11180 | 2BAC
⮭ | 11181 | 2BAD
⮮ | 11182 | 2BAE
⮯ | 11183 | 2BAF
⮰ | 11184 | 2BB0
⮱ | 11185 | 2BB1
⮲ | 11186 | 2BB2
⮳ | 11187 | 2BB3
⮴ | 11188 | 2BB4
⮵ | 11189 | 2BB5
⮶ | 11190 | 2BB6
⮷ | 11191 | 2BB7
⮸ | 11192 | 2BB8
⮹ | 11193 | 2BB9
⮺ | 11194 | 2BBA
⮻ | 11195 | 2BBB
⮼ | 11196 | 2BBC
⮽ | 11197 | 2BBD
⮾ | 11198 | 2BBE
⮿ | 11199 | 2BBF
⯀ | 11200 | 2BC0
⯁ | 11201 | 2BC1
⯂ | 11202 | 2BC2
⯃ | 11203 | 2BC3
⯄ | 11204 | 2BC4
⯅ | 11205 | 2BC5
⯆ | 11206 | 2BC6
⯇ | 11207 | 2BC7
⯈ | 11208 | 2BC8
⯉ | 11209 | 2BC9
⯊ | 11210 | 2BCA
⯋ | 11211 | 2BCB
⯌ | 11212 | 2BCC
⯍ | 11213 | 2BCD
⯎ | 11214 | 2BCE
⯏ | 11215 | 2BCF
⯐ | 11216 | 2BD0
⯑ | 11217 | 2BD1
⯒ | 11218 | 2BD2
⯓ | 11219 | 2BD3
⯔ | 11220 | 2BD4
⯕ | 11221 | 2BD5
⯖ | 11222 | 2BD6
⯗ | 11223 | 2BD7
⯘ | 11224 | 2BD8
⯙ | 11225 | 2BD9
⯚ | 11226 | 2BDA
⯛ | 11227 | 2BDB
⯜ | 11228 | 2BDC
⯝ | 11229 | 2BDD
⯞ | 11230 | 2BDE
⯟ | 11231 | 2BDF
⯠ | 11232 | 2BE0
⯡ | 11233 | 2BE1
⯢ | 11234 | 2BE2
⯣ | 11235 | 2BE3
⯤ | 11236 | 2BE4
⯥ | 11237 | 2BE5
⯦ | 11238 | 2BE6
⯧ | 11239 | 2BE7
⯨ | 11240 | 2BE8
⯩ | 11241 | 2BE9
⯪ | 11242 | 2BEA
⯫ | 11243 | 2BEB
⯬ | 11244 | 2BEC
⯭ | 11245 | 2BED
⯮ | 11246 | 2BEE
⯯ | 11247 | 2BEF
⯰ | 11248 | 2BF0
⯱ | 11249 | 2BF1
⯲ | 11250 | 2BF2
⯳ | 11251 | 2BF3
⯴ | 11252 | 2BF4
⯵ | 11253 | 2BF5
⯶ | 11254 | 2BF6
⯷ | 11255 | 2BF7
⯸ | 11256 | 2BF8
⯹ | 11257 | 2BF9
⯺ | 11258 | 2BFA
⯻ | 11259 | 2BFB
⯼ | 11260 | 2BFC
⯽ | 11261 | 2BFD
⯾ | 11262 | 2BFE
⯿ | 11263 | 2BFF

### Arrow Supplement

Hex 1F800-1F8FF / Dec 129024-129279.

#### Triangle Headed Arrows

Char | Dec | Hex
--- | --- | ---
🠀 | 129024 | 1F800
🠁 | 129025 | 1F801
🠂 | 129026 | 1F802
🠃 | 129027 | 1F803
🠄 | 129028 | 1F804
🠅 | 129029 | 1F805
🠆 | 129030 | 1F806
🠇 | 129031 | 1F807
🠈 | 129032 | 1F808
🠉 | 129033 | 1F809
🠊 | 129034 | 1F80A
🠋 | 129035 | 1F80B
🠌 | 129036 | 1F80C
🠍 | 129037 | 1F80D
🠎 | 129038 | 1F80E
🠏 | 129039 | 1F80F
🠐 | 129040 | 1F810
🠑 | 129041 | 1F811
🠒 | 129042 | 1F812
🠓 | 129043 | 1F813
🠔 | 129044 | 1F814
🠕 | 129045 | 1F815
🠖 | 129046 | 1F816
🠗 | 129047 | 1F817
🠘 | 129048 | 1F818
🠙 | 129049 | 1F819
🠚 | 129050 | 1F81A
🠛 | 129051 | 1F81B
🠜 | 129052 | 1F81C
🠝 | 129053 | 1F81D
🠞 | 129054 | 1F81E
🠟 | 129055 | 1F81F
🠠 | 129056 | 1F820
🠡 | 129057 | 1F821
🠢 | 129058 | 1F822
🠣 | 129059 | 1F823
🠤 | 129060 | 1F824
🠥 | 129061 | 1F825
🠦 | 129062 | 1F826
🠧 | 129063 | 1F827
🠨 | 129064 | 1F828
🠩 | 129065 | 1F829
🠪 | 129066 | 1F82A
🠫 | 129067 | 1F82B
🠬 | 129068 | 1F82C
🠭 | 129069 | 1F82D
🠮 | 129070 | 1F82E
🠯 | 129071 | 1F82F
🠰 | 129072 | 1F830
🠱 | 129073 | 1F831
🠲 | 129074 | 1F832
🠳 | 129075 | 1F833
#### Heavy Arrows

Char | Dec | Hex
--- | --- | ---
🠴 | 129076 | 1F834
🠵 | 129077 | 1F835
🠶 | 129078 | 1F836
🠷 | 129079 | 1F837
🠸 | 129080 | 1F838
🠹 | 129081 | 1F839
🠺 | 129082 | 1F83A
🠻 | 129083 | 1F83B
🠼 | 129084 | 1F83C
🠽 | 129085 | 1F83D
🠾 | 129086 | 1F83E
🠿 | 129087 | 1F83F
🡀 | 129088 | 1F840
🡁 | 129089 | 1F841
🡂 | 129090 | 1F842
🡃 | 129091 | 1F843
🡄 | 129092 | 1F844
🡅 | 129093 | 1F845
🡆 | 129094 | 1F846
🡇 | 129095 | 1F847
🡈 | 129096 | 1F848
🡉 | 129097 | 1F849
🡊 | 129098 | 1F84A
🡋 | 129099 | 1F84B
🡌 | 129100 | 1F84C
🡍 | 129101 | 1F84D
🡎 | 129102 | 1F84E
🡏 | 129103 | 1F84F

#### Sans-serif and Wide Head Arrows

Char | Dec | Hex
--- | --- | ---
🡐 | 129104 | 1F850
🡑 | 129105 | 1F851
🡒 | 129106 | 1F852
🡓 | 129107 | 1F853
🡔 | 129108 | 1F854
🡕 | 129109 | 1F855
🡖 | 129110 | 1F856
🡗 | 129111 | 1F857
🡘 | 129112 | 1F858
🡙 | 129113 | 1F859
🡚 | 129114 | 1F85A
🡛 | 129115 | 1F85B
🡜 | 129116 | 1F85C
🡝 | 129117 | 1F85D
🡞 | 129118 | 1F85E
🡟 | 129119 | 1F85F
🡠 | 129120 | 1F860
🡡 | 129121 | 1F861
🡢 | 129122 | 1F862
🡣 | 129123 | 1F863
🡤 | 129124 | 1F864
🡥 | 129125 | 1F865
🡦 | 129126 | 1F866
🡧 | 129127 | 1F867
🡨 | 129128 | 1F868
🡩 | 129129 | 1F869
🡪 | 129130 | 1F86A
🡫 | 129131 | 1F86B
🡬 | 129132 | 1F86C
🡭 | 129133 | 1F86D
🡮 | 129134 | 1F86E
🡯 | 129135 | 1F86F
🡰 | 129136 | 1F870
🡱 | 129137 | 1F871
🡲 | 129138 | 1F872
🡳 | 129139 | 1F873
🡴 | 129140 | 1F874
🡵 | 129141 | 1F875
🡶 | 129142 | 1F876
🡷 | 129143 | 1F877
🡸 | 129144 | 1F878
🡹 | 129145 | 1F879
🡺 | 129146 | 1F87A
🡻 | 129147 | 1F87B
🡼 | 129148 | 1F87C
🡽 | 129149 | 1F87D
🡾 | 129150 | 1F87E
🡿 | 129151 | 1F87F
🢀 | 129152 | 1F880
🢁 | 129153 | 1F881
🢂 | 129154 | 1F882
🢃 | 129155 | 1F883
🢄 | 129156 | 1F884
🢅 | 129157 | 1F885
🢆 | 129158 | 1F886
🢇 | 129159 | 1F887
🢈 | 129160 | 1F888
🢉 | 129161 | 1F889
🢊 | 129162 | 1F88A
🢋 | 129163 | 1F88B
🢌 | 129164 | 1F88C
🢍 | 129165 | 1F88D
🢎 | 129166 | 1F88E
🢏 | 129167 | 1F88F

#### Arrow Shafts and Heads

Char | Dec | Hex
--- | --- | ---
🢐 | 129168 | 1F890
🢑 | 129169 | 1F891
🢒 | 129170 | 1F892
🢓 | 129171 | 1F893
🢔 | 129172 | 1F894
🢕 | 129173 | 1F895
🢖 | 129174 | 1F896
🢗 | 129175 | 1F897
🢘 | 129176 | 1F898
🢙 | 129177 | 1F899
🢚 | 129178 | 1F89A
🢛 | 129179 | 1F89B
🢜 | 129180 | 1F89C
🢝 | 129181 | 1F89D
🢞 | 129182 | 1F89E
🢟 | 129183 | 1F89F

#### Shaded White Arrows

Char | Dec | Hex
--- | --- | ---
🢠 | 129184 | 1F8A0
🢡 | 129185 | 1F8A1
🢢 | 129186 | 1F8A2
🢣 | 129187 | 1F8A3
🢤 | 129188 | 1F8A4
🢥 | 129189 | 1F8A5
🢦 | 129190 | 1F8A6
🢧 | 129191 | 1F8A7
🢨 | 129192 | 1F8A8
🢩 | 129193 | 1F8A9
🢪 | 129194 | 1F8AA
🢫 | 129195 | 1F8AB
🢬 | 129196 | 1F8AC
🢭 | 129197 | 1F8AD

#### Not in Use
Char | Dec | Hex
--- | --- | ---
🢮 | 129198 | 1F8AE
🢯 | 129199 | 1F8AF
🢰 | 129200 | 1F8B0
🢱 | 129201 | 1F8B1
🢲 | 129202 | 1F8B2
🢳 | 129203 | 1F8B3
🢴 | 129204 | 1F8B4
🢵 | 129205 | 1F8B5
🢶 | 129206 | 1F8B6
🢷 | 129207 | 1F8B7
🢸 | 129208 | 1F8B8
🢹 | 129209 | 1F8B9
🢺 | 129210 | 1F8BA
🢻 | 129211 | 1F8BB
🢼 | 129212 | 1F8BC
🢽 | 129213 | 1F8BD
🢾 | 129214 | 1F8BE
🢿 | 129215 | 1F8BF
🣀 | 129216 | 1F8C0
🣁 | 129217 | 1F8C1
🣂 | 129218 | 1F8C2
🣃 | 129219 | 1F8C3
🣄 | 129220 | 1F8C4
🣅 | 129221 | 1F8C5
🣆 | 129222 | 1F8C6
🣇 | 129223 | 1F8C7
🣈 | 129224 | 1F8C8
🣉 | 129225 | 1F8C9
🣊 | 129226 | 1F8CA
🣋 | 129227 | 1F8CB
🣌 | 129228 | 1F8CC
🣍 | 129229 | 1F8CD
🣎 | 129230 | 1F8CE
🣏 | 129231 | 1F8CF
🣐 | 129232 | 1F8D0
🣑 | 129233 | 1F8D1
🣒 | 129234 | 1F8D2
🣓 | 129235 | 1F8D3
🣔 | 129236 | 1F8D4
🣕 | 129237 | 1F8D5
🣖 | 129238 | 1F8D6
🣗 | 129239 | 1F8D7
🣘 | 129240 | 1F8D8
🣙 | 129241 | 1F8D9
🣚 | 129242 | 1F8DA
🣛 | 129243 | 1F8DB
🣜 | 129244 | 1F8DC
🣝 | 129245 | 1F8DD
🣞 | 129246 | 1F8DE
🣟 | 129247 | 1F8DF
🣠 | 129248 | 1F8E0
🣡 | 129249 | 1F8E1
🣢 | 129250 | 1F8E2
🣣 | 129251 | 1F8E3
🣤 | 129252 | 1F8E4
🣥 | 129253 | 1F8E5
🣦 | 129254 | 1F8E6
🣧 | 129255 | 1F8E7
🣨 | 129256 | 1F8E8
🣩 | 129257 | 1F8E9
🣪 | 129258 | 1F8EA
🣫 | 129259 | 1F8EB
🣬 | 129260 | 1F8EC
🣭 | 129261 | 1F8ED
🣮 | 129262 | 1F8EE
🣯 | 129263 | 1F8EF
🣰 | 129264 | 1F8F0
🣱 | 129265 | 1F8F1
🣲 | 129266 | 1F8F2
🣳 | 129267 | 1F8F3
🣴 | 129268 | 1F8F4
🣵 | 129269 | 1F8F5
🣶 | 129270 | 1F8F6
🣷 | 129271 | 1F8F7
🣸 | 129272 | 1F8F8
🣹 | 129273 | 1F8F9
🣺 | 129274 | 1F8FA
🣻 | 129275 | 1F8FB
🣼 | 129276 | 1F8FC
🣽 | 129277 | 1F8FD
🣾 | 129278 | 1F8FE
🣿 | 129279 | 1F8FF

## Mathematical Operators

Hex 2200-22FF / Decimal 8704-8959.

Char | Dec | Hex | Entity | Name
--- | --- | --- | --- | ---
∀ | 8704 | 2200 | `&forall;` | FOR ALL
∁ | 8705 | 2201 |   | COMPLEMENT
∂ | 8706 | 2202 | `&part;` | PARTIAL DIFFERENTIAL
∃ | 8707 | 2203 | `&exist;` | THERE EXISTS
∄ | 8708 | 2204 |   | THERE DOES NOT EXIST
∅ | 8709 | 2205 | `&empty;` | EMPTY SET
∆ | 8710 | 2206 |   | INCREMENT
∇ | 8711 | 2207 | `&nabla;` | NABLA
∈ | 8712 | 2208 | `&isin;` | ELEMENT OF
∉ | 8713 | 2209 | `&notin;` | NOT AN ELEMENT OF
∊ | 8714 | 220A |   | SMALL ELEMENT OF
∋ | 8715 | 220B | `&ni;` | CONTAINS AS MEMBER
∌ | 8716 | 220C |   | DOES NOT CONTAIN AS MEMBER
∍ | 8717 | 220D |   | SMALL CONTAINS AS MEMBER
∎ | 8718 | 220E |   | END OF PROOF
∏ | 8719 | 220F | `&prod;` | N-ARY PRODUCT
∐ | 8720 | 2210 |   | N-ARY COPRODUCT
∑ | 8721 | 2211 | `&sum;` | N-ARY SUMMATION
− | 8722 | 2212 | `&minus;` | MINUS SIGN
∓ | 8723 | 2213 |   | MINUS-OR-PLUS SIGN
∔ | 8724 | 2214 |   | DOT PLUS
∕ | 8725 | 2215 |   | DIVISION SLASH
∖ | 8726 | 2216 |   | SET MINUS
∗ | 8727 | 2217 | `&lowast;` | ASTERISK OPERATOR
∘ | 8728 | 2218 |   | RING OPERATOR
∙ | 8729 | 2219 |   | BULLET OPERATOR
√ | 8730 | 221A | `&radic;` | SQUARE ROOT
∛ | 8731 | 221B |   | CUBE ROOT
∜ | 8732 | 221C |   | FOURTH ROOT
∝ | 8733 | 221D | `&prop;` | PROPORTIONAL TO
∞ | 8734 | 221E | `&infin;` | INFINITY
∟ | 8735 | 221F |   | RIGHT ANGLE
∠ | 8736 | 2220 | `&ang;` | ANGLE
∡ | 8737 | 2221 |   | MEASURED ANGLE
∢ | 8738 | 2222 |   | SPHERICAL ANGLE
∣ | 8739 | 2223 |   | DIVIDES
∤ | 8740 | 2224 |   | DOES NOT DIVIDE
∥ | 8741 | 2225 |   | PARALLEL TO
∦ | 8742 | 2226 |   | NOT PARALLEL TO
∧ | 8743 | 2227 | `&and;` | LOGICAL AND
∨ | 8744 | 2228 | `&or;` | LOGICAL OR
∩ | 8745 | 2229 | `&cap;` | INTERSECTION
∪ | 8746 | 222A | `&cup;` | UNION
∫ | 8747 | 222B | `&int;` | INTEGRAL
∬ | 8748 | 222C |   | DOUBLE INTEGRAL
∭ | 8749 | 222D |   | TRIPLE INTEGRAL
∮ | 8750 | 222E |   | CONTOUR INTEGRAL
∯ | 8751 | 222F |   | SURFACE INTEGRAL
∰ | 8752 | 2230 |   | VOLUME INTEGRAL
∱ | 8753 | 2231 |   | CLOCKWISE INTEGRAL
∲ | 8754 | 2232 |   | CLOCKWISE CONTOUR INTEGRAL
∳ | 8755 | 2233 |   | ANTICLOCKWISE CONTOUR INTEGRAL
∴ | 8756 | 2234 | `&there4;` | THEREFORE
∵ | 8757 | 2235 |   | BECAUSE
∶ | 8758 | 2236 |   | RATIO
∷ | 8759 | 2237 |   | PROPORTION
∸ | 8760 | 2238 |   | DOT MINUS
∹ | 8761 | 2239 |   | EXCESS
∺ | 8762 | 223A |   | GEOMETRIC PROPORTION
∻ | 8763 | 223B |   | HOMOTHETIC
∼ | 8764 | 223C | `&sim;` | TILDE OPERATOR
∽ | 8765 | 223D |   | REVERSED TILDE
∾ | 8766 | 223E |   | INVERTED LAZY S
∿ | 8767 | 223F |   | SINE WAVE
≀ | 8768 | 2240 |   | WREATH PRODUCT
≁ | 8769 | 2241 |   | NOT TILDE
≂ | 8770 | 2242 |   | MINUS TILDE
≃ | 8771 | 2243 |   | ASYMPTOTICALLY EQUAL TO
≄ | 8772 | 2244 |   | NOT ASYMPTOTICALLY EQUAL TO
≅ | 8773 | 2245 | `&cong;` | APPROXIMATELY EQUAL TO
≆ | 8774 | 2246 |   | APPROXIMATELY BUT NOT ACTUALLY EQUAL TO
≇ | 8775 | 2247 |   | NEITHER APPROXIMATELY NOR ACTUALLY EQUAL TO
≈ | 8776 | 2248 | `&asymp;` | ALMOST EQUAL TO
≉ | 8777 | 2249 |   | NOT ALMOST EQUAL TO
≊ | 8778 | 224A |   | ALMOST EQUAL OR EQUAL TO
≋ | 8779 | 224B |   | TRIPLE TILDE
≌ | 8780 | 224C |   | ALL EQUAL TO
≍ | 8781 | 224D |   | EQUIVALENT TO
≎ | 8782 | 224E |   | GEOMETRICALLY EQUIVALENT TO
≏ | 8783 | 224F |   | DIFFERENCE BETWEEN
≐ | 8784 | 2250 |   | APPROACHES THE LIMIT
≑ | 8785 | 2251 |   | GEOMETRICALLY EQUAL TO
≒ | 8786 | 2252 |   | APPROXIMATELY EQUAL TO OR THE IMAGE OF
≓ | 8787 | 2253 |   | IMAGE OF OR APPROXIMATELY EQUAL TO
≔ | 8788 | 2254 |   | COLON EQUALS
≕ | 8789 | 2255 |   | EQUALS COLON
≖ | 8790 | 2256 |   | RING IN EQUAL TO
≗ | 8791 | 2257 |   | RING EQUAL TO
≘ | 8792 | 2258 |   | CORRESPONDS TO
≙ | 8793 | 2259 |   | ESTIMATES
≚ | 8794 | 225A |   | EQUIANGULAR TO
≛ | 8795 | 225B |   | STAR EQUALS
≜ | 8796 | 225C |   | DELTA EQUAL TO
≝ | 8797 | 225D |   | EQUAL TO BY DEFINITION
≞ | 8798 | 225E |   | MEASURED BY
≟ | 8799 | 225F |   | QUESTIONED EQUAL TO
≠ | 8800 | 2260 | `&ne;` | NOT EQUAL TO
≡ | 8801 | 2261 | `&equiv;` | IDENTICAL TO
≢ | 8802 | 2262 |   | NOT IDENTICAL TO
≣ | 8803 | 2263 |   | STRICTLY EQUIVALENT TO
≤ | 8804 | 2264 | `&le;` | LESS-THAN OR EQUAL TO
≥ | 8805 | 2265 | `&ge;` | GREATER-THAN OR EQUAL TO
≦ | 8806 | 2266 |   | LESS-THAN OVER EQUAL TO
≧ | 8807 | 2267 |   | GREATER-THAN OVER EQUAL TO
≨ | 8808 | 2268 |   | LESS-THAN BUT NOT EQUAL TO
≩ | 8809 | 2269 |   | GREATER-THAN BUT NOT EQUAL TO
≪ | 8810 | 226A |   | MUCH LESS-THAN
≫ | 8811 | 226B |   | MUCH GREATER-THAN
≬ | 8812 | 226C |   | BETWEEN
≭ | 8813 | 226D |   | NOT EQUIVALENT TO
≮ | 8814 | 226E |   | NOT LESS-THAN
≯ | 8815 | 226F |   | NOT GREATER-THAN
≰ | 8816 | 2270 |   | NEITHER LESS-THAN NOR EQUAL TO
≱ | 8817 | 2271 |   | NEITHER GREATER-THAN NOR EQUAL TO
≲ | 8818 | 2272 |   | LESS-THAN OR EQUIVALENT TO
≳ | 8819 | 2273 |   | GREATER-THAN OR EQUIVALENT TO
≴ | 8820 | 2274 |   | NEITHER LESS-THAN NOR EQUIVALENT TO
≵ | 8821 | 2275 |   | NEITHER GREATER-THAN NOR EQUIVALENT TO
≶ | 8822 | 2276 |   | LESS-THAN OR GREATER-THAN
≷ | 8823 | 2277 |   | GREATER-THAN OR LESS-THAN
≸ | 8824 | 2278 |   | NEITHER LESS-THAN NOR GREATER-THAN
≹ | 8825 | 2279 |   | NEITHER GREATER-THAN NOR LESS-THAN
≺ | 8826 | 227A |   | PRECEDES
≻ | 8827 | 227B |   | SUCCEEDS
≼ | 8828 | 227C |   | PRECEDES OR EQUAL TO
≽ | 8829 | 227D |   | SUCCEEDS OR EQUAL TO
≾ | 8830 | 227E |   | PRECEDES OR EQUIVALENT TO
≿ | 8831 | 227F |   | SUCCEEDS OR EQUIVALENT TO
⊀ | 8832 | 2280 |   | DOES NOT PRECEDE
⊁ | 8833 | 2281 |   | DOES NOT SUCCEED
⊂ | 8834 | 2282 | `&sub;` | SUBSET OF
⊃ | 8835 | 2283 | `&sup;` | SUPERSET OF
⊄ | 8836 | 2284 | `&nsub;` | NOT A SUBSET OF
⊅ | 8837 | 2285 |   | NOT A SUPERSET OF
⊆ | 8838 | 2286 | `&sube;` | SUBSET OF OR EQUAL TO
⊇ | 8839 | 2287 | `&supe;` | SUPERSET OF OR EQUAL TO
⊈ | 8840 | 2288 |   | NEITHER A SUBSET OF NOR EQUAL TO
⊉ | 8841 | 2289 |   | NEITHER A SUPERSET OF NOR EQUAL TO
⊊ | 8842 | 228A |   | SUBSET OF WITH NOT EQUAL TO
⊋ | 8843 | 228B |   | SUPERSET OF WITH NOT EQUAL TO
⊌ | 8844 | 228C |   | MULTISET
⊍ | 8845 | 228D |   | MULTISET MULTIPLICATION
⊎ | 8846 | 228E |   | MULTISET UNION
⊏ | 8847 | 228F |   | SQUARE IMAGE OF
⊐ | 8848 | 2290 |   | SQUARE ORIGINAL OF
⊑ | 8849 | 2291 |   | SQUARE IMAGE OF OR EQUAL TO
⊒ | 8850 | 2292 |   | SQUARE ORIGINAL OF OR EQUAL TO
⊓ | 8851 | 2293 |   | SQUARE CAP
⊔ | 8852 | 2294 |   | SQUARE CUP
⊕ | 8853 | 2295 | `&oplus;` | CIRCLED PLUS
⊖ | 8854 | 2296 |   | CIRCLED MINUS
⊗ | 8855 | 2297 | `&otimes;` | CIRCLED TIMES
⊘ | 8856 | 2298 |   | CIRCLED DIVISION SLASH
⊙ | 8857 | 2299 |   | CIRCLED DOT OPERATOR
⊚ | 8858 | 229A |   | CIRCLED RING OPERATOR
⊛ | 8859 | 229B |   | CIRCLED ASTERISK OPERATOR
⊜ | 8860 | 229C |   | CIRCLED EQUALS
⊝ | 8861 | 229D |   | CIRCLED DASH
⊞ | 8862 | 229E |   | SQUARED PLUS
⊟ | 8863 | 229F |   | SQUARED MINUS
⊠ | 8864 | 22A0 |   | SQUARED TIMES
⊡ | 8865 | 22A1 |   | SQUARED DOT OPERATOR
⊢ | 8866 | 22A2 |   | RIGHT TACK
⊣ | 8867 | 22A3 |   | LEFT TACK
⊤ | 8868 | 22A4 |   | DOWN TACK
⊥ | 8869 | 22A5 | `&perp;` | UP TACK
⊦ | 8870 | 22A6 |   | ASSERTION
⊧ | 8871 | 22A7 |   | MODELS
⊨ | 8872 | 22A8 |   | TRUE
⊩ | 8873 | 22A9 |   | FORCES
⊪ | 8874 | 22AA |   | TRIPLE VERTICAL BAR RIGHT TURNSTILE
⊫ | 8875 | 22AB |   | DOUBLE VERTICAL BAR DOUBLE RIGHT TURNSTILE
⊬ | 8876 | 22AC |   | DOES NOT PROVE
⊭ | 8877 | 22AD |   | NOT TRUE
⊮ | 8878 | 22AE |   | DOES NOT FORCE
⊯ | 8879 | 22AF |   | NEGATED DOUBLE VERTICAL BAR DOUBLE RIGHT TURNSTILE
⊰ | 8880 | 22B0 |   | PRECEDES UNDER RELATION
⊱ | 8881 | 22B1 |   | SUCCEEDS UNDER RELATION
⊲ | 8882 | 22B2 |   | NORMAL SUBGROUP OF
⊳ | 8883 | 22B3 |   | CONTAINS AS NORMAL SUBGROUP
⊴ | 8884 | 22B4 |   | NORMAL SUBGROUP OF OR EQUAL TO
⊵ | 8885 | 22B5 |   | CONTAINS AS NORMAL SUBGROUP OR EQUAL TO
⊶ | 8886 | 22B6 |   | ORIGINAL OF
⊷ | 8887 | 22B7 |   | IMAGE OF
⊸ | 8888 | 22B8 |   | MULTIMAP
⊹ | 8889 | 22B9 |   | HERMITIAN CONJUGATE MATRIX
⊺ | 8890 | 22BA |   | INTERCALATE
⊻ | 8891 | 22BB |   | XOR
⊼ | 8892 | 22BC |   | NAND
⊽ | 8893 | 22BD |   | NOR
⊾ | 8894 | 22BE |   | RIGHT ANGLE WITH ARC
⊿ | 8895 | 22BF |   | RIGHT TRIANGLE
⋀ | 8896 | 22C0 |   | N-ARY LOGICAL AND
⋁ | 8897 | 22C1 |   | N-ARY LOGICAL OR
⋂ | 8898 | 22C2 |   | N-ARY INTERSECTION
⋃ | 8899 | 22C3 |   | N-ARY UNION
⋄ | 8900 | 22C4 |   | DIAMOND OPERATOR
⋅ | 8901 | 22C5 | `&sdot;` | DOT OPERATOR
⋆ | 8902 | 22C6 |   | STAR OPERATOR
⋇ | 8903 | 22C7 |   | DIVISION TIMES
⋈ | 8904 | 22C8 |   | BOWTIE
⋉ | 8905 | 22C9 |   | LEFT NORMAL FACTOR SEMIDIRECT PRODUCT
⋊ | 8906 | 22CA |   | RIGHT NORMAL FACTOR SEMIDIRECT PRODUCT
⋋ | 8907 | 22CB |   | LEFT SEMIDIRECT PRODUCT
⋌ | 8908 | 22CC |   | RIGHT SEMIDIRECT PRODUCT
⋍ | 8909 | 22CD |   | REVERSED TILDE EQUALS
⋎ | 8910 | 22CE |   | CURLY LOGICAL OR
⋏ | 8911 | 22CF |   | CURLY LOGICAL AND
⋐ | 8912 | 22D0 |   | DOUBLE SUBSET
⋑ | 8913 | 22D1 |   | DOUBLE SUPERSET
⋒ | 8914 | 22D2 |   | DOUBLE INTERSECTION
⋓ | 8915 | 22D3 |   | DOUBLE UNION
⋔ | 8916 | 22D4 |   | PITCHFORK
⋕ | 8917 | 22D5 |   | EQUAL AND PARALLEL TO
⋖ | 8918 | 22D6 |   | LESS-THAN WITH DOT
⋗ | 8919 | 22D7 |   | GREATER-THAN WITH DOT
⋘ | 8920 | 22D8 |   | VERY MUCH LESS-THAN
⋙ | 8921 | 22D9 |   | VERY MUCH GREATER-THAN
⋚ | 8922 | 22DA |   | LESS-THAN EQUAL TO OR GREATER-THAN
⋛ | 8923 | 22DB |   | GREATER-THAN EQUAL TO OR LESS-THAN
⋜ | 8924 | 22DC |   | EQUAL TO OR LESS-THAN
⋝ | 8925 | 22DD |   | EQUAL TO OR GREATER-THAN
⋞ | 8926 | 22DE |   | EQUAL TO OR PRECEDES
⋟ | 8927 | 22DF |   | EQUAL TO OR SUCCEEDS
⋠ | 8928 | 22E0 |   | DOES NOT PRECEDE OR EQUAL
⋡ | 8929 | 22E1 |   | DOES NOT SUCCEED OR EQUAL
⋢ | 8930 | 22E2 |   | NOT SQUARE IMAGE OF OR EQUAL TO
⋣ | 8931 | 22E3 |   | NOT SQUARE ORIGINAL OF OR EQUAL TO
⋤ | 8932 | 22E4 |   | SQUARE IMAGE OF OR NOT EQUAL TO
⋥ | 8933 | 22E5 |   | SQUARE ORIGINAL OF OR NOT EQUAL TO
⋦ | 8934 | 22E6 |   | LESS-THAN BUT NOT EQUIVALENT TO
⋧ | 8935 | 22E7 |   | GREATER-THAN BUT NOT EQUIVALENT TO
⋨ | 8936 | 22E8 |   | PRECEDES BUT NOT EQUIVALENT TO
⋩ | 8937 | 22E9 |   | SUCCEEDS BUT NOT EQUIVALENT TO
⋪ | 8938 | 22EA |   | NOT NORMAL SUBGROUP OF
⋫ | 8939 | 22EB |   | DOES NOT CONTAIN AS NORMAL SUBGROUP
⋬ | 8940 | 22EC |   | NOT NORMAL SUBGROUP OF OR EQUAL TO
⋭ | 8941 | 22ED |   | DOES NOT CONTAIN AS NORMAL SUBGROUP OR EQUAL
⋮ | 8942 | 22EE |   | VERTICAL ELLIPSIS
⋯ | 8943 | 22EF |   | MIDLINE HORIZONTAL ELLIPSIS
⋰ | 8944 | 22F0 |   | UP RIGHT DIAGONAL ELLIPSIS
⋱ | 8945 | 22F1 |   | DOWN RIGHT DIAGONAL ELLIPSIS
⋲ | 8946 | 22F2 |   | ELEMENT OF WITH LONG HORIZONTAL STROKE
⋳ | 8947 | 22F3 |   | ELEMENT OF WITH VERTICAL BAR AT END OF HORIZONTAL STROKE
⋴ | 8948 | 22F4 |   | SMALL ELEMENT OF WITH VERTICAL BAR AT END OF HORIZONTAL STROKE
⋵ | 8949 | 22F5 |   | ELEMENT OF WITH DOT ABOVE
⋶ | 8950 | 22F6 |   | ELEMENT OF WITH OVERBAR
⋷ | 8951 | 22F7 |   | SMALL ELEMENT OF WITH OVERBAR
⋸ | 8952 | 22F8 |   | ELEMENT OF WITH UNDERBAR
⋹ | 8953 | 22F9 |   | ELEMENT OF WITH TWO HORIZONTAL STROKES
⋺ | 8954 | 22FA |   | CONTAINS WITH LONG HORIZONTAL STROKE
⋻ | 8955 | 22FB |   | CONTAINS WITH VERTICAL BAR AT END OF HORIZONTAL STROKE
⋼ | 8956 | 22FC |   | SMALL CONTAINS WITH VERTICAL BAR AT END OF HORIZONTAL STROKE
⋽ | 8957 | 22FD |   | CONTAINS WITH OVERBAR
⋾ | 8958 | 22FE |   | SMALL CONTAINS WITH OVERBAR
⋿ | 8959 | 22FF |   | Z NOTATION BAG MEMBERSHIP

### UTF-8 Math Symbols A

Hex 27C0-27EF / Decimal 10176-10223.

Char | Dec | Hex | Name
--- | --- | --- | ---
⟀ | 10176 | 27C0 | THREE DIMENSIONAL ANGLE
⟁ | 10177 | 27C1 | WHITE TRIANGLE CONTAINING SMALL WHITE TRIANGLE
⟂ | 10178 | 27C2 | PERPENDICULAR
⟃ | 10179 | 27C3 | OPEN SUBSET
⟄ | 10180 | 27C4 | OPEN SUPERSET
⟅ | 10181 | 27C5 | LEFT S-SHAPED BAG DELIMITER
⟆ | 10182 | 27C6 | RIGHT S-SHAPED BAG DELIMITER
⟇ | 10183 | 27C7 | OR WITH DOT INSIDE
⟈ | 10184 | 27C8 | REVERSE SOLIDUS PRECEDING SUBSET
⟉ | 10185 | 27C9 | SUPERSET PRECEDING SOLIDUS
⟊ | 10186 | 27CA | VERTICAL BAR WITH HORIZONTAL STROKE
⟋ | 10187 | 27CB | MATHEMATICAL RISING DIAGONAL
⟌ | 10188 | 27CC | LONG DIVISION
⟍ | 10189 | 27CD | MATHEMATICAL FALLING DIAGONAL
⟎ | 10190 | 27CE | SQUARED LOGICAL AND
⟏ | 10191 | 27CF | SQUARED LOGICAL OR
⟐ | 10192 | 27D0 | WHITE DIAMOND WITH CENTRED DOT
⟑ | 10193 | 27D1 | AND WITH DOT
⟒ | 10194 | 27D2 | ELEMENT OF OPENING UPWARDS
⟓ | 10195 | 27D3 | LOWER RIGHT CORNER WITH DOT
⟔ | 10196 | 27D4 | UPPER LEFT CORNER WITH DOT
⟕ | 10197 | 27D5 | LEFT OUTER JOIN
⟖ | 10198 | 27D6 | RIGHT OUTER JOIN
⟗ | 10199 | 27D7 | FULL OUTER JOIN
⟘ | 10200 | 27D8 | LARGE UP TACK
⟙ | 10201 | 27D9 | LARGE DOWN TACK
⟚ | 10202 | 27DA | LEFT AND RIGHT DOUBLE TURNSTILE
⟛ | 10203 | 27DB | LEFT AND RIGHT TACK
⟜ | 10204 | 27DC | LEFT MULTIMAP
⟝ | 10205 | 27DD | LONG RIGHT TACK
⟞ | 10206 | 27DE | LONG LEFT TACK
⟟ | 10207 | 27DF | UP TACK WITH CIRCLE ABOVE
⟠ | 10208 | 27E0 | LOZENGE DIVIDED BY HORIZONTAL RULE
⟡ | 10209 | 27E1 | WHITE CONCAVE-SIDED DIAMOND
⟢ | 10210 | 27E2 | WHITE CONCAVE-SIDED DIAMOND WITH LEFTWARDS TICK
⟣ | 10211 | 27E3 | WHITE CONCAVE-SIDED DIAMOND WITH RIGHTWARDS TICK
⟤ | 10212 | 27E4 | WHITE SQUARE WITH LEFTWARDS TICK
⟥ | 10213 | 27E5 | WHITE SQUARE WITH RIGHTWARDS TICK
⟦ | 10214 | 27E6 | MATHEMATICAL LEFT WHITE SQUARE BRACKET
⟧ | 10215 | 27E7 | MATHEMATICAL RIGHT WHITE SQUARE BRACKET
⟨ | 10216 | 27E8 | MATHEMATICAL LEFT ANGLE BRACKET
⟩ | 10217 | 27E9 | MATHEMATICAL RIGHT ANGLE BRACKET
⟪ | 10218 | 27EA | MATHEMATICAL LEFT DOUBLE ANGLE BRACKET
⟫ | 10219 | 27EB | MATHEMATICAL RIGHT DOUBLE ANGLE BRACKET
⟬ | 10220 | 27EC | MATHEMATICAL LEFT WHITE TORTOISE SHELL BRACKET
⟭ | 10221 | 27ED | MATHEMATICAL RIGHT WHITE TORTOISE SHELL BRACKET
⟮ | 10222 | 27EE | MATHEMATICAL LEFT FLATTENED PARENTHESIS
⟯ | 10223 | 27EF | MATHEMATICAL RIGHT FLATTENED PARENTHESIS

### UTF-8 Math Symbols B

Hex 2980-29FF / Decimal 10624-10751.

Char | Dec | Hex | Name
--- | --- | --- | ---
⦀ | 10624 | 2980 | TRIPLE VERTICAL BAR DELIMITER
⦁ | 10625 | 2981 | Z NOTATION SPOT
⦂ | 10626 | 2982 | Z NOTATION TYPE COLON
⦃ | 10627 | 2983 | LEFT WHITE CURLY BRACKET
⦄ | 10628 | 2984 | RIGHT WHITE CURLY BRACKET
⦅ | 10629 | 2985 | LEFT WHITE PARENTHESIS
⦆ | 10630 | 2986 | RIGHT WHITE PARENTHESIS
⦇ | 10631 | 2987 | Z NOTATION LEFT IMAGE BRACKET
⦈ | 10632 | 2988 | Z NOTATION RIGHT IMAGE BRACKET
⦉ | 10633 | 2989 | Z NOTATION LEFT BINDING BRACKET
⦊ | 10634 | 298A | Z NOTATION RIGHT BINDING BRACKET
⦋ | 10635 | 298B | LEFT SQUARE BRACKET WITH UNDERBAR
⦌ | 10636 | 298C | RIGHT SQUARE BRACKET WITH UNDERBAR
⦍ | 10637 | 298D | LEFT SQUARE BRACKET WITH TICK IN TOP CORNER
⦎ | 10638 | 298E | RIGHT SQUARE BRACKET WITH TICK IN BOTTOM CORNER
⦏ | 10639 | 298F | LEFT SQUARE BRACKET WITH TICK IN BOTTOM CORNER
⦐ | 10640 | 2990 | RIGHT SQUARE BRACKET WITH TICK IN TOP CORNER
⦑ | 10641 | 2991 | LEFT ANGLE BRACKET WITH DOT
⦒ | 10642 | 2992 | RIGHT ANGLE BRACKET WITH DOT
⦓ | 10643 | 2993 | LEFT ARC LESS-THAN BRACKET
⦔ | 10644 | 2994 | RIGHT ARC GREATER-THAN BRACKET
⦕ | 10645 | 2995 | DOUBLE LEFT ARC GREATER-THAN BRACKET
⦖ | 10646 | 2996 | DOUBLE RIGHT ARC LESS-THAN BRACKET
⦗ | 10647 | 2997 | LEFT BLACK TORTOISE SHELL BRACKET
⦘ | 10648 | 2998 | RIGHT BLACK TORTOISE SHELL BRACKET
⦙ | 10649 | 2999 | DOTTED FENCE
⦚ | 10650 | 299A | VERTICAL ZIGZAG LINE
⦛ | 10651 | 299B | MEASURED ANGLE OPENING LEFT
⦜ | 10652 | 299C | RIGHT ANGLE VARIANT WITH SQUARE
⦝ | 10653 | 299D | MEASURED RIGHT ANGLE WITH DOT
⦞ | 10654 | 299E | ANGLE WITH S INSIDE
⦟ | 10655 | 299F | ACUTE ANGLE
⦠ | 10656 | 29A0 | SPHERICAL ANGLE OPENING LEFT
⦡ | 10657 | 29A1 | SPHERICAL ANGLE OPENING UP
⦢ | 10658 | 29A2 | TURNED ANGLE
⦣ | 10659 | 29A3 | REVERSED ANGLE
⦤ | 10660 | 29A4 | ANGLE WITH UNDERBAR
⦥ | 10661 | 29A5 | REVERSED ANGLE WITH UNDERBAR
⦦ | 10662 | 29A6 | OBLIQUE ANGLE OPENING UP
⦧ | 10663 | 29A7 | OBLIQUE ANGLE OPENING DOWN
⦨ | 10664 | 29A8 | MEASURED ANGLE WITH OPEN ARM ENDING IN ARROW POINTING UP AND RIGHT
⦩ | 10665 | 29A9 | MEASURED ANGLE WITH OPEN ARM ENDING IN ARROW POINTING UP AND LEFT
⦪ | 10666 | 29AA | MEASURED ANGLE WITH OPEN ARM ENDING IN ARROW POINTING DOWN AND RIGHT
⦫ | 10667 | 29AB | MEASURED ANGLE WITH OPEN ARM ENDING IN ARROW POINTING DOWN AND LEFT
⦬ | 10668 | 29AC | MEASURED ANGLE WITH OPEN ARM ENDING IN ARROW POINTING RIGHT AND UP
⦭ | 10669 | 29AD | MEASURED ANGLE WITH OPEN ARM ENDING IN ARROW POINTING LEFT AND UP
⦮ | 10670 | 29AE | MEASURED ANGLE WITH OPEN ARM ENDING IN ARROW POINTING RIGHT AND DOWN
⦯ | 10671 | 29AF | MEASURED ANGLE WITH OPEN ARM ENDING IN ARROW POINTING LEFT AND DOWN
⦰ | 10672 | 29B0 | REVERSED EMPTY SET
⦱ | 10673 | 29B1 | EMPTY SET WITH OVERBAR
⦲ | 10674 | 29B2 | EMPTY SET WITH SMALL CIRCLE ABOVE
⦳ | 10675 | 29B3 | EMPTY SET WITH RIGHT ARROW ABOVE
⦴ | 10676 | 29B4 | EMPTY SET WITH LEFT ARROW ABOVE
⦵ | 10677 | 29B5 | CIRCLE WITH HORIZONTAL BAR
⦶ | 10678 | 29B6 | CIRCLED VERTICAL BAR
⦷ | 10679 | 29B7 | CIRCLED PARALLEL
⦸ | 10680 | 29B8 | CIRCLED REVERSE SOLIDUS
⦹ | 10681 | 29B9 | CIRCLED PERPENDICULAR
⦺ | 10682 | 29BA | CIRCLE DIVIDED BY HORIZONTAL BAR AND TOP HALF DIVIDED BY VERTICAL BAR
⦻ | 10683 | 29BB | CIRCLE WITH SUPERIMPOSED X
⦼ | 10684 | 29BC | CIRCLED ANTICLOCKWISE-ROTATED DIVISION SIGN
⦽ | 10685 | 29BD | UP ARROW THROUGH CIRCLE
⦾ | 10686 | 29BE | CIRCLED WHITE BULLET
⦿ | 10687 | 29BF | CIRCLED BULLET
⧀ | 10688 | 29C0 | CIRCLED LESS-THAN
⧁ | 10689 | 29C1 | CIRCLED GREATER-THAN
⧂ | 10690 | 29C2 | CIRCLE WITH SMALL CIRCLE TO THE RIGHT
⧃ | 10691 | 29C3 | CIRCLE WITH TWO HORIZONTAL STROKES TO THE RIGHT
⧄ | 10692 | 29C4 | SQUARED RISING DIAGONAL SLASH
⧅ | 10693 | 29C5 | SQUARED FALLING DIAGONAL SLASH
⧆ | 10694 | 29C6 | SQUARED ASTERISK
⧇ | 10695 | 29C7 | SQUARED SMALL CIRCLE
⧈ | 10696 | 29C8 | SQUARED SQUARE
⧉ | 10697 | 29C9 | TWO JOINED SQUARES
⧊ | 10698 | 29CA | TRIANGLE WITH DOT ABOVE
⧋ | 10699 | 29CB | TRIANGLE WITH UNDERBAR
⧌ | 10700 | 29CC | S IN TRIANGLE
⧍ | 10701 | 29CD | TRIANGLE WITH SERIFS AT BOTTOM
⧎ | 10702 | 29CE | RIGHT TRIANGLE ABOVE LEFT TRIANGLE
⧏ | 10703 | 29CF | LEFT TRIANGLE BESIDE VERTICAL BAR
⧐ | 10704 | 29D0 | VERTICAL BAR BESIDE RIGHT TRIANGLE
⧑ | 10705 | 29D1 | BOWTIE WITH LEFT HALF BLACK
⧒ | 10706 | 29D2 | BOWTIE WITH RIGHT HALF BLACK
⧓ | 10707 | 29D3 | BLACK BOWTIE
⧔ | 10708 | 29D4 | TIMES WITH LEFT HALF BLACK
⧕ | 10709 | 29D5 | TIMES WITH RIGHT HALF BLACK
⧖ | 10710 | 29D6 | WHITE HOURGLASS
⧗ | 10711 | 29D7 | BLACK HOURGLASS
⧘ | 10712 | 29D8 | LEFT WIGGLY FENCE
⧙ | 10713 | 29D9 | RIGHT WIGGLY FENCE
⧚ | 10714 | 29DA | LEFT DOUBLE WIGGLY FENCE
⧛ | 10715 | 29DB | RIGHT DOUBLE WIGGLY FENCE
⧜ | 10716 | 29DC | INCOMPLETE INFINITY
⧝ | 10717 | 29DD | TIE OVER INFINITY
⧞ | 10718 | 29DE | INFINITY NEGATED WITH VERTICAL BAR
⧟ | 10719 | 29DF | DOUBLE-ENDED MULTIMAP
⧠ | 10720 | 29E0 | SQUARE WITH CONTOURED OUTLINE
⧡ | 10721 | 29E1 | INCREASES AS
⧢ | 10722 | 29E2 | SHUFFLE PRODUCT
⧣ | 10723 | 29E3 | EQUALS SIGN AND SLANTED PARALLEL
⧤ | 10724 | 29E4 | EQUALS SIGN AND SLANTED PARALLEL WITH TILDE ABOVE
⧥ | 10725 | 29E5 | IDENTICAL TO AND SLANTED PARALLEL
⧦ | 10726 | 29E6 | GLEICH STARK
⧧ | 10727 | 29E7 | THERMODYNAMIC
⧨ | 10728 | 29E8 | DOWN-POINTING TRIANGLE WITH LEFT HALF BLACK
⧩ | 10729 | 29E9 | DOWN-POINTING TRIANGLE WITH RIGHT HALF BLACK
⧪ | 10730 | 29EA | BLACK DIAMOND WITH DOWN ARROW
⧫ | 10731 | 29EB | BLACK LOZENGE
⧬ | 10732 | 29EC | WHITE CIRCLE WITH DOWN ARROW
⧭ | 10733 | 29ED | BLACK CIRCLE WITH DOWN ARROW
⧮ | 10734 | 29EE | ERROR-BARRED WHITE SQUARE
⧯ | 10735 | 29EF | ERROR-BARRED BLACK SQUARE
⧰ | 10736 | 29F0 | ERROR-BARRED WHITE DIAMOND
⧱ | 10737 | 29F1 | ERROR-BARRED BLACK DIAMOND
⧲ | 10738 | 29F2 | ERROR-BARRED WHITE CIRCLE
⧳ | 10739 | 29F3 | ERROR-BARRED BLACK CIRCLE
⧴ | 10740 | 29F4 | RULE-DELAYED
⧵ | 10741 | 29F5 | REVERSE SOLIDUS OPERATOR
⧶ | 10742 | 29F6 | SOLIDUS WITH OVERBAR
⧷ | 10743 | 29F7 | REVERSE SOLIDUS WITH HORIZONTAL STROKE
⧸ | 10744 | 29F8 | BIG SOLIDUS
⧹ | 10745 | 29F9 | BIG REVERSE SOLIDUS
⧺ | 10746 | 29FA | DOUBLE PLUS
⧻ | 10747 | 29FB | TRIPLE PLUS
⧼ | 10748 | 29FC | LEFT-POINTING CURVED ANGLE BRACKET
⧽ | 10749 | 29FD | RIGHT-POINTING CURVED ANGLE BRACKET
⧾ | 10750 | 29FE | TINY
⧿ | 10751 | 29FF | MINY

### Supplemental Math Operators

Hex 2A00-2AFF / Decimal 10752-11007.

Char | Dec | Hex
--- | --- | ---
⨀ | 10752 | 2A00
⨁ | 10753 | 2A01
⨂ | 10754 | 2A02
⨃ | 10755 | 2A03
⨄ | 10756 | 2A04
⨅ | 10757 | 2A05
⨆ | 10758 | 2A06
⨇ | 10759 | 2A07
⨈ | 10760 | 2A08
⨉ | 10761 | 2A09
⨊ | 10762 | 2A0A
⨋ | 10763 | 2A0B
⨌ | 10764 | 2A0C
⨍ | 10765 | 2A0D
⨎ | 10766 | 2A0E
⨏ | 10767 | 2A0F
⨐ | 10768 | 2A10
⨑ | 10769 | 2A11
⨒ | 10770 | 2A12
⨓ | 10771 | 2A13
⨔ | 10772 | 2A14
⨕ | 10773 | 2A15
⨖ | 10774 | 2A16
⨗ | 10775 | 2A17
⨘ | 10776 | 2A18
⨙ | 10777 | 2A19
⨚ | 10778 | 2A1A
⨛ | 10779 | 2A1B
⨜ | 10780 | 2A1C
⨝ | 10781 | 2A1D
⨞ | 10782 | 2A1E
⨟ | 10783 | 2A1F
⨠ | 10784 | 2A20
⨡ | 10785 | 2A21
⨢ | 10786 | 2A22
⨣ | 10787 | 2A23
⨤ | 10788 | 2A24
⨥ | 10789 | 2A25
⨦ | 10790 | 2A26
⨧ | 10791 | 2A27
⨨ | 10792 | 2A28
⨩ | 10793 | 2A29
⨪ | 10794 | 2A2A
⨫ | 10795 | 2A2B
⨬ | 10796 | 2A2C
⨭ | 10797 | 2A2D
⨮ | 10798 | 2A2E
⨯ | 10799 | 2A2F
⨰ | 10800 | 2A30
⨱ | 10801 | 2A31
⨲ | 10802 | 2A32
⨳ | 10803 | 2A33
⨴ | 10804 | 2A34
⨵ | 10805 | 2A35
⨶ | 10806 | 2A36
⨷ | 10807 | 2A37
⨸ | 10808 | 2A38
⨹ | 10809 | 2A39
⨺ | 10810 | 2A3A
⨻ | 10811 | 2A3B
⨼ | 10812 | 2A3C
⨽ | 10813 | 2A3D
⨾ | 10814 | 2A3E
⨿ | 10815 | 2A3F
⩀ | 10816 | 2A40
⩁ | 10817 | 2A41
⩂ | 10818 | 2A42
⩃ | 10819 | 2A43
⩄ | 10820 | 2A44
⩅ | 10821 | 2A45
⩆ | 10822 | 2A46
⩇ | 10823 | 2A47
⩈ | 10824 | 2A48
⩉ | 10825 | 2A49
⩊ | 10826 | 2A4A
⩋ | 10827 | 2A4B
⩌ | 10828 | 2A4C
⩍ | 10829 | 2A4D
⩎ | 10830 | 2A4E
⩏ | 10831 | 2A4F
⩐ | 10832 | 2A50
⩑ | 10833 | 2A51
⩒ | 10834 | 2A52
⩓ | 10835 | 2A53
⩔ | 10836 | 2A54
⩕ | 10837 | 2A55
⩖ | 10838 | 2A56
⩗ | 10839 | 2A57
⩘ | 10840 | 2A58
⩙ | 10841 | 2A59
⩚ | 10842 | 2A5A
⩛ | 10843 | 2A5B
⩜ | 10844 | 2A5C
⩝ | 10845 | 2A5D
⩞ | 10846 | 2A5E
⩟ | 10847 | 2A5F
⩠ | 10848 | 2A60
⩡ | 10849 | 2A61
⩢ | 10850 | 2A62
⩣ | 10851 | 2A63
⩤ | 10852 | 2A64
⩥ | 10853 | 2A65
⩦ | 10854 | 2A66
⩧ | 10855 | 2A67
⩨ | 10856 | 2A68
⩩ | 10857 | 2A69
⩪ | 10858 | 2A6A
⩫ | 10859 | 2A6B
⩬ | 10860 | 2A6C
⩭ | 10861 | 2A6D
⩮ | 10862 | 2A6E
⩯ | 10863 | 2A6F
⩰ | 10864 | 2A70
⩱ | 10865 | 2A71
⩲ | 10866 | 2A72
⩳ | 10867 | 2A73
⩴ | 10868 | 2A74
⩵ | 10869 | 2A75
⩶ | 10870 | 2A76
⩷ | 10871 | 2A77
⩸ | 10872 | 2A78
⩹ | 10873 | 2A79
⩺ | 10874 | 2A7A
⩻ | 10875 | 2A7B
⩼ | 10876 | 2A7C
⩽ | 10877 | 2A7D
⩾ | 10878 | 2A7E
⩿ | 10879 | 2A7F
⪀ | 10880 | 2A80
⪁ | 10881 | 2A81
⪂ | 10882 | 2A82
⪃ | 10883 | 2A83
⪄ | 10884 | 2A84
⪅ | 10885 | 2A85
⪆ | 10886 | 2A86
⪇ | 10887 | 2A87
⪈ | 10888 | 2A88
⪉ | 10889 | 2A89
⪊ | 10890 | 2A8A
⪋ | 10891 | 2A8B
⪌ | 10892 | 2A8C
⪍ | 10893 | 2A8D
⪎ | 10894 | 2A8E
⪏ | 10895 | 2A8F
⪐ | 10896 | 2A90
⪑ | 10897 | 2A91
⪒ | 10898 | 2A92
⪓ | 10899 | 2A93
⪔ | 10900 | 2A94
⪕ | 10901 | 2A95
⪖ | 10902 | 2A96
⪗ | 10903 | 2A97
⪘ | 10904 | 2A98
⪙ | 10905 | 2A99
⪚ | 10906 | 2A9A
⪛ | 10907 | 2A9B
⪜ | 10908 | 2A9C
⪝ | 10909 | 2A9D
⪞ | 10910 | 2A9E
⪟ | 10911 | 2A9F
⪠ | 10912 | 2AA0
⪡ | 10913 | 2AA1
⪢ | 10914 | 2AA2
⪣ | 10915 | 2AA3
⪤ | 10916 | 2AA4
⪥ | 10917 | 2AA5
⪦ | 10918 | 2AA6
⪧ | 10919 | 2AA7
⪨ | 10920 | 2AA8
⪩ | 10921 | 2AA9
⪪ | 10922 | 2AAA
⪫ | 10923 | 2AAB
⪬ | 10924 | 2AAC
⪭ | 10925 | 2AAD
⪮ | 10926 | 2AAE
⪯ | 10927 | 2AAF
⪰ | 10928 | 2AB0
⪱ | 10929 | 2AB1
⪲ | 10930 | 2AB2
⪳ | 10931 | 2AB3
⪴ | 10932 | 2AB4
⪵ | 10933 | 2AB5
⪶ | 10934 | 2AB6
⪷ | 10935 | 2AB7
⪸ | 10936 | 2AB8
⪹ | 10937 | 2AB9
⪺ | 10938 | 2ABA
⪻ | 10939 | 2ABB
⪼ | 10940 | 2ABC
⪽ | 10941 | 2ABD
⪾ | 10942 | 2ABE
⪿ | 10943 | 2ABF
⫀ | 10944 | 2AC0
⫁ | 10945 | 2AC1
⫂ | 10946 | 2AC2
⫃ | 10947 | 2AC3
⫄ | 10948 | 2AC4
⫅ | 10949 | 2AC5
⫆ | 10950 | 2AC6
⫇ | 10951 | 2AC7
⫈ | 10952 | 2AC8
⫉ | 10953 | 2AC9
⫊ | 10954 | 2ACA
⫋ | 10955 | 2ACB
⫌ | 10956 | 2ACC
⫍ | 10957 | 2ACD
⫎ | 10958 | 2ACE
⫏ | 10959 | 2ACF
⫐ | 10960 | 2AD0
⫑ | 10961 | 2AD1
⫒ | 10962 | 2AD2
⫓ | 10963 | 2AD3
⫔ | 10964 | 2AD4
⫕ | 10965 | 2AD5
⫖ | 10966 | 2AD6
⫗ | 10967 | 2AD7
⫘ | 10968 | 2AD8
⫙ | 10969 | 2AD9
⫚ | 10970 | 2ADA
⫛ | 10971 | 2ADB
⫝̸ | 10972 | 2ADC
⫝ | 10973 | 2ADD
⫞ | 10974 | 2ADE
⫟ | 10975 | 2ADF
⫠ | 10976 | 2AE0
⫡ | 10977 | 2AE1
⫢ | 10978 | 2AE2
⫣ | 10979 | 2AE3
⫤ | 10980 | 2AE4
⫥ | 10981 | 2AE5
⫦ | 10982 | 2AE6
⫧ | 10983 | 2AE7
⫨ | 10984 | 2AE8
⫩ | 10985 | 2AE9
⫪ | 10986 | 2AEA
⫫ | 10987 | 2AEB
⫬ | 10988 | 2AEC
⫭ | 10989 | 2AED
⫮ | 10990 | 2AEE
⫯ | 10991 | 2AEF
⫰ | 10992 | 2AF0
⫱ | 10993 | 2AF1
⫲ | 10994 | 2AF2
⫳ | 10995 | 2AF3
⫴ | 10996 | 2AF4
⫵ | 10997 | 2AF5
⫶ | 10998 | 2AF6
⫷ | 10999 | 2AF7
⫸ | 11000 | 2AF8
⫹ | 11001 | 2AF9
⫺ | 11002 | 2AFA
⫻ | 11003 | 2AFB
⫼ | 11004 | 2AFC
⫽ | 11005 | 2AFD
⫾ | 11006 | 2AFE
⫿ | 11007 | 2AFF

## Box Drawings

Hex 2500-257F / Decimal 9472-9599.

| Char | Dec  | Hex  | Name                                     |
| ---- | ---- | ---- | ---------------------------------------- |
| ─    | 9472 | 2500 | LIGHT HORIZONTAL                         |
| ━    | 9473 | 2501 | HEAVY HORIZONTAL                         |
| │    | 9474 | 2502 | LIGHT VERTICAL                           |
| ┃    | 9475 | 2503 | HEAVY VERTICAL                           |
| ┄    | 9476 | 2504 | LIGHT TRIPLE DASH HORIZONTAL             |
| ┅    | 9477 | 2505 | HEAVY TRIPLE DASH HORIZONTAL             |
| ┆    | 9478 | 2506 | LIGHT TRIPLE DASH VERTICAL               |
| ┇    | 9479 | 2507 | HEAVY TRIPLE DASH VERTICAL               |
| ┈    | 9480 | 2508 | LIGHT QUADRUPLE DASH HORIZONTAL          |
| ┉    | 9481 | 2509 | HEAVY QUADRUPLE DASH HORIZONTAL          |
| ┊    | 9482 | 250A | LIGHT QUADRUPLE DASH VERTICAL            |
| ┋    | 9483 | 250B | HEAVY QUADRUPLE DASH VERTICAL            |
| ┌    | 9484 | 250C | LIGHT DOWN AND RIGHT                     |
| ┍    | 9485 | 250D | DOWN LIGHT AND RIGHT HEAVY               |
| ┎    | 9486 | 250E | DOWN HEAVY AND RIGHT LIGHT               |
| ┏    | 9487 | 250F | HEAVY DOWN AND RIGHT                     |
| ┐    | 9488 | 2510 | LIGHT DOWN AND LEFT                      |
| ┑    | 9489 | 2511 | DOWN LIGHT AND LEFT HEAVY                |
| ┒    | 9490 | 2512 | DOWN HEAVY AND LEFT LIGHT                |
| ┓    | 9491 | 2513 | HEAVY DOWN AND LEFT                      |
| └    | 9492 | 2514 | LIGHT UP AND RIGHT                       |
| ┕    | 9493 | 2515 | UP LIGHT AND RIGHT HEAVY                 |
| ┖    | 9494 | 2516 | UP HEAVY AND RIGHT LIGHT                 |
| ┗    | 9495 | 2517 | HEAVY UP AND RIGHT                       |
| ┘    | 9496 | 2518 | LIGHT UP AND LEFT                        |
| ┙    | 9497 | 2519 | UP LIGHT AND LEFT HEAVY                  |
| ┚    | 9498 | 251A | UP HEAVY AND LEFT LIGHT                  |
| ┛    | 9499 | 251B | HEAVY UP AND LEFT                        |
| ├    | 9500 | 251C | LIGHT VERTICAL AND RIGHT                 |
| ┝    | 9501 | 251D | VERTICAL LIGHT AND RIGHT HEAVY           |
| ┞    | 9502 | 251E | UP HEAVY AND RIGHT DOWN LIGHT            |
| ┟    | 9503 | 251F | DOWN HEAVY AND RIGHT UP LIGHT            |
| ┠    | 9504 | 2520 | VERTICAL HEAVY AND RIGHT LIGHT           |
| ┡    | 9505 | 2521 | DOWN LIGHT AND RIGHT UP HEAVY            |
| ┢    | 9506 | 2522 | UP LIGHT AND RIGHT DOWN HEAVY            |
| ┣    | 9507 | 2523 | HEAVY VERTICAL AND RIGHT                 |
| ┤    | 9508 | 2524 | LIGHT VERTICAL AND LEFT                  |
| ┥    | 9509 | 2525 | VERTICAL LIGHT AND LEFT HEAVY            |
| ┦    | 9510 | 2526 | UP HEAVY AND LEFT DOWN LIGHT             |
| ┧    | 9511 | 2527 | DOWN HEAVY AND LEFT UP LIGHT             |
| ┨    | 9512 | 2528 | VERTICAL HEAVY AND LEFT LIGHT            |
| ┩    | 9513 | 2529 | DOWN LIGHT AND LEFT UP HEAVY             |
| ┪    | 9514 | 252A | UP LIGHT AND LEFT DOWN HEAVY             |
| ┫    | 9515 | 252B | HEAVY VERTICAL AND LEFT                  |
| ┬    | 9516 | 252C | LIGHT DOWN AND HORIZONTAL                |
| ┭    | 9517 | 252D | LEFT HEAVY AND RIGHT DOWN LIGHT          |
| ┮    | 9518 | 252E | RIGHT HEAVY AND LEFT DOWN LIGHT          |
| ┯    | 9519 | 252F | DOWN LIGHT AND HORIZONTAL HEAVY          |
| ┰    | 9520 | 2530 | DOWN HEAVY AND HORIZONTAL LIGHT          |
| ┱    | 9521 | 2531 | RIGHT LIGHT AND LEFT DOWN HEAVY          |
| ┲    | 9522 | 2532 | LEFT LIGHT AND RIGHT DOWN HEAVY          |
| ┳    | 9523 | 2533 | HEAVY DOWN AND HORIZONTAL                |
| ┴    | 9524 | 2534 | LIGHT UP AND HORIZONTAL                  |
| ┵    | 9525 | 2535 | LEFT HEAVY AND RIGHT UP LIGHT            |
| ┶    | 9526 | 2536 | RIGHT HEAVY AND LEFT UP LIGHT            |
| ┷    | 9527 | 2537 | UP LIGHT AND HORIZONTAL HEAVY            |
| ┸    | 9528 | 2538 | UP HEAVY AND HORIZONTAL LIGHT            |
| ┹    | 9529 | 2539 | RIGHT LIGHT AND LEFT UP HEAVY            |
| ┺    | 9530 | 253A | LEFT LIGHT AND RIGHT UP HEAVY            |
| ┻    | 9531 | 253B | HEAVY UP AND HORIZONTAL                  |
| ┼    | 9532 | 253C | LIGHT VERTICAL AND HORIZONTAL            |
| ┽    | 9533 | 253D | LEFT HEAVY AND RIGHT VERTICAL LIGHT      |
| ┾    | 9534 | 253E | RIGHT HEAVY AND LEFT VERTICAL LIGHT      |
| ┿    | 9535 | 253F | VERTICAL LIGHT AND HORIZONTAL HEAVY      |
| ╀    | 9536 | 2540 | UP HEAVY AND DOWN HORIZONTAL LIGHT       |
| ╁    | 9537 | 2541 | DOWN HEAVY AND UP HORIZONTAL LIGHT       |
| ╂    | 9538 | 2542 | VERTICAL HEAVY AND HORIZONTAL LIGHT      |
| ╃    | 9539 | 2543 | LEFT UP HEAVY AND RIGHT DOWN LIGHT       |
| ╄    | 9540 | 2544 | RIGHT UP HEAVY AND LEFT DOWN LIGHT       |
| ╅    | 9541 | 2545 | LEFT DOWN HEAVY AND RIGHT UP LIGHT       |
| ╆    | 9542 | 2546 | RIGHT DOWN HEAVY AND LEFT UP LIGHT       |
| ╇    | 9543 | 2547 | DOWN LIGHT AND UP HORIZONTAL HEAVY       |
| ╈    | 9544 | 2548 | UP LIGHT AND DOWN HORIZONTAL HEAVY       |
| ╉    | 9545 | 2549 | RIGHT LIGHT AND LEFT VERTICAL HEAVY      |
| ╊    | 9546 | 254A | LEFT LIGHT AND RIGHT VERTICAL HEAVY      |
| ╋    | 9547 | 254B | HEAVY VERTICAL AND HORIZONTAL            |
| ╌    | 9548 | 254C | LIGHT DOUBLE DASH HORIZONTAL             |
| ╍    | 9549 | 254D | HEAVY DOUBLE DASH HORIZONTAL             |
| ╎    | 9550 | 254E | LIGHT DOUBLE DASH VERTICAL               |
| ╏    | 9551 | 254F | HEAVY DOUBLE DASH VERTICAL               |
| ═    | 9552 | 2550 | DOUBLE HORIZONTAL                        |
| ║    | 9553 | 2551 | DOUBLE VERTICAL                          |
| ╒    | 9554 | 2552 | DOWN SINGLE AND RIGHT DOUBLE             |
| ╓    | 9555 | 2553 | DOWN DOUBLE AND RIGHT SINGLE             |
| ╔    | 9556 | 2554 | DOUBLE DOWN AND RIGHT                    |
| ╕    | 9557 | 2555 | DOWN SINGLE AND LEFT DOUBLE              |
| ╖    | 9558 | 2556 | DOWN DOUBLE AND LEFT SINGLE              |
| ╗    | 9559 | 2557 | DOUBLE DOWN AND LEFT                     |
| ╘    | 9560 | 2558 | UP SINGLE AND RIGHT DOUBLE               |
| ╙    | 9561 | 2559 | UP DOUBLE AND RIGHT SINGLE               |
| ╚    | 9562 | 255A | DOUBLE UP AND RIGHT                      |
| ╛    | 9563 | 255B | UP SINGLE AND LEFT DOUBLE                |
| ╜    | 9564 | 255C | UP DOUBLE AND LEFT SINGLE                |
| ╝    | 9565 | 255D | DOUBLE UP AND LEFT                       |
| ╞    | 9566 | 255E | VERTICAL SINGLE AND RIGHT DOUBLE         |
| ╟    | 9567 | 255F | VERTICAL DOUBLE AND RIGHT SINGLE         |
| ╠    | 9568 | 2560 | DOUBLE VERTICAL AND RIGHT                |
| ╡    | 9569 | 2561 | VERTICAL SINGLE AND LEFT DOUBLE          |
| ╢    | 9570 | 2562 | VERTICAL DOUBLE AND LEFT SINGLE          |
| ╣    | 9571 | 2563 | DOUBLE VERTICAL AND LEFT                 |
| ╤    | 9572 | 2564 | DOWN SINGLE AND HORIZONTAL DOUBLE        |
| ╥    | 9573 | 2565 | DOWN DOUBLE AND HORIZONTAL SINGLE        |
| ╦    | 9574 | 2566 | DOUBLE DOWN AND HORIZONTAL               |
| ╧    | 9575 | 2567 | UP SINGLE AND HORIZONTAL DOUBLE          |
| ╨    | 9576 | 2568 | UP DOUBLE AND HORIZONTAL SINGLE          |
| ╩    | 9577 | 2569 | DOUBLE UP AND HORIZONTAL                 |
| ╪    | 9578 | 256A | VERTICAL SINGLE AND HORIZONTAL DOUBLE    |
| ╫    | 9579 | 256B | VERTICAL DOUBLE AND HORIZONTAL SINGLE    |
| ╬    | 9580 | 256C | DOUBLE VERTICAL AND HORIZONTAL           |
| ╭    | 9581 | 256D | LIGHT ARC DOWN AND RIGHT                 |
| ╮    | 9582 | 256E | LIGHT ARC DOWN AND LEFT                  |
| ╯    | 9583 | 256F | LIGHT ARC UP AND LEFT                    |
| ╰    | 9584 | 2570 | LIGHT ARC UP AND RIGHT                   |
| ╱    | 9585 | 2571 | LIGHT DIAGONAL UPPER RIGHT TO LOWER LEFT |
| ╲    | 9586 | 2572 | LIGHT DIAGONAL UPPER LEFT TO LOWER RIGHT |
| ╳    | 9587 | 2573 | LIGHT DIAGONAL CROSS                     |
| ╴    | 9588 | 2574 | LIGHT LEFT                               |
| ╵    | 9589 | 2575 | LIGHT UP                                 |
| ╶    | 9590 | 2576 | LIGHT RIGHT                              |
| ╷    | 9591 | 2577 | LIGHT DOWN                               |
| ╸    | 9592 | 2578 | HEAVY LEFT                               |
| ╹    | 9593 | 2579 | HEAVY UP                                 |
| ╺    | 9594 | 257A | HEAVY RIGHT                              |
| ╻    | 9595 | 257B | HEAVY DOWN                               |
| ╼    | 9596 | 257C | LIGHT LEFT AND HEAVY RIGHT               |
| ╽    | 9597 | 257D | LIGHT UP AND HEAVY DOWN                  |
| ╾    | 9598 | 257E | HEAVY LEFT AND LIGHT RIGHT               |
| ╿    | 9599 | 257F | HEAVY UP AND LIGHT DOWN                  |

## Block Elements

Hex 2580-259F / Decimal 9600-9631.

Char | Dec | Hex | Name
--- | --- | --- | ---
▀ | 9600 | 2580 | UPPER HALF BLOCK
▁ | 9601 | 2581 | LOWER ONE EIGHTH BLOCK
▂ | 9602 | 2582 | LOWER ONE QUARTER BLOCK
▃ | 9603 | 2583 | LOWER THREE EIGHTHS BLOCK
▄ | 9604 | 2584 | LOWER HALF BLOCK
▅ | 9605 | 2585 | LOWER FIVE EIGHTHS BLOCK
▆ | 9606 | 2586 | LOWER THREE QUARTERS BLOCK
▇ | 9607 | 2587 | LOWER SEVEN EIGHTHS BLOCK
█ | 9608 | 2588 | FULL BLOCK
▉ | 9609 | 2589 | LEFT SEVEN EIGHTHS BLOCK
▊ | 9610 | 258A | LEFT THREE QUARTERS BLOCK
▋ | 9611 | 258B | LEFT FIVE EIGHTHS BLOCK
▌ | 9612 | 258C | LEFT HALF BLOCK
▍ | 9613 | 258D | LEFT THREE EIGHTHS BLOCK
▎ | 9614 | 258E | LEFT ONE QUARTER BLOCK
▏ | 9615 | 258F | LEFT ONE EIGHTH BLOCK
▐ | 9616 | 2590 | RIGHT HALF BLOCK
░ | 9617 | 2591 | LIGHT SHADE
▒ | 9618 | 2592 | MEDIUM SHADE
▓ | 9619 | 2593 | DARK SHADE
▔ | 9620 | 2594 | UPPER ONE EIGHTH BLOCK
▕ | 9621 | 2595 | RIGHT ONE EIGHTH BLOCK
▖ | 9622 | 2596 | QUADRANT LOWER LEFT
▗ | 9623 | 2597 | QUADRANT LOWER RIGHT
▘ | 9624 | 2598 | QUADRANT UPPER LEFT
▙ | 9625 | 2599 | QUADRANT UPPER LEFT AND LOWER LEFT AND LOWER RIGHT
▚ | 9626 | 259A | QUADRANT UPPER LEFT AND LOWER RIGHT
▛ | 9627 | 259B | QUADRANT UPPER LEFT AND UPPER RIGHT AND LOWER LEFT
▜ | 9628 | 259C | QUADRANT UPPER LEFT AND UPPER RIGHT AND LOWER RIGHT
▝ | 9629 | 259D | QUADRANT UPPER RIGHT
▞ | 9630 | 259E | QUADRANT UPPER RIGHT AND LOWER LEFT
▟ | 9631 | 259F | QUADRANT UPPER RIGHT AND LOWER LEFT AND LOWER RIGHT

## Geometric Shapes

Hex 25A0-25FF / Decimal 9632-9727.

Char | Dec | Hex | Name
--- | --- | --- | ---
■ | 9632 | 25A0 | BLACK SQUARE
□ | 9633 | 25A1 | WHITE SQUARE
▢ | 9634 | 25A2 | WHITE SQUARE WITH ROUNDED CORNERS
▣ | 9635 | 25A3 | WHITE SQUARE CONTAINING BLACK SMALL SQUARE
▤ | 9636 | 25A4 | SQUARE WITH HORIZONTAL FILL
▥ | 9637 | 25A5 | SQUARE WITH VERTICAL FILL
▦ | 9638 | 25A6 | SQUARE WITH ORTHOGONAL CROSSHATCH FILL
▧ | 9639 | 25A7 | SQUARE WITH UPPER LEFT TO LOWER RIGHT FILL
▨ | 9640 | 25A8 | SQUARE WITH UPPER RIGHT TO LOWER LEFT FILL
▩ | 9641 | 25A9 | SQUARE WITH DIAGONAL CROSSHATCH FILL
▪ | 9642 | 25AA | BLACK SMALL SQUARE
▫ | 9643 | 25AB | WHITE SMALL SQUARE
▬ | 9644 | 25AC | BLACK RECTANGLE
▭ | 9645 | 25AD | WHITE RECTANGLE
▮ | 9646 | 25AE | BLACK VERTICAL RECTANGLE
▯ | 9647 | 25AF | WHITE VERTICAL RECTANGLE
▰ | 9648 | 25B0 | BLACK PARALLELOGRAM
▱ | 9649 | 25B1 | WHITE PARALLELOGRAM
▲ | 9650 | 25B2 | BLACK UP-POINTING TRIANGLE
△ | 9651 | 25B3 | WHITE UP-POINTING TRIANGLE
▴ | 9652 | 25B4 | BLACK UP-POINTING SMALL TRIANGLE
▵ | 9653 | 25B5 | WHITE UP-POINTING SMALL TRIANGLE
▶ | 9654 | 25B6 | BLACK RIGHT-POINTING TRIANGLE
▷ | 9655 | 25B7 | WHITE RIGHT-POINTING TRIANGLE
▸ | 9656 | 25B8 | BLACK RIGHT-POINTING SMALL TRIANGLE
▹ | 9657 | 25B9 | WHITE RIGHT-POINTING SMALL TRIANGLE
► | 9658 | 25BA | BLACK RIGHT-POINTING POINTER
▻ | 9659 | 25BB | WHITE RIGHT-POINTING POINTER
▼ | 9660 | 25BC | BLACK DOWN-POINTING TRIANGLE
▽ | 9661 | 25BD | WHITE DOWN-POINTING TRIANGLE
▾ | 9662 | 25BE | BLACK DOWN-POINTING SMALL TRIANGLE
▿ | 9663 | 25BF | WHITE DOWN-POINTING SMALL TRIANGLE
◀ | 9664 | 25C0 | BLACK LEFT-POINTING TRIANGLE
◁ | 9665 | 25C1 | WHITE LEFT-POINTING TRIANGLE
◂ | 9666 | 25C2 | BLACK LEFT-POINTING SMALL TRIANGLE
◃ | 9667 | 25C3 | WHITE LEFT-POINTING SMALL TRIANGLE
◄ | 9668 | 25C4 | BLACK LEFT-POINTING POINTER
◅ | 9669 | 25C5 | WHITE LEFT-POINTING POINTER
◆ | 9670 | 25C6 | BLACK DIAMOND
◇ | 9671 | 25C7 | WHITE DIAMOND
◈ | 9672 | 25C8 | WHITE DIAMOND CONTAINING BLACK SMALL DIAMOND
◉ | 9673 | 25C9 | FISHEYE
◊ | 9674 | 25CA | LOZENGE
○ | 9675 | 25CB | WHITE CIRCLE
◌ | 9676 | 25CC | DOTTED CIRCLE
◍ | 9677 | 25CD | CIRCLE WITH VERTICAL FILL
◎ | 9678 | 25CE | BULLSEYE
● | 9679 | 25CF | BLACK CIRCLE
◐ | 9680 | 25D0 | CIRCLE WITH LEFT HALF BLACK
◑ | 9681 | 25D1 | CIRCLE WITH RIGHT HALF BLACK
◒ | 9682 | 25D2 | CIRCLE WITH LOWER HALF BLACK
◓ | 9683 | 25D3 | CIRCLE WITH UPPER HALF BLACK
◔ | 9684 | 25D4 | CIRCLE WITH UPPER RIGHT QUADRANT BLACK
◕ | 9685 | 25D5 | CIRCLE WITH ALL BUT UPPER LEFT QUADRANT BLACK
◖ | 9686 | 25D6 | LEFT HALF BLACK CIRCLE
◗ | 9687 | 25D7 | RIGHT HALF BLACK CIRCLE
◘ | 9688 | 25D8 | INVERSE BULLET
◙ | 9689 | 25D9 | INVERSE WHITE CIRCLE
◚ | 9690 | 25DA | UPPER HALF INVERSE WHITE CIRCLE
◛ | 9691 | 25DB | LOWER HALF INVERSE WHITE CIRCLE
◜ | 9692 | 25DC | UPPER LEFT QUADRANT CIRCULAR ARC
◝ | 9693 | 25DD | UPPER RIGHT QUADRANT CIRCULAR ARC
◞ | 9694 | 25DE | LOWER RIGHT QUADRANT CIRCULAR ARC
◟ | 9695 | 25DF | LOWER LEFT QUADRANT CIRCULAR ARC
◠ | 9696 | 25E0 | UPPER HALF CIRCLE
◡ | 9697 | 25E1 | LOWER HALF CIRCLE
◢ | 9698 | 25E2 | BLACK LOWER RIGHT TRIANGLE
◣ | 9699 | 25E3 | BLACK LOWER LEFT TRIANGLE
◤ | 9700 | 25E4 | BLACK UPPER LEFT TRIANGLE
◥ | 9701 | 25E5 | BLACK UPPER RIGHT TRIANGLE
◦ | 9702 | 25E6 | WHITE BULLET
◧ | 9703 | 25E7 | SQUARE WITH LEFT HALF BLACK
◨ | 9704 | 25E8 | SQUARE WITH RIGHT HALF BLACK
◩ | 9705 | 25E9 | SQUARE WITH UPPER LEFT DIAGONAL HALF BLACK
◪ | 9706 | 25EA | SQUARE WITH LOWER RIGHT DIAGONAL HALF BLACK
◫ | 9707 | 25EB | WHITE SQUARE WITH VERTICAL BISECTING LINE
◬ | 9708 | 25EC | WHITE UP-POINTING TRIANGLE WITH DOT
◭ | 9709 | 25ED | UP-POINTING TRIANGLE WITH LEFT HALF BLACK
◮ | 9710 | 25EE | UP-POINTING TRIANGLE WITH RIGHT HALF BLACK
◯ | 9711 | 25EF | LARGE CIRCLE
◰ | 9712 | 25F0 | WHITE SQUARE WITH UPPER LEFT QUADRANT
◱ | 9713 | 25F1 | WHITE SQUARE WITH LOWER LEFT QUADRANT
◲ | 9714 | 25F2 | WHITE SQUARE WITH LOWER RIGHT QUADRANT
◳ | 9715 | 25F3 | WHITE SQUARE WITH UPPER RIGHT QUADRANT
◴ | 9716 | 25F4 | WHITE CIRCLE WITH UPPER LEFT QUADRANT
◵ | 9717 | 25F5 | WHITE CIRCLE WITH LOWER LEFT QUADRANT
◶ | 9718 | 25F6 | WHITE CIRCLE WITH LOWER RIGHT QUADRANT
◷ | 9719 | 25F7 | WHITE CIRCLE WITH UPPER RIGHT QUADRANT
◸ | 9720 | 25F8 | UPPER LEFT TRIANGLE
◹ | 9721 | 25F9 | UPPER RIGHT TRIANGLE
◺ | 9722 | 25FA | LOWER LEFT TRIANGLE
◻ | 9723 | 25FB | WHITE MEDIUM SQUARE
◼ | 9724 | 25FC | BLACK MEDIUM SQUARE
◽ | 9725 | 25FD | WHITE MEDIUM SMALL SQUARE
◾ | 9726 | 25FE | BLACK MEDIUM SMALL SQUARE
◿ | 9727 | 25FF | LOWER RIGHT TRIANGLE

### Geometric Supplements

Hex 1F780-1F7FF / Dec 129024-129279.

Char | Dec | Hex
--- | --- | ---
🞀 | 128896 | 1F780 
🞁 | 128897 | 1F781 
🞂 | 128898 | 1F782 
🞃 | 128899 | 1F783 
🞄 | 128900 | 1F784 
🞅 | 128901 | 1F785 
🞆 | 128902 | 1F786 
🞇 | 128903 | 1F787 
🞈 | 128904 | 1F788 
🞉 | 128905 | 1F789 
🞊 | 128906 | 1F78A 
🞋 | 128907 | 1F78B 
🞌 | 128908 | 1F78C 
🞍 | 128909 | 1F78D 
🞎 | 128910 | 1F78E 
🞏 | 128911 | 1F78F 
🞐 | 128912 | 1F790 
🞑 | 128913 | 1F791 
🞒 | 128914 | 1F792 
🞓 | 128915 | 1F793 
🞔 | 128916 | 1F794 
🞕 | 128917 | 1F795 
🞖 | 128918 | 1F796 
🞗 | 128919 | 1F797 
🞘 | 128920 | 1F798 
🞙 | 128921 | 1F799 
🞚 | 128922 | 1F79A 
🞛 | 128923 | 1F79B 
🞜 | 128924 | 1F79C 
🞝 | 128925 | 1F79D 
🞞 | 128926 | 1F79E 
🞟 | 128927 | 1F79F 
🞠 | 128928 | 1F7A0 

### Crosses

Char | Dec | Hex
--- | --- | ---
🞡 | 128929 | 1F7A1 
🞢 | 128930 | 1F7A2 
🞣 | 128931 | 1F7A3 
🞤 | 128932 | 1F7A4 
🞥 | 128933 | 1F7A5 
🞦 | 128934 | 1F7A6 
🞧 | 128935 | 1F7A7 
🞨 | 128936 | 1F7A8 
🞩 | 128937 | 1F7A9 
🞪 | 128938 | 1F7AA 
🞫 | 128939 | 1F7AB 
🞬 | 128940 | 1F7AC 
🞭 | 128941 | 1F7AD 
🞮 | 128942 | 1F7AE

### Asteriks

Char | Dec | Hex
--- | --- | ---
🞯 | 128943 | 1F7AF
🞰 | 128944 | 1F7B0
🞱 | 128945 | 1F7B1
🞲 | 128946 | 1F7B2
🞳 | 128947 | 1F7B3
🞴 | 128948 | 1F7B4
🞵 | 128949 | 1F7B5
🞶 | 128950 | 1F7B6
🞷 | 128951 | 1F7B7
🞸 | 128952 | 1F7B8
🞹 | 128953 | 1F7B9
🞺 | 128954 | 1F7BA
🞻 | 128955 | 1F7BB
🞼 | 128956 | 1F7BC
🞽 | 128957 | 1F7BD
🞾 | 128958 | 1F7BE
🞿 | 128959 | 1F7BF

### Stars

Char | Dec | Hex
--- | --- | ---
🟀 | 128960 | 1F7C0
🟁 | 128961 | 1F7C1
🟂 | 128962 | 1F7C2
🟃 | 128963 | 1F7C3
🟄 | 128964 | 1F7C4
🟅 | 128965 | 1F7C5
🟆 | 128966 | 1F7C6
🟇 | 128967 | 1F7C7
🟈 | 128968 | 1F7C8
🟉 | 128969 | 1F7C9
🟊 | 128970 | 1F7CA
🟋 | 128971 | 1F7CB
🟌 | 128972 | 1F7CC
🟍 | 128973 | 1F7CD
🟎 | 128974 | 1F7CE
🟏 | 128975 | 1F7CF
🟐 | 128976 | 1F7D0
🟑 | 128977 | 1F7D1
🟒 | 128978 | 1F7D2
🟓 | 128979 | 1F7D3
🟔 | 128980 | 1F7D4

### Not in Use

Char | Dec | Hex
--- | --- | ---
🟕 | 128981 | 1F7D5
🟖 | 128982 | 1F7D6
🟗 | 128983 | 1F7D7
🟘 | 128984 | 1F7D8
🟙 | 128985 | 1F7D9
🟚 | 128986 | 1F7DA
🟛 | 128987 | 1F7DB
🟜 | 128988 | 1F7DC
🟝 | 128989 | 1F7DD
🟞 | 128990 | 1F7DE
🟟 | 128991 | 1F7DF

### Colored Circles and Squares

Char | Dec | Hex
--- | --- | ---
🟠 | 128992 | 1F7E0
🟡 | 128993 | 1F7E1
🟢 | 128994 | 1F7E2
🟣 | 128995 | 1F7E3
🟤 | 128996 | 1F7E4
🟥 | 128997 | 1F7E5
🟦 | 128998 | 1F7E6
🟧 | 128999 | 1F7E7
🟨 | 129000 | 1F7E8
🟩 | 129001 | 1F7E9
🟪 | 129002 | 1F7EA
🟫 | 129003 | 1F7EB

### Not in Use

Char | Dec | Hex
--- | --- | ---
🟬 | 129004 | 1F7EC
🟭 | 129005 | 1F7ED
🟮 | 129006 | 1F7EE
🟯 | 129007 | 1F7EF
🟰 | 129008 | 1F7F0
🟱 | 129009 | 1F7F1
🟲 | 129010 | 1F7F2
🟳 | 129011 | 1F7F3
🟴 | 129012 | 1F7F4
🟵 | 129013 | 1F7F5
🟶 | 129014 | 1F7F6
🟷 | 129015 | 1F7F7
🟸 | 129016 | 1F7F8
🟹 | 129017 | 1F7F9
🟺 | 129018 | 1F7FA
🟻 | 129019 | 1F7FB
🟼 | 129020 | 1F7FC
🟽 | 129021 | 1F7FD
🟾 | 129022 | 1F7FE
🟿 | 129023 | 1F7FF
## Miscellaneous Symbols

Hex 2600-26FF / Decimal 9728-9983.

Char | Dec | Hex | Name
--- | --- | --- | ---
☀ | 9728 | 2600 | BLACK SUN WITH RAYS
☁ | 9729 | 2601 | CLOUD
☂ | 9730 | 2602 | UMBRELLA
☃ | 9731 | 2603 | SNOWMAN
☄ | 9732 | 2604 | COMET
★ | 9733 | 2605 | BLACK STAR
☆ | 9734 | 2606 | WHITE STAR
☇ | 9735 | 2607 | LIGHTNING
☈ | 9736 | 2608 | THUNDERSTORM
☉ | 9737 | 2609 | SUN
☊ | 9738 | 260A | ASCENDING NODE
☋ | 9739 | 260B | DESCENDING NODE
☌ | 9740 | 260C | CONJUNCTION
☍ | 9741 | 260D | OPPOSITION
☎ | 9742 | 260E | BLACK TELEPHONE
☏ | 9743 | 260F | WHITE TELEPHONE
☐ | 9744 | 2610 | BALLOT BOX
☑ | 9745 | 2611 | BALLOT BOX WITH CHECK
☒ | 9746 | 2612 | BALLOT BOX WITH X
☓ | 9747 | 2613 | SALTIRE
☔ | 9748 | 2614 | UMBRELLA WITH RAIN DROPS
☕ | 9749 | 2615 | HOT BEVERAGE
☖ | 9750 | 2616 | WHITE SHOGI PIECE
☗ | 9751 | 2617 | BLACK SHOGI PIECE
☘ | 9752 | 2618 | SHAMROCK
☙ | 9753 | 2619 | REVERSED ROTATED FLORAL HEART BULLET
☚ | 9754 | 261A | BLACK LEFT POINTING INDEX
☛ | 9755 | 261B | BLACK RIGHT POINTING INDEX
☜ | 9756 | 261C | WHITE LEFT POINTING INDEX
☝ | 9757 | 261D | WHITE UP POINTING INDEX
☞ | 9758 | 261E | WHITE RIGHT POINTING INDEX
☟ | 9759 | 261F | WHITE DOWN POINTING INDEX
☠ | 9760 | 2620 | SKULL AND CROSSBONES
☡ | 9761 | 2621 | CAUTION SIGN
☢ | 9762 | 2622 | RADIOACTIVE SIGN
☣ | 9763 | 2623 | BIOHAZARD SIGN
☤ | 9764 | 2624 | CADUCEUS
☥ | 9765 | 2625 | ANKH
☦ | 9766 | 2626 | ORTHODOX CROSS
☧ | 9767 | 2627 | CHI RHO
☨ | 9768 | 2628 | CROSS OF LORRAINE
☩ | 9769 | 2629 | CROSS OF JERUSALEM
☪ | 9770 | 262A | STAR AND CRESCENT
☫ | 9771 | 262B | FARSI SYMBOL
☬ | 9772 | 262C | KHANDA
☭ | 9773 | 262D | HAMMER AND SICKLE
☮ | 9774 | 262E | PEACE SYMBOL
☯ | 9775 | 262F | YIN YANG
☰ | 9776 | 2630 | TRIGRAM FOR HEAVEN
☱ | 9777 | 2631 | TRIGRAM FOR LAKE
☲ | 9778 | 2632 | TRIGRAM FOR FIRE
☳ | 9779 | 2633 | TRIGRAM FOR THUNDER
☴ | 9780 | 2634 | TRIGRAM FOR WIND
☵ | 9781 | 2635 | TRIGRAM FOR WATER
☶ | 9782 | 2636 | TRIGRAM FOR MOUNTAIN
☷ | 9783 | 2637 | TRIGRAM FOR EARTH
☸ | 9784 | 2638 | WHEEL OF DHARMA
☹ | 9785 | 2639 | WHITE FROWNING FACE
☺ | 9786 | 263A | WHITE SMILING FACE
☻ | 9787 | 263B | BLACK SMILING FACE
☼ | 9788 | 263C | WHITE SUN WITH RAYS
☽ | 9789 | 263D | FIRST QUARTER MOON
☾ | 9790 | 263E | LAST QUARTER MOON
☿ | 9791 | 263F | MERCURY
♀ | 9792 | 2640 | FEMALE SIGN
♁ | 9793 | 2641 | EARTH
♂ | 9794 | 2642 | MALE SIGN
♃ | 9795 | 2643 | JUPITER
♄ | 9796 | 2644 | SATURN
♅ | 9797 | 2645 | URANUS
♆ | 9798 | 2646 | NEPTUNE
♇ | 9799 | 2647 | PLUTO
♈ | 9800 | 2648 | ARIES
♉ | 9801 | 2649 | TAURUS
♊ | 9802 | 264A | GEMINI
♋ | 9803 | 264B | CANCER
♌ | 9804 | 264C | LEO
♍ | 9805 | 264D | VIRGO
♎ | 9806 | 264E | LIBRA
♏ | 9807 | 264F | SCORPIUS
♐ | 9808 | 2650 | SAGITTARIUS
♑ | 9809 | 2651 | CAPRICORN
♒ | 9810 | 2652 | AQUARIUS
♓ | 9811 | 2653 | PISCES
♔ | 9812 | 2654 | WHITE CHESS KING
♕ | 9813 | 2655 | WHITE CHESS QUEEN
♖ | 9814 | 2656 | WHITE CHESS ROOK
♗ | 9815 | 2657 | WHITE CHESS BISHOP
♘ | 9816 | 2658 | WHITE CHESS KNIGHT
♙ | 9817 | 2659 | WHITE CHESS PAWN
♚ | 9818 | 265A | BLACK CHESS KING
♛ | 9819 | 265B | BLACK CHESS QUEEN
♜ | 9820 | 265C | BLACK CHESS ROOK
♝ | 9821 | 265D | BLACK CHESS BISHOP
♞ | 9822 | 265E | BLACK CHESS KNIGHT
♟ | 9823 | 265F | BLACK CHESS PAWN
♠ | 9824 | 2660 | BLACK SPADE SUIT
♡ | 9825 | 2661 | WHITE HEART SUIT
♢ | 9826 | 2662 | WHITE DIAMOND SUIT
♣ | 9827 | 2663 | BLACK CLUB SUIT
♤ | 9828 | 2664 | WHITE SPADE SUIT
♥ | 9829 | 2665 | BLACK HEART SUIT
♦ | 9830 | 2666 | BLACK DIAMOND SUIT
♧ | 9831 | 2667 | WHITE CLUB SUIT
♨ | 9832 | 2668 | HOT SPRINGS
♩ | 9833 | 2669 | QUARTER NOTE
♪ | 9834 | 266A | EIGHTH NOTE
♫ | 9835 | 266B | BEAMED EIGHTH NOTES
♬ | 9836 | 266C | BEAMED SIXTEENTH NOTES
♭ | 9837 | 266D | MUSIC FLAT SIGN
♮ | 9838 | 266E | MUSIC NATURAL SIGN
♯ | 9839 | 266F | MUSIC SHARP SIGN
♰ | 9840 | 2670 | WEST SYRIAC CROSS
♱ | 9841 | 2671 | EAST SYRIAC CROSS
♲ | 9842 | 2672 | UNIVERSAL RECYCLING SYMBOL
♳ | 9843 | 2673 | RECYCLING SYMBOL FOR TYPE-1 PLASTICS
♴ | 9844 | 2674 | RECYCLING SYMBOL FOR TYPE-2 PLASTICS
♵ | 9845 | 2675 | RECYCLING SYMBOL FOR TYPE-3 PLASTICS
♶ | 9846 | 2676 | RECYCLING SYMBOL FOR TYPE-4 PLASTICS
♷ | 9847 | 2677 | RECYCLING SYMBOL FOR TYPE-5 PLASTICS
♸ | 9848 | 2678 | RECYCLING SYMBOL FOR TYPE-6 PLASTICS
♹ | 9849 | 2679 | RECYCLING SYMBOL FOR TYPE-7 PLASTICS
♺ | 9850 | 267A | RECYCLING SYMBOL FOR GENERIC MATERIALS
♻ | 9851 | 267B | BLACK UNIVERSAL RECYCLING SYMBOL
♼ | 9852 | 267C | RECYCLED PAPER SYMBOL
♽ | 9853 | 267D | PARTIALLY-RECYCLED PAPER SYMBOL
♾ | 9854 | 267E | PERMANENT PAPER SIGN
♿ | 9855 | 267F | WHEELCHAIR SYMBOL
⚀ | 9856 | 2680 | DIE FACE-1
⚁ | 9857 | 2681 | DIE FACE-2
⚂ | 9858 | 2682 | DIE FACE-3
⚃ | 9859 | 2683 | DIE FACE-4
⚄ | 9860 | 2684 | DIE FACE-5
⚅ | 9861 | 2685 | DIE FACE-6
⚆ | 9862 | 2686 | WHITE CIRCLE WITH DOT RIGHT
⚇ | 9863 | 2687 | WHITE CIRCLE WITH TWO DOTS
⚈ | 9864 | 2688 | BLACK CIRCLE WITH WHITE DOT RIGHT
⚉ | 9865 | 2689 | BLACK CIRCLE WITH TWO WHITE DOTS
⚊ | 9866 | 268A | MONOGRAM FOR YANG
⚋ | 9867 | 268B | MONOGRAM FOR YIN
⚌ | 9868 | 268C | DIGRAM FOR GREATER YANG
⚍ | 9869 | 268D | DIGRAM FOR LESSER YIN
⚎ | 9870 | 268E | DIGRAM FOR LESSER YANG
⚏ | 9871 | 268F | DIGRAM FOR GREATER YIN
⚐ | 9872 | 2690 | WHITE FLAG
⚑ | 9873 | 2691 | BLACK FLAG
⚒ | 9874 | 2692 | HAMMER AND PICK
⚓ | 9875 | 2693 | ANCHOR
⚔ | 9876 | 2694 | CROSSED SWORDS
⚕ | 9877 | 2695 | STAFF OF AESCULAPIUS
⚖ | 9878 | 2696 | SCALES
⚗ | 9879 | 2697 | ALEMBIC
⚘ | 9880 | 2698 | FLOWER
⚙ | 9881 | 2699 | GEAR
⚚ | 9882 | 269A | STAFF OF HERMES
⚛ | 9883 | 269B | ATOM SYMBOL
⚜ | 9884 | 269C | FLEUR-DE-LIS
⚝ | 9885 | 269D | OUTLINED WHITE STAR
⚞ | 9886 | 269E | THREE LINES CONVERGING RIGHT
⚟ | 9887 | 269F | THREE LINES CONVERGING LEFT
⚠ | 9888 | 26A0 | WARNING SIGN
⚡ | 9889 | 26A1 | HIGH VOLTAGE SIGN
⚢ | 9890 | 26A2 | DOUBLED FEMALE SIGN
⚣ | 9891 | 26A3 | DOUBLED MALE SIGN
⚤ | 9892 | 26A4 | INTERLOCKED FEMALE AND MALE SIGN
⚥ | 9893 | 26A5 | MALE AND FEMALE SIGN
⚦ | 9894 | 26A6 | MALE WITH STROKE SIGN
⚧ | 9895 | 26A7 | MALE WITH STROKE AND MALE AND FEMALE SIGN
⚨ | 9896 | 26A8 | VERTICAL MALE WITH STROKE SIGN
⚩ | 9897 | 26A9 | HORIZONTAL MALE WITH STROKE SIGN
⚪ | 9898 | 26AA | MEDIUM WHITE CIRCLE
⚫ | 9899 | 26AB | MEDIUM BLACK CIRCLE
⚬ | 9900 | 26AC | MEDIUM SMALL WHITE CIRCLE
⚭ | 9901 | 26AD | MARRIAGE SYMBOL
⚮ | 9902 | 26AE | DIVORCE SYMBOL
⚯ | 9903 | 26AF | UNMARRIED PARTNERSHIP SYMBOL
⚰ | 9904 | 26B0 | COFFIN
⚱ | 9905 | 26B1 | FUNERAL URN
⚲ | 9906 | 26B2 | NEUTER
⚳ | 9907 | 26B3 | CERES
⚴ | 9908 | 26B4 | PALLAS
⚵ | 9909 | 26B5 | JUNO
⚶ | 9910 | 26B6 | VESTA
⚷ | 9911 | 26B7 | CHIRON
⚸ | 9912 | 26B8 | BLACK MOON LILITH
⚹ | 9913 | 26B9 | SEXTILE
⚺ | 9914 | 26BA | SEMISEXTILE
⚻ | 9915 | 26BB | QUINCUNX
⚼ | 9916 | 26BC | SESQUIQUADRATE
⚽ | 9917 | 26BD | SOCCER BALL
⚾ | 9918 | 26BE | BASEBALL
⚿ | 9919 | 26BF | SQUARED KEY
⛀ | 9920 | 26C0 | WHITE DRAUGHTS MAN
⛁ | 9921 | 26C1 | WHITE DRAUGHTS KING
⛂ | 9922 | 26C2 | BLACK DRAUGHTS MAN
⛃ | 9923 | 26C3 | BLACK DRAUGHTS KING
⛄ | 9924 | 26C4 | SNOWMAN WITHOUT SNOW
⛅ | 9925 | 26C5 | SUN BEHIND CLOUD
⛆ | 9926 | 26C6 | RAIN
⛇ | 9927 | 26C7 | BLACK SNOWMAN
⛈ | 9928 | 26C8 | THUNDER CLOUD AND RAIN
⛉ | 9929 | 26C9 | TURNED WHITE SHOGI PIECE
⛊ | 9930 | 26CA | TURNED BLACK SHOGI PIECE
⛋ | 9931 | 26CB | WHITE DIAMOND IN SQUARE
⛌ | 9932 | 26CC | CROSSING LANES
⛍ | 9933 | 26CD | DISABLED CAR
⛎ | 9934 | 26CE | OPHIUCHUS
⛏ | 9935 | 26CF | PICK
⛐ | 9936 | 26D0 | CAR SLIDING
⛑ | 9937 | 26D1 | HELMET WITH WHITE CROSS
⛒ | 9938 | 26D2 | CIRCLED CROSSING LANES
⛓ | 9939 | 26D3 | CHAINS
⛔ | 9940 | 26D4 | NO ENTRY
⛕ | 9941 | 26D5 | ALTERNATE ONE-WAY LEFT WAY TRAFFIC
⛖ | 9942 | 26D6 | BLACK TWO-WAY LEFT WAY TRAFFIC
⛗ | 9943 | 26D7 | WHITE TWO-WAY LEFT WAY TRAFFIC
⛘ | 9944 | 26D8 | BLACK LEFT LANE MERGE
⛙ | 9945 | 26D9 | WHITE LEFT LANE MERGE
⛚ | 9946 | 26DA | DRIVE SLOW SIGN
⛛ | 9947 | 26DB | HEAVY WHITE DOWN-POINTING TRIANGLE
⛜ | 9948 | 26DC | LEFT CLOSED ENTRY
⛝ | 9949 | 26DD | SQUARED SALTIRE
⛞ | 9950 | 26DE | FALLING DIAGONAL IN WHITE CIRCLE IN BLACK SQUARE
⛟ | 9951 | 26DF | BLACK TRUCK
⛠ | 9952 | 26E0 | RESTRICTED LEFT ENTRY-1
⛡ | 9953 | 26E1 | RESTRICTED LEFT ENTRY-2
⛢ | 9954 | 26E2 | ASTRONOMICAL SYMBOL FOR URANUS
⛣ | 9955 | 26E3 | HEAVY CIRCLE WITH STROKE AND TWO DOTS ABOVE
⛤ | 9956 | 26E4 | PENTAGRAM
⛥ | 9957 | 26E5 | RIGHT-HANDED INTERLACED PENTAGRAM
⛦ | 9958 | 26E6 | LEFT-HANDED INTERLACED PENTAGRAM
⛧ | 9959 | 26E7 | INVERTED PENTAGRAM
⛨ | 9960 | 26E8 | BLACK CROSS ON SHIELD
⛩ | 9961 | 26E9 | SHINTO SHRINE
⛪ | 9962 | 26EA | CHURCH
⛫ | 9963 | 26EB | CASTLE
⛬ | 9964 | 26EC | HISTORIC SITE
⛭ | 9965 | 26ED | GEAR WITHOUT HUB
⛮ | 9966 | 26EE | GEAR WITH HANDLES
⛯ | 9967 | 26EF | MAP SYMBOL FOR LIGHTHOUSE
⛰ | 9968 | 26F0 | MOUNTAIN
⛱ | 9969 | 26F1 | UMBRELLA ON GROUND
⛲ | 9970 | 26F2 | FOUNTAIN
⛳ | 9971 | 26F3 | FLAG IN HOLE
⛴ | 9972 | 26F4 | FERRY
⛵ | 9973 | 26F5 | SAILBOAT
⛶ | 9974 | 26F6 | SQUARE FOUR CORNERS
⛷ | 9975 | 26F7 | SKIER
⛸ | 9976 | 26F8 | ICE SKATE
⛹ | 9977 | 26F9 | PERSON WITH BALL
⛺ | 9978 | 26FA | TENT
⛻ | 9979 | 26FB | JAPANESE BANK SYMBOL
⛼ | 9980 | 26FC | HEADSTONE GRAVEYARD SYMBOL
⛽ | 9981 | 26FD | FUEL PUMP
⛾ | 9982 | 26FE | CUP ON BLACK SQUARE
⛿ | 9983 | 26FF | WHITE FLAG WITH HORIZONTAL MIDDLE BLACK STRIPE

## Dingbats

Hex 2700-27BF / Decimal 9984-10175.

Char | Dec | Hex | Name
--- | --- | --- | ---
✀ | 9984 | 2700 | BLACK SAFETY SCISSORS
✁ | 9985 | 2701 | UPPER BLADE SCISSORS
✂ | 9986 | 2702 | BLACK SCISSORS
✃ | 9987 | 2703 | LOWER BLADE SCISSORS
✄ | 9988 | 2704 | WHITE SCISSORS
✅ | 9989 | 2705 | WHITE HEAVY CHECK MARK
✆ | 9990 | 2706 | TELEPHONE LOCATION SIGN
✇ | 9991 | 2707 | TAPE DRIVE
✈ | 9992 | 2708 | AIRPLANE
✉ | 9993 | 2709 | ENVELOPE
✊ | 9994 | 270A | RAISED FIST
✋ | 9995 | 270B | RAISED HAND
✌ | 9996 | 270C | VICTORY HAND
✍ | 9997 | 270D | WRITING HAND
✎ | 9998 | 270E | LOWER RIGHT PENCIL
✏ | 9999 | 270F | PENCIL
✐ | 10000 | 2710 | UPPER RIGHT PENCIL
✑ | 10001 | 2711 | WHITE NIB
✒ | 10002 | 2712 | BLACK NIB
✓ | 10003 | 2713 | CHECK MARK
✔ | 10004 | 2714 | HEAVY CHECK MARK
✕ | 10005 | 2715 | MULTIPLICATION X
✖ | 10006 | 2716 | HEAVY MULTIPLICATION X
✗ | 10007 | 2717 | BALLOT X
✘ | 10008 | 2718 | HEAVY BALLOT X
✙ | 10009 | 2719 | OUTLINED GREEK CROSS
✚ | 10010 | 271A | HEAVY GREEK CROSS
✛ | 10011 | 271B | OPEN CENTRE CROSS
✜ | 10012 | 271C | HEAVY OPEN CENTRE CROSS
✝ | 10013 | 271D | LATIN CROSS
✞ | 10014 | 271E | SHADOWED WHITE LATIN CROSS
✟ | 10015 | 271F | OUTLINED LATIN CROSS
✠ | 10016 | 2720 | MALTESE CROSS
✡ | 10017 | 2721 | STAR OF DAVID
✢ | 10018 | 2722 | FOUR TEARDROP-SPOKED ASTERISK
✣ | 10019 | 2723 | FOUR BALLOON-SPOKED ASTERISK
✤ | 10020 | 2724 | HEAVY FOUR BALLOON-SPOKED ASTERISK
✥ | 10021 | 2725 | FOUR CLUB-SPOKED ASTERISK
✦ | 10022 | 2726 | BLACK FOUR POINTED STAR
✧ | 10023 | 2727 | WHITE FOUR POINTED STAR
✨ | 10024 | 2728 | SPARKLES
✩ | 10025 | 2729 | STRESS OUTLINED WHITE STAR
✪ | 10026 | 272A | CIRCLED WHITE STAR
✫ | 10027 | 272B | OPEN CENTRE BLACK STAR
✬ | 10028 | 272C | BLACK CENTRE WHITE STAR
✭ | 10029 | 272D | OUTLINED BLACK STAR
✮ | 10030 | 272E | HEAVY OUTLINED BLACK STAR
✯ | 10031 | 272F | PINWHEEL STAR
✰ | 10032 | 2730 | SHADOWED WHITE STAR
✱ | 10033 | 2731 | HEAVY ASTERISK
✲ | 10034 | 2732 | OPEN CENTRE ASTERISK
✳ | 10035 | 2733 | EIGHT SPOKED ASTERISK
✴ | 10036 | 2734 | EIGHT POINTED BLACK STAR
✵ | 10037 | 2735 | EIGHT POINTED PINWHEEL STAR
✶ | 10038 | 2736 | SIX POINTED BLACK STAR
✷ | 10039 | 2737 | EIGHT POINTED RECTILINEAR BLACK STAR
✸ | 10040 | 2738 | HEAVY EIGHT POINTED RECTILINEAR BLACK STAR
✹ | 10041 | 2739 | TWELVE POINTED BLACK STAR
✺ | 10042 | 273A | SIXTEEN POINTED ASTERISK
✻ | 10043 | 273B | TEARDROP-SPOKED ASTERISK
✼ | 10044 | 273C | OPEN CENTRE TEARDROP-SPOKED ASTERISK
✽ | 10045 | 273D | HEAVY TEARDROP-SPOKED ASTERISK
✾ | 10046 | 273E | SIX PETALLED BLACK AND WHITE FLORETTE
✿ | 10047 | 273F | BLACK FLORETTE
❀ | 10048 | 2740 | WHITE FLORETTE
❁ | 10049 | 2741 | EIGHT PETALLED OUTLINED BLACK FLORETTE
❂ | 10050 | 2742 | CIRCLED OPEN CENTRE EIGHT POINTED STAR
❃ | 10051 | 2743 | HEAVY TEARDROP-SPOKED PINWHEEL ASTERISK
❄ | 10052 | 2744 | SNOWFLAKE
❅ | 10053 | 2745 | TIGHT TRIFOLIATE SNOWFLAKE
❆ | 10054 | 2746 | HEAVY CHEVRON SNOWFLAKE
❇ | 10055 | 2747 | SPARKLE
❈ | 10056 | 2748 | HEAVY SPARKLE
❉ | 10057 | 2749 | BALLOON-SPOKED ASTERISK
❊ | 10058 | 274A | EIGHT TEARDROP-SPOKED PROPELLER ASTERISK
❋ | 10059 | 274B | HEAVY EIGHT TEARDROP-SPOKED PROPELLER ASTERISK
❌ | 10060 | 274C | CROSS MARK
❍ | 10061 | 274D | SHADOWED WHITE CIRCLE
❎ | 10062 | 274E | NEGATIVE SQUARED CROSS MARK
❏ | 10063 | 274F | LOWER RIGHT DROP-SHADOWED WHITE SQUARE
❐ | 10064 | 2750 | UPPER RIGHT DROP-SHADOWED WHITE SQUARE
❑ | 10065 | 2751 | LOWER RIGHT SHADOWED WHITE SQUARE
❒ | 10066 | 2752 | UPPER RIGHT SHADOWED WHITE SQUARE
❓ | 10067 | 2753 | BLACK QUESTION MARK ORNAMENT
❔ | 10068 | 2754 | WHITE QUESTION MARK ORNAMENT
❕ | 10069 | 2755 | WHITE EXCLAMATION MARK ORNAMENT
❖ | 10070 | 2756 | BLACK DIAMOND MINUS WHITE X
❗ | 10071 | 2757 | HEAVY EXCLAMATION MARK SYMBOL
❘ | 10072 | 2758 | LIGHT VERTICAL BAR
❙ | 10073 | 2759 | MEDIUM VERTICAL BAR
❚ | 10074 | 275A | HEAVY VERTICAL BAR
❛ | 10075 | 275B | HEAVY SINGLE TURNED COMMA QUOTATION MARK ORNAMENT
❜ | 10076 | 275C | HEAVY SINGLE COMMA QUOTATION MARK ORNAMENT
❝ | 10077 | 275D | HEAVY DOUBLE TURNED COMMA QUOTATION MARK ORNAMENT
❞ | 10078 | 275E | HEAVY DOUBLE COMMA QUOTATION MARK ORNAMENT
❟ | 10079 | 275F | HEAVY LOW SINGLE COMMA QUOTATION MARK ORNAMENT
❠ | 10080 | 2760 | HEAVY LOW DOUBLE COMMA QUOTATION MARK ORNAMENT
❡ | 10081 | 2761 | CURVED STEM PARAGRAPH SIGN ORNAMENT
❢ | 10082 | 2762 | HEAVY EXCLAMATION MARK ORNAMENT
❣ | 10083 | 2763 | HEAVY HEART EXCLAMATION MARK ORNAMENT
❤ | 10084 | 2764 | HEAVY BLACK HEART
❥ | 10085 | 2765 | ROTATED HEAVY BLACK HEART BULLET
❦ | 10086 | 2766 | FLORAL HEART
❧ | 10087 | 2767 | ROTATED FLORAL HEART BULLET
❨ | 10088 | 2768 | MEDIUM LEFT PARENTHESIS ORNAMENT
❩ | 10089 | 2769 | MEDIUM RIGHT PARENTHESIS ORNAMENT
❪ | 10090 | 276A | MEDIUM FLATTENED LEFT PARENTHESIS ORNAMENT
❫ | 10091 | 276B | MEDIUM FLATTENED RIGHT PARENTHESIS ORNAMENT
❬ | 10092 | 276C | MEDIUM LEFT-POINTING ANGLE BRACKET ORNAMENT
❭ | 10093 | 276D | MEDIUM RIGHT-POINTING ANGLE BRACKET ORNAMENT
❮ | 10094 | 276E | HEAVY LEFT-POINTING ANGLE QUOTATION MARK ORNAMENT
❯ | 10095 | 276F | HEAVY RIGHT-POINTING ANGLE QUOTATION MARK ORNAMENT
❰ | 10096 | 2770 | HEAVY LEFT-POINTING ANGLE BRACKET ORNAMENT
❱ | 10097 | 2771 | HEAVY RIGHT-POINTING ANGLE BRACKET ORNAMENT
❲ | 10098 | 2772 | LIGHT LEFT TORTOISE SHELL BRACKET ORNAMENT
❳ | 10099 | 2773 | LIGHT RIGHT TORTOISE SHELL BRACKET ORNAMENT
❴ | 10100 | 2774 | MEDIUM LEFT CURLY BRACKET ORNAMENT
❵ | 10101 | 2775 | MEDIUM RIGHT CURLY BRACKET ORNAMENT
❶ | 10102 | 2776 | DINGBAT NEGATIVE CIRCLED DIGIT ONE
❷ | 10103 | 2777 | DINGBAT NEGATIVE CIRCLED DIGIT TWO
❸ | 10104 | 2778 | DINGBAT NEGATIVE CIRCLED DIGIT THREE
❹ | 10105 | 2779 | DINGBAT NEGATIVE CIRCLED DIGIT FOUR
❺ | 10106 | 277A | DINGBAT NEGATIVE CIRCLED DIGIT FIVE
❻ | 10107 | 277B | DINGBAT NEGATIVE CIRCLED DIGIT SIX
❼ | 10108 | 277C | DINGBAT NEGATIVE CIRCLED DIGIT SEVEN
❽ | 10109 | 277D | DINGBAT NEGATIVE CIRCLED DIGIT EIGHT
❾ | 10110 | 277E | DINGBAT NEGATIVE CIRCLED DIGIT NINE
❿ | 10111 | 277F | DINGBAT NEGATIVE CIRCLED NUMBER TEN
➀ | 10112 | 2780 | DINGBAT CIRCLED SANS-SERIF DIGIT ONE
➁ | 10113 | 2781 | DINGBAT CIRCLED SANS-SERIF DIGIT TWO
➂ | 10114 | 2782 | DINGBAT CIRCLED SANS-SERIF DIGIT THREE
➃ | 10115 | 2783 | DINGBAT CIRCLED SANS-SERIF DIGIT FOUR
➄ | 10116 | 2784 | DINGBAT CIRCLED SANS-SERIF DIGIT FIVE
➅ | 10117 | 2785 | DINGBAT CIRCLED SANS-SERIF DIGIT SIX
➆ | 10118 | 2786 | DINGBAT CIRCLED SANS-SERIF DIGIT SEVEN
➇ | 10119 | 2787 | DINGBAT CIRCLED SANS-SERIF DIGIT EIGHT
➈ | 10120 | 2788 | DINGBAT CIRCLED SANS-SERIF DIGIT NINE
➉ | 10121 | 2789 | DINGBAT CIRCLED SANS-SERIF NUMBER TEN
➊ | 10122 | 278A | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT ONE
➋ | 10123 | 278B | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT TWO
➌ | 10124 | 278C | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT THREE
➍ | 10125 | 278D | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT FOUR
➎ | 10126 | 278E | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT FIVE
➏ | 10127 | 278F | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT SIX
➐ | 10128 | 2790 | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT SEVEN
➑ | 10129 | 2791 | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT EIGHT
➒ | 10130 | 2792 | DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT NINE
➓ | 10131 | 2793 | DINGBAT NEGATIVE CIRCLED SANS-SERIF NUMBER TEN
➔ | 10132 | 2794 | HEAVY WIDE-HEADED RIGHTWARDS ARROW
➕ | 10133 | 2795 | HEAVY PLUS SIGN
➖ | 10134 | 2796 | HEAVY MINUS SIGN
➗ | 10135 | 2797 | HEAVY DIVISION SIGN
➘ | 10136 | 2798 | HEAVY SOUTH EAST ARROW
➙ | 10137 | 2799 | HEAVY RIGHTWARDS ARROW
➚ | 10138 | 279A | HEAVY NORTH EAST ARROW
➛ | 10139 | 279B | DRAFTING POINT RIGHTWARDS ARROW
➜ | 10140 | 279C | HEAVY ROUND-TIPPED RIGHTWARDS ARROW
➝ | 10141 | 279D | TRIANGLE-HEADED RIGHTWARDS ARROW
➞ | 10142 | 279E | HEAVY TRIANGLE-HEADED RIGHTWARDS ARROW
➟ | 10143 | 279F | DASHED TRIANGLE-HEADED RIGHTWARDS ARROW
➠ | 10144 | 27A0 | HEAVY DASHED TRIANGLE-HEADED RIGHTWARDS ARROW
➡ | 10145 | 27A1 | BLACK RIGHTWARDS ARROW
➢ | 10146 | 27A2 | THREE-D TOP-LIGHTED RIGHTWARDS ARROWHEAD
➣ | 10147 | 27A3 | THREE-D BOTTOM-LIGHTED RIGHTWARDS ARROWHEAD
➤ | 10148 | 27A4 | BLACK RIGHTWARDS ARROWHEAD
➥ | 10149 | 27A5 | HEAVY BLACK CURVED DOWNWARDS AND RIGHTWARDS ARROW
➦ | 10150 | 27A6 | HEAVY BLACK CURVED UPWARDS AND RIGHTWARDS ARROW
➧ | 10151 | 27A7 | SQUAT BLACK RIGHTWARDS ARROW
➨ | 10152 | 27A8 | HEAVY CONCAVE-POINTED BLACK RIGHTWARDS ARROW
➩ | 10153 | 27A9 | RIGHT-SHADED WHITE RIGHTWARDS ARROW
➪ | 10154 | 27AA | LEFT-SHADED WHITE RIGHTWARDS ARROW
➫ | 10155 | 27AB | BACK-TILTED SHADOWED WHITE RIGHTWARDS ARROW
➬ | 10156 | 27AC | FRONT-TILTED SHADOWED WHITE RIGHTWARDS ARROW
➭ | 10157 | 27AD | HEAVY LOWER RIGHT-SHADOWED WHITE RIGHTWARDS ARROW
➮ | 10158 | 27AE | HEAVY UPPER RIGHT-SHADOWED WHITE RIGHTWARDS ARROW
➯ | 10159 | 27AF | NOTCHED LOWER RIGHT-SHADOWED WHITE RIGHTWARDS ARROW
➰ | 10160 | 27B0 | CURLY LOOP
➱ | 10161 | 27B1 | NOTCHED UPPER RIGHT-SHADOWED WHITE RIGHTWARDS ARROW
➲ | 10162 | 27B2 | CIRCLED HEAVY WHITE RIGHTWARDS ARROW
➳ | 10163 | 27B3 | WHITE-FEATHERED RIGHTWARDS ARROW
➴ | 10164 | 27B4 | BLACK-FEATHERED SOUTH EAST ARROW
➵ | 10165 | 27B5 | BLACK-FEATHERED RIGHTWARDS ARROW
➶ | 10166 | 27B6 | BLACK-FEATHERED NORTH EAST ARROW
➷ | 10167 | 27B7 | HEAVY BLACK-FEATHERED SOUTH EAST ARROW
➸ | 10168 | 27B8 | HEAVY BLACK-FEATHERED RIGHTWARDS ARROW
➹ | 10169 | 27B9 | HEAVY BLACK-FEATHERED NORTH EAST ARROW
➺ | 10170 | 27BA | TEARDROP-BARBED RIGHTWARDS ARROW
➻ | 10171 | 27BB | HEAVY TEARDROP-SHANKED RIGHTWARDS ARROW
➼ | 10172 | 27BC | WEDGE-TAILED RIGHTWARDS ARROW
➽ | 10173 | 27BD | HEAVY WEDGE-TAILED RIGHTWARDS ARROW
➾ | 10174 | 27BE | OPEN-OUTLINED RIGHTWARDS ARROW
➿ | 10175 | 27BF | DOUBLE CURLY LOOP
⤴ | 10548 | 2934 | 
⤵ | 10549 | 2935 | 
⬅ | 11013 | 2B05 | 
⬆ | 11014 | 2B06 | 
⬇ | 11015 | 2B07 | 

## Miscellaneous Technical

Hex 2300-23FF / Decimal 8960-9215.

Char | Dec | Hex | Name
--- | --- | --- | ---
⌀ | 8960 | 2300 | Diameter sign
⌁ | 8961 | 2301 | Electric arrow
⌂ | 8962 | 2302 | House
⌃ | 8963 | 2303 | Up arrowhead
⌄ | 8964 | 2304 | Down arrowhead
⌅ | 8965 | 2305 | Projective
⌆ | 8966 | 2306 | Perspective
⌇ | 8967 | 2307 | Wavy line
⌈ | 8968 | 2308 | Left ceiling
⌉ | 8969 | 2309 | Right ceiling
⌊ | 8970 | 230A | Left floor
⌋ | 8971 | 230B | Right floor
⌌ | 8972 | 230C | Bottom right crop
⌍ | 8973 | 230D | Botton left crop
⌎ | 8974 | 230E | Top right crop
⌏ | 8975 | 230F | Top left crop
⌐ | 8976 | 2310 | Reversed not sign
⌑ | 8977 | 2311 | Square lozenge
⌒ | 8978 | 2312 | Arc
⌓ | 8979 | 2313 | Segment
⌔ | 8980 | 2314 | Sector
⌕ | 8981 | 2315 | Telephone recorder
⌖ | 8982 | 2316 | Position indicator
⌗ | 8983 | 2317 | Viewdata square
⌘ | 8984 | 2318 | Place of interest sign
⌙ | 8985 | 2319 | Turned not sign
⌚ | 8986 | 231A | Watch
⌛ | 8987 | 231B | Houglass
⌜ | 8988 | 231C | Top left corner
⌝ | 8989 | 231D | Top right corner
⌞ | 8990 | 231E | Bottom left corner
⌟ | 8991 | 231F | Bottom right corner
⌠ | 8992 | 2320 | Top half integral
⌡ | 8993 | 2321 | Bottom half integral
⌢ | 8994 | 2322 | Frown
⌣ | 8995 | 2323 | Smile
⌤ | 8996 | 2324 | Up arrowhead between bars
⌥ | 8997 | 2325 | Option key
⌦ | 8998 | 2326 | Erase to the right
⌧ | 8999 | 2327 | X in a rectangle box
⌨ | 9000 | 2328 | Keyboard
〈 | 9001 | 2329 | Left pointing angle bracket
〉 | 9002 | 232A | Right pointing angle bracket
⌫ | 9003 | 232B | Erase to the left
⌬ | 9004 | 232C | Benzene ring
⌭ | 9005 | 232D | Cylindricity
⌮ | 9006 | 232E | All around profile
⌯ | 9007 | 2330 | Symmetry
⌰ | 9008 | 2331 | Total runout
⌱ | 9009 | 2332 | Dimension origin
⌲ | 9010 | 2333 | Conical taper
⌳ | 9011 | 2333 |   | 
⌴ | 9012 | 2334 |   | 
⌵ | 9013 | 2335 |   | 
⌶ | 9014 | 2336 |   | 
⌷ | 9015 | 2337 |   | 
⌸ | 9016 | 2338 |   | 
⌹ | 9017 | 2339 |   | 
⌺ | 9018 | 233A |   | 
⌻ | 9019 | 233B |   | 
⌼ | 9020 | 233C |   | 
⌽ | 9021 | 233D |   | 
⌾ | 9022 | 233E |   | 
⌿ | 9023 | 233F |   | 
⍀ | 9024 | 2340 |   | 
⍁ | 9025 | 2341 |   | 
⍂ | 9026 | 2342 |   | 
⍃ | 9027 | 2343 |   | 
⍄ | 9028 | 2344 |   | 
⍅ | 9029 | 2345 |   | 
⍆ | 9030 | 2346 |   | 
⍇ | 9031 | 2347 |   | 
⍈ | 9032 | 2348 |   | 
⍉ | 9033 | 2349 |   | 
⍊ | 9034 | 234A |   | 
⍋ | 9035 | 234B |   | 
⍌ | 9036 | 234C |   | 
⍍ | 9037 | 234D |   | 
⍎ | 9038 | 234E |   | 
⍏ | 9039 | 234F |   | 
⍐ | 9040 | 2350 |   | 
⍑ | 9041 | 2351 |   | 
⍒ | 9042 | 2352 |   | 
⍓ | 9043 | 2353 |   | 
⍔ | 9044 | 2354 |   | 
⍕ | 9045 | 2355 |   | 
⍖ | 9046 | 2356 |   | 
⍗ | 9047 | 2357 |   | 
⍘ | 9048 | 2358 |   | 
⍙ | 9049 | 2359 |   | 
⍚ | 9050 | 235A |   | 
⍛ | 9051 | 235B |   | 
⍜ | 9052 | 235C |   | 
⍝ | 9053 | 235D |   | 
⍞ | 9054 | 235E |   | 
⍟ | 9055 | 235F |   | 
⍠ | 9056 | 2360 |   | 
⍡ | 9057 | 2361 |   | 
⍢ | 9058 | 2362 |   | 
⍣ | 9059 | 2363 |   | 
⍤ | 9060 | 2364 |   | 
⍥ | 9061 | 2365 |   | 
⍦ | 9062 | 2366 |   | 
⍧ | 9063 | 2367 |   | 
⍨ | 9064 | 2368 |   | 
⍩ | 9065 | 2369 |   | 
⍪ | 9066 | 236A |   | 
⍫ | 9067 | 236B |   | 
⍬ | 9068 | 236C |   | 
⍭ | 9069 | 236D |   | 
⍮ | 9070 | 236E |   | 
⍯ | 9071 | 236F |   | 
⍰ | 9072 | 2370 |   | 
⍱ | 9073 | 2371 |   | 
⍲ | 9074 | 2372 |   | 
⍳ | 9075 | 2373 |   | 
⍴ | 9076 | 2374 |   | 
⍵ | 9077 | 2375 |   | 
⍶ | 9078 | 2376 |   | 
⍷ | 9079 | 2377 |   | 
⍸ | 9080 | 2378 |   | 
⍹ | 9081 | 2379 |   | 
⍺ | 9082 | 237A |   | 
⍻ | 9083 | 237B |   | 
⍼ | 9084 | 237C |   | 
⍽ | 9085 | 237D |   | 
⍾ | 9086 | 237E |   | 
⍿ | 9087 | 237F |   | 
⎀ | 9088 | 2380 |   | 
⎁ | 9089 | 2381 |   | 
⎂ | 9090 | 2382 |   | 
⎃ | 9091 | 2383 |   | 
⎄ | 9092 | 2384 |   | 
⎅ | 9093 | 2385 |   | 
⎆ | 9094 | 2386 |   | 
⎇ | 9095 | 2387 |   | 
⎈ | 9096 | 2388 |   | 
⎉ | 9097 | 2389 |   | 
⎊ | 9098 | 238A |   | 
⎋ | 9099 | 238B |   | 
⎌ | 9100 | 238C |   | 
⎍ | 9101 | 238D |   | 
⎎ | 9102 | 238E |   | 
⎏ | 9103 | 238F |   | 
⎐ | 9104 | 2390 |   | 
⎑ | 9105 | 2391 |   | 
⎒ | 9106 | 2392 |   | 
⎓ | 9107 | 2393 |   | 
⎔ | 9108 | 2394 |   | 
⎕ | 9109 | 2395 |   | 
⎖ | 9110 | 2396 |   | 
⎗ | 9111 | 2397 |   | 
⎘ | 9112 | 2398 |   | 
⎙ | 9113 | 2399 |   | 
⎚ | 9114 | 239A |   | 
⎛ | 9115 | 239B |   | 
⎜ | 9116 | 239C |   | 
⎝ | 9117 | 239D |   | 
⎞ | 9118 | 239E |   | 
⎟ | 9119 | 239F |   | 
⎠ | 9120 | 23A0 |   | 
⎡ | 9121 | 23A1 |   | 
⎢ | 9122 | 23A2 |   | 
⎣ | 9123 | 23A3 |   | 
⎤ | 9124 | 23A4 |   | 
⎥ | 9125 | 23A5 |   | 
⎦ | 9126 | 23A6 |   | 
⎧ | 9127 | 23A7 |   | 
⎨ | 9128 | 23A8 |   | 
⎩ | 9129 | 23A9 |   | 
⎪ | 9130 | 23AA |   | 
⎫ | 9131 | 23AB |   | 
⎬ | 9132 | 23AC |   | 
⎭ | 9133 | 23AD |   | 
⎮ | 9134 | 23AE |   | 
⎯ | 9135 | 23AF |   | 
⎰ | 9136 | 23B0 |   | 
⎱ | 9137 | 23B1 |   | 
⎲ | 9138 | 23B2 |   | 
⎳ | 9139 | 23B3 |   | 
⎴ | 9140 | 23B4 |   | 
⎵ | 9141 | 23B5 |   | 
⎶ | 9142 | 23B6 |   | 
⎷ | 9143 | 23B7 |   | 
⎸ | 9144 | 23B8 |   | 
⎹ | 9145 | 23B9 |   | 
⎺ | 9146 | 23BA |   | 
⎻ | 9147 | 23BB |   | 
⎼ | 9148 | 23BC |   | 
⎽ | 9149 | 23BD |   | 
⎾ | 9150 | 23BE |   | 
⎿ | 9151 | 23BF |   | 
⏀ | 9152 | 23C0 |   | 
⏁ | 9153 | 23C1 |   | 
⏂ | 9154 | 23C2 |   | 
⏃ | 9155 | 23C3 |   | 
⏄ | 9156 | 23C4 |   | 
⏅ | 9157 | 23C5 |   | 
⏆ | 9158 | 23C6 |   | 
⏇ | 9159 | 23C7 |   | 
⏈ | 9160 | 23C8 |   | 
⏉ | 9161 | 23C9 |   | 
⏊ | 9162 | 23CA |   | 
⏋ | 9163 | 23CB |   | 
⏌ | 9164 | 23CC |   | 
⏍ | 9165 | 23CD |   | 
⏎ | 9166 | 23CE |   | 
⏏ | 9167 | 23CF |   | 
⏐ | 9168 | 23D0 |   | 
⏑ | 9169 | 23D1 |   | 
⏒ | 9170 | 23D2 |   | 
⏓ | 9171 | 23D3 |   | 
⏔ | 9172 | 23D4 |   | 
⏕ | 9173 | 23D5 |   | 
⏖ | 9174 | 23D6 |   | 
⏗ | 9175 | 23D7 |   | 
⏘ | 9176 | 23D8 |   | 
⏙ | 9177 | 23D9 |   | 
⏚ | 9178 | 23DA |   | 
⏛ | 9179 | 23DB |   | 
⏜ | 9180 | 23DC |   | 
⏝ | 9181 | 23DD |   | 
⏞ | 9182 | 23DE |   | 
⏟ | 9183 | 23DF |   | 
⏠ | 9184 | 23E0 |   | 
⏡ | 9185 | 23E1 |   | 
⏢ | 9186 | 23E2 |   | 
⏣ | 9187 | 23E3 |   | 
⏤ | 9188 | 23E4 |   | 
⏥ | 9189 | 23E5 |   | 
⏦ | 9190 | 23E6 |   | 
⏧ | 9191 | 23E7 |   | 
⏨ | 9192 | 23E8 |   | 
⏩ | 9193 | 23E9 |   | 
⏪ | 9194 | 23EA |   | 
⏫ | 9195 | 23EB |   | 
⏬ | 9196 | 23EC |   | 
⏭ | 9197 | 23ED |   | 
⏮ | 9198 | 23EE |   | 
⏯ | 9199 | 23EF |   | 
⏰ | 9200 | 23F0 |   | 
⏱ | 9201 | 23F1 |   | 
⏲ | 9202 | 23F2 |   | 
⏳ | 9203 | 23F3 |   | 
⏴ | 9204 | 23F4 |   | 
⏵ | 9205 | 23F5 |   | 
⏶ | 9206 | 23F6 |   | 
⏷ | 9207 | 23F7 |   | 
⏸ | 9208 | 23F8 |   | 
⏹ | 9209 | 23F9 |   | 
⏺ | 9210 | 23FA |   | 
⏻ | 9211 | 23FB |   | 
⏼ | 9212 | 23FC |   | 
⏽ | 9213 | 23FD |   | 
⏾ | 9214 | 23FE |   | 
⏿ | 9215 | 23FF |  

## Enclosed Alphanumerics

Hex 2460-24FF / Decimal 9312-9471.

| Char | Dec  | Hex  | Name                               |
| ---- | ---- | ---- | ---------------------------------- |
| ①    | 9312 | 2460 | CIRCLED DIGIT ONE                  |
| ②    | 9313 | 2461 | CIRCLED DIGIT TWO                  |
| ③    | 9314 | 2462 | CIRCLED DIGIT THREE                |
| ④    | 9315 | 2463 | CIRCLED DIGIT FOUR                 |
| ⑤    | 9316 | 2464 | CIRCLED DIGIT FIVE                 |
| ⑥    | 9317 | 2465 | CIRCLED DIGIT SIX                  |
| ⑦    | 9318 | 2466 | CIRCLED DIGIT SEVEN                |
| ⑧    | 9319 | 2467 | CIRCLED DIGIT EIGHT                |
| ⑨    | 9320 | 2468 | CIRCLED DIGIT NINE                 |
| ⑩    | 9321 | 2469 | CIRCLED NUMBER TEN                 |
| ⑪    | 9322 | 246A | CIRCLED NUMBER ELEVEN              |
| ⑫    | 9323 | 246B | CIRCLED NUMBER TWELVE              |
| ⑬    | 9324 | 246C | CIRCLED NUMBER THIRTEEN            |
| ⑭    | 9325 | 246D | CIRCLED NUMBER FOURTEEN            |
| ⑮    | 9326 | 246E | CIRCLED NUMBER FIFTEEN             |
| ⑯    | 9327 | 246F | CIRCLED NUMBER SIXTEEN             |
| ⑰    | 9328 | 2470 | CIRCLED NUMBER SEVENTEEN           |
| ⑱    | 9329 | 2471 | CIRCLED NUMBER EIGHTEEN            |
| ⑲    | 9330 | 2472 | CIRCLED NUMBER NINETEEN            |
| ⑳    | 9331 | 2473 | CIRCLED NUMBER TWENTY              |
| ⑴    | 9332 | 2474 | PARENTHESIZED DIGIT ONE            |
| ⑵    | 9333 | 2475 | PARENTHESIZED DIGIT TWO            |
| ⑶    | 9334 | 2476 | PARENTHESIZED DIGIT THREE          |
| ⑷    | 9335 | 2477 | PARENTHESIZED DIGIT FOUR           |
| ⑸    | 9336 | 2478 | PARENTHESIZED DIGIT FIVE           |
| ⑹    | 9337 | 2479 | PARENTHESIZED DIGIT SIX            |
| ⑺    | 9338 | 247A | PARENTHESIZED DIGIT SEVEN          |
| ⑻    | 9339 | 247B | PARENTHESIZED DIGIT EIGHT          |
| ⑼    | 9340 | 247C | PARENTHESIZED DIGIT NINE           |
| ⑽    | 9341 | 247D | PARENTHESIZED NUMBER TEN           |
| ⑾    | 9342 | 247E | PARENTHESIZED NUMBER ELEVEN        |
| ⑿    | 9343 | 247F | PARENTHESIZED NUMBER TWELVE        |
| ⒀    | 9344 | 2480 | PARENTHESIZED NUMBER THIRTEEN      |
| ⒁    | 9345 | 2481 | PARENTHESIZED NUMBER FOURTEEN      |
| ⒂    | 9346 | 2482 | PARENTHESIZED NUMBER FIFTEEN       |
| ⒃    | 9347 | 2483 | PARENTHESIZED NUMBER SIXTEEN       |
| ⒄    | 9348 | 2484 | PARENTHESIZED NUMBER SEVENTEEN     |
| ⒅    | 9349 | 2485 | PARENTHESIZED NUMBER EIGHTEEN      |
| ⒆    | 9350 | 2486 | PARENTHESIZED NUMBER NINETEEN      |
| ⒇    | 9351 | 2487 | PARENTHESIZED NUMBER TWENTY        |
| ⒈    | 9352 | 2488 | DIGIT ONE FULL STOP                |
| ⒉    | 9353 | 2489 | DIGIT TWO FULL STOP                |
| ⒊    | 9354 | 248A | DIGIT THREE FULL STOP              |
| ⒋    | 9355 | 248B | DIGIT FOUR FULL STOP               |
| ⒌    | 9356 | 248C | DIGIT FIVE FULL STOP               |
| ⒍    | 9357 | 248D | DIGIT SIX FULL STOP                |
| ⒎    | 9358 | 248E | DIGIT SEVEN FULL STOP              |
| ⒏    | 9359 | 248F | DIGIT EIGHT FULL STOP              |
| ⒐    | 9360 | 2490 | DIGIT NINE FULL STOP               |
| ⒑    | 9361 | 2491 | NUMBER TEN FULL STOP               |
| ⒒    | 9362 | 2492 | NUMBER ELEVEN FULL STOP            |
| ⒓    | 9363 | 2493 | NUMBER TWELVE FULL STOP            |
| ⒔    | 9364 | 2494 | NUMBER THIRTEEN FULL STOP          |
| ⒕    | 9365 | 2495 | NUMBER FOURTEEN FULL STOP          |
| ⒖    | 9366 | 2496 | NUMBER FIFTEEN FULL STOP           |
| ⒗    | 9367 | 2497 | NUMBER SIXTEEN FULL STOP           |
| ⒘    | 9368 | 2498 | NUMBER SEVENTEEN FULL STOP         |
| ⒙    | 9369 | 2499 | NUMBER EIGHTEEN FULL STOP          |
| ⒚    | 9370 | 249A | NUMBER NINETEEN FULL STOP          |
| ⒛    | 9371 | 249B | NUMBER TWENTY FULL STOP            |
| ⒜    | 9372 | 249C | PARENTHESIZED LATIN SMALL LETTER A |
| ⒝    | 9373 | 249D | PARENTHESIZED LATIN SMALL LETTER B |
| ⒞    | 9374 | 249E | PARENTHESIZED LATIN SMALL LETTER C |
| ⒟    | 9375 | 249F | PARENTHESIZED LATIN SMALL LETTER D |
| ⒠    | 9376 | 24A0 | PARENTHESIZED LATIN SMALL LETTER E |
| ⒡    | 9377 | 24A1 | PARENTHESIZED LATIN SMALL LETTER F |
| ⒢    | 9378 | 24A2 | PARENTHESIZED LATIN SMALL LETTER G |
| ⒣    | 9379 | 24A3 | PARENTHESIZED LATIN SMALL LETTER H |
| ⒤    | 9380 | 24A4 | PARENTHESIZED LATIN SMALL LETTER I |
| ⒥    | 9381 | 24A5 | PARENTHESIZED LATIN SMALL LETTER J |
| ⒦    | 9382 | 24A6 | PARENTHESIZED LATIN SMALL LETTER K |
| ⒧    | 9383 | 24A7 | PARENTHESIZED LATIN SMALL LETTER L |
| ⒨    | 9384 | 24A8 | PARENTHESIZED LATIN SMALL LETTER M |
| ⒩    | 9385 | 24A9 | PARENTHESIZED LATIN SMALL LETTER N |
| ⒪    | 9386 | 24AA | PARENTHESIZED LATIN SMALL LETTER O |
| ⒫    | 9387 | 24AB | PARENTHESIZED LATIN SMALL LETTER P |
| ⒬    | 9388 | 24AC | PARENTHESIZED LATIN SMALL LETTER Q |
| ⒭    | 9389 | 24AD | PARENTHESIZED LATIN SMALL LETTER R |
| ⒮    | 9390 | 24AE | PARENTHESIZED LATIN SMALL LETTER S |
| ⒯    | 9391 | 24AF | PARENTHESIZED LATIN SMALL LETTER T |
| ⒰    | 9392 | 24B0 | PARENTHESIZED LATIN SMALL LETTER U |
| ⒱    | 9393 | 24B1 | PARENTHESIZED LATIN SMALL LETTER V |
| ⒲    | 9394 | 24B2 | PARENTHESIZED LATIN SMALL LETTER W |
| ⒳    | 9395 | 24B3 | PARENTHESIZED LATIN SMALL LETTER X |
| ⒴    | 9396 | 24B4 | PARENTHESIZED LATIN SMALL LETTER Y |
| ⒵    | 9397 | 24B5 | PARENTHESIZED LATIN SMALL LETTER Z |
| Ⓐ    | 9398 | 24B6 | CIRCLED LATIN CAPITAL LETTER A     |
| Ⓑ    | 9399 | 24B7 | CIRCLED LATIN CAPITAL LETTER B     |
| Ⓒ    | 9400 | 24B8 | CIRCLED LATIN CAPITAL LETTER C     |
| Ⓓ    | 9401 | 24B9 | CIRCLED LATIN CAPITAL LETTER D     |
| Ⓔ    | 9402 | 24BA | CIRCLED LATIN CAPITAL LETTER E     |
| Ⓕ    | 9403 | 24BB | CIRCLED LATIN CAPITAL LETTER F     |
| Ⓖ    | 9404 | 24BC | CIRCLED LATIN CAPITAL LETTER G     |
| Ⓗ    | 9405 | 24BD | CIRCLED LATIN CAPITAL LETTER H     |
| Ⓘ    | 9406 | 24BE | CIRCLED LATIN CAPITAL LETTER I     |
| Ⓙ    | 9407 | 24BF | CIRCLED LATIN CAPITAL LETTER J     |
| Ⓚ    | 9408 | 24C0 | CIRCLED LATIN CAPITAL LETTER K     |
| Ⓛ    | 9409 | 24C1 | CIRCLED LATIN CAPITAL LETTER L     |
| Ⓜ    | 9410 | 24C2 | CIRCLED LATIN CAPITAL LETTER M     |
| Ⓝ    | 9411 | 24C3 | CIRCLED LATIN CAPITAL LETTER N     |
| Ⓞ    | 9412 | 24C4 | CIRCLED LATIN CAPITAL LETTER O     |
| Ⓟ    | 9413 | 24C5 | CIRCLED LATIN CAPITAL LETTER P     |
| Ⓠ    | 9414 | 24C6 | CIRCLED LATIN CAPITAL LETTER Q     |
| Ⓡ    | 9415 | 24C7 | CIRCLED LATIN CAPITAL LETTER R     |
| Ⓢ    | 9416 | 24C8 | CIRCLED LATIN CAPITAL LETTER S     |
| Ⓣ    | 9417 | 24C9 | CIRCLED LATIN CAPITAL LETTER T     |
| Ⓤ    | 9418 | 24CA | CIRCLED LATIN CAPITAL LETTER U     |
| Ⓥ    | 9419 | 24CB | CIRCLED LATIN CAPITAL LETTER V     |
| Ⓦ    | 9420 | 24CC | CIRCLED LATIN CAPITAL LETTER W     |
| Ⓧ    | 9421 | 24CD | CIRCLED LATIN CAPITAL LETTER X     |
| Ⓨ    | 9422 | 24CE | CIRCLED LATIN CAPITAL LETTER Y     |
| Ⓩ    | 9423 | 24CF | CIRCLED LATIN CAPITAL LETTER Z     |
| ⓐ    | 9424 | 24D0 | CIRCLED LATIN SMALL LETTER A       |
| ⓑ    | 9425 | 24D1 | CIRCLED LATIN SMALL LETTER B       |
| ⓒ    | 9426 | 24D2 | CIRCLED LATIN SMALL LETTER C       |
| ⓓ    | 9427 | 24D3 | CIRCLED LATIN SMALL LETTER D       |
| ⓔ    | 9428 | 24D4 | CIRCLED LATIN SMALL LETTER E       |
| ⓕ    | 9429 | 24D5 | CIRCLED LATIN SMALL LETTER F       |
| ⓖ    | 9430 | 24D6 | CIRCLED LATIN SMALL LETTER G       |
| ⓗ    | 9431 | 24D7 | CIRCLED LATIN SMALL LETTER H       |
| ⓘ    | 9432 | 24D8 | CIRCLED LATIN SMALL LETTER I       |
| ⓙ    | 9433 | 24D9 | CIRCLED LATIN SMALL LETTER J       |
| ⓚ    | 9434 | 24DA | CIRCLED LATIN SMALL LETTER K       |
| ⓛ    | 9435 | 24DB | CIRCLED LATIN SMALL LETTER L       |
| ⓜ    | 9436 | 24DC | CIRCLED LATIN SMALL LETTER M       |
| ⓝ    | 9437 | 24DD | CIRCLED LATIN SMALL LETTER N       |
| ⓞ    | 9438 | 24DE | CIRCLED LATIN SMALL LETTER O       |
| ⓟ    | 9439 | 24DF | CIRCLED LATIN SMALL LETTER P       |
| ⓠ    | 9440 | 24E0 | CIRCLED LATIN SMALL LETTER Q       |
| ⓡ    | 9441 | 24E1 | CIRCLED LATIN SMALL LETTER R       |
| ⓢ    | 9442 | 24E2 | CIRCLED LATIN SMALL LETTER S       |
| ⓣ    | 9443 | 24E3 | CIRCLED LATIN SMALL LETTER T       |
| ⓤ    | 9444 | 24E4 | CIRCLED LATIN SMALL LETTER U       |
| ⓥ    | 9445 | 24E5 | CIRCLED LATIN SMALL LETTER V       |
| ⓦ    | 9446 | 24E6 | CIRCLED LATIN SMALL LETTER W       |
| ⓧ    | 9447 | 24E7 | CIRCLED LATIN SMALL LETTER X       |
| ⓨ    | 9448 | 24E8 | CIRCLED LATIN SMALL LETTER Y       |
| ⓩ    | 9449 | 24E9 | CIRCLED LATIN SMALL LETTER Z       |
| ⓪    | 9450 | 24EA | CIRCLED DIGIT ZERO                 |

### UTF-8 Enclosed Supplement

Hex 1F100-1F2FF / Dec 127232-127743.

#### Enclosed Alphanumeric Supplements

Char | Dec | Hex
--- | --- | ---
🄀 | 127232 | 1F100
🄁 | 127233 | 1F101
🄂 | 127234 | 1F102
🄃 | 127235 | 1F103
🄄 | 127236 | 1F104
🄅 | 127237 | 1F105
🄆 | 127238 | 1F106
🄇 | 127239 | 1F107
🄈 | 127240 | 1F108
🄉 | 127241 | 1F109
🄊 | 127242 | 1F10A
🄋 | 127243 | 1F10B
🄌 | 127244 | 1F10C
🄍 | 127245 | 1F10D
🄎 | 127246 | 1F10E
🄏 | 127247 | 1F10F
🄐 | 127248 | 1F110
🄑 | 127249 | 1F111
🄒 | 127250 | 1F112
🄓 | 127251 | 1F113
🄔 | 127252 | 1F114
🄕 | 127253 | 1F115
🄖 | 127254 | 1F116
🄗 | 127255 | 1F117
🄘 | 127256 | 1F118
🄙 | 127257 | 1F119
🄚 | 127258 | 1F11A
🄛 | 127259 | 1F11B
🄜 | 127260 | 1F11C
🄝 | 127261 | 1F11D
🄞 | 127262 | 1F11E
🄟 | 127263 | 1F11F
🄠 | 127264 | 1F120
🄡 | 127265 | 1F121
🄢 | 127266 | 1F122
🄣 | 127267 | 1F123
🄤 | 127268 | 1F124
🄥 | 127269 | 1F125
🄦 | 127270 | 1F126
🄧 | 127271 | 1F127
🄨 | 127272 | 1F128
🄩 | 127273 | 1F129
🄪 | 127274 | 1F12A
🄫 | 127275 | 1F12B
🄬 | 127276 | 1F12C
🄭 | 127277 | 1F12D
🄮 | 127278 | 1F12E
🄯 | 127279 | 1F12F

##### Squared Latin Letters

Char | Dec | Hex
--- | --- | ---
🄰 | 127280 | 1F130
🄱 | 127281 | 1F131
🄲 | 127282 | 1F132
🄳 | 127283 | 1F133
🄴 | 127284 | 1F134
🄵 | 127285 | 1F135
🄶 | 127286 | 1F136
🄷 | 127287 | 1F137
🄸 | 127288 | 1F138
🄹 | 127289 | 1F139
🄺 | 127290 | 1F13A
🄻 | 127291 | 1F13B
🄼 | 127292 | 1F13C
🄽 | 127293 | 1F13D
🄾 | 127294 | 1F13E
🄿 | 127295 | 1F13F
🅀 | 127296 | 1F140
🅁 | 127297 | 1F141
🅂 | 127298 | 1F142
🅃 | 127299 | 1F143
🅄 | 127300 | 1F144
🅅 | 127301 | 1F145
🅆 | 127302 | 1F146
🅇 | 127303 | 1F147
🅈 | 127304 | 1F148
🅉 | 127305 | 1F149
🅊 | 127306 | 1F14A
🅋 | 127307 | 1F14B
🅌 | 127308 | 1F14C
🅍 | 127309 | 1F14D
🅎 | 127310 | 1F14E
🅏 | 127311 | 1F14F

##### White on Black Latin Letters

Char | Dec | Hex
--- | --- | ---
🅐 | 127312 | 1F150
🅑 | 127313 | 1F151
🅒 | 127314 | 1F152
🅓 | 127315 | 1F153
🅔 | 127316 | 1F154
🅕 | 127317 | 1F155
🅖 | 127318 | 1F156
🅗 | 127319 | 1F157
🅘 | 127320 | 1F158
🅙 | 127321 | 1F159
🅚 | 127322 | 1F15A
🅛 | 127323 | 1F15B
🅜 | 127324 | 1F15C
🅝 | 127325 | 1F15D
🅞 | 127326 | 1F15E
🅟 | 127327 | 1F15F
🅠 | 127328 | 1F160
🅡 | 127329 | 1F161
🅢 | 127330 | 1F162
🅣 | 127331 | 1F163
🅤 | 127332 | 1F164
🅥 | 127333 | 1F165
🅦 | 127334 | 1F166
🅧 | 127335 | 1F167
🅨 | 127336 | 1F168
🅩 | 127337 | 1F169

##### Not in Use

Char | Dec | Hex
--- | --- | ---
🅪 | 127338 | 1F16A
🅫 | 127339 | 1F16B
🅬 | 127340 | 1F16C
🅭 | 127341 | 1F16D
🅮 | 127342 | 1F16E
🅯 | 127343 | 1F16F

##### Colored Squared Latin Letters

Char | Dec | Hex
--- | --- | ---
🅰 | 127344 | 1F170
🅱 | 127345 | 1F171
🅲 | 127346 | 1F172
🅳 | 127347 | 1F173
🅴 | 127348 | 1F174
🅵 | 127349 | 1F175
🅶 | 127350 | 1F176
🅷 | 127351 | 1F177
🅸 | 127352 | 1F178
🅹 | 127353 | 1F179
🅺 | 127354 | 1F17A
🅻 | 127355 | 1F17B
🅼 | 127356 | 1F17C
🅽 | 127357 | 1F17D
🅾 | 127358 | 1F17E
🅿 | 127359 | 1F17F
🆀 | 127360 | 1F180
🆁 | 127361 | 1F181
🆂 | 127362 | 1F182
🆃 | 127363 | 1F183
🆄 | 127364 | 1F184
🆅 | 127365 | 1F185
🆆 | 127366 | 1F186
🆇 | 127367 | 1F187
🆈 | 127368 | 1F188
🆉 | 127369 | 1F189
🆊 | 127370 | 1F18A
🆋 | 127371 | 1F18B
🆌 | 127372 | 1F18C
🆍 | 127373 | 1F18D
🆎 | 127374 | 1F18E
🆏 | 127375 | 1F18F
🆐 | 127376 | 1F190
🆑 | 127377 | 1F191
🆒 | 127378 | 1F192
🆓 | 127379 | 1F193
🆔 | 127380 | 1F194
🆕 | 127381 | 1F195
🆖 | 127382 | 1F196
🆗 | 127383 | 1F197
🆘 | 127384 | 1F198
🆙 | 127385 | 1F199
🆚 | 127386 | 1F19A

##### Not in Use

Char | Dec | Hex
--- | --- | ---
🆛 | 127387 | 1F19B
🆜 | 127388 | 1F19C
🆝 | 127389 | 1F19D
🆞 | 127390 | 1F19E
🆟 | 127391 | 1F19F
🆠 | 127392 | 1F1A0
🆡 | 127393 | 1F1A1
🆢 | 127394 | 1F1A2
🆣 | 127395 | 1F1A3
🆤 | 127396 | 1F1A4
🆥 | 127397 | 1F1A5
🆦 | 127398 | 1F1A6
🆧 | 127399 | 1F1A7
🆨 | 127400 | 1F1A8
🆩 | 127401 | 1F1A9
🆪 | 127402 | 1F1AA
🆫 | 127403 | 1F1AB
🆬 | 127404 | 1F1AC
🆭 | 127405 | 1F1AD
🆮 | 127406 | 1F1AE
🆯 | 127407 | 1F1AF
🆰 | 127408 | 1F1B0
🆱 | 127409 | 1F1B1
🆲 | 127410 | 1F1B2
🆳 | 127411 | 1F1B3
🆴 | 127412 | 1F1B4
🆵 | 127413 | 1F1B5
🆶 | 127414 | 1F1B6
🆷 | 127415 | 1F1B7
🆸 | 127416 | 1F1B8
🆹 | 127417 | 1F1B9
🆺 | 127418 | 1F1BA
🆻 | 127419 | 1F1BB
🆼 | 127420 | 1F1BC
🆽 | 127421 | 1F1BD
🆾 | 127422 | 1F1BE
🆿 | 127423 | 1F1BF
🇀 | 127424 | 1F1C0
🇁 | 127425 | 1F1C1
🇂 | 127426 | 1F1C2
🇃 | 127427 | 1F1C3
🇄 | 127428 | 1F1C4
🇅 | 127429 | 1F1C5
🇆 | 127430 | 1F1C6
🇇 | 127431 | 1F1C7
🇈 | 127432 | 1F1C8
🇉 | 127433 | 1F1C9
🇊 | 127434 | 1F1CA
🇋 | 127435 | 1F1CB
🇌 | 127436 | 1F1CC
🇍 | 127437 | 1F1CD
🇎 | 127438 | 1F1CE
🇏 | 127439 | 1F1CF
🇐 | 127440 | 1F1D0
🇑 | 127441 | 1F1D1
🇒 | 127442 | 1F1D2
🇓 | 127443 | 1F1D3
🇔 | 127444 | 1F1D4
🇕 | 127445 | 1F1D5
🇖 | 127446 | 1F1D6
🇗 | 127447 | 1F1D7
🇘 | 127448 | 1F1D8
🇙 | 127449 | 1F1D9
🇚 | 127450 | 1F1DA
🇛 | 127451 | 1F1DB
🇜 | 127452 | 1F1DC
🇝 | 127453 | 1F1DD
🇞 | 127454 | 1F1DE
🇟 | 127455 | 1F1DF
🇠 | 127456 | 1F1E0
🇡 | 127457 | 1F1E1
🇢 | 127458 | 1F1E2
🇣 | 127459 | 1F1E3
🇤 | 127460 | 1F1E4
🇥 | 127461 | 1F1E5

##### Regional Indicators

Char | Dec | Hex
--- | --- | ---
🇦 | 127462 | 1F1E6
🇧 | 127463 | 1F1E7
🇨 | 127464 | 1F1E8
🇩 | 127465 | 1F1E9
🇪 | 127466 | 1F1EA
🇫 | 127467 | 1F1EB
🇬 | 127468 | 1F1EC
🇭 | 127469 | 1F1ED
🇮 | 127470 | 1F1EE
🇯 | 127471 | 1F1EF
🇰 | 127472 | 1F1F0
🇱 | 127473 | 1F1F1
🇲 | 127474 | 1F1F2
🇳 | 127475 | 1F1F3
🇴 | 127476 | 1F1F4
🇵 | 127477 | 1F1F5
🇶 | 127478 | 1F1F6
🇷 | 127479 | 1F1F7
🇸 | 127480 | 1F1F8
🇹 | 127481 | 1F1F9
🇺 | 127482 | 1F1FA
🇻 | 127483 | 1F1FB
🇼 | 127484 | 1F1FC
🇽 | 127485 | 1F1FD
🇾 | 127486 | 1F1FE
🇿 | 127487 | 1F1FF

##### Enclosed Ideographic Supplement

Char | Dec | Hex
--- | --- | ---
🈀 | 127488 | 1F200
🈁 | 127489 | 1F201
🈂 | 127490 | 1F202
🈃 | 127491 | 1F203
🈄 | 127492 | 1F204
🈅 | 127493 | 1F205
🈆 | 127494 | 1F206
🈇 | 127495 | 1F207
🈈 | 127496 | 1F208
🈉 | 127497 | 1F209
🈊 | 127498 | 1F20A
🈋 | 127499 | 1F20B
🈌 | 127500 | 1F20C
🈍 | 127501 | 1F20D
🈎 | 127502 | 1F20E
🈏 | 127503 | 1F20F
🈐 | 127504 | 1F210
🈑 | 127505 | 1F211
🈒 | 127506 | 1F212
🈓 | 127507 | 1F213
🈔 | 127508 | 1F214
🈕 | 127509 | 1F215
🈖 | 127510 | 1F216
🈗 | 127511 | 1F217
🈘 | 127512 | 1F218
🈙 | 127513 | 1F219
🈚 | 127514 | 1F21A
🈛 | 127515 | 1F21B
🈜 | 127516 | 1F21C
🈝 | 127517 | 1F21D
🈞 | 127518 | 1F21E
🈟 | 127519 | 1F21F
🈠 | 127520 | 1F220
🈡 | 127521 | 1F221
🈢 | 127522 | 1F222
🈣 | 127523 | 1F223
🈤 | 127524 | 1F224
🈥 | 127525 | 1F225
🈦 | 127526 | 1F226
🈧 | 127527 | 1F227
🈨 | 127528 | 1F228
🈩 | 127529 | 1F229
🈪 | 127530 | 1F22A
🈫 | 127531 | 1F22B
🈬 | 127532 | 1F22C
🈭 | 127533 | 1F22D
🈮 | 127534 | 1F22E
🈯 | 127535 | 1F22F
🈰 | 127536 | 1F230
🈱 | 127537 | 1F231
🈲 | 127538 | 1F232
🈳 | 127539 | 1F233
🈴 | 127540 | 1F234
🈵 | 127541 | 1F235
🈶 | 127542 | 1F236
🈷 | 127543 | 1F237
🈸 | 127544 | 1F238
🈹 | 127545 | 1F239
🈺 | 127546 | 1F23A
🈻 | 127547 | 1F23B
🈼 | 127548 | 1F23C
🈽 | 127549 | 1F23D
🈾 | 127550 | 1F23E
🈿 | 127551 | 1F23F
🉀 | 127552 | 1F240
🉁 | 127553 | 1F241
🉂 | 127554 | 1F242
🉃 | 127555 | 1F243
🉄 | 127556 | 1F244
🉅 | 127557 | 1F245
🉆 | 127558 | 1F246
🉇 | 127559 | 1F247
🉈 | 127560 | 1F248
🉉 | 127561 | 1F249
🉊 | 127562 | 1F24A
🉋 | 127563 | 1F24B
🉌 | 127564 | 1F24C
🉍 | 127565 | 1F24D
🉎 | 127566 | 1F24E
🉏 | 127567 | 1F24F
🉐 | 127568 | 1F250
🉑 | 127569 | 1F251

##### Not in Use

Char | Dec | Hex
--- | --- | ---
🉒 | 127570 | 1F252
🉓 | 127571 | 1F253
🉔 | 127572 | 1F254
🉕 | 127573 | 1F255
🉖 | 127574 | 1F256
🉗 | 127575 | 1F257
🉘 | 127576 | 1F258
🉙 | 127577 | 1F259
🉚 | 127578 | 1F25A
🉛 | 127579 | 1F25B
🉜 | 127580 | 1F25C
🉝 | 127581 | 1F25D
🉞 | 127582 | 1F25E
🉟 | 127583 | 1F25F
🉠 | 127584 | 1F260
🉡 | 127585 | 1F261
🉢 | 127586 | 1F262
🉣 | 127587 | 1F263
🉤 | 127588 | 1F264
🉥 | 127589 | 1F265
🉦 | 127590 | 1F266
🉧 | 127591 | 1F267
🉨 | 127592 | 1F268
🉩 | 127593 | 1F269
🉪 | 127594 | 1F26A
🉫 | 127595 | 1F26B
🉬 | 127596 | 1F26C
🉭 | 127597 | 1F26D
🉮 | 127598 | 1F26E
🉯 | 127599 | 1F26F
🉰 | 127600 | 1F270
🉱 | 127601 | 1F271
🉲 | 127602 | 1F272
🉳 | 127603 | 1F273
🉴 | 127604 | 1F274
🉵 | 127605 | 1F275
🉶 | 127606 | 1F276
🉷 | 127607 | 1F277
🉸 | 127608 | 1F278
🉹 | 127609 | 1F279
🉺 | 127610 | 1F27A
🉻 | 127611 | 1F27B
🉼 | 127612 | 1F27C
🉽 | 127613 | 1F27D
🉾 | 127614 | 1F27E
🉿 | 127615 | 1F27F
🊀 | 127616 | 1F280
🊁 | 127617 | 1F281
🊂 | 127618 | 1F282
🊃 | 127619 | 1F283
🊄 | 127620 | 1F284
🊅 | 127621 | 1F285
🊆 | 127622 | 1F286
🊇 | 127623 | 1F287
🊈 | 127624 | 1F288
🊉 | 127625 | 1F289
🊊 | 127626 | 1F28A
🊋 | 127627 | 1F28B
🊌 | 127628 | 1F28C
🊍 | 127629 | 1F28D
🊎 | 127630 | 1F28E
🊏 | 127631 | 1F28F
🊐 | 127632 | 1F290
🊑 | 127633 | 1F291
🊒 | 127634 | 1F292
🊓 | 127635 | 1F293
🊔 | 127636 | 1F294
🊕 | 127637 | 1F295
🊖 | 127638 | 1F296
🊗 | 127639 | 1F297
🊘 | 127640 | 1F298
🊙 | 127641 | 1F299
🊚 | 127642 | 1F29A
🊛 | 127643 | 1F29B
🊜 | 127644 | 1F29C
🊝 | 127645 | 1F29D
🊞 | 127646 | 1F29E
🊟 | 127647 | 1F29F
🊠 | 127648 | 1F2A0
🊡 | 127649 | 1F2A1
🊢 | 127650 | 1F2A2
🊣 | 127651 | 1F2A3
🊤 | 127652 | 1F2A4
🊥 | 127653 | 1F2A5
🊦 | 127654 | 1F2A6
🊧 | 127655 | 1F2A7
🊨 | 127656 | 1F2A8
🊩 | 127657 | 1F2A9
🊪 | 127658 | 1F2AA
🊫 | 127659 | 1F2AB
🊬 | 127660 | 1F2AC
🊭 | 127661 | 1F2AD
🊮 | 127662 | 1F2AE
🊯 | 127663 | 1F2AF
🊰 | 127664 | 1F2B0
🊱 | 127665 | 1F2B1
🊲 | 127666 | 1F2B2
🊳 | 127667 | 1F2B3
🊴 | 127668 | 1F2B4
🊵 | 127669 | 1F2B5
🊶 | 127670 | 1F2B6
🊷 | 127671 | 1F2B7
🊸 | 127672 | 1F2B8
🊹 | 127673 | 1F2B9
🊺 | 127674 | 1F2BA
🊻 | 127675 | 1F2BB
🊼 | 127676 | 1F2BC
🊽 | 127677 | 1F2BD
🊾 | 127678 | 1F2BE
🊿 | 127679 | 1F2BF
🋀 | 127680 | 1F2C0
🋁 | 127681 | 1F2C1
🋂 | 127682 | 1F2C2
🋃 | 127683 | 1F2C3
🋄 | 127684 | 1F2C4
🋅 | 127685 | 1F2C5
🋆 | 127686 | 1F2C6
🋇 | 127687 | 1F2C7
🋈 | 127688 | 1F2C8
🋉 | 127689 | 1F2C9
🋊 | 127690 | 1F2CA
🋋 | 127691 | 1F2CB
🋌 | 127692 | 1F2CC
🋍 | 127693 | 1F2CD
🋎 | 127694 | 1F2CE
🋏 | 127695 | 1F2CF
🋐 | 127696 | 1F2D0
🋑 | 127697 | 1F2D1
🋒 | 127698 | 1F2D2
🋓 | 127699 | 1F2D3
🋔 | 127700 | 1F2D4
🋕 | 127701 | 1F2D5
🋖 | 127702 | 1F2D6
🋗 | 127703 | 1F2D7
🋘 | 127704 | 1F2D8
🋙 | 127705 | 1F2D9
🋚 | 127706 | 1F2DA
🋛 | 127707 | 1F2DB
🋜 | 127708 | 1F2DC
🋝 | 127709 | 1F2DD
🋞 | 127710 | 1F2DE
🋟 | 127711 | 1F2DF
🋠 | 127712 | 1F2E0
🋡 | 127713 | 1F2E1
🋢 | 127714 | 1F2E2
🋣 | 127715 | 1F2E3
🋤 | 127716 | 1F2E4
🋥 | 127717 | 1F2E5
🋦 | 127718 | 1F2E6
🋧 | 127719 | 1F2E7
🋨 | 127720 | 1F2E8
🋩 | 127721 | 1F2E9
🋪 | 127722 | 1F2EA
🋫 | 127723 | 1F2EB
🋬 | 127724 | 1F2EC
🋭 | 127725 | 1F2ED
🋮 | 127726 | 1F2EE
🋯 | 127727 | 1F2EF
🋰 | 127728 | 1F2F0
🋱 | 127729 | 1F2F1
🋲 | 127730 | 1F2F2
🋳 | 127731 | 1F2F3
🋴 | 127732 | 1F2F4
🋵 | 127733 | 1F2F5
🋶 | 127734 | 1F2F6
🋷 | 127735 | 1F2F7
🋸 | 127736 | 1F2F8
🋹 | 127737 | 1F2F9
🋺 | 127738 | 1F2FA
🋻 | 127739 | 1F2FB
🋼 | 127740 | 1F2FC
🋽 | 127741 | 1F2FD
🋾 | 127742 | 1F2FE
🋿 | 127743 | 1F2FF


## Braille

Hex 2800-28FF / Decimal 10240-10495.

### Braille

27F0 to 27FF.

Char | Dec | Hex
--- | --- | ---
⠀ | 10240 | 2800
⠁ | 10241 | 2801
⠂ | 10242 | 2802
⠃ | 10243 | 2803
⠄ | 10244 | 2804
⠅ | 10245 | 2805
⠆ | 10246 | 2806
⠇ | 10247 | 2807
⠈ | 10248 | 2808
⠉ | 10249 | 2809
⠊ | 10250 | 280A
⠋ | 10251 | 280B
⠌ | 10252 | 280C
⠍ | 10253 | 280D
⠎ | 10254 | 280E
⠏ | 10255 | 280F
⠐ | 10256 | 2810
⠑ | 10257 | 2811
⠒ | 10258 | 2812
⠓ | 10259 | 2813
⠔ | 10260 | 2814
⠕ | 10261 | 2815
⠖ | 10262 | 2816
⠗ | 10263 | 2817
⠘ | 10264 | 2818
⠙ | 10265 | 2819
⠚ | 10266 | 281A
⠛ | 10267 | 281B
⠜ | 10268 | 281C
⠝ | 10269 | 281D
⠞ | 10270 | 281E
⠟ | 10271 | 281F
⠠ | 10272 | 2820
⠡ | 10273 | 2821
⠢ | 10274 | 2822
⠣ | 10275 | 2823
⠤ | 10276 | 2824
⠥ | 10277 | 2825
⠦ | 10278 | 2826
⠧ | 10279 | 2827
⠨ | 10280 | 2828
⠩ | 10281 | 2829
⠪ | 10282 | 282A
⠫ | 10283 | 282B
⠬ | 10284 | 282C
⠭ | 10285 | 282D
⠮ | 10286 | 282E
⠯ | 10287 | 282F
⠰ | 10288 | 2830
⠱ | 10289 | 2831
⠲ | 10290 | 2832
⠳ | 10291 | 2833
⠴ | 10292 | 2834
⠵ | 10293 | 2835
⠶ | 10294 | 2836
⠷ | 10295 | 2837
⠸ | 10296 | 2838
⠹ | 10297 | 2839
⠺ | 10298 | 283A
⠻ | 10299 | 283B
⠼ | 10300 | 283C
⠽ | 10301 | 283D
⠾ | 10302 | 283E
⠿ | 10303 | 283F
⡀ | 10304 | 2840
⡁ | 10305 | 2841
⡂ | 10306 | 2842
⡃ | 10307 | 2843
⡄ | 10308 | 2844
⡅ | 10309 | 2845
⡆ | 10310 | 2846
⡇ | 10311 | 2847
⡈ | 10312 | 2848
⡉ | 10313 | 2849
⡊ | 10314 | 284A
⡋ | 10315 | 284B
⡌ | 10316 | 284C
⡍ | 10317 | 284D
⡎ | 10318 | 284E
⡏ | 10319 | 284F
⡐ | 10320 | 2850
⡑ | 10321 | 2851
⡒ | 10322 | 2852
⡓ | 10323 | 2853
⡔ | 10324 | 2854
⡕ | 10325 | 2855
⡖ | 10326 | 2856
⡗ | 10327 | 2857
⡘ | 10328 | 2858
⡙ | 10329 | 2859
⡚ | 10330 | 285A
⡛ | 10331 | 285B
⡜ | 10332 | 285C
⡝ | 10333 | 285D
⡞ | 10334 | 285E
⡟ | 10335 | 285F
⡠ | 10336 | 2860
⡡ | 10337 | 2861
⡢ | 10338 | 2862
⡣ | 10339 | 2863
⡤ | 10340 | 2864
⡥ | 10341 | 2865
⡦ | 10342 | 2866
⡧ | 10343 | 2867
⡨ | 10344 | 2868
⡩ | 10345 | 2869
⡪ | 10346 | 286A
⡫ | 10347 | 286B
⡬ | 10348 | 286C
⡭ | 10349 | 286D
⡮ | 10350 | 286E
⡯ | 10351 | 286F
⡰ | 10352 | 2870
⡱ | 10353 | 2871
⡲ | 10354 | 2872
⡳ | 10355 | 2873
⡴ | 10356 | 2874
⡵ | 10357 | 2875
⡶ | 10358 | 2876
⡷ | 10359 | 2877
⡸ | 10360 | 2878
⡹ | 10361 | 2879
⡺ | 10362 | 287A
⡻ | 10363 | 287B
⡼ | 10364 | 287C
⡽ | 10365 | 287D
⡾ | 10366 | 287E
⡿ | 10367 | 287F
⢀ | 10368 | 2880
⢁ | 10369 | 2881
⢂ | 10370 | 2882
⢃ | 10371 | 2883
⢄ | 10372 | 2884
⢅ | 10373 | 2885
⢆ | 10374 | 2886
⢇ | 10375 | 2887
⢈ | 10376 | 2888
⢉ | 10377 | 2889
⢊ | 10378 | 288A
⢋ | 10379 | 288B
⢌ | 10380 | 288C
⢍ | 10381 | 288D
⢎ | 10382 | 288E
⢏ | 10383 | 288F
⢐ | 10384 | 2890
⢑ | 10385 | 2891
⢒ | 10386 | 2892
⢓ | 10387 | 2893
⢔ | 10388 | 2894
⢕ | 10389 | 2895
⢖ | 10390 | 2896
⢗ | 10391 | 2897
⢘ | 10392 | 2898
⢙ | 10393 | 2899
⢚ | 10394 | 289A
⢛ | 10395 | 289B
⢜ | 10396 | 289C
⢝ | 10397 | 289D
⢞ | 10398 | 289E
⢟ | 10399 | 289F
⢠ | 10400 | 28A0
⢡ | 10401 | 28A1
⢢ | 10402 | 28A2
⢣ | 10403 | 28A3
⢤ | 10404 | 28A4
⢥ | 10405 | 28A5
⢦ | 10406 | 28A6
⢧ | 10407 | 28A7
⢨ | 10408 | 28A8
⢩ | 10409 | 28A9
⢪ | 10410 | 28AA
⢫ | 10411 | 28AB
⢬ | 10412 | 28AC
⢭ | 10413 | 28AD
⢮ | 10414 | 28AE
⢯ | 10415 | 28AF
⢰ | 10416 | 28B0
⢱ | 10417 | 28B1
⢲ | 10418 | 28B2
⢳ | 10419 | 28B3
⢴ | 10420 | 28B4
⢵ | 10421 | 28B5
⢶ | 10422 | 28B6
⢷ | 10423 | 28B7
⢸ | 10424 | 28B8
⢹ | 10425 | 28B9
⢺ | 10426 | 28BA
⢻ | 10427 | 28BB
⢼ | 10428 | 28BC
⢽ | 10429 | 28BD
⢾ | 10430 | 28BE
⢿ | 10431 | 28BF
⣀ | 10432 | 28C0
⣁ | 10433 | 28C1
⣂ | 10434 | 28C2
⣃ | 10435 | 28C3
⣄ | 10436 | 28C4
⣅ | 10437 | 28C5
⣆ | 10438 | 28C6
⣇ | 10439 | 28C7
⣈ | 10440 | 28C8
⣉ | 10441 | 28C9
⣊ | 10442 | 28CA
⣋ | 10443 | 28CB
⣌ | 10444 | 28CC
⣍ | 10445 | 28CD
⣎ | 10446 | 28CE
⣏ | 10447 | 28CF
⣐ | 10448 | 28D0
⣑ | 10449 | 28D1
⣒ | 10450 | 28D2
⣓ | 10451 | 28D3
⣔ | 10452 | 28D4
⣕ | 10453 | 28D5
⣖ | 10454 | 28D6
⣗ | 10455 | 28D7
⣘ | 10456 | 28D8
⣙ | 10457 | 28D9
⣚ | 10458 | 28DA
⣛ | 10459 | 28DB
⣜ | 10460 | 28DC
⣝ | 10461 | 28DD
⣞ | 10462 | 28DE
⣟ | 10463 | 28DF
⣠ | 10464 | 28E0
⣡ | 10465 | 28E1
⣢ | 10466 | 28E2
⣣ | 10467 | 28E3
⣤ | 10468 | 28E4
⣥ | 10469 | 28E5
⣦ | 10470 | 28E6
⣧ | 10471 | 28E7
⣨ | 10472 | 28E8
⣩ | 10473 | 28E9
⣪ | 10474 | 28EA
⣫ | 10475 | 28EB
⣬ | 10476 | 28EC
⣭ | 10477 | 28ED
⣮ | 10478 | 28EE
⣯ | 10479 | 28EF
⣰ | 10480 | 28F0
⣱ | 10481 | 28F1
⣲ | 10482 | 28F2
⣳ | 10483 | 28F3
⣴ | 10484 | 28F4
⣵ | 10485 | 28F5
⣶ | 10486 | 28F6
⣷ | 10487 | 28F7
⣸ | 10488 | 28F8
⣹ | 10489 | 28F9
⣺ | 10490 | 28FA
⣻ | 10491 | 28FB
⣼ | 10492 | 28FC
⣽ | 10493 | 28FD
⣾ | 10494 | 28FE
⣿ | 10495 | 28FF

## Tiles and Playing Cards

Hex 1F000-1F0FF / Dec 126976-127231.

### Mahjong Tiles

Char | Dec | Hex
--- | --- | ---
🀀 | 126976 | 1F000
🀁 | 126977 | 1F001
🀂 | 126978 | 1F002
🀃 | 126979 | 1F003
🀄 | 126980 | 1F004
🀅 | 126981 | 1F005
🀆 | 126982 | 1F006
🀇 | 126983 | 1F007
🀈 | 126984 | 1F008
🀉 | 126985 | 1F009
🀊 | 126986 | 1F00A
🀋 | 126987 | 1F00B
🀌 | 126988 | 1F00C
🀍 | 126989 | 1F00D
🀎 | 126990 | 1F00E
🀏 | 126991 | 1F00F
🀐 | 126992 | 1F010
🀑 | 126993 | 1F011
🀒 | 126994 | 1F012
🀓 | 126995 | 1F013
🀔 | 126996 | 1F014
🀕 | 126997 | 1F015
🀖 | 126998 | 1F016
🀗 | 126999 | 1F017
🀘 | 127000 | 1F018
🀙 | 127001 | 1F019
🀚 | 127002 | 1F01A
🀛 | 127003 | 1F01B
🀜 | 127004 | 1F01C
🀝 | 127005 | 1F01D
🀞 | 127006 | 1F01E
🀟 | 127007 | 1F01F
🀠 | 127008 | 1F020
🀡 | 127009 | 1F021
🀢 | 127010 | 1F022
🀣 | 127011 | 1F023
🀤 | 127012 | 1F024
🀥 | 127013 | 1F025
🀦 | 127014 | 1F026
🀧 | 127015 | 1F027
🀨 | 127016 | 1F028
🀩 | 127017 | 1F029
🀪 | 127018 | 1F02A
🀫 | 127019 | 1F02B
🀬 | 127020 | 1F02C
🀭 | 127021 | 1F02D
🀮 | 127022 | 1F02E
🀯 | 127023 | 1F02F

### Domino Tiles

Char | Dec | Hex
--- | --- | ---
🀰 | 127024 | 1F030
🀱 | 127025 | 1F031
🀲 | 127026 | 1F032
🀳 | 127027 | 1F033
🀴 | 127028 | 1F034
🀵 | 127029 | 1F035
🀶 | 127030 | 1F036
🀷 | 127031 | 1F037
🀸 | 127032 | 1F038
🀹 | 127033 | 1F039
🀺 | 127034 | 1F03A
🀻 | 127035 | 1F03B
🀼 | 127036 | 1F03C
🀽 | 127037 | 1F03D
🀾 | 127038 | 1F03E
🀿 | 127039 | 1F03F
🁀 | 127040 | 1F040
🁁 | 127041 | 1F041
🁂 | 127042 | 1F042
🁃 | 127043 | 1F043
🁄 | 127044 | 1F044
🁅 | 127045 | 1F045
🁆 | 127046 | 1F046
🁇 | 127047 | 1F047
🁈 | 127048 | 1F048
🁉 | 127049 | 1F049
🁊 | 127050 | 1F04A
🁋 | 127051 | 1F04B
🁌 | 127052 | 1F04C
🁍 | 127053 | 1F04D
🁎 | 127054 | 1F04E
🁏 | 127055 | 1F04F
🁐 | 127056 | 1F050
🁑 | 127057 | 1F051
🁒 | 127058 | 1F052
🁓 | 127059 | 1F053
🁔 | 127060 | 1F054
🁕 | 127061 | 1F055
🁖 | 127062 | 1F056
🁗 | 127063 | 1F057
🁘 | 127064 | 1F058
🁙 | 127065 | 1F059
🁚 | 127066 | 1F05A
🁛 | 127067 | 1F05B
🁜 | 127068 | 1F05C
🁝 | 127069 | 1F05D
🁞 | 127070 | 1F05E
🁟 | 127071 | 1F05F
🁠 | 127072 | 1F060
🁡 | 127073 | 1F061
🁢 | 127074 | 1F062
🁣 | 127075 | 1F063
🁤 | 127076 | 1F064
🁥 | 127077 | 1F065
🁦 | 127078 | 1F066
🁧 | 127079 | 1F067
🁨 | 127080 | 1F068
🁩 | 127081 | 1F069
🁪 | 127082 | 1F06A
🁫 | 127083 | 1F06B
🁬 | 127084 | 1F06C
🁭 | 127085 | 1F06D
🁮 | 127086 | 1F06E
🁯 | 127087 | 1F06F
🁰 | 127088 | 1F070
🁱 | 127089 | 1F071
🁲 | 127090 | 1F072
🁳 | 127091 | 1F073
🁴 | 127092 | 1F074
🁵 | 127093 | 1F075
🁶 | 127094 | 1F076
🁷 | 127095 | 1F077
🁸 | 127096 | 1F078
🁹 | 127097 | 1F079
🁺 | 127098 | 1F07A
🁻 | 127099 | 1F07B
🁼 | 127100 | 1F07C
🁽 | 127101 | 1F07D
🁾 | 127102 | 1F07E
🁿 | 127103 | 1F07F
🂀 | 127104 | 1F080
🂁 | 127105 | 1F081
🂂 | 127106 | 1F082
🂃 | 127107 | 1F083
🂄 | 127108 | 1F084
🂅 | 127109 | 1F085
🂆 | 127110 | 1F086
🂇 | 127111 | 1F087
🂈 | 127112 | 1F088
🂉 | 127113 | 1F089
🂊 | 127114 | 1F08A
🂋 | 127115 | 1F08B
🂌 | 127116 | 1F08C
🂍 | 127117 | 1F08D
🂎 | 127118 | 1F08E
🂏 | 127119 | 1F08F
🂐 | 127120 | 1F090
🂑 | 127121 | 1F091
🂒 | 127122 | 1F092
🂓 | 127123 | 1F093

### Not in Use

Char | Dec | Hex
--- | --- | ---
🂔 | 127124 | 1F094
🂕 | 127125 | 1F095
🂖 | 127126 | 1F096
🂗 | 127127 | 1F097
🂘 | 127128 | 1F098
🂙 | 127129 | 1F099
🂚 | 127130 | 1F09A
🂛 | 127131 | 1F09B
🂜 | 127132 | 1F09C
🂝 | 127133 | 1F09D
🂞 | 127134 | 1F09E
🂟 | 127135 | 1F09F

### Playing Cards

Char | Dec | Hex
--- | --- | ---
🂠 | 127136 | 1F0A0
🂡 | 127137 | 1F0A1
🂢 | 127138 | 1F0A2
🂣 | 127139 | 1F0A3
🂤 | 127140 | 1F0A4
🂥 | 127141 | 1F0A5
🂦 | 127142 | 1F0A6
🂧 | 127143 | 1F0A7
🂨 | 127144 | 1F0A8
🂩 | 127145 | 1F0A9
🂪 | 127146 | 1F0AA
🂫 | 127147 | 1F0AB
🂬 | 127148 | 1F0AC
🂭 | 127149 | 1F0AD
🂮 | 127150 | 1F0AE
🂯 | 127151 | 1F0AF
🂰 | 127152 | 1F0B0
🂱 | 127153 | 1F0B1
🂲 | 127154 | 1F0B2
🂳 | 127155 | 1F0B3
🂴 | 127156 | 1F0B4
🂵 | 127157 | 1F0B5
🂶 | 127158 | 1F0B6
🂷 | 127159 | 1F0B7
🂸 | 127160 | 1F0B8
🂹 | 127161 | 1F0B9
🂺 | 127162 | 1F0BA
🂻 | 127163 | 1F0BB
🂼 | 127164 | 1F0BC
🂽 | 127165 | 1F0BD
🂾 | 127166 | 1F0BE
🂿 | 127167 | 1F0BF
🃀 | 127168 | 1F0C0
🃁 | 127169 | 1F0C1
🃂 | 127170 | 1F0C2
🃃 | 127171 | 1F0C3
🃄 | 127172 | 1F0C4
🃅 | 127173 | 1F0C5
🃆 | 127174 | 1F0C6
🃇 | 127175 | 1F0C7
🃈 | 127176 | 1F0C8
🃉 | 127177 | 1F0C9
🃊 | 127178 | 1F0CA
🃋 | 127179 | 1F0CB
🃌 | 127180 | 1F0CC
🃍 | 127181 | 1F0CD
🃎 | 127182 | 1F0CE
🃏 | 127183 | 1F0CF
🃐 | 127184 | 1F0D0
🃑 | 127185 | 1F0D1
🃒 | 127186 | 1F0D2
🃓 | 127187 | 1F0D3
🃔 | 127188 | 1F0D4
🃕 | 127189 | 1F0D5
🃖 | 127190 | 1F0D6
🃗 | 127191 | 1F0D7
🃘 | 127192 | 1F0D8
🃙 | 127193 | 1F0D9
🃚 | 127194 | 1F0DA
🃛 | 127195 | 1F0DB
🃜 | 127196 | 1F0DC
🃝 | 127197 | 1F0DD
🃞 | 127198 | 1F0DE
🃟 | 127199 | 1F0DF
🃠 | 127200 | 1F0E0
🃡 | 127201 | 1F0E1
🃢 | 127202 | 1F0E2
🃣 | 127203 | 1F0E3
🃤 | 127204 | 1F0E4
🃥 | 127205 | 1F0E5
🃦 | 127206 | 1F0E6
🃧 | 127207 | 1F0E7
🃨 | 127208 | 1F0E8
🃩 | 127209 | 1F0E9
🃪 | 127210 | 1F0EA
🃫 | 127211 | 1F0EB
🃬 | 127212 | 1F0EC
🃭 | 127213 | 1F0ED
🃮 | 127214 | 1F0EE
🃯 | 127215 | 1F0EF
🃰 | 127216 | 1F0F0
🃱 | 127217 | 1F0F1
🃲 | 127218 | 1F0F2
🃳 | 127219 | 1F0F3
🃴 | 127220 | 1F0F4
🃵 | 127221 | 1F0F5

### Not in Use

Char | Dec | Hex
--- | --- | ---
🃶 | 127222 | 1F0F6
🃷 | 127223 | 1F0F7
🃸 | 127224 | 1F0F8
🃹 | 127225 | 1F0F9
🃺 | 127226 | 1F0FA
🃻 | 127227 | 1F0FB
🃼 | 127228 | 1F0FC
🃽 | 127229 | 1F0FD
🃾 | 127230 | 1F0FE
🃿 | 127231 | 1F0FF