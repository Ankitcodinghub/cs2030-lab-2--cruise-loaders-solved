# cs2030-lab-2--cruise-loaders-solved
**TO GET THIS SOLUTION VISIT:** [CS2030 Lab 2- Cruise Loaders Solved](https://www.ankitcodinghub.com/product/cs2030-cruise-loaders-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114509&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2030 Lab 2- Cruise Loaders Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Topic Coverage

Inheritance

Polymorphism

Method overriding

String formatting

Problem Description

Normal Cruise:

Takes 30min for a loader to fully load

Requires only one loader

Big Cruise (with a cruise code that starts with ‘B’):

Takes 60min for loaders to fully load

Requires two loaders

Furthermore, as the Cruise Centre wants to go green, their policy states that every third loader purchased must be a loader made from recycled materials (referred to as a recycled loader), which undergoes maintenance for one hour after each service. The recycled loader is unable to serve a cruise during the maintenance period.

For each cruise, check through the inventory of loaders, starting from the loader first purchased and so on.

The first (or first two) loaders available will be used to serve the cruise.

If there are not enough loaders, purchase a new one(s), and that loader(s) will be used to serve the cruise. Every third loader purchased must be a recycled loader.

Task

The program will output

The number of cruises

The number of big cruises

The number of loaders required

The number of recycled loaders required

Take note of the following assumptions:

Input cruises are presented chronologically by arrival time

There can be up to 30 cruises in one day

There are no duplicate cruises in the input

Although the solution to this problem can be implemented procedurally, you should learnt to model the solution using an object-oriented approach instead.

Level 1

Represent a Cruise

The following is a sample run of the program. User input is underlined.

$ java Main

1

A1234 0

A1234@0000

$ java Main

6

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test.in | diff – test1.out

Make a copy of your Java programs to the level directory by typing the Unix commands

$ jar cvf cruise1.jar *.java

$ mkdir cruise1

$ cp *.java cruise1

$ cp cruise1.jar cruise1

Level 2

Ensure that each line denoting the cruise served is prefixed with four spaces.

In this level, all cruises (even those with codes that begin with ‘B’) will be taken as a normal cruise.

The Cruise Centre’s go-green policy has not been in place as of yet. All loaders purchased are not recycled.

The following is a sample run of the program. User input is underlined.

$ java Main

1

A1234 0

Loader 1 serves:

A1234@0000

Loader 1 serves:

A1111@0900

B1113@0940

B1115@1030

D1115@1130 Loader 2 serves: B1112@0901

C2030@1000

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test.in | diff – test2.out

Make a copy of your Java programs to the level directory by typing the Unix commands

$ jar cvf cruise2.jar *.java

$ mkdir cruise2

$ cp *.java cruise2

$ cp cruise2.jar cruise2

Level 3

Serve Big Cruises

Big cruises require two loaders and 60 minutes to serve.

The following is a sample run of the program. User input is underlined.

$ java Main

1

B1111 0

Loader 1 serves:

B1111@0000 Loader 2 serves:

B1111@0000

Loader 1 serves:

A1111@0900

B1113@0940

D1115@1130 Loader 2 serves:

B1112@0901

B1115@1030 Loader 3 serves:

B1112@0901

B1115@1030 Loader 4 serves:

B1113@0940 Loader 5 serves:

C2030@1000

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test.in | diff – test3.out

Make a copy of your Java programs to the level directory by typing the Unix commands

$ jar cvf cruise3.jar *.java

$ mkdir cruise3

$ cp *.java cruise3

$ cp cruise3.jar cruise3

Level 4

Purchase recycled loaders

Note that every third loader purchased must be recycled, and recycled loaders require 60 minutes of maintenance after each cruise served.

The following is a sample run of the program. User input is underlined.

$ java Main

4

Loader 1 serves:

A1111@1300

C1113@1359 Loader 2 serves:

B1112@1300

B1114@1400 Loader 4 serves:

B1114@1400

Loader 3 (recycled) serves: B1112@1300

Loader 1 serves:

A1111@0900

B1113@0940

D1115@1130 Loader 2 serves:

B1112@0901

B1115@1030 Loader 4 serves:

B1113@0940 Loader 5 serves:

C2030@1000

B1115@1030

Loader 3 (recycled) serves: B1112@0901

Loader 1 serves:

A1234@0000

C1238@0030

X1241@0100

B1242@0200

B1243@0300 Loader 2 serves:

B1235@0001

B1242@0200

B1243@0300 Loader 4 serves:

B1236@0002 Loader 5 serves:

B1236@0002 Loader 7 serves:

B1237@0003 Loader 8 serves:

V1239@0031 Loader 10 serves:

B1240@0032

Loader 3 (recycled) serves:

B1235@0001

Loader 6 (recycled) serves:

B1237@0003

Loader 9 (recycled) serves: B1240@0032

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test.in | diff – test4.out

$ java Main

4

A1111 1300

B1112 1300

C1113 1359

B1114 1400

+==================================+

| Cruise Statistics |

+———————————-+

| Number of normal cruises = 2 |

| Number of big cruises = 2 |

+==================================+

| Equipment statistics |

+———————————-+

| Number of loaders = 3 |

| Number of recycled loaders = 1 |

+==================================+

| Loader 1 serves: |

| A1111@1300 |

| C1113@1359 |

+==================================+

| Loader 2 serves: |

| B1112@1300 |

| B1114@1400 |

+==================================+

| Loader 4 serves: |

| B1114@1400 |

+==================================+

| Loader 3 (recycled) serves: |

| B1112@1300 |

+==================================+

$ java Main

6

A1111 0900

B1112 0901

B1113 0940

C2030 1000

B1115 1030

D1115 1130

+==================================+

| Cruise Statistics |

+———————————-+

| Number of normal cruises = 3 |

| Number of big cruises = 3 |

+==================================+

| Equipment statistics |

+———————————-+

| Number of loaders = 4 |

| Number of recycled loaders = 1 |

+==================================+

| Loader 1 serves: |

| A1111@0900 |

| B1113@0940 |

| D1115@1130 |

+==================================+

| Loader 2 serves: |

| B1112@0901 |

| B1115@1030 |

+==================================+

| Loader 4 serves: |

| B1113@0940 |

+==================================+

| Loader 5 serves: |

| C2030@1000 |

| B1115@1030 |

+==================================+

| Loader 3 (recycled) serves: |

| B1112@0901 |

+==================================+

Make a copy of your Java programs to the level directory by typing the Unix commands

$ jar cvf cruise5.jar *.java

$ mkdir cruise5

$ cp *.java cruise5

$ cp cruise5.jar cruise5
