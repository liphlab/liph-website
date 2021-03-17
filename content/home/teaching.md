+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "projects"
active = true

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Teaching"
subtitle = ""

# Order that this section will appear in.
weight = 6

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "teaching"

# View.
# Customize how projects are displayed.
# Legend:
#    1 = List (previously Simple)
#    2 = Compact (previously Stream)
#    3 = Card (previously Detailed)
#    4 = Citation (previously APA and MLA), only available for publications
#        Optionally, edit the value of citation_style in params.toml to APA or MLA
#    5 = Showcase (large images), only available for projects
view = 3

# Widget layout
# Legend: 0 = two columns (default), 1 = single column
widget_layout = 0

# For Showcase view, flip alternate rows?
flip_alt_rows = false


# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "* " tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.

[[filter]]
  name = "All"
  tag = "current-course"

[[filter]]
  name = "Bachelor"
  tag = "bachelor-course"

[[filter]]
  name = "Master"
  tag = "master-course"

[[filter]]
  name = "PhD"
  tag = "phd-course"

[[filter]]
  name = "Past courses"
  tag = "past-courses"
+++
