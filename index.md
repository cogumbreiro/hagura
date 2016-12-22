---
layout: post
title:  "Trace inspector"
date:   2016-09-16 23:34:56 +0530
use_cg: true
---

Execution trace:

<figure class="highlight">
<textarea id="trace_in">
2: reg 1 WO
2: reg 3 SW
2: drop
3: signal
3: wait
1: wait
3: signal
1: wait
</textarea>
</figure>

Phaser state:

<figure class="highlight">
<textarea id="state_out">
</textarea>
</figure>

Phase-ordering relation:

<figure class="highlight">
<div id="graph_out" />
</figure>



