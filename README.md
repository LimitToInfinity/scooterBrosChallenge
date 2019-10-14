Objectives to Accomplish!
    (check them off as you go :)

1) Create a Bro Class.

2) Create a Scooter Class.

3) Many to many relationship between Scooters and Bros.

4) Create Routes for Bros:
    a) Index
    b) Show
    c) Create
    d) New
    e) Update
    f) Edit
    g) Destroy

5) Create Routes for Scooters:
    a) Index
    b) Show
    c) Create
    d) Destroy
    BONUS:
    e) New
    f) Update
    g) Edit

6) Actions for Bros:
    a) Index
    b) Show
    c) Create
    d) New
    e) Update
    f) Edit
    g) Destroy
    h) allowed bro params
    BONUS:
    i) Before action with find bro for show, update, edit, and destroy only.
    j) Search feature in index action.
    k) Redirect to index in destroy action after destruction.

7) Actions for Scooters:
    a) Index
    b) Show
    c) Create
    d) Destroy
    e) allowed bro params
    BONUS:
    f) New
    g) Update
    h) Edit
    i) Before action with find bro for show, update, edit, and destroy only.

8) Validation for Bros:
    a) Name must be given (cannot be blank) and cannot be the same as any other bros that already exist.

9) Validations for Scooters:
    a) Brand must be given (cannot be blank).

10) More with Bro:
    a) Can make a new scooter at the same time a new bro is made (hint: nested attributes and params...).

BONUS:

11) Make Views for Bros and Scooters:
    a) Index page:
        1. Displays all Bros (or Scooters).
        2. Each Bro's (or Scooter's) name links to their show page.
        BONUS BONUS:
        3. An element that takes you to the Bro's (or Scooter's) New page.
        4. An element that takes you to its relationship's index page (i.e. Bro's index would go to Scooter's index and vice versa).
        5. Search bar at the top of the index page.
    b) Show page:
        1. Displays all the scooters related to that bro (vice versa for bros related to that scooter).
        2. Delete button for the specific instance.
        BONUS BONUS:
        3. Each scooter links to the scooters show page (or each bro on the scooter's show page links to that bro's page).
        4. An element that takes you to the its index page (e.g. bro's show page can go to bro's index page).
    c) New page (for Bro only):
        1. Form to create a new bro instance with name, age, and a scooter related to that bro with a brand.
        BONUS BONUS:
        2. Display error messages for any validation not met.
        3. An element that takes you to the bros index page.
    d) Edit page (for Bro only):
        1. Form to change a bros name.
        BONUS BONUS:
        2. Form to add an existing OR new scooter related to this bro.
