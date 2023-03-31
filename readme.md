Check out the [original readme](https://github.com/foambubble/foam-template/blob/master/readme.md)


# Foam Template

My take on a foam template. It's a bit different from the default template.



## Structure:
- 📂 `.foam`
  - 📂 `templates`
    - 📝 `daily-note.md`: template for daily notes
    - 📝 `meeting.md`: template for meeting notes
- 📂 `main`: the main workspace
  - 📂 `private`: private notes
    - 📂 `daily-notes`: daily notes
      - 📂 `$year`
        - 📝 `$year-$month-$day.md`: daily note
    - 📂 `work`: work notes
      - 📂 `meetings`: meeting notes
    - 📂 `personal`: personal notes
    - 📝 `todo.md`: todo list
  - 📂 `public`: public notes



## How to:
- 📝 `todo.md`: add a todo item by adding a line that starts with `- [ ]`
- `meeting.md`: add a meeting note by 
  - navigating to daily note
  - pressing `Cmd`+`Shift`+`P` 
  - selecting `Foam: Create New Note From Template` and selecting `Meeting Note`