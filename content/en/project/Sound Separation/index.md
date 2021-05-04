---
title: Sound Separation
summary: Sound Separation with the independent component analysis.
tags:
- ICA
- sound separation
- signal processing
date: "2001-09-30"

draft: false

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
links:

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Some Trials of Blind Source Separation

We show some results of our experiments on Blind Source Separation. In every experiment, the number of the inputs and the outputs is 2. The following files are all stereo sound files. Left channel and right channel correspond to the inputs to the microphne 1 and microphne 2, respectively. Links to our <a href="research/ica_matlab.tgz">matlab codes</a> and <a href="research/ica_C.tgz">C codes</a> (last updated in 1998).

<p class=" c-body">&nbsp;<br>I. <a href="#trial1" class=" js-link_scroller">Signals Mixed on Computer</a><br>II. <a href="#trial2" class=" js-link_scroller">Signals from Dr. Te-Won Lee's Home Page</a><br>III. <a href="#trial3" class=" js-link_scroller">Signals from Mr. Paris Smaragdis' Home Page</a><br>IV. <a href="#trial4" class=" js-link_scroller">Signals from Prof. Kota Takahashi</a><br>V. <a href="#trial5" class=" js-link_scroller">Signals from Dr. Mark Girolami</a><br>VI. <a href="#trial6" class=" js-link_scroller">Online Learning Algorithm</a></p>
<h3 class=" c-large_headline">I. Signals Mixed on Computer<a name="trial1">&nbsp;</a></h3>
<p class=" c-body">These examples are artificially mixed on DEC Alpha station 200 after recording each source signal separately. For the detail, please go to the <a href="research/sounds/simulation.html" target="_blank">description page</a>.</p>
<h4 class=" c-small_headline">1. Instantaneous mixtures</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/LINEAR/X_linear.wav" target="_blank">Mixed Sounds</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/LINEAR/Y1_linear.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/LINEAR/Y2_linear.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">2. Convolutive mixtures I</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/CONV/X_conv.wav" target="_blank">Mixed Sounds</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/CONV/Y1_conv.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/CONV/Y2_conv.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">3. Convolutive mixtures II (in a virtual room)</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/ROOM/X_room.wav" target="_blank">Mixed Sounds</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/ROOM/Y1_room.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/ROOM/Y2_room.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h3 class=" c-large_headline">II. Signals from Dr. Te-Won Lee's Home Page<a name="trial2">&nbsp;</a></h3>
<p class=" c-body">These examples are taken from <a href="http://cnl.salk.edu/~tewon/Blind/blind_audio.html" target="_blank">Dr. Te-Won Lee's Home page</a> at the Salk Institute.</p>
<h4 class=" c-small_headline">1. Speech - Music Separation</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/RSM/X_rsm2.wav" target="_blank">Recorded Sound</a>&nbsp;(stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/RSM/Y1_rsm2.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/RSM/Y2_rsm2.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">2. Speech - Speech Separation</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/RSS/X_rss.wav" target="_blank">Recorded Sounds</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/RSS/Y1_rss.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/RSS/Y2_rss.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">3. Speech - Speech Separation in difficult environments</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/CPE/X_cpe.wav" target="_blank">Recorded Sounds</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/CPE/Y1_cpe.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/CPE/Y2_cpe.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h3 class=" c-large_headline">III. Signals from Mr. Paris Smaragdis' Home Page<a name="trial3">&nbsp;</a></h3>
<p class=" c-body">This example is taken from <a href="http://paris.cs.illinois.edu/" target="_blank">Dr. Paris Smaragdis' Home Page</a> in 90's.</p>
<ul class="c-list-sign">
<li>Input Sounds</li>
<ul class="c-list-sign">
<li><a href="research/sounds/PARIS/paris_in1.wav" target="_blank">Microphone 1</a> (monoral)</li>
<li><a href="research/sounds/PARIS/paris_in2.wav" target="_blank">Microphone 2</a> (monoral)</li>
</ul>
</ul>
<p class=" c-body">Sampling Rate was modified for our experiment (<a href="research/sounds/PARIS/X_paris.wav" target="_blank">Input stereo sound</a>). We need the data to be sampled with 16 kHz. This is because of the practical reason of the calculation. We are using MATLAB, and restricted amount of memory. So, we changed the sampling rate from 44.1 kHz to 16 kHz with free software "sox".</p>
<ul class="c-list-sign">
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/PARIS/Y1_paris.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/PARIS/Y2_paris.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h3 class=" c-large_headline">IV. Signals from Prof. Kota Takahashi<a name="trial4">&nbsp;</a></h3>
<p class=" c-body">These data were given by Prof. Kota Takahashi in the University of Electro-Communication.</p>
<h4 class=" c-small_headline">1. Speech - Speech Separation in difficult environments</h4>
<p class=" c-body">These data were recorded in a real environment.</p>
<ul class="c-list-sign">
<li><a href="research/sounds/UEC1/X_uec1.wav" target="_blank">Input sound</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/UEC1/Y1_uec1.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/UEC1/Y2_uec1.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">2. Speech - Speech Separation in difficult environments</h4>
<p class=" c-body">This data were also recorded in the same lab. But they include more reflections.</p>
<ul class="c-list-sign">
<li><a href="research/sounds/UEC2/X_uec2.wav" target="_blank">Input sound</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/UEC2/Y1_uec2.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/UEC2/Y2_uec2.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h3 class=" c-large_headline">V. Signals from Dr. Mark Girolami<a name="trial5">&nbsp;</a></h3>
<p class=" c-body">Dr. Mark Girolami gave me some data, and I used them for experiments.</p>
<h4 class=" c-small_headline">1. Speech - Speech</h4>
<p class=" c-body">These data were recorded in a real environment.</p>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/X_dr_ml.wav" target="_blank">Input sound</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/Y1_dr_ml.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/MARK/Y2_dr_ml.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">2. Speech - Noise (Gaussian)</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/X_dr_gl.wav" target="_blank">Input sound</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/Y1_dr_gl.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/MARK/Y2_dr_gl.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">3. Speech - Noise (Laplace)</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/X_dr_ll.wav" target="_blank">Input sound</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/Y1_dr_ll.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/MARK/Y2_dr_ll.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">4. Speech - Noise (Gaussian)</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/X_mr_gl.wav" target="_blank">Input sound</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/Y1_mr_gl.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/MARK/Y2_mr_gl.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h4 class=" c-small_headline">5. Speech - Noise (Laplace)</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/X_mr_ll.wav" target="_blank">Input sound</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/MARK/Y1_mr_ll.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/MARK/Y2_mr_ll.wav" target="_blank">Separated Source 2</a> (stereo)</li>
</ul>
</ul>
<h3 class=" c-large_headline">VI. Online Learning Algorithm<a name="trial6">&nbsp;</a></h3>
<p class=" c-body">These examples are artificially mixed on DEC Alpha station 200 after recording each source signal separately.</p>
<h4 class=" c-small_headline">1. Online Learning</h4>
<ul class="c-list-sign">
<li><a href="research/sounds/ONLINE/X_online.wav" target="_blank">Mixed Sounds</a> (stereo)</li>
<li>Our Results</li>
<ul class="c-list-sign">
<li><a href="research/sounds/ONLINE/Y1_online.wav" target="_blank">Separated Source 1</a> (stereo)</li>
<li><a href="research/sounds/ONLINE/Y2_online.wav" target="_blank">Separated Source 2</a> (stereo)</li>
