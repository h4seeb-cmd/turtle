---
layout: page
title: Trivia Prototype
permalink: /triv/
---

<style>
    .card{
        height: 50px;
        width: 200px;
        border-style: solid;
        border-color: black;
        display: inline-grid;
        justify-self: center;
        margin: auto;
        border-radius: 30px;
        text-align: center;
        color: black !important;
        justify-content: center;
    }
    #card1{
        background-color: blue !important;
        justify-content:center;
        text-align: center;
        color: black !important;
    }
    #card2{
        background-color: green !important;
        color: black;
    }
    #card3{
        background-color: red !important;
        color: black;
    }
    #card4{
        background-color: yellow !important;
        color: black;
    }
    .grid{
        display: block;
        grid-columns: 200px 200px;
        justify-self: center !important;
    }
</style>


### Question: What IDE is reccomended for APCSP?

<div class = grid id = grid1>
<div class = "card" id = "card1">
<p> Pycharm </p>
</div>

<div class = "card" id = "card2">
<p> VSCode </p>
</div>
</div>
<div class = grid id = grid2>

<div class = "card" id = "card3">
<p> Scratch </p>
</div>

<div class = "card" id = "card4">
<p> IntelliJ </p>
</div>

</div>