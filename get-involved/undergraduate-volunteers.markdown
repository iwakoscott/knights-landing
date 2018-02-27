---
title: Undergraduate Volunteers
date: 2018-02-26 11:14:00 -08:00
position: 0
addToNavBar: true
volunteer:
  requirements:
  - 'Registered UC Davis undergraduate student. '
  - 'Minimum 2 quarter commitment. '
  - 1-2 unit quarterly clinic class (P/NP grading) on Mondays nights from 6:00 PM
    - 7:00 PM.
  - Maintain a 3.0 GPA or higher while volunteering .**
  - Volunteer at clinic a minimum of 2 Sundays per quarter .
  - Immunizations cleared through UC Davis Office of Medical Education (further information
    will be provided upon acceptance.)
  - Minimum of 1 hour of community service, 1 hour of outreach, and 1 social hour.
  questions: |-
    Questions?
    Please email klclinic.ucdsom@gmail.com with the subject line "QUESTION".
info sessions:
- 'March 7th, 2018 from 7:10 PM - 8:00 PM in Wellman 230. '
- March 8th, 2018 from 6:10 PM - 7:00 PM in Giedt 1006.
- 'April 4th, 2018 from 6:10 PM - 7:00 PM in Wellman 119. '
layout: simple
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

<div class="btn-group" role="group" aria-label="button group">
<a class="btn btn-lg btn-success" href="{{site.url}}/get-involved/clinic-volunteer-application.html">
Clinic Volunteers</a>

<a class="btn btn-lg btn-primary" href="{{site.url}}/get-involved/klhep-volunteer-application.html">KLHEP Volunteers</a>
</div>