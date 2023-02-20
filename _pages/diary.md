---
layout: page
title: My Diary
permalink: /diary/
description: Keeping my life here.
nav: false
horizontal: false
---

<head>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

  <script>
    $(document).ready(function() {
        $("#diary-password-form").submit(function(e) {
            e.preventDefault();
            var password = $("#diary-password-input").val();
            if (password === "1234657890") {
                $("#diary-content").show();
            } else {
                alert("Incorrect password!");
            }
        });
    });
  </script>

  <script>
    function showContent() {
    var password = prompt("Please enter password:");
    if (password === "1234657890") {
        $("#diary-content").show();
    } else {
        alert("Incorrect password!");
    }
    }
  </script>

</head>


<div id="diary-content" style="display: none;">

<h2>16 -- 22岁，在中国</h2>

<ul>
    <li><a href="/my_diaries/intro.md">引言</a></li>
    <li><a href="/my_diaries/love_stories_china/第0篇_张蕴之.md">第0篇：张蕴之</a></li>
    <li><a href="/my_diaries/love_stories_china/第1篇_陈钰琳.md">第1篇：陈钰琳</a></li>
    <li><a href="/my_diaries/love_stories_china/第2篇_崔怡丹.md">第2篇：崔怡丹</a></li>
    <li><a href="/my_diaries/love_stories_china/第3篇_陆祎琳.md">第3篇：陆祎琳</a></li>
    <li><a href="/my_diaries/love_stories_china/第4篇_吴嘉鑫.md">第4篇：吴嘉鑫</a></li>
    <li><a href="/my_diaries/love_stories_china/第5篇_靳梦楚.md">第5篇：靳梦楚</a></li>
    <li><a href="/my_diaries/love_stories_china/番外篇.md">番外篇</a></li>
</ul>

<h2>22 -- Present, USA</h2>

</div>

<button onclick="showContent()">Show Diary</button>