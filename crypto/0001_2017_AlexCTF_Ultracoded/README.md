# 2017 AlexCTF - [CRYPTO] Ultracoded

## Solution

문제에 `ZERO`와 `ONE`이라는 글자가 채워진 zero_one 텍스트 파일이 제공됩니다.

```
ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ZERO ZERO ZERO ONE ZERO ONE ONE ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ONE ZERO ONE ZERO ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ONE ZERO ONE ZERO ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ZERO ZERO ONE ONE ZERO ZERO ONE ONE ONE ZERO ONE ZERO ZERO ONE ONE ZERO ZERO ZERO ONE ZERO ONE ZERO ZERO ZERO ONE ZERO ZERO ONE ONE ONE ONE ZERO ONE ZERO ZERO ONE ONE ONE ONE ZERO ONE
```

문제에는 총 5가지 Task 가 존재합니다.

1. 파일 읽기
2. `ZERO`와 `ONE`글자를 각각 `0`, `1`로 변경
3. `Binary String`을 `Hexlify`하여 `Ascii String`으로 변경
  - `Base64` 출력
4. `Base64` Decode
  - `Morse Code` 출력
5. `Morse Code` Decode
  - `Flag` 출력

## Code

``` python
from binascii import unhexlify

target = "./zero_one"
msg1   = ""
print "[step 1] : read from file"
with open(target) as fd:
	msg1 = fd.read()
print msg1 + "\n"

print "[step 2] reaplce 'ZERO' to '0' and 'ONE' to '1'"
msg2 = ""
for m in msg1.split(" "):
	m = m.replace("\n","")
	if m == "ONE": msg2 += "1"
	elif m == "ZERO": msg2 += "0"
print msg2

print "[step 3] convert binary string to binary and unhex"
msg3 = ""
msg3 = unhexlify('%x' % int(msg2, 2))
print msg3 + "\n"

print "[step 4] decode base64"
msg4 = ""
msg4 = msg3.decode("base64")
print msg4

encode_mc = {
        'A': '.-',              'a': '.-',
        'B': '-...',            'b': '-...',
        'C': '-.-.',            'c': '-.-.',
        'D': '-..',             'd': '-..',
        'E': '.',               'e': '.',
        'F': '..-.',            'f': '..-.',
        'G': '--.',             'g': '--.',
        'H': '....',            'h': '....',
        'I': '..',              'i': '..',
        'J': '.---',            'j': '.---',
        'K': '-.-',             'k': '-.-',
        'L': '.-..',            'l': '.-..',
        'M': '--',              'm': '--',
        'N': '-.',              'n': '-.',
        'O': '---',             'o': '---',
        'P': '.--.',            'p': '.--.',
        'Q': '--.-',            'q': '--.-',
        'R': '.-.',             'r': '.-.',
        'S': '...',             's': '...',
        'T': '-',               't': '-',
        'U': '..-',             'u': '..-',
        'V': '...-',            'v': '...-',
        'W': '.--',             'w': '.--',
        'X': '-..-',            'x': '-..-',
        'Y': '-.--',            'y': '-.--',
        'Z': '--..',            'z': '--..',
        '0': '-----',           ',': '--..--',
        '1': '.----',           '.': '.-.-.-',
        '2': '..---',           '?': '..--..',
        '3': '...--',           ';': '-.-.-.',
        '4': '....-',           ':': '---...',
        '5': '.....',           "'": '.----.',
        '6': '-....',           '-': '-....-',
        '7': '--...',           '/': '-..-.',
        '8': '---..',           '(': '-.--.-',
        '9': '----.',           ')': '-.--.-',
        ' ': ' ',               '_': '..--.-',
}


print "[step 5] decode morse code"
msg5 = ""
decode_mc = dict((v, k) for (k, v) in encode_mc.items())
msg5 = ''.join(decode_mc[dec] for dec in msg4.split(" "))
print msg5
```


## Result

```
[step 2] reaplce 'ZERO' to '0' and 'ONE' to '1'
0100110001101001001100000110011101001100011010010011000001110101010011000110100101000001011101010100100101000011001100000111010101001100011010010011000001100111010011000101001100110100011101000100110001101001010000010111010001001001010000110011010001110101010011000101001100110100011001110100110001010011010000010111010101001100011010010011010001110101010010010100001100110100011101000100110001010011001100000111010001001001010000110011010001110101010011000110100100110100011101010100100101000011001100000111010001001100010100110100000101110101010011000101001100110000011101000100110001010011010000010111010101001100011010010011010001100111010011000101001100110000011101000100100101000011001101000111010101001100011010010011010001110101010010010100001100110100011101010100110001010011010000010111010101001100010100110011000001110101010010010100001100110100011101010100110001101001001100000111010001001001010000110011010001110100010011000110100101000001011101000100110001010011001100000110011101001100011010010011010001110101010011000110100100110100011001110100110001101001010000010111010001001100011010010011000001110101010010010100001100110100011101000100110001101001010000010111010101001100011010010011010001110100010011000101001101000001011101000100100101000011001100000111010001001100010100110100000101110100010010010100001100110000011101010100110001101001001100000110011101001100010100010011110100111101
[step 3] convert binary string to binary and unhex
Li0gLi0uLiAuIC0uLi0gLS4tLiAtIC4uLS4gLSAuLi4uIC4tLS0tIC4uLi4uIC0tLSAuLS0tLSAuLi4gLS0tIC4uLi4uIC4uLSAuLS0uIC4uLi0tIC4tLiAtLS0gLi4uLi4gLiAtLi0uIC4tLiAuLi4tLSAtIC0tLSAtIC0uLi0gLQ==

[step 4] decode base64
.- .-.. . -..- -.-. - ..-. - .... .---- ..... --- .---- ... --- ..... ..- .--. ...-- .-. --- ..... . -.-. .-. ...-- - --- - -..- -
[step 5] decode morse code
alexctfth15o1so5up3ro5ecr3totxt
```
