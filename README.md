Download Link: https://assignmentchef.com/product/solved-cmsc203-assignment-1-wind-chill-temperature-index
<br>
<strong>Wind Chill</strong> is the term used to describe the rate of heat loss on the human body resulting from the combined effect of low temperature and wind.  As winds increase, heat is carried away from the body at a faster rate, driving down both the skin temperature and eventually the internal body temperature.

The first wind chill formulas and tables were developed by <a href="https://en.wikipedia.org/wiki/Paul_Allman_Siple">Paul Allman Siple</a> and <a href="https://en.wikipedia.org/wiki/Charles_F._Passel">Charles F. Passel</a> working in the Antarctic before the <a href="https://en.wikipedia.org/wiki/Second_World_War">Second World War</a> They were based on the cooling rate of a small plastic bottle as its contents turned to ice while suspended in the wind on the expedition hut roof, at the same level as the <a href="https://en.wikipedia.org/wiki/Anemometer">anemometer</a> (pictured above). The so-called Windchill Index provided a pretty good indication of the severity of the weather.

<strong>In late 2001, the National Weather Service implemented a new Wind Chill Temperature (WCT) Index. The reason for the change was to improve upon the old index used by the NWS and the Meteorological Services of Canada (MSC) which was based on the 1945 Siple and Passel Index.</strong>
















Develop a Java application that prompts for and reads two double numeric amounts that represent the Fahrenheit temperature and the wind speed.  The temperature must be between -45 and 40 inclusively. The wind speed must be between 5 and 60 inclusively. Use these two amounts in the formula below to calculate the wind chill temperature in degrees Fahrenheit.

Here is how you calculate the <strong>New Wind Chill Index:</strong>

<strong>          </strong>Wind Chill (<sup>o</sup>F) = 35.74 + 0.6215T – 35.75(V<sup>0.16</sup>) + 0.4275T(V<sup>0.16</sup>), where

V is the Wind Speed in MPH, and

T is the temperature in degrees F.













<ul>

 <li>Creating a class</li>

 <li>Variables</li>

 <li>Strings</li>

 <li>Input/output facilities</li>

 <li>Conditional statements</li>

 <li>Logical operators</li>

 <li>Eclipse IDE</li>

</ul>

<strong> </strong>

<strong> </strong>




Your program must use the single class WindChill with only one static void main method










<ul>

 <li>Use the Scanner class for input, and use System.out.print or System.out.println for output. Please make sure that the Scanner is closed when your project terminates.</li>

 <li>You must use “named constants” for any literal values that will not change during program execution.</li>

 <li>You must use meaningful variable names and good indentation.</li>

 <li>Ask the user for the Fahrenheit temperature and the wind speed.</li>

 <li>Remind the user that temperature values should be greater than or equal to -45, but less than or equal to 40, and the wind speeds should be greater than or equal to 5, but less than or equal to 60, but don’t validate these values in your code.</li>

 <li>Display a header for your application.</li>

 <li>Display the wind chill temperature that results.</li>

 <li>Display your name as programmer at the end.</li>

 <li>Just in case you know what an array is — you may not use arrays (or any Java collections of any kind) while implementing this project.</li>

 <li>Run your application with the command line (javac, java) and with an IDE Integrated Development Environment (Eclipse)</li>

</ul>

<strong> </strong>







Example 1:

Wind Chill Calculator




Please enter the temperature in Fahrenheit (must be &gt;= -45 and &lt;= 40): 30

Please enter the wind speed (must be &gt;= 5 and &lt;= 60): 20




Wind chill temperature: 17.361783756466327 degrees Fahrenheit




Programmer: (insert your name here)




Example 2:

Wind Chill Calculator




Please enter the temperature in Fahrenheit (must be &gt;= -45 and &lt;= 40): -15.5

Please enter the wind speed (must be &gt;= 5 and &lt;= 60): 35.3




Wind chill temperature: -48.842359110042835 degrees Fahrenheit




Programmer: (insert your name here)




Example 3:

Wind Chill Calculator




Please enter the temperature in Fahrenheit (must be &gt;= -45 and &lt;= 40): -9.3

Please enter the wind speed (must be &gt;= 5 and &lt;= 60): 22.8




Wind chill temperature: -35.55509110244696 degrees Fahrenheit




Programmer: (insert your name here)




Example4:

Wind Chill Calculator




Please enter the temperature in Fahrenheit (must be &gt;= -45 and &lt;= 40): 0

Please enter the wind speed (must be &gt;= 5 and &lt;= 60): 22.5




Wind chill temperature: -23.09357636894822 degrees Fahrenheit




Programmer: insert your name here













Design: Submit your initial design (pseudo-code and test cases) in Blackboard.

Implementation: Run the application twice, and turn in screen shots of both runs in Blackboard.

<ul>

 <li>Run it once using command-line Java (javac to compile, and java to run). Your screen shot should show both compilation and execution. If your computer cannot find the javac or java commands, see the lecture slides explaining how to set the path for Java.</li>

 <li>Run it again using an Integrated Development Environment (IDE). I would recommend Eclipse. Provide a screen shot of the console output. See the lecture slides explaining how to download and install Eclipse.</li>

 <li>Turn in your final design (pseudo-code and test cases)</li>

 <li>Turn in the working java file WindChill.java (not the .class file).</li>

 <li>Learning Experience: In 3+ paragraphs, highlight your lessons learned and learning experience from working on this project. What have you learned? What did you struggle with? What will you do differently on your next project?</li>

</ul>

<strong>Submission Detail</strong>

<ul>

 <li>Upload two .zip files for each assignment. The first .zip file will contain <strong>all</strong> the files required for the assignment (final design with pseudocode and table of test cases, screen shot of runs and the .java file, and will be named: LastNameFirstName_AssignmentX.zip.</li>

 <li>The second .zip file will only contain the .java files and will be named: LastNameFirstName_AssignmentX_Moss.zip. <strong>This .zip will not have any folders in it – only .java files.</strong></li>

</ul>

Here’s an example for Assignment 1:

KartchnerJeannette_Assignment1.zip [a compressed file containing the following]

PseudoCode_and_TestTable.docx

Learning_Experience.docx

CmdLine_output.jpg

Eclipse_console_output.jpg

WindChill.java




KartchnerJeannette_Assignment1_Moss.zip [a compressed file containing only the following]

WindChill.java