+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "projects"
active = true

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Opportunities"
subtitle = ""

# Order that this section will appear in.
weight = 9

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "opportunities"

# View.
# Customize how projects are displayed.
# Legend:
#    1 = List (previously Simple)
#    2 = Compact (previously Stream)
#    3 = Card (previously Detailed)
#    4 = Citation (previously APA and MLA), only available for publications
#        Optionally, edit the value of citation_style in params.toml to APA or MLA
#    5 = Showcase (large images), only available for projects
view = 1

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
  tag = "*"

[[filter]]
  name = "Bachelor's thesis"
  tag = "bachelor-thesis-proposal"

[[filter]]
  name = "Master's thesis"
  tag = "master-thesis-proposal"

[[filter]]
  name = "PhD"
  tag = "phd-positions"

[[filter]]
  name = "Post-doc"
  tag = "postdoc-positions"
+++

We propose theses in the field of Statistical Physics of Complex Systems, applied (but not limited) to ecology, biology, neuroscience and machine learning. Our thesis students will be invited to join the lab activities such us journal club, research discussion, etc…
