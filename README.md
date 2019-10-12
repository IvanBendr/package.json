# package.json
{
  " имя " : " HoraToken " ,
  " версия " : " 1.0.0 " ,
  " description " : " Наградной жетон, который будет использоваться в видеоиграх. Жетоны Hora можно получить (добыть), только играя в Crypto Idle Miner, в мобильную игру Hora Games. У Hora Token месячный лимит чеканки составляет 100 м жетонов, а кепка - 12 миллиардов, которые должны быть достигнуты в ближайшие 10 лет. " ,
  " каталоги " : {
    " тест " : " тест "
  },
  " сценарии " : {
    " dev " : " lite-server -c ./bs-config.js " ,
    " test " : " echo \" Ошибка: тест не указан \ " && exit 1 " ,
    " setup-dapp " : " bash scripts / migrate-and-setup.sh "
  },
  " originalAuthors " : " трюфель " ,
  " автор " : {
    " имя " : " Горан Алексич " ,
    " электронная почта " : " goran@horagames.com "
  },
  « лицензия » : « MIT » ,
  " devDependencies " : {
    « мел » : « ^ 2.4.1 » ,
    " lite-сервер " : " ^ 2.4.0 "
  },
  " зависимости " : {
    " openzeppelin-solidity " : " ^ 2.3.0 "
  }
