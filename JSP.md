# JSP 页面元素构成
<h3>1.静态内容</h3>
<h3>2.指令</h3>
      page指令：位于jsp页面顶端，且可包含多个page指令<br>
          语法：<%@page 属性1="属性值" 属性2="属性值" ... 属性n="属性值"%>
            <table>
            <tr><td>属性</td><td>描述</td><td>默认值</td></tr>
            <tr><td>language</td><td>制定JSP页面使用的脚本语言</td><td>java</td></tr>
            <tr><td>import</td><td>通过该属性来引用脚本语言中使用到的类文件</td><td></td></tr>
            <tr><td>contentType</td><td>用来指定JSP页面所采用的编码方式</td><td>text/html,ISO-8859-1</td>
            </tr>
            </table>
      include指令（包含）：将外部文件嵌入到jsp文件中<br>
      taglib指令（标签库）：使用标签库定义新的自定义标签，在JSP页面中启用制定行为
<h3>3.表达式</h3>
         JSP中执行的表达式
         语法：<%= 表达式%> //不以分号结束
<h3>4.脚本</h3>
          语法：<% Java代码%>
<h3>5.声明</h3>
         在jsp页面中定义变量或方法
          语法：<%! Java代码%>
<h3>6.注释</h3>
      服务端注释：
            jsp注释：<%-- text --%>
            jsp脚本注释：//
                        /* */
      客户端注释：
            &lt;!-- --&gt;
<h1>九大内置对象</h1>
1.out
2.request
3.response
4.application
5.session
6.page
7.pagContext
8.exception
9.config
