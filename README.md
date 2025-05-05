# java-lab-7-solved
**TO GET THIS SOLUTION VISIT:** [Java Lab 7 Solved](https://www.ankitcodinghub.com/product/java-lab-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95426&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Java Lab 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Concurrency

Write a program that simulates the following positional game between a given number of players (TSP Game).

At the beginning of the game the board contains n tokens, each token containing a distinct pair of numbers between 1 and n, and a specific positive value.

Each player extracts tokens successively from the board and must create with them a a closed sequence, that is t1=(i1,i2), t2=(i2,i3),…,tk=(ik,i1), where ti are tokens.

The value of a sequences may be evaluated in various modes: the sum of the token values, the number of tokens, etc. A special bonus may be given if the length of the sequence is n.

The game ends when all tokens have been removed from the boar d and each player receives a number of points equal to the the value of its largest sequence, or equal to the sum of its sequences, etc.

The players might take turns (or not…) and a time limit might be imposed (or not…). The main specifications of the application are:

Compulsory (1p)

<ul>
<li>Create classes in order to model the problem. You may assume that all possible tokens are initially available, having random values.</li>
<li>Each player will have a name and they must perform in a concurrent manner, extracting repeatedly tokens from the board.</li>
<li>Simulate the game using a thread for each player.

Pay attention to the synchronization of the threads when extracting tokens from the board.

Optional (2p)
</li>
</ul>
<ul>
<li>Implement the scoring and determine who the winner is at the end of the game.</li>
<li>Make sure that players wait their turns, using a wait-notify approach.</li>
<li>Consider the situation when each player might have a different strategy for
extracting a number: automated (random) or manual.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
A manual player will use the keyboard, while the bot will extract a random

token. Simulate bot contests on large graphs.

• Implement a timekeeper thread that runs concurrently with the player threads,

as a daemon. This thread will display the running time of the game and it will stop the game if it exceeds a certain time limit.

Bonus (2p+)

<ul>
<li>Implement a “smart” player. This should try to create valuable sequences, while not allowing others to extend theirs.</li>
<li>Implement various scoring strategies (in a flexible manner), for example the winner could be the one that determines the most valuable hamiltonian circuit.</li>
<li>Create a simple graphical user interface for the game, using JavaFX. References</li>
</ul>
<ul>
<li>Slides</li>
<li>The Java Tutorials: Concurrency</li>
<li>Java Language Specification: Threads and Locks</li>
<li>Java Concurrency / Multithreading Tutorial
Objectives
</li>
</ul>
<ul>
<li>Understand the basic principles of concurrent programming.</li>
<li>Create and run threads using the Thread class and the Runnable interface.</li>
<li>Understand resource contention and thread interference.</li>
<li>Create synchronized methods or statements.</li>
<li>Implement the wait-notify mechanism.</li>
<li>Understand the thread pool and fork/join concepts.</li>
</ul>
</div>
</div>
</div>
