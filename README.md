# markdown-example

### markdown是一种轻量级标记语言，具有纯文本格式语法。它由John Gruber 与Aaron Swartz在2004年合作创建。其目标是让人们“使用易于阅读且易于编写的纯文本格式进行编写，可选将其转换为结构上有效的XHTML或HTML”。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性 [文档](https://www.markdownguide.org/basic-syntax/)

其实markdown基本支持html, 如果想做比较好看的, 直接用html即可, 可以设定css markdown了解简单的即可,完全没必要再去琢磨怎么用好、美化.  


### 一. 标题
  <details>
  <summary>效果展示</summary>
    <pre>
    <img width="580" alt="image" src="https://github.com/StanleyCocos/markdown-example/assets/22318878/a07b435e-2e8e-4e5c-9966-8ad2c1a1c58c">
    </pre>
  </details>
  
 <details>
  <summary>代码</summary>
    <pre>
      <code>
# 一级标题
## 二级标题
### 三级标题
### 四级标题
#### 五级标题
##### 六级标题
###### 七级标题
      </code>
     </pre>
</details>


### 二. 字体
<details>
  <summary>效果展示</summary>
    <pre>
    <img width="380" alt="image" src="https://github.com/StanleyCocos/markdown-example/assets/22318878/8dfec9a0-457c-410b-ba3b-765ca9881a9e">
    </pre>
</details>

 <details>
  <summary>代码</summary>
    <pre>
      <code>
*我是斜体*
_我是斜体_
**我是加粗**
__我是加粗__
~~我是删除~~
***我是又粗又斜***
___我是又粗又斜___
      </code>
     </pre>
</details>


### 三. 图片
<details>
  <summary>效果展示</summary>
    <pre>
    <img width="580" alt="image" src="https://markdown.tw/images/208x128.png">
    </pre>
  </details>
<details>
  <summary>代码</summary>
    <pre>
      <code>
![图片未加载出来展示文本](https://markdown.tw/images/208x128.png "图片说明")
      </code>
     </pre>
</details>


### 四. 代码块

<details>
  <summary>效果展示</summary>
    <pre>
    <img width="303" alt="image" src="https://github.com/StanleyCocos/markdown-example/assets/22318878/6e3eb7f7-7d9f-43e1-9b1b-f1c5901bdad9">
    </pre>
 </details>
 
 <details>
  <summary>代码</summary>
    <pre>
      <code>
```python
import os
print("hello world")
def show_time():
return time.time()
```
      </code>
     </pre>
</details>
  

### 五. 分割线
<details>
  <summary>效果展示</summary>
    <pre>
    <img width="939" alt="image" src="https://github.com/StanleyCocos/markdown-example/assets/22318878/10cd91fc-730b-4041-ad51-d53cdd333ca8">
    </pre>
 </details>
 <details>
  <summary>代码</summary>
    <pre>
      <code>
***
---
      </code>
     </pre>
</details>



### 六. 超链接
<details>
  <summary>效果展示</summary>
    <pre>
    <img width="295" alt="image" src="https://github.com/StanleyCocos/markdown-example/assets/22318878/742bd53c-44f5-4bb2-9057-1edd9ae6f692">
    </pre>
 </details>
 <details>
  <summary>代码</summary>
    <pre>
      <code>
[超链接](https://www.markdownguide.org)
[引用链接](https://www.markdownguide.org "说明文字")
[![图片超链接](https://markdown.tw/images/208x128.png "图片说明")](https://www.markdownguide.org)
      </code>
     </pre>
</details>

### 七. 表格
<details>
  <summary>效果展示</summary>
    <pre>
    <img width="318" alt="image" src="https://github.com/StanleyCocos/markdown-example/assets/22318878/60c40df7-a55b-43ad-b68e-f18802968ee6">
    </pre>
 </details>

 <details>
  <summary>代码</summary>
    <pre>
      <code>
表格由3个部分组成
第一个部分是表格的标题，使用|来作为列的分割
第二个部分是表示列的对齐方式，有左对齐、居中对齐和居右对齐三种类型，直接看例子吧， --- 表示了默认的左对齐， :--- 表示 左对齐 ， ---: 表示 右对齐 ， :---: 表示居中对齐
第三个部分就是内容了，表示方式跟标题一样，可以有多行  
|居左|居中|居右|默认|
|:------|:------:|------:|------|
|居左|居中|居右|默认|
|测试文本|测试文本|测试文本|测试文本|
      </code>
     </pre>
</details>

### 八. 列表
<details>
  <summary>效果展示</summary>
    <pre>
    <img width="503" alt="image" src="https://github.com/StanleyCocos/markdown-example/assets/22318878/ba392f57-7a30-4237-9c14-277523d1b07c">
    </pre>
 </details>
<details>
  <summary>代码</summary>
    <pre>
      <code>
使用 -、+ 和 *+空格 +文字内容 表示无序列表
可用tab 或者空格 + -、+ 或者 * +文字内容使列表嵌套
成功嵌套的条件是下一层的-、+ 和 * 的前面的空白长度满足以下条件
tab长度×(层数-1) < 空白长度 ≤ tab长度×层数
- 1
    - 1-2
        - 1-3-1
+ 第一层
    * 第二层
        * 第三层


+ 再来一个第一层

1. 第一层
    1. 第一层
    2. 第二层
        1. 第一层
        2. 第二层
    
      </code>
     </pre>
</details>


### 九. 流程图
  
  <details>
  <summary>效果展示</summary>
    <pre>
     <img width="717" alt="image" src="https://github.com/StanleyCocos/markdown-example/assets/22318878/711e4a8a-0c51-4592-93ae-8e99cc47c82e">
    </pre>
 </details>
 

  <details>
  <summary>代码</summary>
    <pre>
      <code>
我是没搞懂 谁会用这个玩意 去做流程图 
```mermaid 
  sequenceDiagram
  Alice->>John: Hello John, how are you?
  loop Healthcheck
  John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```  
      </code>
     </pre>
</details>
  

### 十. 表情符号 [Unicode 列表]([https://www.markdownguide.org](https://apps.timwhitlock.info/emoji/tables/unicode#))
<details>
  <summary>代码</summary>
    <pre>
      <code>
语法："&#xcode"; (注意最后的分号 ; 不可少)

其中 code 可以从表情符号 Unicode 列表中查到

例子： 查到了 表情对应的 Unicode 编码为 U+1F600，则与此表情对应的 CODE 为 1F600 (舍弃前面的 U+)。我们只需在 Markdown 文档中输入 &#x1F600; 即可显示为 😀。

&#x1F600;

❤️ ✨⭐ ❗❓❕❔ ✊✌️ ✋✋ ☝️

☀️ ☔ ☁️ ❄️ ⛄ ⚡ ⛅

☎️ ☎️ ⌛ ⏳ ⏰ ⌚ ➿ ✉️ ✉️ ✂️ ✒️ ✏️ ⚽ ⚾️ ⛳ ♠️ ♥️ ♣️ ♦️ ☕

⛪ ⛺ ⛲ ⛵ ⛵ ⚓ ✈️ ⛽ ⚠️ ♨️

1️⃣ 2️⃣ 3️⃣ 4️⃣ 5️⃣ 6️⃣ 7️⃣ 8️⃣ 9️⃣ 0️⃣ #️⃣ ◀️ ⬇️ ▶️ ⬅️ ↙️ ↘️ ➡️ ⬆️ ↖️ ↗️ ⏬ ⏫ ⤵️ ⤴️ ↩️ ↪️ ↔️ ↕️ ⏪ ⏩ ℹ️ ️ ️ ️ ♿ ㊙️ ㊗️ Ⓜ️ ⛔ ✳️ ❇️ ✴️ ♈ ♉ ♊ ♋ ♌ ♍ ♎ ♏ ♐ ♑ ♒ ♓ ⛎ ❎ ️ ️ ️ ♻️ ©️ ®️ ™️ ❌ ❗ ‼️ ⁉️ ⭕ ✖️ ➕ ➖ ➗ ✔️ ☑️ ➰ 〰️ 〽️ ▪️ ▫️ ◾ ◽ ◼️ ◻️ ⬛ ⬜ ✅ ⚫ ⚪
      </code>
     </pre>
</details>
  
### 十一. [数学公式](https://1024th.github.io/MathJax_Tutorial_CN/#/full_doc/basic)

