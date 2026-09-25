<!doctype html>
<html lang="ko">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#f8f6ef">
<title>일본어 첫걸음 · 하루 한 걸음</title>
<style>
:root{--bg:#f8f6ef;--paper:#fffef9;--ink:#22382e;--muted:#68736b;--line:#dce1d6;--green:#285744;--soft:#e8eee3;--orange:#c55637;--peach:#f9e5d7;--red:#a33232;--shadow:0 12px 32px #273c3010;--radius:22px;color-scheme:light}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:-apple-system,BlinkMacSystemFont,"Apple SD Gothic Neo","Noto Sans KR","Noto Sans JP",sans-serif;line-height:1.65;word-break:keep-all}
button,input,select{font:inherit}
button{cursor:pointer;color:inherit}
button:disabled{cursor:default;opacity:.45}
button,a,input,select{-webkit-tap-highlight-color:transparent}
button:focus-visible,a:focus-visible,input:focus-visible,select:focus-visible{outline:3px solid var(--orange);outline-offset:4px}
a{color:var(--green)}
button{touch-action:manipulation}
h1,h2,h3,p{margin-top:0}
h1{font-size:clamp(32px,5vw,54px);line-height:1.25;letter-spacing:-2px;margin-bottom:18px}
h2{font-size:25px;letter-spacing:-.8px;margin-bottom:8px}
h3{font-size:19px;margin-bottom:8px}
small,.small{font-size:13px}
.muted{color:var(--muted)}
.jp{font-family:"Hiragino Kaku Gothic ProN","Yu Gothic","Noto Sans JP","Noto Sans KR",sans-serif;word-break:normal}
.shell{max-width:1160px;margin:auto;padding:0 32px}
.topbar{border-bottom:1px solid var(--line);background:var(--bg)}
.brandrow{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:24px 0}
.brand{display:flex;align-items:center;gap:12px;font-weight:750;font-size:19px;letter-spacing:-.6px}
.brandmark{display:grid;place-items:center;background:var(--green);color:#fffef9;width:43px;height:43px;border-radius:14px;font-size:26px}
.brand small{display:block;font-size:10px;letter-spacing:2px;font-weight:600;color:var(--muted)}
.daily-pill{font-size:12px;border:1px solid var(--line);border-radius:50px;padding:7px 12px;white-space:nowrap}
.daily-pill b{color:var(--orange)}
nav{display:flex;gap:30px}
.navbtn{position:relative;background:none;border:0;padding:13px 1px 17px;color:var(--muted);font-weight:600}
.navbtn.active{color:var(--green)}
.navbtn.active:after{content:"";height:3px;border-radius:2px;position:absolute;bottom:0;left:0;right:0;background:var(--green)}
.navnum{font-size:10px;margin-right:6px;opacity:.65}
.main{padding-top:34px;padding-bottom:35px;min-height:65vh}
section[hidden]{display:none!important}
.main:focus{outline:none}
.eyebrow{font-size:11px;letter-spacing:2px;font-weight:700;text-transform:uppercase;color:var(--orange);margin-bottom:14px}
.hero{position:relative;display:grid;grid-template-columns:1.4fr 1fr;gap:35px;align-items:center;background:var(--soft);padding:40px 42px;border-radius:28px;overflow:hidden}
.hero p{max-width:470px;color:#4c6052;margin-bottom:22px}
.hero-art{position:relative;min-height:240px;display:flex;align-items:center;justify-content:center}
.sun{position:absolute;width:152px;height:152px;border-radius:50%;background:#d57852;right:28px;top:12px;opacity:.85}
.letter-card{position:relative;background:var(--paper);border:1px solid #ffffff;border-radius:16px;width:130px;height:166px;display:flex;flex-direction:column;align-items:center;justify-content:center;box-shadow:8px 14px 0 #21463214;transform:rotate(-11deg);z-index:1}
.letter-card span{font-size:82px;line-height:1.25}
.letter-card small{font-size:12px;letter-spacing:2px;color:var(--muted)}
.letter-card.second{transform:rotate(11deg);margin:55px 0 0 -12px}
.art-label{position:absolute;left:3px;bottom:-4px;font-size:10px;letter-spacing:2px}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;border:1px solid var(--line);padding:11px 18px;border-radius:12px;background:var(--paper);font-weight:600;min-height:46px;text-decoration:none}
.btn.primary{background:var(--green);color:#fffef9;border-color:var(--green)}
.btn.accent{background:var(--peach);border-color:var(--peach);color:#843f29}
.btn.small{font-size:13px;padding:8px 12px;min-height:40px}
.btn.ghost{background:transparent}
.btn:hover:not(:disabled){filter:brightness(.96);transform:translateY(-1px)}
.row{display:flex;gap:10px;align-items:center;flex-wrap:wrap}
.between{justify-content:space-between}
.stats{display:grid;grid-template-columns:1.2fr 1fr 1fr;gap:18px;margin:22px 0 38px}
.stat{display:flex;align-items:center;gap:15px;padding:20px;background:var(--paper);border:1px solid var(--line);border-radius:18px}
.stat strong{font-size:26px;line-height:1.1;font-weight:700}
.stat p{font-size:12px;margin:4px 0 0;color:var(--muted)}
.stat .bar{margin-top:9px;width:100%;min-width:80px}
.grow{flex:1}
.bar{height:5px;border-radius:10px;background:#dce4d5;overflow:hidden}
.bar>span{display:block;height:100%;background:var(--green);border-radius:inherit;transition:width .25s}
.sectionhead{display:flex;justify-content:space-between;align-items:end;gap:15px;margin-bottom:19px}
.sectionhead p{margin:0;color:var(--muted);font-size:14px}
.sectionhead h2{margin-bottom:4px}
.tag{background:var(--soft);color:var(--green);border-radius:7px;padding:4px 8px;font-size:11px;white-space:nowrap}
.coursegrid{display:grid;grid-template-columns:repeat(3,1fr);gap:15px}
.course{display:flex;flex-direction:column;align-items:flex-start;position:relative;text-align:left;border:1px solid var(--line);background:var(--paper);border-radius:19px;padding:22px;min-height:182px;transition:.15s}
.course:hover{border-color:#81937e;box-shadow:var(--shadow);transform:translateY(-3px)}
.course .number{font-size:12px;letter-spacing:1px;color:var(--muted)}
.course h3{margin:20px 0 6px;font-size:17px}
.course p{margin:0;font-size:13px;color:var(--muted)}
.course .preview{position:absolute;top:19px;right:20px;font-size:24px;color:var(--green)}
.course .done{font-size:11px;color:var(--green);margin-left:8px}
.course.next{border-color:var(--green)}
.callout{background:var(--peach);border-radius:15px;padding:17px 20px;font-size:14px;margin:23px 0}
.callout p:last-child{margin-bottom:0}
.panel{background:var(--paper);border:1px solid var(--line);border-radius:var(--radius);padding:26px}
.lesson-top{margin:21px 0}
.lesson-top h1{font-size:36px;margin-bottom:10px}
.lesson-layout{display:grid;grid-template-columns:minmax(0,1fr) 255px;gap:22px;align-items:start}
.lesson-body{display:grid;gap:18px}
.lesson-body p{font-size:15px;color:#46584c}
.lesson-body ul{padding-left:21px;font-size:15px}
.lesson-body li{margin:8px 0}
.lesson-body .note{font-size:13px;border-left:3px solid #d88b62;padding-left:12px;color:var(--muted);margin:16px 0 0}
.example{padding:16px 0;border-bottom:1px solid var(--line)}
.example:last-child{border-bottom:none;padding-bottom:0}
.example:first-child{padding-top:0}
.example-top{display:flex;align-items:center;justify-content:space-between;gap:14px}
.example .jp{font-size:22px;font-weight:550;line-height:1.5}
.example .reading{font-size:12px;color:var(--orange);margin-top:5px}
.example .meaning{font-size:14px;margin-top:5px}
.sound{display:inline-flex;align-items:center;justify-content:center;flex-shrink:0;min-width:42px;min-height:42px;border:1px solid var(--line);border-radius:50%;background:var(--paper);color:var(--green)}
.sound svg{width:18px;height:18px}
.side-panel{position:sticky;top:20px}
.side-panel .jp{font-size:52px;display:block;margin:10px 0}
.side-panel p{font-size:13px}
.side-links{display:grid;gap:9px;margin-top:20px}
.mini-quiz{padding:20px;background:#f0f3eb;border-radius:17px}
.mini-quiz p{margin-bottom:12px;font-weight:600;color:var(--ink)}
.choices{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.choice{border:1px solid var(--line);background:var(--paper);border-radius:12px;padding:13px 14px;text-align:left;min-height:51px;overflow-wrap:anywhere}
.choice:hover:not(:disabled){border-color:var(--green);background:var(--soft)}
.choice.correct{border-color:var(--green);background:#e0eede;color:#204931}
.choice.wrong{border-color:var(--red);background:#fbe3df;color:var(--red)}
.choice:disabled{opacity:1}
.feedback{font-size:14px;margin-top:12px}
.feedback:empty{display:none}
.lesson-actions{margin-top:25px;padding-top:20px;border-top:1px solid var(--line)}
.toolbar{display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin:18px 0}
.segmented{display:inline-flex;padding:4px;border:1px solid var(--line);background:#eeeee5;border-radius:12px;gap:4px;flex-wrap:wrap}
.segmented button{background:transparent;border:0;border-radius:8px;padding:8px 15px;font-size:14px;min-height:42px}
.segmented button.active{background:var(--paper);box-shadow:0 2px 5px #0000000a;font-weight:650;color:var(--green)}
.switch{display:flex;align-items:center;gap:7px;font-size:13px;cursor:pointer}
.switch input{width:18px;height:18px;accent-color:var(--green)}
.kana-layout{display:grid;grid-template-columns:minmax(0,1fr) 270px;gap:24px;align-items:start}
.kana-grid{display:grid;grid-template-columns:repeat(5,minmax(0,1fr));gap:9px}
.kana-cell{border:1px solid var(--line);background:var(--paper);border-radius:12px;padding:13px 4px;min-height:92px;display:flex;flex-direction:column;align-items:center;justify-content:center}
.kana-cell .jp{font-size:32px;line-height:1.3}
.kana-cell small{color:var(--muted);font-size:12px;margin-top:4px}
.kana-cell.active{border-color:var(--green);background:var(--soft)}
.kana-cell.known:after{content:"✓";font-size:10px;color:var(--green);position:absolute;top:3px;right:7px}
.kana-cell{position:relative}
.kana-gap{visibility:hidden}
.kana-detail{text-align:center;position:sticky;top:24px}
.big-kana{font-size:96px;line-height:1.45}
.kana-detail .reading{font-size:21px;font-weight:650;color:var(--orange)}
.kana-detail .description{font-size:13px;color:var(--muted);min-height:40px}
.kana-detail .row{justify-content:center}
.subhead{font-size:13px;color:var(--muted);margin-bottom:12px}
.yoon .kana-cell .jp{font-size:25px}
.yoon{grid-template-columns:repeat(3,minmax(0,1fr))}
{title:'히라가나 ②',desc:'は행부터 ん까지',glyph:'は ん',time:12,goal:'나머지 기본 히라가나를 읽고 짧은 단어를 완성해요.',body:()=>
panel('나머지 기본 글자','<p>이번에는 は행부터 마지막 ん까지 익혀요. や행과 わ행에는 빈칸이 있다는 것도 기억하세요.</p>'+ex('は ひ ふ へ ほ','ha · hi · fu · he · ho','하 · 히 · 후 · 헤 · 호')+ex('ま み む め も','ma · mi · mu · me · mo','마 · 미 · 무 · 메 · 모')+ex('や ゆ よ','ya · yu · yo','야 · 유 · 요')+ex('ら り る れ ろ','ra · ri · ru · re · ro','라 · 리 · 루 · 레 · 로')+ex('わ を ん','wa · o(wo) · n','와 · 오 · ㄴ')+'<p class="note">ふ(fu)는 두 입술 사이로 가볍게 바람을 내는 소리예요. を는 현대 일본어에서 주로 조사로 쓰며 보통 o로 읽어요.</p>')+
panel('조사에서 달라지는 읽기','<p>글자 모양과 실제 읽기가 달라지는 대표적인 조사가 있어요. 문장을 배울 때 다시 만납니다.</p>'+ex('は','wa · 와','조사로 쓰일 때 wa')+ex('へ','e · 에','방향 조사로 쓰일 때 e')+ex('を','o · 오','목적어를 나타내는 조사')),
qs:[question('조사로 쓰인 「は」는 어떻게 읽을까요?','wa',['ha','wa','pa'],'단어 안에서는 ha지만, 주제를 나타내는 조사 は는 wa로 읽어요.'),question('「を」의 일반적인 조사 발음은?','o',['wo','o','yo'],'표기는 を지만 현대 표준어에서는 보통 o로 읽어요.')]},

{title:'작은 글자와 긴 소리',desc:'탁음 · 요음 · 촉음 · 장음',glyph:'きゃ',time:12,goal:'작은 글자와 소리 변화가 단어의 발음을 어떻게 바꾸는지 알아요.',body:()=>
panel('점 두 개와 동그라미','<p>글자 오른쪽 위에 <b>゛</b>가 붙으면 소리가 탁해지고, は행에 <b>゜</b>가 붙으면 p 소리가 납니다.</p>'+ex('か → が','ka → ga','카 → 가')+ex('さ → ざ','sa → za','사 → 자')+ex('た → だ','ta → da','타 → 다')+ex('は → ば → ぱ','ha → ba → pa','하 → 바 → 파'))+
panel('작은 ゃ・ゅ・ょ','<p>い단 글자 뒤에 작은 ゃ・ゅ・ょ가 오면 두 글자를 한 박자처럼 이어 읽어요.</p>'+ex('きゃ','kya · 캬','き + 작은 ゃ')+ex('しゅ','shu · 슈','し + 작은 ゅ')+ex('ちょ','cho · 초','ち + 작은 ょ'))+
panel('작은 っ과 긴 소리','<p>작은 <b>っ</b>는 다음 자음 앞에서 한 박자 멈추는 느낌이에요. 가타카나의 <b>ー</b>는 앞 모음을 길게 늘여요.</p>'+ex('きって','kitte · 킷테','우표')+ex('がっこう','gakkō · 각코오','학교')+ex('コーヒー','kōhī · 코오히이','커피')+'<p class="note">きて(kite, 와서)와 きって(kitte, 우표)는 소리 길이가 달라요. 작은 っ을 빠뜨리지 마세요.</p>'),
qs:[question('「きゃ」는 어떻게 읽을까요?','kya',['kiya','kya','ka'],'작은 ゃ는 앞 글자와 합쳐 한 박자로 읽어요.'),question('「きって」의 작은 っ은 무엇을 나타낼까요?','다음 자음 앞의 짧은 멈춤',['긴 모음','다음 자음 앞의 짧은 멈춤','문장의 끝'],'작은 っ은 뒤 자음을 겹쳐 발음하는 촉음을 나타내요.')]},

{title:'가타카나 시작하기',desc:'익숙한 외래어 읽기',glyph:'カナ',time:10,goal:'히라가나와 같은 소리 체계를 가진 가타카나를 익숙한 단어로 읽어요.',body:()=>
panel('소리는 같고 모양은 달라요','<p>가타카나도 히라가나와 같은 기본 소리를 사용해요. 외래어, 외국 이름, 의성어 등에 자주 보입니다.</p>'+ex('ア イ ウ エ オ','a · i · u · e · o','아 · 이 · 우 · 에 · 오')+ex('カ キ ク ケ コ','ka · ki · ku · ke · ko','카 · 키 · 쿠 · 케 · 코')+ex('サ シ ス セ ソ','sa · shi · su · se · so','사 · 시 · 스 · 세 · 소'))+
panel('이미 아는 말부터','<p>한국어에서도 익숙한 외래어를 먼저 읽으면 가타카나가 훨씬 빨리 눈에 들어와요.</p>'+ex('コーヒー','kōhī · 코오히이','커피')+ex('ホテル','hoteru · 호테루','호텔')+ex('バス','basu · 바스','버스')+ex('テレビ','terebi · 테레비','텔레비전')+ex('レストラン','resutoran · 레스토란','레스토랑')),
qs:[question('「ホテル」의 뜻은?','호텔',['버스','호텔','커피'],'ホテル(hoteru)는 호텔이에요.'),question('가타카나의 「ア」와 히라가나 「あ」의 기본 소리는?','둘 다 a',['둘 다 a','ア만 a','あ만 a'],'두 문자는 모양은 다르지만 기본 소리 체계는 같아요.')]},

{title:'첫 인사 나누기',desc:'인사 · 감사 · 사과',glyph:'こんにちは',time:10,goal:'만나고 헤어질 때 쓰는 기본 인사를 상황에 맞게 말해요.',body:()=>
panel('만났을 때','<p>처음에는 통째로 익혀도 좋아요. 듣기 버튼을 누르고 자연스러운 속도로 따라 말해 보세요.</p>'+ex('おはようございます','ohayō gozaimasu · 오하요오 고자이마스','안녕하세요 / 좋은 아침입니다')+ex('こんにちは','konnichiwa · 곤니치와','안녕하세요')+ex('こんばんは','konbanwa · 곤방와','안녕하세요 / 좋은 저녁입니다'))+
panel('감사와 사과',ex('ありがとうございます','arigatō gozaimasu · 아리가토오 고자이마스','감사합니다')+ex('すみません','sumimasen · 스미마센','실례합니다 / 죄송합니다 / 저기요')+ex('ごめんなさい','gomennasai · 고멘나사이','미안합니다'))+
panel('헤어질 때',ex('じゃあ、また。','jā, mata · 자아, 마타','그럼, 또 봐요.')+ex('おやすみなさい','oyasuminasai · 오야스미나사이','안녕히 주무세요')+'<p class="note">さようなら도 ‘안녕히 가세요’라는 뜻이지만 일상에서는 상황에 따라 またね, じゃあ、また 등을 더 자주 쓰기도 해요.</p>'),
qs:[question('감사합니다에 해당하는 표현은?','ありがとうございます',['すみません','ありがとうございます','こんばんは'],'ありがとうございます는 정중한 감사 표현이에요.'),question('「すみません」으로 할 수 없는 것은?','축하하기',['사과하기','사람 부르기','축하하기'],'すみません은 사과, 양해, 사람을 부를 때 등에 널리 쓰여요.')]},

{title:'“저는 학생입니다”',desc:'AはBです · 질문 · 부정',glyph:'です',time:12,goal:'자기소개에 필요한 가장 기본적인 명사 문장을 만들어요.',body:()=>
panel('A는 B입니다','<p><b>A は B です</b>는 “A는 B입니다”라는 기본 문형이에요. 여기서 조사 は는 <b>wa</b>로 읽습니다.</p>'+ex('わたしは がくせいです。','watashi wa gakusei desu · 와타시와 가쿠세이데스','저는 학생입니다.')+ex('わたしは かんこくじんです。','watashi wa kankokujin desu · 와타시와 칸코쿠진데스','저는 한국인입니다.'))+
panel('질문하기','<p>문장 끝에 <b>か</b>를 붙이면 정중한 질문이 됩니다.</p>'+ex('がくせいですか。','gakusei desu ka · 가쿠세이데스카','학생입니까?')+ex('はい、そうです。','hai, sō desu · 하이, 소오데스','네, 그렇습니다.')+ex('いいえ、ちがいます。','iie, chigaimasu · 이이에, 치가이마스','아니요, 아닙니다.'))+
panel('아닙니다','<p>명사의 정중한 부정은 <b>ではありません</b>을 쓰면 됩니다. 회화에서는 じゃありません도 많이 써요.</p>'+ex('せんせいではありません。','sensei dewa arimasen · 센세이데와 아리마센','선생님이 아닙니다.')),
qs:[question('「わたしは がくせいです。」의 뜻은?','저는 학생입니다.',['저는 선생님입니다.','저는 학생입니다.','학생입니까?'],'わたし는 저, がくせい는 학생이에요.'),question('정중한 질문을 만들 때 문장 끝에 붙이는 것은?','か',['の','か','を'],'ですか처럼 か를 붙이면 질문이 돼요.')]},

{title:'이것·그것과 “~의”',desc:'これ・それ・あれ · の',glyph:'これ',time:11,goal:'물건을 가리키고 누구의 것인지 간단히 말해요.',body:()=>
panel('거리로 구분해요','<p><b>これ</b>는 말하는 사람 가까이, <b>それ</b>는 듣는 사람 가까이, <b>あれ</b>는 둘 다에게서 먼 것을 가리켜요.</p>'+ex('これは ほんです。','kore wa hon desu · 코레와 혼데스','이것은 책입니다.')+ex('それは なんですか。','sore wa nan desu ka · 소레와 난데스카','그것은 무엇입니까?')+ex('あれは ホテルです。','are wa hoteru desu · 아레와 호테루데스','저것은 호텔입니다.'))+
panel('の = ~의','<p><b>A の B</b>는 “A의 B”처럼 소유나 관계를 나타냅니다.</p>'+ex('わたしの ほん','watashi no hon · 와타시노 혼','제 책')+ex('にほんの コーヒー','nihon no kōhī · 니혼노 코오히이','일본의 커피')+ex('これは わたしの ほんです。','kore wa watashi no hon desu · 코레와 와타시노 혼데스','이것은 제 책입니다.')),
qs:[question('말하는 사람 가까이에 있는 “이것”은?','これ',['これ','それ','あれ'],'これ는 화자 가까이에 있는 것을 가리켜요.'),question('「わたしの ほん」의 뜻은?','제 책',['제 가방','제 책','일본 책'],'の는 “~의”라는 관계를 나타내요.')]},
{title:'문장을 연결하는 조사',desc:'を · で · に · へ · と',glyph:'を で',time:12,goal:'목적어·행동 장소·이동 방향을 구분해 말해요.',body:()=>
panel('を: 무엇을 하나요?',ex('パンを食べます。','パンを たべます · pan o tabemasu','빵을 먹습니다.')+ex('水を飲みます。','みずを のみます · mizu o nomimasu','물을 마십니다.')+'<p class="note">を는 여기서 행동의 대상을 나타내고 o로 읽어요. 일본어는 대체로 “무엇을 + 동사” 순서예요.</p>')+
panel('で: 어디에서 행동하나요?',ex('カフェで勉強します。','カフェで べんきょうします · kafe de benkyō shimasu','카페에서 공부합니다.'))+
panel('に / へ: 어디로 가나요?',ex('学校に行きます。','がっこうに いきます · gakkō ni ikimasu','학교에 갑니다. 도착점을 나타내요.')+ex('日本へ行きます。','にほんへ いきます · nihon e ikimasu','일본으로 갑니다. 방향을 나타내며 へ는 e예요.'))+
panel('と: 누구와 함께 하나요?',ex('友だちと行きます。','ともだちと いきます · tomodachi to ikimasu','친구와 갑니다.')+'<p class="note">조사는 뜻이 여러 가지예요. 여기서는 기본 용법만 익혀요. “집에 있어요” 같은 존재의 장소는 で가 아니라 に를 써요.</p>'),
qs:[question('「水＿飲みます」의 빈칸에 들어갈 조사는?','を',['で','を','へ'],'마시는 대상인 물 뒤에는 を를 써요.'),question('「カフェ＿勉強します」의 빈칸에 들어갈 조사는?','で',['で','を','の'],'공부라는 행동이 일어나는 장소에는 で를 써요.')]},

{title:'동사로 일상 말하기',desc:'ます · ません · ました',glyph:'ます',time:12,goal:'공손한 동사형으로 긍정·부정·과거를 말해요.',body:()=>
panel('먼저 ます형으로 외워요',ex('食べます','たべます · tabemasu','먹습니다 / 먹어요')+ex('飲みます','のみます · nomimasu','마십니다 / 마셔요')+ex('行きます','いきます · ikimasu','갑니다 / 가요')+ex('勉強します','べんきょうします · benkyō shimasu','공부합니다 / 공부해요')+'<p class="note">ます형은 습관·현재의 일반적인 일이나 미래 행동에 쓸 수 있어요. “지금 먹는 중”이라는 진행은 별도 표현을 배워야 해요.</p>')+
panel('끝부분을 바꿔 보세요',ex('食べます。','tabemasu','먹어요.')+ex('食べません。','tabemasen','먹지 않아요.')+ex('食べました。','tabemashita','먹었어요.')+ex('食べませんでした。','tabemasen deshita','먹지 않았어요.')+'<p class="note">이미 ます형인 동사에서 끝을 바꾸는 연습이에요. 사전형에서 ます형으로 바꾸는 방법은 동사 그룹별로 달라요.</p>')+
panel('시간을 붙여 내 일상으로',ex('毎日、日本語を勉強します。','まいにち、にほんごを べんきょうします · mainichi, nihongo o benkyō shimasu','매일 일본어를 공부합니다.')+ex('昨日、パンを食べました。','きのう、パンを たべました · kinō, pan o tabemashita','어제 빵을 먹었습니다.')),
qs:[question('“먹지 않아요”는?','食べません。',['食べました。','食べません。','食べます。'],'ます → ません으로 바꾸면 공손한 부정형이에요.'),question('“어제 물을 마셨습니다”에 맞는 끝부분은?','飲みました。',['飲みます。','飲みません。','飲みました。'],'완료된 과거의 행동은 ました로 말해요.')]},

{title:'숫자와 가격 읽기',desc:'0~99 · 엔 · 개수',glyph:'いち',time:12,goal:'기본 숫자를 읽고 가격과 수량을 물어봐요.',body:()=>
panel('기본 숫자 0부터 10까지',ex('ゼロ・いち・に・さん・よん','zero · ichi · ni · san · yon','0 · 1 · 2 · 3 · 4')+ex('ご・ろく・なな・はち・きゅう・じゅう','go · roku · nana · hachi · kyū · jū','5 · 6 · 7 · 8 · 9 · 10')+'<p class="note">4는 し, 7은 しち, 9는 く라고도 읽어요. 처음에는 よん・なな・きゅう부터 익히고 시간·날짜 등에서 달라지는 읽기는 따로 배워요.</p>')+
panel('11~99는 조합하면 돼요',ex('じゅういち','jūichi','11: 10 + 1')+ex('にじゅう','nijū','20: 2 × 10')+ex('にじゅうさん','nijūsan','23: 2 × 10 + 3')+ex('きゅうじゅうきゅう','kyūjūkyū','99: 9 × 10 + 9'))+
panel('가격을 묻고 수량 말하기',ex('いくらですか。','ikura desu ka · 이쿠라 데스카','얼마인가요?')+ex('五百円です。','ごひゃくえんです · gohyaku en desu','500엔입니다.')+ex('ひとつ・ふたつ・みっつ','hitotsu · futatsu · mittsu','한 개 · 두 개 · 세 개')+'<p class="note">숫자를 그냥 읽는 것과 물건 개수를 세는 것은 달라요. 주문할 때는 ひとつ・ふたつ 등을 써 볼 수 있어요. 300은 さんびゃく, 600은 ろっぴゃく, 800은 はっぴゃく처럼 소리가 달라져요.</p>'),
qs:[question('「にじゅうさん」은 몇인가요?','23',['13','23','32'],'に(2) × じゅう(10) + さん(3) = 23이에요.'),question('가격을 물을 때 하는 말은?','いくらですか。',['何ですか。','いくらですか。','学生ですか。'],'いくら는 가격을 묻는 “얼마”예요.')]},

{title:'처음 하는 실전 대화',desc:'자기소개 · 카페 주문',glyph:'話す',time:10,goal:'배운 표현을 연결해 짧은 대화 두 개를 해 봐요.',body:()=>
panel('대화 ① 처음 만났을 때',ex('はじめまして。','hajimemashite · 하지메마시테','처음 뵙겠습니다.')+ex('わたしはミンです。','watashi wa Min desu','저는 민입니다. ミン 자리에 본인 이름을 넣어 보세요.')+ex('韓国人です。','かんこくじんです · kankokujin desu','한국인입니다.')+ex('よろしくお願いします。','yoroshiku onegaishimasu','잘 부탁드립니다.'))+
panel('대화 ② 카페에서',ex('すみません。','sumimasen','손님: 실례합니다.')+ex('コーヒーをひとつください。','kōhī o hitotsu kudasai','손님: 커피 한 잔 주세요.')+ex('はい。五百円です。','hai. gohyaku en desu','직원: 네. 500엔입니다.')+ex('ありがとうございます。','arigatō gozaimasu','손님: 감사합니다.')+'<p class="note">명사 + をください는 “~을 주세요”라는 뜻이에요. ひとつ는 여기서 주문 수량을 말해요. 잔을 세는 전용 표현 一杯(いっぱい)도 나중에 배워 보세요.</p>')+
panel('잘 못 들었을 때도 괜찮아요',ex('もう一度お願いします。','もういちど おねがいします · mō ichido onegaishimasu','다시 한 번 부탁드립니다.')+ex('ゆっくり話してください。','ゆっくり はなしてください · yukkuri hanashite kudasai','천천히 말해 주세요.')+'<p class="note">마지막 문장은 통째로 익혀 두세요. 동사의 て형은 이 입문 과정을 마친 뒤에 배울 내용이에요.</p>')+
panel('다음 공부로 이어 가기','<ul><li>히라가나·가타카나를 순서 없이도 읽어 보세요.</li><li>い형용사·な형용사, 동사 그룹과 て형을 이어서 배워요.</li><li>매일 짧은 문장 3개를 만들고 소리 내어 읽어요.</li></ul>'),
qs:[question('커피 하나를 주문하는 문장은?','コーヒーをひとつください。',['コーヒーは学生です。','コーヒーをひとつください。','コーヒーに行きます。'],'물건 + を + 수량 + ください로 주문할 수 있어요.'),question('잘 못 들어서 다시 말해 달라고 하려면?','もう一度お願いします。',['はじめまして。','もう一度お願いします。','ありがとうございます。'],'もう一度는 “다시 한 번”이라는 뜻이에요.')]}
];

// [히라가나, 가타카나, 로마자, 한글 근사 발음]. 빈칸은 현대 기본표에서 쓰지 않는 자리.
const BASE=[
['あ','ア','a','아'],['い','イ','i','이'],['う','ウ','u','우'],['え','エ','e','에'],['お','オ','o','오'],
['か','カ','ka','카'],['き','キ','ki','키'],['く','ク','ku','쿠'],['け','ケ','ke','케'],['こ','コ','ko','코'],
['さ','サ','sa','사'],['し','シ','shi','시'],['す','ス','su','스'],['せ','セ','se','세'],['そ','ソ','so','소'],
['た','タ','ta','타'],['ち','チ','chi','치'],['つ','ツ','tsu','츠'],['て','テ','te','테'],['と','ト','to','토'],
['な','ナ','na','나'],['に','ニ','ni','니'],['ぬ','ヌ','nu','누'],['ね','ネ','ne','네'],['の','ノ','no','노'],
['は','ハ','ha','하'],['ひ','ヒ','hi','히'],['ふ','フ','fu','후'],['へ','ヘ','he','헤'],['ほ','ホ','ho','호'],
['ま','マ','ma','마'],['み','ミ','mi','미'],['む','ム','mu','무'],['め','メ','me','메'],['も','モ','mo','모'],
['や','ヤ','ya','야'],null,['ゆ','ユ','yu','유'],null,['よ','ヨ','yo','요'],
['ら','ラ','ra','라'],['り','リ','ri','리'],['る','ル','ru','루'],['れ','レ','re','레'],['ろ','ロ','ro','로'],
['わ','ワ','wa','와'],null,null,null,['を','ヲ','o','오'],['ん','ン','n','응/ㄴ']
];

const DAKU=[
['が','ガ','ga','가'],['ぎ','ギ','gi','기'],['ぐ','グ','gu','구'],['げ','ゲ','ge','게'],['ご','ゴ','go','고'],
['ざ','ザ','za','자'],['じ','ジ','ji','지'],['ず','ズ','zu','즈'],['ぜ','ゼ','ze','제'],['ぞ','ゾ','zo','조'],
['だ','ダ','da','다'],['ぢ','ヂ','ji','지'],['づ','ヅ','zu','즈'],['で','デ','de','데'],['ど','ド','do','도'],
['ば','バ','ba','바'],['び','ビ','bi','비'],['ぶ','ブ','bu','부'],['べ','ベ','be','베'],['ぼ','ボ','bo','보'],
['ぱ','パ','pa','파'],['ぴ','ピ','pi','피'],['ぷ','プ','pu','푸'],['ぺ','ペ','pe','페'],['ぽ','ポ','po','포']
];

const YOON=[
['きゃ','キャ','kya','캬'],['きゅ','キュ','kyu','큐'],['きょ','キョ','kyo','쿄'],
['しゃ','シャ','sha','샤'],['しゅ','シュ','shu','슈'],['しょ','ショ','sho','쇼'],
['ちゃ','チャ','cha','차'],['ちゅ','チュ','chu','추'],['ちょ','チョ','cho','초'],
['にゃ','ニャ','nya','냐'],['にゅ','ニュ','nyu','뉴'],['にょ','ニョ','nyo','뇨'],
['ひゃ','ヒャ','hya','햐'],['ひゅ','ヒュ','hyu','휴'],['ひょ','ヒョ','hyo','효'],
['みゃ','ミャ','mya','먀'],['みゅ','ミュ','myu','뮤'],['みょ','ミョ','myo','묘'],
['りゃ','リャ','rya','랴'],['りゅ','リュ','ryu','류'],['りょ','リョ','ryo','료'],
['ぎゃ','ギャ','gya','갸'],['ぎゅ','ギュ','gyu','규'],['ぎょ','ギョ','gyo','교'],
['じゃ','ジャ','ja','자'],['じゅ','ジュ','ju','주'],['じょ','ジョ','jo','조'],
['びゃ','ビャ','bya','뱌'],['びゅ','ビュ','byu','뷰'],['びょ','ビョ','byo','뵤'],
['ぴゃ','ピャ','pya','퍄'],['ぴゅ','ピュ','pyu','퓨'],['ぴょ','ピョ','pyo','표']
];

const WORDS=[
['こんにちは','こんにちは','konnichiwa','안녕하세요 (낮)','인사'],
['おはようございます','おはようございます','ohayō gozaimasu','좋은 아침입니다','인사'],
['こんばんは','こんばんは','konbanwa','안녕하세요 (저녁)','인사'],
['ありがとうございます','ありがとうございます','arigatō gozaimasu','감사합니다','인사'],
['すみません','すみません','sumimasen','실례합니다 / 죄송합니다','인사'],
['はじめまして','はじめまして','hajimemashite','처음 뵙겠습니다','인사'],
['はい','はい','hai','네','인사'],
['いいえ','いいえ','iie','아니요','인사'],
['おやすみなさい','おやすみなさい','oyasuminasai','안녕히 주무세요','인사'],
['よろしくお願いします','よろしくおねがいします','yoroshiku onegaishimasu','잘 부탁드립니다','인사'],
['わたし','わたし','watashi','나 / 저','사람'],['友だち','ともだち','tomodachi','친구','사람'],['先生','せんせい','sensei','선생님','사람'],['学生','がくせい','gakusei','학생','사람'],['家族','かぞく','kazoku','가족','사람'],['母','はは','haha','(남에게 말하는) 우리 어머니','사람'],['父','ちち','chichi','(남에게 말하는) 우리 아버지','사람'],['韓国人','かんこくじん','kankokujin','한국인','사람'],
['本','ほん','hon','책','일상'],['学校','がっこう','gakkō','학교','일상'],['駅','えき','eki','역','일상'],['家','いえ','ie','집','일상'],['店','みせ','mise','가게','일상'],['日本語','にほんご','nihongo','일본어','일상'],['今日','きょう','kyō','오늘','일상'],['明日','あした','ashita','내일','일상'],['昨日','きのう','kinō','어제','일상'],['毎日','まいにち','mainichi','매일','일상'],['猫','ねこ','neko','고양이','일상'],['犬','いぬ','inu','개','일상'],['花','はな','hana','꽃','일상'],['山','やま','yama','산','일상'],
['水','みず','mizu','물','음식'],['お茶','おちゃ','ocha','차 (음료)','음식'],['ご飯','ごはん','gohan','밥 / 식사','음식'],['パン','パン','pan','빵','음식'],['コーヒー','コーヒー','kōhī','커피','음식'],['牛乳','ぎゅうにゅう','gyūnyū','우유','음식'],['肉','にく','niku','고기','음식'],['魚','さかな','sakana','생선 / 물고기','음식'],['卵','たまご','tamago','달걀','음식'],['りんご','りんご','ringo','사과','음식'],['すし','すし','sushi','초밥','음식'],['ラーメン','ラーメン','rāmen','라멘','음식'],
['食べます','たべます','tabemasu','먹어요','동사'],['飲みます','のみます','nomimasu','마셔요','동사'],['行きます','いきます','ikimasu','가요','동사'],['来ます','きます','kimasu','와요','동사'],['帰ります','かえります','kaerimasu','돌아가요 / 돌아와요','동사'],['見ます','みます','mimasu','봐요','동사'],['聞きます','ききます','kikimasu','들어요 / 물어요','동사'],['読みます','よみます','yomimasu','읽어요','동사'],['書きます','かきます','kakimasu','써요','동사'],['話します','はなします','hanashimasu','말해요','동사'],['買います','かいます','kaimasu','사요','동사'],['勉強します','べんきょうします','benkyō shimasu','공부해요','동사'],
['これ','これ','kore','이것','기본 표현'],['それ','それ','sore','그것','기본 표현'],['あれ','あれ','are','저것','기본 표현'],['いくら','いくら','ikura','얼마','기본 표현'],['ひとつ','ひとつ','hitotsu','한 개','기본 표현'],['ふたつ','ふたつ','futatsu','두 개','기본 표현'],['もう一度','もういちど','mō ichido','다시 한 번','기본 표현'],['ゆっくり','ゆっくり','yukkuri','천천히','기본 표현']
].map((v,i)=>({id:'w'+i,ja:v[0],kana:v[1],roma:v[2],ko:v[3],cat:v[4]}));

const ALL_KANA=[...BASE.filter(Boolean),...DAKU,...YOON];
const Q_BANK=[];

for(let t=0;t<2;t++)for(const k of ALL_KANA){
Q_BANK.push({
id:'k'+t+'-'+k[0],
type:t?'katakana':'hiragana',
prompt:k[t],
answer:k[2]+' · '+k[3],
explanation:k[t]+' → '+k[2]+' ('+k[3]+'). '+(k[0]==='を'?'현대 표준어에서는 보통 o로 읽어요.':k[0]==='ん'?'뒤에 오는 소리에 따라 발음이 달라져요.':''),
speak:k[t],
level:BASE.includes(k)?'base':'extra'
});
}

for(const w of WORDS)
Q_BANK.push({
id:w.id,
type:'words',
prompt:w.ja,
answer:w.ko,
explanation:w.kana+' · '+w.roma+' → '+w.ko,
speak:w.ja
});

LESSONS.forEach((l,i)=>l.qs.forEach((q,j)=>
Q_BANK.push({...q,id:'l'+i+'-'+j,type:'lesson',lesson:i})
));

const STORE_KEY='japanese-first-steps-v1';

const fresh=()=>({
version:1,
done:[],
knownKana:[],
knownWords:[],
wrong:[],
today:{},
total:0,
correct:0,
lastLesson:0,
reading:true
});

let state=fresh(),storageOK=true;

try{
const saved=JSON.parse(localStorage.getItem(STORE_KEY));
if(saved&&saved.version===1){
for(const key of ['done','knownKana','knownWords','wrong'])
if(Array.isArray(saved[key]))state[key]=[...new Set(saved[key])];

for(const key of ['total','correct','lastLesson'])
if(Number.isFinite(saved[key])&&saved[key]>=0)state[key]=saved[key];

if(saved.today&&typeof saved.today==='object'&&!Array.isArray(saved.today))
state.today=saved.today;

if(typeof saved.reading==='boolean')
state.reading=saved.reading;

state.done=state.done.filter(i=>Number.isInteger(i)&&i>=0&&i<LESSONS.length);
state.lastLesson=Math.min(LESSONS.length-1,Math.floor(state.lastLesson));
state.wrong=state.wrong.filter(id=>Q_BANK.some(q=>q.id===id));
}
}catch(e){
storageOK=false;
}

let activeView='learn',
activeLesson=null,
kanaType=0,
kanaGroup='base',
selectedKana=BASE[0],
wordCat='전체',
wordMode='card',
wordIndex=0,
wordSearch='',
wordOnlyUnknown=false,
wordFlipped=false,
quizType='hiragana',
quizLevel='base',
quizSession=null,
toastTimer=null,
voiceList=[];

const localDay=()=>{
const d=new Date();
return d.getFullYear()+'-'+
String(d.getMonth()+1).padStart(2,'0')+'-'+
String(d.getDate()).padStart(2,'0');
};

function save(){
try{
localStorage.setItem(STORE_KEY,JSON.stringify(state));
}catch(e){
storageOK=false;
}
updateHeader();
}

function updateHeader(){
$('#today-count').textContent=Number(state.today[localDay()])||0;
$('#save-note').textContent=storageOK
?'학습 기록은 이 브라우저에 자동 저장됩니다. 다른 기기와 동기화되지는 않습니다.'
:'이 환경에서는 기록 저장을 사용할 수 없어요. 페이지를 닫으면 이번 학습 기록이 사라질 수 있어요.';
}

function toast(message){
clearTimeout(toastTimer);
$('#toast').textContent=message;
$('#toast').hidden=false;
toastTimer=setTimeout(()=>$('#toast').hidden=true,3600);
}

function speak(text){
if(!('speechSynthesis' in window)){
toast('이 브라우저에서는 음성을 지원하지 않아요. 다른 브라우저에서 열어 주세요.');
return;
}

const synth=window.speechSynthesis;
synth.cancel();

const u=new SpeechSynthesisUtterance(text);
u.lang='ja-JP';
u.rate=.8;

voiceList=synth.getVoices();

const voice=
voiceList.find(v=>/^ja(-|_)/i.test(v.lang))||
voiceList.find(v=>/^ja/i.test(v.lang));

if(voice)u.voice=voice;
else toast('일본어 음성이 들리지 않으면 기기의 일본어 음성 설정을 확인해 주세요.');

u.onerror=e=>{
if(!['canceled','interrupted'].includes(e.error))
toast('음성을 재생하지 못했어요. 일본어 음성 설정과 연결 상태를 확인해 주세요.');
};

synth.speak(u);
}

if('speechSynthesis' in window){
voiceList=window.speechSynthesis.getVoices();
window.speechSynthesis.addEventListener(
'voiceschanged',
()=>voiceList=window.speechSynthesis.getVoices()
);
}

function setView(view,focus=true){
activeView=view;

document.querySelectorAll('[id^="view-"]').forEach(
s=>s.hidden=s.id!=='view-'+view
);

document.querySelectorAll('[data-view]').forEach(b=>{
b.classList.toggle('active',b.dataset.view===view);

if(b.dataset.view===view)
b.setAttribute('aria-current','page');
else
b.removeAttribute('aria-current');
});

if(view==='learn')renderLearn();
if(view==='kana')renderKana();
if(view==='words')renderWords();
if(view==='quiz')renderQuiz();

if(focus){
window.scrollTo({top:0,behavior:'instant'});
$('#main').focus({preventScroll:true});
}
}

function nextLesson(){
return LESSONS.findIndex((l,i)=>!state.done.includes(i));
}

function registerAnswer(q,correct){
state.total++;

if(correct)
state.correct++;

const d=localDay();
state.today[d]=(Number(state.today[d])||0)+1;

if(correct)
state.wrong=state.wrong.filter(id=>id!==q.id);
else if(!state.wrong.includes(q.id))
state.wrong.push(q.id);

save();
}

function shuffle(items){
const a=[...items];

for(let i=a.length-1;i>0;i--){
const j=Math.floor(Math.random()*(i+1));
[a[i],a[j]]=[a[j],a[i]];
}

return a;
}

function quizPool(){
if(quizType==='review')
return Q_BANK.filter(q=>state.wrong.includes(q.id));

return Q_BANK.filter(q=>
q.type===quizType&&
(!['hiragana','katakana'].includes(quizType)||
quizLevel==='all'||
q.level==='base')
);
}

function startQuiz(){
const pool=quizPool();

if(!pool.length){
toast('복습할 오답이 아직 없어요. 다른 퀴즈부터 풀어 보세요.');
return;
}

quizSession={
questions:shuffle(pool).slice(0,10),
index:0,
score:0,
answered:false,
selected:null,
options:[],
finished:false,
mode:quizType
};

setView('quiz');
}

document.addEventListener('change',event=>{
const e=event.target;

if(e.id==='practice-check')
$('#complete-lesson').disabled=!e.checked;

if(e.id==='kana-reading'){
state.reading=e.checked;
save();
renderKana();
}

if(e.id==='word-category'){
wordCat=e.value;
wordIndex=0;
wordFlipped=false;
renderWords();
}

if(e.id==='word-unknown'){
wordOnlyUnknown=e.checked;
wordIndex=0;
wordFlipped=false;
renderWords();
}
});

document.addEventListener('input',event=>{
if(event.target.id==='word-search'){
wordSearch=event.target.value;
wordIndex=0;
wordFlipped=false;
renderWordContent();
}
});

save();
setView('learn',false);
</script>
</body>
</html>
