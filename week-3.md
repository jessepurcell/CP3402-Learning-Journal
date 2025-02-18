# Week 3

# Learning Activites and Resources

This week I learned how to install and setup a basic WordPress site.

# Estimated Hours

Approx 3 hours<br>
https://www.docker.com/blog/how-to-dockerize-wordpress/<br>
https://www.linkedin.com/learning/wordpress-workflows-2015/<br>
https://developer.wordpress.org/advanced-administration/before-install/development/<br>
https://localwp.com/<br>

# Content Insights

WordPress is an easy to use CMS with a great amount of customizability with its community of developers creating themes and plugins. Setting up WordPress is fairly straightforward, only taking a few clicks. Something I noticed early on was how WordPress manages and store content, WordPress dynamically builds its webpages using data stored in its associated database (for me MariaDB). This means that posts, pages, users, theme configurations among other things are not baked into the html served to the client or saved as files on the server but retrieved from the database each time it fetches a page for the user. My original attempt to run WordPress locally was through a Docker container as I had at the time assumed this would make my project portable and easier to work on between multiple devices. This lead to me losing progress when switching between computers when setting up my site as my docker setup did not save the state of the database between devices. This lead to me having to learn how to export the database so I could work with the same configuration on multiple machines.

# Career/Employability/Learning Insights

Setting up WordPress for the first time and deciding to use Docker to run it locally highlighted the importance of the database in WordPress. Learning how to export and restore the database to ensure an identical setup between devices when developing help improve my skills in backup management and problem solving which I believe to be important skills in IT.