---
about_this_resource_text: "<p><strong>Description:</strong> Plot the line that results\
  \ from our fit on the data. Construct a matrix with looping, inverse, transposition\
  \ functions. Use 'hold on' &amp; 'hold off' features. Manual axis configuration.\
  \ Using semicolon to clean up command line display. Debugging errors.</p>\r\n<p><strong>Instructor:</strong>\
  \ Prof. Ian Hutchinson</p>"
course_id: 22-15-essential-numerical-methods-fall-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: NtMOab_nhs0
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  title: Video-YouTube-Stream
  type: Video
  uid: 0242632e8b5698b97dce2fb9b383fe83
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/NtMOab_nhs0/default.jpg
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: be4171a0074f66598561faf9073d3438
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id978726426
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  title: Video-iTunes U-MP4
  type: Video
  uid: d9a99bbcc184f23f4c25524b5909af95
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT22.15F14/MIT22_15F14_octavefit2_720p.mp4
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  title: Video-Internet Archive-MP4
  type: Video
  uid: 21d3d607e2b50fe13329f8a70cfffc6d
- id: 3Play-3PlayYouTubeid-MP4
  media_location: NtMOab_nhs0
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: fe12ed78ebbd213ec29227c59cdefc07
- id: NtMOab_nhs0.srt
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  technical_location: https://ocw.mit.edu/courses/nuclear-engineering/22-15-essential-numerical-methods-fall-2014/tutorial-videos/octave-matlabae-for-beginners-part-2-fitting-data-and-plotting/NtMOab_nhs0.srt
  title: 3play caption file
  type: null
  uid: 3d53c2e6e54fde72ca0473c7b20e58b1
- id: NtMOab_nhs0.pdf
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  technical_location: https://ocw.mit.edu/courses/nuclear-engineering/22-15-essential-numerical-methods-fall-2014/tutorial-videos/octave-matlabae-for-beginners-part-2-fitting-data-and-plotting/NtMOab_nhs0.pdf
  title: 3play pdf file
  type: null
  uid: 0dd6c018e71833146fff9db8a52d0f4c
- id: Caption-3Play YouTube id-SRT
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9df7e2b1d30728e8d2ebba9f405fce71
- id: Transcript-3Play YouTube id-PDF
  parent_uid: c90db86683cd18e6b6fc8e7d1d277487
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: c5a08630a4029d3b0cdd24c724695f11
inline_embed_id: "66166290octave/matlab\xAEforbeginners,part2:fittingdataandplotting68499866"
layout: video
order_index: null
parent_uid: 0e9a581264e807a6c482f19256c29502
related_resources_text: ''
short_url: octave-matlabae-for-beginners-part-2-fitting-data-and-plotting
technical_location: https://ocw.mit.edu/courses/nuclear-engineering/22-15-essential-numerical-methods-fall-2014/tutorial-videos/octave-matlabae-for-beginners-part-2-fitting-data-and-plotting
template_type: Tabbed
title: "Octave/MATLAB\xAE for Beginners, Part 2: Fitting Data and Plotting"
transcript: '<p><span m=''8730''>PROFESSOR: OK.</span> <span m=''10320''>Here we</span>
  <span m=''10580''>are.</span> <span m=''11330''>We''ve</span> <span m=''12100''>got
  our</span> <span m=''12510''>data.</span> <span m=''12800''>We''ve</span> <span
  m=''12950''>managed</span> <span m=''13280''>to</span> <span m=''13350''>plot</span>
  <span m=''13680''>it.</span> <span m=''15540''>Now</span> <span m=''15980''>let''s</span>
  <span m=''17630''>go</span> <span m=''17880''>about</span> <span m=''18730''>constructing</span>
  <span m=''20970''>a</span> <span m=''21100''>matrix</span> <span m=''21770''>which</span>
  <span m=''21960''>will</span> <span m=''22150''>enable</span> <span m=''22560''>us</span>
  <span m=''22800''>to</span> <span m=''22950''>fit</span> <span m=''24190''>a</span>
  <span m=''24310''>polynomial</span> <span m=''25400''>to</span> <span m=''25550''>this</span>
  <span m=''25810''>data.</span> <span m=''27670''>First</span> <span m=''28070''>of
  all,</span> <span m=''28470''>I</span> <span m=''28765''>need</span> <span m=''29060''>a</span>
  <span m=''29120''>matrix.</span> <span m=''30160''>Here</span> <span m=''30340''>is</span>
  <span m=''30440''>a</span> <span m=''30530''>way</span> <span m=''30880''>to</span>
  <span m=''31180''>construct</span> <span m=''31730''>a</span> <span m=''31770''>matrix.</span>
  <span m=''32759''>We</span> <span m=''32970''>put</span> <span m=''33290''>s</span>
  <span m=''33640''>equal</span> <span m=''34090''>to--</span> <span m=''36580''>The</span>
  <span m=''37710''>function</span> <span m=''38310''>zeros</span> <span m=''40220''>is</span>
  <span m=''40460''>a</span> <span m=''40540''>function</span> <span m=''41180''>which</span>
  <span m=''41760''>produces</span> <span m=''42380''>a</span> <span m=''42440''>matrix</span>
  <span m=''42990''>with</span> <span m=''43170''>all</span> <span m=''43320''>zeros</span>
  <span m=''43585''>in</span> <span m=''43850''>it,</span> <span m=''45040''>and</span>
  <span m=''45480''>I</span> <span m=''45690''>want</span> <span m=''45980''>this</span>
  <span m=''46940''>matrix</span> <span m=''47870''>to</span> <span m=''48150''>have</span>
  <span m=''48440''>dimensions</span> <span m=''49320''>endpoints</span> <span m=''50190''>by</span>
  <span m=''50440''>endpoints.</span> <span m=''52330''>So</span> <span m=''52540''>this</span>
  <span m=''52820''>command</span> <span m=''53720''>should</span> <span m=''53980''>produce</span>
  <span m=''54640''>such</span> <span m=''55060''>a</span> <span m=''55110''>matrix,</span>
  <span m=''56400''>and</span> <span m=''57760''>lo</span> <span m=''57930''>and</span>
  <span m=''58030''>behold,</span> <span m=''58370''>it</span> <span m=''58510''>does.</span>
  </p><p><span m=''59240''>Let</span> <span m=''59380''>me</span> <span m=''63960''>just</span>
  <span m=''64290''>clean</span> <span m=''64599''>up</span> <span m=''64739''>this</span>
  <span m=''65000''>display</span> <span m=''65519''>a</span> <span m=''65580''>little</span>
  <span m=''65810''>bit.</span> <span m=''67490''>At</span> <span m=''67640''>the</span>
  <span m=''67710''>moment,</span> <span m=''68120''>it''s</span> <span m=''68290''>a</span>
  <span m=''68340''>little</span> <span m=''68550''>bit</span> <span m=''68730''>annoying</span>
  <span m=''69230''>that</span> <span m=''70070''>I''m</span> <span m=''70610''>plotting</span>
  <span m=''70960''>out</span> <span m=''71100''>absolutely</span> <span m=''71650''>everything</span>
  <span m=''72390''>that</span> <span m=''72760''>I</span> <span m=''73380''>have.</span>
  <span m=''74340''>This</span> <span m=''74520''>won''t</span> <span m=''74750''>be</span>
  <span m=''74900''>too</span> <span m=''75020''>much</span> <span m=''75220''>trouble</span>
  <span m=''75550''>when</span> <span m=''75760''>I</span> <span m=''76170''>only</span>
  <span m=''76410''>have</span> <span m=''76630''>six</span> <span m=''76980''>points,</span>
  <span m=''77300''>but</span> <span m=''77430''>it</span> <span m=''77520''>might</span>
  <span m=''77810''>be</span> <span m=''77910''>in</span> <span m=''78120''>a lot</span>
  <span m=''78250''>of</span> <span m=''78570''>trouble</span> <span m=''78620''>if
  I had a</span> <span m=''78900''>lot</span> <span m=''79170''>more</span> <span
  m=''79370''>points.</span> </p><p><span m=''80820''>Here''s</span> <span m=''81100''>how</span>
  <span m=''81290''>to</span> <span m=''81450''>stop</span> <span m=''82820''>our</span>
  <span m=''83030''>MATLAB</span> <span m=''83310''>or</span> <span m=''83590''>Octave</span>
  <span m=''84170''>from</span> <span m=''84950''>printing</span> <span m=''85480''>out</span>
  <span m=''85860''>the</span> <span m=''85950''>results</span> <span m=''86560''>of
  a</span> <span m=''86730''>command.</span> <span m=''88190''>All</span> <span m=''88400''>you</span>
  <span m=''88600''>do</span> <span m=''89000''>is</span> <span m=''89220''>you</span>
  <span m=''89400''>put</span> <span m=''89930''>a</span> <span m=''90280''>semicolon</span>
  <span m=''91480''>at</span> <span m=''91620''>the</span> <span m=''91760''>end</span>
  <span m=''92000''>of</span> <span m=''92100''>the</span> <span m=''92210''>line,</span>
  <span m=''92540''>like</span> <span m=''92760''>that.</span> <span m=''93320''>Or,</span>
  <span m=''93920''>like</span> <span m=''94190''>that.</span> <span m=''95180''>If</span>
  <span m=''95370''>I</span> <span m=''95480''>make</span> <span m=''95760''>that</span>
  <span m=''96060''>change,</span> <span m=''96710''>so</span> <span m=''96770''>you
  hit</span> <span m=''97070''>and</span> <span m=''97230''>run</span> <span m=''97430''>again,</span>
  <span m=''99780''>it no</span> <span m=''100000''>longer</span> <span m=''100440''>prints</span>
  <span m=''100790''>out</span> <span m=''101030''>x</span> <span m=''101310''>and</span>
  <span m=''101450''>y.</span> <span m=''102080''>It''s</span> <span m=''102270''>still</span>
  <span m=''102530''>doing</span> <span m=''102770''>the</span> <span m=''102870''>plotting,</span>
  <span m=''106290''>and</span> <span m=''106510''>it''s</span> <span m=''107870''>printing</span>
  <span m=''108460''>out</span> <span m=''108720''>s</span> <span m=''109626''>as</span>
  <span m=''110080''>being</span> <span m=''110340''>zeros</span> <span m=''110980''>of</span>
  <span m=''111130''>endpoints</span> <span m=''111740''>endpoints.</span> </p><p><span
  m=''112630''>That''s</span> <span m=''112870''>not</span> <span m=''113090''>terribly</span>
  <span m=''113480''>interesting</span> <span m=''113960''>either,</span> <span m=''114370''>so</span>
  <span m=''114410''>I''m</span> <span m=''114600''>going</span> <span m=''115560''>to</span>
  <span m=''115810''>put</span> <span m=''116030''>a</span> <span m=''116120''>code</span>
  <span m=''116390''>on</span> <span m=''116600''>at the</span> <span m=''116770''>end</span>
  <span m=''117030''>of</span> <span m=''117130''>that</span> <span m=''117410''>line</span>
  <span m=''117880''>and</span> <span m=''118180''>prevent</span> <span m=''118480''>s</span>
  <span m=''118790''>from</span> <span m=''118970''>being</span> <span m=''119260''>printed</span>
  <span m=''119670''>out.</span> <span m=''121570''>Now,</span> <span m=''121730''>zeros</span>
  <span m=''122270''>is</span> <span m=''122420''>not</span> <span m=''122640''>what</span>
  <span m=''123040''>I want.</span> <span m=''123590''>What I</span> <span m=''123680''>want</span>
  <span m=''124130''>is</span> <span m=''124610''>a</span> <span m=''124690''>matrix</span>
  <span m=''125340''>which</span> <span m=''126380''>has</span> <span m=''126840''>the</span>
  <span m=''127030''>appropriate</span> <span m=''127650''>values</span> <span m=''130152''>to</span>
  <span m=''131009''>enable</span> <span m=''131440''>me</span> <span m=''131610''>to</span>
  <span m=''131720''>fit</span> <span m=''133550''>polynomials.</span> <span m=''134950''>And</span>
  <span m=''135120''>those</span> <span m=''135370''>values</span> <span m=''136700''>I''m</span>
  <span m=''136880''>going</span> <span m=''137070''>to</span> <span m=''137150''>generate</span>
  <span m=''137910''>by</span> <span m=''138150''>using</span> <span m=''139070''>a</span>
  <span m=''139170''>loop.</span> </p><p><span m=''140260''>In</span> <span m=''140380''>general,</span>
  <span m=''140810''>it''s</span> <span m=''140850''>not</span> <span m=''141000''>a</span>
  <span m=''141070''>great</span> <span m=''141480''>idea</span> <span m=''141950''>within</span>
  <span m=''142630''>MATLAB</span> <span m=''143105''>or</span> <span m=''143580''>Octave</span>
  <span m=''144030''>to use</span> <span m=''144480''>loops,</span> <span m=''145570''>but</span>
  <span m=''145760''>it''s</span> <span m=''145910''>perfectly</span> <span m=''146350''>possible</span>
  <span m=''146800''>to</span> <span m=''146930''>do</span> <span m=''147190''>so.</span>
  <span m=''148330''>Loops</span> <span m=''148970''>are</span> <span m=''150580''>generated</span>
  <span m=''151480''>in</span> <span m=''152140''>the</span> <span m=''152230''>following</span>
  <span m=''152700''>way.</span> <span m=''153370''>Supposing</span> <span m=''153940''>I</span>
  <span m=''154030''>choose</span> <span m=''154390''>i</span> <span m=''154700''>to</span>
  <span m=''154830''>be</span> <span m=''154980''>the</span> <span m=''155170''>index</span>
  <span m=''155750''>of</span> <span m=''155860''>my loop,</span> <span m=''157150''>I</span>
  <span m=''157290''>can</span> <span m=''157480''>let</span> <span m=''157880''>i</span>
  <span m=''158260''>range</span> <span m=''158750''>from</span> <span m=''159250''>one</span>
  <span m=''159850''>to</span> <span m=''160590''>endpoints</span> <span m=''161660''>by</span>
  <span m=''161850''>writing</span> <span m=''162570''>4i</span> <span m=''163410''>equals</span>
  <span m=''164640''>1</span> <span m=''165550''>Coulomb</span> <span m=''166190''>endpoints.</span>
  </p><p><span m=''168370''>The</span> <span m=''168750''>end</span> <span m=''169110''>of</span>
  <span m=''169250''>that</span> <span m=''172060''>for loop</span> <span m=''173240''>is</span>
  <span m=''175850''>indicated</span> <span m=''176530''>by</span> <span m=''176690''>writing</span>
  <span m=''177370''>end.</span> <span m=''178380''>Actually,</span> <span m=''178960''>in</span>
  <span m=''179110''>Octave,</span> <span m=''179420''>it''s</span> <span m=''179700''>endfor,</span>
  <span m=''180670''>but</span> <span m=''181100''>in</span> <span m=''181430''>MATLAB</span>
  <span m=''181630''>it''s</span> <span m=''181940''>end,</span> <span m=''182640''>and</span>
  <span m=''182820''>so</span> <span m=''182930''>I''m</span> <span m=''183050''>just</span>
  <span m=''183260''>going</span> <span m=''183430''>to</span> <span m=''183510''>put</span>
  <span m=''183720''>end</span> <span m=''184210''>and</span> <span m=''184515''>that</span>
  <span m=''184820''>works in</span> <span m=''185080''>Octave</span> <span m=''185340''>as</span>
  <span m=''185460''>well.</span> <span m=''186770''>So</span> <span m=''186840''>that</span>
  <span m=''187040''>would</span> <span m=''187240''>loop</span> <span m=''187650''>over</span>
  <span m=''188660''>one</span> <span m=''189260''>index,</span> <span m=''189660''>but</span>
  <span m=''190010''>actually I</span> <span m=''190290''>want</span> <span m=''190570''>two</span>
  <span m=''191540''>indices.</span> <span m=''193320''>So</span> <span m=''193580''>I''m</span>
  <span m=''193730''>going</span> <span m=''193900''>to</span> <span m=''193990''>put</span>
  <span m=''194200''>another</span> <span m=''194750''>loop</span> <span m=''195500''>inside</span>
  <span m=''196120''>of</span> <span m=''196310''>the</span> <span m=''196390''>first</span>
  <span m=''196910''>loop that</span> <span m=''197340''>I</span> <span m=''197480''>had</span>
  <span m=''199150''>and</span> <span m=''199450''>I''m</span> <span m=''199540''>going</span>
  <span m=''199740''>to</span> <span m=''199830''>make</span> <span m=''200070''>its</span>
  <span m=''200290''>index</span> <span m=''200780''>j</span> <span m=''201320''>and</span>
  <span m=''201430''>I''m</span> <span m=''201530''>going</span> <span m=''201680''>to</span>
  <span m=''201770''>let</span> <span m=''202030''>it</span> <span m=''202190''>also</span>
  <span m=''202670''>run</span> <span m=''203400''>from</span> <span m=''203870''>one</span>
  <span m=''204270''>to</span> <span m=''204390''>endpoints.</span> </p><p><span m=''206590''>And</span>
  <span m=''206950''>I</span> <span m=''207130''>need</span> <span m=''207850''>to</span>
  <span m=''208160''>end</span> <span m=''208850''>that</span> <span m=''209200''>loop,</span>
  <span m=''209590''>too.</span> <span m=''211410''>Let''s</span> <span m=''212230''>do</span>
  <span m=''212410''>my</span> <span m=''212590''>indentation</span> <span m=''214060''>neatly</span>
  <span m=''214540''>so</span> <span m=''214770''>I</span> <span m=''214860''>can</span>
  <span m=''215090''>understand</span> <span m=''215860''>this</span> <span m=''217220''>loop</span>
  <span m=''217630''>when</span> <span m=''218510''>I</span> <span m=''219750''>come</span>
  <span m=''219930''>back</span> <span m=''220140''>and</span> <span m=''220240''>read</span>
  <span m=''220550''>it</span> <span m=''220975''>later,</span> <span m=''221790''>and</span>
  <span m=''222000''>now</span> <span m=''223720''>that''s</span> <span m=''224000''>a</span>
  <span m=''224060''>loop</span> <span m=''224790''>which</span> <span m=''224990''>will</span>
  <span m=''225680''>loop</span> <span m=''225920''>over</span> <span m=''226420''>all
  of</span> <span m=''226830''>the</span> <span m=''226980''>indices</span> <span
  m=''228450''>of</span> <span m=''229440''>the</span> <span m=''229620''>matrix</span>
  <span m=''230210''>s.</span> <span m=''231270''>To</span> <span m=''231420''>refer</span>
  <span m=''231850''>to</span> <span m=''232210''>a</span> <span m=''232290''>particular</span>
  <span m=''233740''>element</span> <span m=''234250''>of</span> <span m=''234320''>the</span>
  <span m=''234390''>matrix</span> <span m=''235020''>s,</span> <span m=''235530''>I</span>
  <span m=''235690''>write</span> <span m=''236090''>s</span> <span m=''236730''>of</span>
  <span m=''237750''>i</span> <span m=''237910''>and</span> <span m=''238080''>j,</span>
  <span m=''238910''>where</span> <span m=''239140''>i</span> <span m=''239340''>and
  j</span> <span m=''239710''>are</span> <span m=''239950''>indices.</span> </p><p><span
  m=''241760''>So</span> <span m=''242340''>I''m</span> <span m=''242540''>going</span>
  <span m=''242690''>to</span> <span m=''242750''>set</span> <span m=''243050''>the</span>
  <span m=''243530''>ij-th</span> <span m=''244150''>element</span> <span m=''244500''>of</span>
  <span m=''244850''>s</span> <span m=''246020''>equal</span> <span m=''246460''>to</span>
  <span m=''246660''>an</span> <span m=''246790''>appropriate</span> <span m=''247510''>value</span>
  <span m=''249000''>to</span> <span m=''250050''>use</span> <span m=''250720''>for</span>
  <span m=''251770''>polynomial</span> <span m=''252490''>fitting,</span> <span m=''253510''>and</span>
  <span m=''253700''>that</span> <span m=''253930''>value</span> <span m=''254590''>is</span>
  <span m=''254820''>x--</span> <span m=''255722''>actually</span> <span m=''256173''>x</span>
  <span m=''258870''>I</span> <span m=''259200''>have to</span> <span m=''259279''>refer</span>
  <span m=''259700''>to</span> <span m=''259820''>by</span> <span m=''260070''>its</span>
  <span m=''260220''>index,</span> <span m=''260790''>so</span> <span m=''260810''>that''s</span>
  <span m=''261120''>xi--</span> <span m=''262830''>and</span> <span m=''263210''>I''m</span>
  <span m=''263340''>going</span> <span m=''263540''>to</span> <span m=''263690''>raise</span>
  <span m=''264070''>it</span> <span m=''264390''>to</span> <span m=''264550''>the</span>
  <span m=''264680''>power</span> <span m=''267040''>j</span> <span m=''267320''>minus</span>
  <span m=''267750''>1.</span> </p><p><span m=''268780''>So if</span> <span m=''269070''>j</span>
  <span m=''269330''>is</span> <span m=''269490''>1,</span> <span m=''269940''>which</span>
  <span m=''270130''>is</span> <span m=''270270''>the</span> <span m=''270370''>lowest</span>
  <span m=''270750''>element,</span> <span m=''271280''>this</span> <span m=''271430''>would</span>
  <span m=''271600''>raise</span> <span m=''271850''>it</span> <span m=''271990''>to</span>
  <span m=''272310''>the</span> <span m=''272430''>0</span> <span m=''273020''>power,</span>
  <span m=''273430''>which would</span> <span m=''274040''>just</span> <span m=''274310''>give</span>
  <span m=''274450''>me</span> <span m=''275180''>the</span> <span m=''275200''>result</span>
  <span m=''275750''>of</span> <span m=''275860''>being</span> <span m=''276150''>x</span>
  <span m=''276390''>to the 0,</span> <span m=''276790''>which</span> <span m=''276920''>is</span>
  <span m=''277120''>1,</span> <span m=''278420''>and</span> <span m=''279760''>for</span>
  <span m=''279910''>higher</span> <span m=''280600''>powers,</span> <span m=''282170''>it</span>
  <span m=''282340''>would</span> <span m=''284850''>go</span> <span m=''285160''>on</span>
  <span m=''285290''>appropriately.</span> <span m=''286550''>I</span> <span m=''286640''>don''t</span>
  <span m=''286800''>want</span> <span m=''286960''>to</span> <span m=''287050''>print</span>
  <span m=''287340''>this</span> <span m=''287550''>out</span> <span m=''287790''>at</span>
  <span m=''287920''>every</span> <span m=''289850''>time</span> <span m=''290120''>that</span>
  <span m=''290240''>I</span> <span m=''290330''>calculate it,</span> <span m=''290735''>so</span>
  <span m=''291140''>I''m</span> <span m=''291290''>going</span> <span m=''291520''>to</span>
  <span m=''291850''>end the line</span> <span m=''292550''>with</span> <span m=''292950''>a</span>
  <span m=''293080''>semicolon.</span> <span m=''294670''>And</span> <span m=''294780''>then</span>
  <span m=''294930''>at</span> <span m=''295030''>the</span> <span m=''295200''>end,</span>
  <span m=''295485''>perhaps</span> <span m=''295770''>I</span> <span m=''296050''>do</span>
  <span m=''296250''>want</span> <span m=''296470''>to</span> <span m=''296560''>see</span>
  <span m=''296920''>s,</span> <span m=''297690''>so</span> <span m=''297960''>let</span>
  <span m=''298130''>me</span> <span m=''298240''>just</span> <span m=''298520''>write</span>
  <span m=''298860''>s,</span> <span m=''299320''>and</span> <span m=''299680''>that
  will</span> <span m=''300020''>cause</span> <span m=''300420''>s</span> <span m=''300670''>to</span>
  <span m=''300760''>be</span> <span m=''300910''>printed</span> <span m=''301260''>out.</span>
  </p><p><span m=''302320''>So</span> <span m=''302640''>here</span> <span m=''302980''>I</span>
  <span m=''303070''>am.</span> <span m=''304480''>I</span> <span m=''304620''>run</span>
  <span m=''304840''>it</span> <span m=''305120''>again,</span> <span m=''305680''>and</span>
  <span m=''305960''>now</span> <span m=''307570''>s</span> <span m=''308680''>consists</span>
  <span m=''309350''>of</span> <span m=''309720''>this</span> <span m=''309870''>6</span>
  <span m=''310220''>by</span> <span m=''310370''>6</span> <span m=''310670''>matrix</span>
  <span m=''312350''>whose</span> <span m=''312550''>values,</span> <span m=''313050''>if</span>
  <span m=''313160''>I</span> <span m=''313210''>look</span> <span m=''313430''>at</span>
  <span m=''313520''>the</span> <span m=''313730''>top</span> <span m=''314250''>line,</span>
  <span m=''316680''>you</span> <span m=''316930''>can</span> <span m=''317120''>see</span>
  <span m=''318230''>that--</span> <span m=''319300''>Well, first</span> <span m=''319570''>of
  all,</span> <span m=''319840''>let''s</span> <span m=''320130''>look</span> <span
  m=''320260''>at</span> <span m=''320310''>the</span> <span m=''320390''>first</span>
  <span m=''321060''>column.</span> <span m=''322190''>The</span> <span m=''322270''>first</span>
  <span m=''322640''>column</span> <span m=''323130''>is</span> <span m=''323875''>all</span>
  <span m=''324140''>the</span> <span m=''324390''>values</span> <span m=''325050''>of</span>
  <span m=''325350''>j</span> <span m=''325720''>equals</span> <span m=''326110''>1,</span>
  <span m=''326590''>and</span> <span m=''326740''>they''re</span> <span m=''327110''>all</span>
  <span m=''327180''>x</span> <span m=''327520''>to</span> <span m=''327630''>the</span>
  <span m=''327750''>0.</span> <span m=''330730''>And</span> <span m=''331240''>then</span>
  <span m=''331770''>this</span> <span m=''332580''>next</span> <span m=''333020''>column</span>
  <span m=''333410''>is</span> <span m=''333610''>x</span> <span m=''333970''>to</span>
  <span m=''334110''>the</span> <span m=''334260''>power</span> <span m=''334720''>1,</span>
  <span m=''335270''>so</span> <span m=''335410''>you</span> <span m=''335630''>can</span>
  <span m=''335790''>see</span> <span m=''336180''>that</span> <span m=''336770''>it</span>
  <span m=''337250''>ranges</span> <span m=''337640''>from</span> <span m=''337820''>a</span>
  <span m=''337880''>6</span> <span m=''338590''>to</span> <span m=''339060''>1.</span>
  </p><p><span m=''340990''>The</span> <span m=''341130''>next</span> <span m=''341600''>column</span>
  <span m=''342150''>is</span> <span m=''343330''>x</span> <span m=''343650''>to</span>
  <span m=''343760''>the</span> <span m=''343850''>power</span> <span m=''344360''>2,</span>
  <span m=''345380''>and</span> <span m=''345570''>so</span> <span m=''345740''>it</span>
  <span m=''345820''>runs</span> <span m=''346110''>from</span> <span m=''346350''>a</span>
  <span m=''346580''>smaller</span> <span m=''346870''>value</span> <span m=''347160''>up</span>
  <span m=''347280''>to</span> <span m=''347390''>1.</span> <span m=''347800''>So</span>
  <span m=''348250''>of</span> <span m=''348320''>course all the</span> <span m=''348720''>values</span>
  <span m=''349690''>along</span> <span m=''350020''>the</span> <span m=''350090''>bottom</span>
  <span m=''350500''>row</span> <span m=''350930''>are</span> <span m=''352100''>1,</span>
  <span m=''353070''>and</span> <span m=''353460''>the</span> <span m=''353520''>values</span>
  <span m=''354310''>along</span> <span m=''354670''>the</span> <span m=''354830''>top</span>
  <span m=''355250''>row</span> <span m=''355820''>are</span> <span m=''356030''>1/6</span>
  <span m=''357430''>to</span> <span m=''357580''>the</span> <span m=''357720''>power</span>
  <span m=''358080''>0,</span> <span m=''358580''>1,</span> <span m=''359100''>2,</span>
  <span m=''359900''>3,</span> <span m=''360410''>and</span> <span m=''360580''>so</span>
  <span m=''360880''>forth.</span> <span m=''361420''>So that''s</span> <span m=''361760''>my</span>
  <span m=''361920''>s</span> <span m=''362500''>and</span> <span m=''362670''>that''s</span>
  <span m=''362900''>what</span> <span m=''363360''>I''m</span> <span m=''364290''>going</span>
  <span m=''364600''>to</span> <span m=''364710''>use</span> <span m=''366830''>as</span>
  <span m=''367050''>my</span> <span m=''367230''>matrix.</span> </p><p><span m=''368870''>Now,</span>
  <span m=''369290''>I</span> <span m=''369450''>can</span> <span m=''369670''>take</span>
  <span m=''369960''>the</span> <span m=''370120''>inverse</span> <span m=''371040''>of</span>
  <span m=''371330''>s</span> <span m=''372510''>by</span> <span m=''375020''>writing</span>
  <span m=''375740''>some</span> <span m=''376120''>new</span> <span m=''380180''>variable</span>
  <span m=''380710''>name.</span> <span m=''381160''>I''m</span> <span m=''381170''>going</span>
  <span m=''381330''>to</span> <span m=''381410''>call</span> <span m=''381710''>it</span>
  <span m=''381910''>sinv</span> <span m=''383540''>to</span> <span m=''383620''>remind</span>
  <span m=''384100''>me</span> <span m=''384140''>that</span> <span m=''384300''>it''s
  the</span> <span m=''384410''>inverse</span> <span m=''384880''>of</span> <span
  m=''385020''>s,</span> <span m=''385740''>and</span> <span m=''386000''>put</span>
  <span m=''386180''>it</span> <span m=''386290''>equal</span> <span m=''386660''>to</span>
  <span m=''386800''>a</span> <span m=''386880''>function</span> <span m=''387460''>which</span>
  <span m=''387680''>is</span> <span m=''387890''>called</span> <span m=''388290''>inv,</span>
  <span m=''388890''>which</span> <span m=''389300''>stands</span> <span m=''389670''>for</span>
  <span m=''389830''>inverse,</span> <span m=''391730''>called s.</span> <span m=''393620''>So</span>
  <span m=''393840''>this</span> <span m=''394300''>command</span> <span m=''395660''>finds</span>
  <span m=''396080''>me the</span> <span m=''396460''>inverse</span> <span m=''397160''>of</span>
  <span m=''397280''>the</span> <span m=''397360''>matrix</span> <span m=''398000''>s.</span>
  <span m=''398285''>And</span> <span m=''398570''>when</span> <span m=''398780''>I</span>
  <span m=''398870''>run</span> <span m=''399190''>that,</span> <span m=''400650''>I</span>
  <span m=''400720''>find</span> <span m=''401090''>that</span> <span m=''401320''>s</span>
  <span m=''401610''>inverse</span> <span m=''402160''>is</span> <span m=''402310''>given</span>
  <span m=''402660''>by</span> <span m=''403460''>this</span> <span m=''404530''>matrix</span>
  <span m=''405080''>here,</span> <span m=''405750''>whose</span> <span m=''405970''>values</span>
  <span m=''409000''>will be</span> <span m=''409110''>very</span> <span m=''409400''>hard</span>
  <span m=''409830''>to</span> <span m=''410020''>guess.</span> </p><p><span m=''412560''>Now,</span>
  <span m=''413930''>the</span> <span m=''414120''>way</span> <span m=''414330''>to</span>
  <span m=''414480''>find</span> <span m=''414980''>the</span> <span m=''415140''>coefficients</span>
  <span m=''417360''>of</span> <span m=''417710''>a</span> <span m=''420620''>polynomial</span>
  <span m=''421250''>fit</span> <span m=''421740''>to</span> <span m=''421840''>my</span>
  <span m=''422030''>original</span> <span m=''422480''>data</span> <span m=''424030''>are</span>
  <span m=''424230''>to</span> <span m=''424500''>put</span> <span m=''424770''>those</span>
  <span m=''425050''>coefficients</span> <span m=''426170''>equal</span> <span m=''426560''>to</span>
  <span m=''426720''>the</span> <span m=''426850''>matrix</span> <span m=''427480''>product</span>
  <span m=''428770''>of</span> <span m=''428980''>the</span> <span m=''429180''>inverse</span>
  <span m=''429810''>of</span> <span m=''429970''>s,</span> <span m=''430550''>which</span>
  <span m=''430620''>is</span> <span m=''430750''>sinv</span> <span m=''432190''>times</span>
  <span m=''433360''>the</span> <span m=''433530''>y</span> <span m=''433880''>values,</span>
  <span m=''435900''>which</span> <span m=''436060''>we</span> <span m=''436730''>learned</span>
  <span m=''437050''>about</span> <span m=''437300''>in</span> <span m=''437770''>the</span>
  <span m=''438100''>lecture.</span> <span m=''439190''>So</span> <span m=''439790''>that</span>
  <span m=''440010''>would</span> <span m=''440210''>give</span> <span m=''440440''>me</span>
  <span m=''440840''>the</span> <span m=''441020''>coefficients.</span> <span m=''443250''>When</span>
  <span m=''443420''>I</span> <span m=''443510''>run</span> <span m=''443750''>that,</span>
  <span m=''444390''>I</span> <span m=''444470''>find</span> <span m=''444900''>out</span>
  <span m=''445180''>what</span> <span m=''445380''>the</span> <span m=''445530''>coefficients,</span>
  <span m=''447420''>or</span> <span m=''447830''>the</span> <span m=''448120''>different</span>
  <span m=''449030''>powers,</span> <span m=''449840''>of</span> <span m=''450070''>x</span>
  <span m=''450720''>are.</span> </p><p><span m=''451550''>So</span> <span m=''451720''>in</span>
  <span m=''451820''>other</span> <span m=''451980''>words,</span> <span m=''453910''>these</span>
  <span m=''454410''>coefficients--</span> <span m=''457630''>the</span> <span m=''458110''>first</span>
  <span m=''458880''>line</span> <span m=''459190''>is</span> <span m=''459310''>the</span>
  <span m=''459440''>coefficient</span> <span m=''461040''>of</span> <span m=''461370''>the</span>
  <span m=''461450''>power</span> <span m=''462320''>x</span> <span m=''462590''>to
  the</span> <span m=''463020''>power</span> <span m=''463285''>0,</span> <span m=''463550''>the</span>
  <span m=''463640''>next</span> <span m=''463940''>one</span> <span m=''464080''>is</span>
  <span m=''464250''>x</span> <span m=''464665''>to the</span> <span m=''465080''>power</span>
  <span m=''465410''>1,</span> <span m=''465780''>and</span> <span m=''466020''>so</span>
  <span m=''466500''>on.</span> <span m=''468640''>So</span> <span m=''468850''>I''ve</span>
  <span m=''468990''>actually</span> <span m=''469420''>found</span> <span m=''469890''>the</span>
  <span m=''470000''>coefficients</span> <span m=''470800''>of</span> <span m=''471000''>the</span>
  <span m=''471100''>fit.</span> <span m=''471920''>For</span> <span m=''471980''>the</span>
  <span m=''472070''>moment,</span> <span m=''473290''>it''s</span> <span m=''473460''>not</span>
  <span m=''473690''>obvious</span> <span m=''474020''>whether</span> <span m=''475170''>I''ve</span>
  <span m=''475480''>done</span> <span m=''475790''>it</span> <span m=''476070''>correctly.</span>
  <span m=''478260''>I</span> <span m=''478410''>could</span> <span m=''478710''>certainly</span>
  <span m=''481030''>plot</span> <span m=''481410''>out the</span> <span m=''481820''>values</span>
  <span m=''483980''>of</span> <span m=''485260''>this</span> <span m=''485620''>fit</span>
  <span m=''486410''>at</span> <span m=''486640''>various</span> <span m=''487180''>places,</span>
  <span m=''487700''>and</span> <span m=''487850''>that''s</span> <span m=''488060''>what</span>
  <span m=''488250''>I''m</span> <span m=''488695''>going</span> <span m=''489140''>to
  do.</span> </p><p><span m=''489585''>I''m</span> <span m=''490030''>going</span>
  <span m=''490190''>to</span> <span m=''490260''>plot</span> <span m=''490600''>it</span>
  <span m=''490750''>actually</span> <span m=''491240''>with</span> <span m=''493220''>more</span>
  <span m=''493670''>points</span> <span m=''494070''>than</span> <span m=''494240''>I</span>
  <span m=''494320''>started</span> <span m=''494800''>with.</span> <span m=''495340''>So</span>
  <span m=''495620''>let</span> <span m=''495830''>me</span> <span m=''496640''>define</span>
  <span m=''497330''>a</span> <span m=''497470''>new</span> <span m=''500000''>parameter,</span>
  <span m=''500990''>np2.</span> <span m=''503100''>I</span> <span m=''503200''>might</span>
  <span m=''503480''>make</span> <span m=''503700''>it</span> <span m=''503770''>equal</span>
  <span m=''504000''>to,</span> <span m=''504120''>let''s</span> <span m=''504350''>say,</span>
  <span m=''504570''>40.</span> <span m=''507890''>I</span> <span m=''508490''>could</span>
  <span m=''508750''>then</span> <span m=''510010''>have</span> <span m=''510770''>a</span>
  <span m=''511710''>second</span> <span m=''512380''>variable,</span> <span m=''513620''>x2,</span>
  <span m=''515559''>equal</span> <span m=''516010''>to</span> <span m=''518159''>something</span>
  <span m=''518710''>running</span> <span m=''519132''>from</span> <span m=''519554''>1</span>
  <span m=''519976''>to</span> <span m=''520820''>np2</span> <span m=''524930''>transposed,</span>
  <span m=''526330''>divided</span> <span m=''526850''>by</span> <span m=''527410''>np2.</span>
  <span m=''528540''>So</span> <span m=''528750''>that</span> <span m=''529010''>will</span>
  <span m=''529220''>be</span> <span m=''529480''>an</span> <span m=''529680''>x</span>
  <span m=''530100''>array</span> <span m=''531120''>running</span> <span m=''531470''>from</span>
  <span m=''531810''>a</span> <span m=''531910''>small</span> <span m=''532290''>value</span>
  <span m=''532710''>to</span> <span m=''532880''>1</span> <span m=''533860''>with,</span>
  <span m=''534200''>in</span> <span m=''534280''>this</span> <span m=''534500''>case,</span>
  <span m=''534820''>40</span> <span m=''535370''>steps.</span> </p><p><span m=''537420''>I''ll</span>
  <span m=''537670''>set, for</span> <span m=''538240''>now,</span> <span m=''538640''>y2</span>
  <span m=''539760''>equal</span> <span m=''540140''>to</span> <span m=''541556''>x2.</span>
  <span m=''542580''>That''s</span> <span m=''542810''>just</span> <span m=''543120''>created</span>
  <span m=''544910''>an</span> <span m=''545170''>array</span> <span m=''547070''>that</span>
  <span m=''547720''>is</span> <span m=''547975''>of</span> <span m=''548230''>the</span>
  <span m=''548310''>same</span> <span m=''548740''>length</span> <span m=''550230''>as</span>
  <span m=''550850''>x,</span> <span m=''551690''>and</span> <span m=''551890''>is</span>
  <span m=''552020''>actually</span> <span m=''552430''>equal</span> <span m=''552810''>to</span>
  <span m=''552920''>x,</span> <span m=''553990''>but</span> <span m=''554110''>I''m</span>
  <span m=''554260''>actually</span> <span m=''554780''>going</span> <span m=''554920''>to</span>
  <span m=''555210''>end</span> <span m=''555500''>up</span> <span m=''555660''>setting</span>
  <span m=''556360''>y</span> <span m=''556710''>to</span> <span m=''557440''>be</span>
  <span m=''557590''>something</span> <span m=''558130''>else</span> <span m=''558440''>in</span>
  <span m=''558550''>a</span> <span m=''558590''>minute.</span> <span m=''562900''>And</span>
  <span m=''564720''>let</span> <span m=''564930''>me,</span> <span m=''567150''>for</span>
  <span m=''567300''>now,</span> <span m=''568140''>put</span> <span m=''568360''>fj,</span>
  <span m=''569590''>a</span> <span m=''569710''>new</span> <span m=''570710''>variable,</span>
  <span m=''571290''>equal</span> <span m=''571740''>to</span> <span m=''572075''>the</span>
  <span m=''572410''>c</span> <span m=''572850''>that I''ve</span> <span m=''573180''>just</span>
  <span m=''573530''>calculated.</span> </p><p><span m=''578930''>This</span> <span
  m=''579050''>won''t do</span> <span m=''579150''>anything</span> <span m=''579480''>interesting,</span>
  <span m=''580000''>because</span> <span m=''580260''>I''ve</span> <span m=''580460''>commented</span>
  <span m=''580980''>those</span> <span m=''581260''>out,</span> <span m=''581720''>and
  so</span> <span m=''582020''>when I</span> <span m=''582130''>run</span> <span m=''582330''>it,</span>
  <span m=''582470''>I</span> <span m=''582520''>just</span> <span m=''582760''>get</span>
  <span m=''582930''>the</span> <span m=''582980''>same</span> <span m=''583250''>result</span>
  <span m=''583650''>that</span> <span m=''583970''>I</span> <span m=''584070''>had
  before. So</span> <span m=''584570''>I</span> <span m=''584730''>haven''t</span>
  <span m=''584870''>actually</span> <span m=''585090''>done</span> <span m=''585300''>anything.</span>
  <span m=''586350''>Now</span> <span m=''586520''>I''m</span> <span m=''586640''>going</span>
  <span m=''586750''>to</span> <span m=''586790''>have</span> <span m=''587720''>another</span>
  <span m=''589380''>couple</span> <span m=''589700''>of</span> <span m=''589800''>nested</span>
  <span m=''590410''>for loops.</span> <span m=''591860''>I''m</span> <span m=''591980''>going</span>
  <span m=''592100''>to</span> <span m=''592170''>say</span> <span m=''592490''>for
  j</span> <span m=''593350''>equals</span> <span m=''595440''>1,np2,</span> <span
  m=''598930''>and</span> <span m=''599250''>for</span> <span m=''601120''>i</span>
  <span m=''601710''>equals</span> <span m=''602630''>1:np2.</span> </p><p><span m=''609450''>Let''s</span>
  <span m=''610000''>f</span> <span m=''610380''>set</span> <span m=''611060''>the</span>
  <span m=''611200''>value</span> <span m=''612240''>of</span> <span m=''612693''>fj,</span>
  <span m=''614100''>which</span> <span m=''614400''>is</span> <span m=''615220''>a</span>
  <span m=''615310''>matrix</span> <span m=''615880''>of</span> <span m=''615980''>the</span>
  <span m=''617500''>vector,</span> <span m=''618010''>strictly</span> <span m=''618310''>speaking,</span>
  <span m=''619720''>column</span> <span m=''620040''>vector</span> <span m=''620520''>of</span>
  <span m=''620600''>the</span> <span m=''620690''>same</span> <span m=''621080''>length</span>
  <span m=''621880''>as</span> <span m=''622440''>c.</span> <span m=''623870''>Let''s</span>
  <span m=''624270''>set</span> <span m=''624350''>that</span> <span m=''625040''>the</span>
  <span m=''625420''>i-th</span> <span m=''625770''>element</span> <span m=''626250''>of</span>
  <span m=''626450''>that</span> <span m=''627380''>equal</span> <span m=''627810''>to</span>
  <span m=''630960''>the</span> <span m=''631130''>x</span> <span m=''631470''>value,</span>
  <span m=''633050''>which</span> <span m=''633120''>is</span> <span m=''633450''>x2,</span>
  <span m=''633960''>because</span> <span m=''634270''>this</span> <span m=''634430''>is</span>
  <span m=''634570''>the</span> <span m=''634640''>second</span> <span m=''635270''>array</span>
  <span m=''635620''>that</span> <span m=''635820''>I''m</span> <span m=''636620''>creating,</span>
  <span m=''638460''>evaluated</span> <span m=''639850''>at</span> <span m=''640140''>parameter</span>
  <span m=''640740''>j</span> <span m=''642730''>to</span> <span m=''642940''>the</span>
  <span m=''643080''>power</span> <span m=''644980''>j</span> <span m=''645280''>minus</span>
  <span m=''645730''>1.</span> <span m=''647340''>So</span> <span m=''648050''>that''s</span>
  <span m=''648340''>actually</span> <span m=''648740''>evaluating</span> <span m=''650920''>x2</span>
  <span m=''653150''>to</span> <span m=''653620''>the</span> <span m=''653740''>appropriate</span>
  <span m=''656610''>power.</span> </p><p><span m=''656960''>So</span> <span m=''657230''>it</span>
  <span m=''657350''>shouldn''t</span> <span m=''657650''>have been j</span> <span
  m=''657850''>minus</span> <span m=''658195''>1. It</span> <span m=''658540''>should
  have</span> <span m=''659000''>been i</span> <span m=''659355''>minus</span> <span
  m=''659710''>1.</span> <span m=''660140''>So</span> <span m=''660300''>this</span>
  <span m=''660430''>is</span> <span m=''660580''>x2 j</span> <span m=''661850''>to</span>
  <span m=''662030''>the i</span> <span m=''662180''>minus</span> <span m=''662850''>1.</span>
  <span m=''666860''>Again,</span> <span m=''667180''>I</span> <span m=''667220''>don''t</span>
  <span m=''667630''>want to</span> <span m=''668120''>print all of those</span> <span
  m=''668400''>out,</span> <span m=''668740''>so</span> <span m=''668820''>I''m</span>
  <span m=''668950''>going</span> <span m=''669120''>to</span> <span m=''669220''>put</span>
  <span m=''669850''>a</span> <span m=''669940''>semicolon</span> <span m=''670270''>at</span>
  <span m=''670570''>the</span> <span m=''670880''>end.</span> <span m=''672240''>So</span>
  <span m=''673000''>that''s</span> <span m=''678060''>calculated</span> <span m=''679190''>by</span>
  <span m=''681170''>fj</span> <span m=''681480''>value,</span> <span m=''682726''>and</span>
  <span m=''683090''>now</span> <span m=''683750''>I''m</span> <span m=''683910''>going</span>
  <span m=''684140''>to</span> <span m=''684990''>put</span> <span m=''685670''>y2</span>
  <span m=''686942''>of</span> <span m=''688205''>j</span> <span m=''690220''>equal</span>
  <span m=''690640''>to--</span> <span m=''691400''>Well,</span> <span m=''691820''>what
  I</span> <span m=''692500''>basically</span> <span m=''692960''>want</span> <span
  m=''693330''>to</span> <span m=''693520''>do is</span> <span m=''693680''>form</span>
  <span m=''694300''>the</span> <span m=''694430''>dot</span> <span m=''694870''>product</span>
  <span m=''695590''>between</span> <span m=''695980''>c,</span> <span m=''698090''>the</span>
  <span m=''698260''>coefficients,</span> <span m=''699830''>and</span> <span m=''700420''>the</span>
  <span m=''700590''>value</span> <span m=''701030''>of</span> <span m=''701200''>fj</span>
  <span m=''701825''>that</span> <span m=''702140''>I''ve</span> <span m=''702250''>just</span>
  <span m=''702580''>calculated.</span> <span m=''704020''>So</span> <span m=''704260''>I</span>
  <span m=''704350''>want</span> <span m=''705110''>c1</span> <span m=''706410''>times</span>
  <span m=''706980''>fj1</span> <span m=''707620''>plus</span> <span m=''709150''>c2</span>
  <span m=''710060''>times</span> <span m=''710730''>fj2</span> <span m=''711640''>and</span>
  <span m=''711850''>so</span> <span m=''712080''>forth.</span> </p><p><span m=''712920''>One</span>
  <span m=''713070''>way of</span> <span m=''713310''>doing</span> <span m=''713650''>that--</span>
  <span m=''714376''>there are</span> <span m=''714752''>various</span> <span m=''715520''>different</span>
  <span m=''715800''>ways</span> <span m=''716010''>of doing it--</span> <span m=''716290''>is</span>
  <span m=''716570''>to</span> <span m=''716740''>take</span> <span m=''716980''>the</span>
  <span m=''717050''>transpose</span> <span m=''717430''>of</span> <span m=''717810''>c.</span>
  <span m=''718070''>C</span> <span m=''718370''>remember,</span> <span m=''719240''>is</span>
  <span m=''720010''>a</span> <span m=''720350''>column</span> <span m=''720710''>vector.</span>
  <span m=''721390''>Let''s</span> <span m=''721590''>transpose</span> <span m=''722280''>it.</span>
  <span m=''722500''>That''s</span> <span m=''722780''>going</span> <span m=''722980''>to</span>
  <span m=''723090''>give</span> <span m=''723280''>me</span> <span m=''723450''>a</span>
  <span m=''723560''>row</span> <span m=''723810''>vector.</span> <span m=''724770''>I</span>
  <span m=''724900''>can</span> <span m=''725170''>then</span> <span m=''725420''>take</span>
  <span m=''725650''>the</span> <span m=''725940''>product</span> <span m=''726270''>of</span>
  <span m=''726600''>that</span> <span m=''726810''>row</span> <span m=''727040''>vector</span>
  <span m=''727980''>with</span> <span m=''728240''>the</span> <span m=''728360''>column</span>
  <span m=''728820''>vector</span> <span m=''732540''>fj.</span> <span m=''735890''>And</span>
  <span m=''736140''>so</span> <span m=''736420''>taking</span> <span m=''737250''>to</span>
  <span m=''737810''>the</span> <span m=''738820''>matrix</span> <span m=''739400''>product</span>
  <span m=''739890''>of</span> <span m=''740000''>a</span> <span m=''740090''>column</span>
  <span m=''740470''>vector</span> <span m=''740990''>times</span> <span m=''741560''>a</span>
  <span m=''741700''>row</span> <span m=''741990''>vector</span> <span m=''742450''>is</span>
  <span m=''742640''>equivalent</span> <span m=''743140''>to</span> <span m=''743240''>taking</span>
  <span m=''743640''>the</span> <span m=''743770''>dot</span> <span m=''744060''>product</span>
  <span m=''745150''>of</span> <span m=''745410''>two</span> <span m=''746720''>vectors.</span>
  </p><p><span m=''747870''>So</span> <span m=''748090''>that</span> <span m=''748390''>has</span>
  <span m=''748860''>produced</span> <span m=''750060''>a</span> <span m=''750430''>value</span>
  <span m=''751100''>y2</span> <span m=''751810''>of</span> <span m=''751900''>j,</span>
  <span m=''752380''>which</span> <span m=''752760''>is</span> <span m=''752870''>equal</span>
  <span m=''753240''>to the</span> <span m=''753300''>sum</span> <span m=''754270''>of</span>
  <span m=''754330''>the</span> <span m=''754500''>coefficients</span> <span m=''755550''>times</span>
  <span m=''756870''>the</span> <span m=''756990''>values</span> <span m=''757480''>of</span>
  <span m=''757630''>x</span> <span m=''758200''>to</span> <span m=''759330''>the</span>
  <span m=''759410''>appropriate</span> <span m=''760010''>power.</span> <span m=''760820''>So</span>
  <span m=''760990''>that''s</span> <span m=''761900''>what</span> <span m=''762590''>I</span>
  <span m=''762700''>want</span> <span m=''763100''>to</span> <span m=''763190''>form</span>
  <span m=''764870''>in</span> <span m=''767340''>that</span> <span m=''767540''>matrix.</span>
  <span m=''768100''>Again,</span> <span m=''770510''>I''m--</span> </p><p><span m=''773310''>It</span>
  <span m=''773370''>seems</span> <span m=''773630''>as though</span> <span m=''773820''>I''ve</span>
  <span m=''773970''>made</span> <span m=''774260''>a</span> <span m=''774310''>mistake.</span>
  <span m=''785690''>And</span> <span m=''785880''>I''m</span> <span m=''786010''>not</span>
  <span m=''786190''>quite</span> <span m=''786460''>sure</span> <span m=''786720''>what</span>
  <span m=''786910''>I</span> <span m=''786970''>did</span> <span m=''787240''>wrong,</span>
  <span m=''790410''>but</span> <span m=''793670''>I</span> <span m=''793810''>need</span>
  <span m=''794040''>to</span> <span m=''794140''>find</span> <span m=''794540''>out.</span>
  <span m=''796630''>So</span> <span m=''797390''>let''s</span> <span m=''797780''>have</span>
  <span m=''798020''>a</span> <span m=''798070''>look.</span> <span m=''801500''>It''s</span>
  <span m=''801760''>saying</span> <span m=''802380''>that</span> <span m=''802560''>I</span>
  <span m=''802660''>made</span> <span m=''802950''>my</span> <span m=''803090''>mistake</span>
  <span m=''803860''>at</span> <span m=''804060''>line</span> <span m=''804610''>29</span>
  <span m=''805065''>of</span> <span m=''805520''>column 8.</span> <span m=''806770''>29</span>
  <span m=''807580''>is</span> <span m=''807820''>this,</span> <span m=''809660''>and</span>
  <span m=''809840''>it''s</span> <span m=''810080''>saying</span> <span m=''810620''>that</span>
  <span m=''810780''>I</span> <span m=''810900''>have</span> <span m=''811100''>a</span>
  <span m=''814840''>1</span> <span m=''815150''>by</span> <span m=''815310''>6,</span>
  <span m=''816080''>and</span> <span m=''816240''>op2</span> <span m=''817510''>is</span>
  <span m=''817720''>40</span> <span m=''818220''>by</span> <span m=''818490''>1.</span>
  <span m=''821290''>I</span> <span m=''821330''>don''t</span> <span m=''821540''>know</span>
  <span m=''821730''>why</span> <span m=''823300''>that</span> <span m=''823500''>is</span>
  <span m=''823700''>40</span> <span m=''823950''>by</span> <span m=''824370''>1.</span>
  <span m=''826870''>I''m</span> <span m=''827010''>a</span> <span m=''827070''>bit</span>
  <span m=''827350''>surprised</span> <span m=''828040''>by</span> <span m=''828230''>it,</span>
  <span m=''830360''>because--</span> <span m=''834668''>Ah.</span> <span m=''835120''>I</span>
  <span m=''835460''>see</span> <span m=''835720''>what</span> <span m=''835870''>I</span>
  <span m=''835940''>did</span> <span m=''836210''>wrong.</span> <span m=''837080''>This</span>
  <span m=''837290''>should</span> <span m=''837500''>have</span> <span m=''837580''>been</span>
  <span m=''837960''>endpoints.</span> </p><p><span m=''839550''>So</span> <span m=''842620''>what</span>
  <span m=''842770''>I</span> <span m=''842850''>did</span> <span m=''843160''>was,</span>
  <span m=''843960''>this</span> <span m=''844230''>inner</span> <span m=''844410''>for
  loop</span> <span m=''845040''>shouldn''t</span> <span m=''845380''>have</span>
  <span m=''845510''>been</span> <span m=''845720''>over</span> <span m=''845940''>all
  of</span> <span m=''846090''>the</span> <span m=''846700''>j</span> <span m=''846970''>values.</span>
  <span m=''847420''>The</span> <span m=''847530''>j</span> <span m=''847810''>values</span>
  <span m=''848250''>refer</span> <span m=''848650''>to</span> <span m=''848760''>the</span>
  <span m=''851050''>length</span> <span m=''851380''>of</span> <span m=''851520''>the</span>
  <span m=''851810''>new</span> <span m=''853100''>vectors</span> <span m=''853330''>that
  I</span> <span m=''853540''>produced.</span> <span m=''854660''>It</span> <span
  m=''854790''>should''ve</span> <span m=''855160''>been</span> <span m=''856410''>over</span>
  <span m=''856750''>the</span> <span m=''856810''>shorter</span> <span m=''857920''>version.</span>
  <span m=''858330''>So</span> <span m=''858560''>let''s</span> <span m=''858870''>see.</span>
  <span m=''859360''>Let''s</span> <span m=''859670''>save</span> <span m=''859830''>that</span>
  <span m=''860240''>and</span> <span m=''860505''>hope that''s</span> <span m=''860770''>corrected</span>
  <span m=''861190''>my</span> <span m=''861490''>error.</span> <span m=''862410''>Yes.</span>
  <span m=''862770''>Lo</span> <span m=''863010''>and behold,</span> <span m=''863330''>it</span>
  <span m=''863440''>has.</span> <span m=''864250''>I</span> <span m=''864630''>haven''t</span>
  <span m=''865010''>actually</span> <span m=''865370''>done</span> <span m=''865560''>anything</span>
  <span m=''865880''>to</span> <span m=''865970''>show</span> <span m=''866260''>what</span>
  <span m=''866430''>the</span> <span m=''866530''>result</span> <span m=''866980''>is,</span>
  <span m=''867270''>but at</span> <span m=''867580''>least</span> <span m=''868770''>now</span>
  <span m=''869660''>I''ve</span> <span m=''869990''>got</span> <span m=''870830''>the</span>
  <span m=''870950''>result.</span> </p><p><span m=''873030''>Now</span> <span m=''873430''>what
  I</span> <span m=''873480''>want</span> <span m=''873710''>to</span> <span m=''873810''>do</span>
  <span m=''874080''>is,</span> <span m=''874260''>I</span> <span m=''874330''>want</span>
  <span m=''874560''>to</span> <span m=''875075''>plot</span> <span m=''876940''>these</span>
  <span m=''877260''>two</span> <span m=''877460''>new</span> <span m=''877680''>matrices,</span>
  <span m=''880330''>x2</span> <span m=''880880''>and</span> <span m=''881060''>y2,</span>
  <span m=''886730''>and</span> <span m=''887790''>actually</span> <span m=''888170''>I''d</span>
  <span m=''888300''>like</span> <span m=''888550''>to</span> <span m=''890080''>overplot</span>
  <span m=''890445''>them</span> <span m=''890810''>on</span> <span m=''891280''>my</span>
  <span m=''891696''>old plot.</span> <span m=''892530''>If</span> <span m=''892750''>I</span>
  <span m=''892830''>just</span> <span m=''893040''>say</span> <span m=''893380''>plot</span>
  <span m=''893730''>like</span> <span m=''893950''>this,</span> <span m=''895360''>save</span>
  <span m=''895660''>this</span> <span m=''895850''>and</span> <span m=''895930''>plot
  it</span> <span m=''896250''>again,</span> <span m=''897935''>that</span> <span
  m=''898340''>isn''t</span> <span m=''898380''>what</span> <span m=''898530''>happens.</span>
  <span m=''899160''>Instead,</span> <span m=''899680''>what</span> <span m=''899830''>happens</span>
  <span m=''900320''>is</span> <span m=''900690''>just</span> <span m=''901030''>the</span>
  <span m=''901150''>curve</span> <span m=''901680''>that</span> <span m=''901840''>I''ve</span>
  <span m=''902170''>just</span> <span m=''902490''>calculated</span> <span m=''904080''>is</span>
  <span m=''904310''>plotted,</span> <span m=''905110''>and</span> <span m=''905230''>my</span>
  <span m=''905420''>previous</span> <span m=''906880''>plot</span> <span m=''908390''>is</span>
  <span m=''908560''>wiped</span> <span m=''909010''>out.</span> </p><p><span m=''912370''>What</span>
  <span m=''912570''>I</span> <span m=''912640''>can</span> <span m=''912870''>do</span>
  <span m=''913200''>to</span> <span m=''913320''>prevent</span> <span m=''913740''>that</span>
  <span m=''913950''>happening</span> <span m=''914480''>is</span> <span m=''914670''>to</span>
  <span m=''914780''>say,</span> <span m=''915690''>hold</span> <span m=''916590''>on.</span>
  <span m=''919210''>Only</span> <span m=''920200''>MATLAB</span> <span m=''921100''>slash</span>
  <span m=''921720''>Octave</span> <span m=''924190''>would</span> <span m=''924920''>have</span>
  <span m=''925240''>something</span> <span m=''925720''>like</span> <span m=''926710''>hold</span>
  <span m=''927230''>on</span> <span m=''927570''>as</span> <span m=''927850''>a</span>
  <span m=''927940''>command.</span> <span m=''928950''>But</span> <span m=''929200''>anyway,</span>
  <span m=''929872''>hold</span> <span m=''930210''>on</span> <span m=''930840''>basically</span>
  <span m=''931370''>says,</span> <span m=''932050''>retain</span> <span m=''932440''>the</span>
  <span m=''932530''>data</span> <span m=''932980''>that</span> <span m=''933220''>you''ve</span>
  <span m=''933640''>already</span> <span m=''934000''>got</span> <span m=''934340''>in</span>
  <span m=''934470''>this</span> <span m=''934680''>plot</span> <span m=''935390''>and</span>
  <span m=''935640''>add</span> <span m=''935990''>some</span> <span m=''936050''>more</span>
  <span m=''936310''>data on.</span> <span m=''936620''>So</span> <span m=''937130''>let''s</span>
  <span m=''937430''>try</span> <span m=''937670''>this.</span> </p><p><span m=''939680''>So</span>
  <span m=''939900''>now</span> <span m=''940170''>what</span> <span m=''940410''>we</span>
  <span m=''940530''>see</span> <span m=''940890''>is</span> <span m=''941370''>the</span>
  <span m=''941810''>data</span> <span m=''942100''>that</span> <span m=''942240''>I''ve</span>
  <span m=''943110''>plotted</span> <span m=''943380''>out</span> <span m=''943600''>in</span>
  <span m=''943660''>my</span> <span m=''943830''>first</span> <span m=''944330''>plot,</span>
  <span m=''945070''>which</span> <span m=''945280''>was</span> <span m=''945790''>up</span>
  <span m=''946040''>here,</span> <span m=''947380''>is</span> <span m=''947590''>held</span>
  <span m=''948670''>and</span> <span m=''949200''>the</span> <span m=''949320''>second</span>
  <span m=''949770''>plot</span> <span m=''950100''>is</span> <span m=''950290''>plotted.</span>
  <span m=''951790''>Notice</span> <span m=''952860''>that</span> <span m=''953700''>this</span>
  <span m=''954070''>fit</span> <span m=''954310''>does</span> <span m=''954580''>indeed</span>
  <span m=''955110''>go</span> <span m=''955370''>through</span> <span m=''955730''>the</span>
  <span m=''955850''>six</span> <span m=''956190''>points</span> <span m=''956910''>that</span>
  <span m=''957040''>I</span> <span m=''957340''>originally</span> <span m=''959570''>retained,</span>
  <span m=''961970''>and</span> <span m=''966270''>yet,</span> <span m=''967080''>that</span>
  <span m=''967370''>line</span> <span m=''967720''>actually</span> <span m=''967960''>does
  some</span> <span m=''968430''>funny</span> <span m=''968790''>things.</span> <span
  m=''969070''>Particularly</span> <span m=''969790''>at</span> <span m=''969940''>the</span>
  <span m=''970120''>end</span> <span m=''970410''>here,</span> <span m=''971340''>it</span>
  <span m=''971490''>goes</span> <span m=''971750''>negative.</span> </p><p><span
  m=''973780''>There''s</span> <span m=''973980''>another</span> <span m=''974390''>trick</span>
  <span m=''974920''>that</span> <span m=''976110''>one</span> <span m=''976330''>can</span>
  <span m=''976480''>do</span> <span m=''976670''>in</span> <span m=''976820''>plotting,</span>
  <span m=''977670''>and</span> <span m=''977890''>one</span> <span m=''978050''>can</span>
  <span m=''978190''>say</span> <span m=''978520''>things</span> <span m=''978920''>like</span>
  <span m=''980450''>axis</span> <span m=''981590''>manual,</span> <span m=''983988''>and</span>
  <span m=''984390''>I</span> <span m=''984530''>think</span> <span m=''984920''>that,</span>
  <span m=''985300''>if</span> <span m=''985480''>I''m</span> <span m=''985610''>lucky,</span>
  <span m=''985990''>that</span> <span m=''986200''>will</span> <span m=''987970''>fix</span>
  <span m=''988470''>this</span> <span m=''988700''>plot.</span> <span m=''989120''>No,</span>
  <span m=''989420''>it</span> <span m=''989720''>won''t.</span> <span m=''990800''>Never
  mind.</span> <span m=''992880''>Anyway,</span> <span m=''993150''>there''s</span>
  <span m=''993535''>a</span> <span m=''993920''>way--</span> <span m=''994690''>and</span>
  <span m=''995280''>I''ll</span> <span m=''995460''>show it</span> <span m=''995860''>later--</span>
  <span m=''996780''>to</span> <span m=''996910''>prevent</span> <span m=''997280''>the</span>
  <span m=''997360''>plot</span> <span m=''997700''>rescaling</span> <span m=''999490''>and</span>
  <span m=''1000740''>the</span> <span m=''1000950''>required</span> <span m=''1001240''>command</span>
  <span m=''1001530''>is</span> <span m=''1001720''>axis</span> <span m=''1002220''>manual.</span>
  </p><p><span m=''1002760''>But</span> <span m=''1003630''>at</span> <span m=''1003800''>the</span>
  <span m=''1003880''>moment,</span> <span m=''1006400''>I</span> <span m=''1006590''>think,</span>
  <span m=''1006820''>before</span> <span m=''1007180''>I</span> <span m=''1008750''>do</span>
  <span m=''1008900''>it,</span> <span m=''1009010''>I''ve</span> <span m=''1009150''>got</span>
  <span m=''1009320''>to</span> <span m=''1009390''>say</span> <span m=''1009640''>hold</span>
  <span m=''1011050''>off.</span> <span m=''1012960''>And</span> <span m=''1013080''>then</span>
  <span m=''1013210''>if</span> <span m=''1013460''>I</span> <span m=''1013670''>re-run</span>
  <span m=''1013890''>it,</span> <span m=''1015570''>I</span> <span m=''1015750''>will</span>
  <span m=''1015940''>find</span> <span m=''1016675''>that</span> <span m=''1016970''>lo
  and</span> <span m=''1017230''>behold,</span> <span m=''1017740''>I''ve</span> <span
  m=''1017990''>got</span> <span m=''1018250''>a</span> <span m=''1018500''>plot</span>
  <span m=''1019190''>of</span> <span m=''1019750''>the</span> <span m=''1019870''>six</span>
  <span m=''1020240''>points</span> <span m=''1021250''>and</span> <span m=''1021480''>the</span>
  <span m=''1021580''>line</span> <span m=''1021940''>that</span> <span m=''1022080''>I</span>
  <span m=''1022190''>fitted,</span> <span m=''1022710''>which</span> <span m=''1022950''>is</span>
  <span m=''1023080''>a</span> <span m=''1023130''>polynomial</span> <span m=''1023535''>fitted</span>
  <span m=''1023940''>to</span> <span m=''1024410''>those</span> <span m=''1024660''>lines.</span>
  <span m=''1025839''>And</span> <span m=''1026540''>lo</span> <span m=''1026740''>and</span>
  <span m=''1026970''>behold,</span> <span m=''1027920''>it</span> <span m=''1028210''>fits.</span>
  </p>'
type: course
uid: c90db86683cd18e6b6fc8e7d1d277487

---
None