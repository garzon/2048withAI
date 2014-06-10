# 2048 with AI
A clone of 2048 with AI by garzon.

此为在原版2048的基础上，添加了电脑AI解题，并稍微修改了UI添加按钮来触发AI。<br />
AI的核心在/js/myAI.js里，相关函数在window.myPlugin里<br />
核心算法是用dfs搜3步后使代价函数window.myPlugin.evalCost期望值最小的走法，<br />
代价函数的设计目的是让块尽量按由大到小顺序堆叠在右上角，并合并。<br />
实验效果是基本能保证到2048，偶尔到4096甚至8192(概率较小)。 <br />
可单独把myAI.js提取出来作为脚本在浏览器里直接运行

# Changes
Add myAI.js - the core of AI <br />
Modify index.html - link to the myAI.js and replace the note

# License
(c) 2014 Garzon. Released under the terms of the MIT license.
AI by Garzon.2048 by Gabriele Cirulli (http://gabrielecirulli.com/). The original game can be found at http://gabrielecirulli.github.io/2048/.

