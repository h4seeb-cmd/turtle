---
keywords: fastai
description: Demonstration of the JavaScript kernel working in a Jupyter Notebook
title: "JavaScript Demonstration"
toc: true
comments: true 
branch: master
badges: true
author: Haseeb Beg
categories: [fastpages, jupyter, Week 5]
permalink: /submenu/js-trial-and-error
nb_path: _notebooks/2022-09-22-js-trial-and-error.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-22-js-trial-and-error.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<table>
        <tbody>
    <tr>
        <td>
        <a href="{{site.baseurl}}/submenu/js-trial-and-error">JS Table</a>
        </td>
        <td>
        <a href="{{site.baseurl}}/submenu2/APIUsage">API Usage</a>
        </td>
        <td>
        <a href="#">Link 3</a>
        </td>
    </tr>
        </tbody>
</table>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="kd">var</span> <span class="nx">Letters</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;a&quot;</span><span class="p">,</span> <span class="s2">&quot;b&quot;</span><span class="p">,</span> <span class="s2">&quot;c&quot;</span><span class="p">,</span> <span class="s2">&quot;d&quot;</span><span class="p">,</span> <span class="s2">&quot;e&quot;</span><span class="p">,</span> <span class="s2">&quot;f&quot;</span><span class="p">,</span> <span class="s2">&quot;g&quot;</span><span class="p">,</span> <span class="s2">&quot;h&quot;</span><span class="p">,</span> <span class="s2">&quot;i&quot;</span><span class="p">,</span> <span class="s2">&quot;j&quot;</span><span class="p">,</span> <span class="s2">&quot;k&quot;</span><span class="p">,</span> <span class="s2">&quot;l&quot;</span><span class="p">,</span> <span class="s2">&quot;m&quot;</span><span class="p">,</span> <span class="s2">&quot;n&quot;</span><span class="p">,</span> <span class="s2">&quot;o&quot;</span><span class="p">,</span> <span class="s2">&quot;p&quot;</span><span class="p">,</span> <span class="s2">&quot;q&quot;</span><span class="p">,</span> <span class="s2">&quot;r&quot;</span><span class="p">,</span> <span class="s2">&quot;s&quot;</span><span class="p">,</span> <span class="s2">&quot;t&quot;</span><span class="p">,</span> <span class="s2">&quot;u&quot;</span><span class="p">,</span> <span class="s2">&quot;v&quot;</span><span class="p">,</span> <span class="s2">&quot;w&quot;</span><span class="p">,</span> <span class="s2">&quot;x&quot;</span><span class="p">,</span> <span class="s2">&quot;y&quot;</span><span class="p">,</span> <span class="s2">&quot;z&quot;</span><span class="p">];</span>
<span class="kd">var</span> <span class="nx">numbers</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;1&quot;</span><span class="p">,</span> <span class="s2">&quot;2&quot;</span><span class="p">,</span> <span class="s2">&quot;3&quot;</span><span class="p">,</span> <span class="s2">&quot;4&quot;</span><span class="p">,</span> <span class="s2">&quot;5&quot;</span><span class="p">];</span>
<span class="kd">var</span> <span class="nx">rLetters</span> <span class="o">=</span> <span class="nb">Math</span><span class="p">.</span><span class="nx">floor</span><span class="p">(</span><span class="nb">Math</span><span class="p">.</span><span class="nx">random</span><span class="p">()</span><span class="o">*</span><span class="nx">Letters</span><span class="p">.</span><span class="nx">length</span><span class="p">);</span>
<span class="kd">var</span> <span class="nx">rNumbers</span> <span class="o">=</span> <span class="nb">Math</span><span class="p">.</span><span class="nx">floor</span><span class="p">(</span><span class="nb">Math</span><span class="p">.</span><span class="nx">random</span><span class="p">()</span><span class="o">*</span><span class="nx">numbers</span><span class="p">.</span><span class="nx">length</span><span class="p">);</span>
<span class="kd">var</span> <span class="nx">user</span> <span class="o">=</span> <span class="nx">Letters</span><span class="p">[</span><span class="nx">rLetters</span><span class="p">]</span> <span class="o">+</span> <span class="nx">numbers</span><span class="p">[</span><span class="nx">rNumbers</span><span class="p">];</span>
<span class="nx">console</span><span class="p">.</span><span class="nx">log</span> <span class="p">(</span><span class="nx">user</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>w5
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-javascript"><pre><span></span><span class="c1">// Defining variable team</span>
<span class="kd">var</span> <span class="nx">team</span> <span class="o">=</span> <span class="p">{</span>
    <span class="nx">Haseeb</span><span class="o">:</span> <span class="s2">&quot;h4seeb-cmd&quot;</span><span class="p">,</span>
    <span class="nx">Shaurya</span><span class="o">:</span> <span class="s2">&quot;STG-7&quot;</span><span class="p">,</span>
    <span class="nx">Tirth</span><span class="o">:</span> <span class="s2">&quot;Tirth-Thakkar&quot;</span><span class="p">,</span>
    <span class="nx">Evan</span><span class="o">:</span> <span class="s2">&quot;chewy-boba10&quot;</span><span class="p">,</span>
    <span class="nx">Alex</span><span class="o">:</span> <span class="s2">&quot;YLu-1258&quot;</span>
<span class="p">};</span>

<span class="c1">// Creating the function to make the table</span>
<span class="kd">function</span> <span class="nx">createTable</span><span class="p">(</span><span class="nx">values</span><span class="p">){</span>
    <span class="kd">var</span> <span class="nx">table</span> <span class="o">=</span> <span class="s2">&quot;&lt;table&gt;&lt;tr&gt;&lt;th&gt;Name&lt;/th&gt;&lt;th&gt;GitHub Username&lt;/th&gt;&lt;/tr&gt;&quot;</span>
    <span class="kd">var</span> <span class="nx">keys</span> <span class="o">=</span> <span class="nb">Object</span><span class="p">.</span><span class="nx">keys</span><span class="p">(</span><span class="nx">values</span><span class="p">);</span>

<span class="c1">// Printing the values into the table</span>
    <span class="k">for</span><span class="p">(</span><span class="kd">var</span> <span class="nx">index</span> <span class="k">in</span> <span class="nx">keys</span><span class="p">){</span>
        <span class="kr">const</span> <span class="nx">key</span> <span class="o">=</span> <span class="nx">keys</span><span class="p">[</span><span class="nx">index</span><span class="p">];</span>
        <span class="kr">const</span> <span class="nx">value</span> <span class="o">=</span> <span class="nx">team</span><span class="p">[</span><span class="nx">key</span><span class="p">];</span>
        <span class="nx">table</span> <span class="o">+=</span> <span class="s2">&quot;&lt;tr&gt;&lt;td&gt;&quot;</span><span class="o">+</span><span class="nx">key</span><span class="o">+</span><span class="s2">&quot;&lt;/td&gt;&lt;td&gt;&quot;</span><span class="o">+</span><span class="nx">value</span><span class="o">+</span><span class="s2">&quot;&lt;/td&gt;&lt;/tr&gt;&quot;</span><span class="p">;</span>
    <span class="p">}</span>
    <span class="nx">table</span> <span class="o">+=</span> <span class="s2">&quot;&lt;/table&gt;&quot;</span><span class="p">;</span>
    <span class="k">return</span> <span class="nx">table</span><span class="p">;</span>
<span class="p">}</span>

<span class="nx">$$</span><span class="p">.</span><span class="nx">html</span><span class="p">(</span><span class="nx">createTable</span><span class="p">(</span><span class="nx">team</span><span class="p">));</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">


<div class="output_html rendered_html output_subarea output_execute_result">
<table><tr><th>Name</th><th>GitHub Username</th></tr><tr><td>Haseeb</td><td>h4seeb-cmd</td></tr><tr><td>Shaurya</td><td>STG-7</td></tr><tr><td>Tirth</td><td>Tirth-Thakkar</td></tr><tr><td>Evan</td><td>chewy-boba10</td></tr><tr><td>Alex</td><td>YLu-1258</td></tr></table>
</div>

</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

