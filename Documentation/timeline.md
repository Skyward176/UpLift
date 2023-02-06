# Design
1. Use Case diagram (1 day)
2. System Architecture diagram (1 day)
3. Data Flow, User Flow, System Sequence Diagrams (2 days)
4. Database diagram (2 days)
5. UI Design ( 2 weeks). Each includes computer, tablet, and mobile layouts. Excess time will be used for refinement.
    1. Homepage ( 1 day) 
    2. Routine Creator (3 days)
    3. Routine Viewer ( 1 day)
    4. Routine Search ( 1 day)
    5. Workout Editor ( 2 days)
    6. Workout List ( 1 day)
    7. Login/Register ( 1 day)
    8. Profile( 1 day)

# Development

**Test cases should be created before starting on each component.**
1. Fit Test: Create ultra-barebones API, frontend, and database to test integration of technologies. (1 day)
2. User table: Create the Database tables for user accounts.( 1 day)
3. User Serializers: Create API views to allow CRUD of Users.(2 days)
4. User Authorization: Connect API with firebase Auth (1 day)
5. Login frontend: Create frontend page to login a user and send them to dummy homepage.(1 day)
6. Register frontend: Create registration page to create new users.(1 day)
7. Navbar: Create site navigation bar. (1 day)
8. Exercise table: Create tables and populate with common weight exercises.(1 day)
9. Exercise serializers: Create views to CRUD exercises. ( 2 days)
10. Routine table: Create Database tables related to Routine creation. (1 day)
11. Routine serializers: Create views to CRUD reviews.( 2 days)
12. Routine create frontend: Create view to create a new routine. (3 days)
13. Routine list frontend: Create page for viewing list of public routines created by all users.  ( 1 day)
14. Routine search frontend: Allow for searching of routines. Should allow for filtering on various database fields.( 2 days)
15. Workout Model/table: Create Models to track instances of working out. Must be associated with routines.( 1 day)
16. Workout Serializer: Create API views for CRUD of workouts. ( 2 days)
17. Workout Editor frontend: Start a workout, then be guided through all exercises in a routine. Prompts for weightsxreps throughout. If first workout of routine, then ask for initial values. Workout controller should be aware of former workouts to dictate weight increases/decreases. These will be based on what is dictated by the routine.    ( 3 days)
18. Workout list frontend: Get a list of each time you've worked out, and be able to open workout objects to see how you did. ( 1 day)
19. Homepage Frontend: A homepage that informs you of what workout is due for that day, and also provides access to all other features of the site. ( 2 days)
20. User profile frontend: Change your username, contact info, reported weight, age, and other details. ( 1 day)