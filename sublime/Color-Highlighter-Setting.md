# Color Highlighter 세팅

참고: [Sublime Text Plugins](https://developers.google.com/web/shows/ttt/series-1/sublime-text-plugins?hl=en)

Color Highlighter에서 컬러가 더 보기 쉽게 해당 색으로 하이라이트하게 해주는 설정.

![Before]
(fill-before.png)

원래는 이렇게 표시 됨. 세팅을 하면...

![After]
(fill-after.png)

짜잔!

‘Preferences > Package Settings > Color Highlighter > Settings - User‘로 가서 다음을 입력

![Setting - User]
(fill-setting.png)

‘‘‘
{
  "ha_style": "filled"
}
‘‘‘

그리고 ‘Command + S‘로 저장한다.

CSS파일을 열어보면 컬러가 하이라이트 되어있는 아름다운 광경이 펼쳐진다.