This repository provides materials for APL meeting for JLREQ in Kyoto, 9/8/2019.

I'd like to arise several accessibility issues in East-Asia text layout such as vertical writing and ruby text. We could extend the discussion on W3C TPAC Fukuoka as an unconferenced day topic to collect more comments.

## Ruby text with screen reader.

[This page](https://bobbytung.github.io/Ruby_testcase_TTS/) lists three usage of ruby text:

1. for spelling/pronunciation.

2. for another language (and Katakana).

3. for different meaning.

## Page progress direction with screen reader.

I've recorded 3 videos with iOS 12 on iPhone X with Voice Over function on to read ebooks in Apple Books App.

1. [A normal English book](https://vimeo.com/user32432365/review/357069179/59d36065c1)

2. [A Japanese vertical writing book](https://vimeo.com/user32432365/review/357069478/6216b4b8e6)[^1]

3. [A Japanese book mixed with horizontal and vertical writing](https://vimeo.com/user32432365/review/357070184/48a6241dda)

I'm not visually impaired, so I don't know how Voice Over should work, but compare the behavior, I can list some requirement:

1. Reader(TTS engine) should notice user about page progress direction (for Japanese/Chinese vertical writing books, flip left to right).

2. Behavior should be consistent for content structure. In video 2, voice stopped before end of line, not end of paragraph.

3. In paged media as EPUB, page progress direction should follow metadata (i.e. page-progression in <spine>).

[^1]: [鈴木勉の本（抜粋版）](https://bccks.jp/bcck/115255/info)
  
  
