---
title: Veterinary Undergraduate Volunteers
date: 2019-02-26 09:33:00 -08:00
position: 1
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