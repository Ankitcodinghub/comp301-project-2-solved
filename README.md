# comp301-project-2-solved
**TO GET THIS SOLUTION VISIT:** [Comp301 Project 2 Solved](https://www.ankitcodinghub.com/product/comp301-project-2-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117868&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp301 Project 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
There is a single code boilerplates provided to you: Project2MYLET. Submit a report containing your answers to the written questions in PDF format and Racket files for the coding questions to Blackboard as a zip. Include a brief explanation of your team’s workload breakdown in the pdf file. Name your submission files as:

p2_member1IDno_member1username_member2IDno_member2username.zip Example: p2_0011221_baristopal20_0011222_akutuk21.zip

Table 1. Grade Breakdown for Project 2

Question Grade Possible

Part A 15

Part B 10

Part C 5

Part D 70

Total 100

Program ::= Expression

a-program (exp1)

Expression ::= Number

const-exp (num)

Expression ::= (Number / Number)

rational-exp (num1, num2)

Expression ::= op(Expression, Expression, Number) op-exp (exp1, exp2, num)

Expression ::= create-new-list ()

list-exp (lst)

Expression ::= cons Expression to Expression

cons-exp (exp1 lst)

Expression ::= sum (Expression)

sum-exp (lst)

Expression ::= zero? (Expression)

zero?-exp (exp1)

Expression ::= if Expression then Expression {elif Expression then Expression}* else Expression

if-exp (exp1 exp2 conds exps exp3)

Expression ::= Identifier

var-exp (var)

Expression ::= let Identifier = Expression in Expression

let-exp (var exp1 body)

Figure 1. Syntax for the MYLET language

Part A (15 pts). This part will prepare you for the following parts of the project.

(1) Write the 5 components of the language :

(2) For each component, specify where or which racket file (if it applies) we define and handle them.

Part B (10 pts). In this part, you will create an initial environment for programs to run.

(1) Create an initial environment that contains 3 different variables (x, y, and z).

(2) Using the environment abbreviation shown in the lectures, write how the environment changes at each variable addition.

Part C (5 pts). Specify expressed and denoted values for MYLET language.

Part D (70 pts). This is the main part of the project where you implement the MYLET language given in Figure 1 by adding the missing expressions.

(1) (10 pts) Add list-exp to the language. list-exp should take no arguments and should

return an empty list.

bers. const-exp should take a list and a number to add to the list.

(3) (15 pts) Add sum-exp to the language. sum-exp should take a list and sum all its ele-

ments. An empty list is assumed to have a sum of 0.

(4) (10 pts) Add rational-exp to the language. In this design, rational numbers are kept as

“list”.

(5) (15 pts) Support additional operations in op-exp. op-exp is similar to the diff-exp of the

LET language; however, in LET language, the only possible operation was subtraction. op-exp enables you to do 5 arithmetic operations via its third input (Number), when third input is:

• 1: perform addition (exp1 + exp2)

• 2: perform multiplication (exp1 * exp2)

• 3: perform division (exp1 / exp2)

• any other number: perform subtraction (exp1 – exp2)

All of these operations should support both integers and rational numbers. In the given code, we have provided the implementations for addition and multiplication, and your task is to implement the rest. For all operations except the simplification operation, you are not expected to simplify the resulting rational number (e.g., 5/3 + 9/6 will output 57/18, not 19/6).

(6) (10 pts) Support the rational simplification operation simpl-exp. simpl-exp takes either

a number or a rational and simplifies it. In the case of rationals, this is done by dividing both the numerator and the denominator by the greatest common divisor. This is trivial for numbers.

Note 1: We provided several test cases for you to try your implementation. Uncomment corresponding test cases and run tests.rkt to test your implementation.

Bonus. Find the GCD of the numerator and denominator in O(log(n)).

Note 3: The bonus question is worth 0.5 points in your overall final grade and no partial credits will be awarded. To get full credit, please implement the algorithm in your simpl-exp implementation
