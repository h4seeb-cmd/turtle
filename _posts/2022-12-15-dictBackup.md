---
keywords: fastai
title: Title
nb_path: _notebooks/dictBackup.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/dictBackup.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-python"><pre><span></span><span class="n">dataset</span> <span class="o">=</span> <span class="p">{</span>
    <span class="s1">&#39;DelNorte&#39;</span><span class="p">:{</span>
        <span class="s1">&#39;Westview&#39;</span><span class="p">:</span><span class="mi">15</span><span class="p">,</span>
        <span class="s1">&#39;MtCarmel&#39;</span><span class="p">:</span><span class="mi">20</span><span class="p">,</span>
        <span class="s1">&#39;Poway&#39;</span><span class="p">:</span><span class="mi">35</span><span class="p">,</span>
        <span class="s1">&#39;RanchoBernrdo&#39;</span><span class="p">:</span><span class="mi">50</span>
    <span class="p">},</span>
    <span class="s1">&#39;Westview&#39;</span><span class="p">:{</span>
        <span class="s1">&#39;DelNorte&#39;</span><span class="p">:</span><span class="mi">15</span><span class="p">,</span>
        <span class="s1">&#39;MtCarmel&#39;</span><span class="p">:</span><span class="mi">35</span><span class="p">,</span>
        <span class="s1">&#39;Poway&#39;</span><span class="p">:</span><span class="mi">25</span><span class="p">,</span>
        <span class="s1">&#39;RanchoBernrdo&#39;</span><span class="p">:</span> <span class="mi">45</span>
    <span class="p">},</span>
    <span class="s1">&#39;MtCarmel&#39;</span><span class="p">:{</span>
        <span class="s1">&#39;Westview&#39;</span><span class="p">:</span><span class="mi">35</span><span class="p">,</span>
        <span class="s1">&#39;DelNorte&#39;</span><span class="p">:</span><span class="mi">20</span><span class="p">,</span>
        <span class="s1">&#39;Poway&#39;</span><span class="p">:</span><span class="mi">40</span><span class="p">,</span>
        <span class="s1">&#39;RanchoBernrdo&#39;</span><span class="p">:</span><span class="mi">30</span>
    <span class="p">},</span>
    <span class="s1">&#39;Poway&#39;</span><span class="p">:{</span>
        <span class="s1">&#39;Westview&#39;</span><span class="p">:</span><span class="mi">25</span><span class="p">,</span>
        <span class="s1">&#39;MtCarmel&#39;</span><span class="p">:</span><span class="mi">40</span><span class="p">,</span>
        <span class="s1">&#39;DelNorte&#39;</span><span class="p">:</span><span class="mi">35</span><span class="p">,</span>
        <span class="s1">&#39;RanchoBernrdo&#39;</span><span class="p">:</span><span class="mi">15</span>
    <span class="p">},</span>
    <span class="s1">&#39;RanchoBernardo&#39;</span><span class="p">:{</span>
        <span class="s1">&#39;Westview&#39;</span><span class="p">:</span><span class="mi">45</span><span class="p">,</span>
        <span class="s1">&#39;MtCarmel&#39;</span><span class="p">:</span><span class="mi">30</span><span class="p">,</span>
        <span class="s1">&#39;Poway&#39;</span><span class="p">:</span><span class="mi">15</span><span class="p">,</span>
        <span class="s1">&#39;DelNorte&#39;</span><span class="p">:</span><span class="mi">50</span>
    <span class="p">}</span>
<span class="p">}</span>


<span class="k">def</span> <span class="nf">fastestroute</span><span class="p">(</span><span class="n">start</span><span class="p">,</span><span class="n">data</span><span class="p">):</span>
   <span class="n">drivetime</span> <span class="o">=</span> <span class="mi">0</span>
   <span class="n">order</span> <span class="o">=</span> <span class="p">[]</span>
   <span class="k">for</span> <span class="n">key1</span><span class="p">,</span> <span class="n">value1</span> <span class="ow">in</span> <span class="n">dataset</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;key1&quot;</span><span class="p">,</span> <span class="n">key1</span><span class="p">,</span> <span class="s2">&quot;value1&quot;</span><span class="p">,</span> <span class="n">value1</span><span class="p">)</span>
        <span class="nb">print</span><span class="p">(</span><span class="n">value1</span><span class="p">)</span>
        <span class="n">temp</span> <span class="o">=</span> <span class="s2">&quot;&quot;</span>
        <span class="n">temp</span> <span class="o">+=</span> <span class="n">key1</span>
        <span class="n">lowestValue</span> <span class="o">=</span> <span class="mi">0</span>
        <span class="k">for</span> <span class="n">key2</span><span class="p">,</span> <span class="n">value2</span> <span class="ow">in</span> <span class="n">value1</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;value2&quot;</span><span class="p">,</span> <span class="n">value2</span><span class="p">)</span>    
            <span class="k">if</span> <span class="n">lowestValue</span> <span class="o">==</span> <span class="mi">0</span><span class="p">:</span>
                 <span class="n">lowestValue</span> <span class="o">=</span> <span class="n">value2</span>
            <span class="k">if</span> <span class="n">value2</span> <span class="o">&lt;=</span> <span class="n">lowestValue</span><span class="p">:</span>
                 <span class="n">lowestValue</span> <span class="o">=</span> <span class="n">value2</span>
                 <span class="n">drivetime</span> <span class="o">=</span> <span class="n">drivetime</span> <span class="o">+</span> <span class="n">lowestValue</span>
                 <span class="n">lowestKey</span> <span class="o">=</span> <span class="n">key2</span>
                 <span class="n">order</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">key2</span><span class="p">)</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Lowest Value is:&quot;</span><span class="p">,</span> <span class="n">lowestValue</span><span class="p">)</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Drivetime:&quot;</span><span class="p">,</span> <span class="n">drivetime</span><span class="p">)</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Lowest Key&quot;</span><span class="p">,</span> <span class="n">lowestKey</span><span class="p">)</span>
        <span class="nb">print</span><span class="p">(</span><span class="n">order</span><span class="p">)</span>
        <span class="k">return</span><span class="p">(</span><span class="n">drivetime</span><span class="p">,</span><span class="n">order</span><span class="p">)</span>
   <span class="n">dataset</span><span class="p">[</span><span class="s1">&#39;start&#39;</span><span class="p">]</span>
   <span class="k">for</span> <span class="n">data</span> <span class="ow">in</span> <span class="n">dataset</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="n">drivetime</span><span class="p">,</span> <span class="n">order</span><span class="p">)</span>

<span class="k">def</span> <span class="nf">nested_dict_values_iterator</span><span class="p">(</span><span class="n">data</span><span class="p">):</span>
 <span class="k">for</span> <span class="n">value</span> <span class="ow">in</span> <span class="n">data</span><span class="o">.</span><span class="n">values</span><span class="p">():</span>
     <span class="k">if</span> <span class="nb">isinstance</span><span class="p">(</span><span class="n">value</span><span class="p">,</span> <span class="nb">dict</span><span class="p">):</span>
         <span class="k">for</span> <span class="n">v</span> <span class="ow">in</span> <span class="n">nested_dict_values_iterator</span><span class="p">(</span><span class="n">value</span><span class="p">):</span>
             <span class="k">yield</span> <span class="n">v</span>
         <span class="k">else</span><span class="p">:</span>
             <span class="k">yield</span> <span class="n">value</span>
             
<span class="c1">#for value in nested_dict_values_iterator(dataset):</span>
 <span class="c1">#   print(value)</span>
                 

<span class="k">def</span> <span class="nf">fastestroute2</span><span class="p">(</span><span class="n">start</span><span class="p">,</span> <span class="n">data</span><span class="p">):</span>
    <span class="n">drivetime</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">order</span> <span class="o">=</span> <span class="p">[]</span>
    <span class="n">order</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">start</span><span class="p">)</span>
    <span class="k">global</span> <span class="n">lowestKey</span>
    <span class="n">lowestKey</span> <span class="o">=</span> <span class="n">start</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">dataset</span><span class="p">:</span>
        <span class="c1">#print(&quot;Dataset&quot;, dataset[i])</span>
        <span class="c1">#print(&quot;data i: &quot;, data[i].keys())</span>
        <span class="c1">#print(data[i].values())</span>
        <span class="c1">#print(&quot;Data Poway&quot;, data[&#39;Poway&#39;])</span>
        <span class="k">for</span> <span class="n">key2</span><span class="p">,</span> <span class="n">value2</span> <span class="ow">in</span> <span class="n">dataset</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
            <span class="n">key2</span> <span class="o">=</span> <span class="n">lowestKey</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;First Dictionary key2&quot;</span><span class="p">,</span> <span class="n">key2</span><span class="p">,</span> <span class="s2">&quot;value2&quot;</span><span class="p">,</span> <span class="n">value2</span><span class="p">)</span>
            <span class="c1">#print(value2)</span>
            <span class="n">temp</span> <span class="o">=</span> <span class="s2">&quot;&quot;</span>
            <span class="n">temp</span> <span class="o">+=</span> <span class="n">key2</span>
            <span class="n">lowestValue</span> <span class="o">=</span> <span class="mi">0</span>
            <span class="k">for</span> <span class="n">key2</span><span class="p">,</span> <span class="n">value2</span> <span class="ow">in</span> <span class="n">value2</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
                <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Second Dictionary key2&quot;</span><span class="p">,</span> <span class="n">key2</span><span class="p">)</span>
                <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;value2&quot;</span><span class="p">,</span> <span class="n">value2</span><span class="p">)</span>    
                <span class="k">if</span> <span class="n">lowestValue</span> <span class="o">==</span> <span class="mi">0</span><span class="p">:</span>
                    <span class="n">lowestValue</span> <span class="o">=</span> <span class="n">value2</span>
                <span class="k">if</span> <span class="n">value2</span> <span class="o">&lt;=</span> <span class="n">lowestValue</span> <span class="ow">and</span> <span class="n">key2</span> <span class="ow">not</span> <span class="ow">in</span> <span class="n">order</span><span class="p">:</span>
                    <span class="n">lowestValue</span> <span class="o">=</span> <span class="n">value2</span>
                    <span class="n">drivetime</span> <span class="o">=</span> <span class="n">drivetime</span> <span class="o">+</span> <span class="n">lowestValue</span>
                    <span class="n">lowestKey</span> <span class="o">=</span> <span class="n">key2</span>
                    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Lowest key inside Second Dictionary : &quot;</span><span class="p">,</span> <span class="n">lowestKey</span><span class="p">)</span>
                    <span class="c1"># check if key is not already in order[]</span>
                    <span class="k">if</span> <span class="n">key2</span> <span class="ow">not</span> <span class="ow">in</span> <span class="n">order</span><span class="p">:</span>
                        <span class="n">order</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">key2</span><span class="p">)</span>
                <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Lowest Value is:&quot;</span><span class="p">,</span> <span class="n">lowestValue</span><span class="p">)</span>
                <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Drivetime:&quot;</span><span class="p">,</span> <span class="n">drivetime</span><span class="p">)</span>
                <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Lowest Key&quot;</span><span class="p">,</span> <span class="n">lowestKey</span><span class="p">)</span>
            <span class="nb">print</span><span class="p">(</span><span class="n">order</span><span class="p">)</span>
        <span class="k">return</span><span class="p">(</span><span class="n">drivetime</span><span class="p">,</span><span class="n">order</span><span class="p">)</span>
<span class="n">start</span> <span class="o">=</span> <span class="s1">&#39;DelNorte&#39;</span>
<span class="n">fastestroute2</span><span class="p">(</span><span class="n">start</span><span class="p">,</span><span class="n">dataset</span><span class="p">)</span>

<span class="c1"># &#39;dataset&#39; is the name of the nested key value pair</span>
<span class="c1">#fastestroute(start,dataset)</span>

<span class="c1">#print(data)</span>
<span class="c1">#    print(data, dataset[data])</span>
<span class="c1">#print(dataset.values())</span>
<span class="c1">#min(dataset, key=dataset.get)</span>
<span class="c1">#print(dataset.values())</span>
<span class="c1">#print(max(dataset.values()))</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

</div>
 

