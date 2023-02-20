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
    <li><a href="https://raw.githubusercontent.com/honglizhan/honglizhan.github.io/master/_my_diaries/_love_stories_china/%E5%BC%95%E8%A8%80.md">引言</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/honglizhan.github.io/master/_my_diaries/_love_stories_china/%E7%AC%AC0%E7%AF%87_%E5%BC%A0%E8%95%B4%E4%B9%8B.md">第0篇：张蕴之</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/honglizhan.github.io/master/_my_diaries/_love_stories_china/%E7%AC%AC1%E7%AF%87_%E9%99%88%E9%92%B0%E7%90%B3.md">第1篇：陈钰琳</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/honglizhan.github.io/master/_my_diaries/_love_stories_china/%E7%AC%AC2%E7%AF%87_%E5%B4%94%E6%80%A1%E4%B8%B9.md">第2篇：崔怡丹</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/honglizhan.github.io/master/_my_diaries/_love_stories_china/%E7%AC%AC3%E7%AF%87_%E9%99%86%E7%A5%8E%E7%90%B3.md">第3篇：陆祎琳</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/honglizhan.github.io/master/_my_diaries/_love_stories_china/%E7%AC%AC4%E7%AF%87_%E5%90%B4%E5%98%89%E9%91%AB.md">第4篇：吴嘉鑫</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/honglizhan.github.io/master/_my_diaries/_love_stories_china/%E7%AC%AC5%E7%AF%87_%E9%9D%B3%E6%A2%A6%E6%A5%9A.md">第5篇：靳梦楚</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/honglizhan.github.io/master/_my_diaries/_love_stories_china/%E7%95%AA%E5%A4%96%E7%AF%87.md">番外篇</a></li>
</ul>

<h2>22 -- Present, USA</h2>

</div>

<button onclick="showContent()">Show Diary</button>