# cmpe321---project-3-solved
**TO GET THIS SOLUTION VISIT:** [CmpE321 – Project 3 Solved](https://www.ankitcodinghub.com/product/cmpe321-project-3-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;76343&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;&nbsp;&nbsp;&nbsp; CmpE321 - Project 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
&nbsp;

&nbsp;

<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Project Description</h1>
In this project, you are supposed to implement a simple song management platform, called <em>DBtify</em>, with a web-based user interface. There will be listeners, songs, albums, and artists in the platform. These entities will have the following properties:

<ul>
<li><strong>Listener: </strong>Username and e-mail. They are both unique which means there exists only one listener with a specific username and e-mail address.</li>
<li><strong>Artist: </strong>Name and surname. They are not necessarily unique independently but you can assume there exists only one artist with a name and surname couple.</li>
<li><strong>Album: </strong>ID, genre, and title. By definition, each ID is unique. Each album must contain at least one song.</li>
<li><strong>Song: </strong>ID and title. By definition, each ID is unique. Each song must reside in only one album. Each song may be produced by one or multiple artists.</li>
</ul>
Two types of people will be using <em>DBtify</em>: Listeners and artists. You do not have to implement an authentication mechanism. You are allowed to provide two options for being a listener or an artist. The person can choose what he/she is and cannot perform other type of person’s operations.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Requirements</h1>
Your UI must support the following operations:

<ul>
<li>Artists shall be able to add/update/delete albums.</li>
<li>Artists shall be able to add/update/delete songs in the albums.</li>
<li>Listeners shall be able to separately view all songs, albums, and artists in <em>DBtify</em>.</li>
<li>Listeners shall be able to view all songs and albums of an artist.</li>
<li>Listeners shall be able to view all songs of an album.</li>
<li>Listeners shall be able to like songs and albums.</li>
</ul>
1

<ul>
<li>Listeners shall be able to view other listeners’ liked songs as well as his/her liked songs.</li>
<li>Listeners shall be able to view popular songs (according to number of likes) of an artist.</li>
<li>Listeners shall be able to rank all artists by the total number of likes of their songs.</li>
<li>Listeners shall be able to view songs of a specific genre.</li>
<li>Listeners shall be able to search a keyword and view the songs that contain this keyword in their titles.</li>
<li>Listeners shall be able to view the artists who produced a song together. This must be implemented as a <strong>stored procedure</strong>. Parameters of this procedure are the artist’s name and surname.</li>
<li>The system shall have three <strong>triggers</strong>:
<ol>
<li>When an album is deleted, all the songs in this album must also be deleted.</li>
<li>When a song is deleted, it must be removed from listeners’ likes.</li>
<li>When a listener likes an album, all the songs of this album must also be likedby that listener.</li>
</ol>
</li>
</ul>
<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Notes</h1>
<ul>
<li>The quality of the web interface does not matter. So, you don’t need to style it. The functionality of the system will be evaluated.</li>
<li>The allowed languages are PHP, Java, JavaScript, and Python. You can use a framework, however, you must write the SQL queries and boot the database server yourself. Note that you should set up the database and create the tables on your own. You are not allowed to use any tool that helps with these parts.</li>
<li>You are not expected to deploy your system. So, it is fine for it to work on your local.</li>
<li>There is no restriction for database choice, you can use any <strong>relational </strong></li>
</ul>
Non-relational databases will not be evaluated at all.

<h1>4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Report &amp; Grading</h1>
Submissions will be through Moodle. The submission must include your <strong>code </strong>(∼%80) and <strong>ER diagram(s) </strong>(∼%20) describing your system. Your diagram(s) should follow the conventions described in the course material. Otherwise, you should explain clearly what shape corresponds to which concept. The system will be evaluated during a demo session that will be arranged. Demo day(s) will be announced.

2
