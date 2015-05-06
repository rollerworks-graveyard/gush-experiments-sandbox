---
layout: docu-page
full_title: "Gush: Rapid workflow for project maintainers and contributors"
---
{% block content %}
branch:push
-----------

* Description: Pushes and tracks the current local branch into user own fork
* Usage:

  * `branch:push [-u|--set-upstream] [--] [<target_organization>]`

The <info>branch:push</info> command pushes the current local branch into your own fork:

    <info>$ gush branch:push</info>


### Arguments:

**target_organization:**

* Name: target_organization
* Is required: no
* Is array: no
* Description: Organization (default to username) to where to push the branch
* Default: `NULL`

### Options:

**set-upstream:**

* Name: `--set-upstream`
* Shortcut: `-u`
* Accept value: no
* Is value required: no
* Is multiple: no
* Description: Set the target_organization as the default upstream
* Default: `false`
{% endblock %}