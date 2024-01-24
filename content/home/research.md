+++
# Projects widget.
widget = "projects"
active = true
date = 2018-06-07T00:00:00

title = "Research"
subtitle = ""

# Order that this section will appear in.
weight = 2

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "research"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards, 2 = showcase.
view = 2

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
  tag = "research-project"

[[filter]]
  name = "Ecology"
  tag = "ecology"

[[filter]]
  name = "Neuroscience"
  tag = "neuroscience"

[[filter]]
  name = "System Biology"
  tag = "biology"


[[filter]]
  name = "Old projects"
  tag = "old-research-project"
+++
