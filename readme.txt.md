readme.txt
https://aws.amazon.com/jp/getting-started/hands-on/build-react-app-amplify-graphql/module-one/?e=gs2020&p=build-a-react-app-intro

1) 新しいReact アプリケーションを作成する
簡単に React アプリケーションを作成するには、create-react-app のコマンドを使用します。コマンドプロンプトまたはターミナルで次のコマンドを使用して、このパッケージをインストールします。

npx create-react-app amplifyapp
cd amplifyapp
npm start

--Result--
PS C:\Users\silve\Downloads\2022May19> npx create-react-app amplifyapp
npx: installed 67 in 6.213s

Creating a new React app in C:\Users\silve\Downloads\2022May19\amplifyapp.

Installing packages. This might take a couple of minutes.
Installing react, react-dom, and react-scripts with cra-template...


> core-js@3.22.5 postinstall C:\Users\silve\Downloads\2022May19\amplifyapp\node_modules\core-js
> node -e "try{require('./postinstall')}catch(e){}"


> core-js-pure@3.22.5 postinstall C:\Users\silve\Downloads\2022May19\amplifyapp\node_modules\core-js-pure
> node -e "try{require('./postinstall')}catch(e){}"

+ react-scripts@5.0.1
+ react@18.1.0
+ react-dom@18.1.0
+ cra-template@1.2.0
added 1390 packages from 620 contributors in 91.865s

183 packages are looking for funding
  run `npm fund` for details


Initialized a git repository.

Installing template dependencies using npm...
npm WARN @apideck/better-ajv-errors@0.3.3 requires a peer of ajv@>=8 but none is installed. You must install peer dependencies yourself.
npm WARN fork-ts-checker-webpack-plugin@6.5.2 requires a peer of typescript@>= 2.7 but none is installed. You must install peer dependencies yourself.
npm WARN tsutils@3.21.0 requires a peer of typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta but none is installed. You must install peer dependencies yourself.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@2.3.2 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.3.2: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})       

+ web-vitals@2.1.4
+ @testing-library/react@13.2.0
+ @testing-library/user-event@13.5.0
+ @testing-library/jest-dom@5.16.4
added 39 packages from 109 contributors in 18.458s

183 packages are looking for funding
  run `npm fund` for details

Removing template package using npm...

npm WARN @apideck/better-ajv-errors@0.3.3 requires a peer of ajv@>=8 but none is installed. You must install peer dependencies yourself.
npm WARN fork-ts-checker-webpack-plugin@6.5.2 requires a peer of typescript@>= 2.7 but none is installed. You must install peer dependencies yourself.
npm WARN tsutils@3.21.0 requires a peer of typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta but none is installed. You must install peer dependencies yourself.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@2.3.2 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.3.2: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})       

removed 1 package and audited 1429 packages in 16.846s

183 packages are looking for funding
  run `npm fund` for details

found 1 moderate severity vulnerability
  run `npm audit fix` to fix them, or `npm audit` for details

Created git commit.
Success! Created amplifyapp at C:\Users\silve\Downloads\2022May19\amplifyapp
Inside that directory, you can run several commands:

  npm start
    Starts the development server.

  npm run build

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd amplifyapp
  npm start
PS C:\Users\silve\Downloads\2022May19> cd cd amplifyapp
Set-Location : A positional parameter cannot be found that accepts argument 'amplifyapp'.
At line:1 char:1
+ cd cd amplifyapp
+ ~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Set-Location], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.SetLocationCommand
 
PS C:\Users\silve\Downloads\2022May19> ls
Compiled successfully!

You can now view amplifyapp in the browser.      

  Local:            http://localhost:3000        
  On Your Network:  http://192.168.56.1:3000     

Note that the development build is not optimized.
To create a production build, use npm run build. 

webpack compiled successfully


2) Github repository を初期化する


https://github.com/GochaLearningSpace/amplifyapp.git




Reference between 