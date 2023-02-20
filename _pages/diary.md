---
layout: page
title: My Diary
permalink: /diary/
description: Keeping my life here.
nav: false
horizontal: false
---

<head>
  <script>
  function showContent() {
      var password = prompt("Please enter the password:");
      if (password == "<your_password>") {
          document.getElementById("diary-content").style.display = "block";
      } else {
          alert("Incorrect password!");
      }
  }
  </script>
</head>


<div id="diary-content" style="display: none;">

    <h2>16 -- 22岁，在中国</h2>

    - [引言](/_my_diaries/_love_stories_china/引言.md)
    - [第0篇：张蕴之](/_my_diaries/_love_stories_china/第0篇_张蕴之.md)
    - [第1篇：陈钰琳](/_my_diaries/_love_stories_china/第1篇_陈钰琳.md)
    - [第2篇：崔怡丹](/_my_diaries/_love_stories_china/第2篇_崔怡丹.md)
    - [第3篇：陆祎琳](/_my_diaries/_love_stories_china/第3篇_陆祎琳.md)
    - [第4篇：吴嘉鑫](/_my_diaries/_love_stories_china/第4篇_吴嘉鑫.md)
    - [第5篇：靳梦楚](/_my_diaries/_love_stories_china/第5篇_靳梦楚.md)
    - [番外篇](/_my_diaries/_love_stories_china/番外篇.md)
    
    <h2>22 -- Present, USA</h2>

</div>

<button onclick="showContent()">Show Diary</button>