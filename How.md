npx create-react-app crudPractice-Frontend
cd crudPractice-Frontend

// install bootstrap and reactstrap with its dependencies…
npm install bootstrap 
npm install --save reactstrap react react-dom

// install the react-csv plugin
npm install react-csv

// create some folders and files in the src folder...
cd src

mkdir Components
cd Components/

mkdir Forms Modals Tables

cd Forms/
touch AddEditForm.js

cd ../Modals/
touch Modal.js

cd ../Tables/
touch DataTable.js