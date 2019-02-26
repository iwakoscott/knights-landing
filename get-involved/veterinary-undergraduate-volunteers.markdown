---
title: Veterinary Undergraduate Volunteers
date: 2019-02-26 09:33:00 -08:00
position: 1
addToNavBar: true
volunteer:
  requirements:
  - Registered UC Davis undergraduate student.
  - 'Minimum 3 quarter (1 year) requirement. '
  - Maintain a 3.0 GPA or higher.
  - 1-2 unit quarterly clinic class (P/NP grading) on Monday nights from 6:00-7:00
    PM.
  - Attendance of a minimum of 2/3 clinic dates (Knights Landing OR Mercer) per quarter.
  - Rabies vaccination required to handle animals at clinic (Not required to volunteer.)
  - Minimum of 5 hours of service hours outside of clinic.
  questions: "Questions? \nPlease email klohcundergrad.edu@gmail.com with the subject
    line \"QUESTION\"."
info sessions:
- Wednesday, March 6th 2019 at 8:10pm in Wellman 229.
- Thursday, April 4th 2019 at 8:10pm in Wellman 233.
- Wednesday, April 10th 2019 at 8:10pm in Wellman 233.
application_info: The 2018 application will open on March 19th and close April 7th
  at 11:59pm. [Click here to apply](https://goo.gl/forms/qPuW5IaFDoG7fCsn2) during
  those dates and times to go to the application form. [Check out our website [here](https://www2.vetmed.ucdavis.edu/onehealth/students/knights_landing/index.cfm
  )]
layout: volunteer
---

<div class="card">
      <div class="card-header">
        <h2 class="card-title">Minimum Volunteer Requirements</h2>
      </div>
      <div class="card-body">
          <ol>
            {% for requirement in page.volunteer.requirements %}
              <li>
                <strong>{{ requirement }}</strong>
              </li>
            {% endfor %}
          </ol>
          <h5 class="text-center">{{ page.volunteer.questions }}</h5>
          <p>**Note: Your GPA does not have to be a 3.0 at the time of applying - we just ask that you maintain a 3.0 quarterly GPA as a volunteer to ensure that you can balance clinic with your academics. </p>
      </div>
    </div>

{% if page['info sessions'] %}
<div class="card">
    <div class="card-header">
      <h2 class="card-title">Upcoming Info Sessions</h2>
    </div>
    <div class="card-body text-center">
        <ul class="list-group list-group-flush">
          {% for session in page['info sessions'] %}
            <li class="list-group-item text-center">
              <strong>{{ session }}</strong>
            </li>
          {% endfor %}
        </ul>
    </div>
</div>
{% endif %}

<div>
  <div class="col-sm-6 offset-sm-3">
     <div class="alert alert-info" role="alert">
        {{ page.application_info | markdownify }}
      </div>
   </div>
</div>