User Stories:
- Users should be able to log into the app quickly, using their existing Google Accounts.
- Users should be greeted with a dashboard. 
- On the dashboard, users should see a button that allows users to log their workout for the day, including details like: (
  - the kind of workout; 
  - how many sets and how many reps; 
  - how long of a break users take between sets; 
  - what muscles and muscle groups have been targetted; 
  - where they worked out).
- On the dashboard, users should see another button displaying how their workout statistics for the past week, 2 weeks, 30 days. 
  - They should see stats like 
    - what muscle groups were targetted on what days, 
    - how long the users worked out for on different days, 
    - how much time was allocated to each muscle group and workout. 
    - They should be able to see this information in table form, where each row accounts for a different statistic. 
    - Users should also be able to see this information in calendar form, where each day of the month has a different box in the calendar. 
      - For each box-day, the earliest workout should appear on the box-day's cover, and the rest of the workout should appear as "<X> number of workouts done today" on the box-day's cover. 
      - Clicking the box-day's cover should expand that day and tell you what workouts you did, and give you the above summary statistics.
- Users should also be given a button to track food they ate, to keep count of their macros. 
  - Macros are broken down into the four categories, and you can either 
    - manually input a food item and have the app run the macro calculations for you, 
    - or enter the grams of the food you ate, and the macros this food gives.
- Users should then be able to see table graphs and calendar graphs for their food intake, similar to what was done for the workouts.

Dev Stories:
- Must be written using SpringBoot, TypeScript React, React Router, PostgreSQL, Tailwind CSS

System Design:

