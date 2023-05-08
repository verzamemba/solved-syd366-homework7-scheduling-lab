Download Link: https://assignmentchef.com/product/solved-syd366-homework7-scheduling-lab
<br>
Scheduling Module

Christy’s finds that she’s driving her truck and trailer more than she should.  She would like a scheduling tool that allows her to see her clients on a map so that she can attend to clients in the same geographical area on the same day.

Christy would like the system to help her add appointments to her calendar.  The appointment must include the customer, the customer’s pets and the services requested.  Ideally, Christy would like to create an invoice from the appointment information.

User Story

As the owner of this business, I would like to record my appointments and be able to see my appointments for a single day on a map.  I would like to be able to create an invoice from an appointment, so I’ll need the same information on the appointment, as an invoice.

Acceptance Criteria:

<ol>

 <li>Must be able to record services for multiple pets belonging to a customer</li>

 <li>Must be able to turn an appointment into an invoice</li>

 <li>Must be able to query calendar by day and see the results on a map.</li>

</ol>







Use Case Descriptions




<table>

 <tbody>

  <tr>

   <td width="124">Use Case Name</td>

   <td colspan="3" width="508">Create Customer Appointment</td>

  </tr>

  <tr>

   <td width="124">Triggering Event</td>

   <td colspan="3" width="508">Customer has requested service</td>

  </tr>

  <tr>

   <td width="124">Brief Description</td>

   <td colspan="3" width="508">Allows the Owner to record a new sales invoice</td>

  </tr>

  <tr>

   <td width="124">Actors</td>

   <td colspan="3" width="508">Owner</td>

  </tr>

  <tr>

   <td width="124">Related Use Cases</td>

   <td colspan="3" width="508"> </td>

  </tr>

  <tr>

   <td width="124">Preconditions</td>

   <td colspan="3" width="508">Owner has opened the Main Menu.</td>

  </tr>

  <tr>

   <td width="124">Post Conditions</td>

   <td colspan="3" width="508">Appointment is created and can now be queried</td>

  </tr>

  <tr>

   <td width="124">Flow of activities</td>

   <td colspan="2" width="267">Actor</td>

   <td width="241">System</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">1.</td>

   <td width="217">Requests to add an appointment</td>

   <td width="241">Displays a list of customers and prompts for selection</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">2.</td>

   <td width="217">Selects a customer</td>

   <td width="241">Prompts for service date</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">3.</td>

   <td width="217">Enters service date</td>

   <td width="241">Displays a list of already scheduled appointments for that day.  Each appointment has a total hours.</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">4.</td>

   <td width="217">Selects a time</td>

   <td width="241">Generates and displays appointment IDDisplays a list of pets and prompts for selection</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">loop</td>

   <td width="217"> </td>

   <td width="241"> </td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">4.</td>

   <td width="217">Selects the pet</td>

   <td width="241">Displays a list of services including service name and price/hour prompting for selection</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">5.</td>

   <td width="217">Selects services that apply</td>

   <td width="241">Adds services to the invoice.Calculates the detail amount (hours * price). Displays the appointment  service details, prompting for changes to  hours and pricePrompts for another petPrompts to save</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">End</td>

   <td width="217">Repeats above 2 steps until all pets have been selected.</td>

   <td width="241">Displays the appointment service details and prompts to save</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="50">6.</td>

   <td width="217">Chooses to save</td>

   <td width="241">Saves the invoice.Return to the main menu</td>

  </tr>

  <tr>

   <td width="124">Exception Conditions</td>

   <td colspan="3" width="508">·         Owner chooses to abort adding the appointment</td>

  </tr>

 </tbody>

</table>

Your tasks:

<ol>

 <li>Create a class diagram to support the above case study and Systems Use Case Specifications</li>

 <li>Create a object level sequence diagram, detailing the Create Appointment use case specification</li>

</ol>