---
layout: docu-page
full_title: "Gush: Rapid workflow for project maintainers and contributors"
---
{% block content %}
pull-request:fabbot-io
----------------------

* Description: Run fabbot-io patches on given PR
* Usage:

  * `pull-request:fabbot-io <pr_number>`

The <info>pull-request:fabbot-io</info> command applies patch fabbot-io robot on given PR:

    <info>$ gush pull-request:fabbot-io 12</info>


### Arguments:

**pr_number:**

* Name: pr_number
* Is required: yes
* Is array: no
* Description: PR number
* Default: `NULL`
{% endblock %}