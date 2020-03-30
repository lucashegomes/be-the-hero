## Backend inital steps
npm install -y
npm install express
npm install -d nodemon - to install nodemon just for develop environment
npm install cors
npm install knex - query builder to Node querie databases
npx knex init - to create knex file config
npx knex migrate:make create_ongs - to create migrate file config
npx knex migrate:latest - to deploy migrate
npx knex migrate:make create_incidents

## Frontend inital steps
npx create-react-app frontend 
npm install react-icons
npm install react-router-dom
npm install axios

## Mobile inital steps
npm install -g expo-cli
expo init mobile
npm install @react-navigation/native
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
npm install @react-navigation/stack
expo install expo-constants