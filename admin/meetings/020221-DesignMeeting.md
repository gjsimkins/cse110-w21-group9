# Team 9 Design Meeting - Feb 2, 2020

- Goal:
  - Decide application flow
  - Decide on a single design mockup (open for modifications later on)
- Members Present:
  - Gary Simkins
  - Lucy Gai
  - Eswar Ramineni
  - Trevor Salom
  - Iurii Iuzifovich
  - Asher Av
- Members Absent:
- Meeting Logistics
- Agenda
  - Unresolved Topics from Past Meeting: None
- Notes
  - Reviewed Gary's application flowchart
    - How do we handle unfinished tasks?
    - Break in between tasks
    - User logs in
      - Show task screen
      - Manage tasks
      - Start a task (Automatically starts pomo and switches to timer screen)
    - On the pomo timer screen
      - Timer, Cancel, Log Distraction
    - On completion of the pomo:
      1. Ring timer
      2. Goto break screen/task management (long or short)
      - Automatically start break timer
      - Allow users to manage tasks/distractions (task state)
      - Set current task
      - Disable start task button until break timer is completed
      - Potentially have finish task on the one last completed task
      3. After break timer
      - Ask user to start a new pomo
    - Make task management be the home page
    - Show break timer on task management page (in the corner or something)
  - Settled on two page layout
    - Columns:
      - Task
      - Distraction Count
      - Pomo count
      - Pomo Estimate count
      - Task status dropdown
      - Start task button
  - Responsive support for desktop to mobile screens [Table solution?](https://medium.com/allenhwkim/mobile-friendly-table-b0cb066dbc0e)
  - Started creating issues/project board
  - Page communication
- Unresolved Topics
  - Transfer miro board to scope - Asher
  - Development Policies - Trevor
  - JS Version ADR - Trevor
- Future Agenda

This is a change to make an example PR. You can ignore this
