Ndic
====

English-Korean Dictionary on Command Line
(Powered by [Naver](http://endic.naver.com/))


## Installation

Install via npm:

    npm install ndic -g


## Usage

    Usage: ndic [-hds] <word>

    Description:
      Find the meaning of <word> in English-Korean Dictionary.
      (Powered by Naver)

    Options:
      -h  Show help message
      -d  Turn on debug mode
      -s  Speak the word
      -c  Search by clipboard contents

    Examples:
      $ ndic nice
      [형용사](기분) 좋은, 즐거운, 멋진
      [명사]니스 ((프랑스 남동부의 피한지))

      $ ndic "good thing" # use quotes if a word has spaces
      [구어] 좋은 일; 좋은 착상; 행운; 경구; 진미; 사치품

      $ ndic -s nice # search and speak the word     

      $ ndic -c # search by clipboard contents
