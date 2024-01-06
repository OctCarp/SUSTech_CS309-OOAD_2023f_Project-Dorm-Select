## Dormitory Selection System

### Basic Requirements (75%)

1. **Dormitory Management System**:
    - Support for multiple dormitory buildings in different locations.
        - Each dormitory building comprises multiple rooms.
        - Room types: single, double, triple, and quadruple occupancy.
2. **Faculty Portal**:
    - Enable faculty to upload or modify dormitory-related information, including zoning, building details, floor plans, room layouts, and descriptions.
    - Support user management, allowing manual addition, deletion, and modification of individual student users. Bulk import of student information and account creation through tables should be possible.
    - Set dormitory selection timeframes.
    - Provide the ability to export dormitory selection data.
3. **Student Portal**:
    - Allow students to view and filter available rooms. (Note: Room search hierarchy: Zoning [Phase II] -> Building [17 buildings] -> Floor [3 floors] -> Room number [301])
    - Include a profile module for students to publish personal information, accommodation habits, and the ability to search for potential roommates.
    - Implement a roommate formation module, where each student can either create or join a team.
    - Offer a room bookmarking module, allowing students to save a limited number of preferred rooms and monitor their availability.
    - Include a commenting module for students to leave feedback on rooms or respond to comments.
    - Implement a dormitory selection module that opens at specified times, allowing selection by teams.
    - Provide a notification module for comment and team-related information.

### Advanced Requirements (25%):

1. Incorporate elements specific to SUSTech, considering real-world scenarios.
2. Introduce a campus map (SUSTech map) to display dormitory building locations, room positions, and bed placements. Users should be able to click for previews and selections.
3. Design staggered selection times differentiating between male and female students, doctoral and master's students, waiting list selection times, and room type displays.
4. Implement a room exchange feature on the platform.
5. Include online communication capabilities.
6. Address high concurrency for dormitory selection.
7. Implement an anti-cheating system to restrict scripting and allow only single-user logins.
8. Develop a dedicated client.
9. Ensure an aesthetically pleasing user interface.
10. Deploy servers for system operation.

### Stakeholders:
- Xiang Yi (易翔)
- Yiwei Ren (任艺伟)