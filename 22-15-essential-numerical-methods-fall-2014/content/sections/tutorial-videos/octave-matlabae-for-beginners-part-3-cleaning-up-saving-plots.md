---
about_this_resource_text: <p><strong>Description:</strong> Clean up and save plots.
  Configure axis labels. Call another script (plotdefaults.m) within fitting.m.  Get
  Octave help with 'doc' command. Using comments in scripts. Save plots with the 'print'
  command.</p><p><strong>Instructor:</strong> Prof. Ian Hutchinson</p>
course_id: 22-15-essential-numerical-methods-fall-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: WUxImdA7k8E
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  title: Video-YouTube-Stream
  type: Video
  uid: edb3a4d78283a1d89fa3789e324b16ba
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/WUxImdA7k8E/default.jpg
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5aa04fb7185588e7b760c9c02d191ee5
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id978726426
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  title: Video-iTunes U-MP4
  type: Video
  uid: 1a10f5e3f6ffcea7c76ba0305f58a134
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT22.15F14/MIT22_15F14_octavefit3_720p.mp4
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  title: Video-Internet Archive-MP4
  type: Video
  uid: fefb1156fdd137bbca57446f8d08a22a
- id: 3Play-3PlayYouTubeid-MP4
  media_location: WUxImdA7k8E
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 96edbbd584665a67a16dbd8a3428d157
- id: 3Play-3PlayYouTubeid-MP4_1
  media_location: WUxImdA7k8E
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c6ed8f4d9e9d546f58d4c83eb42b1f86
- id: WUxImdA7k8E.srt
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  technical_location: https://ocw.mit.edu/courses/nuclear-engineering/22-15-essential-numerical-methods-fall-2014/tutorial-videos/octave-matlabae-for-beginners-part-3-cleaning-up-saving-plots/WUxImdA7k8E.srt
  title: 3play caption file
  type: null
  uid: 0c1ad90118663f84d1dcbaae2a5d0de3
- id: WUxImdA7k8E.pdf
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  technical_location: https://ocw.mit.edu/courses/nuclear-engineering/22-15-essential-numerical-methods-fall-2014/tutorial-videos/octave-matlabae-for-beginners-part-3-cleaning-up-saving-plots/WUxImdA7k8E.pdf
  title: 3play pdf file
  type: null
  uid: 80855f8b4a94bc5d3454b9f4e457c06e
- id: Caption-3Play YouTube id-SRT
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 12cf081dadb76a10ba912647953b4980
- id: Transcript-3Play YouTube id-PDF
  parent_uid: f1a26b7dcdab6126cdf5e30159517282
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1f88c2dc86963b1667260c9c305f2f92
inline_embed_id: "64784347octave/matlab\xAEforbeginners,part3:cleaningup&savingplots74753924"
layout: video
order_index: null
parent_uid: 0e9a581264e807a6c482f19256c29502
related_resources_text: <p><a href="./resolveuid/a16b1d38080987b1ec8d6d8882c7fd3e">plotdefaults.m
  script used in this video (M)</a></p>
short_url: octave-matlabae-for-beginners-part-3-cleaning-up-saving-plots
technical_location: https://ocw.mit.edu/courses/nuclear-engineering/22-15-essential-numerical-methods-fall-2014/tutorial-videos/octave-matlabae-for-beginners-part-3-cleaning-up-saving-plots
template_type: Tabbed
title: "Octave/MATLAB\xAE for Beginners, Part 3: Cleaning Up & Saving Plots"
transcript: '<p><span m=''8170''>IAN HUTCHINSON: Let''s</span> <span m=''8420''>just</span>
  <span m=''8590''>finish</span> <span m=''8890''>this</span> <span m=''9110''>off</span>
  <span m=''9390''>by</span> <span m=''10480''>cleaning</span> <span m=''10940''>up</span>
  <span m=''11080''>this</span> <span m=''11390''>plot</span> <span m=''13080''>and</span>
  <span m=''13480''>saving</span> <span m=''13890''>it.</span> <span m=''15220''>In</span>
  <span m=''15310''>the first</span> <span m=''15700''>case,</span> <span m=''18090''>I</span>
  <span m=''18150''>don''t</span> <span m=''18330''>have</span> <span m=''18760''>any</span>
  <span m=''19010''>labels</span> <span m=''19390''>on</span> <span m=''19510''>my</span>
  <span m=''19660''>axes.</span> <span m=''20760''>That''s</span> <span m=''21120''>bad.</span>
  <span m=''22080''>Let</span> <span m=''22280''>me</span> <span m=''22470''>put</span>
  <span m=''22700''>some</span> <span m=''22940''>labels</span> <span m=''23610''>on</span>
  <span m=''23760''>my</span> <span m=''23930''>axes.</span> <span m=''25790''>X-label</span>
  <span m=''28050''>is</span> <span m=''28390''>the</span> <span m=''28530''>way</span>
  <span m=''28740''>you</span> <span m=''28890''>do</span> <span m=''29080''>this.</span>
  <span m=''29930''>And</span> <span m=''31690''>in</span> <span m=''31800''>this</span>
  <span m=''32009''>case</span> <span m=''32400''>I</span> <span m=''32710''>have</span>
  <span m=''33020''>a</span> <span m=''33080''>very</span> <span m=''33390''>simple</span>
  <span m=''35250''>label</span> <span m=''35630''>that</span> <span m=''35770''>I</span>
  <span m=''35860''>want.</span> <span m=''37490''>And the</span> <span m=''37560''>same</span>
  <span m=''37880''>thing,</span> <span m=''38300''>presumably</span> <span m=''38970''>for</span>
  <span m=''39390''>Y-label.</span> <span m=''42600''>That</span> <span m=''42910''>will</span>
  <span m=''44670''>at</span> <span m=''44810''>least</span> <span m=''45850''>put</span>
  <span m=''46160''>some</span> <span m=''46360''>labels</span> <span m=''46740''>on.</span>
  <span m=''47020''>Aren''t</span> <span m=''47390''>they</span> <span m=''47510''>horribly</span>
  <span m=''47970''>small?</span> <span m=''49260''>But</span> <span m=''49500''>they</span>
  <span m=''49680''>are</span> <span m=''49830''>there.</span> </p><p><span m=''52410''>Now,</span>
  <span m=''52770''>I</span> <span m=''53080''>want</span> <span m=''53340''>to</span>
  <span m=''53500''>improve</span> <span m=''54010''>this</span> <span m=''54270''>plot</span>
  <span m=''55690''>in</span> <span m=''55830''>general.</span> <span m=''57740''>Let</span>
  <span m=''57980''>me</span> <span m=''58680''>point</span> <span m=''58960''>out</span>
  <span m=''59140''>another</span> <span m=''59450''>thing</span> <span m=''59780''>that</span>
  <span m=''60090''>I</span> <span m=''60220''>want</span> <span m=''60520''>to</span>
  <span m=''60620''>do.</span> <span m=''62540''>I</span> <span m=''62710''>don''t</span>
  <span m=''62890''>want</span> <span m=''63030''>to have</span> <span m=''63390''>hold</span>
  <span m=''63900''>on</span> <span m=''64110''>permanently,</span> <span m=''64940''>so</span>
  <span m=''65239''>let</span> <span m=''65480''>me</span> <span m=''66500''>put</span>
  <span m=''66770''>hold</span> <span m=''67330''>off</span> <span m=''69460''>after</span>
  <span m=''70480''>the</span> <span m=''70650''>second</span> <span m=''71150''>plot.</span>
  <span m=''71540''>And</span> <span m=''71840''>that''s</span> <span m=''72050''>going</span>
  <span m=''72200''>to</span> <span m=''72270''>avoid</span> <span m=''72720''>difficulties</span>
  <span m=''73370''>in</span> <span m=''73460''>the</span> <span m=''73540''>future.</span>
  <span m=''74530''>So</span> <span m=''74710''>I''m just going to</span> <span m=''74960''>save</span>
  <span m=''75400''>that.</span> </p><p><span m=''77500''>Now</span> <span m=''77640''>in</span>
  <span m=''77800''>order</span> <span m=''78100''>to</span> <span m=''78330''>improve</span>
  <span m=''79050''>the</span> <span m=''79230''>size</span> <span m=''79680''>of
  the</span> <span m=''79780''>labels</span> <span m=''80350''>and</span> <span m=''80530''>so</span>
  <span m=''80760''>forth</span> <span m=''81150''>that''s</span> <span m=''81420''>involved</span>
  <span m=''82050''>with</span> <span m=''82360''>this,</span> <span m=''83320''>there</span>
  <span m=''83550''>are</span> <span m=''83650''>a</span> <span m=''83750''>number</span>
  <span m=''83890''>of</span> <span m=''84040''>things</span> <span m=''84380''>one</span>
  <span m=''84600''>can</span> <span m=''84810''>do.</span> <span m=''85800''>And</span>
  <span m=''86980''>in</span> <span m=''87190''>general,</span> <span m=''88020''>I''m</span>
  <span m=''88210''>going</span> <span m=''88410''>to</span> <span m=''88500''>do</span>
  <span m=''88740''>this</span> <span m=''89140''>for</span> <span m=''89260''>many</span>
  <span m=''89590''>of</span> <span m=''89680''>my</span> <span m=''89870''>plots.</span>
  <span m=''91600''>And</span> <span m=''91690''>so</span> <span m=''91830''>what
  I</span> <span m=''92050''>want</span> <span m=''92230''>to</span> <span m=''92340''>do</span>
  <span m=''92720''>is</span> <span m=''92880''>I</span> <span m=''92940''>want</span>
  <span m=''93170''>to</span> <span m=''93320''>illustrate</span> <span m=''95450''>the</span>
  <span m=''95620''>fact</span> <span m=''96030''>that</span> <span m=''96200''>my</span>
  <span m=''96420''>script--</span> <span m=''97050''>which</span> <span m=''97250''>is</span>
  <span m=''97370''>called</span> <span m=''97620''>fitting.m,</span> <span m=''98820''>can</span>
  <span m=''99330''>call</span> <span m=''99910''>another</span> <span m=''100260''>script.</span>
  <span m=''101630''>And</span> <span m=''101970''>it</span> <span m=''102100''>can
  call as</span> <span m=''102590''>many</span> <span m=''102880''>scripts</span>
  <span m=''103840''>as</span> <span m=''104010''>I</span> <span m=''104140''>like.</span>
  </p><p><span m=''105240''>The</span> <span m=''105360''>script</span> <span m=''105780''>I''m</span>
  <span m=''105950''>going</span> <span m=''106180''>to</span> <span m=''106360''>call,</span>
  <span m=''107990''>I</span> <span m=''108450''>have in</span> <span m=''108580''>my</span>
  <span m=''109210''>editor</span> <span m=''109720''>already.</span> <span m=''111030''>It''s</span>
  <span m=''111280''>called</span> <span m=''112590''>plot</span> <span m=''113070''>defaults.</span>
  <span m=''114980''>Plot</span> <span m=''115310''>defaults.m.</span> <span m=''117320''>And</span>
  <span m=''118640''>here</span> <span m=''118950''>are</span> <span m=''119120''>some</span>
  <span m=''119530''>mysterious</span> <span m=''123100''>calls</span> <span m=''124700''>that</span>
  <span m=''125030''>you</span> <span m=''125250''>will</span> <span m=''125450''>find</span>
  <span m=''125830''>out</span> <span m=''126110''>only</span> <span m=''126350''>by</span>
  <span m=''126680''>reading</span> <span m=''128350''>the</span> <span m=''128490''>help</span>
  <span m=''128810''>files</span> <span m=''129729''>in</span> <span m=''129910''>general.</span>
  </p><p><span m=''131050''>By</span> <span m=''131090''>the</span> <span m=''131200''>way,</span>
  <span m=''132020''>in</span> <span m=''132210''>Octave</span> <span m=''132860''>there''s</span>
  <span m=''133100''>all</span> <span m=''133300''>kinds</span> <span m=''133640''>of</span>
  <span m=''133740''>help</span> <span m=''135530''>that</span> <span m=''135700''>you</span>
  <span m=''135850''>can</span> <span m=''136100''>find</span> <span m=''136430''>out</span>
  <span m=''136650''>by</span> <span m=''136830''>typing</span> <span m=''137270''>things</span>
  <span m=''137540''>like,</span> <span m=''137820''>help.</span> <span m=''140410''>But</span>
  <span m=''140720''>in</span> <span m=''140880''>general</span> <span m=''142210''>it''s</span>
  <span m=''142480''>more</span> <span m=''143210''>useful</span> <span m=''144760''>usually</span>
  <span m=''146250''>to</span> <span m=''146410''>use</span> <span m=''146700''>doc.</span>
  <span m=''147620''>And</span> <span m=''147830''>so</span> <span m=''148040''>we</span>
  <span m=''148190''>could</span> <span m=''148450''>do</span> <span m=''148810''>doc,</span>
  <span m=''149180''>let''s</span> <span m=''149470''>say</span> <span m=''149760''>a
  plat</span> <span m=''150920''>and</span> <span m=''151650''>it</span> <span m=''151840''>would</span>
  <span m=''152060''>then</span> <span m=''152380''>bring</span> <span m=''152750''>me</span>
  <span m=''152910''>to</span> <span m=''153030''>a</span> <span m=''153110''>place</span>
  <span m=''153800''>in</span> <span m=''154110''>the</span> <span m=''154190''>documentation,</span>
  <span m=''155590''>where</span> <span m=''155800''>the</span> <span m=''155940''>documentation</span>
  <span m=''157050''>for</span> <span m=''157310''>plot</span> <span m=''157830''>is</span>
  <span m=''158050''>described.</span> <span m=''159850''>MathLab</span> <span m=''160620''>has</span>
  <span m=''160970''>got</span> <span m=''161265''>its own</span> <span m=''161560''>help</span>
  <span m=''161890''>system</span> <span m=''164340''>and</span> <span m=''164900''>you</span>
  <span m=''165540''>can</span> <span m=''165680''>use</span> <span m=''165950''>that</span>
  <span m=''166440''>to</span> <span m=''166940''>look</span> <span m=''167150''>up</span>
  <span m=''168890''>various</span> <span m=''169360''>things.</span> <span m=''170720''>I</span>
  <span m=''170870''>could</span> <span m=''171120''>do</span> <span m=''171300''>doc</span>
  <span m=''171930''>of,</span> <span m=''173100''>let''s</span> <span m=''173590''>say,</span>
  <span m=''174040''>set,</span> <span m=''175170''>and</span> <span m=''175380''>it</span>
  <span m=''175520''>will</span> <span m=''176320''>show</span> <span m=''176700''>me</span>
  <span m=''177010''>what</span> <span m=''177260''>these</span> <span m=''177670''>set</span>
  <span m=''178100''>commands</span> <span m=''178670''>that</span> <span m=''178780''>are</span>
  <span m=''178920''>in</span> <span m=''179070''>this</span> <span m=''179650''>file</span>
  <span m=''180090''>plot</span> <span m=''180530''>defaults</span> <span m=''182600''>are</span>
  <span m=''182860''>doing.</span> </p><p><span m=''183800''>The</span> <span m=''184000''>syntax</span>
  <span m=''184620''>is</span> <span m=''184860''>complicated</span> <span m=''185660''>and</span>
  <span m=''185790''>it''s</span> <span m=''185960''>not</span> <span m=''186140''>worth</span>
  <span m=''186750''>us</span> <span m=''187690''>dwelling</span> <span m=''188090''>on</span>
  <span m=''188230''>it</span> <span m=''188460''>at the</span> <span m=''188860''>moment.</span>
  <span m=''189190''>Let</span> <span m=''189330''>me</span> <span m=''189430''>just</span>
  <span m=''189660''>explain</span> <span m=''190160''>what</span> <span m=''190470''>it''s</span>
  <span m=''190940''>going</span> <span m=''191130''>to</span> <span m=''191220''>do.</span>
  <span m=''191500''>First</span> <span m=''191830''>of all</span> <span m=''192240''>it''s</span>
  <span m=''192460''>going to</span> <span m=''192580''>set</span> <span m=''193500''>the</span>
  <span m=''194260''>default</span> <span m=''195060''>access</span> <span m=''195950''>label</span>
  <span m=''196400''>font</span> <span m=''196760''>size</span> <span m=''197120''>to</span>
  <span m=''197230''>be</span> <span m=''197460''>bigger,</span> <span m=''197940''>20.</span>
  <span m=''199520''>Second</span> <span m=''199690''>thing it''s</span> <span m=''199840''>going</span>
  <span m=''200010''>to</span> <span m=''200080''>do</span> <span m=''200290''>is</span>
  <span m=''200460''>it''s</span> <span m=''200560''>going</span> <span m=''200590''>to</span>
  <span m=''200650''>make</span> <span m=''200890''>the</span> <span m=''201180''>width</span>
  <span m=''201670''>of</span> <span m=''201850''>the</span> <span m=''201980''>lines</span>
  <span m=''202600''>of</span> <span m=''203060''>the</span> <span m=''204410''>axes</span>
  <span m=''206062''>two</span> <span m=''206520''>instead</span> <span m=''206870''>of</span>
  <span m=''206950''>one</span> <span m=''207290''>because</span> <span m=''207620''>the</span>
  <span m=''207800''>axes</span> <span m=''208720''>on</span> <span m=''208900''>these</span>
  <span m=''209130''>plots</span> <span m=''211510''>may</span> <span m=''211880''>well</span>
  <span m=''213410''>be</span> <span m=''213610''>better</span> <span m=''214020''>if</span>
  <span m=''214170''>they''re</span> <span m=''214470''>thicker.</span> <span m=''215750''>In</span>
  <span m=''215940''>general</span> <span m=''216450''>these</span> <span m=''216560''>plots</span>
  <span m=''216890''>tend</span> <span m=''217100''>to</span> <span m=''217160''>come</span>
  <span m=''217350''>up</span> <span m=''217520''>with</span> <span m=''218740''>rather</span>
  <span m=''218910''>thin</span> <span m=''219230''>lines.</span> </p><p><span m=''221750''>That''s</span>
  <span m=''222180''>useful</span> <span m=''223810''>generally,</span> <span m=''224680''>but</span>
  <span m=''225970''>the</span> <span m=''226120''>most</span> <span m=''227440''>useful</span>
  <span m=''228030''>thing</span> <span m=''229900''>to</span> <span m=''230170''>fix</span>
  <span m=''230630''>these</span> <span m=''230840''>plots,</span> <span m=''231280''>and</span>
  <span m=''231420''>to</span> <span m=''231490''>get</span> <span m=''231740''>the</span>
  <span m=''232100''>labelling</span> <span m=''232710''>to</span> <span m=''232850''>be</span>
  <span m=''233080''>a</span> <span m=''233180''>decent</span> <span m=''233690''>size</span>
  <span m=''234760''>turns</span> <span m=''235100''>out</span> <span m=''235310''>to</span>
  <span m=''235380''>be</span> <span m=''235560''>to</span> <span m=''235660''>shrink</span>
  <span m=''236120''>the</span> <span m=''236190''>size</span> <span m=''236590''>of
  the</span> <span m=''236820''>plot</span> <span m=''237360''>leave</span> <span
  m=''237810''>the</span> <span m=''238640''>font</span> <span m=''239080''>size</span>
  <span m=''239480''>the</span> <span m=''239590''>same.</span> <span m=''240550''>So</span>
  <span m=''240750''>what</span> <span m=''240980''>this</span> <span m=''241200''>command</span>
  <span m=''241610''>does</span> <span m=''241920''>is</span> <span m=''243450''>it</span>
  <span m=''243860''>basically</span> <span m=''246320''>sets</span> <span m=''246920''>the</span>
  <span m=''247030''>paper</span> <span m=''247430''>units,</span> <span m=''248280''>the</span>
  <span m=''248390''>paper</span> <span m=''248730''>orientation,</span> <span m=''249790''>and</span>
  <span m=''249900''>the</span> <span m=''249990''>paper</span> <span m=''250430''>size</span>
  <span m=''252390''>to</span> <span m=''252480''>be</span> <span m=''252650''>three</span>
  <span m=''252910''>inches</span> <span m=''253290''>by</span> <span m=''253490''>four</span>
  <span m=''253850''>inches,</span> <span m=''255890''>height</span> <span m=''256260''>versus</span>
  <span m=''256630''>width.</span> <span m=''257320''>And</span> <span m=''257640''>then</span>
  <span m=''257790''>it</span> <span m=''257910''>sets</span> <span m=''258300''>the</span>
  <span m=''258399''>paper</span> <span m=''258810''>position</span> <span m=''260220''>in</span>
  <span m=''260510''>such</span> <span m=''260829''>a</span> <span m=''260940''>way</span>
  <span m=''261290''>that</span> <span m=''262230''>we</span> <span m=''262500''>aren''t</span>
  <span m=''263590''>writing</span> <span m=''264110''>off</span> <span m=''264450''>the</span>
  <span m=''264530''>paper.</span> </p><p><span m=''267260''>As</span> <span m=''267460''>I</span>
  <span m=''267530''>said,</span> <span m=''268030''>all</span> <span m=''268290''>of
  this</span> <span m=''268630''>is</span> <span m=''269840''>subtle</span> <span
  m=''270190''>and</span> <span m=''272370''>you</span> <span m=''272550''>wouldn''t</span>
  <span m=''272950''>necessarily</span> <span m=''273560''>want</span> <span m=''273770''>to</span>
  <span m=''273880''>know</span> <span m=''274130''>all the</span> <span m=''274240''>details</span>
  <span m=''274650''>of</span> <span m=''274740''>this.</span> <span m=''275270''>I''ll</span>
  <span m=''275760''>happily</span> <span m=''275880''>make</span> <span m=''276130''>this</span>
  <span m=''276360''>file</span> <span m=''276660''>available</span> <span m=''277180''>to</span>
  <span m=''277310''>you.</span> <span m=''279430''>But</span> <span m=''279770''>all</span>
  <span m=''279890''>I</span> <span m=''279990''>have</span> <span m=''280190''>to</span>
  <span m=''280310''>do</span> <span m=''282100''>in</span> <span m=''282280''>order</span>
  <span m=''282560''>to</span> <span m=''285670''>execute</span> <span m=''286320''>those</span>
  <span m=''286590''>commands</span> <span m=''287160''>in</span> <span m=''287270''>that</span>
  <span m=''287540''>file,</span> <span m=''288180''>plot</span> <span m=''288370''>defaults,</span>
  <span m=''292710''>is</span> <span m=''293470''>write</span> <span m=''293960''>the</span>
  <span m=''294070''>command</span> <span m=''294580''>plot</span> <span m=''294900''>defaults.</span>
  <span m=''295690''>And</span> <span m=''295860''>I''m</span> <span m=''295960''>going</span>
  <span m=''296080''>to</span> <span m=''296180''>do</span> <span m=''296390''>that</span>
  <span m=''296650''>before</span> <span m=''297060''>my</span> <span m=''297290''>first</span>
  <span m=''297770''>plot.</span> <span m=''299180''>So</span> <span m=''299470''>plot</span>
  <span m=''299860''>defaults</span> <span m=''300550''>should</span> <span m=''301940''>read</span>
  <span m=''302320''>in</span> <span m=''302810''>that</span> <span m=''303820''>file</span>
  <span m=''304540''>that</span> <span m=''304820''>I</span> <span m=''305210''>was
  just</span> <span m=''305460''>looking</span> <span m=''305670''>at,</span> <span
  m=''305890''>this</span> <span m=''306130''>file,</span> <span m=''308400''>and</span>
  <span m=''309070''>execute</span> <span m=''309590''>the</span> <span m=''309670''>commands</span>
  <span m=''310180''>in</span> <span m=''310290''>it.</span> </p><p><span m=''311430''>Notice,</span>
  <span m=''311900''>by</span> <span m=''312050''>the</span> <span m=''312200''>way,</span>
  <span m=''312400''>comments,</span> <span m=''313230''>very</span> <span m=''313510''>important.</span>
  <span m=''315560''>Because</span> <span m=''316030''>these</span> <span m=''316390''>commands</span>
  <span m=''317080''>are</span> <span m=''317910''>mysterious,</span> <span m=''318840''>I</span>
  <span m=''319020''>put</span> <span m=''319360''>some</span> <span m=''320080''>commentary</span>
  <span m=''322110''>to</span> <span m=''322260''>remind</span> <span m=''322710''>you</span>
  <span m=''322830''>what</span> <span m=''323030''>they''re</span> <span m=''323210''>supposed</span>
  <span m=''323640''>to</span> <span m=''323700''>be</span> <span m=''323880''>doing</span>
  <span m=''324640''>next</span> <span m=''324930''>to</span> <span m=''324990''>them,</span>
  <span m=''325330''>and</span> <span m=''325510''>the</span> <span m=''325600''>way</span>
  <span m=''325780''>the</span> <span m=''326020''>comment</span> <span m=''326480''>is</span>
  <span m=''326600''>defined</span> <span m=''327680''>is</span> <span m=''328170''>by</span>
  <span m=''328480''>having</span> <span m=''329760''>a</span> <span m=''332100''>percent</span>
  <span m=''332630''>line</span> <span m=''333120''>at</span> <span m=''333250''>the</span>
  <span m=''333330''>beginning</span> <span m=''333780''>of</span> <span m=''333870''>the</span>
  <span m=''333980''>line,</span> <span m=''334730''>or</span> <span m=''334940''>actually</span>
  <span m=''335260''>anywhere</span> <span m=''335620''>else</span> <span m=''335850''>in
  the</span> <span m=''336040''>line</span> <span m=''337270''>for</span> <span m=''337490''>that</span>
  <span m=''337740''>matter.</span> <span m=''339040''>OK.</span> </p><p><span m=''339610''>Let''s</span>
  <span m=''339930''>save</span> <span m=''340300''>this</span> <span m=''340550''>new</span>
  <span m=''341640''>file</span> <span m=''342510''>and</span> <span m=''342970''>run</span>
  <span m=''343210''>it</span> <span m=''343360''>again.</span> <span m=''345870''>And</span>
  <span m=''346460''>lo</span> <span m=''346680''>and</span> <span m=''346770''>behold</span>
  <span m=''347380''>it''s</span> <span m=''348480''>run.</span> <span m=''350780''>Probably--</span>
  <span m=''353330''>I</span> <span m=''353510''>may</span> <span m=''353890''>not</span>
  <span m=''354230''>have</span> <span m=''356780''>several</span> <span m=''357420''>of</span>
  <span m=''357510''>the</span> <span m=''357620''>defaults</span> <span m=''358180''>right</span>
  <span m=''358520''>because</span> <span m=''358770''>I''ve</span> <span m=''358880''>been</span>
  <span m=''359040''>doing</span> <span m=''359460''>a</span> <span m=''359560''>number</span>
  <span m=''359920''>of</span> <span m=''360030''>things</span> <span m=''360540''>in</span>
  <span m=''360680''>this</span> <span m=''360940''>Octave</span> <span m=''361530''>session.</span>
  <span m=''363830''>If</span> <span m=''364040''>I</span> <span m=''364110''>get</span>
  <span m=''364400''>tired</span> <span m=''364830''>of</span> <span m=''364990''>this</span>
  <span m=''365440''>Octave</span> <span m=''365960''>session--</span> <span m=''366260''>I''ve</span>
  <span m=''366560''>run</span> <span m=''366990''>25</span> <span m=''367420''>different</span>
  <span m=''367770''>commands</span> <span m=''368300''>on</span> <span m=''368440''>it,
  it''s</span> <span m=''368770''>telling</span> <span m=''369090''>me--</span> <span
  m=''369735''>and</span> <span m=''370220''>I</span> <span m=''370430''>want</span>
  <span m=''370640''>to</span> <span m=''370720''>start</span> <span m=''371090''>a</span>
  <span m=''371130''>fresh,</span> <span m=''373895''>it''s</span> <span m=''374360''>sometimes</span>
  <span m=''374840''>helpful</span> <span m=''375260''>to</span> <span m=''376360''>start</span>
  <span m=''376880''>a</span> <span m=''376980''>new,</span> <span m=''377350''>fresh</span>
  <span m=''377820''>session.</span> </p><p><span m=''378720''>I</span> <span m=''378850''>can</span>
  <span m=''379020''>do</span> <span m=''379170''>this</span> <span m=''379420''>very</span>
  <span m=''379680''>straightforwardly,</span> <span m=''380020''>we''re</span> <span
  m=''380360''>just</span> <span m=''380790''>saying,</span> <span m=''381000''>exit,</span>
  <span m=''381960''>and</span> <span m=''382120''>then</span> <span m=''382290''>starting</span>
  <span m=''382870''>over</span> <span m=''383040''>again.</span> <span m=''383770''>That''s</span>
  <span m=''384220''>one</span> <span m=''384460''>way</span> <span m=''384620''>to</span>
  <span m=''384750''>be</span> <span m=''384850''>sure</span> <span m=''385200''>you''ve</span>
  <span m=''385500''>got</span> <span m=''386000''>a</span> <span m=''386090''>nice,</span>
  <span m=''386760''>fresh</span> <span m=''387050''>session.</span> <span m=''387980''>One</span>
  <span m=''388100''>of</span> <span m=''388160''>the</span> <span m=''388230''>nicest</span>
  <span m=''389580''>things</span> <span m=''389830''>about</span> <span m=''390560''>Octave</span>
  <span m=''390940''>is</span> <span m=''391350''>it</span> <span m=''391610''>actually</span>
  <span m=''392020''>still</span> <span m=''392350''>remembers</span> <span m=''392820''>what</span>
  <span m=''392980''>your</span> <span m=''393130''>commands</span> <span m=''393650''>were,</span>
  <span m=''394010''>even</span> <span m=''394270''>though</span> <span m=''394360''>you''ve</span>
  <span m=''394580''>got</span> <span m=''394770''>a</span> <span m=''394830''>new</span>
  <span m=''395640''>session.</span> </p><p><span m=''396080''>So</span> <span m=''397830''>here''s</span>
  <span m=''399210''>what</span> <span m=''399710''>the</span> <span m=''400210''>plot</span>
  <span m=''400500''>looks</span> <span m=''400800''>like,</span> <span m=''401300''>in</span>
  <span m=''401480''>the</span> <span m=''401580''>case</span> <span m=''401920''>when</span>
  <span m=''402100''>I</span> <span m=''402200''>run</span> <span m=''402430''>it</span>
  <span m=''402610''>with</span> <span m=''403170''>plot</span> <span m=''403600''>defaults</span>
  <span m=''405290''>and</span> <span m=''405600''>executed</span> <span m=''406440''>before</span>
  <span m=''407090''>any</span> <span m=''407380''>of other</span> <span m=''407660''>plotting</span>
  <span m=''407945''>commands.</span> <span m=''409370''>So</span> <span m=''409580''>the</span>
  <span m=''409680''>plot</span> <span m=''410000''>defaults</span> <span m=''410460''>needs</span>
  <span m=''410730''>to</span> <span m=''411200''>happen</span> <span m=''411530''>before</span>
  <span m=''412130''>anything</span> <span m=''412490''>else.</span> <span m=''413200''>And</span>
  <span m=''413440''>now</span> <span m=''413830''>what you</span> <span m=''413950''>see</span>
  <span m=''414250''>is</span> <span m=''416020''>much</span> <span m=''416370''>better,</span>
  <span m=''416850''>much</span> <span m=''417110''>bigger</span> <span m=''417720''>at</span>
  <span m=''417850''>any</span> <span m=''417970''>rate</span> <span m=''418760''>labels</span>
  <span m=''419860''>on</span> <span m=''420110''>the</span> <span m=''420230''>axes,</span>
  <span m=''421260''>et</span> <span m=''421470''>cetera,</span> <span m=''421780''>et</span>
  <span m=''421940''>cetera.</span> </p><p><span m=''422370''>Things</span> <span
  m=''422630''>aren''t</span> <span m=''422850''>perfect.</span> <span m=''423290''>There''s</span>
  <span m=''423420''>a</span> <span m=''423590''>little</span> <span m=''424180''>y</span>
  <span m=''424660''>is crashed</span> <span m=''425080''>with</span> <span m=''425230''>the</span>
  <span m=''425360''>x</span> <span m=''425710''>there,</span> <span m=''426172''>but</span>
  <span m=''426634''>anyway.</span> <span m=''427560''>You</span> <span m=''427710''>can</span>
  <span m=''427980''>tweak</span> <span m=''428110''>around</span> <span m=''428950''>with</span>
  <span m=''429080''>those</span> <span m=''429430''>to</span> <span m=''429530''>your</span>
  <span m=''429690''>heart''s</span> <span m=''430070''>content.</span> <span m=''434500''>If</span>
  <span m=''434700''>this</span> <span m=''434900''>were</span> <span m=''435150''>fine,</span>
  <span m=''436380''>my</span> <span m=''436620''>final</span> <span m=''437340''>plot,</span>
  <span m=''438240''>what</span> <span m=''438530''>I</span> <span m=''438590''>wanted</span>
  <span m=''438900''>to</span> <span m=''439030''>save,</span> <span m=''439470''>one</span>
  <span m=''440050''>of the</span> <span m=''440120''>ways</span> <span m=''440470''>I</span>
  <span m=''440550''>could</span> <span m=''440800''>save</span> <span m=''441070''>it</span>
  <span m=''441200''>would</span> <span m=''441360''>be</span> <span m=''441560''>to</span>
  <span m=''441670''>do</span> <span m=''441830''>some</span> <span m=''442110''>kind</span>
  <span m=''442370''>of</span> <span m=''442420''>screen</span> <span m=''442890''>capture</span>
  <span m=''443320''>on</span> <span m=''443510''>this</span> <span m=''443690''>window</span>
  <span m=''444140''>that I''m</span> <span m=''444420''>plotting</span> <span m=''444770''>it
  in.</span> <span m=''446110''>That</span> <span m=''446520''>would</span> <span
  m=''446740''>give</span> <span m=''446960''>me</span> <span m=''447150''>a</span>
  <span m=''447220''>rather</span> <span m=''447970''>cumbersome</span> <span m=''449370''>and</span>
  <span m=''449720''>not</span> <span m=''449890''>very</span> <span m=''450110''>pretty</span>
  <span m=''450500''>plot.</span> </p><p><span m=''451500''>There</span> <span m=''451670''>is</span>
  <span m=''451890''>another</span> <span m=''452240''>way</span> <span m=''452820''>of</span>
  <span m=''453590''>plotting,</span> <span m=''455050''>of</span> <span m=''455250''>saving</span>
  <span m=''455600''>this</span> <span m=''455760''>plot.</span> <span m=''456710''>And</span>
  <span m=''456960''>that</span> <span m=''457250''>is</span> <span m=''457480''>to</span>
  <span m=''457580''>use</span> <span m=''458120''>the</span> <span m=''459020''>command</span>
  <span m=''459460''>print.</span> <span m=''460180''>So</span> <span m=''460460''>print</span>
  <span m=''461340''>is</span> <span m=''461520''>actually</span> <span m=''462000''>printing</span>
  <span m=''462550''>out</span> <span m=''463630''>the</span> <span m=''463720''>plotting.</span>
  <span m=''465680''>One</span> <span m=''465990''>has</span> <span m=''466320''>to</span>
  <span m=''466460''>tell</span> <span m=''466840''>print</span> <span m=''467750''>what</span>
  <span m=''468050''>format</span> <span m=''468700''>one</span> <span m=''469190''>wants.</span>
  <span m=''469680''>Supposing</span> <span m=''470370''>I</span> <span m=''470450''>want</span>
  <span m=''471810''>EPS</span> <span m=''473210''>format,</span> <span m=''477910''>I</span>
  <span m=''478090''>could</span> <span m=''479070''>say</span> <span m=''479540''>D
  EPS.</span> <span m=''481260''>And</span> <span m=''481500''>suppose</span> <span
  m=''483480''>that</span> <span m=''483760''>I</span> <span m=''484550''>know</span>
  <span m=''487330''>what</span> <span m=''488580''>file</span> <span m=''489100''>I</span>
  <span m=''489190''>want</span> <span m=''489440''>to</span> <span m=''489480''>save</span>
  <span m=''489830''>it</span> <span m=''489980''>into,</span> <span m=''490950''>I</span>
  <span m=''491130''>could,</span> <span m=''491760''>for</span> <span m=''491860''>example,</span>
  <span m=''492440''>write</span> <span m=''492740''>fitted.EPS,</span> <span m=''496860''>like</span>
  <span m=''497160''>that.</span> </p><p><span m=''498660''>So</span> <span m=''498740''>this</span>
  <span m=''498980''>tells</span> <span m=''499280''>it</span> <span m=''499450''>to</span>
  <span m=''499530''>print</span> <span m=''499950''>out</span> <span m=''500660''>this</span>
  <span m=''500990''>plot</span> <span m=''501640''>into</span> <span m=''503360''>an</span>
  <span m=''503500''>EPS</span> <span m=''504090''>file,</span> <span m=''504560''>which</span>
  <span m=''504920''>is</span> <span m=''505110''>then</span> <span m=''505660''>named</span>
  <span m=''506480''>fitted.EPS.</span> <span m=''508910''>Let''s</span> <span m=''509150''>see</span>
  <span m=''509320''>what</span> <span m=''509460''>happens.</span> <span m=''512720''>Nothing</span>
  <span m=''513200''>obvious,</span> <span m=''514210''>except</span> <span m=''514700''>that</span>
  <span m=''515120''>if</span> <span m=''515320''>I</span> <span m=''515440''>now</span>
  <span m=''515710''>look</span> <span m=''516010''>in</span> <span m=''516130''>the</span>
  <span m=''516240''>directory,</span> <span m=''516870''>which</span> <span m=''517620''>in</span>
  <span m=''517890''>Octave</span> <span m=''517980''>I can</span> <span m=''518190''>do</span>
  <span m=''518429''>by typing</span> <span m=''518714''>LS,</span> <span m=''520780''>there
  is</span> <span m=''521120''>a</span> <span m=''521190''>file</span> <span m=''521720''>called</span>
  <span m=''522230''>fitted</span> <span m=''522870''>EPS.</span> <span m=''524450''>I</span>
  <span m=''524560''>don''t</span> <span m=''524960''>want</span> <span m=''525150''>to
  get</span> <span m=''525220''>out of</span> <span m=''525535''>my Octave</span>
  <span m=''525850''>session.</span> <span m=''526720''>I''m in</span> <span m=''526820''>the</span>
  <span m=''526910''>same</span> <span m=''527200''>directory</span> <span m=''527480''>here.</span>
  <span m=''528560''>Here</span> <span m=''528820''>it is,</span> <span m=''529340''>fitted</span>
  <span m=''530510''>EPS.</span> <span m=''531780''>Let''s</span> <span m=''532000''>have</span>
  <span m=''532150''>a</span> <span m=''532200''>look</span> <span m=''532480''>at</span>
  <span m=''532610''>that</span> <span m=''532860''>file</span> <span m=''534050''>using</span>
  <span m=''534420''>ghost</span> <span m=''534740''>view,</span> <span m=''535370''>and</span>
  <span m=''536030''>there</span> <span m=''536250''>it</span> <span m=''536535''>is.</span>
  </p><p><span m=''539780''>This</span> <span m=''540280''>is</span> <span m=''541950''>now</span>
  <span m=''542500''>a</span> <span m=''542910''>good</span> <span m=''543180''>quality</span>
  <span m=''545590''>file</span> <span m=''546190''>that</span> <span m=''546330''>I</span>
  <span m=''546430''>might</span> <span m=''546830''>be</span> <span m=''547840''>proud</span>
  <span m=''548660''>to</span> <span m=''548810''>show</span> <span m=''549280''>to</span>
  <span m=''549540''>my</span> <span m=''549710''>professor.</span> <span m=''553390''>It''s</span>
  <span m=''553570''>actually</span> <span m=''553910''>not</span> <span m=''554140''>in</span>
  <span m=''554290''>color.</span> <span m=''556270''>That''s</span> <span m=''556580''>because</span>
  <span m=''556990''>I</span> <span m=''557090''>use</span> <span m=''557970''>EPS.</span>
  <span m=''558740''>I</span> <span m=''558810''>think</span> <span m=''559240''>it''s</span>
  <span m=''559520''>EPS</span> <span m=''559840''>C</span> <span m=''560945''>for</span>
  <span m=''561240''>color.</span> <span m=''561690''>Let me</span> <span m=''561890''>try</span>
  <span m=''562220''>it.</span> <span m=''563390''>Let''s</span> <span m=''563740''>run</span>
  <span m=''563990''>that</span> <span m=''564160''>again</span> <span m=''565190''>and</span>
  <span m=''565780''>now</span> <span m=''566180''>look</span> <span m=''566400''>at</span>
  <span m=''566500''>it</span> <span m=''566630''>again,</span> <span m=''567150''>and</span>
  <span m=''567470''>see,</span> <span m=''568210''>yes,</span> <span m=''568670''>it''s</span>
  <span m=''568920''>color.</span> <span m=''569560''>Now</span> <span m=''569790''>it''s</span>
  <span m=''569990''>color.</span> </p><p><span m=''571820''>So</span> <span m=''572990''>that''s</span>
  <span m=''573400''>how</span> <span m=''573870''>to</span> <span m=''574440''>get</span>
  <span m=''574690''>a</span> <span m=''574750''>plot</span> <span m=''575720''>and</span>
  <span m=''575940''>to</span> <span m=''576030''>save</span> <span m=''576500''>it</span>
  <span m=''577240''>looking</span> <span m=''577990''>halfway</span> <span m=''578560''>decent.</span>
  <span m=''580780''>And</span> <span m=''581860''>that''s</span> <span m=''582110''>where</span>
  <span m=''582270''>we''ll</span> <span m=''582570''>end.</span> </p>'
type: course
uid: f1a26b7dcdab6126cdf5e30159517282

---
None