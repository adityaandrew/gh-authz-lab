# HBV4 math lane

1 href-js
$$\href{javascript:alert(1)}{CLICK1}$$

2 href-data
$$\href{data:text/html,<script>alert(2)</script>}{CLICK2}$$

3 url
$$\url{javascript:alert(3)}$$

4 includegraphics
$$\includegraphics{javascript:alert(4)}$$

5 htmlData
$$\htmlData{foo=bar}{CLICK5}$$

6 htmlClass htmlId htmlStyle
$$\htmlClass{c6}{\htmlId{i6}{\htmlStyle{color:red}{CLICK6}}}$$

7 text with markup
$$\text{<img src=x onerror=alert(7)>}$$

8 macro def then href
$$\def\p{javascript:alert(8)}\href{\p}{CLICK8}$$

9 href relative-scheme
$$\href{//evil.example.com}{CLICK9}$$

10 href vbscript
$$\href{vbscript:alert(10)}{CLICK10}$$

11 inline math
$`\href{javascript:alert(11)}{CLICK11}`$

12 benign control
$$E = mc^2$$
