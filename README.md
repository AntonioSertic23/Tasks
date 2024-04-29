# Tasks

## Web application for task management

The Tasks project originated as a college assignment for construction exercises in the **Server-Side Web Programming** and **Scripting Programming Languages** courses.

The project's objective was to create a task management program with user authentication and hierarchical relationships, where the Comment class contains objects of the User and Task classes.

The webpage showcases knowledge of the following web technologies: **AngularJS v1.6.9** with **jQuery 3.2.1**, **PHP 7**, and **Bootstrap 4.4.1** for design. **MySQL** was used as the database.

[![My Skills](https://skillicons.dev/icons?i=angular,jquery,php,bootstrap,mysql)](https://skillicons.dev)

---

### After logging into the application, the user can:

- View and update their profile information
- Visit profiles of other individuals they collaborate with on tasks
- Browse their completed and unfinished tasks, which can be sorted and searched by name
- Comment on their own tasks (those they are assigned to) and mark them as completed; they can also edit and delete their comments on these tasks
- View created tasks, which can be sorted and searched by name, and create new tasks
- Edit, comment on, and delete created tasks, as well as edit and delete their comments on these tasks
- In case a user who created a resolved task does not consider it truly completed, they can return it to the execution state

---

### Project Setup

To run the project, you need to install [XAMPP](https://www.apachefriends.org) and then start **Apache** and **MySQL** through it.

Next, copy the **Tasks** folder to `C:\xampp\htdocs`.

Access the link to the database: [http://localhost/phpmyadmin/index.php](http://localhost/phpmyadmin/index.php).

In **phpMyAdmin**, create a database named `zadaci` (Character Set should be set to **Collation**), and then import the `zadaci.sql` file located in the root of the project.

Access the application through the link: [http://localhost/zadaci/index.php#!/](http://localhost/zadaci/index.php#!/).
