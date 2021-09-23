NOTES APP
Technology Used : NODEJS
NPM Modules used : chalk,yargs


Command Line Options:

Listing All Notes from JSON file
	> node app.js list

Reading a particular note based on its tital
	> node app.js read --title="Title to be read"

Removing a note using title
	> node app.js remove --title="Title to be deleted"

Adding a note
	> node app.js add --title="Title of note" --body="Content"
