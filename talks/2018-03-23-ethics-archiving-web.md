# TALK TALK TALK TALK TALK 

# slide 
This has been such a great conference and it's great to hear so many different angles from which we present the same subject. I'll be speaking somewhat in the hypothetical here, in that these ideas or concepts don't exist presently for web archives in particular, but I hope my research in other digital media preservation practices can be potentially be absorbed into the web content domain.

# slide 
I think these ideas could be applied to present systems if any organizations or granting agencies are listening out there and are interesting in providing funding! Otherwise progress simply won't happen.

# slide 
OK so I know we can do web archiving in several ways: 
# slide 
harvesting: crawling sites and saving them
# slide 
database preservation: retrieving and storing the database of database-driven websites. I would put social media cataloging from proprietary systems in this category.
# slide 
transactional archiving: storing during the act of transferring data 

# slide 
And we generally think of the first of these when talking about web archiving, the creation of WARC files. So I'll be speaking of web archiving in this context too, although the other two are certainly worth thinking about for this conference and for this panel and for this talk. 

# slide 
My surrounding panelists have or will be speaking on the many crucial issues outside of this "act of saving" -- of security compromises before collection and after storage, or during access and presentation, so I want to talk particularly about what can be done during this most active time in the preservation life cycle, the ingest stage. The stage in which the archivist has the most active control over the material, presumably. 

# slide 
And through this, I want to talk about file integrity! Which is what I understand brought me to be on this panel in the first place? Integrity can mean so many things, especially at such an interdisciplinary conference as this one. But I'm speaking of file integrity and at the juncture of file fixity

# slide 
We don't talk about fixity via algorithmic hashing enough in the context of preservation, in a meaningful way. There's a lot "oh I should be doing that" or "I do that" but without being integrated holistically  into preservation systems in a way that brings value or a clear understand as to the "why". I think this is partly a lack of education in this sphere for the people making decisions and designing business rules around proposed systems more than the processing concerns.

# slide 
I want to think about archiving web-based materials in the way I think many institutions will be and have been applying such practices to their long-term preservation, using the concept of ingest and processing derived from the OAIS framework. If you don't know what that is, don't work about it, it's a conceptual framework that recommends how data should move through long-term preservation systems. 

# slide 
But specifically, thinking about this point after immediately after collection and curation, about what kind of microservices can be applied at that pre-ingest juncture to verify the many different formats found within the WARC package, and what kind of verifications can happen. This allows for the verification of the encompassed physical assets as well as a documented process of how this information was gathered from a technical standpoint and a human-readable standpoint. 

# slide 
I want to use a simple example to give some context and framework from which I am coming from, and from which largely much of this material will be collected when done in a formal way by archives, and that is to use this analogy of how complex media is handled digitally and traditionally has been established as a method of preservation. I've worked in close detail, in media analysis and working with digitized analog video tapes, so this is the example. [ analogy about tapes here ] 

# slide 
The object and content fundamentally changes when it goes through this transformation from analog magnetic tape in a plastic casing to a new digital form where it can live in more stable, long-term and accessible conditions, as we run out of VHS players and the consumer non-archival magnetic tape begins to degrade. 

# slide 
At this point, some decisions must be made, both personal and technical in nature. There's a personal touch in setting the saturation and hue, for example, and there's the technical issue of the machine and capture devices themselves, resulting in a combination of unique potential errors, physical and user-based, for this one stream that passes through.

# slide
The tape is more than this one content stream, but when the tape is digitized, it is captured forever, and that stream is what goes into cultural memory long-term, into the archives. Practitioners deny the phrase "has been archived", arguing (rightfully) that archiving is a continual process, but this is a major archival event and the stream captured cannot be undone, only altered later, digitally, maybe, unlikely, and also disingenuously, inaccurately, without authentication.

# slide 
So I agree that this is analogous to the process of web archiving as we've come to understand it based on historical preservation practices, in which a sample is created and stored, but there are person-based and technology-based factors in place that forever change the stream. Or in this case, the "capture."

# slide 
For video files, which are in essence streams of data, they can have fixity applied to every frame in the video, or even every slice of every frame in the video. This sort of obsessive granularity can be somewhat CPU-processing intensive, but people also waste a ton of energy mining bitcoin, so maybe that's not a realistic dissenting factor. 

# slide 
But for very important digital video files, this is what can be done to protect as much of the content as possible, and be able to determine exactly where a problem exists within a file. Performing this kind of fixity not just on the entire file, but sections of the file itself. 

# slide 
Web archives are composed of many complex files. Can we make sure all of the files within the larger WARC wrapper have proper identification during this point of archival ingest?  🤔

# slide 
I want us to look at the WARC specification. I'm constantly lamenting that the specification we rely on for generating web archives, the WARC format, remains closed as it standardized through ISO, and we only have an assumed close equivalent draft available publicly (of course, of which I'm grateful for). Thanks IIPC. 

# slide 
Can we know if the specification is being utilized in the applications that archivists depend on to its full capacity unless we are ALL able to fully analyze it?

# slide 
I digress and want to highlight this part of the spec, in the section dedicated to the goals of a WARC file: Support for data compression and maintenance of data record integrity.

# slide 
One of the warc records within warc files is the "conversion" record, which is used to determine if the content has been transformed or changed in any way. This is primarily used for seeing if there is a difference in the webpage between captures -- has it changed since the last capture? If not, note as such. If so, note changes. These were primarily thought about in the context of how to save space, transfer bandwidth, and time, but not necessarily in the context of malicious intervention.

# slide 
So there is inherently a lack of space for holding fixity in place within the structure of the format, but there is space to add metadata. A system generating WARC files could, if desired, perform this kind of additional security on each of the assets coming into the file and saving that information within the file or outside of the file, or both. 

# slide 
This would allow for an extra check on the contents of a web archive as it is being ingested into a system, and can be used for verification and validation in the future, when and if contested. 

# slide 
Of course this doesn't mitigate falsification through an update in the checksum storage point used for validation, but it's significantly greater, particularly in the case of the aforementioned sort of injection attack. These practices are already applied to other forms of complex media, so why not content found in web archives?
 
# slide 
So again I urge more institutions to get involved with and financially back this effort, investigate and take seriously the aforementioned research from Dr. Lerner, and fund more research & development in these issues. 

# END TALK TALK TALK TALK TALK 



- Teaching & Learning https://web.archive.org/web/20091026013933/http://geocities.com/toe6000/index.html
- IT-Network https://web.archive.org/web/20091025075831/http://geocities.com/arthit_ake/lan_network.html
Blue white tigers - https://web.archive.org/web/20090727122534/http://de.geocities.com/netmarket20022002/networkmarketing_award_s_verga/networkmarketing_award_s_verga.html
- Psychic index https://web.archive.org/web/20090831180102/http://geocities.com/heartland/hollow/8743/Psychic_index.html
- Satan?! https://web.archive.org/web/20090807101036/http://geocities.com/cow_harvest/34.html
- Class of 1981 https://web.archive.org/web/20090816004643/http://www.geocities.com:80/othelum/classof1981.html
- telenovella https://web.archive.org/web/20090804160106/http://geocities.com/TelevisionCity/2725/Zingara/zingaraes.html
- sonic page https://web.archive.org/web/20091023063123/http://geocities.com/SiliconValley/Network/9070/index2.html
- his harvest moon https://web.archive.org/web/20091026082556/http://geocities.com/his_harvest_moon/index.html
Sports and Entertainment - https://web.archive.org/web/20091026014240/http://geocities.com/services1900/Sports_Entertainment_Line/index.htm
- Gruppenbild https://web.archive.org/web/20090727085957/http://de.geocities.com/markusrosenkranz/html/fotogalerie.html
- Welcome to the Temptations Information Page https://web.archive.org/web/20091022034056/http://geocities.com/nataliavinaixa/home.html
- TV Archive https://web.archive.org/web/20091027144635/http://geocities.com/crystal30145/rulesdisclaimer.html
- MIDI Archive https://web.archive.org/web/20091026235523/http://www.geocities.com/aequum/music.html
- Wombat https://web.archive.org/web/20091026133830/http://geocities.com/Athens/Styx/8956/archive/
- About Us https://web.archive.org/web/20091027122820/http://geocities.com/Heartland/Oaks/6473/AboutUs.html
Goals for Increased Personal Participation - https://web.archive.org/web/20091028061011/http://www.geocities.com/hifc/archive/goalsfor.html
- Chinese characters https://web.archive.org/web/20090831085352/http://geocities.com/homesafety_cfsc/hsfs1.htm
- Get a Star on Internet Safety https://web.archive.org/web/20091023102722/http://geocities.com/CollegePark/Square/7548/ncca/safety.htm
- Hot Links https://web.archive.org/web/20091023175837/http://geocities.com/circletracksafety/links.html
- SafetyMe https://web.archive.org/web/20091022083000/http://geocities.com/mansafe03/course.html
- Sarahs Site https://web.archive.org/web/20091024095201/http://geocities.com/safetypins018/Princess_Sarahs_Site.html
- Top o da world entertainment https://web.archive.org/web/20091027022949/http://geocities.com/kingdur2000/
- My cup overflowed https://web.archive.org/web/20090829040022/http://geocities.com/phil_addoms/index2.html
- lodge of fidelity https://web.archive.org/web/20090724061849/http://ca.geocities.com/fidelity231@rogers.com/Hundred_history.htm
- Hi-tech https://web.archive.org/web/20091026223318/http://geocities.com/promiseoflove/page41.html
- NSYNC animations https://web.archive.org/web/20091025091304/http://geocities.com/lilnsyncgirlie/animations.html
- Velcome!! https://web.archive.org/web/20090806154444/http://geocities.com/breeze59/hallomain.html
- Zac's World https://web.archive.org/web/20090830231952/http://geocities.com/Hollywood/Heights/8580/Zac.index.html
- Troops 1512 https://web.archive.org/web/20091025080211/http://geocities.com/gstroop1512/troopmembers.html



