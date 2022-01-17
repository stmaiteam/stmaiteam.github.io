---
title: Team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>

## Current Members

Our team is focused on solving challenging machine learning problems. Our main work generally covers NLP, information retrieval, and cybersecurity, but we also have expertise in bioinformatics, healthcare, predictive maintenance, ML-based forecasting, finance, and image processing.

{% capture html %}
{% include team-list.html role="pi" group="current" %}
{% include team-list.html role="postdoc" group="current" %}
{% include team-list.html role="phd" group="current" %}
{% include team-list.html role="undergrad" group="current" %}
{% include team-list.html role="programmer" group="current" %}
{% include team-list.html role="mascot" group="current" %}
{% include team-list.html role="manager" group="current" %}
{% include team-list.html role="team_leader" group="current" %}
{% include team-list.html role="senior_data_scientist" group="current" %}
{% include team-list.html role="data_scientist" group="current" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->
<!--
## Alumni

We are incredibly proud of all of the COMBINE-lab alumni who have passed through the lab, for whatever period of time they were with us. Below
is a list of lab alumni (if you feel you're missing from the list and would like to be added, please e-mail us):

{% capture html %}
{% include team-list.html role="pi" group="alum" mini="true" %}
{% include team-list.html role="phd_g" group="alum" mini="true" %}
{% include team-list.html role="undergrad" group="alum" mini="true" %}
{% endcapture %}
-->
{% include centerer.html html=html %}
