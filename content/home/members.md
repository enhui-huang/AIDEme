+++
# People widget.
widget = "people"  # Use the People widget
headless = true  # This file represents a page section.
active = true
weight = 20

title = "Members"

# ... Put Your Section Options Here (title etc.) ...

[content]
  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
  user_groups = ["Professors",
                 "PhD Students"]

[design]
  # Show user's social networking links? (true/false)
  show_social = true

  # Show user's interests? (true/false)
  show_interests = false
  
  # Show user's affliations (true/false)
  show_affliations = true
  
+++