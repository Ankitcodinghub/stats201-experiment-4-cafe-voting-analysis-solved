# stats201-experiment-4-cafe-voting-analysis-solved
**TO GET THIS SOLUTION VISIT:** [STATS201 Experiment 4-CAFE Voting Analysis Solved](https://www.ankitcodinghub.com/product/stats201-experiment-4-cafe-voting-analysis-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91875&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STATS201 Experiment 4-CAFE Voting Analysis Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
CAFE Voting Analysis

This question is concerned with a vote on a bill in the US senate on the Corporate Average Fuel Economy (CAFE) standard in 2002. The bill was widely held to be beneficial to automotive manufacturers, as a vote of NO would have forced them to increase fuel economy across their fleets. It is of interest to determine whether a senator’s voting decision was related on their political ideology, and/or the amount of money contributed to them by individuals or political action committees associated with the automotive industry. The variables

are as follows:

<ul>
<li>party: indicating the political party of a senator; either D for Democrat or R for Republican.</li>
<li>contributions: the total lifetime dollar amount contributed to a senator by the automotive industry, rounded to the nearest ten thousand dollars, and given in tens of thousands of dollars (e.g., a value of 2
indicates $20,000 worth of contributions).
</li>
<li>yes: the number of senators who voted YES on the bill for a particular combination of party and
contributions.
</li>
<li>no: the number of senators who voted NO on the bill for a particular combination of party and</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
contributions. The data are as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
party contributions yes no

D0 821 D127 D272 D321 R033 R1 171 R2 131 R3 101

</div>
</div>
<div class="layoutArea">
<div class="column">
We are interested in determining if the amount of contributions from the automotive industry is related to the probability a senator votes YES on the bill. We are also interested to determine if senators from one party are more likely to vote YES on the bill than the other. Also, does the effect of contributions depend on the political party? Conduct a full analysis, and include Methods and Assumption Checks along with an Executive Summary.

In your report, add to the plot code that is provided (to plot contributions vs proportion voting YES) to also show the fit of your chosen model.

Hints

General comments

• Your assignment should be written using R Markdown in RStudio. It should include the code you used and its output, including plots.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>There are many examples of Methods and Assumption Checks and Executive Summaries in your course book. It is a good idea to find a case study with a similar analysis, and use this to guide you, but remember to write things in your own words. Additionally, each data set may have its own specific questions of interest, so do not only base your answers on examples from other case studies.</li>
<li>There are some more specific guidelines for the Methods and Assumption Checks and Executive Summaries below.
Methods and assumption checks

Unless told otherwise, this should include the following:
</li>
</ul>
<ul>
<li>A brief comment on any plots of the data.</li>
<li>A brief description of how you arrived at your final model. For example, if you fitted multiple models, you may comment on what changes you made, and why.</li>
<li>A brief description of any concerns with the model assumptions. If you have no concerns then it is enough to say “All model assumptions appear to be satisfied.”</li>
<li>The model equation, making sure to define all model terms.</li>
<li>Reporting the R-square of the model.
Executive Summary

Unless told otherwise, this should include the following:

<ul>
<li>A brief statement summarising what your analysis was investigating, and the model that was used.</li>
<li>Interpretations of the important findings. For example, was there evidence to suggest that your explanatory variables were related to the response variable? Where appropriate, use confidence intervals to express the magnitude of the relationship.</li>
<li>Answers to any specify research questions.</li>
<li>This should be written without too much technical detail. An intelligent person who is not a statistician should be able to understand what your findings were. Imagine that you are trying to explain the results of your analysis to a friend who is not taking this course.
For the plot
</li>
</ul>
<ul>
<li>Try to predict the probability of voting YES for contributions ranging from 0 to 3. You can create such a vector using seq(0, 3, length.out = 1000).</li>
<li>Use the lines() function to superimpose your lines onto the plot.</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
