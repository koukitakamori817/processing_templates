# processing_templates

TODO: あみだくじをつくってみました。
ランダムで横線が引かれ、線をなぞっていきます。
ゴールしたらマウスをクリックすることでランダムに円が光ります。

## Installation
githubでkoukitakamori817/processing_templatesをforkする。



## Usage

TODO: 左クリックしながら線を引き、右クリックをおすと、円がランダムに光ります。

## Code review

TODO:
for (int i =0; i < 20; i++) {
    int num = int(random(1000))%6;
    line(50+num*150,50+i*35, 200+num*150, 50+i*35);
    
  }
  
  int[] player;
  player = new int[7];
  ｝
横線を配列にしてからランダムに出てくるコードを書いて横線がランダムになるように
 特に引用はしていません。

## License

ここではサンプルとしてMITライセンスの表示をしています．Creative commonsとかLGPLでもOKです．
[Githubのライセンシングを解説した記事](https://www.catch.jp/oss-license/2013/09/10/github/)は
とても参考になります(だいぶその時...2013か...からは改訂されてるけど)．

The processing application is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Test project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/processing_templates/blob/master/CODE_OF_CONDUCT.md).
