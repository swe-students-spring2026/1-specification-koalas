# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## Team members

Bella D'Aquino - [GitHub Profile](https://github.com/belladaq)
Zhuowen (William) Zhang - [GitHub Profile](https://github.com/Incrediblez7)

## Stakeholders

### Primary User Interview

**Name**: Nina Johnson  
**User Type**: Current NYU Student; Regular Campus Study Space User

#### Goals / Needs
- Quickly identify available study spaces in real time
- Find study environments that match certain needs (e.g. quiet vs. group-friendly)
- See specific seating availability within a space (e.g. tables near window)
- Receive personalized study space recommendations based on set preferences and current crowdedness conditions across study areas
- See information about what a building or space may provide (e.g. computer or printer access, nearby cafe or dining hall)

#### Problems / Frustrations
- Study spaces prioritize aesthetics over functionality, resulting in limited seating in NYU buildings during prime hours
- For existing NYU study space reservations, the process is long and inconvenient
- Lack of visibility into which specific areas or tables are occupied, leading to wasted time searching for a suitable study space
- It's sometimes unclear what spaces are meant for silent study without checking in person, making it harder to find locations for group study
- Existing tools (e.g. Google "busy hours") don't reflect real time conditions or student needs


## Product Vision Statement

This app is an intuitive, real-time campus crowdedness app that helps NYU students quickly find available study spaces that match their preferences for noise level, resources, seating, and group size without wasting time searching in-person.

## User Requirements (Stories)
### NYU Members
##### Readers
1. As a NYU student, I want to check the nearest silent study space so that I can find the closest place to work on projects.
2. As a NYU student, I want to check how crowded a study space is so that I can decide whether it's worth the effort to go there.
3. As a NYU student, I want to check the crowdedness of a study space before leaving my dorm so that I can save commute time.
4. As a NYU student, I want to avoid crowded study spaces so that I can find a seat.
5. As a NYU student, I want to see which floor on bobst has most space so that I can find a place to study.
6. As a NYU student, I want to know the update time of the crowdedness data so that I know the data is reliable.
7. As a NYU student, I want to know when the study space closes so that I know where to go at midnight.
8. As a NYU student, I want to check how crowded the collaborative study space is so that I can plan group conversation slots accordingly.
9. As a NYU student, I want to check if the collaborative study space is already full before I go there so that I won't have to wander around finding a new place.
10. As a NYU student, I want to see the historical trend of the crowdedness data so that I can plan accordingly.
11. As a NYU student, I want to filter out the crowded spaces so that I can quickly locate a quiet space.
12. As a NYU student, I want to get a notification when a study space gets less crowded so that I can secure a seat ASAP.
13. As a NYU student, I want to bookmark a study space so that I can quickly access it later.
14. As a NYU student, I want to submit a complaint about inaccurate data so that the admins can fix it.
15. As a NYU student, I want to reserve a study room so that I am guaranteed to have a seat with peace of mind.
<!-- p.s. Doable by <Ab>using "POST /spaces/availability/grid" and "POST /ajax/space/times" of nyu.libcal.com -->
##### Contributors
16. As a NYU student, I want to update the crowdedness data of a study space so that I can help others find a place to study.
17. As a NYU student, I want to not spend a lot of time updating the crowdedness data so that I can efficiently update the data.
18. As a NYU student, I want to contribute to the data since more people use the app, the more accurate the data will be.
19. As a NYU student, I want to select the building and floor of the study space so that I can quickly locate the study space I want to update.
20. As a NYU student, I want to automatically update the crowdedness data when I go there so that I don't have to do anything while still contributing to the data.
21. As a NYU student, I want to select between a predefined set of crowdedness levels (lots of seats, few seats if any, completely full, closed, etc.) so that I don't have to describe in my own words.
22. As a NYU student, I want to see the last updated time so that I don't have to duplicate-update the data.
23. As a NYU student, I want to get a push notification when I enter a study space so that I can quickly contribute to the crowdedness data.

### Administrators
1. As an administrator, I want to remove invalid submissions so that everything is up to date.
2. As an administrator, I want to avoid sybil attacks (spams, fake accounts, etc.) so that the data is not manipulated.
3. As an administrator, I want to temporarily disable the submission of data so that I can do whatever maintenance I need to do.
4. As an administrator, I want to add warnings to a specific building/floor (activities, construction, etc.) so that users are aware of the situation.
5. As an administrator, I want to add/remove/edit buildings and floors so that the data is up to date.
6. As an administrator, I want to be able to verify myself so that I can access to the elevated permissions.
7. As an administrator, I want to quickly pinpoint errors in submitted crowdedness data so that I can fix them quickly.
8. As an administrator, I want to solve complaints from users so that I can fix data/bugs that went wrong.
9. As an administrator, I want to take actions against users who misuse the app so that the app is safe for everyone.
10. As an administrator, I want to audit the crowdedness data so that I can identify systematic problems.

## Activity Diagrams

Source UML Activity Diagrams: [UML.drawio](contents/uml/UML.drawio)

![NYU-Member-1](contents/uml/NYU-Member-1.svg)
![NYU-Member-2](contents/uml/NYU-Member-2.svg)
![NYU-Member-3](contents/uml/NYU-Member-3.svg)
![Administrator-1](contents/uml/Administrator-1.svg)
![Administrator-2](contents/uml/Administrator-2.svg)

## Clickable Prototype

See instructions. Delete this line and place a publicly-accessible link to your clickable prototype here.
