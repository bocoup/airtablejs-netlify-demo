# airtablejs-netlify-demo

Demonstration of integrating airtable.js and Netlify Lambda functions

To run:

1. Clone this repository
2. Make the following replacements to the `hello-world.js` file:
   - `<my key>` - replace with an Airtable API access key
   - `<my base>` - replace with an Airtable Base ID
   - `<table name>` - replace with the name of an Airtable Table in the
     Airtable Base
   - `Grid view` - replace with the name of an Airtable View in the Airtable
     Table
   - `title` - replace with the name of an Airtable Field in the Airtable View
3. Execute the following two commands from a terminal located in the project's
   root directory:

    npm install
    npm run dev

4. Open a second terminal window located in the project's root directory, and
   execute the following command:

    npm run invoke

## License

Copyright 2020 Mike Pennisi under [the GNU General Public License
v3.0](https://www.gnu.org/licenses/gpl-3.0.html)
