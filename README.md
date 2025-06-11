# comp9021-coding-quiz-3-solved
**TO GET THIS SOLUTION VISIT:** [COMP9021 Coding Quiz 3 Solved](https://mantutor.com/product/comp9021-solved-2/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114849&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9021 Coding Quiz 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Coding Quiz 3

Description

You are provided with a stub in which you need to insert your code where indicated without doing any changes to the existing code to complete the task.

The current code prompts the user for an arity (a natural number) n and a word. Your task is to complete the function is_valid(word, arity) that checks if the provided word with the given arity will return either True if the word is valid or False if the word is invalid based on the constraints below.

Let’s call a symbol a word consisting of nothing but alphabetic characters and underscores.

The function checks if the word is valid given an arity n, that is, it satisfies the following inductive definition:

• a symbol, with spaces allowed at both ends, is a valid word.

• a word of the form s(w1, …, wn) with s denoting a symbol and w1, …, wn denoting valid words, with spaces allowed at both ends and around parentheses and commas, is a valid word.

See the test cases below for more details.

Make sure not to change the filename quiz_3.py while submitting by clicking on [Mark] button in Ed. It is your responsibility to check that your submission did go through properly using Submissions link in Ed otherwise your mark will be zero for Quiz 3.

Test Cases

$ python3 quiz_3.py

Input an arity : 0

Input a word: f_1

The word is invalid.

$ python3 quiz_3.py

Input an arity : 0

Input a word: ()

The word is invalid.

$ python3 quiz_3.py

Input an arity : 0

Input a word: function_of_arity_one(hello) The word is invalid.

$ python3 quiz_3.py

Input an arity : 1

Input a word: f)

The word is invalid.

$ python3 quiz_3.py

Input an arity : 1

Input a word: f[a]

The word is invalid.

$ python3 quiz_3.py

Input an arity : 2

Input a word: f(a, g(b)) The word is invalid.

$ python3 quiz_3.py

Input an arity : 3

Input a word: constant The word is invalid.

$ python3 quiz_3.py

Input an arity : 3

Input a word: f((a,b,c)) The word is invalid.

$ python3 quiz_3.py

Input an arity : 3

Input a word: f(g(a,a), f(a,b)) The word is invalid.

$ python3 quiz_3.py

Input an arity : 3

Input a word: f(g(a,b,c),g(a,b,c),g(a,b,c) The word is invalid.

$ python3 quiz_3.py

Input an arity : 3

Input a word: f(a, g(a, b, f(a,b,c)), b, c) The word is invalid.

$ python3 quiz_3.py

Input an arity : 0

Input a word: a

The word is valid.

$ python3 quiz_3.py

Input an arity : 1

Input a word: function_of_arity_one(hello) The word is valid.

$ python3 quiz_3.py

Input an arity : 2

Input a word: F(g(a,a), f(a,b)) The word is valid.

$ python3 quiz_3.py

Input an arity : 3

Input a word: ff(ff(ff(a,b,ff(aa,bb,cc)) , b , ff(a,b,c)) , b , ff(a,ff(a,b,c),c)) The word is valid.

$ python3 quiz_3.py

Input an arity : 4

Input a word: f(a, FF(a, b, fff(a, b, c, FfFf(a,b,c,d)), FfFf(a,b,c,d)), c, d) The word is valid.

Some More Test Cases

Input an arity : 0

Input a word: f() The word is invalid.

Input an arity : 1

Input a word: f() The word is invalid.

Input an arity : 0

Input a word: f The word is valid.

Input an arity : 1

Input a word: f(x) The word is valid.

Input an arity : 0

Input a word: _

The word is valid

Input an arity : 2

Input a word: f ( a , _ ) The word is valid.

Input an arity : 2

Input a word: f ( f , ) The word is invalid.

Input an arity : 2

Input a word: f ( f , a ) The word is valid.

Input an arity : 1

Input a word: f (f) The word is valid.

Input an arity : 0

Input a word: f. f The word is invalid.
