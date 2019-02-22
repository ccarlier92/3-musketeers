# cash program

## :boom: Goal
:money_with_wings:Convert one currency to other ones in real time
## Instalation 

- [x] Fork the project
- [x] Clone the project in your workspace
- [x] In the shell, run the following commands :
      $ cd path_to_workspace
      $ npm i
      $ node index.js


## :question: How to use it
''
$ cash <amount> <from> <to>
$ cash <options>
'' 
  
## :heavy_plus_sign: Options
'$ --set -s    // Set default currencies'

## :heavy_check_mark: Examples
'$ cash 10 usd eur pln'
'$ cash --set usd aud'


## :grey_question:How does it work?

 1. The program is looking for the API adress in the constants.js file.
 2. It checks the actual currencies rate on internet in real time.
 3. It sets currency goal default in an array.
 4. The program uses the convert method in node libraries to convert the currency.
 5. If you havn't specified any currency goal or/and origin, it will convert you 1 USD in Euro, Britsh Pound, and Japanese Yen.
