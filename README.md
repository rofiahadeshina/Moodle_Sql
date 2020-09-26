# Moodle_Sql

This is an analysis of the 2019 10 Academy learners activity in the Moodle Learning Management System. All students activities are stored in a highly structured database.
The Moodle LMS  is a free and open-source learning management system written in PHP and distributed under the GNU General Public License. It is used for blended learning, distance education, flipped classroom and other e-learning projects in schools, universities, workplaces and other sectors. With customizable management features, it is used to create private websites with online courses for educators and trainers to achieve learning goals. Moodle allows for extending and tailoring learning environments using community-sourced plugins.
Here we explore the 10 Academy Moodle logs stored in the database together with many other relevant tables

## Most Important Tables (MIT)
Moodle database is complex - with more than 400 connected tables! In this project we are interested only in the subset of the tables. The most important tables we will consider in this challenge are (tables in bold are VIP)

- **mdl_logstore_standard_log**
- **mdl_context**
- **mdl_user**
- **mdl_course**
- **mdl_modules**
- **mdl_course_modules**
- **mdl_course_modules_completion** 
- mdl_grade_items
- **mdl_grade_grades**
- mdl_grade_categories
- mdl_grade_items_history
- mdl_grade_grades_history
- mdl_grade_categories_history
- mdl_forum
- mdl_forum_discussions
- mdl_forum_posts
