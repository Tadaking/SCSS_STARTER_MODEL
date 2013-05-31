SCSS_STARTER_MODEL
==================

This model contains base settings, and UI-settings in common use.

Requirement
==================
•sass 3.2
•compass 

sassディレクトリ内構成
==================
design_settings
->サイトデザインに利用する色や大きさの値、状態・イベントに応じた値を設定

site_styles
->サイトのスタイルを記述

ui_modules
->site_stylesで利用するextend元のスタイルが記述されている。
UIを追加するときは、ここに記述。

_mixin.scss
->globalに利用できる独自関数

_normalize.scss

application.scss
->すべての関連scssをインポート

