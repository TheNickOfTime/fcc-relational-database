# Relational Database Projects

1. [Celestial Bodies Database](./01%20-%20Celestial%20Bodies/)
2. [World Cup Database](./02%20-%20World%20Cup%20Database/)
3. [Salon Appointment Scheduler](./03%20-%20Salon%20Appointment%20Scheduler/)
4. [Periodic Table Database](./04%20-%20Periodic%20Table%20Database/)
5. [Number Guessing Game](./05%20-%20Number%20Guessing%20Game/)

## How to run projects
1. Open this repository in a GitHub Codespace (if you have not already).
2. Right click on the folder of your desired project, select `Open in Integrated Terminal`
3. Once the terminal has opened, switch to the postgres user via `sudo su postgres`
4. If needed, import the database .sql files with `psql -U postgres < example.sql`
5. Have at it
	- Connect to the database with the commands `psql` then `\c example`
	- Run the various .sh files via the commandline `./example.sh`