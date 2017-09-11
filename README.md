 
  Copyright (c) 1996, 1998, 1999, 2000, 2003, 2004, 2006,
	2013, 2014, 2016
  Tama Communications Corporation. All rights reserved.
 
  Redistribution and use in source and binary forms, with or without
  modification, are permitted provided that the following conditions
  are met:
  1. Redistributions of source code must retain the above copyright
     notice, this list of conditions and the following disclaimer.
  2. Redistributions in binary form must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.
 
  THIS SOFTWARE IS PROVIDED BY THE AUTHOR AND CONTRIBUTORS ``AS IS'' AND
  ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
  IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
  ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE
  FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
  DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
  OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
  HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
  LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
  OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
  SUCH DAMAGE.
 
                ----------------------------------

履歴書スタイル(B5サイズ x 2) version 2.7

						2016/2/12 有限会社多摩通信社

履歴書を作成するためのスタイルファイルです。

一度必要事項を埋めてしまえば、後はいくらでも履歴書が生成出来ますので、
就職活動の合理化が図れます。


対応LaTeX:
	アスキー版 pLaTeX2
漢字コード:
	UTF-8
履歴書サイズ:
	B5 x 2 (市販のものと同じ大きさです)
出力用紙:
	B5用紙
	B5用紙2枚に見開きイメージで印刷しますので、2枚並べてB4用紙に
	コピーしてお使いください。
最新のものは下記の場所にございます。

	http://www.tamacom.com/rireki-j.html

------------------------------------------------------------------------------
[使用方法]
------------------------------------------------------------------------------

1. 履歴書の必要事項を記入する

	rireki.tex をコピーして、注釈を参考にしながら必要項目を記入します。
	一度rireki.tex をそのままコンパイルして出力してみることをおすすめします。

2. DVIファイル(rireki.dvi)を生成する

	$ platex rireki

4. PDFファイル(rireki.pdf)に変換する

	$ dvipdfmx -p jisb5 rireki.dvi

5. PDFファイルを出力する

	Adobe Reader を用いて紙に出力します。
	プリンタがない場合は、コンビニのプリントサービスを利用します。

------------------------------------------------------------------------------
[トラブルシューティング]
------------------------------------------------------------------------------

o 本スタイルファイルは、UTF-8で記述されています。
  ご使用のTeXがUTF-8版でない場合は、rireki.sty およびrireki.tex をご使用の
  TeXの対応コードに変換した上で、ご利用ください。

o 不具合などございましたら、弊社問い合わせ窓口までメールでご連絡いただければ
  幸いです。

ご健闘をお祈り致します。
