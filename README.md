# Supply Chain Analytics Workflow using Alteryx

This is a Supply Chain Management challenge.
<br>
<br>
<p>
We have two inputs. 
<ul>
<li>
The Historical Data File contains information on a Supplier name, Annual Purchasing Value (APV) and Part Number (PN).</li>
<li>Our second input, the New Demand File, contains data on the forecasted APV for the PNs that will be demanded.</li>
</ul>
</p>
<br>
<br>
I have generated the Negotiation file for Category Managers to be used while negotiating new prices with the Suppliers. 
<br>
I have matched each PN with prior Supplier Names and APV. In order not to duplicate records while joining data, we want to have one column that indicates a case where there was more than one Supplier in the historical data.

