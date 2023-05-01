Download Link: https://assignmentchef.com/product/solved-buzz-advertising
<br>
Figure 1

<strong><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/03/863.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/03/863.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></strong>

<strong>Instructions</strong>

<strong> </strong>In this case, you will create a Visual Basic solution that simulates a program running on a kiosk. This program allows Buzz Advertising to generate ad sales for its weekly shopping deals booklet in a local flea market. Merchants can book their own ads by using this program. This program uses objects created from classes. Use the accompanying graphic file and the instructions below.




<strong>Requirements:</strong>

Ad price is based on the size of the ad and the location in the shopping deals booklet.  Table 1 shows the ad sizes and the price relationship of each size to the base price.  Table 2 shows the location markup that must be applied to the calculated price to determine the final price.  Prices are calculated as follows:

&lt;price determined by size&gt; * &lt;markup&gt; = &lt;final price&gt;




The base price of an ad is $225.00.




<strong>Restrictions</strong>:

<ol>

 <li>Business card size ads may only be placed on interior pages.  Do not allow the user to selection any location when interior page location is selected.</li>

 <li>The outside back cover is reserved for a full page ad.  Do not allow the user to select outside back cover unless full page has already been selected.</li>

</ol>




<strong></strong>

<table>

 <tbody>

  <tr>

   <td><strong>Size</strong></td>

   <td><strong>Price</strong></td>

  </tr>

  <tr>

   <td>Full page</td>

   <td>100% of base price</td>

  </tr>

  <tr>

   <td>Half page</td>

   <td>65% of base price</td>

  </tr>

  <tr>

   <td>Quarter page</td>

   <td>40% of base price</td>

  </tr>

  <tr>

   <td>Business card</td>

   <td>$35.00</td>

  </tr>

 </tbody>

</table>

<strong>Table 1 – Price by Size</strong>




<table>

 <tbody>

  <tr>

   <td><strong>Location</strong></td>

   <td><strong>Markup</strong></td>

  </tr>

  <tr>

   <td>Interior page</td>

   <td>1.00</td>

  </tr>

  <tr>

   <td>Inside front cover</td>

   <td>1.20</td>

  </tr>

  <tr>

   <td>Inside back cover</td>

   <td>1.15</td>

  </tr>

  <tr>

   <td>Outside back cover</td>

   <td>1.40</td>

  </tr>

 </tbody>

</table>

<strong>Table 2 – Markup by Location</strong>

<strong></strong>

<strong>Step 1: Create the Project:</strong>

Create a Visual Basic Project using the project name “BuzzAdvertising”.




<strong>Step 2 – Design the Form:</strong>

Design the form as shown in Figure 1.  You will need three button controls, eight radio buttons, two group boxes, seven labels, and one picture box. Load the downloaded bee.jpg image into the picture box. Remove the control box because this program will run in a kiosk.







<strong>Step 3 – Create the Ad class</strong>

Add a Class file named Ad to the project.  The Ad class should have the following properties:  company, telephone, run date, size, location, and price. Create a method in the Ad class that calculates the final price of an ad.




<strong>Step 4 – Write code in the main form:</strong>

Set the size and location based on the radio button selections. Create a new Ad object, passing in the required data values to the constructor.  After the Ad object has been created, call the Ad object’s calculate method to obtain the final price.  Display the final price with appropriate formatting.

<strong> </strong>

<strong>Step 7 – Finish up:</strong>

Be sure to add the code for the Clear and Exit buttons.




<strong>Step 8:  Save and run</strong>

Save all files, then start the application. Figures 2 and 3 show sample runs of this program demonstrating the restrictions.




Figure 2

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/03/926.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/03/926.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

Figure 3

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/03/432.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/03/432.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>