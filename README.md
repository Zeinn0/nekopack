{
  "name": "𝐓𝐄𝐋𝐄𝐇𝐎𝐍 𝐅𝐋𝐀𝐒𝐇",
  "description": "اللهم صلي وسلم وزد وبارك على سيدنا محمد 🌺",
  "logo": "https://telegra.ph/file/738661f85fe3e4fd54d20.jpg",
  "keywords": [
    "plugin",
    "modular",
    "productivity"
  ],
  "repository": "https://github.com/IQ-FLASH/FLASH",
  "website": "#TODO",
  "success_url": "#TODO",
  "env": {
    "ALIVE_NAME": {
      "description": "هنا ضع اسم التلجرام الخاص بك",
      "value": ""
    },
    "APP_ID": {
      "description": "هنا ضع الايبي ايدي الخاص بك يتكون من 8 ارقام", 
      "value": ""
    },
    "API_HASH": {
      "description": "هنا ضع الايبي هاش الخاص بك",
      "value": ""
    },
    "ENV": {
      "description": "لا تغير هذه القيمه",
      "value": "ANYTHING"
    },
    "COMMAND_HAND_LER": {
      "description": "لا تغير هذه القيمه",
      "value": "."
    },
    "STRING_SESSION": {
      "description": "هنا ضع جلسة بايروجرام او تيلثون",
      "value": "",
      "required": false
    },
    "TG_BOT_TOKEN": {
      "description": "هنا ضع توكن بوتك",
      "value": ""
    },
    "HEROKU_API_KEY": {
      "description": "هنا ضع الايبي كي الخاص بحساب هيروكو من هذا الرابط https://dashboard.heroku.com/account",
      "value": "",
      "required": false
    },
    "HEROKU_APP_NAME": {
      "description": "اسم التطبيق اول مربع كتبتة",
      "value": "",
      "required": false
    },
    "TZ": {
      "description": "المنطقه الزمنيه من القارة الخاصه بك وعاصمه بلدك يجب ان يكون اول حرف كبير",
      "value": "Africa/Baghdad",
      "required": false
    }
  },
  "addons": [{
    "plan": "heroku-postgresql",
    "options": {
      "version": "12"
    }
  }],
  "buildpacks": [{
    "url": "https://github.com/SOURCE-FLASH/heroku-buildpack-ffmpeg-latest-main.git"
  },{
    "url":"https://github.com/heroku/heroku-buildpack-google-chrome"
  },{
    "url":"https://github.com/heroku/heroku-buildpack-chromedriver"
  },{
    "url": "https://github.com/riganf/heroku-buildpack-p7zip"
  },{
    "url": "https://github.com/heroku/heroku-buildpack-apt.git"
  },{
    "url": "https://github.com/chrismytton/heroku-buildpack-jq"
  },{
    "url": "https://github.com/rahulps1000/heroku-buildpack-nodejs"
  },{
    "url": "heroku/python"
  }],
  "stack": "heroku-22"
}
