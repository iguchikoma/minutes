# minutes

### google translateのinstall
http://www.questetra.com/ja/blog/cat-ambitions-ja/use-google-translate-api/

### keyの生成方法
https://cloud.google.com/translate/v2/getting_started?csw=1
public側で生成するとうまくいった

### google translateのsample API
https://www.googleapis.com/language/translate/v2?key=<取得したkey>&q="This is a car."&source=en&target=ja

'''json
{
  "data": {
    "translations": [
      {
        "translatedText": "「これは車です。」"
      }
    ]
  }
}
'''

### 音声系をpythonで扱えるようにする

