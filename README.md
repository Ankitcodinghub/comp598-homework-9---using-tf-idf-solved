# comp598-homework-9---using-tf-idf-solved
**TO GET THIS SOLUTION VISIT:** [COMP598 Homework 9 – Using TF-IDF Solved](https://www.ankitcodinghub.com/product/comp-598-homework-9-using-tf-idf-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118620&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP598 Homework 9 – Using TF-IDF Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Non-standard (i.e., built-in) python libraries you can use:

– pandas

– requests

In this assignment, we’re going back to homework 3 and computing the each pony’s most frequent words using TF-IDF. Note that, throughout this assignment, we refer to “pony names” – use the canonical names we used for each of the main character ponies in HW3.

Task 1: Compute word counts (15 pts)

Write a script that computed word counts for each pony from all episodes of MLP. Your script, compile_word_counts.py should run as follows:

python compile_word_counts.py -o &lt;word_counts_json&gt; &lt;clean_dialog.csv file&gt;

The output file should be a dictionary with the following form:

{

“&lt;pony-name&gt;”: {

“&lt;word&gt;”: &lt;# of times it appears&gt;, “&lt;word&gt;”: &lt;# of times it appears&gt;,

…

},

“&lt;pony-name&gt;”: {

…

}

}

Note that in the output file you should ONLY have word counts for words that are spoken by the pony at least five times. Toss out any words that happen less than this many times (this is a common technique to avoid storing information on a crazy number of words).

Other details:

– Only consider speech acts involving one of the main character ponies. Ignore any others.

– Treat each word encountered as case insensitive. Store words in all lowercase form.

– Before processing text, replace punctuation characters with a space – a punctuation character is one of

these: ( ) [ ] , – . ? ! : ; # &amp;

– A word must only include alpha-only characters. All other words should be ignored.

– Tip: to keep your script performant, store your word counts in dictionaries.

Task 2: Compute most frequent &amp; distinctive pony language (15 pts) Write the script compute_pony_lang.py which is run as follows:

python compute_pony_lang.py &lt;pony_counts.json&gt; &lt;num_words&gt;

Output should be written in JSON format to stdout with the following structure:

{

“&lt;pony name&gt;”: [ “highest-tfidf-word”, “second-highest-tfidf-word”, … ],

“&lt;pony name&gt;”: …

}

Each pony word list should have &lt;num_words&gt; entries.

Submission Instructions

Your MyCourses submission must be a single zip file entiled HW9_&lt;studentid&gt;.zip. It should contain the following items:

– scripts/ o compile_word_counts.py – script for Task 1 o compute_pony_lang.py – script for Task 2
