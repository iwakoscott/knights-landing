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
layout: simple
---

<div class="card">
      <div class="card-header">
        <h2 class="card-title">Volunteer Requirements</h2>
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
      </div>
    </div>

<div class="row">

<div class="col-sm-3 offset-sm-3">
<a class="btn btn-lg btn-block btn-success" href="{{site.url}}/get-involved/clinic-volunteer-application.html">
Clinic Volunteers</a>
</div>

<div class="col-sm-3">
<a class="btn btn-lg btn-block btn-primary" href="{{site.url}}/get-involved/klhep-volunteer-application.html">KLHEP Volunteers</a>
</div>

</div>