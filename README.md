# jquery-translate
translate in the language you like

##Install
npm install

##Start
npm start

$("#langPicker").translate();

##Options
$("langPicker").translate({
  byHostName: true,
  picker: false,
  defaultLang: 'nl',
  langDir: "promo/js/locals/translate.json"
});

##byHostName
true or false
if one of the languages is found in hostname. Example: www.domain.nl -> .nl

##picker
true or false



