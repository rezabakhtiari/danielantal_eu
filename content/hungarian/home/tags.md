+++
# Tag Cloud widget.
widget = "tag_cloud"  
headless = true  # This file represents a page section.
active = true 
weight = 40  # Order that this section will appear.

title = "Gyakori témák"
subtitle = ""

[content]
  # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy = "tags"
  
  # Choose how many tags you would like to display (0 = all tags)
  count = 40

[design]
  # Minimum and maximum font sizes (1.0 = 100%).
  font_size_min = 0.5
  font_size_max = 2.0
+++

