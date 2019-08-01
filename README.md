# Element-Xpath
實現Element物件轉成Xpath，和Xpath轉成Element物件

### 作法
<p>開網頁，按F12，將js內容貼上按Enter</p>
<p>裡面的A代表某個物件的id</p>
<p>使用getXPath會得到該物件的XPath</p>
<pre><code>getXPath('documetn.document.getElementById('A')')
</code></pre>
<p>使用getElementByXpath會得到該物件的Element</p>
<pre><code>getElementByXpath('id(A)')
</code></pre>
