+++
# Projects widget.
widget = "projects"
active = true

title = "People"
subtitle = ""

# Order that this section will appear in.
weight = 3

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "people"

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
# To show all items, set `tag` to " x* ".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "people"

[[filter]]
  name = "Ecology"
  tag = "ecology"

[[filter]]
  name = "Neuroscience"
  tag = "neuroscience"

[[filter]]
  name = "Systems Biology"
  tag = "systems-biology"

#[[filter]]
#  name = "QuCoBiM"
#  tag = "QuCoBiM"

#[[filter]]
#  name = "Other"
#  tag = "QucoBiM, NeSM, ProBiPoNaM, miscellaneous"

#[[filter]]
#  name = "NeSM"
#  tag = ".NeSM"

#[[filter]]
#  name = "ProBiPoNaM"
#  tag = ".ProBiPoNaM"

#[[filter]]
#  name = "Miscellaneous"
#  tag = "miscellaneous"

[[filter]]
  name = "Past members"
  tag = "past-members"
+++
