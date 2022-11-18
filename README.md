# devcondmobile

//Criar projeto
npx react-native init <projectName> --template react-native@^0.70.0

//Iniciando
npx react-native run-android


//Instalar dependências
yarn add @react-navigation/native

yarn add react-native-screens react-native-safe-area-context

//No android
react-native-screens package requires one additional configuration step to properly work on Android devices. Edit MainActivity.java file which is located in android/app/src/main/java/<your package name>/MainActivity.java.

Add the following code to the body of MainActivity class:

@Override
protected void onCreate(Bundle savedInstanceState) {
  super.onCreate(null);
}

//Criar o stack
yarn add @react-navigation/native-stack

//Instalar mais bibliotecas
yarn add @react-navigation/drawer

yarn add @react-native-async-storage/async-storage

[Styled components](https://styled-components.com/docs/basics#installation)

yarn add styled-components

npm i @types/styled-components-react-native

[Calendar picker](https://github.com/stephy/CalendarPicker)

npm install --save react-native-calendar-picker

npm install --save moment

//Conflito
npm install --save styled-components

//Resolve 
npm audit fix --force

//Error 01
//this command with --force or --legacy-peer-deps

npm i --force

npm install --legacy-peer-deps