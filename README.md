# devcondmobile

//Criar projeto
npx react-native init <projectName> --template react-native@^0.70.0

//Iniciando
npx react-native run-android

//ver devices ativos
adb devices

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

//Resolvendo Conflitos
npm install --legacy-peer-deps

npm install --save styled-components --legacy-peer-deps
npm i react-native-gesture-handler --legacy-peer-deps
npm install react-native-safe-area-context

npm install --save styled-components --force
npm i react-native-gesture-handler --force

//Resolvendo erros
npm audit fix --force
npm i --force

npm cache clean --force

npm install --legacy-peer-deps

//async storage
npm i @react-native-async-storage/async-storage

//React navigation
yarn add @react-navigation/native

@react-navigation/stack


//Erro Resolvendo
//inserir no index do node-modules/react-nantive

 // Deprecated Prop Types
  get ColorPropType(): $FlowFixMe {
    return require('deprecated-react-native-prop-types').ColorPropType;
    // invariant(
    //   false,
    //   'ColorPropType has been removed from React Native. Migrate to ' +
    //     "ColorPropType exported from 'deprecated-react-native-prop-types'.",
    // );
  },
  get EdgeInsetsPropType(): $FlowFixMe {
    return require('deprecated-react-native-prop-types').EdgeInsetsPropType;
    // invariant(
    //   false,
    //   'EdgeInsetsPropType has been removed from React Native. Migrate to ' +
    //     "EdgeInsetsPropType exported from 'deprecated-react-native-prop-types'.",
    // );
  },
  get PointPropType(): $FlowFixMe {
    return require('deprecated-react-native-prop-types').PointPropType;
    // invariant(
    //   false,
    //   'PointPropType has been removed from React Native. Migrate to ' +
    //     "PointPropType exported from 'deprecated-react-native-prop-types'.",
    // );
  },
  get ViewPropTypes(): $FlowFixMe {
    return require('deprecated-react-native-prop-types').ViewPropTypes;
  //   invariant(
  //     false,
  //     'ViewPropTypes has been removed from React Native. Migrate to ' +
  //       "ViewPropTypes exported from 'deprecated-react-native-prop-types'.",
  //   );
  // },
};


[Dica](https://stackoverflow.com/questions/72755476/invariant-violation-viewproptypes-has-been-removed-from-react-native-migrate-t)