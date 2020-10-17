---
layout: workshop
# More detailed instructions (including how to fill these variables for an
# online workshop) are available at
# https://carpentries.github.io/workshop-template/customization/index.html
venue: "University of Saskatchewan, Pulse Crop Research Group"  
address: "online"
country: "ca"
language: "en"
latitude: "52.131590"
longitude: "-106.660600"
email: ["knowpulse@usask.ca"]
---

<h2 id="general">General Information</h2>

<p>The KnowPulse KnowledgeBase focuses on short question-based tutorials to help researchers get their work done. Specifically, this collection of tutorials includes questions asked by pulse crop researchers supporting the breeding program at the University of Saskatchewan, Crop Development Center. Each question is answered through a short tutorial which uses KnowPulse as part of the workflow to answer the question. The whole workflow, including non-KnowPulse focused steps, is covered with a holistic approach to help the researcher answer their question efficiently.</p>

<p style="font-style: italic; text-align:center;">This knowledgebase is inspired by <a href="https://carpentries.org/">The Carpentries</a>.<br />For more information on this style of teaching see their paper <a href="http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001745">"Best Practices for Scientific Computing"</a>.</p>

<hr>

<p id="who">
  <strong>Who:</strong>
  These tutorials are aimed at pulse crop graduate students and researchers.
</p>

<p id="requirements">
  <strong>Requirements:</strong>
  Participants must bring a laptop with a
  Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on.
</p>

{% comment %}
CONTACT EMAIL ADDRESS

Display the contact email address set in the configuration file.
{% endcomment %}
<p id="contact">
  <strong>Contact:</strong>
  Please email
  {% if page.email %}
  {% for email in page.email %}
  {% if forloop.last and page.email.size > 1 %}
  or
  {% else %}
  {% unless forloop.first %}
  ,
  {% endunless %}
  {% endif %}
  <a href='mailto:{{email}}'>{{email}}</a>
  {% endfor %}
  {% else %}
  to-be-announced
  {% endif %}
  for more information.
</p>

<hr/>

<h2 id="lessons">Lessons</h2>

<p style="font-style:italic;">Lessons are currently under development. They will be added here as they become available.</p>
