Download Link: https://assignmentchef.com/product/solved-cs3431-homework-3-relational-model-algebra
<br>



<strong><u>Problem 1 (Map ERD to Relational Model) </u></strong>

Map the ERD given in Figure 1 (Page 3 in this HW), to the corresponding relational model. The ERD is a representation of a <strong><em>book database</em></strong> that captures the relationships between “books”, “publishers”, and “authors”.

You should follow the refinement rules given in the class while generating the relational model. In the relational model, you should provide:

<ul>

 <li>For a given relation (say R) with attributes A1, A2, …An, represent R as follows:

  <ul>

   <li>R(A1, A2, …, An) and underline the primary key attribute(s)</li>

  </ul></li>

 <li>State the foreign key relationships. If R.A1 references the primary key S.B1, then represent that as follows:

  <ul>

   <li>Foreign key: R.A1 references S.B1</li>

  </ul></li>

 <li><strong><em>In this homework, you are </em></strong><strong><em><u>not</u></em></strong><strong><em> asked to write Create Table statements nor to define data types.</em></strong></li>

</ul>

<strong><u> </u></strong>

<strong><u>RELATIONAL MODEL:</u></strong>




<strong><u>Problem 2 (Relational Algebra) [</u></strong>

Given the relational model that you will build in Problem 1, provide the algebraic expression corresponding to the following queries:




σ, π, g, <strong>d</strong><strong>, </strong>⋈,

Q1: Report the author name who has a phone number “1-555-444-7777”.




Q2: Report the book information for the book with ISBN = 1112223333444.

Q3: Report the names and addresses of the authors and publishers who have contracts between “Jan-01-2007” and “Dec-31-2008” with total payment above $100,000. Also report the contract date.

Q4: Report the publisher name that have published more than 10 books.

Q5: Report the number of pages of textbook “The Country” edition 3.

Q6: Report the contract IDs that have the sum of “partial payments” of the contact lines does not match the “total payment” defined in the contract.

<strong><u>Problem 3 (Relational Algebra) </u></strong>

Referring to the relational model in slide 15 in “ER-mapping” (about author, publisher, shopping-basket, …), provide the algebraic expressing for the following queries.




Q1: Report the book title, and year for the books that have been written by exactly 2 authors, one of them is “Mark Smith”.

First find all ISBNs written by Mark Smith




Next find all ISBNs with exactly 2 Authors




Finally intersect the two and find the associated book title

Q2: For each customer, we need to report the email and the number of books this customer have bought across all shopping baskets.

Q3: Report the unique (distinct) author names who have written books in both 2010 and 2011.

<strong><u>Problem 4 (Relational Algebra) </u></strong>

Assume we have the two relations R and S as shown above. Answer the following questions:

<ol>

 <li>Write the output relation from the following expression (if the relation is empty, then state so):</li>

</ol>




<ol start="2">

 <li>Write the output relation from the following expression (if the relation is empty, then state so):</li>

</ol>




<ol start="3">

 <li>Write the output relation from the following expression (if the relation is empty, then state so):</li>

</ol>




<ol start="4">

 <li>Write the output relation from the following expression (if the relation is empty, then state so):</li>

</ol>

R – S

The two relations aren’t union compatible, the difference operation is hence <strong><u>undefined</u></strong>.







<ol start="5">

 <li>Write the output relation from the following expression (if the relation is empty, then state so):</li>

</ol>




<strong> </strong>

<strong>**Note: In the output relations that you will write, the column names should be included.</strong>




<table width="100%">

 <tbody>

  <tr>

   <td>Figure 1</td>

  </tr>

 </tbody>

</table>

<strong> </strong>