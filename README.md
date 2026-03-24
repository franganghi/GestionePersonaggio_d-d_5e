# GestionePersonaggio_d-d_5e
Permette la gestione locale di un personaggio del g.d.r. D&amp;D 5e sul proprio browser


How to get a translated complete spell list?

  sudo apt-get install pip
  mkdir deep-translator-json
  cd deep-translator-json/
  python3 -m venv venv
  source venv/bin/activate
  pip install -U deep-translator requests
  wget <json_translate.py> <target_language>
  python3 json_translate.py  
