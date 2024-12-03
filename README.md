# RC-5
  
## 1.基本の使い方
起動後、メモリ番号が表示されている画面は「プレイ画面」  
メモリは01から99まである。  
使うメモリ番号に、必要な設定をしてそれを保存して、わかりやすい名前を付け、メモリ番号を呼び出して使う。
  
●各メモリに対する主な設定項目
|No|内容|設定場所|項目名|設定方法|
|--|--|--|--|--|
|1|BPMを指定|TEMPO|BPM|RHYTHM[TEMPO]ボタンを押し、TEMPOを表示し、[MEMORY/LOOP LEVEL]つまみを回す、またはRHYTHM[TEMPO]ボタンでタップ・テンポする。RHYTHM[TEMPO]ボタンを２秒以上長押しすると、初期値に戻る。|  
|2|バッキングトラックを再生する|BOSS TONE STUDIO|メモリ番号のフォルダに音声ファイルを置く|対応するファイル形式はWAV（44.1kHz、ステレオ32 ビット浮動小数点）|
|3|再生回数を１回か繰り返しか|LOOP|1SHOT|ONで１回再生、OFFで繰り返し再生|
|4|トラックの再生音量|LOOP|LEVEL|100から上下させる再生中に［ MEMORY/LOOP LEVEL］つまみを押し込んで回す。|
|5|リズムの再生音量|RHYTHM|LEVEL|100から上下させる|
|6|録音時、カウントインする|RHYTHM|REC COUNT|1MEASにすると鳴る|
|7|再生時、カウントインする|RHYTHM|PLAY COUNT|1MEASにすると鳴る|
|8|録音する小節数を指定する|LOOP|MEASURE|1～?64?MEAS|
|9|||||





|No|操作|内容|ディスプレイの色|
|--|--|--|--|
|1|MEMORY/LOOP LEVEL |押す||  
|2|MEMORY/LOOP LEVEL |回す||  
|3|TEMPO|押す|リズムのテンポ設定画面|  
|4|ON/OFF|押す|リズムのオン・オフ・待機|  
|5|SETUP|押す|全体設定|  
|6|MEMORY|押す|今の設定を保存するメモリー|  
  
|No|操作|内容|ディスプレイの色|
|--|--|--|--|
|1|MEMORY/LOOP LEVELノブを回す|メモリーを選ぶ|録音データが有れば青、無ければ白|  
|2|MEMORY/LOOP LEVELノブを押し込む|LOOP 音量設定。ノブを回して調節、押し込んで終了。|LOOP音量がフロート表示|  
|3|停止中に1回踏む|録音|赤点灯|
|4|録音中に1回踏む|再生|緑点灯|
|5|再生中に1回踏む|オーバーダビング|黄色点灯|
|6|再生中に2回踏む|停止||
|7|停止中に長く踏む|削除||
|8|再生中・オーバーダビング中に長く踏む|アンドゥ||
|9|アンドゥ後に長く踏む|リドゥ||
|||||  
  
※起動後、メモリ番号が表示されている画面は「プレイ画面」  
※停止のコツは、2回踏むにあたって、1回目は4拍目、2回目を次の小節の1拍目で踏む。  
※メモリーには、「トラック（録音）」と「リズム」の設定が保存される。  
  
|No|ディスプレイの色|状態|
|--|--|--|
|1|青点灯|フレーズなし|
|2|赤点灯|録音中|
|3|緑点灯|再生中|
|4|黄色点灯|オーバーダビング中|
|5|白点灯|フレーズあり|
||||
  
## 2. Tips
1. 録音時、カウントインする：「RHYTHM」のREC COUNT を1MEASに
2. 再生時、カウントインする：「RHYTHM」のPLAY COUNT を1MEASに
3. 録音時のみリズムを鳴らし、ループ再生時にはリズムを鳴らさない：「RHYTHM」のSTOPをREC ENDに
4. 録音する小節数を指定：「LOOP」のMEASURE を1MEAS～99MEASに
5. バッキングトラックを１回だけ再生して停止する（録音しない）：「LOOP」の1SHOT をONに
6. バッキングトラックに使える音声ファイル形式：WAV（44.1kHz、ステレオ32ビット浮動小数点）、１トラック最大約1.5時間、メモリー合計最大約13時間
  
## 3.設定の体系
1. TEMPO：BPM
2. メモリー：LOOP、RHYTHM、NAME
3. SETUP：GENERAL、CONTROL、MIDI、STORAGE、F.RESET
  
TEMPO の設定項目
|No|設定項目名|説明|
|--|--|--|
|1|TEMPO|RHYTHM[TEMPO]ボタンを押し、TEMPOを表示し、[MEMORY/LOOP LEVEL]つまみを回す、またはRHYTHM[TEMPO]ボタンでタップ・テンポする。RHYTHM[TEMPO]ボタンを２秒以上長押しすると、初期値に戻る。|
  
LOOP の設定項目
|No|設定項目名|説明|
|--|--|--|
|1|REVERSE|通常再生する（OFF）か、リバース再生する（ON）かを設定します。|
|2|1SHOT|ONにすると、トラックの先頭から最後までを一度だけ再生して、自動的に停止します（ワン・ショット再生）。再生中にペダル・スイッチを踏むと、トラックの先頭からもう一度再生が開始されます（リトリガー再生）。オーバーダビングはできません。|
|3|LEVEL|トラックの再生レベルを調節します。※再生中に［ MEMORY/LOOP LEVEL］つまみを押し込んで回すことでも調節することもできます。|
|4|REC ACTION|ペダル・スイッチを踏んだときの、録音の次に（再生／オーバーダビング）の切り替わる順番を設定します。|
|5|DUB MODE|オーバーダビングのしかたを設定します。OVERDUB（重ね録り）かREPLACE（上書き）かを選びます。|
|6|AUTO REC|OFF ではペダル・スイッチを踏んだ瞬間、録音が開始されますが、ON では、ペダル・スイッチを踏むと画面が録音待機状態の表示になり、演奏を開始すると画面が録音状態の表示に変わり、録音を開始します。|
|7|START|トラックの再生時、フェード・インしながら再生スタートさせるか、すぐに再生スタートさせるかを設定します。|
|8|STOP|ペダル・スイッチを踏んだときの、トラックの停止方法を設定します。すぐに停止、フェードアウト、ループの最後、の３種類。|
|9|FADE TIME|START を「FADE IN」またはSTOP を「FADE OUT」に設定している場合の、フェード・イン／アウトの時間を小節数で設定します。|
|10|MEASURE|トラックの小節数を設定します。リズム音に合わせて録音するときに、録音前にあらかじめ小節数を設定しておけば、録音終了時にスイッチ操作をしなくても設定した小節の長さでループします。|

RHYTHM の設定項目
|No|設定項目名|説明|
|--|--|--|
|1|LEVEL|リズムの音量を設定します。LOOPの音量とは独立している。|
|2|REVERB|リズムにかけるリバーブの深さを設定します。|
|3|PATTERN|リズム・パターンを選びます。|
|4|VARIATION|リズム・パターンのバリエーション（A またはＢ）を選びます。|
|5|VAR.CHANGE|リズム・パターンのバリエーションを切り替えるタイミングを設定します。小節の最後か、ループの最後か。|
|6|KIT|リズム再生に使うドラム・キットを選びます。|
|7|BEAT|リズムの拍子を設定します。※トラックを録音したあとで変更することはできません。必ず録音前に設定してください。|
|8|START|リズム再生の始めかたを設定します。|
|9|STOP|リズム再生の止めかたを設定します。|
|10|REC COUNT|録音時にカウント・インを鳴らすか鳴らさないかを設定します。※トラックやリズムが再生されているときは、カウント・インは鳴りません。|
|11|PLAY COUNT|再生時にカウント・インを鳴らすか鳴らさないかを設定します。|
|12|FILL|フィル・イン付きのリズム再生にする（ON）か、フィル・インなしのリズム再生にする（OFF）かを設定します。|
|13|PART1 〜4|ドラム・キットを構成する4 つのドラム音（PART1 〜4）について、ドラム音ごとに鳴らす（ON）か鳴らさない（OFF）かを設定します。|
|14|TONE LOW|リズム音の低域の音色を調節します。|
|15|TONE HIGH|リズム音の高域の音色を調節します。|
  
NAME の設定項目
|No|設定項目名|説明|
|--|--|--|
|1|NAME|英数12文字まで|

## 4.設定画面への入り方
1. ［RHYTHM TEMPO］ボタンを押す：TEMPO表示、タップ・テンポでTEMPOを設定する。
2. ［RHYTHM ON/OFF］ボタンを押す：リズムのオン（点灯）／オフ（消灯）／待機（点滅）を切り替え。
3. ［RHYTHM ON/OFF］ボタンを長押し：RHYTHMの設定画面へ。
4. ［SETUP］ボタンを押す：全体設定画面へ。
5. ［MEMORY］ボタンを押す：LOOP、RHYTHM、NAME設定画面へ。
6. ［SETUP］ボタンと［MEMORY］ボタンを同時押し：保存、削除する。
7. ［MEMORY/LOOP LEVEL］ノブを回す：メモリーを選択する。
8. ［MEMORY/LOOP LEVEL］ノブを押し込む：LOOP音量を設定する。
  
## 5. 参考になるページ
https://dreadrock.org/knowhow-boss-rc-5-loop-station-001/
### シナリオ１
練習用メトロノーム・プリセット BPM=100  
1-1. BPM=100の設定  
(1)「TEMPO」ボタンを押す。  
(2)「MEMORY/LOOP LEVEL」つまみを右か左に回して液晶画面下段に「100.0」を表示させる。  
(3) もう一度「TEMPO」ボタンを押すか、何もせずに３秒くらいすると元の画面に戻る。  
1-2. メトロノーム・リズムの設定  
(1) 「ON/OFF」ボタンを長く押す。  
(2) 液晶画面上段に「LEVEL」が表示される。「MEMORY/LOOP LEVEL」つまみを回して、液晶画面上段に「PATTERN」を表示させる。  
(3) 「MEMORY/LOOP LEVEL」つまみを押す。液晶画面左端の三角形が上段から下段に動く。  
(4) 「MEMORY/LOOP LEVEL」つまみを回して、液晶画面下段に「Metronome1」または「Metronome2」を表示させる。「Metronome1」と「Metronome2」の違いは、1泊目にチャイムが入っているかいないかの違い。  
(5) 「MEMORY/LOOP LEVEL」つまみを押す。液晶画面左端の三角形が下段から上段に動く。  
(6) 「MEMORY」ボタンを押す。  
(7) さらに「MEMORY」ボタンを押す。これで元の画面に戻る。  
1-3. 最初の録音の時のプリカウントの設定  
(1) 「ON/OFF」ボタンを長く押す。  
(2) 液晶画面上段に「LEVEL」が表示される。「MEMORY/LOOP LEVEL」つまみを回して、液晶画面上段に「REC COUNT」を表示させる。  
(3) 「MEMORY/LOOP LEVEL」つまみを押す。液晶画面左端の三角形が上段から下段に動く。  
(4) 「MEMORY/LOOP LEVEL」つまみを回して、液晶画面下段に「1 MEAS」を表示させる。  
(5) 「MEMORY/LOOP LEVEL」つまみを押す。液晶画面左端の三角形が下段から上段に動く。  
(6) 「MEMORY」ボタンを押す。  
(7) さらに「MEMORY」ボタンを押す。これで元の画面に戻る。  
1-4. プリセット名を設定する  
(1) 「MEMORY」ボタンを押す。  
(2)  液晶晶画面上段に「MEMORY」、液晶画面下段に「LOOP」が表示される。「MEMORY/LOOP LEVEL」つまみを回して、液晶画面下段に「NAME」を表示させて、「MEMORY/LOOP LEVEL」つまみを押す。  
(3)  液晶画面下段に「Memory01」が表示される。 「MEMORY/LOOP LEVEL」つまみを回すと、文字の下の下線が左右に動く。これがカーソルの位置。「MEMORY/LOOP LEVEL」つまみを押すと、カーソル位置の文字が反転する。この状態で「MEMORY/LOOP LEVEL」つまみを回すと、文字が変更される。 「MEMORY/LOOP LEVEL」つまみを押すと、反転文字が下線付きの文字に変わる。  
(4) これを繰り返して、プリセット名を決定する。（例えば、「Metro 100」）  
(5) 「MEMORY」ボタンを押す。  
(6) 「MEMORY」ボタンを押す。これで元の画面に戻る。元の画面でプリセット名が変更されている。  
1-5. 設定を保存する  
(1) 「SETUP」ボタンと「MEMORY」ボタンを両方押す。  
(2) 液晶画面上段に「UTILITY」、液晶画面下段に「WRITE」が表示される。「MEMORY/LOOP LEVEL」つまみを押す。  
(3) 液晶画面上段に「WRITE:01」、液晶画面下段に「Memory01」（＝1-4で設定する前のプリセット名）が表示される。「MEMORY/LOOP LEVEL」つまみを押す。  
(4) 液晶画面上段に「EXECUTING…」が表示され、数秒したら最初の画面に戻る。  
  
### シナリオ２
パフォーマンス用プリセット。リズムなしだが最初のループ録音時にはガイド用のメトロノームが鳴るように設定する。  
2-1. 1のプリセットをコピーする。  
(1) 「SETUP」ボタンと「MEMORY」ボタンを両方押す。  
(2) 液晶画面上段に「UTILITY」、液晶画面下段に「WRITE」が表示される。「MEMORY/LOOP LEVEL」つまみを押す。  
(3) 液晶画面上段に「WRITE:01」、液晶画面下段に「Metro 100」（＝1-4で設定して1-5で保存したプリセット名）が表示される。「MEMORY/LOOP LEVEL」つまみを回して、液晶画面上段に「WRITE:02」を表示させる。「MEMORY/LOOP LEVEL」つまみを押す。  
(4) 液晶画面上段に「EXECUTING…」が表示され、数秒したら最初の画面に戻る。  
2-2. ガイドのメトロノーム音を最初のループ録音が終了した後は鳴らないようにする。  
(1) 「ON/OFF」ボタンを長く押す。  
(2) 液晶画面上段に「LEVEL」が表示される。「MEMORY/LOOP LEVEL」つまみを回して、液晶画面上段に「STOP」を表示させて、 「MEMORY/LOOP LEVEL」つまみを押す。  
(3) 「MEMORY/LOOP LEVEL」つまみを回して、液晶画面下段に「REC END」を表示させて、 「MEMORY/LOOP LEVEL」つまみを押す。  
(4) 「MEMORY」ボタンを押す。  
(5) 「MEMORY」ボタンを押す。これで元の画面に戻る。  
2-3. プリセット名を設定する  
(1) 「MEMORY」ボタンを押す。  
(2)  液晶晶画面上段に「MEMORY」、液晶画面下段に「LOOP」が表示される。「MEMORY/LOOP LEVEL」つまみを回して、液晶画面下段に「NAME」を表示させる。  
(3) 「MEMORY/LOOP LEVEL」つまみを押すと、 液晶画面下段に「Metro 100」（＝1-4で設定して1-5で保存したプリセット名が表示される。「MEMORY/LOOP LEVEL」つまみを回すと、文字の下の下線が左右に動く。これがカーソルの位置。 「MEMORY/LOOP LEVEL」つまみを押すと、カーソルの位置の文字が反転する。この状態で「MEMORY/LOOP LEVEL」つまみを回すと、文字が変更される。「MEMORY/LOOP LEVEL」つまみを押すと、反転の文字が下線付きの文字に変わる。  
(4) これを繰り返して、プリセット名を決定する。（例えば、「Pefrm 100」）  
(5) 「MEMORY」ボタンを押す。  
(6) 「MEMORY」ボタンを押す。これで元の画面に戻る。  
2-4. 設定を保存する  
(1) 「SETUP」ボタンと「MEMORY」ボタンを両方押す。  
(2) 液晶画面上段に「UTILITY」、液晶画面下段に「WRITE」が表示される。「MEMORY/LOOP LEVEL」つまみを押す。  
(3) 液晶画面上段に「WRITE:02」、液晶画面下段に「Metro 100」が表示される。「MEMORY/LOOP LEVEL」つまみを押すと、液晶画面上段に「EXECUTING…」が表示され、数秒したら最初の画面に戻る。  
  
### シナリオ３
パフォーマンス用プリセット。リズムあり。  
3-1. 1のプリセットをコピーする。  
(1) 「MEMORY/LOOP LEVEL」つまみを回して、液晶画面左側に「01」、右上段に「Metro」、右下段に「100」を表示させる。  
(2) 「SETUP」ボタンと「MEMORY」ボタンを両方押す。  
(3) 液晶画面上段に「UTILITY」、液晶画面下段に「WRITE」が表示される。MEMORY/LOOP LEVEL」つまみを押す。  
(4) 液晶画面上段に「WRITE:01」、液晶画面下段に「Metro 100」が表示される。「MEMORY/LOOP LEVEL」つまみを回して、液晶画面上段に「WRITE:03」を表示させる。  
(5)「MEMORY/LOOP LEVEL」つまみを押すと、 液晶画面上段に「EXECUTING…」が表示され、数秒したら最初の画面に戻る。  
3-2. リズムを変更する。ここでは例としてRock1にしますが、お好みのリズムを選んでください。  
(1) 「ON/OFF」ボタンを長く押す。  
(2) 液晶画面上段に「LEVEL」が表示される。「MEMORY/LOOP LEVEL」つまみを回して、液晶画面上段に「PATTERN」を表示させる。  
(3) 「MEMORY/LOOP LEVEL」つまみを押すと、液晶画面左端の三角形が上段から下段に動く。  
(4) 「MEMORY/LOOP LEVEL」つまみを回して、液晶画面下段に「Rock1」を表示させ、「MEMORY/LOOP LEVEL」つまみを押す。  
(5) 「MEMORY」ボタンを押す。  
(6) 「MEMORY」ボタンを押す。これで元の画面に戻る。  
3-3. プリセット名を設定する  
3-4. 設定を保存する  
  