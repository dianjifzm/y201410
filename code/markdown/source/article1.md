## 本雜誌的投搞方式

大家好，我是 [少年科技人雜誌] 與 [程式人雜誌] 的編輯「陳鍾誠」，歡迎收看本雜誌！

由於有不少熱心的朋友詢問該如何投稿給這兩個雜誌，因此我特別撰寫這篇文章來說明撰寫文章與投搞的方法。

我在編輯雜誌時，採用的是 Markdown 語法來撰寫文件，然後用 pandoc + makefile + calibre ebook-convert + mimetex 等工具進行轉換，但是如果您只是要撰寫文章給我們出刊，不需要用到這麼多工具。

如果您會撰寫 Markdown 文件，請直接寫完後將檔案 (連同圖片一起壓縮成 zip 檔) 之後寄到 ccckmit@gmail.com 給我就可以了，但是如果您不會撰寫 Markdown 文件，那麼也可以採用 MS. Word，Libre Office 的 Writer 、Google Doc、甚至是網誌的傳寫方法，然後將文件或網址寄給我，我會自行編輯成 Markdown 格式之後納入雜誌出刊。

當您投稿時，最重要需注意的一件事情，是智慧財產權的問題。

您必須確定投搞的文章沒有侵權的問題！

如果文章與圖片完全是您自行製作的，那應該不會侵權。但是如果您有使用網路上的圖片或修改網路上的文章，請務必採用沒有侵權疑慮的來源，像是 [維基百科] 或者 [創作共用](http://zh.wikipedia.org/zh-tw/%E5%88%9B%E4%BD%9C%E5%85%B1%E7%94%A8) 授權的文章，並且標明修改來源。

舉例而言，如果您修改自維基百科，請標上「本文修改自維基百科」，如果是其他「創作共用」文章或圖片，則需要附上原始文件或圖片的連結。

以下是「創作共用」文章的授權類型，您可以在標識姓名來源後採用「姓名標示（BY）」與「
姓名標示（BY）-相同方式分享（SA）」這兩類授權的文章，也可以在特別標示授權後採用「姓名標示（BY）-非商業性（NC）」或「姓名標示（BY）-非商業性（NC）-相同方式分享（SA）」的文章，但是不要採用有「禁止改作（ND）」的文章來進行衍生創作。

![](../img/cclicenses.jpg)

如果您不熟悉 Markdown 的語法，可以參考 <http://markdown.tw/> 中的說明，或者直接閱讀本文件的 [原始碼](article1.md)。

然後我使用的方法是，安裝 pandoc 之後，用下列指令將 article1.md 轉為 article1.html

> pandoc -s article1.md -o article1.html

[程式人雜誌社團]: https://www.facebook.com/groups/programmerMagazine/
[少年科技人社團]: https://www.facebook.com/groups/youngmaker.magazine/
[少年科技人雜誌]:http://youngmaker.github.com/home/
[程式人雜誌]:http://programmermagazine.github.com/home/
[維基百科]:http://zh.wikipedia.org/
