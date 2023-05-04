Download Link: https://assignmentchef.com/product/solved-cs6313-mini-project-5
<br>
<ol>

 <li>Consider the data stored in bodytemp-heartrate.csv on eLearning, containing measurements of body temperature and heart rate for 65 male (gender = 1) and 65 female (gender = 2) subjects.

  <ul>

   <li>Do males and females differ in mean body temperature? Answer this questionby performing an appropriate analysis of the data, including an exploratory analysis.</li>

   <li>Do males and females differ in mean heart rate? Answer this question by performing an appropriate analysis of the data, including an exploratory analysis.</li>

   <li>Is there a linear relationship between body temperature and heart rate? Doesthis relationship depend on gender? Answer these questions by performing an appropriate analysis of the data, including an exploratory analysis.</li>

  </ul></li>

</ol>

<ol start="2">

 <li>The goal of this exercise to see how large <em>n </em>should be for the large-sample and the (<strong>parametric</strong>) bootstrap percentile method confidence intervals for the mean of an exponential population to be accurate. To be specific, let <em>X</em><sub>1</sub><em>,…,X<sub>n </sub></em>represent a random sample from an exponential (<em>λ</em>) distribution. Note that this distribution is skewed and its mean is <em>µ </em>= 1<em>/λ</em>. We can construct two confidence intervals for <em>µ </em>— one the large-sample <em>z</em>-interval (interval 1) and the other a (<strong>parametric</strong>) bootstrap percentile method interval (interval 2). We would like to investigate their accuracy, i.e., how close their estimated coverage probabilities are to the assumed nominal level of confidence, for various combinations of (<em>n,λ</em>). This investigation will focus on 1 − <em>α </em>= 0<em>.</em>95, <em>λ </em>= 0<em>.</em>01<em>,</em>0<em>.</em>1<em>,</em>1<em>,</em>10 and <em>n </em>= 5<em>,</em>10<em>,</em>30<em>,</em> Thus, we have a total of 4 ∗ 4 = 16 combinations of (<em>n,λ</em>) to investigate.

  <ul>

   <li>For a given setting, compute Monte Carlo estimates of coverage probabilities ofthe two intervals by simulating appropriate data, using them to construct the two confidence intervals, and repeating the process 5000 times.</li>

   <li>Repeat (a) for the remaining combinations of (<em>n,λ</em>). Present an appropriate summary of the results.</li>

   <li>Interpret all the results. Be sure to answer the following questions: In case ofthe large-sample interval, how large <em>n </em>is needed for the interval to be accurate? Likewise, in case of the bootstrap interval, how large <em>n </em>is needed for the interval to be accurate? Do these answers depend on <em>λ</em>? Can we say that one method is more accurate than the other? Which interval would you recommend? Provide justification for all your conclusions.</li>

   <li>Do your conclusions in (c) depend on the specific values of <em>λ </em>that were fixed in advance? Explain.</li>

  </ul></li>

</ol>