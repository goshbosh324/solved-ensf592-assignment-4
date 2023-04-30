Download Link: https://assignmentchef.com/product/solved-ensf592-assignment-4
<br>
5/5 - (1 vote)

<header></header>



 <main></main>



<h2 id="learningoutcomes">&#x1f4da; Learning Outcomes</h2>

<ul>

 <li>Create multi-dimensional arrays using NumPy</li>

 <li>Validate user input through exception handling</li>

 <li>Use dictionaries to store and search for values</li>

 <li>Process data according to specifications</li>

 <li>Manipulate NumPy arrays</li>

 <li>Determine and execute NumPy array computations</li>

</ul>

<h2 id="programspecifications">&#x1f4bb; Program Specifications</h2>

The City of Calgary publishes data on various demographics, include school enrollment. You are being asked to design a terminal-based application for computing and printing statistics based on given input. Your application must meet the following design specifications:

<ul>

 <li>Your final output should match the given examples (see attached screenshots)</li>

 <li>Stage 1: Array Creation</li>

</ul>

<ol>

 <li>Create a 3-dimensional array using the provided high school enrollment data. You must use a NumPy array.</li>

 <li>Print the shape and dimensions of the array.</li>

</ol>

<ul>

 <li>Stage 2: School Stats</li>

</ul>

<ol>

 <li>Prompt the user to enter either the name or numerical code of a school. If the name or code do not exist within the given data, raise a ValueError to print “You must enter a valid school name or code.”</li>

 <li>Calculate and print the answers for the following school-specific statistics, using the given output as a template.

  <ul>

   <li>The school name and school code</li>

   <li>Mean enrollment for Grade 10 across all years</li>

   <li>Mean enrollment for Grade 11 across all years</li>

   <li>Mean enrollment for Grade 12 across all years</li>

   <li>Highest enrollment for a single grade within the entire time period</li>

   <li>Lowest enrollment for a single grade within the entire time period</li>

   <li>Total enrollment for each year from 2013 to 2020</li>

   <li>Education planners want to better understand the impact of large-scale classes in high schools. Determine if any enrollment numbers were over 500. If not, print “No enrollments over 500.” If yes, print the median value of the &gt;500 enrollments.</li>

  </ul></li>

</ol>

<ul>

 <li>Stage 3: General Stats</li>

</ul>

<ol>

 <li>Every run of your program should also calculate and print the answers for the following general statistics. These will be the same for every run.

  <ul>

   <li>The mean enrollment in 2013</li>

   <li>The mean enrollment in 2020</li>

   <li>Total graduating class of 2020 across all schools</li>

   <li>Highest enrollment for a single grade within the entire time period (across all schools)</li>

   <li>Lowest enrollment for a single grade within the entire time period (across all schools)</li>

  </ul></li>

</ol>

<ul>

 <li>Your code should include and use at least one 3-dimensional NumPy array, at least one subarray view, at least four different NumPy computational functions, at least one masking operation, and at least one dictionary.</li>

 <li>Your code must follow the conventions discussed so far in the course (names<em>with</em>underscores, ClassNames, four spaces for indentations, spaces between variables/operators, comments throughout, etc.)</li>

 <li>All classes, methods, and functions must contain docstring documentation.

  <ol>

   <li>For each class, include a functionality summary and describe any class and/or instance variables (do not include a separate docstring for __init__)</li>

   <li>For each method/function, include a functionality summary and describe parameters and return values (or specify if there are none)</li>

   <li>Main functions do not need a docstring but should be well-commented</li>

  </ol></li>

 <li>Your code will be run by the TAs as your end user.</li>

 <li>FAQs about the assignment will be answered on the D2L discussion boards. Please check the boards for any clarifications before submitting.</li>

 <li>The grading rubric will be posted to D2L.</li>

</ul>

<h2 id="assignmenttasks">&#x1f4dd; Assignment Tasks</h2>

<ul>

 <li>Make sure to watch video lessons 15 – 17, labs 6 and 7, and review the corresponding Jupyter Notebooks.</li>

 <li>Clone this repository to your local computer.</li>

 <li>Open VSCode and start a new terminal. Make sure that your <code>ensf592</code> environment is activated.</li>

 <li><code>school_data.py</code> is provided as a starting point. Fill in the header with your own information.</li>

 <li>Remember to test your program execution via the terminal: <code>python school_data.py</code></li>

 <li>Take a screenshot of your successful program run and upload it to your assignment repository.</li>

 <li>Commit your screenshot and code.</li>

 <li>Push your local git history to github: <code>git push origin main</code></li>

 <li>Submit your repository HTTPS link to the Assignment 3 D2L dropbox.</li>

 <li>Tip: If you want to learn more about a specific aspect of a Python object or the functionality of NumPy, remember to take a look at the official documentation!</li>