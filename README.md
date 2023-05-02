Download Link: https://assignmentchef.com/product/solved-cis560-homework-5
<br>
<strong>Part 1</strong>

<strong>For the first three questions, use the below relation and known functional dependencies. </strong><strong><u>Relation </u></strong>

<em>Route(ArrivalTime, DepartureTime, Location, Bus) </em><strong><u>Functional Dependencies </u></strong>

<em>{DepartureTime, Location} -+ </em><em>{Bus} {ArrivalTime} {DepartureTime} {Bus, ArrivalTime} —&gt; {Location}</em>

<strong>Question 1</strong>

<strong>20 points – Compute the closure of all sets of attributes.</strong>

<strong>Question 2</strong>

<strong>5 points – Using the closures from Question 1, identify the keys for the relation <em>Route. </em>Remember we want minimal keys, not just any superkey.</strong>

<strong>Question 3</strong>

<strong>10 points – Using the closures from Question 1, list all non-trivial functional dependencies for the relation <em>Route.</em></strong>

<strong>Part 2</strong>

<strong>For the below relation and known dependencies to answer Questions 4 and 5.</strong>

<strong><u>Relation </u></strong>

<strong>Shuttle(DepartureTime, Route, Driver, Bus, Capacity)</strong>

<strong><u>Functional Dependencies </u></strong>

<em>{Bus, DepartureTime} {Driver} </em><em>{Bus} -+ {Capacity}</em>

<em>{Route, DepartureTime} -+ {Bus}</em>

<strong>Question 4</strong>

<strong>5 points – </strong><strong>For each of the three provided functional dependencies above, X —&gt; Y, compute X. Once you have the closures computed, identify the key(s) for the relation </strong><em>Shuttle.</em>

<strong>Question 5</strong>

<strong>10 points – </strong><strong>From Question 4, we can see that </strong><strong>Bus —&gt; Capacity </strong><strong>is a violation of Boyce-Codd Normal Form (BCNF). Decompose the relation </strong><em>Shuttle </em><strong>into BCNF relations, starting with this dependency violation.</strong>

<ul>

 <li><strong>Show each iteration in your work, and make clear which relations are your resulting BCNF relations.</strong></li>

 <li><strong>Identify the key in each of the resulting BCNF relations.</strong></li>

</ul>


