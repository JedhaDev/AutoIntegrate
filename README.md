<h2>Simple automated job approval system.</h2>
<pre>


Generate a random job sheet and a total price for the work. This job sheet should then be submitted, assessed and a decision returned.

Business Rules:
If any of these rules are broken, then automatically decline the job sheet:
   • Tyres must be changed in pairs, and a job sheet can include a maximum of 4.
   • Brake pads and discs must be changed at the same time.
   • A job sheet can only a include a maximum of 1 exhaust.
   • The total hours labour must not exceed the reference number of hours labour.

Overall Decision:
   • Approve - If the total price is within 10% of the reference price.
   • Refer - If the total price is between 10% and 15% of the reference price.
   • Decline - If the total price exceeds 15% of the reference price.


Reference Data:
Item                           Unit Time (Mins)             Unit Cost (£)
Tyre                                 30                       200
Brake Discs                          90                       100
Brake Pads                           60                        50
Oil                                  30                        20
Exhaust                             240                       175

NB. Labor is charged at £45 per hour.

</pre>

