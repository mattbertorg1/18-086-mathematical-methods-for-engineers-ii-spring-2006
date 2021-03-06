---
about_this_resource_text: ''
course_id: 18-086-mathematical-methods-for-engineers-ii-spring-2006
embedded_media:
- id: Video-YouTube-Stream
  media_location: LtNVodIs1dI
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  title: Video-YouTube-Stream
  type: Video
  uid: 3a24fd0d41b5b781b8f68630c2bdb984
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/LtNVodIs1dI/default.jpg
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: adb9351c0ae4725788b3675cffa6f577
- id: Video--MP4
  media_location: http://www.archive.org/download/MIT18.086S06/ocw-18.086-13mar2006-220k.mp4
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  title: Video-Internet Archive-MP4
  type: Video
  uid: e7924a69cd1ba5ca90a5053dcdda87ad
- id: Audio-InternetArchive-MP3
  media_location: http://www.archive.org/download/MIT18.086S06/ocw-18.086-13mar2006.mp3
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  title: Audio-Internet Archive-MP3
  type: Audio
  uid: 41684d0cdf8a34fc879a163207a74d63
- id: Video--MP4_1
  media_location: http://itunes.apple.com/us/podcast/lecture-15-iterative-methods/id354869182?i=80690695
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  title: Video-iTunes U-MP4
  type: Video
  uid: 3dfd98458c9253503dffa02731573159
- id: 3Play-3PlayYouTubeid-MP4
  media_location: LtNVodIs1dI
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9bffa9babd2e7094411fb539b755523a
- id: LtNVodIs1dI.srt
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  technical_location: https://ocw.mit.edu/courses/mathematics/18-086-mathematical-methods-for-engineers-ii-spring-2006/video-lectures/lecture-15-iterative-methods-and-preconditioners/LtNVodIs1dI.srt
  title: 3play caption file
  type: null
  uid: 618b2fe7ef00e33577ed9daddee302fc
- id: LtNVodIs1dI.pdf
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  technical_location: https://ocw.mit.edu/courses/mathematics/18-086-mathematical-methods-for-engineers-ii-spring-2006/video-lectures/lecture-15-iterative-methods-and-preconditioners/LtNVodIs1dI.pdf
  title: 3play pdf file
  type: null
  uid: 973af184dc1aee39b92641feec21b923
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f5e8fec0fe474320b9cffea7b1ce99ba
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4f27eb5dfa89a234abfeb050423eaa59
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 15ec3ddbe448b7b62fbcfdbc5bc3e9af
inline_embed_id: 70253912lecture15:iterativemethodsandpreconditioners77616493
layout: video
order_index: null
parent_uid: ae0952f1bf1e6ddfcac1200232d8c3a7
related_resources_text: ''
short_url: lecture-15-iterative-methods-and-preconditioners
technical_location: https://ocw.mit.edu/courses/mathematics/18-086-mathematical-methods-for-engineers-ii-spring-2006/video-lectures/lecture-15-iterative-methods-and-preconditioners
template_type: Tabbed
title: 'Lecture 15: Iterative Methods and Preconditioners'
transcript: <p><span m='0'>NARRATOR:</span> <span m='180'>The</span> <span m='360'>following</span>
  <span m='810'>content</span> <span m='1350'>is</span> <span m='1470'>provided</span>
  <span m='1950'>by</span> <span m='2160'>MIT</span> <span m='2770'>OpenCourseWare</span>
  <span m='3680'>under</span> <span m='3830'>a</span> <span m='3980'>Creative</span>
  <span m='4420'>Commons</span> <span m='4690'>license.</span> <span m='6090'>Additional</span>
  <span m='6540'>information</span> <span m='7100'>about</span> <span m='7360'>our</span>
  <span m='7470'>license</span> <span m='8230'>and</span> <span m='8330'>MIT</span>
  <span m='8680'>OpenCourseWare</span> <span m='9450'>in</span> <span m='9650'>general</span>
  <span m='10460'>is</span> <span m='10720'>available</span> <span m='11480'>at</span>
  <span m='11800'>ocw.mit.edu.</span> </p><p><span m='14370'>PROFESSOR:</span> <span
  m='15320'>So</span> <span m='15510'>I'm</span> <span m='15730'>thinking</span> <span
  m='16260'>of</span> <span m='19010'>large</span> <span m='20240'>sparse</span> <span
  m='21210'>matrices.</span> <span m='24600'>So</span> <span m='24840'>the</span>
  <span m='26430'>point</span> <span m='26520'>about</span> <span m='26810'>a --</span>
  <span m='27840'>the</span> <span m='27950'>kind</span> <span m='28170'>of</span>
  <span m='28230'>matrices</span> <span m='28820'>that</span> <span m='28950'>we've</span>
  <span m='29140'>been</span> <span m='29280'>writing</span> <span m='29650'>down,</span>
  <span m='30690'>maybe</span> <span m='31110'>two</span> <span m='31380'>dimensional,</span>
  <span m='32010'>maybe</span> <span m='32350'>three</span> <span m='32650'>dimensional</span>
  <span m='33460'>difference</span> <span m='34060'>matrices.</span> <span m='35620'>So</span>
  <span m='36500'>it</span> <span m='36640'>might</span> <span m='36920'>be</span>
  <span m='37340'>five</span> <span m='37990'>or</span> <span m='38350'>seven</span>
  <span m='39610'>non</span> <span m='39990'>0s</span> <span m='40800'>on</span> <span
  m='40980'>a</span> <span m='41060'>typical</span> <span m='41580'>row</span> <span
  m='42570'>and</span> <span m='42750'>that</span> <span m='42940'>means</span> <span
  m='43360'>that</span> <span m='45490'>you</span> <span m='45690'>don't</span> <span
  m='45790'>want</span> <span m='46020'>to</span> <span m='46090'>invert</span> <span
  m='46550'>such</span> <span m='46810'>a</span> <span m='46880'>matrix.</span> <span
  m='47500'>These</span> <span m='47665'>are</span> <span m='47830'>big</span> <span
  m='48110'>matrices.</span> <span m='49470'>The</span> <span m='49590'>order</span>
  <span m='49880'>could</span> <span m='50060'>easily</span> <span m='50370'>be</span>
  <span m='50500'>a</span> <span m='50590'>million.</span> <span m='51640'>What</span>
  <span m='51840'>you</span> <span m='51990'>can</span> <span m='52360'>do</span>
  <span m='52560'>fast</span> <span m='53290'>is</span> <span m='54620'>multiply</span>
  <span m='55300'>a</span> <span m='55680'>by</span> <span m='55930'>a</span> <span
  m='56040'>vector,</span> <span m='56990'>because</span> <span m='57180'>multiplying</span>
  <span m='57780'>a</span> <span m='58520'>sparse</span> <span m='58840'>matrix</span>
  <span m='59290'>by</span> <span m='59390'>a</span> <span m='59490'>vector,</span>
  <span m='59880'>you</span> <span m='60000'>only</span> <span m='60180'>have</span>
  <span m='60780'>maybe</span> <span m='61080'>five</span> <span m='61530'>non</span>
  <span m='61800'>0s</span> <span m='63030'>times</span> <span m='63610'>the</span>
  <span m='63770'>n --</span> <span m='65720'>the</span> <span m='66050'>vector</span>
  <span m='66290'>of</span> <span m='66450'>length</span> <span m='66730'>n,</span>
  <span m='67630'>so</span> <span m='68230'>say</span> <span m='68420'>five</span>
  <span m='68890'>n</span> <span m='69590'>operations --</span> <span m='70340'>so</span>
  <span m='70490'>that's</span> <span m='70780'>fast.</span> <span m='76230'>I'm</span>
  <span m='76380'>thinking</span> <span m='76830'>that</span> <span m='76990'>we</span>
  <span m='77360'>are</span> <span m='78100'>at</span> <span m='78270'>a</span> <span
  m='78350'>size</span> <span m='78950'>where</span> <span m='79810'>elimination,</span>
  <span m='81840'>even</span> <span m='82290'>with</span> <span m='82530'>a</span>
  <span m='82590'>good</span> <span m='83100'>ordering,</span> <span m='84220'>is</span>
  <span m='85650'>too</span> <span m='85840'>expensive</span> <span m='87020'>in</span>
  <span m='87480'>time</span> <span m='87960'>or</span> <span m='88110'>in</span>
  <span m='88480'>storage.</span> <span m='89760'>So</span> <span m='90390'>I'm</span>
  <span m='90650'>going</span> <span m='91060'>from</span> <span m='91660'>direct</span>
  <span m='92340'>elimination</span> <span m='93080'>methods</span> <span m='93640'>to</span>
  <span m='94230'>iterative</span> <span m='94810'>methods.</span> <span m='96800'>Iterative</span>
  <span m='97350'>means</span> <span m='98310'>that</span> <span m='98500'>I</span>
  <span m='98600'>never</span> <span m='98900'>actually</span> <span m='99370'>get</span>
  <span m='99640'>to</span> <span m='99770'>the</span> <span m='99930'>perfect</span>
  <span m='100530'>answer</span> <span m='100990'>x,</span> <span m='102000'>but</span>
  <span m='102680'>I</span> <span m='102810'>get</span> <span m='103140'>close</span>
  <span m='104770'>and</span> <span m='105700'>what</span> <span m='105900'>I</span>
  <span m='105960'>want</span> <span m='106190'>to</span> <span m='106250'>do</span>
  <span m='106390'>is</span> <span m='106550'>get</span> <span m='106790'>close</span>
  <span m='107270'>quickly.</span> </p><p><span m='108650'>So</span> <span m='109960'>a</span>
  <span m='110060'>lot</span> <span m='110320'>of</span> <span m='110450'>thought</span>
  <span m='110820'>has</span> <span m='111020'>gone</span> <span m='111380'>into</span>
  <span m='112490'>creating</span> <span m='113170'>iterative</span> <span m='113750'>methods.</span>
  <span m='115630'>I'll</span> <span m='115850'>write</span> <span m='116100'>down</span>
  <span m='116610'>one</span> <span m='117080'>key</span> <span m='117450'>word</span>
  <span m='118030'>here.</span> <span m='119710'>Part</span> <span m='120020'>of</span>
  <span m='120120'>the</span> <span m='121010'>decision</span> <span m='121820'>is</span>
  <span m='122760'>to</span> <span m='122910'>choose</span> <span m='123380'>a</span>
  <span m='123470'>good</span> <span m='123990'>preconditioner.</span> <span m='126130'>I'll</span>
  <span m='126450'>call</span> <span m='126720'>that</span> <span m='126940'>matrix</span>
  <span m='127630'>p.</span> <span m='129440'>So</span> <span m='129610'>it's</span>
  <span m='129760'>a</span> <span m='130190'>matrix</span> <span m='131680'>that's</span>
  <span m='131910'>supposed</span> <span m='132420'>to</span> <span m='132510'>be
  --</span> <span m='133840'>that</span> <span m='133940'>we</span> <span m='134100'>have</span>
  <span m='134310'>some</span> <span m='134470'>freedom</span> <span m='134880'>to</span>
  <span m='135010'>choose</span> <span m='135460'>and</span> <span m='135620'>it</span>
  <span m='135780'>very</span> <span m='136180'>much</span> <span m='136560'>speeds</span>
  <span m='137060'>up,</span> <span m='137390'>so</span> <span m='138140'>the</span>
  <span m='138280'>decisions</span> <span m='138940'>are,</span> <span m='139850'>what</span>
  <span m='140130'>preconditioner</span> <span m='140980'>to</span> <span m='141110'>choose?</span>
  <span m='141640'>A</span> <span m='141730'>preconditioner</span> <span m='142480'>that's</span>
  <span m='142820'>somehow</span> <span m='144080'>like</span> <span m='144840'>the</span>
  <span m='144970'>matrix</span> <span m='145550'>a,</span> <span m='145990'>but</span>
  <span m='147330'>hopefully</span> <span m='147810'>a</span> <span m='147890'>lot</span>
  <span m='148160'>simpler.</span> <span m='156540'>There</span> <span m='156830'>are</span>
  <span m='157650'>a</span> <span m='157730'>bunch</span> <span m='158110'>of</span>
  <span m='158230'>iterative</span> <span m='158830'>methods</span> <span m='159890'>and</span>
  <span m='160090'>that's</span> <span m='160350'>what</span> <span m='160570'>today's</span>
  <span m='160990'>lecture</span> <span m='161210'>is</span> <span m='161430'>about.</span>
  </p><p><span m='162770'>Multigrid</span> <span m='164560'>is</span> <span m='165980'>an</span>
  <span m='166160'>idea</span> <span m='166500'>that</span> <span m='166600'>just</span>
  <span m='166910'>keeps</span> <span m='167450'>developing.</span> <span m='169040'>It</span>
  <span m='169220'>really</span> <span m='171410'>is</span> <span m='171610'>producing</span>
  <span m='172200'>answers</span> <span m='172900'>to</span> <span m='173070'>very</span>
  <span m='173440'>large</span> <span m='173780'>problems</span> <span m='174310'>very</span>
  <span m='174630'>fast,</span> <span m='175910'>so</span> <span m='176040'>that</span>
  <span m='176270'>will</span> <span m='176410'>be</span> <span m='177850'>the</span>
  <span m='178210'>following</span> <span m='178680'>lectures</span> <span m='179590'>and</span>
  <span m='179820'>then</span> <span m='180340'>come</span> <span m='181240'>these</span>
  <span m='182120'>methods --</span> <span m='182920'>you</span> <span m='183070'>may</span>
  <span m='183250'>not</span> <span m='183610'>be</span> <span m='183930'>familiar</span>
  <span m='184410'>with</span> <span m='184560'>that</span> <span m='184750'>word</span>
  <span m='185020'>Krylov.</span> <span m='185710'>Let</span> <span m='185890'>me</span>
  <span m='186020'>mention</span> <span m='186610'>that</span> <span m='188090'>in</span>
  <span m='188290'>this</span> <span m='188560'>family,</span> <span m='189080'>the</span>
  <span m='189270'>best</span> <span m='189740'>known</span> <span m='190110'>method</span>
  <span m='190360'>it</span> <span m='190490'>is</span> <span m='190680'>called</span>
  <span m='191160'>conjugate</span> <span m='191830'>gradience.</span> <span m='192840'>The</span>
  <span m='192950'>conjugate</span> <span m='193330'>gradient,</span> <span m='194750'>so</span>
  <span m='195490'>I'll</span> <span m='195740'>just</span> <span m='195980'>write</span>
  <span m='196280'>that</span> <span m='196530'>down.</span> <span m='197620'>Conjugate</span>
  <span m='198130'>gradient,</span> <span m='199120'>so</span> <span m='199300'>that</span>
  <span m='199760'>will</span> <span m='199970'>come</span> <span m='200320'>next</span>
  <span m='200700'>week.</span> <span m='204620'>That's</span> <span m='204890'>a</span>
  <span m='204990'>method</span> <span m='205420'>that's</span> <span m='205660'>a</span>
  <span m='206220'>giant</span> <span m='206770'>success</span> <span m='207570'>for</span>
  <span m='208750'>symmetric</span> <span m='209720'>positive</span> <span m='210220'>definite</span>
  <span m='210850'>problem.</span> <span m='212040'>So</span> <span m='212200'>I</span>
  <span m='212310'>don't</span> <span m='213260'>assume</span> <span m='213570'>in</span>
  <span m='213880'>general</span> <span m='214350'>that</span> <span m='214520'>a</span>
  <span m='214770'>is</span> <span m='215040'>symmetric</span> <span m='215650'>or</span>
  <span m='215810'>positive</span> <span m='216300'>definite.</span> <span m='217420'>Often</span>
  <span m='217810'>it</span> <span m='217980'>is</span> <span m='218270'>if</span>
  <span m='218440'>it</span> <span m='218550'>comes</span> <span m='218910'>from</span>
  <span m='220140'>a</span> <span m='220950'>finite</span> <span m='221580'>difference</span>
  <span m='222090'>or</span> <span m='222190'>finite</span> <span m='222620'>element</span>
  <span m='224730'>approximation.</span> <span m='227250'>If</span> <span m='227420'>it</span>
  <span m='227550'>is,</span> <span m='228100'>then</span> <span m='228620'>conjugate</span>
  <span m='228990'>gradience</span> <span m='229980'>is</span> <span m='231730'>highly</span>
  <span m='232070'>recommended.</span> </p><p><span m='233690'>I'll</span> <span m='233940'>start</span>
  <span m='234350'>with</span> <span m='235720'>the</span> <span m='236080'>general</span>
  <span m='236480'>picture.</span> <span m='236910'>Let</span> <span m='237040'>me</span>
  <span m='237160'>put</span> <span m='237660'>the</span> <span m='238020'>general</span>
  <span m='238470'>picture</span> <span m='238910'>of</span> <span m='239040'>what</span>
  <span m='240160'>an</span> <span m='240370'>iteration</span> <span m='240960'>looks</span>
  <span m='241240'>like.</span> <span m='242250'>So</span> <span m='242420'>an</span>
  <span m='242630'>iteration</span> <span m='243180'>computes</span> <span m='243540'>the</span>
  <span m='243900'>new</span> <span m='244350'>x.</span> <span m='246170'>Let</span>
  <span m='246340'>me</span> <span m='246490'>call</span> <span m='246810'>it</span>
  <span m='248180'>x-new</span> <span m='248820'>or</span> <span m='250130'>xk</span>
  <span m='250460'>plus</span> <span m='250780'>1</span> <span m='253630'>from</span>
  <span m='256570'>the</span> <span m='256730'>known</span> <span m='257055'>x.</span>
  <span m='257380'>So</span> <span m='257510'>we</span> <span m='257670'>start</span>
  <span m='257860'>with</span> <span m='258050'>x</span> <span m='258500'>0,</span>
  <span m='259920'>any</span> <span m='260550'>x</span> <span m='260980'>0.</span>
  <span m='262090'>In</span> <span m='262300'>principle,</span> <span m='263570'>it's</span>
  <span m='263780'>not</span> <span m='264090'>too</span> <span m='264320'>important</span>
  <span m='264900'>for</span> <span m='265340'>0</span> <span m='265630'>to</span>
  <span m='265760'>be</span> <span m='265920'>close</span> <span m='267570'>in</span>
  <span m='267770'>linear</span> <span m='268180'>methods.</span> <span m='269560'>You</span>
  <span m='269720'>could</span> <span m='271050'>start</span> <span m='271440'>even</span>
  <span m='271700'>at</span> <span m='271840'>0.</span> <span m='273110'>In</span>
  <span m='273360'>nonlinear</span> <span m='273990'>methods,</span> <span m='274680'>Newton</span>
  <span m='275120'>methods,</span> <span m='275940'>you</span> <span m='276360'>do</span>
  <span m='276510'>want</span> <span m='276810'>to</span> <span m='276870'>be</span>
  <span m='277010'>close</span> <span m='277610'>and</span> <span m='277665'>a</span>
  <span m='277720'>lot</span> <span m='277970'>of</span> <span m='278260'>attention</span>
  <span m='278910'>goes</span> <span m='279250'>into</span> <span m='279510'>a</span>
  <span m='279610'>good</span> <span m='279860'>start.</span> <span m='280590'>Here</span>
  <span m='280790'>the</span> <span m='280930'>start</span> <span m='281280'>isn't</span>
  <span m='281540'>too</span> <span m='281700'>important;</span> <span m='282670'>it's</span>
  <span m='282970'>the</span> <span m='283920'>steps</span> <span m='284400'>that</span>
  <span m='284560'>you</span> <span m='284740'>taking.</span> <span m='285300'>Let</span>
  <span m='285500'>me --</span> <span m='286580'>so</span> <span m='287340'>I</span>
  <span m='287560'>guess</span> <span m='287860'>I'm</span> <span m='288060'>going</span>
  <span m='288310'>to --</span> <span m='293300'>I'm</span> <span m='293610'>trying</span>
  <span m='293860'>to</span> <span m='293950'>solve</span> <span m='294250'>ax</span>
  <span m='294800'>equal</span> <span m='294910'>b.</span> <span m='297770'>I'm</span>
  <span m='297890'>going</span> <span m='298100'>to</span> <span m='298210'>split</span>
  <span m='298780'>that</span> <span m='302060'>equation</span> <span m='303580'>into
  --</span> <span m='305910'>I'm</span> <span m='306200'>just</span> <span m='306390'>going
  to</span> <span m='306550'>write</span> <span m='306850'>the</span> <span m='306980'>same</span>
  <span m='307250'>equation</span> <span m='307730'>this</span> <span m='307930'>way.</span>
  <span m='308140'>I</span> <span m='308270'>could</span> <span m='308480'>write</span>
  <span m='308730'>it</span> <span m='308930'>as</span> <span m='310040'>x</span>
  <span m='310563'>equals</span> <span m='313250'>i</span> <span m='313410'>minus</span>
  <span m='314190'>ax</span> <span m='315820'>plus</span> <span m='316510'>b.</span>
  <span m='318330'>That</span> <span m='318500'>would</span> <span m='318630'>be</span>
  <span m='318740'>the</span> <span m='318880'>same</span> <span m='319160'>equation,</span>
  <span m='319600'>right?</span> <span m='319820'>Because</span> <span m='321040'>x</span>
  <span m='321206'>and</span> <span m='321373'>x</span> <span m='321540'>cancel.</span>
  <span m='322500'>ax</span> <span m='323040'>comes</span> <span m='323340'>over</span>
  <span m='323560'>here</span> <span m='323870'>and</span> <span m='324010'>I</span>
  <span m='324070'>have</span> <span m='324340'>ax</span> <span m='324690'>equal</span>
  <span m='324960'>b.</span> <span m='329640'>I've</span> <span m='329840'>split</span>
  <span m='330300'>up</span> <span m='330680'>the</span> <span m='331250'>equation</span>
  <span m='332260'>and</span> <span m='332450'>now</span> <span m='332800'>actually,</span>
  <span m='333610'>let</span> <span m='333810'>me</span> <span m='333980'>bring --</span>
  <span m='334640'>so</span> <span m='334760'>that's</span> <span m='335020'>without</span>
  <span m='335420'>preconditioner.</span> <span m='336860'>You</span> <span m='337010'>don't</span>
  <span m='337270'>see</span> <span m='337500'>a</span> <span m='338420'>matrix</span>
  <span m='339000'>p.</span> <span m='341520'>That's</span> <span m='342430'>just</span>
  <span m='342730'>an</span> <span m='342850'>ordinary</span> <span m='343600'>iteration,</span>
  <span m='344190'>no</span> <span m='344500'>preconditioner.</span> </p><p><span
  m='346440'>The</span> <span m='346570'>preconditioner</span> <span m='347380'>will</span>
  <span m='347590'>come.</span> <span m='348380'>I'll</span> <span m='348580'>have</span>
  <span m='348940'>p</span> <span m='350270'>and</span> <span m='351330'>it'll</span>
  <span m='351780'>go</span> <span m='351940'>here</span> <span m='352230'>too.</span>
  <span m='354310'>Then</span> <span m='354910'>of</span> <span m='355020'>course,</span>
  <span m='355310'>I</span> <span m='355390'>have</span> <span m='355520'>to</span>
  <span m='355650'>change</span> <span m='355950'>that</span> <span m='356310'>to</span>
  <span m='356960'>a</span> <span m='357470'>p.</span> <span m='360080'>So</span>
  <span m='360240'>that's</span> <span m='360510'>still</span> <span m='360770'>the</span>
  <span m='360890'>same</span> <span m='361120'>equation,</span> <span m='361570'>right?</span>
  <span m='362380'>px</span> <span m='362610'>is</span> <span m='363110'>on</span>
  <span m='363290'>both</span> <span m='363560'>sides,</span> <span m='364010'>cancels
  --</span> <span m='365410'>and</span> <span m='365820'>I</span> <span m='365930'>have</span>
  <span m='366180'>ax</span> <span m='366730'>equal</span> <span m='366860'>b.</span>
  <span m='367080'>So</span> <span m='367260'>that's</span> <span m='367620'>the</span>
  <span m='367830'>same</span> <span m='368320'>equation,</span> <span m='369690'>but</span>
  <span m='369870'>it</span> <span m='370050'>suggests</span> <span m='371930'>the</span>
  <span m='372460'>iteration</span> <span m='372590'>that</span> <span m='372740'>I</span>
  <span m='372830'>want</span> <span m='373100'>to</span> <span m='373930'>analyze.</span>
  <span m='377570'>On</span> <span m='377820'>the</span> <span m='377900'>right</span>
  <span m='378140'>hand</span> <span m='378390'>side</span> <span m='379740'>is</span>
  <span m='380250'>the</span> <span m='380380'>known</span> <span m='386910'>approximation.</span>
  <span m='388900'>On</span> <span m='389170'>the</span> <span m='389270'>left</span>
  <span m='389540'>side</span> <span m='390790'>is</span> <span m='391060'>the</span>
  <span m='391170'>next</span> <span m='391680'>approximation,</span> <span m='392770'>xk</span>
  <span m='392950'>plus</span> <span m='393230'>1.</span> <span m='396100'>I</span>
  <span m='396230'>multiply</span> <span m='396810'>by</span> <span m='397130'>p,</span>
  <span m='398850'>so</span> <span m='399060'>I --</span> <span m='400590'>the</span>
  <span m='400940'>idea</span> <span m='401260'>is</span> <span m='401530'>p</span>
  <span m='401800'>should</span> <span m='402000'>be</span> <span m='402140'>close</span>
  <span m='402480'>to</span> <span m='402600'>a.</span> <span m='403800'>Of</span>
  <span m='403940'>course,</span> <span m='404230'>if</span> <span m='404380'>it</span>
  <span m='404550'>was</span> <span m='404730'>exactly</span> <span m='405400'>a --</span>
  <span m='406950'>if</span> <span m='407150'>p</span> <span m='407410'>equalled</span>
  <span m='407750'>a,</span> <span m='408710'>then</span> <span m='409200'>this</span>
  <span m='409420'>wouldn't</span> <span m='409710'>be</span> <span m='409920'>here</span>
  <span m='411180'>and</span> <span m='411370'>I</span> <span m='411440'>would</span>
  <span m='411650'>just</span> <span m='411910'>be</span> <span m='412050'>solving</span>
  <span m='412570'>in</span> <span m='412730'>one</span> <span m='412920'>step</span>
  <span m='413760'>ax</span> <span m='414370'>equal</span> <span m='414500'>b.</span>
  <span m='416730'>So</span> <span m='416880'>p</span> <span m='417220'>equal</span>
  <span m='417560'>a</span> <span m='418155'>is</span> <span m='418750'>one</span>
  <span m='418990'>extreme.</span> <span m='421490'>I</span> <span m='421560'>mean,</span>
  <span m='421890'>it's</span> <span m='422240'>totally,</span> <span m='423480'>perfectly</span>
  <span m='424070'>preconditioned,</span> <span m='425210'>but</span> <span m='425420'>the</span>
  <span m='425530'>point</span> <span m='425840'>is</span> <span m='427830'>that</span>
  <span m='427990'>if</span> <span m='428150'>p</span> <span m='428320'>equals</span>
  <span m='428770'>a,</span> <span m='429520'>we</span> <span m='429720'>don't</span>
  <span m='429930'>want</span> <span m='431010'>to</span> <span m='431220'>solve</span>
  <span m='432520'>that</span> <span m='432880'>system.</span> <span m='433320'>We're</span>
  <span m='433440'>trying</span> <span m='433710'>to</span> <span m='433840'>escape</span>
  <span m='434380'>from</span> <span m='434580'>solving</span> <span m='434990'>that</span>
  <span m='435200'>system,</span> <span m='435790'>but</span> <span m='435980'>we're</span>
  <span m='436140'>willing</span> <span m='436520'>to</span> <span m='436660'>solve</span>
  <span m='437280'>a</span> <span m='438310'>related</span> <span m='438900'>system</span>
  <span m='440110'>that</span> <span m='441700'>is</span> <span m='441890'>simpler.</span>
  <span m='443450'>Why</span> <span m='443800'>simpler?</span> </p><p><span m='445190'>Here</span>
  <span m='445435'>are</span> <span m='445680'>some</span> <span m='446020'>possible</span>
  <span m='446360'>preconditioners.</span> <span m='447960'>p</span> <span m='448470'>equals</span>
  <span m='450150'>the</span> <span m='450300'>diagonal.</span> <span m='452060'>Just</span>
  <span m='452390'>take</span> <span m='452680'>the</span> <span m='452820'>diagonal</span>
  <span m='453800'>of</span> <span m='453960'>a</span> <span m='456100'>and</span>
  <span m='456310'>that</span> <span m='456990'>choice</span> <span m='457550'>is</span>
  <span m='458150'>named</span> <span m='458620'>after</span> <span m='459230'>Jacobi.</span>
  <span m='461000'>That's</span> <span m='461600'>Jacobi's</span> <span m='462040'>method.</span>
  <span m='463670'>Actually,</span> <span m='464200'>it's</span> <span m='464350'>already</span>
  <span m='465360'>a</span> <span m='465640'>good</span> <span m='465860'>idea,</span>
  <span m='467770'>because</span> <span m='468690'>the</span> <span m='468990'>effect</span>
  <span m='469430'>of</span> <span m='469560'>that</span> <span m='469870'>is</span>
  <span m='470080'>somehow</span> <span m='470800'>to</span> <span m='471740'>properly</span>
  <span m='472330'>scaled</span> <span m='474550'>the</span> <span m='474710'>equations.</span>
  <span m='476400'>When</span> <span m='476610'>I</span> <span m='476700'>had</span>
  <span m='476970'>the</span> <span m='477070'>identity</span> <span m='477700'>here,</span>
  <span m='478480'>I</span> <span m='478600'>had</span> <span m='478770'>no</span>
  <span m='478990'>idea</span> <span m='479410'>whether</span> <span m='479690'>the</span>
  <span m='479830'>identity</span> <span m='480570'>and</span> <span m='481060'>a</span>
  <span m='481300'>are</span> <span m='481590'>in</span> <span m='481720'>the</span>
  <span m='481820'>right</span> <span m='482170'>scaling.</span> <span m='484180'>a</span>
  <span m='484540'>may</span> <span m='485220'>be</span> <span m='485620'>divided</span>
  <span m='486140'>by</span> <span m='486310'>delta</span> <span m='486670'>x</span>
  <span m='486950'>squared</span> <span m='487420'>or</span> <span m='487510'>something.</span>
  <span m='487810'>It</span> <span m='488020'>could</span> <span m='488220'>be</span>
  <span m='489020'>totally</span> <span m='489470'>different</span> <span m='489830'>units,</span>
  <span m='491210'>but</span> <span m='491680'>p --</span> <span m='493060'>if</span>
  <span m='493250'>I</span> <span m='493350'>take</span> <span m='493620'>the</span>
  <span m='493750'>diagonal</span> <span m='494200'>of</span> <span m='494350'>a,</span>
  <span m='494560'>at</span> <span m='494680'>least</span> <span m='495100'>they're</span>
  <span m='495880'>comparable.</span> <span m='496510'>Then</span> <span m='497130'>you</span>
  <span m='497270'>see</span> <span m='497450'>what --</span> <span m='498300'>we'll</span>
  <span m='498480'>study</span> <span m='498870'>Jacobi's</span> <span m='499360'>method.</span>
  <span m='502190'>So</span> <span m='502330'>that's</span> <span m='502570'>a</span>
  <span m='502640'>very</span> <span m='502870'>simple</span> <span m='503210'>choice.</span>
  <span m='504600'>Takes</span> <span m='504900'>no</span> <span m='505130'>more</span>
  <span m='505400'>work</span> <span m='505660'>than</span> <span m='505830'>the</span>
  <span m='505950'>identity,</span> <span m='506540'>really.</span> <span m='508650'>Second</span>
  <span m='509080'>choice</span> <span m='509520'>would</span> <span m='509800'>be
  --</span> <span m='510050'>so</span> <span m='510190'>that</span> <span m='510370'>would</span>
  <span m='510510'>be</span> <span m='510690'>p</span> <span m='511090'>for</span>
  <span m='511460'>Jacobi.</span> <span m='512230'>A</span> <span m='512360'>second</span>
  <span m='512780'>choice</span> <span m='513180'>that</span> <span m='514300'>you</span>
  <span m='514480'>would</span> <span m='514640'>think</span> <span m='514890'>of</span>
  <span m='515030'>pretty</span> <span m='515310'>fast</span> <span m='516280'>is</span>
  <span m='518050'>the</span> <span m='518240'>diagonal</span> <span m='518990'>and</span>
  <span m='519650'>the</span> <span m='519940'>lower</span> <span m='520380'>triangular</span>
  <span m='521130'>part.</span> <span m='522460'>So</span> <span m='522680'>it's</span>
  <span m='522910'>the --</span> <span m='523540'>I'll</span> <span m='523770'>say</span>
  <span m='524130'>the</span> <span m='525620'>triangular --</span> <span m='526760'>I'm</span>
  <span m='526950'>going</span> <span m='527085'>to</span> <span m='527220'>say</span>
  <span m='527600'>lower</span> <span m='527940'>triangular,</span> <span m='528980'>triangular</span>
  <span m='529630'>part</span> <span m='531920'>of</span> <span m='532100'>a,</span>
  <span m='533000'>including</span> <span m='533580'>the</span> <span m='533700'>diagonal.</span>
  <span m='538100'>This</span> <span m='538360'>is</span> <span m='538870'>associated</span>
  <span m='539660'>with</span> <span m='540190'>Gauss's</span> <span m='541700'>great</span>
  <span m='542040'>name</span> <span m='542670'>and</span> <span m='544370'>Seidel.</span>
  <span m='545390'>So</span> <span m='545620'>that's</span> <span m='545940'>the</span>
  <span m='546120'>Gauss-Seidel</span> <span m='547230'>choice.</span> <span m='551470'>So</span>
  <span m='551630'>why</span> <span m='552010'>triangular?</span> <span m='555300'>We'll</span>
  <span m='555500'>analyze</span> <span m='555720'>the</span> <span m='556200'>effect</span>
  <span m='556750'>of</span> <span m='556980'>this</span> <span m='557120'>choice.</span>
  <span m='558980'>If</span> <span m='559170'>p</span> <span m='559500'>is</span>
  <span m='560440'>triangular,</span> <span m='562420'>then</span> <span m='562950'>we</span>
  <span m='563130'>can</span> <span m='563380'>solve --</span> <span m='567600'>I'm</span>
  <span m='567700'>never</span> <span m='567950'>going</span> <span m='568130'>to</span>
  <span m='568190'>write</span> <span m='568470'>out</span> <span m='568660'>an</span>
  <span m='568750'>inverse</span> <span m='569225'>matrix.</span> <span m='569700'>That's</span>
  <span m='569930'>understood,</span> <span m='571360'>but</span> <span m='572280'>I</span>
  <span m='573050'>can</span> <span m='573280'>compute</span> <span m='573910'>the</span>
  <span m='574040'>new</span> <span m='574270'>x</span> <span m='575340'>from</span>
  <span m='575570'>the</span> <span m='575680'>old</span> <span m='576020'>x</span>
  <span m='577690'>1</span> <span m='579370'>just</span> <span m='579620'>by</span>
  <span m='579790'>back</span> <span m='580030'>substitution.</span> <span m='581380'>I</span>
  <span m='581490'>find</span> <span m='581860'>the</span> <span m='581990'>first</span>
  <span m='582440'>component</span> <span m='582980'>of</span> <span m='583080'>x,</span>
  <span m='584180'>k</span> <span m='584370'>plus</span> <span m='584630'>1,</span>
  <span m='586270'>then</span> <span m='586520'>the</span> <span m='586640'>second,</span>
  <span m='587100'>then</span> <span m='587240'>the</span> <span m='587330'>third.</span>
  <span m='588840'>It's</span> <span m='589110'>just</span> <span m='592330'>because</span>
  <span m='592660'>the</span> <span m='592790'>first</span> <span m='593310'>equation
  --</span> <span m='594840'>if</span> <span m='595340'>p</span> <span m='595600'>is</span>
  <span m='595880'>triangular,</span> <span m='596750'>the</span> <span m='597490'>first</span>
  <span m='597890'>equation</span> <span m='598320'>will</span> <span m='598490'>only</span>
  <span m='598740'>have</span> <span m='599380'>one</span> <span m='600560'>term,</span>
  <span m='601320'>one</span> <span m='601550'>new</span> <span m='601800'>term</span>
  <span m='602160'>on</span> <span m='602290'>the</span> <span m='602380'>left</span>
  <span m='602660'>side</span> <span m='602940'>and</span> <span m='603070'>everything</span>
  <span m='603440'>else</span> <span m='603650'>will</span> <span m='603740'>be</span>
  <span m='603860'>over</span> <span m='604090'>there.</span> <span m='605250'>The</span>
  <span m='605350'>second</span> <span m='605760'>equation</span> <span m='606840'>will</span>
  <span m='607320'>have</span> <span m='607590'>a</span> <span m='607700'>diagonal</span>
  <span m='608420'>and</span> <span m='609320'>something</span> <span m='609850'>that</span>
  <span m='610690'>uses</span> <span m='611780'>the</span> <span m='612570'>number</span>
  <span m='612890'>I</span> <span m='613010'>just</span> <span m='613460'>found</span>
  <span m='616350'>for</span> <span m='616460'>the</span> <span m='616570'>first</span>
  <span m='616830'>component</span> <span m='617580'>and</span> <span m='617800'>onward.</span>
  <span m='618650'>So</span> <span m='619520'>in</span> <span m='619690'>other</span>
  <span m='619850'>words,</span> <span m='620060'>triangular</span> <span m='620610'>matrices</span>
  <span m='620810'>are good.</span> </p><p><span m='623320'>Then</span> <span m='623780'>people</span>
  <span m='624180'>thought</span> <span m='624480'>about</span> <span m='625760'>combinations</span>
  <span m='626660'>of</span> <span m='626770'>these.</span> <span m='630400'>A</span>
  <span m='631000'>big</span> <span m='631540'>lot</span> <span m='631770'>of</span>
  <span m='631860'>activity</span> <span m='632550'>went</span> <span m='633280'>in</span>
  <span m='633400'>something</span> <span m='633820'>called</span> <span m='634440'>overrelaxation,</span>
  <span m='638380'>where</span> <span m='638760'>you</span> <span m='639180'>did</span>
  <span m='639400'>a --</span> <span m='639520'>you</span> <span m='639640'>had</span>
  <span m='639760'>a</span> <span m='639840'>weighting</span> <span m='640450'>of</span>
  <span m='640580'>these</span> <span m='641030'>and</span> <span m='641160'>it</span>
  <span m='641250'>turned</span> <span m='641540'>out</span> <span m='641760'>to</span>
  <span m='641870'>be</span> <span m='643050'>if</span> <span m='643300'>you</span>
  <span m='643450'>adjusted</span> <span m='644020'>the</span> <span m='644130'>weight,</span>
  <span m='645430'>you</span> <span m='645610'>could</span> <span m='645840'>speed</span>
  <span m='646240'>up</span> <span m='646440'>the</span> <span m='646560'>method,</span>
  <span m='649900'>sometimes</span> <span m='650440'>called</span> <span m='650770'>SOR--</span>
  <span m='652590'>successive</span> <span m='653310'>overrelaxation.</span> <span
  m='655230'>So</span> <span m='656230'>when</span> <span m='656460'>I</span> <span
  m='656560'>was</span> <span m='656730'>in</span> <span m='656880'>graduate</span>
  <span m='657300'>school,</span> <span m='657680'>that</span> <span m='657870'>was</span>
  <span m='658070'>a</span> <span m='660320'>very --</span> <span m='660890'>that</span>
  <span m='661110'>was</span> <span m='661910'>sort</span> <span m='662170'>of</span>
  <span m='662260'>the</span> <span m='662370'>beginning</span> <span m='663030'>of</span>
  <span m='663860'>progress</span> <span m='664490'>beyond</span> <span m='665120'>Jacobi</span>
  <span m='665240'>and</span> <span m='665810'>Gauss-Seidel.</span> <span m='667740'>Then</span>
  <span m='669060'>after</span> <span m='669490'>that</span> <span m='669900'>came</span>
  <span m='670750'>a</span> <span m='670900'>very</span> <span m='671250'>natural
  --</span> <span m='672960'>ilu</span> <span m='673710'>is</span> <span m='674195'>the</span>
  <span m='674680'>next</span> <span m='675050'>one</span> <span m='675220'>that</span>
  <span m='675315'>I</span> <span m='675410'>want --</span> <span m='678040'>the</span>
  <span m='678390'>i</span> <span m='678720'>stands</span> <span m='679120'>for</span>
  <span m='679300'>incomplete,</span> <span m='680260'>incomplete</span> <span m='681020'>lu.</span>
  <span m='684400'>So</span> <span m='684540'>what</span> <span m='684760'>are</span>
  <span m='684850'>l</span> <span m='685020'>and</span> <span m='685190'>u?</span>
  <span m='687520'>That's</span> <span m='688380'>the</span> <span m='688760'>letters</span>
  <span m='689230'>I</span> <span m='689390'>always</span> <span m='689780'>use</span>
  <span m='690040'>as</span> <span m='690270'>a</span> <span m='690380'>signal</span>
  <span m='690860'>for</span> <span m='691060'>the</span> <span m='691680'>lower</span>
  <span m='692080'>triangular</span> <span m='692880'>and</span> <span m='693060'>upper</span>
  <span m='693370'>triangular</span> <span m='693940'>factors</span> <span m='695220'>of</span>
  <span m='695490'>a,</span> <span m='698190'>the</span> <span m='698320'>ones</span>
  <span m='698600'>that</span> <span m='698800'>exact</span> <span m='699550'>elimination</span>
  <span m='700230'>would</span> <span m='700470'>produce.</span> <span m='701310'>But</span>
  <span m='701470'>we</span> <span m='701700'>don't</span> <span m='701880'>want</span>
  <span m='701990'>to</span> <span m='702100'>do</span> <span m='702270'>exact</span>
  <span m='702770'>elimination.</span> <span m='703410'>Why?</span> <span m='704450'>Because</span>
  <span m='705830'>non</span> <span m='706230'>0s</span> <span m='706690'>fill</span>
  <span m='707070'>in.</span> <span m='708040'>Non</span> <span m='708530'>0s</span>
  <span m='709100'>appear</span> <span m='711200'>in</span> <span m='711790'>those</span>
  <span m='712090'>spaces</span> <span m='712830'>where</span> <span m='713270'>a</span>
  <span m='713500'>itself</span> <span m='714080'>is</span> <span m='714310'>0.</span>
  <span m='715230'>So</span> <span m='715450'>the</span> <span m='715970'>factors</span>
  <span m='716840'>are</span> <span m='717100'>much --</span> <span m='719960'>have</span>
  <span m='720130'>many</span> <span m='720420'>more</span> <span m='720660'>non</span>
  <span m='720970'>0s</span> <span m='721440'>than</span> <span m='721630'>the</span>
  <span m='721700'>original</span> <span m='722170'>a.</span> <span m='722910'>They're</span>
  <span m='723050'>not</span> <span m='723300'>as</span> <span m='723500'>sparse.</span>
  </p><p><span m='724700'>So</span> <span m='725160'>the</span> <span m='725340'>idea</span>
  <span m='725710'>of</span> <span m='725800'>incomplete</span> <span m='726520'>lu</span>
  <span m='727060'>is --</span> <span m='728150'>and</span> <span m='728320'>I'll</span>
  <span m='728620'>come</span> <span m='728760'>back</span> <span m='729010'>to</span>
  <span m='729130'>it --</span> <span m='730470'>the</span> <span m='730540'>idea</span>
  <span m='730740'>of</span> <span m='730890'>incomplete</span> <span m='731290'>lu
  --</span> <span m='732040'>you</span> <span m='732150'>might</span> <span m='732400'>say,</span>
  <span m='732630'>should</span> <span m='732840'>have</span> <span m='732940'>occurred</span>
  <span m='733260'>to</span> <span m='733350'>people</span> <span m='733660'>earlier
  --</span> <span m='736400'>only</span> <span m='737420'>keep</span> <span m='738980'>the</span>
  <span m='739140'>non</span> <span m='739520'>0s</span> <span m='740260'>that</span>
  <span m='740590'>are</span> <span m='742180'>non</span> <span m='742490'>0s</span>
  <span m='742800'>in</span> <span m='742890'>the</span> <span m='742980'>original</span>
  <span m='743495'>a.</span> <span m='744010'>Don't</span> <span m='744270'>allow</span>
  <span m='744610'>fill</span> <span m='744835'>in</span> <span m='745940'>or</span>
  <span m='746130'>allow</span> <span m='746490'>a</span> <span m='746580'>certain</span>
  <span m='746930'>amount</span> <span m='747220'>of</span> <span m='747310'>fill</span>
  <span m='747640'>in.</span> <span m='747970'>You</span> <span m='748110'>could</span>
  <span m='748280'>have</span> <span m='748450'>a</span> <span m='748520'>tolerance</span>
  <span m='749950'>and</span> <span m='750130'>you</span> <span m='750210'>would</span>
  <span m='750690'>include</span> <span m='751470'>a</span> <span m='751605'>non</span>
  <span m='751740'>0</span> <span m='752210'>if</span> <span m='752335'>it</span>
  <span m='752460'>was</span> <span m='752650'>big</span> <span m='752870'>enough,</span>
  <span m='753690'>but</span> <span m='753890'>the</span> <span m='754140'>many,</span>
  <span m='754550'>many</span> <span m='754950'>small</span> <span m='755600'>non</span>
  <span m='755930'>0s</span> <span m='756350'>that</span> <span m='756490'>just</span>
  <span m='756750'>fill</span> <span m='757040'>in</span> <span m='757340'>and</span>
  <span m='758720'>make</span> <span m='759090'>the</span> <span m='759560'>elimination</span>
  <span m='761560'>long,</span> <span m='763060'>you</span> <span m='763760'>throw</span>
  <span m='763960'>them</span> <span m='764100'>out.</span> <span m='764840'>So</span>
  <span m='765010'>p</span> <span m='765580'>is --</span> <span m='766160'>in</span>
  <span m='766300'>this</span> <span m='766520'>case,</span> <span m='766960'>p</span>
  <span m='767390'>is</span> <span m='767770'>l,</span> <span m='768870'>is</span>
  <span m='769030'>an</span> <span m='769190'>approximate</span> <span m='769850'>l</span>
  <span m='771470'>times</span> <span m='771850'>an</span> <span m='771980'>approximate</span>
  <span m='772590'>u.</span> <span m='776290'>So</span> <span m='777020'>it's</span>
  <span m='777200'>close</span> <span m='777600'>to</span> <span m='777730'>a,</span>
  <span m='780430'>but</span> <span m='780570'>because</span> <span m='781210'>we've</span>
  <span m='783240'>refused</span> <span m='784910'>some</span> <span m='785150'>of</span>
  <span m='785240'>the</span> <span m='785340'>fill</span> <span m='785575'>in,</span>
  <span m='786530'>it's</span> <span m='786710'>not</span> <span m='786960'>exactly</span>
  <span m='787470'>a.</span> <span m='789410'>You</span> <span m='789550'>have</span>
  <span m='789750'>a</span> <span m='789840'>tolerance</span> <span m='790390'>there</span>
  <span m='790690'>where</span> <span m='791190'>if</span> <span m='791500'>you</span>
  <span m='791620'>set</span> <span m='791880'>the</span> <span m='792010'>tolerance</span>
  <span m='792520'>high,</span> <span m='793380'>then</span> <span m='794220'>these</span>
  <span m='794510'>are</span> <span m='794640'>exact,</span> <span m='795430'>but</span>
  <span m='795760'>you've</span> <span m='796080'>got</span> <span m='796300'>all</span>
  <span m='796490'>that</span> <span m='796700'>fill</span> <span m='796940'>in.</span>
  <span m='797930'>If</span> <span m='798120'>you</span> <span m='798240'>set</span>
  <span m='798500'>the</span> <span m='798630'>tolerance</span> <span m='799340'>to</span>
  <span m='800480'>0,</span> <span m='802960'>you've</span> <span m='803090'>got</span>
  <span m='803250'>the</span> <span m='803370'>other</span> <span m='803620'>[? instance.
  ?]</span> </p><p><span m='805540'>So</span> <span m='806800'>that</span> <span m='806960'>would</span>
  <span m='807120'>give</span> <span m='807280'>you</span> <span m='807400'>an</span>
  <span m='807510'>idea</span> <span m='807735'>of</span> <span m='807960'>preconditions,</span>
  <span m='809330'>of</span> <span m='810070'>reasonable</span> <span m='810600'>choices.</span>
  <span m='812660'>Now</span> <span m='813230'>I'm</span> <span m='813490'>going to</span>
  <span m='813800'>think</span> <span m='814120'>about --</span> <span m='815580'>first,</span>
  <span m='817000'>how</span> <span m='817360'>do --</span> <span m='819600'>how</span>
  <span m='820110'>to</span> <span m='820190'>decide</span> <span m='823360'>whether</span>
  <span m='824040'>the</span> <span m='824210'>xs</span> <span m='824780'>approach</span>
  <span m='825570'>the</span> <span m='825670'>correct</span> <span m='826070'>answer?</span>
  <span m='827300'>I</span> <span m='827660'>need</span> <span m='827910'>an</span>
  <span m='828030'>equation</span> <span m='828530'>for</span> <span m='828670'>the</span>
  <span m='828810'>error</span> <span m='829130'>and</span> <span m='829270'>because</span>
  <span m='830220'>my</span> <span m='830545'>equations</span> <span m='830870'>are</span>
  <span m='830980'>linear,</span> <span m='831410'>I'm</span> <span m='831580'>just</span>
  <span m='831800'>going to</span> <span m='835720'>subtract</span> <span m='836700'>the</span>
  <span m='836860'>upper</span> <span m='837430'>equation</span> <span m='838030'>from</span>
  <span m='838190'>the</span> <span m='838280'>lower</span> <span m='838590'>one</span>
  <span m='839470'>and</span> <span m='839660'>I'll</span> <span m='839830'>call</span>
  <span m='840250'>the --</span> <span m='840580'>so</span> <span m='840780'>the</span>
  <span m='840980'>error</span> <span m='842350'>ek</span> <span m='843210'>will</span>
  <span m='843460'>be</span> <span m='843830'>x</span> <span m='844420'>minus</span>
  <span m='844850'>the</span> <span m='844960'>true</span> <span m='845250'>answer.</span>
  <span m='846370'>This</span> <span m='846530'>is</span> <span m='847070'>x</span>
  <span m='847605'>exact.</span> <span m='848140'>Minus</span> <span m='848650'>x,</span>
  <span m='850930'>my</span> <span m='851400'>case</span> <span m='851780'>approximation.</span>
  <span m='853110'>So</span> <span m='853280'>when</span> <span m='853450'>I</span>
  <span m='853540'>subtract</span> <span m='854530'>that</span> <span m='854930'>from</span>
  <span m='855130'>that,</span> <span m='855820'>I</span> <span m='855940'>have</span>
  <span m='856350'>ek</span> <span m='857070'>plus</span> <span m='857310'>1</span>
  <span m='859720'>and</span> <span m='859850'>here</span> <span m='860060'>I</span>
  <span m='860200'>have</span> <span m='860570'>p</span> <span m='861000'>minus</span>
  <span m='861470'>a.</span> <span m='862510'>I</span> <span m='862690'>subtract</span>
  <span m='863200'>that</span> <span m='863450'>from</span> <span m='863610'>that.</span>
  <span m='863850'>I</span> <span m='863950'>have</span> <span m='864050'>ek</span>
  <span m='865380'>and</span> <span m='865600'>when</span> <span m='865750'>I</span>
  <span m='866020'>subtract</span> <span m='866310'>that</span> <span m='866530'>from</span>
  <span m='866690'>that,</span> <span m='866960'>0.</span> <span m='868280'>So</span>
  <span m='868690'>very</span> <span m='869120'>simple</span> <span m='870920'>error</span>
  <span m='871320'>equation.</span> <span m='872410'>so</span> <span m='872570'>this</span>
  <span m='872730'>is</span> <span m='872880'>an</span> <span m='872970'>equation,</span>
  <span m='873290'>this</span> <span m='873500'>would</span> <span m='873670'>be</span>
  <span m='873810'>the</span> <span m='873970'>error</span> <span m='874430'>equation.</span>
  <span m='883340'>You</span> <span m='883480'>see</span> <span m='883810'>the</span>
  <span m='884000'>b</span> <span m='884710'>has</span> <span m='884890'>disappeared,</span>
  <span m='887260'>because</span> <span m='887500'>I'm</span> <span m='888140'>only</span>
  <span m='888620'>looking</span> <span m='889620'>at</span> <span m='889820'>differences</span>
  <span m='890460'>now.</span> <span m='894440'>Let</span> <span m='894620'>me</span>
  <span m='894740'>write</span> <span m='895010'>that</span> <span m='895220'>over</span>
  <span m='895460'>on</span> <span m='895570'>this</span> <span m='895780'>board,</span>
  <span m='899090'>even</span> <span m='899440'>slightly</span> <span m='899950'>differently.</span>
  </p><p><span m='901380'>Now</span> <span m='901820'>I</span> <span m='902020'>will</span>
  <span m='903040'>multiply</span> <span m='903530'>through</span> <span m='903760'>by</span>
  <span m='903980'>p</span> <span m='904220'>inverse.</span> <span m='905360'>That</span>
  <span m='906130'>really</span> <span m='906440'>shows</span> <span m='906820'>it</span>
  <span m='907210'>just</span> <span m='907590'>so</span> <span m='907780'>clearly.</span>
  <span m='908670'>So</span> <span m='908835'>the</span> <span m='909000'>new</span>
  <span m='909230'>error</span> <span m='911250'>is,</span> <span m='911960'>if</span>
  <span m='912120'>I</span> <span m='912300'>multiply</span> <span m='912570'>by</span>
  <span m='912780'>p</span> <span m='912990'>inverse,</span> <span m='915600'>p</span>
  <span m='915900'>inverse</span> <span m='916160'>times</span> <span m='916480'>p</span>
  <span m='916970'>is</span> <span m='917260'>i</span> <span m='919360'>and</span>
  <span m='919660'>I</span> <span m='919720'>have</span> <span m='919970'>p</span>
  <span m='920170'>inverse</span> <span m='920610'>aek.</span> <span m='929500'>So</span>
  <span m='929690'>what</span> <span m='929900'>does</span> <span m='930030'>that</span>
  <span m='930220'>say?</span> <span m='931300'>That</span> <span m='931480'>says</span>
  <span m='931810'>that</span> <span m='931980'>at</span> <span m='932090'>every</span>
  <span m='932710'>iteration,</span> <span m='935130'>I</span> <span m='935260'>multiply</span>
  <span m='936340'>the</span> <span m='936530'>error</span> <span m='937160'>by</span>
  <span m='937350'>that</span> <span m='937640'>matrix.</span> <span m='940380'>Of</span>
  <span m='940470'>course,</span> <span m='940900'>if</span> <span m='941080'>p</span>
  <span m='941480'>equals</span> <span m='942000'>a,</span> <span m='942300'>if</span>
  <span m='942470'>I</span> <span m='942610'>pick</span> <span m='944410'>the</span>
  <span m='944520'>perfect</span> <span m='945070'>preconditioner,</span> <span m='947580'>then</span>
  <span m='949380'>p</span> <span m='949590'>inverse</span> <span m='949800'>a</span>
  <span m='949990'>is</span> <span m='950180'>the</span> <span m='950290'>identity.</span>
  <span m='950920'>This</span> <span m='951180'>is</span> <span m='951340'>the</span>
  <span m='951460'>0</span> <span m='951770'>matrix</span> <span m='952310'>and</span>
  <span m='952580'>the</span> <span m='952985'>error</span> <span m='953390'>in</span>
  <span m='953510'>the</span> <span m='953630'>first</span> <span m='953930'>step</span>
  <span m='954300'>is</span> <span m='954450'>0.</span> <span m='955390'>I'm</span>
  <span m='955570'>solving</span> <span m='956180'>exactly.</span> <span m='957140'>I</span>
  <span m='957260'>don't</span> <span m='957510'>plan</span> <span m='957760'>to</span>
  <span m='957890'>do</span> <span m='958040'>that.</span> <span m='959360'>I</span>
  <span m='959500'>plan</span> <span m='960100'>to</span> <span m='961360'>have</span>
  <span m='961650'>a</span> <span m='961810'>p</span> <span m='963010'>that's</span>
  <span m='963220'>close</span> <span m='963610'>to</span> <span m='963780'>a,</span>
  <span m='964030'>so</span> <span m='964300'>in</span> <span m='964510'>some</span>
  <span m='964770'>way,</span> <span m='965820'>this</span> <span m='965990'>should</span>
  <span m='966240'>be</span> <span m='966410'>close</span> <span m='966880'>to</span>
  <span m='967010'>i.</span> <span m='967810'>This</span> <span m='968000'>whole</span>
  <span m='968230'>matrix</span> <span m='968750'>should</span> <span m='968930'>be</span>
  <span m='969120'>close</span> <span m='969900'>to</span> <span m='970030'>0,</span>
  <span m='972880'>close</span> <span m='973270'>in</span> <span m='973440'>some</span>
  <span m='973740'>sense.</span> <span m='974130'>Let</span> <span m='974260'>me</span>
  <span m='974390'>give</span> <span m='974620'>a</span> <span m='974710'>name</span>
  <span m='975120'>for</span> <span m='975280'>that</span> <span m='975530'>matrix.</span>
  <span m='976620'>Let 's</span> <span m='976880'>call</span> <span m='977080'>that</span>
  <span m='977270'>matrix</span> <span m='977800'>m.</span> <span m='979030'>So</span>
  <span m='981420'>that's</span> <span m='981730'>the</span> <span m='982700'>iteration</span>
  <span m='983410'>matrix,</span> <span m='985240'>which</span> <span m='985640'>we're</span>
  <span m='985840'>never</span> <span m='986190'>going</span> <span m='986470'>to</span>
  <span m='987760'>display.</span> <span m='988970'>I</span> <span m='989070'>mean,</span>
  <span m='989210'>it</span> <span m='989290'>would</span> <span m='989430'>be</span>
  <span m='989560'>madness</span> <span m='990120'>to</span> <span m='990280'>display.</span>
  <span m='990750'>We</span> <span m='990920'>don't</span> <span m='991140'>want</span>
  <span m='991340'>to</span> <span m='991410'>compute</span> <span m='992180'>p</span>
  <span m='992400'>inverse</span> <span m='994340'>explicitly</span> <span m='995500'>or</span>
  <span m='995660'>display</span> <span m='996140'>it,</span> <span m='996520'>but</span>
  <span m='996900'>to</span> <span m='997080'>understand</span> <span m='997800'>it
  --</span> <span m='998810'>to</span> <span m='999000'>understand</span> <span m='999640'>convergence</span>
  <span m='1000330'>or</span> <span m='1000440'>not</span> <span m='1000740'>covergence,</span>
  <span m='1001960'>it's</span> <span m='1002230'>m</span> <span m='1003480'>that</span>
  <span m='1003640'>controls</span> <span m='1004160'>everything.</span> </p><p><span
  m='1005120'>So</span> <span m='1005640'>this</span> <span m='1005960'>is</span>
  <span m='1006150'>what</span> <span m='1006350'>I</span> <span m='1006450'>would</span>
  <span m='1006650'>call</span> <span m='1007080'>pure</span> <span m='1007470'>iteration</span>
  <span m='1008610'>or</span> <span m='1008790'>maybe</span> <span m='1011730'>another</span>
  <span m='1012160'>word</span> <span m='1012510'>that's</span> <span m='1012800'>used</span>
  <span m='1013260'>instead</span> <span m='1013610'>of</span> <span m='1013800'>pure</span>
  <span m='1014330'>is</span> <span m='1015060'>stationary</span> <span m='1016030'>iteration.</span>
  <span m='1016630'>What</span> <span m='1016850'>does</span> <span m='1016970'>stationary</span>
  <span m='1017620'>mean?</span> <span m='1018430'>It</span> <span m='1018620'>means</span>
  <span m='1018890'>that</span> <span m='1019050'>you</span> <span m='1019160'>do</span>
  <span m='1019310'>the</span> <span m='1019450'>same</span> <span m='1019710'>thing</span>
  <span m='1019930'>all</span> <span m='1020060'>the</span> <span m='1020180'>time.</span>
  <span m='1021380'>At</span> <span m='1021580'>every</span> <span m='1021870'>step,</span>
  <span m='1023620'>you</span> <span m='1023790'>just</span> <span m='1025340'>use</span>
  <span m='1025580'>the</span> <span m='1025700'>same</span> <span m='1025970'>equation,</span>
  <span m='1027330'>where</span> <span m='1030810'>these</span> <span m='1031110'>methods</span>
  <span m='1031710'>will</span> <span m='1032190'>be</span> <span m='1033250'>smarter.</span>
  <span m='1035690'>They'll</span> <span m='1035930'>adapt.</span> <span m='1036530'>They'll</span>
  <span m='1036710'>use</span> <span m='1037040'>more</span> <span m='1037290'>information.</span>
  <span m='1037960'>They'll</span> <span m='1038090'>converge</span> <span m='1038570'>faster,</span>
  <span m='1039710'>but</span> <span m='1040020'>this</span> <span m='1040240'>is</span>
  <span m='1040430'>the</span> <span m='1040730'>simple</span> <span m='1041120'>one
  --</span> <span m='1042450'>and</span> <span m='1043060'>this</span> <span m='1043360'>one</span>
  <span m='1043700'>plays</span> <span m='1044100'>a</span> <span m='1044270'>part</span>
  <span m='1044650'>in</span> <span m='1045040'>those.</span> </p><p><span m='1046830'>So</span>
  <span m='1047830'>what's</span> <span m='1048130'>the</span> <span m='1048280'>story</span>
  <span m='1048660'>on</span> <span m='1048890'>convergence</span> <span m='1049640'>now?</span>
  <span m='1052310'>What</span> <span m='1052790'>about</span> <span m='1053230'>that</span>
  <span m='1053480'>matrix</span> <span m='1053990'>m?</span> <span m='1055690'>If</span>
  <span m='1056050'>I</span> <span m='1056200'>take</span> <span m='1056440'>a</span>
  <span m='1056540'>starting</span> <span m='1057000'>vector,</span> <span m='1057370'>e</span>
  <span m='1057910'>0 --</span> <span m='1058940'>my</span> <span m='1059200'>initial</span>
  <span m='1059620'>error</span> <span m='1059970'>could</span> <span m='1060200'>be</span>
  <span m='1060330'>anything --</span> <span m='1061430'>I</span> <span m='1061570'>multiply</span>
  <span m='1062270'>by</span> <span m='1062500'>m</span> <span m='1063760'>to</span>
  <span m='1063900'>get</span> <span m='1064090'>e</span> <span m='1064220'>1.</span>
  <span m='1065620'>Then</span> <span m='1065790'>I</span> <span m='1065950'>multiply</span>
  <span m='1066330'>m</span> <span m='1066650'>by</span> <span m='1066910'>m</span>
  <span m='1067060'>again</span> <span m='1067410'>to</span> <span m='1067510'>get</span>
  <span m='1067670'>e</span> <span m='1067860'>2.</span> <span m='1068900'>Everu</span>
  <span m='1069280'>step,</span> <span m='1069610'>I</span> <span m='1069750'>multiply</span>
  <span m='1070250'>by</span> <span m='1070520'>m.</span> <span m='1072040'>So</span>
  <span m='1072200'>after</span> <span m='1072940'>k</span> <span m='1073540'>steps,</span>
  <span m='1074580'>I've</span> <span m='1074910'>multiplied</span> <span m='1076130'>k</span>
  <span m='1076410'>times</span> <span m='1076980'>by</span> <span m='1077300'>m.</span>
  <span m='1078800'>I</span> <span m='1078910'>want</span> <span m='1079170'>to</span>
  <span m='1079230'>know --</span> <span m='1081240'>so</span> <span m='1081350'>the</span>
  <span m='1081500'>key</span> <span m='1081760'>question</span> <span m='1082270'>is,</span>
  <span m='1082540'>does</span> <span m='1082700'>that</span> <span m='1082900'>go</span>
  <span m='1083050'>to</span> <span m='1083170'>0?</span> <span m='1084690'>So</span>
  <span m='1085200'>the</span> <span m='1085360'>question,</span> <span m='1085830'>does</span>
  <span m='1086090'>it</span> <span m='1086200'>go</span> <span m='1086340'>to</span>
  <span m='1086430'>0</span> <span m='1086920'>and</span> <span m='1087340'>if</span>
  <span m='1087500'>it</span> <span m='1087590'>does,</span> <span m='1088220'>how</span>
  <span m='1088440'>fast?</span> <span m='1094460'>The</span> <span m='1095360'>two</span>
  <span m='1095520'>parts,</span> <span m='1096100'>does</span> <span m='1096370'>it</span>
  <span m='1096500'>go</span> <span m='1096640'>to</span> <span m='1096780'>0</span>
  <span m='1097260'>and</span> <span m='1097480'>how</span> <span m='1097690'>fast</span>
  <span m='1098600'>are</span> <span m='1098780'>pretty</span> <span m='1099140'>much</span>
  <span m='1100040'>controlled</span> <span m='1100630'>by</span> <span m='1100760'>the</span>
  <span m='1100930'>same</span> <span m='1102700'>property</span> <span m='1103540'>of</span>
  <span m='1103860'>m.</span> <span m='1104180'>So</span> <span m='1104350'>what's</span>
  <span m='1104680'>the</span> <span m='1104810'>answer?</span> <span m='1105220'>When</span>
  <span m='1105630'>does --</span> <span m='1107380'>if</span> <span m='1107570'>I</span>
  <span m='1107740'>take --</span> <span m='1108500'>I</span> <span m='1108690'>don't</span>
  <span m='1108900'>know</span> <span m='1109000'>anything</span> <span m='1109300'>about</span>
  <span m='1109500'>e</span> <span m='1109650'>0,</span> <span m='1111360'>so</span>
  <span m='1111530'>what</span> <span m='1112170'>property</span> <span m='1112780'>of</span>
  <span m='1112970'>m</span> <span m='1113820'>is</span> <span m='1114010'>going</span>
  <span m='1114190'>to</span> <span m='1114280'>decide</span> <span m='1114990'>whether</span>
  <span m='1115390'>its</span> <span m='1115590'>powers</span> <span m='1117260'>get</span>
  <span m='1117470'>small,</span> <span m='1118030'>go</span> <span m='1118190'>to</span>
  <span m='1118310'>0,</span> <span m='1119280'>so</span> <span m='1119440'>that</span>
  <span m='1120010'>the</span> <span m='1120250'>error</span> <span m='1120610'>goes</span>
  <span m='1120920'>to</span> <span m='1121335'>0?</span> <span m='1121750'>That's</span>
  <span m='1122010'>convergence.</span> <span m='1124890'>Maybe</span> <span m='1127160'>wall</span>
  <span m='1127470'>up</span> <span m='1128950'>or</span> <span m='1129130'>maybe</span>
  <span m='1129950'>stay</span> <span m='1131090'>away</span> <span m='1131410'>from</span>
  <span m='1131690'>0.</span> <span m='1132790'>What</span> <span m='1133040'>controls</span>
  <span m='1133870'>it?</span> </p><p><span m='1136590'>One</span> <span m='1136870'>word</span>
  <span m='1137570'>is</span> <span m='1137690'>the</span> <span m='1137810'>answer.</span>
  <span m='1139090'>The</span> <span m='1139330'>eigenvalues.</span> <span m='1140240'>It's</span>
  <span m='1140410'>the</span> <span m='1140560'>eigenvalues</span> <span m='1141460'>of</span>
  <span m='1141570'>m,</span> <span m='1142530'>and</span> <span m='1142810'>in</span>
  <span m='1142930'>particular,</span> <span m='1143590'>it's</span> <span m='1143760'>the</span>
  <span m='1143880'>biggest.</span> <span m='1147810'>If</span> <span m='1147980'>I</span>
  <span m='1148060'>have</span> <span m='1148270'>an</span> <span m='1148370'>eigenvalue</span>
  <span m='1149110'>of</span> <span m='1149220'>m,</span> <span m='1151340'>as</span>
  <span m='1151530'>far</span> <span m='1151740'>as</span> <span m='1151850'>I</span>
  <span m='1151960'>know,</span> <span m='1152240'>e-not</span> <span m='1152800'>could</span>
  <span m='1153060'>be</span> <span m='1153230'>the</span> <span m='1153390'>eigenvector</span>
  <span m='1155060'>and</span> <span m='1155310'>then</span> <span m='1156220'>every</span>
  <span m='1156590'>step</span> <span m='1156950'>would</span> <span m='1157140'>multiply</span>
  <span m='1157610'>by</span> <span m='1157780'>that</span> <span m='1158020'>eigenvalue</span>
  <span m='1158650'>lambda.</span> <span m='1159700'>So</span> <span m='1159850'>the</span>
  <span m='1159990'>condition</span> <span m='1160530'>is</span> <span m='1162620'>all</span>
  <span m='1165470'>eigenvalues</span> <span m='1166330'>of</span> <span m='1166440'>m</span>
  <span m='1167860'>have</span> <span m='1168010'>to</span> <span m='1168130'>be</span>
  <span m='1168930'>smaller</span> <span m='1169420'>than</span> <span m='1169570'>1</span>
  <span m='1170470'>and</span> <span m='1171290'>in</span> <span m='1171940'>magnitude</span>
  <span m='1172550'>of</span> <span m='1172660'>course,</span> <span m='1172940'>because</span>
  <span m='1173100'>they</span> <span m='1173230'>could</span> <span m='1173460'>be</span>
  <span m='1173580'>negative,</span> <span m='1174030'>they</span> <span m='1174200'>could</span>
  <span m='1174400'>be</span> <span m='1174550'>complex.</span> <span m='1178890'>So</span>
  <span m='1179600'>that's</span> <span m='1180010'>the</span> <span m='1180140'>total</span>
  <span m='1180580'>condition,</span> <span m='1181080'>that's</span> <span m='1181540'>exactly</span>
  <span m='1182070'>the</span> <span m='1182200'>requirement</span> <span m='1182820'>on</span>
  <span m='1183040'>m.</span> <span m='1185640'>How</span> <span m='1185900'>do</span>
  <span m='1185990'>we</span> <span m='1186170'>say</span> <span m='1186530'>how</span>
  <span m='1186790'>fast</span> <span m='1187290'>they</span> <span m='1187430'>go</span>
  <span m='1187590'>to</span> <span m='1187710'>0?</span> <span m='1188950'>How</span>
  <span m='1189230'>fast --</span> <span m='1190010'>if</span> <span m='1190190'>all</span>
  <span m='1190350'>the</span> <span m='1190480'>eigenvalues</span> <span m='1191110'>are</span>
  <span m='1191190'>below</span> <span m='1191790'>1,</span> <span m='1193000'>then</span>
  <span m='1193440'>the</span> <span m='1193580'>slowest</span> <span m='1197180'>convergence</span>
  <span m='1197790'>is</span> <span m='1197970'>going</span> <span m='1198160'>to</span>
  <span m='1198250'>come</span> <span m='1199470'>for</span> <span m='1199870'>the</span>
  <span m='1200150'>eigenvalue</span> <span m='1200570'>that's</span> <span m='1200720'>the</span>
  <span m='1200870'>closest</span> <span m='1201440'>to</span> <span m='1201530'>1.</span>
  <span m='1202140'>So</span> <span m='1202370'>really</span> <span m='1202870'>it</span>
  <span m='1203070'>will</span> <span m='1203270'>be --</span> <span m='1204370'>and</span>
  <span m='1204630'>this</span> <span m='1206510'>is</span> <span m='1206670'>called</span>
  <span m='1207090'>the</span> <span m='1207390'>spectral</span> <span m='1209340'>radius</span>
  <span m='1211720'>and</span> <span m='1212220'>it's</span> <span m='1212970'>usually</span>
  <span m='1213500'>denoted</span> <span m='1214050'>by</span> <span m='1214400'>a</span>
  <span m='1214640'>Greek</span> <span m='1214880'>row</span> <span m='1215470'>of</span>
  <span m='1215670'>m,</span> <span m='1216890'>which</span> <span m='1217130'>is</span>
  <span m='1217380'>the</span> <span m='1217500'>maximum</span> <span m='1218130'>of</span>
  <span m='1218250'>these</span> <span m='1218500'>guys.</span> <span m='1219540'>It's</span>
  <span m='1219740'>the</span> <span m='1219840'>max</span> <span m='1221850'>of</span>
  <span m='1222160'>the</span> <span m='1222340'>eigenvalues</span> <span m='1223710'>and</span>
  <span m='1223920'>that</span> <span m='1224110'>has</span> <span m='1224370'>to</span>
  <span m='1224470'>be</span> <span m='1224660'>below</span> <span m='1225060'>1.</span>
  <span m='1226320'>So</span> <span m='1226540'>it's</span> <span m='1226700'>this</span>
  <span m='1226920'>number,</span> <span m='1228500'>that</span> <span m='1228720'>number,</span>
  <span m='1231090'>because</span> <span m='1231450'>it's</span> <span m='1231700'>that</span>
  <span m='1231990'>number</span> <span m='1232420'>which</span> <span m='1233360'>really</span>
  <span m='1233720'>says</span> <span m='1234980'>what</span> <span m='1235280'>I'm</span>
  <span m='1235450'>multiplying</span> <span m='1235990'>by</span> <span m='1236230'>it</span>
  <span m='1236310'>every</span> <span m='1236540'>step.</span> <span m='1238100'>Most</span>
  <span m='1238460'>likely,</span> <span m='1240160'>e-not,</span> <span m='1240420'>my</span>
  <span m='1240570'>initial</span> <span m='1241460'>unknown</span> <span m='1241930'>error</span>
  <span m='1242640'>has</span> <span m='1242910'>some</span> <span m='1243260'>component</span>
  <span m='1244900'>in</span> <span m='1245150'>the</span> <span m='1245270'>direction</span>
  <span m='1245850'>of</span> <span m='1245990'>this</span> <span m='1247490'>biggest</span>
  <span m='1247890'>eigenvalue,</span> <span m='1249440'>in</span> <span m='1249680'>the</span>
  <span m='1249790'>direction</span> <span m='1250130'>of</span> <span m='1250230'>its</span>
  <span m='1250460'>eigenvector.</span> <span m='1252300'>Then</span> <span m='1252480'>that</span>
  <span m='1253040'>component</span> <span m='1254390'>will</span> <span m='1254580'>multiply</span>
  <span m='1255160'>at</span> <span m='1255250'>every</span> <span m='1255480'>step</span>
  <span m='1255960'>by</span> <span m='1256210'>lambda,</span> <span m='1256810'>but</span>
  <span m='1258040'>that</span> <span m='1258250'>one</span> <span m='1258450'>will</span>
  <span m='1258590'>be</span> <span m='1258910'>the</span> <span m='1259060'>biggest</span>
  <span m='1259560'>guy,</span> <span m='1259800'>rho.</span> <span m='1262910'>So</span>
  <span m='1263060'>it's</span> <span m='1263280'>the</span> <span m='1263410'>maximum</span>
  <span m='1263940'>eigenvalue.</span> </p><p><span m='1265170'>That's</span> <span
  m='1265400'>really</span> <span m='1265680'>what</span> <span m='1265890'>it</span>
  <span m='1265970'>comes</span> <span m='1266330'>to.</span> <span m='1266690'>What</span>
  <span m='1267170'>is</span> <span m='1267400'>the</span> <span m='1267500'>maximum</span>
  <span m='1268060'>eigenvalue?</span> <span m='1269230'>Let</span> <span m='1269400'>me</span>
  <span m='1269530'>take</span> <span m='1269930'>Jacobi.</span> <span m='1271900'>Can</span>
  <span m='1272120'>we</span> <span m='1272260'>figure</span> <span m='1272620'>out</span>
  <span m='1272880'>the</span> <span m='1273000'>maximum</span> <span m='1273690'>eigenvalue</span>
  <span m='1274540'>for</span> <span m='1274800'>Jacobi?</span> <span m='1277440'>Of</span>
  <span m='1277530'>course,</span> <span m='1279470'>if</span> <span m='1279680'>I</span>
  <span m='1279750'>don't</span> <span m='1279980'>know</span> <span m='1280100'>anything</span>
  <span m='1280470'>about</span> <span m='1280720'>the</span> <span m='1280810'>matrix,</span>
  <span m='1282540'>I</span> <span m='1282670'>certainly</span> <span m='1283030'>don't</span>
  <span m='1283230'>want</span> <span m='1283390'>to</span> <span m='1283450'>compute</span>
  <span m='1284010'>eigenvalues.</span> <span m='1286840'>I</span> <span m='1286970'>could</span>
  <span m='1287190'>run</span> <span m='1287840'>Jacobi's</span> <span m='1288320'>method.</span>
  <span m='1289450'>So</span> <span m='1289650'>again,</span> <span m='1290280'>Jacobi's</span>
  <span m='1290670'>method,</span> <span m='1291500'>I'm</span> <span m='1291670'>taking</span>
  <span m='1292110'>p</span> <span m='1292430'>to</span> <span m='1292570'>be</span>
  <span m='1292730'>the</span> <span m='1292890'>diagonal</span> <span m='1293380'>part,</span>
  <span m='1293660'>but</span> <span m='1293840'>let</span> <span m='1293990'>me</span>
  <span m='1294100'>make</span> <span m='1294340'>that</span> <span m='1294540'>explicit</span>
  <span m='1295570'>and</span> <span m='1295910'>let</span> <span m='1296010'>me</span>
  <span m='1296130'>take</span> <span m='1297650'>the</span> <span m='1297810'>matrix</span>
  <span m='1298310'>that</span> <span m='1298470'>we</span> <span m='1298600'>know</span>
  <span m='1298810'>the</span> <span m='1298950'>best.</span> <span m='1300180'>I'll</span>
  <span m='1300370'>call</span> <span m='1300610'>it</span> <span m='1300810'>k.</span>
  <span m='1302160'>So</span> <span m='1302775'>k</span> <span m='1303390'>or</span>
  <span m='1303680'>a --</span> <span m='1304580'>this</span> <span m='1304780'>is</span>
  <span m='1304865'>the</span> <span m='1304950'>a --</span> <span m='1305850'>is</span>
  <span m='1306220'>my</span> <span m='1307560'>friend</span> <span m='1308650'>with</span>
  <span m='1308920'>2s</span> <span m='1309330'>on</span> <span m='1309520'>the</span>
  <span m='1309610'>diagonal</span> <span m='1310440'>minus</span> <span m='1310890'>1s</span>
  <span m='1311340'>above.</span> <span m='1311820'>I</span> <span m='1311960'>apologize
  --</span> <span m='1314280'>I</span> <span m='1314380'>don't</span> <span m='1314680'>really</span>
  <span m='1315020'>apologize,</span> <span m='1315760'>but</span> <span m='1316860'>I'll</span>
  <span m='1318150'>pretend</span> <span m='1318530'>to</span> <span m='1318640'>apologize</span>
  <span m='1319770'>for</span> <span m='1321260'>bringing</span> <span m='1321670'>this</span>
  <span m='1321860'>matrix</span> <span m='1322390'>in</span> <span m='1322630'>so</span>
  <span m='1322840'>often.</span> <span m='1327040'>Do</span> <span m='1327170'>we</span>
  <span m='1327320'>remember</span> <span m='1327820'>its</span> <span m='1328060'>eigenvalues?</span>
  <span m='1334780'>We</span> <span m='1335000'>computed</span> <span m='1335550'>them</span>
  <span m='1336030'>last</span> <span m='1336460'>semester,</span> <span m='1337030'>but</span>
  <span m='1337530'>that's</span> <span m='1338980'>another</span> <span m='1339290'>world.</span>
  <span m='1342180'>I'll</span> <span m='1342440'>say</span> <span m='1342680'>what</span>
  <span m='1342910'>they</span> <span m='1343070'>are.</span> <span m='1344900'>The</span>
  <span m='1345120'>eigenvalues</span> <span m='1346940'>of</span> <span m='1347170'>a
  --</span> <span m='1347920'>this</span> <span m='1348180'>is</span> <span m='1348380'>an</span>
  <span m='1348550'>m</span> <span m='1348720'>now --</span> <span m='1349830'>the</span>
  <span m='1350090'>eigenvalues</span> <span m='1350550'>of</span> <span m='1350760'>this</span>
  <span m='1351180'>matrix</span> <span m='1351650'>a --</span> <span m='1353170'>I</span>
  <span m='1353340'>see</span> <span m='1353650'>2s</span> <span m='1354110'>on</span>
  <span m='1354240'>the</span> <span m='1354340'>diagonal.</span> <span m='1356140'>So</span>
  <span m='1356270'>that's</span> <span m='1356660'>a</span> <span m='1356790'>2.</span>
  <span m='1357460'>That</span> <span m='1357680'>accounts</span> <span m='1358120'>for</span>
  <span m='1358320'>the</span> <span m='1358460'>diagonal</span> <span m='1358890'>part,</span>
  <span m='1359210'>2</span> <span m='1359390'>times</span> <span m='1359700'>the</span>
  <span m='1359870'>identity.</span> <span m='1361240'>I</span> <span m='1361300'>have</span>
  <span m='1361420'>a</span> <span m='1361510'>minus</span> <span m='1362870'>and</span>
  <span m='1363055'>then</span> <span m='1363240'>the</span> <span m='1363440'>part</span>
  <span m='1363640'>that</span> <span m='1363840'>comes</span> <span m='1364230'>from</span>
  <span m='1364440'>these</span> <span m='1365960'>1s,</span> <span m='1367580'>which</span>
  <span m='1367790'>are</span> <span m='1367940'>forward</span> <span m='1368570'>and</span>
  <span m='1368740'>back.</span> </p><p><span m='1369460'>What</span> <span m='1369555'>would</span>
  <span m='1369650'>von</span> <span m='1369840'>Neumann</span> <span m='1370080'>say?</span>
  <span m='1371360'>What</span> <span m='1371550'>would</span> <span m='1371730'>von</span>
  <span m='1371960'>Neumann</span> <span m='1372350'>do</span> <span m='1372490'>with</span>
  <span m='1372640'>that</span> <span m='1372940'>matrix?</span> <span m='1373580'>Of</span>
  <span m='1373760'>course,</span> <span m='1374860'>he</span> <span m='1375070'>would</span>
  <span m='1377540'>tested</span> <span m='1378150'>on</span> <span m='1379020'>exponentials</span>
  <span m='1381210'>and</span> <span m='1381820'>he</span> <span m='1382050'>would</span>
  <span m='1382420'>get</span> <span m='1382640'>2</span> <span m='1383590'>minus</span>
  <span m='1385190'>e</span> <span m='1385380'>to</span> <span m='1385440'>the</span>
  <span m='1385570'>ik</span> <span m='1387020'>minus</span> <span m='1387840'>e</span>
  <span m='1388200'>to</span> <span m='1388235'>the</span> <span m='1388270'>minus</span>
  <span m='1388720'>ik.</span> <span m='1391050'>He</span> <span m='1391190'>would</span>
  <span m='1391420'>put</span> <span m='1391690'>the</span> <span m='1392400'>two</span>
  <span m='1392630'>exponentials</span> <span m='1393400'>together</span> <span m='1393860'>into</span>
  <span m='1394100'>cosines</span> <span m='1395100'>and</span> <span m='1395270'>that's</span>
  <span m='1395550'>the</span> <span m='1396095'>answer.</span> <span m='1396640'>It's</span>
  <span m='1396860'>2</span> <span m='1397090'>minus</span> <span m='1397530'>2</span>
  <span m='1397910'>cosines</span> <span m='1398850'>of</span> <span m='1399270'>whatever</span>
  <span m='1399690'>angel's</span> <span m='1400190'>theta.</span> <span m='1401500'>Those</span>
  <span m='1401750'>are</span> <span m='1401840'>the</span> <span m='1401990'>eigenvalues.</span>
  <span m='1403590'>The</span> <span m='1403840'>j'th</span> <span m='1404680'>eigenvalue</span>
  <span m='1407910'>is --</span> <span m='1408430'>the</span> <span m='1408630'>cosine</span>
  <span m='1409260'>is</span> <span m='1409410'>at</span> <span m='1409630'>some</span>
  <span m='1409870'>angle</span> <span m='1410630'>theta</span> <span m='1411250'>j.</span>
  <span m='1413020'>It's</span> <span m='1413200'>worth</span> <span m='1413580'>since
  --</span> <span m='1414900'>maybe</span> <span m='1415190'>just</span> <span m='1415470'>to</span>
  <span m='1415570'>take</span> <span m='1415830'>again</span> <span m='1416200'>a</span>
  <span m='1416270'>minute</span> <span m='1416720'>on</span> <span m='1416960'>this</span>
  <span m='1417190'>matrix.</span> <span m='1419180'>So</span> <span m='1419390'>the</span>
  <span m='1419510'>eigenvalues</span> <span m='1420250'>are</span> <span m='1420320'>between</span>
  <span m='1420880'>0</span> <span m='1421430'>and</span> <span m='1421610'>4.</span>
  <span m='1422670'>The</span> <span m='1422840'>eigenvalues</span> <span m='1423250'>never</span>
  <span m='1423480'>go</span> <span m='1423610'>negative,</span> <span m='1424130'>right?</span>
  <span m='1424420'>Because</span> <span m='1424760'>the</span> <span m='1424860'>cosine</span>
  <span m='1426820'>can't</span> <span m='1427060'>be</span> <span m='1427170'>bigger</span>
  <span m='1427430'>than</span> <span m='1427580'>1.</span> <span m='1428890'>Actually,</span>
  <span m='1429390'>for</span> <span m='1429560'>this</span> <span m='1429800'>matrix</span>
  <span m='1430400'>the</span> <span m='1430530'>cosine</span> <span m='1431080'>doesn't</span>
  <span m='1431520'>reach</span> <span m='1431850'>1.</span> <span m='1432910'>So</span>
  <span m='1433180'>the</span> <span m='1433570'>smallest</span> <span m='1434090'>eigenvalue</span>
  <span m='1434920'>is</span> <span m='1435110'>2</span> <span m='1435410'>minus</span>
  <span m='1435910'>2</span> <span m='1436990'>times</span> <span m='1437340'>that</span>
  <span m='1438100'>cosine</span> <span m='1438810'>close</span> <span m='1439270'>to</span>
  <span m='1439390'>1.</span> <span m='1443210'>It's</span> <span m='1443540'>too</span>
  <span m='1443750'>close</span> <span m='1444210'>for</span> <span m='1444370'>comfort,</span>
  <span m='1444830'>but</span> <span m='1446530'>it</span> <span m='1446730'>is</span>
  <span m='1448000'>below</span> <span m='1448290'>1.</span> <span m='1450040'>The</span>
  <span m='1450130'>eigenvalues</span> <span m='1450760'>are</span> <span m='1450860'>positive</span>
  <span m='1452790'>and</span> <span m='1453620'>they're</span> <span m='1453760'>between</span>
  <span m='1454420'>0</span> <span m='1454690'>and</span> <span m='1454850'>4.</span>
  <span m='1457560'>At</span> <span m='1457770'>the</span> <span m='1457900'>other</span>
  <span m='1458190'>extreme,</span> <span m='1459260'>theta</span> <span m='1459460'>is</span>
  <span m='1459690'>near</span> <span m='1460960'>pi.</span> <span m='1462620'>The</span>
  <span m='1462760'>cosine</span> <span m='1463270'>is</span> <span m='1463430'>near</span>
  <span m='1463690'>minus</span> <span m='1464190'>1</span> <span m='1464670'>and</span>
  <span m='1464880'>we</span> <span m='1465000'>have</span> <span m='1465220'>something</span>
  <span m='1465640'>near</span> <span m='1465800'>4.</span> <span m='1466430'>So</span>
  <span m='1466610'>the</span> <span m='1466730'>eigenvalues</span> <span m='1467430'>of</span>
  <span m='1467550'>that --</span> <span m='1467920'>if</span> <span m='1468070'>you</span>
  <span m='1468220'>look</span> <span m='1468440'>at</span> <span m='1468530'>that</span>
  <span m='1468730'>matrix,</span> <span m='1468890'>you</span> <span m='1469286'>should</span>
  <span m='1469683'>see.</span> <span m='1472050'>Special</span> <span m='1472550'>matrix</span>
  <span m='1473170'>eigenvalues</span> <span m='1474640'>in</span> <span m='1474810'>this</span>
  <span m='1475020'>interval</span> <span m='1475510'>0</span> <span m='1475790'>to</span>
  <span m='1475920'>4.</span> <span m='1478650'>The</span> <span m='1479230'>key</span>
  <span m='1479600'>point</span> <span m='1479990'>is,</span> <span m='1480210'>how</span>
  <span m='1480580'>close</span> <span m='1481070'>to</span> <span m='1481220'>0?</span>
  </p><p><span m='1482300'>Now</span> <span m='1482430'>what</span> <span m='1482640'>about</span>
  <span m='1482920'>m --</span> <span m='1483730'>what</span> <span m='1483910'>about</span>
  <span m='1484340'>p</span> <span m='1484730'>first?</span> <span m='1485210'>What's</span>
  <span m='1485480'>p?</span> <span m='1488195'>For</span> <span m='1488370'>Jacobi,</span>
  <span m='1489600'>so</span> <span m='1489860'>p</span> <span m='1490310'>for</span>
  <span m='1490700'>Jacobi</span> <span m='1493880'>is</span> <span m='1495330'>the</span>
  <span m='1495460'>diagonal</span> <span m='1496020'>part,</span> <span m='1496290'>which</span>
  <span m='1496490'>is</span> <span m='1496630'>exactly</span> <span m='1497180'>2</span>
  <span m='1497420'>i.</span> <span m='1499680'>That's</span> <span m='1499970'>a</span>
  <span m='1500050'>very</span> <span m='1500350'>simple</span> <span m='1501800'>diagonal</span>
  <span m='1502380'>part,</span> <span m='1503590'>very</span> <span m='1503830'>simple</span>
  <span m='1504180'>p.</span> <span m='1507620'>It</span> <span m='1507820'>produces</span>
  <span m='1508400'>the</span> <span m='1508480'>matrix</span> <span m='1508950'>m.</span>
  <span m='1510620'>You</span> <span m='1510780'>remember</span> <span m='1511080'>m</span>
  <span m='1511630'>is</span> <span m='1512090'>the</span> <span m='1512220'>identity</span>
  <span m='1512810'>matrix</span> <span m='1513420'>minus</span> <span m='1514480'>p</span>
  <span m='1514800'>inverse</span> <span m='1514940'>a.</span> <span m='1521540'>That's</span>
  <span m='1521810'>beautiful.</span> <span m='1522790'>So</span> <span m='1524620'>p</span>
  <span m='1524830'>is</span> <span m='1524990'>just</span> <span m='1525240'>2</span>
  <span m='1525400'>i.</span> <span m='1525740'>So</span> <span m='1526010'>I'm</span>
  <span m='1526160'>just</span> <span m='1526420'>dividing</span> <span m='1527000'>a</span>
  <span m='1527250'>by</span> <span m='1527540'>2,</span> <span m='1531240'>which</span>
  <span m='1531540'>puts</span> <span m='1531690'>a</span> <span m='1531780'>1</span>
  <span m='1532110'>there</span> <span m='1533450'>and</span> <span m='1533740'>then</span>
  <span m='1533970'>subtracting</span> <span m='1534640'>from</span> <span m='1534810'>the</span>
  <span m='1534920'>identity.</span> <span m='1535430'>So</span> <span m='1535610'>it</span>
  <span m='1535720'>has</span> <span m='1535920'>0s</span> <span m='1536340'>on</span>
  <span m='1536480'>the</span> <span m='1536580'>diagonal.</span> <span m='1537220'>That's</span>
  <span m='1537600'>what</span> <span m='1537780'>we</span> <span m='1537900'>expect.</span>
  <span m='1538660'>It</span> <span m='1538860'>will</span> <span m='1539020'>be</span>
  <span m='1539340'>0s</span> <span m='1539910'>on</span> <span m='1540070'>the</span>
  <span m='1540180'>diagonal</span> <span m='1546440'>and</span> <span m='1546840'>off</span>
  <span m='1547065'>the</span> <span m='1547290'>diagonal,</span> <span m='1547830'>what</span>
  <span m='1547990'>do</span> <span m='1548070'>I</span> <span m='1548210'>have?</span>
  <span m='1548490'>Minus --</span> <span m='1549350'>with</span> <span m='1549555'>that</span>
  <span m='1549760'>minus,</span> <span m='1550750'>p</span> <span m='1551080'>is</span>
  <span m='1551320'>2</span> <span m='1551730'>so</span> <span m='1551910'>it's</span>
  <span m='1552050'>1/2.</span> <span m='1553150'>It's</span> <span m='1553300'>1/2</span>
  <span m='1553920'>off</span> <span m='1554250'>the</span> <span m='1554360'>diagonal</span>
  <span m='1560420'>and</span> <span m='1560670'>otherwise,</span> <span m='1561130'>all</span>
  <span m='1561320'>0s.</span> <span m='1562370'>That's</span> <span m='1562720'>the</span>
  <span m='1563520'>nice</span> <span m='1563950'>matrix</span> <span m='1565320'>that</span>
  <span m='1565600'>we</span> <span m='1566790'>get</span> <span m='1568720'>for</span>
  <span m='1568990'>m</span> <span m='1570170'>in</span> <span m='1570400'>one</span>
  <span m='1570600'>dimension.</span> </p><p><span m='1571750'>I</span> <span m='1571870'>have</span>
  <span m='1572040'>to</span> <span m='1572170'>say,</span> <span m='1572420'>of</span>
  <span m='1572540'>course,</span> <span m='1573070'>as</span> <span m='1573310'>you</span>
  <span m='1573440'>know,</span> <span m='1574420'>we</span> <span m='1574610'>wouldn't</span>
  <span m='1574870'>be</span> <span m='1575000'>doing</span> <span m='1575260'>any</span>
  <span m='1575500'>of</span> <span m='1575590'>this</span> <span m='1577210'>for</span>
  <span m='1577400'>this</span> <span m='1577940'>one</span> <span m='1578220'>dimensional</span>
  <span m='1578710'>matrix</span> <span m='1579180'>a.</span> <span m='1579480'>It's</span>
  <span m='1580580'>tridiagonal.</span> <span m='1581880'>We</span> <span m='1582030'>can't</span>
  <span m='1582340'>ask</span> <span m='1582620'>for</span> <span m='1582740'>more</span>
  <span m='1583000'>than</span> <span m='1583160'>that.</span> <span m='1583960'>Direct</span>
  <span m='1584620'>elimination</span> <span m='1585440'>would</span> <span m='1585620'>be</span>
  <span m='1586180'>top</span> <span m='1586460'>speed,</span> <span m='1588090'>but</span>
  <span m='1589010'>the</span> <span m='1589360'>2D</span> <span m='1589930'>case</span>
  <span m='1591810'>is</span> <span m='1592010'>what</span> <span m='1592240'>we</span>
  <span m='1592560'>understand</span> <span m='1593890'>that</span> <span m='1594460'>it</span>
  <span m='1595500'>has</span> <span m='1595720'>a</span> <span m='1595800'>big</span>
  <span m='1596060'>bandwidth</span> <span m='1596670'>because</span> <span m='1597050'>it's</span>
  <span m='1597290'>two</span> <span m='1597500'>dimensional,</span> <span m='1598700'>three</span>
  <span m='1598960'>dimensional</span> <span m='1599450'>even</span> <span m='1599740'>bigger
  --</span> <span m='1601010'>and</span> <span m='1601420'>the</span> <span m='1601520'>eigenvalues</span>
  <span m='1602420'>will</span> <span m='1603600'>come</span> <span m='1603870'>directly</span>
  <span m='1604310'>from</span> <span m='1604490'>the</span> <span m='1604600'>eigenvalues</span>
  <span m='1605320'>of</span> <span m='1605440'>this</span> <span m='1605730'>1D</span>
  <span m='1606330'>case.</span> <span m='1606700'>So</span> <span m='1607470'>if</span>
  <span m='1607750'>we</span> <span m='1607890'>understand</span> <span m='1608420'>the</span>
  <span m='1608500'>1D</span> <span m='1608910'>case,</span> <span m='1609290'>we'll</span>
  <span m='1609590'>knock</span> <span m='1609890'>out</span> <span m='1610130'>the</span>
  <span m='1610270'>two</span> <span m='1610560'>and</span> <span m='1610720'>three</span>
  <span m='1610960'>dimensional</span> <span m='1612290'>easily.</span> <span m='1613090'>So</span>
  <span m='1613290'>I'll</span> <span m='1613460'>stay</span> <span m='1613710'>with</span>
  <span m='1613940'>this</span> <span m='1614080'>one</span> <span m='1614320'>dimensional</span>
  <span m='1615320'>case,</span> <span m='1616560'>where</span> <span m='1617020'>the</span>
  <span m='1617170'>matrix</span> <span m='1617950'>m --</span> <span m='1619830'>and</span>
  <span m='1620010'>I'll</span> <span m='1620170'>even</span> <span m='1620470'>maybe</span>
  <span m='1620860'>shouldn't</span> <span m='1621130'>write</span> <span m='1621510'>down</span>
  <span m='1622300'>exactly</span> <span m='1622940'>what</span> <span m='1623140'>the</span>
  <span m='1623260'>iteration</span> <span m='1623910'>does --</span> <span m='1626360'>but</span>
  <span m='1626560'>if</span> <span m='1626700'>I'm</span> <span m='1626900'>looking</span>
  <span m='1627310'>now</span> <span m='1627620'>at</span> <span m='1627750'>convergence,</span>
  <span m='1628720'>do</span> <span m='1628890'>I</span> <span m='1629060'>have</span>
  <span m='1629580'>or</span> <span m='1629750'>don't</span> <span m='1630050'>I</span>
  <span m='1630190'>have</span> <span m='1630590'>convergence</span> <span m='1631320'>and</span>
  <span m='1631520'>how</span> <span m='1631740'>fast?</span> <span m='1633980'>What</span>
  <span m='1634170'>are</span> <span m='1634270'>the</span> <span m='1634410'>eigenvalues</span>
  <span m='1635290'>and</span> <span m='1635520'>what's</span> <span m='1635840'>the</span>
  <span m='1635980'>biggest</span> <span m='1636360'>one?</span> <span m='1638030'>The</span>
  <span m='1638270'>eigenvalues</span> <span m='1638770'>of</span> <span m='1638950'>a</span>
  <span m='1639510'>are</span> <span m='1640520'>this</span> <span m='1640980'>and</span>
  <span m='1641350'>p</span> <span m='1642730'>is</span> <span m='1642960'>just --</span>
  <span m='1644230'>p</span> <span m='1644430'>inverse</span> <span m='1644600'>is</span>
  <span m='1645010'>just</span> <span m='1645220'>1/2</span> <span m='1648990'>times</span>
  <span m='1649120'>the</span> <span m='1649330'>identity.</span> <span m='1652910'>So</span>
  <span m='1653900'>what</span> <span m='1654080'>are</span> <span m='1654170'>the</span>
  <span m='1654280'>eigenvalues?</span> <span m='1655360'>Again,</span> <span m='1657190'>I</span>
  <span m='1657260'>mean,</span> <span m='1657490'>I</span> <span m='1657580'>know</span>
  <span m='1657770'>the</span> <span m='1657910'>eigenvalues</span> <span m='1658630'>of</span>
  <span m='1658810'>a,</span> <span m='1660220'>so</span> <span m='1660370'>I</span>
  <span m='1660440'>divide</span> <span m='1660850'>by</span> <span m='1661040'>2.</span>
  <span m='1662920'>Let</span> <span m='1663080'>me</span> <span m='1663180'>write</span>
  <span m='1663490'>down</span> <span m='1663690'>what</span> <span m='1663840'>I'm</span>
  <span m='1663960'>going to</span> <span m='1664170'>get</span> <span m='1664430'>now</span>
  <span m='1664880'>for</span> <span m='1665020'>the</span> <span m='1665160'>eigenvalues</span>
  <span m='1666300'>of</span> <span m='1666700'>m,</span> <span m='1671590'>remembering</span>
  <span m='1672260'>this</span> <span m='1672710'>connection.</span> <span m='1673230'>So</span>
  <span m='1673430'>the</span> <span m='1673530'>eigenvalues</span> <span m='1674250'>of</span>
  <span m='1674380'>m</span> <span m='1675080'>are</span> <span m='1675370'>1</span>
  <span m='1675890'>minus</span> <span m='1676370'>1/2</span> <span m='1677070'>times</span>
  <span m='1677340'>the</span> <span m='1677610'>eigenvalues</span> <span m='1678230'>of</span>
  <span m='1678290'>a.</span> <span m='1678870'>Better</span> <span m='1679040'>write</span>
  <span m='1679270'>that</span> <span m='1679420'>down.</span> <span m='1680080'>1</span>
  <span m='1680640'>minus</span> <span m='1681090'>1/2</span> <span m='1681820'>times</span>
  <span m='1682280'>the</span> <span m='1682490'>eigenvalues</span> <span m='1682870'>of</span>
  <span m='1683440'>a.</span> <span m='1683730'>Of</span> <span m='1688580'>course,</span>
  <span m='1688730'>it's</span> <span m='1688880'>very</span> <span m='1689270'>special</span>
  <span m='1689750'>that</span> <span m='1689875'>we</span> <span m='1690000'>have</span>
  <span m='1692470'>this</span> <span m='1693110'>terrific</span> <span m='1693980'>example</span>
  <span m='1694690'>matrix</span> <span m='1695300'>where</span> <span m='1695500'>we</span>
  <span m='1695710'>know</span> <span m='1695950'>the</span> <span m='1696140'>eigenvalues</span>
  <span m='1696870'>and</span> <span m='1697050'>really</span> <span m='1697360'>can</span>
  <span m='1697620'>see</span> <span m='1698040'>what's</span> <span m='1698330'>happening</span>
  <span m='1699160'>and</span> <span m='1699370'>we</span> <span m='1699500'>know</span>
  <span m='1699670'>the</span> <span m='1699820'>matrix.</span> </p><p><span m='1701670'>So</span>
  <span m='1701860'>what</span> <span m='1702090'>happens?</span> <span m='1702520'>I</span>
  <span m='1702640'>take</span> <span m='1702960'>half</span> <span m='1703410'>of</span>
  <span m='1703490'>that --</span> <span m='1704850'>that</span> <span m='1705020'>makes</span>
  <span m='1705280'>it</span> <span m='1705450'>a</span> <span m='1705520'>1.</span>
  <span m='1707140'>When</span> <span m='1707330'>I</span> <span m='1707410'>subtract</span>
  <span m='1708050'>it</span> <span m='1708180'>from</span> <span m='1708370'>that</span>
  <span m='1708600'>one,</span> <span m='1709050'>it's</span> <span m='1709250'>gone.</span>
  <span m='1712090'>1/2</span> <span m='1712700'>of</span> <span m='1712780'>that,</span>
  <span m='1713260'>that</span> <span m='1713490'>2</span> <span m='1713720'>is</span>
  <span m='1713920'>cancelled --</span> <span m='1714330'>I</span> <span m='1714470'>just</span>
  <span m='1714740'>get</span> <span m='1714940'>cos</span> <span m='1715400'>theta.</span>
  <span m='1716980'>Theta</span> <span m='1719030'>sub</span> <span m='1719910'>whatever</span>
  <span m='1720380'>that</span> <span m='1720560'>angle</span> <span m='1720820'>was.</span>
  <span m='1723910'>It's</span> <span m='1724110'>a</span> <span m='1724180'>cosine</span>
  <span m='1727280'>and</span> <span m='1727500'>it's</span> <span m='1727640'>less</span>
  <span m='1727900'>than</span> <span m='1728080'>1.</span> <span m='1731190'>So</span>
  <span m='1731490'>convergence</span> <span m='1732110'>is</span> <span m='1732270'>going
  to</span> <span m='1732490'>happen</span> <span m='1733830'>and</span> <span m='1734090'>convergence</span>
  <span m='1734750'>is</span> <span m='1734880'>going</span> <span m='1735060'>to</span>
  <span m='1735120'>be</span> <span m='1735290'>slow</span> <span m='1735545'>or</span>
  <span m='1735800'>fast</span> <span m='1736380'>according</span> <span m='1736990'>as</span>
  <span m='1738040'>this</span> <span m='1738350'>is</span> <span m='1738950'>very</span>
  <span m='1739460'>near</span> <span m='1739740'>1</span> <span m='1741080'>or</span>
  <span m='1741330'>not --</span> <span m='1741950'>and</span> <span m='1742310'>unfortunately,</span>
  <span m='1743020'>it</span> <span m='1743130'>is</span> <span m='1743310'>pretty</span>
  <span m='1743580'>near</span> <span m='1743810'>1,</span> <span m='1744620'>because</span>
  <span m='1745140'>the</span> <span m='1745300'>first,</span> <span m='1746120'>the</span>
  <span m='1746400'>largest</span> <span m='1747020'>one --</span> <span m='1748760'>I</span>
  <span m='1748930'>could</span> <span m='1749150'>tell</span> <span m='1749370'>you</span>
  <span m='1749480'>what</span> <span m='1749710'>the</span> <span m='1749830'>angles</span>
  <span m='1750300'>are.</span> <span m='1751040'>That's --</span> <span m='1751810'>to</span>
  <span m='1751940'>complete</span> <span m='1752400'>this</span> <span m='1752620'>information,</span>
  <span m='1753340'>I</span> <span m='1753440'>should</span> <span m='1753670'>have</span>
  <span m='1754200'>put</span> <span m='1754390'>in</span> <span m='1754560'>what
  --</span> <span m='1755320'>and</span> <span m='1756450'>von</span> <span m='1756610'>Neumann</span>
  <span m='1757090'>got</span> <span m='1757310'>them</span> <span m='1757410'>right.</span>
  <span m='1758610'>That's</span> <span m='1758910'>j --</span> <span m='1763140'>is</span>
  <span m='1763330'>there</span> <span m='1763710'>maybe</span> <span m='1764010'>a</span>
  <span m='1764220'>pi</span> <span m='1765780'>over</span> <span m='1766560'>n</span>
  <span m='1766790'>plus</span> <span m='1767060'>1?</span> <span m='1767610'>I</span>
  <span m='1767790'>think</span> <span m='1768040'>so.</span> <span m='1771200'>Those</span>
  <span m='1771450'>are</span> <span m='1771540'>the</span> <span m='1771680'>angles</span>
  <span m='1772230'>that</span> <span m='1772420'>come</span> <span m='1772630'>in,</span>
  <span m='1773160'>just</span> <span m='1773520'>the</span> <span m='1773670'>equally</span>
  <span m='1774260'>spaced</span> <span m='1774730'>angles</span> <span m='1775850'>in</span>
  <span m='1776100'>the</span> <span m='1776410'>finite</span> <span m='1777180'>case.</span>
  <span m='1777580'>So</span> <span m='1777790'>we</span> <span m='1777970'>have</span>
  <span m='1778630'>n</span> <span m='1779340'>eigenvalue.</span> <span m='1781210'>The</span>
  <span m='1781350'>biggest</span> <span m='1781820'>one</span> <span m='1782100'>is</span>
  <span m='1782260'>going to</span> <span m='1782530'>be</span> <span m='1783500'>when</span>
  <span m='1783680'>j</span> <span m='1783920'>is</span> <span m='1784080'>1.</span>
  <span m='1784900'>So</span> <span m='1785030'>the</span> <span m='1785150'>biggest</span>
  <span m='1785540'>one,</span> <span m='1785730'>rho,</span> <span m='1786320'>the</span>
  <span m='1787060'>maximum</span> <span m='1788000'>of</span> <span m='1788940'>these</span>
  <span m='1789280'>guys,</span> <span m='1790780'>of</span> <span m='1790985'>these</span>
  <span m='1791190'>lambdas</span> <span m='1791850'>will</span> <span m='1792090'>be</span>
  <span m='1793000'>the</span> <span m='1793500'>cosine</span> <span m='1794030'>of</span>
  <span m='1794640'>when</span> <span m='1794830'>j</span> <span m='1795080'>is</span>
  <span m='1795240'>1</span> <span m='1796040'>pi</span> <span m='1796420'>over</span>
  <span m='1796780'>n</span> <span m='1797035'>plus</span> <span m='1797290'>1.</span>
  <span m='1800180'>That's</span> <span m='1800450'>the</span> <span m='1800570'>one</span>
  <span m='1800780'>that's</span> <span m='1800950'>slowing</span> <span m='1801400'>us</span>
  <span m='1801560'>down.</span> <span m='1806800'>Notice</span> <span m='1807360'>the</span>
  <span m='1807490'>eigenvector</span> <span m='1808230'>that's</span> <span m='1808400'>slowing</span>
  <span m='1808940'>us</span> <span m='1809423'>down,</span> <span m='1810390'>because</span>
  <span m='1811140'>it's</span> <span m='1811450'>the</span> <span m='1812720'>eigenvector</span>
  <span m='1813420'>that</span> <span m='1813590'>goes</span> <span m='1813890'>with</span>
  <span m='1814040'>that</span> <span m='1814260'>eigenvalue</span> <span m='1815080'>that's</span>
  <span m='1815730'>the</span> <span m='1815920'>biggest</span> <span m='1816390'>eigenvalue</span>
  <span m='1817070'>that's</span> <span m='1817270'>going to</span> <span m='1817510'>hang</span>
  <span m='1817740'>around</span> <span m='1818090'>the</span> <span m='1818160'>longest,</span>
  <span m='1819430'>decay</span> <span m='1819620'>the</span> <span m='1820200'>slowest.</span>
  <span m='1821920'>That</span> <span m='1822310'>eigenvector</span> <span m='1823510'>is</span>
  <span m='1825110'>very</span> <span m='1825410'>smooth.</span> <span m='1825980'>It's</span>
  <span m='1826330'>the</span> <span m='1826560'>low</span> <span m='1826750'>frequency.</span>
  <span m='1827850'>It's</span> <span m='1828070'>frequency</span> <span m='1828700'>1.</span>
  <span m='1829660'>So</span> <span m='1829770'>this</span> <span m='1829950'>is</span>
  <span m='1830130'>j</span> <span m='1830500'>equal</span> <span m='1830820'>to</span>
  <span m='1830950'>1.</span> <span m='1832180'>This</span> <span m='1832400'>is</span>
  <span m='1832590'>the</span> <span m='1832710'>low</span> <span m='1833050'>frequency,</span>
  <span m='1834260'>j</span> <span m='1834446'>equal</span> <span m='1834633'>1,</span>
  <span m='1834820'>low</span> <span m='1835170'>frequency.</span> <span m='1839030'>The</span>
  <span m='1839510'>eigenvector</span> <span m='1842170'>is</span> <span m='1842420'>just</span>
  <span m='1845210'>samples</span> <span m='1847100'>of</span> <span m='1847530'>the</span>
  <span m='1847960'>sine,</span> <span m='1849070'>of</span> <span m='1849220'>a</span>
  <span m='1849290'>discrete</span> <span m='1849740'>sine.</span> <span m='1851020'>One</span>
  <span m='1852500'>lowest</span> <span m='1852920'>frequency</span> <span m='1853750'>that</span>
  <span m='1853980'>the</span> <span m='1854390'>grid</span> <span m='1854690'>can</span>
  <span m='1857010'>sustain.</span> </p><p><span m='1860600'>Why</span> <span m='1860920'>do</span>
  <span m='1861060'>I</span> <span m='1861230'>emphasize</span> <span m='1861840'>which</span>
  <span m='1862130'>eigenvector</span> <span m='1862840'>it</span> <span m='1862960'>is?</span>
  <span m='1864250'>Because</span> <span m='1865010'>when</span> <span m='1865200'>you</span>
  <span m='1865370'>know</span> <span m='1866410'>which</span> <span m='1866770'>eigenvector</span>
  <span m='1867470'>is</span> <span m='1867600'>slowing</span> <span m='1868020'>you</span>
  <span m='1868190'>down --</span> <span m='1869650'>and</span> <span m='1869920'>here</span>
  <span m='1870230'>it's</span> <span m='1870740'>the</span> <span m='1871000'>eigenvector</span>
  <span m='1871480'>you</span> <span m='1871660'>would</span> <span m='1871830'>think</span>
  <span m='1872060'>would</span> <span m='1872200'>be</span> <span m='1872330'>the</span>
  <span m='1872480'>simplest</span> <span m='1873010'>one</span> <span m='1873210'>to</span>
  <span m='1873310'>handle --</span> <span m='1874640'>this</span> <span m='1874820'>is</span>
  <span m='1874980'>the</span> <span m='1875140'>easiest</span> <span m='1875770'>eigenvector,</span>
  <span m='1876490'>higher</span> <span m='1876900'>frequency</span> <span m='1877490'>eigenvector,</span>
  <span m='1880070'>have</span> <span m='1880800'>eigenvalues</span> <span m='1881830'>that</span>
  <span m='1882050'>start</span> <span m='1882440'>dropping.</span> <span m='1884110'>Cosine</span>
  <span m='1884520'>of</span> <span m='1884690'>2</span> <span m='1884950'>pi.</span>
  <span m='1886500'>Cosine</span> <span m='1886970'>3</span> <span m='1887285'>pi</span>
  <span m='1887600'>over</span> <span m='1887770'>n</span> <span m='1887950'>plus</span>
  <span m='1888240'>1</span> <span m='1888670'>is</span> <span m='1888920'>going to</span>
  <span m='1889260'>be</span> <span m='1889810'>further</span> <span m='1890310'>away</span>
  <span m='1890580'>from</span> <span m='1890850'>1.</span> <span m='1891420'>Now</span>
  <span m='1891590'>I</span> <span m='1891670'>have</span> <span m='1891900'>to</span>
  <span m='1892030'>admit</span> <span m='1895090'>that</span> <span m='1895330'>the</span>
  <span m='1895390'>very</span> <span m='1895820'>highest</span> <span m='1896270'>frequency,</span>
  <span m='1898630'>when</span> <span m='1898910'>j</span> <span m='1899540'>is</span>
  <span m='1899910'>capital</span> <span m='1900440'>n,</span> <span m='1903250'>so</span>
  <span m='1904540'>when</span> <span m='1904750'>j</span> <span m='1904965'>is</span>
  <span m='1905180'>capital</span> <span m='1905690'>n,</span> <span m='1907610'>I</span>
  <span m='1907790'>have</span> <span m='1908020'>to</span> <span m='1908160'>admit</span>
  <span m='1908510'>it</span> <span m='1908600'>happens</span> <span m='1909070'>to</span>
  <span m='1909210'>come</span> <span m='1909420'>back</span> <span m='1910340'>with</span>
  <span m='1910580'>a</span> <span m='1910680'>minus</span> <span m='1911090'>sign,</span>
  <span m='1911450'>but</span> <span m='1911800'>the</span> <span m='1911950'>magnitude</span>
  <span m='1912550'>is</span> <span m='1912690'>still</span> <span m='1912970'>just</span>
  <span m='1913340'>as</span> <span m='1913500'>bad.</span> <span m='1914820'>The</span>
  <span m='1914960'>cosine</span> <span m='1915770'>of</span> <span m='1916700'>n</span>
  <span m='1916965'>pi</span> <span m='1917230'>over</span> <span m='1917530'>n</span>
  <span m='1917770'>plus</span> <span m='1918030'>1</span> <span m='1920850'>is</span>
  <span m='1921170'>just</span> <span m='1922060'>the</span> <span m='1922220'>negative</span>
  <span m='1922700'>of</span> <span m='1922810'>that</span> <span m='1923040'>one.</span>
  <span m='1924820'>So</span> <span m='1925000'>actually</span> <span m='1925410'>we</span>
  <span m='1925560'>have</span> <span m='1925830'>two</span> <span m='1926650'>eigenvalues</span>
  <span m='1927650'>that</span> <span m='1927800'>are</span> <span m='1927870'>both</span>
  <span m='1928280'>hitting</span> <span m='1929490'>the</span> <span m='1929990'>spectral</span>
  <span m='1930410'>radius</span> <span m='1933070'>and</span> <span m='1934220'>both</span>
  <span m='1934500'>of</span> <span m='1934600'>them</span> <span m='1937470'>are</span>
  <span m='1937630'>the</span> <span m='1937950'>worst,</span> <span m='1938710'>the</span>
  <span m='1938850'>slowest</span> <span m='1939560'>converging</span> <span m='1940350'>eigenvectors.</span>
  <span m='1942610'>This</span> <span m='1942870'>eigenvector</span> <span m='1943900'>looks</span>
  <span m='1945720'>very</span> <span m='1946010'>smooth.</span> <span m='1947360'>The</span>
  <span m='1947430'>eigenvector</span> <span m='1948200'>for</span> <span m='1948380'>that</span>
  <span m='1948630'>high</span> <span m='1948880'>frequency</span> <span m='1949550'>one</span>
  <span m='1949880'>is</span> <span m='1950090'>the</span> <span m='1950230'>fastest</span>
  <span m='1950900'>oscillating.</span> <span m='1952760'>If</span> <span m='1953100'>I</span>
  <span m='1953200'>graph</span> <span m='1953660'>the</span> <span m='1953760'>eigenvectors,</span>
  <span m='1955280'>eigenvalues,</span> <span m='1956710'>I</span> <span m='1956850'>will.</span>
  <span m='1957520'>I'll</span> <span m='1957740'>graph</span> <span m='1958080'>the</span>
  <span m='1958260'>eigenvalues.</span> <span m='1959950'>You'll</span> <span m='1960130'>see</span>
  <span m='1960420'>that</span> <span m='1960710'>it's</span> <span m='1960960'>the</span>
  <span m='1961110'>first</span> <span m='1961590'>and</span> <span m='1961720'>the</span>
  <span m='1961820'>last</span> <span m='1962350'>that</span> <span m='1962500'>are</span>
  <span m='1964040'>nearest</span> <span m='1964670'>in</span> <span m='1964800'>magnitude</span>
  <span m='1965410'>to</span> <span m='1965500'>1.</span> </p><p><span m='1969010'>I</span>
  <span m='1969160'>was</span> <span m='1969310'>just</span> <span m='1969510'>going</span>
  <span m='1969630'>to</span> <span m='1969710'>say,</span> <span m='1970950'>can</span>
  <span m='1971180'>I</span> <span m='1971330'>anticipate</span> <span m='1972020'>multigrid</span>
  <span m='1972620'>for</span> <span m='1972730'>a</span> <span m='1972790'>minute?</span>
  <span m='1975850'>So</span> <span m='1975980'>multigrid</span> <span m='1976620'>does
  --</span> <span m='1977670'>is</span> <span m='1977830'>going to</span> <span m='1978070'>try</span>
  <span m='1978400'>to</span> <span m='1979470'>get</span> <span m='1979660'>these</span>
  <span m='1979960'>guys</span> <span m='1981300'>to</span> <span m='1981480'>go</span>
  <span m='1981680'>faster.</span> <span m='1983460'>Now</span> <span m='1983700'>this</span>
  <span m='1984020'>one</span> <span m='1984760'>can</span> <span m='1985190'>be</span>
  <span m='1985390'>handled,</span> <span m='1985970'>you'll</span> <span m='1986190'>see,</span>
  <span m='1986510'>by</span> <span m='1986710'>just</span> <span m='1987130'>a</span>
  <span m='1987220'>simple</span> <span m='1987740'>adjustment</span> <span m='1988350'>of</span>
  <span m='1988670'>Jacobi.</span> <span m='1989650'>I</span> <span m='1989730'>just</span>
  <span m='1990040'>wait</span> <span m='1990530'>Jacobi</span> <span m='1990900'>a</span>
  <span m='1991980'>little</span> <span m='1992220'>bit.</span> <span m='1993500'>Instead</span>
  <span m='1993900'>of</span> <span m='1994020'>2</span> <span m='1994300'>i,</span>
  <span m='1994570'>I</span> <span m='1994790'>take</span> <span m='1995870'>3</span>
  <span m='1996230'>i</span> <span m='1996600'>or</span> <span m='1997130'>4</span>
  <span m='1997460'>i.</span> <span m='1999350'>3</span> <span m='1999560'>i</span>
  <span m='1999760'>would</span> <span m='2000000'>be</span> <span m='2000140'>very</span>
  <span m='2000490'>good</span> <span m='2001950'>for</span> <span m='2002280'>the</span>
  <span m='2002780'>preconditioner.</span> <span m='2004330'>That</span> <span m='2004570'>will</span>
  <span m='2004730'>have</span> <span m='2005020'>the</span> <span m='2005130'>effect</span>
  <span m='2006040'>on</span> <span m='2006380'>this</span> <span m='2007120'>high</span>
  <span m='2007340'>frequency</span> <span m='2008040'>one</span> <span m='2008440'>that'll</span>
  <span m='2008990'>be</span> <span m='2009550'>well</span> <span m='2009980'>down</span>
  <span m='2010300'>now,</span> <span m='2010600'>below</span> <span m='2010870'>1.</span>
  <span m='2012290'>This</span> <span m='2012560'>will</span> <span m='2012750'>still</span>
  <span m='2013120'>be</span> <span m='2013790'>the</span> <span m='2015320'>slowpoke</span>
  <span m='2016100'>in</span> <span m='2016350'>converging.</span> <span m='2017980'>That's</span>
  <span m='2018340'>where</span> <span m='2018680'>multigrid</span> <span m='2019530'>says,</span>
  <span m='2022660'>that's</span> <span m='2023170'>low</span> <span m='2023500'>frequency.</span>
  <span m='2024460'>That's</span> <span m='2024840'>too</span> <span m='2025120'>low.</span>
  <span m='2025740'>That's</span> <span m='2026520'>not</span> <span m='2026920'>converging</span>
  <span m='2027510'>quickly.</span> <span m='2028530'>Take</span> <span m='2028840'>a</span>
  <span m='2028960'>different</span> <span m='2029410'>grid</span> <span m='2029820'>on</span>
  <span m='2030020'>which</span> <span m='2030980'>that</span> <span m='2031270'>same</span>
  <span m='2031860'>thing</span> <span m='2032380'>looks</span> <span m='2032730'>higher</span>
  <span m='2033070'>frequency.</span> <span m='2034300'>We'll</span> <span m='2034460'>see</span>
  <span m='2035370'>that</span> <span m='2035600'>tomorrow.</span> </p><p><span m='2038360'>So</span>
  <span m='2038780'>if</span> <span m='2038980'>I</span> <span m='2039100'>stay</span>
  <span m='2039540'>with</span> <span m='2039970'>Jacobi,</span> <span m='2040440'>what</span>
  <span m='2040680'>have</span> <span m='2040740'>I</span> <span m='2040800'>learned?</span>
  <span m='2042060'>I've</span> <span m='2042280'>learned</span> <span m='2042750'>that</span>
  <span m='2042970'>this</span> <span m='2043440'>is</span> <span m='2043930'>rho.</span>
  <span m='2045410'>For</span> <span m='2045600'>this</span> <span m='2045870'>matrix,</span>
  <span m='2046870'>the</span> <span m='2047120'>spectral</span> <span m='2047370'>radius</span>
  <span m='2047870'>is</span> <span m='2048050'>that</span> <span m='2048290'>number</span>
  <span m='2049110'>and</span> <span m='2049330'>let's</span> <span m='2049540'>just</span>
  <span m='2049760'>see</span> <span m='2049980'>how</span> <span m='2050160'>big</span>
  <span m='2050460'>it</span> <span m='2050560'>is.</span> <span m='2051550'>How</span>
  <span m='2051900'>big</span> <span m='2052160'>is --</span> <span m='2052820'>that's</span>
  <span m='2053070'>a</span> <span m='2053160'>cosine</span> <span m='2053680'>of</span>
  <span m='2053770'>a</span> <span m='2053860'>small</span> <span m='2054440'>number.</span>
  <span m='2055380'>So</span> <span m='2055510'>the</span> <span m='2055630'>cosine</span>
  <span m='2056120'>of</span> <span m='2056200'>a</span> <span m='2056310'>small</span>
  <span m='2056690'>number,</span> <span m='2057960'>theta</span> <span m='2058790'>near
  --</span> <span m='2059250'>theta</span> <span m='2059700'>near</span> <span m='2059870'>0,</span>
  <span m='2060320'>the</span> <span m='2060470'>cosine</span> <span m='2060970'>of</span>
  <span m='2061100'>theta</span> <span m='2062030'>is</span> <span m='2062410'>1</span>
  <span m='2063970'>minus --</span> <span m='2064720'>so</span> <span m='2064880'>it's</span>
  <span m='2065010'>below</span> <span m='2065360'>1,</span> <span m='2065600'>of</span>
  <span m='2065730'>course --</span> <span m='2066100'>1/2</span> <span m='2066720'>theta</span>
  <span m='2067000'>squared.</span> <span m='2067960'>Theta</span> <span m='2068210'>is</span>
  <span m='2068690'>pi</span> <span m='2069670'>over</span> <span m='2070170'>n</span>
  <span m='2070500'>plus</span> <span m='2070840'>1</span> <span m='2071770'>squared.</span>
  <span m='2073370'>All</span> <span m='2073630'>these</span> <span m='2074180'>simple</span>
  <span m='2074940'>estimates</span> <span m='2076160'>really</span> <span m='2076730'>tell</span>
  <span m='2077010'>you</span> <span m='2078110'>what</span> <span m='2078500'>happens</span>
  <span m='2080390'>when</span> <span m='2080650'>you</span> <span m='2081250'>do</span>
  <span m='2081380'>Jacobi</span> <span m='2082010'>iteration.</span> <span m='2084230'>You'll</span>
  <span m='2084490'>see</span> <span m='2084720'>it</span> <span m='2086150'>on</span>
  <span m='2086500'>the</span> <span m='2088900'>output</span> <span m='2089420'>from
  --</span> <span m='2090800'>I</span> <span m='2090880'>mean,</span> <span m='2091720'>you</span>
  <span m='2091970'>can --</span> <span m='2092450'>I</span> <span m='2092620'>hope</span>
  <span m='2092790'>will --</span> <span m='2093810'>code</span> <span m='2094160'>up</span>
  <span m='2097670'>Jacobi's</span> <span m='2098100'>method,</span> <span m='2099690'>taking</span>
  <span m='2100200'>p</span> <span m='2100630'>to</span> <span m='2100760'>be</span>
  <span m='2101550'>a</span> <span m='2102310'>multiple</span> <span m='2102800'>of</span>
  <span m='2102880'>the</span> <span m='2102960'>identity,</span> <span m='2104530'>so</span>
  <span m='2104810'>very</span> <span m='2105150'>fast</span> <span m='2106710'>and</span>
  <span m='2107200'>you'll</span> <span m='2107460'>see</span> <span m='2107770'>the</span>
  <span m='2108210'>convergence</span> <span m='2108860'>rate</span> <span m='2109210'>you</span>
  <span m='2109350'>can</span> <span m='2109510'>graph.</span> </p><p><span m='2111090'>Here's</span>
  <span m='2111450'>an</span> <span m='2111610'>interesting</span> <span m='2112120'>point</span>
  <span m='2112290'>and</span> <span m='2112460'>I'll</span> <span m='2112600'>make</span>
  <span m='2112880'>it</span> <span m='2112990'>again.</span> <span m='2113900'>What</span>
  <span m='2114050'>should</span> <span m='2114200'>you</span> <span m='2114500'>graph</span>
  <span m='2116510'>in</span> <span m='2118480'>seeing --</span> <span m='2119970'>to</span>
  <span m='2120130'>display</span> <span m='2120770'>convergence</span> <span m='2121540'>and</span>
  <span m='2121770'>rate</span> <span m='2122040'>of</span> <span m='2122170'>convergence?</span>
  <span m='2124640'>Let</span> <span m='2124770'>me</span> <span m='2124890'>draw</span>
  <span m='2125100'>a</span> <span m='2125310'>possible</span> <span m='2125810'>graph</span>
  <span m='2126200'>here.</span> <span m='2128400'>Let</span> <span m='2128570'>me</span>
  <span m='2128700'>draw</span> <span m='2128920'>two</span> <span m='2129420'>possible</span>
  <span m='2129930'>graphs.</span> <span m='2130950'>I</span> <span m='2131100'>could</span>
  <span m='2131370'>graph --</span> <span m='2134360'>this</span> <span m='2134600'>is</span>
  <span m='2135920'>k</span> <span m='2136630'>as</span> <span m='2136800'>I</span>
  <span m='2136890'>take</span> <span m='2137190'>more</span> <span m='2137400'>steps.</span>
  <span m='2138660'>I</span> <span m='2138800'>could</span> <span m='2139050'>graph</span>
  <span m='2139530'>the</span> <span m='2139630'>error,</span> <span m='2141790'>the</span>
  <span m='2141970'>size</span> <span m='2142440'>of</span> <span m='2142530'>the</span>
  <span m='2142710'>error.</span> <span m='2142890'>It's</span> <span m='2143090'>a</span>
  <span m='2143160'>vector,</span> <span m='2144770'>so</span> <span m='2144980'>I</span>
  <span m='2145240'>take</span> <span m='2145590'>its</span> <span m='2145760'>length.</span>
  <span m='2147980'>I</span> <span m='2148100'>don't</span> <span m='2148290'>know</span>
  <span m='2148360'>where</span> <span m='2148590'>I</span> <span m='2148690'>start
  --</span> <span m='2149270'>at</span> <span m='2149450'>e-not.</span> <span m='2150340'>This</span>
  <span m='2150540'>is</span> <span m='2150720'>k</span> <span m='2150833'>equals</span>
  <span m='2150946'>0.</span> <span m='2151320'>This</span> <span m='2151500'>is</span>
  <span m='2151610'>the</span> <span m='2151800'>initial</span> <span m='2151930'>guess.</span>
  <span m='2155380'>If</span> <span m='2155670'>I</span> <span m='2155870'>use --</span>
  <span m='2159310'>I'm</span> <span m='2159430'>going to</span> <span m='2159680'>draw</span>
  <span m='2160010'>a</span> <span m='2160315'>graph,</span> <span m='2160620'>which</span>
  <span m='2161330'>you'll</span> <span m='2161700'>draw</span> <span m='2162000'>much</span>
  <span m='2162230'>better</span> <span m='2162870'>by</span> <span m='2163160'>actually</span>
  <span m='2164030'>getting</span> <span m='2164500'>MATLAB</span> <span m='2165020'>to</span>
  <span m='2165150'>do</span> <span m='2165360'>it.</span> <span m='2168690'>Before</span>
  <span m='2169040'>I</span> <span m='2169130'>draw</span> <span m='2169530'>it,</span>
  <span m='2169930'>let</span> <span m='2170160'>me</span> <span m='2170570'>mention</span>
  <span m='2171060'>the</span> <span m='2171170'>other</span> <span m='2171420'>graph</span>
  <span m='2172020'>we</span> <span m='2172225'>could</span> <span m='2172510'>draw.</span>
  <span m='2173680'>This</span> <span m='2174030'>tells</span> <span m='2174400'>us</span>
  <span m='2174610'>the</span> <span m='2174790'>error</span> <span m='2175370'>in
  --</span> <span m='2176630'>this</span> <span m='2176850'>is</span> <span m='2177740'>the</span>
  <span m='2177890'>error</span> <span m='2182350'>in</span> <span m='2182630'>the</span>
  <span m='2182740'>solution.</span> <span m='2185270'>If</span> <span m='2185410'>I</span>
  <span m='2185510'>think</span> <span m='2185730'>that's</span> <span m='2185990'>the</span>
  <span m='2186070'>natural</span> <span m='2186490'>thing</span> <span m='2186660'>to</span>
  <span m='2186760'>draw,</span> <span m='2187090'>it</span> <span m='2187190'>is,</span>
  <span m='2188310'>but</span> <span m='2188630'>we</span> <span m='2188820'>could</span>
  <span m='2189000'>also</span> <span m='2189420'>draw</span> <span m='2190930'>the</span>
  <span m='2191170'>error</span> <span m='2192360'>in</span> <span m='2192560'>the</span>
  <span m='2192660'>equation,</span> <span m='2194610'>the</span> <span m='2194790'>residual</span>
  <span m='2195500'>error.</span> <span m='2196410'>So</span> <span m='2196570'>I'll</span>
  <span m='2196640'>just</span> <span m='2196910'>put</span> <span m='2197070'>up</span>
  <span m='2197220'>here</span> <span m='2198010'>what</span> <span m='2198200'>I</span>
  <span m='2198280'>mean</span> <span m='2198580'>by</span> <span m='2198770'>that.</span>
  <span m='2199730'>If</span> <span m='2199960'>I</span> <span m='2200160'>put</span>
  <span m='2200500'>it</span> <span m='2200610'>in --</span> <span m='2202390'>so</span>
  <span m='2204450'>ax</span> <span m='2204960'>equals</span> <span m='2205500'>b</span>
  <span m='2205760'>exactly.</span> <span m='2208220'>axk</span> <span m='2210950'>is</span>
  <span m='2212230'>close.</span> <span m='2216990'>The</span> <span m='2217170'>residual</span>
  <span m='2218310'>is --</span> <span m='2218990'>let</span> <span m='2219170'>me</span>
  <span m='2219310'>call</span> <span m='2219530'>it</span> <span m='2219650'>r,</span>
  <span m='2220100'>as</span> <span m='2220230'>everybody</span> <span m='2220690'>does
  --</span> <span m='2221070'>is</span> <span m='2221300'>the</span> <span m='2221410'>difference</span>
  <span m='2224590'>ax</span> <span m='2225090'>minus</span> <span m='2225500'>axk.</span>
  <span m='2230470'>It's</span> <span m='2232450'>how</span> <span m='2232620'>close</span>
  <span m='2232950'>we</span> <span m='2233110'>are</span> <span m='2233820'>to</span>
  <span m='2233940'>b,</span> <span m='2237090'>so</span> <span m='2237250'>it's</span>
  <span m='2237390'>b</span> <span m='2237770'>minus</span> <span m='2238230'>axk.</span>
  <span m='2238850'>The</span> <span m='2239000'>true</span> <span m='2239260'>ax</span>
  <span m='2239800'>gets</span> <span m='2240010'>b</span> <span m='2240350'>exactly</span>
  <span m='2240900'>right.</span> <span m='2241610'>The</span> <span m='2241750'>wrong</span>
  <span m='2242260'>ax</span> <span m='2242780'>gets</span> <span m='2243030'>b</span>
  <span m='2243370'>nearly</span> <span m='2243600'>right.</span> <span m='2248030'>So</span>
  <span m='2248300'>you</span> <span m='2248490'>see,</span> <span m='2249600'>because</span>
  <span m='2249920'>we</span> <span m='2250060'>have</span> <span m='2250320'>this</span>
  <span m='2250520'>linear</span> <span m='2250920'>problem,</span> <span m='2252090'>it's</span>
  <span m='2252320'>a</span> <span m='2252760'>times</span> <span m='2253140'>the</span>
  <span m='2253230'>error.</span> <span m='2253560'>x</span> <span m='2257060'>minus</span>
  <span m='2257400'>xk</span> <span m='2257960'>is</span> <span m='2258410'>ek.</span>
  <span m='2258860'>So</span> <span m='2259100'>this</span> <span m='2259380'>is</span>
  <span m='2259580'>the</span> <span m='2259690'>residual</span> <span m='2268100'>and</span>
  <span m='2268510'>I</span> <span m='2268630'>could</span> <span m='2268880'>grapj</span>
  <span m='2269180'>that.</span> <span m='2269770'>That's</span> <span m='2270660'>how</span>
  <span m='2270930'>close</span> <span m='2272010'>my</span> <span m='2272990'>answer</span>
  <span m='2273490'>comes</span> <span m='2274010'>to</span> <span m='2274140'>getting</span>
  <span m='2274620'>b</span> <span m='2275030'>right,</span> <span m='2275470'>how</span>
  <span m='2275660'>close</span> <span m='2275950'>the</span> <span m='2276050'>equation</span>
  <span m='2276620'>is.</span> <span m='2277360'>Where</span> <span m='2277680'>this</span>
  <span m='2277970'>is</span> <span m='2278180'>how</span> <span m='2278400'>close</span>
  <span m='2278900'>the</span> <span m='2279830'>xk</span> <span m='2280840'>is.</span>
  <span m='2281440'>So</span> <span m='2281640'>that</span> <span m='2281850'>would</span>
  <span m='2281990'>be</span> <span m='2282120'>the</span> <span m='2282240'>other</span>
  <span m='2282510'>thing</span> <span m='2282760'>I</span> <span m='2282840'>could</span>
  <span m='2283100'>graph.</span> <span m='2286570'>rk</span> <span m='2287630'>is</span>
  <span m='2287835'>the</span> <span m='2288040'>size</span> <span m='2288500'>of</span>
  <span m='2288630'>the</span> <span m='2288720'>residual,</span> <span m='2291540'>which</span>
  <span m='2291790'>is</span> <span m='2291990'>aek.</span> </p><p><span m='2299670'>So</span>
  <span m='2299800'>now</span> <span m='2299980'>I</span> <span m='2300010'>have</span>
  <span m='2300160'>to</span> <span m='2300270'>remember</span> <span m='2301850'>what</span>
  <span m='2302040'>I</span> <span m='2302150'>think</span> <span m='2302450'>these</span>
  <span m='2302700'>graphs</span> <span m='2303070'>look</span> <span m='2303310'>like,</span>
  <span m='2303610'>but</span> <span m='2303780'>of</span> <span m='2303910'>course,</span>
  <span m='2304190'>it's</span> <span m='2304320'>a</span> <span m='2304420'>little</span>
  <span m='2304660'>absurd</span> <span m='2305050'>for</span> <span m='2305180'>me</span>
  <span m='2305350'>to</span> <span m='2305490'>draw</span> <span m='2305780'>them</span>
  <span m='2306140'>when --</span> <span m='2307400'>I</span> <span m='2307520'>think</span>
  <span m='2307950'>what</span> <span m='2308350'>we</span> <span m='2308550'>see</span>
  <span m='2310990'>is</span> <span m='2312790'>that</span> <span m='2313000'>the</span>
  <span m='2313090'>residual</span> <span m='2313690'>drops</span> <span m='2314190'>pretty</span>
  <span m='2314540'>fast.</span> <span m='2315040'>The</span> <span m='2317500'>residual</span>
  <span m='2318140'>drops</span> <span m='2318560'>pretty</span> <span m='2318850'>fast</span>
  <span m='2319240'>and</span> <span m='2320000'>keeps</span> <span m='2320350'>going.</span>
  <span m='2323790'>Let's</span> <span m='2324010'>say</span> <span m='2324630'>Jacobi's</span>
  <span m='2325090'>method</span> <span m='2326210'>or</span> <span m='2327120'>in</span>
  <span m='2327300'>a</span> <span m='2327350'>minute</span> <span m='2327760'>or</span>
  <span m='2328030'>maybe</span> <span m='2328290'>the</span> <span m='2328590'>next</span>
  <span m='2329010'>time,</span> <span m='2330420'>another</span> <span m='2331430'>iterative</span>
  <span m='2331870'>method --</span> <span m='2332940'>but</span> <span m='2333230'>the</span>
  <span m='2333390'>error</span> <span m='2333890'>in</span> <span m='2334080'>the</span>
  <span m='2334200'>solution</span> <span m='2335580'>starts</span> <span m='2336080'>down</span>
  <span m='2336420'>fast</span> <span m='2337000'>and</span> <span m='2337130'>what's</span>
  <span m='2337350'>happening</span> <span m='2337830'>here</span> <span m='2338560'>is</span>
  <span m='2339000'>the</span> <span m='2339700'>high</span> <span m='2339930'>frequency</span>
  <span m='2340590'>components</span> <span m='2341230'>are</span> <span m='2341340'>getting</span>
  <span m='2341700'>killed,</span> <span m='2344190'>but</span> <span m='2344370'>those</span>
  <span m='2344680'>low</span> <span m='2345080'>frequency</span> <span m='2345760'>components</span>
  <span m='2347990'>are</span> <span m='2348950'>not</span> <span m='2349750'>disappearing,</span>
  <span m='2350430'>because</span> <span m='2350640'>we</span> <span m='2350820'>figured</span>
  <span m='2351400'>out</span> <span m='2351620'>that</span> <span m='2353100'>they</span>
  <span m='2353290'>give</span> <span m='2353500'>the</span> <span m='2353640'>spectral</span>
  <span m='2354090'>radius</span> <span m='2354530'>the</span> <span m='2354650'>largest</span>
  <span m='2355300'>eigenvalue.</span> <span m='2356410'>So</span> <span m='2356620'>somehow</span>
  <span m='2358910'>it</span> <span m='2359230'>slopes</span> <span m='2359950'>off</span>
  <span m='2360440'>and</span> <span m='2360610'>it's --</span> <span m='2367840'>the</span>
  <span m='2367960'>price</span> <span m='2368360'>of</span> <span m='2368510'>such</span>
  <span m='2368800'>a</span> <span m='2368880'>simple</span> <span m='2369260'>method</span>
  <span m='2370100'>is</span> <span m='2370360'>that</span> <span m='2370530'>you</span>
  <span m='2370660'>don't</span> <span m='2370940'>get</span> <span m='2371680'>great</span>
  <span m='2371990'>convergence.</span> </p><p><span m='2373020'>Of</span> <span m='2373190'>course,</span>
  <span m='2374890'>if</span> <span m='2375070'>I</span> <span m='2375150'>put</span>
  <span m='2375400'>this</span> <span m='2375590'>on</span> <span m='2375730'>a</span>
  <span m='2375850'>log-log</span> <span m='2376510'>plot,</span> <span m='2378520'>the</span>
  <span m='2378690'>slope</span> <span m='2380590'>would</span> <span m='2381140'>be</span>
  <span m='2381410'>exactly</span> <span m='2381940'>connected</span> <span m='2382470'>to</span>
  <span m='2382560'>the</span> <span m='2382770'>spectral</span> <span m='2383060'>radius.</span>
  <span m='2384310'>That's</span> <span m='2384970'>the</span> <span m='2385220'>rate</span>
  <span m='2385590'>of</span> <span m='2385720'>decay.</span> <span m='2388970'>It's</span>
  <span m='2389840'>the --</span> <span m='2390490'>ek</span> <span m='2391980'>is</span>
  <span m='2392290'>approximately --</span> <span m='2393320'>the</span> <span m='2393490'>size</span>
  <span m='2393890'>of</span> <span m='2394010'>ek</span> <span m='2394570'>is</span>
  <span m='2394720'>approximately</span> <span m='2395880'>that</span> <span m='2396480'>worst</span>
  <span m='2396920'>eigenvalue</span> <span m='2397750'>to</span> <span m='2397900'>the</span>
  <span m='2398020'>kth</span> <span m='2398360'>power.</span> <span m='2404830'>Do</span>
  <span m='2405100'>you</span> <span m='2405250'>see</span> <span m='2405430'>how</span>
  <span m='2405590'>this</span> <span m='2405820'>can</span> <span m='2405990'>happen?</span>
  <span m='2409080'>You</span> <span m='2409270'>see,</span> <span m='2409440'>this</span>
  <span m='2409690'>can</span> <span m='2409890'>be</span> <span m='2410030'>quite</span>
  <span m='2410340'>small,</span> <span m='2411830'>the</span> <span m='2411950'>residual</span>
  <span m='2412570'>quite</span> <span m='2412880'>small.</span> <span m='2413750'>I</span>
  <span m='2413890'>think</span> <span m='2414150'>it's</span> <span m='2414570'>very</span>
  <span m='2414860'>important</span> <span m='2415270'>to</span> <span m='2415330'>see</span>
  <span m='2415900'>the</span> <span m='2416100'>two</span> <span m='2416330'>different</span>
  <span m='2416670'>quantities.</span> <span m='2417760'>The</span> <span m='2417880'>residual</span>
  <span m='2418500'>can</span> <span m='2418690'>be</span> <span m='2418850'>quite</span>
  <span m='2419160'>small,</span> <span m='2420130'>but</span> <span m='2420320'>then</span>
  <span m='2421880'>from</span> <span m='2422150'>the</span> <span m='2422250'>residual,</span>
  <span m='2422780'>if</span> <span m='2422900'>I</span> <span m='2422990'>wanted</span>
  <span m='2423310'>to</span> <span m='2423400'>get</span> <span m='2423600'>back</span>
  <span m='2423840'>to</span> <span m='2423930'>the</span> <span m='2424040'>error,</span>
  <span m='2424640'>I'd</span> <span m='2424820'>have</span> <span m='2424990'>to</span>
  <span m='2425100'>multiply</span> <span m='2425600'>by</span> <span m='2425870'>a</span>
  <span m='2426100'>inverse</span> <span m='2427480'>and</span> <span m='2428060'>a</span>
  <span m='2428230'>inverse</span> <span m='2428400'>is</span> <span m='2428570'>not</span>
  <span m='2428980'>small.</span> <span m='2430730'>Our</span> <span m='2430910'>matrix</span>
  <span m='2431480'>a</span> <span m='2431850'>is</span> <span m='2432650'>pretty
  --</span> <span m='2433530'>has</span> <span m='2433810'>eigenvalues</span> <span
  m='2434660'>close</span> <span m='2435010'>to</span> <span m='2435130'>0.</span>
  <span m='2436090'>So</span> <span m='2436290'>a</span> <span m='2436540'>inverse</span>
  <span m='2436680'>is</span> <span m='2437190'>pretty</span> <span m='2437500'>big.</span>
  <span m='2438180'>a</span> <span m='2438590'>inverse</span> <span m='2440250'>times</span>
  <span m='2441060'>aek --</span> <span m='2443360'>this</span> <span m='2443620'>is</span>
  <span m='2443800'>small</span> <span m='2444450'>but</span> <span m='2444650'>a</span>
  <span m='2444810'>inverse</span> <span m='2447340'>picks</span> <span m='2447690'>up</span>
  <span m='2448170'>those</span> <span m='2449610'>smallest</span> <span m='2450110'>eigenvalues</span>
  <span m='2450820'>of</span> <span m='2450980'>a --</span> <span m='2451220'>picks</span>
  <span m='2451550'>up</span> <span m='2451720'>those</span> <span m='2452010'>low</span>
  <span m='2452270'>frequencies</span> <span m='2453510'>and</span> <span m='2454110'>it's</span>
  <span m='2455750'>bigger,</span> <span m='2459110'>slower</span> <span m='2459350'>to</span>
  <span m='2459590'>go</span> <span m='2459730'>to</span> <span m='2459860'>0</span>
  <span m='2460540'>as</span> <span m='2460780'>we</span> <span m='2460930'>see</span>
  <span m='2461210'>in</span> <span m='2461350'>this</span> <span m='2461590'>picture.</span>
  <span m='2462580'>So</span> <span m='2462760'>it's</span> <span m='2462890'>this</span>
  <span m='2463130'>picture</span> <span m='2464710'>that</span> <span m='2466360'>is</span>
  <span m='2466570'>our</span> <span m='2466750'>problem.</span> <span m='2468080'>That</span>
  <span m='2468370'>shows</span> <span m='2469730'>where</span> <span m='2470010'>Jacobi</span>
  <span m='2470610'>is</span> <span m='2471600'>not</span> <span m='2471960'>good</span>
  <span m='2472150'>enough.</span> </p><p><span m='2474580'>So</span> <span m='2474790'>what</span>
  <span m='2475330'>more</span> <span m='2475510'>to</span> <span m='2475650'>say</span>
  <span m='2475880'>about</span> <span m='2476330'>Jacobi?</span> <span m='2478760'>For</span>
  <span m='2478920'>this</span> <span m='2479170'>matrix</span> <span m='2479670'>k,</span>
  <span m='2480910'>we</span> <span m='2481030'>know</span> <span m='2481300'>its</span>
  <span m='2481580'>eigenvalues.</span> <span m='2484650'>The</span> <span m='2485000'>eigenvalues</span>
  <span m='2485610'>of</span> <span m='2485770'>m,</span> <span m='2486330'>we</span>
  <span m='2486450'>know</span> <span m='2486680'>exactly.</span> <span m='2487560'>The</span>
  <span m='2487710'>matrix</span> <span m='2488280'>m</span> <span m='2488580'>we</span>
  <span m='2488700'>know</span> <span m='2488900'>exactly.</span> <span m='2490000'>You</span>
  <span m='2490420'>see</span> <span m='2490595'>in</span> <span m='2490770'>that</span>
  <span m='2490950'>matrix --</span> <span m='2492480'>now</span> <span m='2492640'>if</span>
  <span m='2492730'>I</span> <span m='2493420'>said,</span> <span m='2493740'>look</span>
  <span m='2493990'>at</span> <span m='2494080'>that</span> <span m='2494280'>matrix</span>
  <span m='2495650'>and</span> <span m='2495830'>tell</span> <span m='2496000'>me</span>
  <span m='2496180'>something</span> <span m='2496550'>about</span> <span m='2496810'>its</span>
  <span m='2497040'>eigenvalues,</span> <span m='2497870'>what</span> <span m='2498140'>would</span>
  <span m='2498310'>you</span> <span m='2498430'>say?</span> <span m='2501370'>You</span>
  <span m='2501590'>would</span> <span m='2501780'>say,</span> <span m='2501950'>it's</span>
  <span m='2502150'>symmetric,</span> <span m='2502700'>so</span> <span m='2502840'>the</span>
  <span m='2502970'>eigenvalues</span> <span m='2503540'>are</span> <span m='2503650'>real</span>
  <span m='2505630'>and</span> <span m='2505840'>you</span> <span m='2505940'>would</span>
  <span m='2506140'>say</span> <span m='2506680'>that</span> <span m='2507070'>every</span>
  <span m='2507500'>eigenvalue</span> <span m='2508540'>is</span> <span m='2508800'>smaller</span>
  <span m='2509150'>than</span> <span m='2509330'>1.</span> <span m='2509870'>Why?</span>
  <span m='2510880'>Because</span> <span m='2511350'>every</span> <span m='2511660'>eigenvalue</span>
  <span m='2512640'>is --</span> <span m='2513400'>if</span> <span m='2513700'>you</span>
  <span m='2513860'>like</span> <span m='2514180'>to</span> <span m='2514310'>remember</span>
  <span m='2514820'>this</span> <span m='2515120'>business</span> <span m='2515600'>of</span>
  <span m='2517050'>silly</span> <span m='2517450'>circles,</span> <span m='2518660'>every</span>
  <span m='2518980'>eigenvalue</span> <span m='2519850'>is</span> <span m='2520010'>in</span>
  <span m='2520150'>a</span> <span m='2520260'>circle</span> <span m='2521540'>centered</span>
  <span m='2522180'>at</span> <span m='2522430'>this</span> <span m='2522700'>number
  -</span> <span m='2523280'>in</span> <span m='2523450'>other</span> <span m='2523610'>words,</span>
  <span m='2523860'>centered</span> <span m='2524180'>at</span> <span m='2524360'>0</span>
  <span m='2525260'>and</span> <span m='2525450'>its</span> <span m='2525620'>radius</span>
  <span m='2526390'>is</span> <span m='2527010'>the</span> <span m='2527310'>sum</span>
  <span m='2527630'>of</span> <span m='2527750'>those,</span> <span m='2528280'>which</span>
  <span m='2528510'>is</span> <span m='2528640'>1.</span> <span m='2530090'>So</span>
  <span m='2530630'>we</span> <span m='2530950'>know</span> <span m='2531260'>that</span>
  <span m='2531430'>every</span> <span m='2531710'>eigenvalue</span> <span m='2532430'>is</span>
  <span m='2534600'>in</span> <span m='2534760'>the</span> <span m='2534860'>unit</span>
  <span m='2535210'>circle</span> <span m='2536180'>and</span> <span m='2536410'>actually,</span>
  <span m='2538390'>it</span> <span m='2539940'>comes</span> <span m='2540360'>inside</span>
  <span m='2540830'>the</span> <span m='2540940'>unit</span> <span m='2541150'>circle,</span>
  <span m='2541510'>but</span> <span m='2541700'>not</span> <span m='2541950'>very</span>
  <span m='2542210'>much --</span> <span m='2542640'>only</span> <span m='2542960'>by</span>
  <span m='2543210'>1</span> <span m='2543480'>over</span> <span m='2543720'>n</span>
  <span m='2543920'>squared.</span> <span m='2545570'>What</span> <span m='2545770'>do</span>
  <span m='2545860'>I</span> <span m='2545960'>learn</span> <span m='2546350'>from</span>
  <span m='2546530'>this</span> <span m='2547260'>1</span> <span m='2547480'>over</span>
  <span m='2547730'>n</span> <span m='2547950'>squared?</span> <span m='2552090'>How</span>
  <span m='2552230'>many</span> <span m='2552460'>iterations</span> <span m='2553100'>do</span>
  <span m='2553220'>I</span> <span m='2553300'>have</span> <span m='2553490'>to</span>
  <span m='2553620'>take</span> <span m='2553950'>to</span> <span m='2554070'>reduce</span>
  <span m='2554580'>the</span> <span m='2554730'>error</span> <span m='2555090'>by,</span>
  <span m='2555410'>let's</span> <span m='2555650'>say,</span> <span m='2555860'>10</span>
  <span m='2556720'>or</span> <span m='2556900'>e</span> <span m='2557320'>or</span>
  <span m='2557460'>whatever?</span> <span m='2559630'>If</span> <span m='2559800'>the</span>
  <span m='2559910'>eigenvalues</span> <span m='2560650'>are</span> <span m='2560790'>1</span>
  <span m='2561290'>minus</span> <span m='2562260'>a</span> <span m='2562400'>constant</span>
  <span m='2563010'>over</span> <span m='2563320'>n</span> <span m='2563740'>squared,</span>
  <span m='2564900'>I'll</span> <span m='2565090'>have</span> <span m='2565310'>to</span>
  <span m='2565440'>take</span> <span m='2565680'>the</span> <span m='2565820'>n</span>
  <span m='2566040'>squared</span> <span m='2566440'>power.</span> <span m='2567930'>So</span>
  <span m='2568120'>if</span> <span m='2568250'>I</span> <span m='2568400'>have</span>
  <span m='2568590'>a</span> <span m='2568680'>matrix</span> <span m='2569230'>of</span>
  <span m='2569320'>order</span> <span m='2569790'>100,</span> <span m='2570900'>the</span>
  <span m='2571060'>number</span> <span m='2571370'>of</span> <span m='2571490'>iterations</span>
  <span m='2572160'>I'm</span> <span m='2572320'>going to</span> <span m='2572560'>need</span>
  <span m='2572820'>is</span> <span m='2574070'>100</span> <span m='2574440'>squared,</span>
  <span m='2574780'>10,000</span> <span m='2576270'>steps.</span> <span m='2579600'>Every</span>
  <span m='2579910'>step</span> <span m='2580250'>is</span> <span m='2580400'>fast,</span>
  <span m='2582250'>especially</span> <span m='2582840'>with</span> <span m='2583250'>the</span>
  <span m='2583500'>Jacobi</span> <span m='2584040'>choice.</span> <span m='2589420'>Here's</span>
  <span m='2589650'>my</span> <span m='2589840'>iteration --</span> <span m='2591510'>and</span>
  <span m='2591770'>p</span> <span m='2592060'>is</span> <span m='2592310'>just</span>
  <span m='2593730'>a</span> <span m='2593850'>multiple</span> <span m='2594250'>of</span>
  <span m='2594310'>the</span> <span m='2594370'>identity</span> <span m='2594920'>here.</span>
  <span m='2598350'>So</span> <span m='2598590'>every</span> <span m='2598820'>step</span>
  <span m='2599020'>is</span> <span m='2599220'>certainly</span> <span m='2599570'>fast.</span>
  <span m='2600830'>Every</span> <span m='2601100'>step</span> <span m='2601460'>involves</span>
  <span m='2601740'>a</span> <span m='2601840'>matrix</span> <span m='2602310'>multiplication</span>
  <span m='2603050'>and</span> <span m='2603430'>that's</span> <span m='2603710'>why</span>
  <span m='2603900'>I</span> <span m='2603930'>began</span> <span m='2604400'>the</span>
  <span m='2604510'>lecture</span> <span m='2604840'>by</span> <span m='2605000'>saying,</span>
  <span m='2605850'>matrix</span> <span m='2606330'>multiplications</span> <span m='2606940'>are</span>
  <span m='2607080'>fast.</span> <span m='2608000'>a</span> <span m='2608350'>times</span>
  <span m='2608900'>xk --</span> <span m='2609130'>that's</span> <span m='2609450'>the</span>
  <span m='2609570'>work</span> <span m='2610950'>and</span> <span m='2611520'>it's</span>
  <span m='2611850'>not</span> <span m='2612170'>much.</span> <span m='2612860'>It's</span>
  <span m='2613720'>maybe</span> <span m='2614370'>five</span> <span m='2614790'>non</span>
  <span m='2615060'>0s</span> <span m='2615340'>and</span> <span m='2615590'>a --</span>
  <span m='2616300'>so</span> <span m='2616460'>five</span> <span m='2616940'>n.</span>
  <span m='2617440'>That's</span> <span m='2617690'>fast,</span> <span m='2618640'>but</span>
  <span m='2618870'>if</span> <span m='2618990'>I</span> <span m='2619100'>have</span>
  <span m='2619250'>to</span> <span m='2619390'>do</span> <span m='2619520'>it</span>
  <span m='2619660'>10,000</span> <span m='2620430'>times</span> <span m='2620890'>just</span>
  <span m='2621140'>to</span> <span m='2621240'>reduce</span> <span m='2621680'>the</span>
  <span m='2621810'>error</span> <span m='2622140'>by</span> <span m='2623110'>some</span>
  <span m='2623810'>constant</span> <span m='2624300'>factor</span> <span m='2624720'>that's</span>
  <span m='2625090'>not</span> <span m='2625495'>good.</span> <span m='2627210'>So</span>
  <span m='2627400'>that's</span> <span m='2627670'>why</span> <span m='2627940'>people</span>
  <span m='2628610'>think</span> <span m='2629350'>Jacobi</span> <span m='2630300'>gives</span>
  <span m='2630520'>us</span> <span m='2630670'>the</span> <span m='2630780'>idea.</span>
  <span m='2632530'>It</span> <span m='2632820'>does</span> <span m='2633340'>knock</span>
  <span m='2633620'>off</span> <span m='2634110'>the</span> <span m='2634260'>high</span>
  <span m='2634560'>frequencies</span> <span m='2635380'>quite</span> <span m='2635670'>quickly,</span>
  <span m='2636130'>but</span> <span m='2636440'>it</span> <span m='2638090'>leaves</span>
  <span m='2638420'>those</span> <span m='2638600'>low</span> <span m='2638850'>frequencies.</span>
  </p><p><span m='2640740'>I</span> <span m='2640820'>was</span> <span m='2641000'>going
  to</span> <span m='2641220'>mention</span> <span m='2641780'>weighed</span> <span
  m='2642280'>Jacobi.</span> <span m='2643860'>Weighted</span> <span m='2644410'>Jacobi</span>
  <span m='2645890'>is</span> <span m='2646200'>to</span> <span m='2646350'>take</span>
  <span m='2649030'>instead</span> <span m='2649580'>of</span> <span m='2649760'>p
  --</span> <span m='2651860'>and</span> <span m='2652040'>put</span> <span m='2652230'>in</span>
  <span m='2652380'>a</span> <span m='2652450'>weight.</span> <span m='2655230'>So</span>
  <span m='2655390'>weighted</span> <span m='2656010'>Jacobi --</span> <span m='2656300'>let</span>
  <span m='2656470'>me</span> <span m='2657060'>put</span> <span m='2657260'>this</span>
  <span m='2657510'>here</span> <span m='2658060'>and</span> <span m='2658390'>we'll</span>
  <span m='2658530'>come</span> <span m='2658700'>back</span> <span m='2658970'>to</span>
  <span m='2659240'>it.</span> <span m='2659510'>So</span> <span m='2660340'>weighted</span>
  <span m='2661240'>Jacobi</span> <span m='2665490'>simply</span> <span m='2666010'>takes</span>
  <span m='2666890'>p</span> <span m='2667330'>to</span> <span m='2667470'>be</span>
  <span m='2668500'>the</span> <span m='2668660'>diagonal</span> <span m='2670640'>over</span>
  <span m='2674100'>a</span> <span m='2674260'>factor</span> <span m='2674720'>omega.</span>
  <span m='2679240'>For</span> <span m='2679380'>example,</span> <span m='2681670'>omega</span>
  <span m='2682090'>equals --</span> <span m='2684760'>2/3</span> <span m='2686130'>is</span>
  <span m='2686285'>a</span> <span m='2686440'>good</span> <span m='2686610'>choice.</span>
  <span m='2689300'>Let</span> <span m='2689440'>me</span> <span m='2689550'>draw</span>
  <span m='2689910'>the --</span> <span m='2690640'>you</span> <span m='2690930'>can</span>
  <span m='2691110'>imagine</span> <span m='2691600'>that</span> <span m='2691740'>if</span>
  <span m='2691900'>I --</span> <span m='2693200'>this</span> <span m='2693430'>is</span>
  <span m='2693600'>2</span> <span m='2693810'>times</span> <span m='2694080'>the</span>
  <span m='2694200'>identity,</span> <span m='2695420'>so</span> <span m='2695590'>it's</span>
  <span m='2695780'>just</span> <span m='2696040'>2</span> <span m='2696340'>over</span>
  <span m='2696630'>omega</span> <span m='2697090'>i --</span> <span m='2698020'>I'm</span>
  <span m='2698220'>just</span> <span m='2698530'>choosing</span> <span m='2698840'>a</span>
  <span m='2698930'>different</span> <span m='2699310'>constant.</span> <span m='2701280'>I'm</span>
  <span m='2701420'>just</span> <span m='2701700'>choosing</span> <span m='2702000'>a</span>
  <span m='2702080'>different</span> <span m='2702470'>constant</span> <span m='2702840'>in</span>
  <span m='2703180'>p</span> <span m='2703780'>and</span> <span m='2704010'>has</span>
  <span m='2704740'>a</span> <span m='2704850'>simple</span> <span m='2705280'>affect</span>
  <span m='2705950'>on</span> <span m='2706350'>n.</span> <span m='2708260'>I'll</span>
  <span m='2708570'>draw</span> <span m='2708760'>the</span> <span m='2708890'>pictures.</span>
  <span m='2712100'>The</span> <span m='2712280'>eigenvalues</span> <span m='2713110'>of</span>
  <span m='2713540'>m</span> <span m='2714620'>are</span> <span m='2714880'>these</span>
  <span m='2715270'>cosines.</span> <span m='2716180'>So</span> <span m='2716400'>I'm</span>
  <span m='2716520'>going to</span> <span m='2716760'>draw</span> <span m='2717080'>those</span>
  <span m='2718080'>cosines,</span> <span m='2718680'>the</span> <span m='2718810'>eigenvalues</span>
  <span m='2719580'>of</span> <span m='2719705'>m.</span> <span m='2719830'>So</span>
  <span m='2719980'>they</span> <span m='2720150'>start --</span> <span m='2720960'>I'll</span>
  <span m='2721170'>just</span> <span m='2721500'>draw</span> <span m='2721770'>the</span>
  <span m='2721850'>picture</span> <span m='2722250'>of</span> <span m='2722370'>cos</span>
  <span m='2722585'>theta</span> <span m='2723030'>if</span> <span m='2723210'>I</span>
  <span m='2723290'>can.</span> <span m='2723940'>What</span> <span m='2724170'>does</span>
  <span m='2724280'>a</span> <span m='2724390'>graph</span> <span m='2724740'>of</span>
  <span m='2724890'>cos</span> <span m='2725460'>theta</span> <span m='2725620'>look</span>
  <span m='2725880'>like?</span> <span m='2732060'>From</span> <span m='2732280'>0</span>
  <span m='2732690'>to</span> <span m='2732780'>pi,</span> <span m='2734840'>so</span>
  <span m='2735060'>I'm</span> <span m='2735210'>going</span> <span m='2735380'>to</span>
  <span m='2735440'>see --</span> <span m='2736230'>this</span> <span m='2736410'>is</span>
  <span m='2736640'>theta</span> <span m='2736900'>equals</span> <span m='2737300'>0.</span>
  <span m='2738910'>This</span> <span m='2739100'>is</span> <span m='2739300'>theta</span>
  <span m='2739530'>equal</span> <span m='2739890'>pi.</span> <span m='2741890'>If</span>
  <span m='2742060'>I</span> <span m='2742160'>just</span> <span m='2742530'>draw</span>
  <span m='2742980'>cos</span> <span m='2743540'>theta --</span> <span m='2744360'>please</span>
  <span m='2744910'>tell</span> <span m='2745120'>me</span> <span m='2745260'>if</span>
  <span m='2745460'>this</span> <span m='2745670'>isn't</span> <span m='2745980'>it.</span>
  <span m='2747070'>Is</span> <span m='2747300'>it</span> <span m='2747450'>something</span>
  <span m='2747840'>like</span> <span m='2748030'>that?</span> <span m='2752620'>Now</span>
  <span m='2753000'>where</span> <span m='2753340'>are</span> <span m='2753600'>these</span>
  <span m='2754970'>theta</span> <span m='2755370'>1.</span> <span m='2756860'>the</span>
  <span m='2756980'>bad</span> <span m='2757320'>one.</span> <span m='2757910'>Theta</span>
  <span m='2758320'>2,</span> <span m='2758940'>theta</span> <span m='2759330'>3,</span>
  <span m='2760030'>theta</span> <span m='2760360'>4,</span> <span m='2761110'>theta</span>
  <span m='2761420'>five,</span> <span m='2761840'>equally</span> <span m='2762280'>bad</span>
  <span m='2762680'>down</span> <span m='2762970'>here.</span> </p><p><span m='2763580'>So</span>
  <span m='2763740'>there's</span> <span m='2764880'>cos,</span> <span m='2765290'>there's</span>
  <span m='2765930'>the</span> <span m='2766040'>biggest</span> <span m='2767060'>one.</span>
  <span m='2767180'>That's</span> <span m='2767300'>rho</span> <span m='2767940'>and</span>
  <span m='2768130'>you</span> <span m='2768250'>see</span> <span m='2768460'>it's</span>
  <span m='2768670'>pretty</span> <span m='2768940'>near</span> <span m='2769200'>1.</span>
  <span m='2772130'>Here</span> <span m='2772370'>I'm</span> <span m='2772560'>going
  to</span> <span m='2772770'>hit --</span> <span m='2773760'>at</span> <span m='2773940'>this</span>
  <span m='2774210'>frequency,</span> <span m='2774890'>I'm</span> <span m='2775030'>going
  to</span> <span m='2775200'>hit</span> <span m='2775770'>minus</span> <span m='2776610'>rho.</span>
  <span m='2777620'>It'll</span> <span m='2777800'>be,</span> <span m='2778120'>again,</span>
  <span m='2778610'>near</span> <span m='2778830'>1.</span> <span m='2780730'>So</span>
  <span m='2781580'>the</span> <span m='2782930'>spectral</span> <span m='2783230'>radius</span>
  <span m='2783680'>is</span> <span m='2783880'>that,</span> <span m='2784460'>that's</span>
  <span m='2784980'>rho.</span> <span m='2787180'>The</span> <span m='2787320'>cosine</span>
  <span m='2788140'>of</span> <span m='2788270'>that</span> <span m='2788550'>smallest</span>
  <span m='2789230'>angle,</span> <span m='2790180'>theta</span> <span m='2790580'>over</span>
  <span m='2791670'>n</span> <span m='2791880'>plus</span> <span m='2792090'>1.</span>
  <span m='2794160'>What</span> <span m='2794340'>happens</span> <span m='2794740'>when</span>
  <span m='2794940'>I</span> <span m='2795010'>bring</span> <span m='2795300'>in</span>
  <span m='2795450'>these</span> <span m='2795700'>weights?</span> <span m='2796740'>It</span>
  <span m='2796870'>turns</span> <span m='2797250'>out</span> <span m='2797590'>that</span>
  <span m='2800120'>now</span> <span m='2800470'>the</span> <span m='2800600'>eigenvalues</span>
  <span m='2801920'>of</span> <span m='2802100'>m</span> <span m='2803090'>with</span>
  <span m='2803320'>the</span> <span m='2803420'>weights</span> <span m='2804690'>will</span>
  <span m='2804980'>be</span> <span m='2805320'>1 --</span> <span m='2806020'>it</span>
  <span m='2806180'>turns</span> <span m='2806520'>out</span> <span m='2806780'>1</span>
  <span m='2807160'>minus</span> <span m='2807790'>omega</span> <span m='2808780'>plus</span>
  <span m='2809580'>omega</span> <span m='2810140'>cos</span> <span m='2810540'>theta.</span>
  <span m='2813820'>You'll</span> <span m='2814100'>see</span> <span m='2814300'>it</span>
  <span m='2814430'>in</span> <span m='2814560'>the</span> <span m='2814660'>notes,</span>
  <span m='2815460'>no</span> <span m='2815640'>problem.</span> <span m='2816720'>So</span>
  <span m='2818100'>it's</span> <span m='2818270'>simply</span> <span m='2818580'>influenced</span>
  <span m='2819160'>by</span> <span m='2819350'>omega.</span> <span m='2820990'>If</span>
  <span m='2821290'>omega</span> <span m='2821800'>is</span> <span m='2822010'>2/3
  --</span> <span m='2823440'>if</span> <span m='2823680'>omega</span> <span m='2823910'>is</span>
  <span m='2824090'>2/3,</span> <span m='2824660'>then</span> <span m='2824820'>I</span>
  <span m='2824950'>have</span> <span m='2825100'>1</span> <span m='2825250'>minus</span>
  <span m='2825510'>omega</span> <span m='2825910'>as</span> <span m='2826150'>1/3</span>
  <span m='2827540'>plus</span> <span m='2828380'>2/3</span> <span m='2829950'>cos</span>
  <span m='2830275'>theta.</span> <span m='2835620'>Instead</span> <span m='2836020'>of</span>
  <span m='2836110'>graphing</span> <span m='2836640'>cos</span> <span m='2836975'>theta,</span>
  <span m='2837380'>which</span> <span m='2837660'>I've</span> <span m='2837870'>done
  --</span> <span m='2838240'>let</span> <span m='2838710'>me</span> <span m='2838850'>draw
  --</span> <span m='2839680'>let</span> <span m='2839800'>me</span> <span m='2839920'>complete</span>
  <span m='2840220'>this</span> <span m='2840520'>graph</span> <span m='2841350'>for</span>
  <span m='2841830'>cos</span> <span m='2842070'>theta.</span> <span m='2843220'>The</span>
  <span m='2843420'>eigenvalues</span> <span m='2845000'>unweighted</span> <span m='2845670'>with</span>
  <span m='2845960'>weight</span> <span m='2846370'>omega</span> <span m='2846760'>equal</span>
  <span m='2847110'>1.</span> <span m='2847880'>Now</span> <span m='2850160'>it's</span>
  <span m='2850370'>this</span> <span m='2850610'>thing</span> <span m='2850880'>I</span>
  <span m='2851000'>draw.</span> <span m='2851450'>So</span> <span m='2852120'>what</span>
  <span m='2852350'>happens?</span> <span m='2853420'>What's</span> <span m='2853680'>going</span>
  <span m='2853930'>on</span> <span m='2854120'>here?</span> <span m='2856170'>For</span>
  <span m='2856440'>a</span> <span m='2856520'>small</span> <span m='2856930'>theta,</span>
  <span m='2859070'>cosine</span> <span m='2859600'>is</span> <span m='2859780'>near</span>
  <span m='2860320'>1.</span> <span m='2860890'>I'm</span> <span m='2861090'>again</span>
  <span m='2861480'>near</span> <span m='2861640'>1.</span> <span m='2862200'>In</span>
  <span m='2862330'>fact,</span> <span m='2862660'>I'm</span> <span m='2862770'>probably</span>
  <span m='2863260'>even</span> <span m='2863520'>little</span> <span m='2863840'>worse,</span>
  <span m='2865100'>probably</span> <span m='2865530'>up</span> <span m='2865740'>here.</span>
  <span m='2871230'>I</span> <span m='2871400'>think</span> <span m='2871680'>it</span>
  <span m='2873830'>goes</span> <span m='2874120'>down</span> <span m='2874370'>like</span>
  <span m='2874580'>that.</span> <span m='2877410'>So</span> <span m='2877630'>it</span>
  <span m='2877770'>starts</span> <span m='2878170'>at</span> <span m='2878360'>near</span>
  <span m='2878570'>1,</span> <span m='2878990'>but</span> <span m='2879200'>it</span>
  <span m='2879360'>ends</span> <span m='2881040'>when</span> <span m='2881210'>theta</span>
  <span m='2881500'>is</span> <span m='2881740'>pi.</span> <span m='2883180'>This</span>
  <span m='2883370'>is</span> <span m='2883540'>1/3</span> <span m='2884210'>minus</span>
  <span m='2884640'>2/3.</span> <span m='2885140'>It</span> <span m='2885280'>ends</span>
  <span m='2885520'>at</span> <span m='2885650'>minus</span> <span m='2886030'>1/3.</span>
  <span m='2886770'>That's</span> <span m='2886960'>a</span> <span m='2887040'>lot</span>
  <span m='2887300'>smarter.</span> <span m='2890150'>This</span> <span m='2890390'>one</span>
  <span m='2890570'>ended</span> <span m='2890980'>at</span> <span m='2891120'>minus</span>
  <span m='2891570'>1,</span> <span m='2892490'>that</span> <span m='2892720'>one</span>
  <span m='2892900'>ended</span> <span m='2893280'>at</span> <span m='2893410'>near</span>
  <span m='2893780'>minus</span> <span m='2894180'>1</span> <span m='2894470'>but</span>
  <span m='2894620'>this</span> <span m='2894850'>one</span> <span m='2895040'>will</span>
  <span m='2895250'>end</span> <span m='2895730'>with</span> <span m='2895910'>omega
  --</span> <span m='2896820'>this</span> <span m='2896990'>is</span> <span m='2897160'>the</span>
  <span m='2897310'>omega</span> <span m='2897680'>equal</span> <span m='2900520'>2/3</span>
  <span m='2901130'>of</span> <span m='2901260'>weighted</span> <span m='2901670'>1.</span>
  <span m='2902400'>All</span> <span m='2902620'>you've</span> <span m='2902820'>done</span>
  <span m='2903090'>is</span> <span m='2903260'>fix</span> <span m='2903780'>the</span>
  <span m='2904710'>high</span> <span m='2904900'>frequency.</span> <span m='2906830'>When</span>
  <span m='2907000'>I</span> <span m='2907090'>say,</span> <span m='2907710'>that</span>
  <span m='2907800'>was</span> <span m='2907960'>a</span> <span m='2908040'>good</span>
  <span m='2908220'>thing</span> <span m='2908450'>to</span> <span m='2908580'>do,</span>
  <span m='2910080'>the</span> <span m='2910280'>high</span> <span m='2910550'>frequencies</span>
  <span m='2912070'>are</span> <span m='2912220'>no</span> <span m='2912390'>longer</span>
  <span m='2912800'>a</span> <span m='2912880'>problem.</span> <span m='2914060'>The</span>
  <span m='2914220'>low</span> <span m='2914470'>frequencies</span> <span m='2915530'>still</span>
  <span m='2916120'>are.</span> <span m='2917340'>So</span> <span m='2917980'>the</span>
  <span m='2918060'>only</span> <span m='2918280'>way</span> <span m='2918440'>we'll</span>
  <span m='2918630'>get</span> <span m='2918860'>out</span> <span m='2919040'>of</span>
  <span m='2919120'>that</span> <span m='2919320'>problem</span> <span m='2919800'>is</span>
  <span m='2920400'>moving</span> <span m='2920830'>to</span> <span m='2920970'>multigrid.</span>
  </p><p><span m='2923470'>Can</span> <span m='2923670'>I,</span> <span m='2924440'>in</span>
  <span m='2924650'>the</span> <span m='2924740'>remaining</span> <span m='2925370'>minute,</span>
  <span m='2926830'>report</span> <span m='2927510'>on</span> <span m='2928680'>Gauss-Seidel</span>
  <span m='2930090'>and</span> <span m='2930250'>then</span> <span m='2930390'>I'll</span>
  <span m='2930560'>come</span> <span m='2930760'>back</span> <span m='2931030'>to</span>
  <span m='2931140'>it?</span> <span m='2931220'>But</span> <span m='2931710'>quick</span>
  <span m='2932030'>report</span> <span m='2932420'>on</span> <span m='2932590'>Gauss-Seidel.</span>
  <span m='2934320'>So</span> <span m='2934450'>what's</span> <span m='2934690'>the</span>
  <span m='2934790'>difference</span> <span m='2935230'>in</span> <span m='2935370'>Gauss-Seidel?</span>
  <span m='2938150'>What</span> <span m='2938360'>does</span> <span m='2938480'>Gauss-Seidel</span>
  <span m='2939090'>do?</span> <span m='2939560'>It</span> <span m='2939840'>uses</span>
  <span m='2940450'>the</span> <span m='2940570'>latest</span> <span m='2941050'>information.</span>
  <span m='2941740'>As</span> <span m='2941860'>soon</span> <span m='2942140'>as</span>
  <span m='2942250'>you</span> <span m='2942400'>compute</span> <span m='2942900'>an</span>
  <span m='2943080'>x,</span> <span m='2943260'>you</span> <span m='2943400'>use</span>
  <span m='2943960'>it.</span> <span m='2945770'>Jacobi</span> <span m='2947230'>compueted</span>
  <span m='2948750'>all --</span> <span m='2950670'>had</span> <span m='2950890'>to</span>
  <span m='2950970'>key</span> <span m='2951900'>all</span> <span m='2952130'>these</span>
  <span m='2952410'>xs</span> <span m='2953810'>until</span> <span m='2954190'>it</span>
  <span m='2954350'>found</span> <span m='2954810'>all</span> <span m='2954990'>the</span>
  <span m='2955110'>new</span> <span m='2955290'>xs,</span> <span m='2956840'>but</span>
  <span m='2957090'>the</span> <span m='2957510'>Gauss-Seidel</span> <span m='2958170'>idea</span>
  <span m='2958475'>is,</span> <span m='2958780'>as</span> <span m='2958910'>soon</span>
  <span m='2959100'>as</span> <span m='2959190'>you</span> <span m='2959300'>have</span>
  <span m='2959510'>a</span> <span m='2959600'>better</span> <span m='2959940'>x,</span>
  <span m='2961030'>put</span> <span m='2961230'>it</span> <span m='2961360'>in</span>
  <span m='2961510'>the</span> <span m='2961620'>system.</span> <span m='2962010'>So</span>
  <span m='2962170'>the</span> <span m='2962300'>storage</span> <span m='2962710'>is</span>
  <span m='2962990'>cut</span> <span m='2963190'>in</span> <span m='2963320'>half,</span>
  <span m='2963720'>because</span> <span m='2963910'>you're</span> <span m='2965290'>not</span>
  <span m='2965620'>saving</span> <span m='2966160'>a</span> <span m='2966340'>big</span>
  <span m='2967720'>old</span> <span m='2968050'>vector</span> <span m='2968530'>while</span>
  <span m='2968780'>you</span> <span m='2968970'>compute</span> <span m='2969460'>the</span>
  <span m='2969500'>new</span> <span m='2969680'>one.</span> <span m='2972380'>I'll</span>
  <span m='2972640'>write</span> <span m='2972870'>down</span> <span m='2973080'>Gauss-Seidel</span>
  <span m='2973700'>again.</span> <span m='2974550'>So</span> <span m='2976390'>it's</span>
  <span m='2976800'>more</span> <span m='2977010'>up</span> <span m='2977160'>to</span>
  <span m='2977280'>date</span> <span m='2977870'>and</span> <span m='2978110'>the</span>
  <span m='2978180'>effect</span> <span m='2978650'>is</span> <span m='2979980'>that</span>
  <span m='2980270'>the</span> <span m='2980470'>Jacobi</span> <span m='2981010'>eigenvalues</span>
  <span m='2981950'>get</span> <span m='2982140'>squared.</span> <span m='2984080'>So</span>
  <span m='2984220'>you're</span> <span m='2984450'>squaring</span> <span m='2985270'>numbers</span>
  <span m='2987440'>that</span> <span m='2987740'>are</span> <span m='2988730'>less</span>
  <span m='2988990'>than</span> <span m='2989140'>1.</span> <span m='2990380'>So</span>
  <span m='2990910'>Gauss-Seidel,</span> <span m='2994390'>this</span> <span m='2995430'>gives</span>
  <span m='2995980'>the</span> <span m='2996170'>Jacobi</span> <span m='2996810'>eigenvalues</span>
  <span m='2999330'>squared.</span> <span m='3001460'>The</span> <span m='3001670'>result</span>
  <span m='3002100'>is</span> <span m='3002460'>that</span> <span m='3002790'>if</span>
  <span m='3002990'>I</span> <span m='3003100'>draw</span> <span m='3003380'>the</span>
  <span m='3003500'>same</span> <span m='3003810'>curve</span> <span m='3004065'>for</span>
  <span m='3004320'>Gauss-Seidel,</span> <span m='3006310'>I'll</span> <span m='3007690'>be</span>
  <span m='3007860'>below,</span> <span m='3008310'>right?</span> <span m='3011920'>Essentially</span>
  <span m='3012820'>a</span> <span m='3012920'>Gauss-Seidel</span> <span m='3013730'>step</span>
  <span m='3014000'>is</span> <span m='3014100'>worth</span> <span m='3014440'>two</span>
  <span m='3014720'>Jacobi</span> <span m='3015220'>steps.</span> <span m='3016660'>Eigenvalues</span>
  <span m='3017330'>get</span> <span m='3017520'>squared</span> <span m='3017980'>as</span>
  <span m='3018160'>they</span> <span m='3018300'>would</span> <span m='3018580'>do</span>
  <span m='3018790'>in</span> <span m='3019200'>two</span> <span m='3019340'>Jacobi</span>
  <span m='3020460'>steps.</span> <span m='3020496'>If</span> <span m='3020533'>I</span>
  <span m='3020570'>do</span> <span m='3020890'>Jacobi</span> <span m='3021200'>twice,</span>
  <span m='3021610'>I</span> <span m='3021710'>square</span> <span m='3021930'>its</span>
  <span m='3022150'>eigenvalues.</span> <span m='3023460'>So</span> <span m='3024580'>it</span>
  <span m='3024740'>seems</span> <span m='3025030'>like</span> <span m='3025530'>absolutely</span>
  <span m='3026100'>a</span> <span m='3026325'>smart</span> <span m='3026550'>move.</span>
  <span m='3027110'>It's</span> <span m='3027310'>not</span> <span m='3027600'>brilliant,</span>
  <span m='3029110'>because</span> <span m='3032340'>this</span> <span m='3032570'>becomes</span>
  <span m='3033070'>cosine</span> <span m='3033580'>squared.</span> <span m='3035320'>I</span>
  <span m='3035470'>lose</span> <span m='3035910'>the</span> <span m='3036030'>1/2,</span>
  <span m='3038160'>but</span> <span m='3038360'>I'm</span> <span m='3038520'>still</span>
  <span m='3040030'>very,</span> <span m='3040500'>very</span> <span m='3040830'>close</span>
  <span m='3041110'>to</span> <span m='3041220'>1.</span> <span m='3041960'>It</span>
  <span m='3042110'>still</span> <span m='3042390'>takes</span> <span m='3042960'>order</span>
  <span m='3043340'>n</span> <span m='3043640'>squared</span> <span m='3044400'>iterations</span>
  <span m='3045140'>to</span> <span m='3045470'>get</span> <span m='3045700'>anywhere.</span>
  <span m='3047150'>so</span> <span m='3047370'>Jacobi</span> <span m='3047940'>is,</span>
  <span m='3049950'>you</span> <span m='3050090'>could</span> <span m='3050260'>say,</span>
  <span m='3050490'>replaced</span> <span m='3051060'>by</span> <span m='3051260'>Gauss-Seidel</span>
  <span m='3051960'>as</span> <span m='3052140'>being</span> <span m='3052840'>one</span>
  <span m='3053100'>step</span> <span m='3053470'>better,</span> <span m='3053760'>but</span>
  <span m='3053980'>it's</span> <span m='3054190'>not</span> <span m='3054530'>good</span>
  <span m='3054740'>enough</span> <span m='3055750'>and</span> <span m='3056220'>that's</span>
  <span m='3056530'>why</span> <span m='3058760'>the</span> <span m='3060550'>subject</span>
  <span m='3061050'>kept</span> <span m='3061290'>going.</span> <span m='3062950'>This</span>
  <span m='3063640'>gives</span> <span m='3064240'>rho</span> <span m='3064980'>as</span>
  <span m='3065320'>1</span> <span m='3065840'>minus</span> <span m='3066650'>order</span>
  <span m='3067140'>of</span> <span m='3067315'>1</span> <span m='3067490'>over</span>
  <span m='3067770'>n</span> <span m='3068140'>first</span> <span m='3068590'>power,</span>
  <span m='3071210'>where</span> <span m='3071490'>these</span> <span m='3071940'>were</span>
  <span m='3072720'>1</span> <span m='3072950'>minus</span> <span m='3073350'>1</span>
  <span m='3073580'>over</span> <span m='3073790'>n</span> <span m='3074040'>squared.</span>
  <span m='3074920'>So</span> <span m='3075160'>this</span> <span m='3075400'>is</span>
  <span m='3075610'>definitely</span> <span m='3076100'>further</span> <span m='3076550'>from</span>
  <span m='3076810'>1</span> <span m='3077460'>and</span> <span m='3077780'>then</span>
  <span m='3077990'>this</span> <span m='3078240'>can</span> <span m='3078450'>be</span>
  <span m='3078620'>way</span> <span m='3079140'>further</span> <span m='3079860'>from</span>
  <span m='3080060'>1.</span> </p><p><span m='3080460'>So</span> <span m='3080980'>you</span>
  <span m='3081120'>can</span> <span m='3081320'>see</span> <span m='3081620'>some</span>
  <span m='3081830'>of</span> <span m='3081990'>the</span> <span m='3082750'>numerical</span>
  <span m='3083250'>experiments</span> <span m='3083980'>and</span> <span m='3084250'>analysis</span>
  <span m='3085000'>that's</span> <span m='3085170'>coming.</span> <span m='3086340'>I'll</span>
  <span m='3086500'>see</span> <span m='3086630'>you</span> <span m='3087420'>Wednesday</span>
  <span m='3088500'>to</span> <span m='3088720'>finish</span> <span m='3089050'>this</span>
  <span m='3089450'>and</span> <span m='3089770'>move</span> <span m='3090090'>into</span>
  <span m='3090400'>multigrid,</span> <span m='3091280'>which</span> <span m='3091570'>uses</span>
  <span m='3091810'>these</span> <span m='3092050'>guys.</span> </p>
type: course
uid: 4f27eb5dfa89a234abfeb050423eaa59

---
None