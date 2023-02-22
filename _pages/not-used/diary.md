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
    <li><a href="https://raw.githubusercontent.com/honglizhan/My-Diaries/main/Love%20Stories%20--%20China/%E5%BC%95%E8%A8%80.md?token=GHSAT0AAAAAAB5GCDF44SKURS2OFDUMLF3UY7T37YQ">引言</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/My-Diaries/main/Love%20Stories%20--%20China/%E7%AC%AC0%E7%AF%87_%E5%BC%A0%E8%95%B4%E4%B9%8B.md?token=GHSAT0AAAAAAB5GCDF4WHVTS3HGKROKMK62Y7T4AMQ">第0篇：张蕴之</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/My-Diaries/main/Love%20Stories%20--%20China/%E7%AC%AC1%E7%AF%87_%E9%99%88%E9%92%B0%E7%90%B3.md?token=GHSAT0AAAAAAB5GCDF4LK6ZBSHAS7UUBU3EY7T4BDA">第1篇：陈钰琳</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/My-Diaries/main/Love%20Stories%20--%20China/%E7%AC%AC2%E7%AF%87_%E5%B4%94%E6%80%A1%E4%B8%B9.md?token=GHSAT0AAAAAAB5GCDF4KBCL5CMLWT5UYEXKY7T4BMQ">第2篇：崔怡丹</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/My-Diaries/main/Love%20Stories%20--%20China/%E7%AC%AC3%E7%AF%87_%E9%99%86%E7%A5%8E%E7%90%B3.md?token=GHSAT0AAAAAAB5GCDF4ZRPXDHQN5JUVFGDIY7T4BWA">第3篇：陆祎琳</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/My-Diaries/main/Love%20Stories%20--%20China/%E7%AC%AC4%E7%AF%87_%E5%90%B4%E5%98%89%E9%91%AB.md?token=GHSAT0AAAAAAB5GCDF5BSCEPQDWPYV5QAUYY7T4B6A">第4篇：吴嘉鑫</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/My-Diaries/main/Love%20Stories%20--%20China/%E7%AC%AC5%E7%AF%87_%E9%9D%B3%E6%A2%A6%E6%A5%9A.md?token=GHSAT0AAAAAAB5GCDF5HHZWHNYVT2ZDMIWKY7T4CFQ">第5篇：靳梦楚</a></li>
    <li><a href="https://raw.githubusercontent.com/honglizhan/My-Diaries/main/Love%20Stories%20--%20China/%E7%95%AA%E5%A4%96%E7%AF%87.md?token=GHSAT0AAAAAAB5GCDF4NYIJEOIRMRZ7NZSMY7T4CMQ">番外篇</a></li>
</ul>

<h2>22 -- Present, USA</h2>

</div>

<button onclick="showContent()">Show Diary</button>