<html>
<head></head>
<body>
Title: Development Status (2010-02-15)<br />
Primary contributor: hierophant<br />
For attribution and license, please consult the following URL: <a href="http://opensiddur.org/?p=463">http://opensiddur.org/?p=463</a>
<p />
<hr />

<strong>Open Siddur Project Development Status as of   February 2010/Adar 5770</strong>

Friends,

The communal project  of Jewish spirituality can only be improved through cooperation and  collaboration. The creative work used in our traditional liturgies is  the common  cultural heritage of the Jewish people. Most of this work resides in the  public domain. The Open Siddur is your Siddur. Join the Open Siddur  Project  today and begin crafting and sharing the siddur you've always wanted.

This  development status update chronicles progress on the Open Siddur made  since our last update 11/11/2009. If you’d like to get news of Open  Siddur Project development as it occurs, make sure to follow <a href="http://twitter.com/opensiddur" target="_blank" rel="noopener noreferrer">@opensiddur</a> at Twitter, or join  the <a href="http://groups.google.com/group/opensiddur-announce" target="_blank" rel="noopener noreferrer">opensiddur-announce</a> email list.

<em>Contributions </em>(Aharon, Anonymous, Gabriel,  Efraim, Eve, Daniel, John)

<div style="padding-left: 30px;">Following  the contribution of Reb Zalman's <a href="../../../2009/10/reb-zalmans-open-siddur-tehillat-hashem/">Siddur  Tehillat HaShem</a>, R. Daniel Brenner, executive director of  Birthright Israel Next, contributed a <a href="../../../2009/12/kaddish-by-rabbi-daniel-brenner/">Kaddish  prayer</a> that he composed in English. Check it out <a href="../../../2009/12/kaddish-by-rabbi-daniel-brenner/">here</a>.  Feel free to adapt and modify these works for yourself. They are  distributed with a <a href="http://www.creativecommons.org/licenses/by-sa/3.0" target="_blank" rel="noopener noreferrer">Creative  Commons 3.0 Share Alike By Attribution</a> license. (All derivative  works must show attribution to the original authors and must also be  distributed under the CC-BY-SA 3.0 license.)

John B. Hare of the <a href="http://www.sacred-texts.com/" target="_blank" rel="noopener noreferrer">Internet Sacred Text Archive</a> contributed the scans and auto-transcribed text of the 1917 JPS English  Translation of the TaNaKh. We are currently helping John release the  first ever free licensed digital text of the 1917 JPS TaNaKh translation  and have proofread the Book of Neḥemia and nearly 70% of Psalms. Please  help us complete this task by <a href="https://opensiddur.org/translations/%d7%aa%d7%a0%d7%b4%d7%9a-the-holy-scriptures-a-new-translation-jps-1917/" target="_blank" rel="noopener noreferrer">proofreading  a few pages</a> -- it's a relatively easy way to begin working on the  Open Siddur Project.

John Hare also scanned and transcribed a  1915 edition of the <a href="http://www.sacred-texts.com/jud/spb/index.htm" target="_blank" rel="noopener noreferrer">Singer Siddur</a>,  an English translation based on Seligman Baer's Seder Avodat Yisrael.  Thank you, John!

<a href="https://opensiddur.org/tools/transcribe/" target="_blank" rel="noopener noreferrer">Transcription of  Seder Avodat Yisrael </a>has picked up since our last update. We have  transcribed 33 pages of the liturgy from Baer's critical edition. Every  line of text transcribed is digitally liberated with the <a href="http://www.creativecommons.org/publicdomain/zero/1.0" target="_blank" rel="noopener noreferrer">Creative Commons Zero</a> (CC0) license for  free use in future siddurim. If you haven’t yet, register on the wiki  and start transcribing today. This is a great way to become fluent  typing Hebrew with <em>nikkudot</em> (vowels) -- a real skill!

Gabriel   Wasserman contributed his transcription of many sections of the Seder  Avodat Yisrael that he had incorporated into his Maḥzor for Shabbat  Ḥanukkah. Thank you, Gabriel!

Efraim Feinstein acquired and  scanned a work of the Siddur Torah Ohr  (Nusaḥ HaAri/Lubavitch) an important siddur based on the text edited by  R. Shneur Zalman of Liadi. A partial digital transcription of the siddur  is already available on <a href="http://he.wikisource.org/wiki/%D7%A1%D7%99%D7%93%D7%95%D7%A8_%D7%AA%D7%95%D7%A8%D7%94_%D7%90%D7%95%D7%A8" target="_blank" rel="noopener noreferrer">Wikisource</a> and this scan will help us complete  that transcription and provide a source for proofreading it. Thanks  Efraim!

An anonymous contributor provided a text of the  Spanish-Portuguese  Nusaḥ. The text is currently formatted in the proprietary format of  DavkaWriter Platinum. Please let us know if you have a copy of this  software and if you can help us convert this document to an open  standard Unicode format.

If you have digitized any text of the  siddur or prepared a siddur that you'd like to share, please consider  contributing your work to the Open Siddur Project.

</div>

<em>Software  Development </em>(Efraim, Ze'ev, Ilan, Raphael)

<div style="padding-left: 30px;">We have now a functioning demonstration of  how we can display text encoded in JLPTEI XML on a webpage. Click <a href="http://app.opensiddur.org" target="_blank" rel="noopener noreferrer">here</a> for examples of  working Open Siddur technology.

An update to our demo is  forthcoming this week. License statements and contributor credits lists  are now being generated by the code, and both are mostly functional.   These should be incorporated in demo release 0.3.1 Generating a  bibliography correctly is a bit harder, and may have to wait for 0.4. We  are in the process of moving our Tanach to get its data directly from  the Westminster Leningrad Codex.  The process is almost complete, and  the new code will likely be in demo release 0.4.

Since our last  update, we've passed a few milestones, especially in our work on data  transforms. The major improvements we've made are the following:
<ul>
    <li>JLPTEI's  <a href="http://web.archive.org/web/20100507124255/http://wiki.jewishliturgy.org:80/Conditionals" target="_blank" rel="noopener noreferrer">conditional  inclusion feature</a></li>
    <li>Parallel text alignment for <a href="http://web.archive.org/web/20101229095129/http://wiki.jewishliturgy.org:80/Translations" target="_blank" rel="noopener noreferrer">translations</a></li>
    <li>Generic  standoff <a href="https://github.com/opensiddur/opensiddur-client/wiki" target="_blank" rel="noopener noreferrer">annotations</a>,  the basis for instructions, commentary, linkages, historical notation</li>
</ul>
With  a lot of help from Ze'ev Clementson, cross platform build procedures  and instructions were tested; many build errors and documentation errors  were <a href="http://web.archive.org/web/20100507124255/http://wiki.jewishliturgy.org:80/Conditionals" target="_blank" rel="noopener noreferrer">conditional  inclusion feature</a>.

Ze'ev  has been checking in code to converting the STML formatted text of the  Singer Siddur provided by John B. Hare (see above) into a more easily  parsed XML representation. He's now working on encoding this into JLPTEI  XML formatted text for integration into the Open Siddur's database.  Ze'ev has also committed code for converting Strong's Hebrew Dictionary  into JLPTEI XML for integration into the Open Siddur. (It's currently  formatted in OSIS.) Ze'ev is currently working on the conversion of  David Troidl's digitization of the Strong's Biblical Hebrew dictionary  from OSIS to JLPTEI for integration into the Open Siddur.

Ilan Cohen committed an outline of the jQuery port of the transcription  interface. Thanks Ilan!

Some of the work we're doing requires  expertise in the rules of Hebrew grammar and its effect on vowel  markings. Jonah Rank provided Joshua Jacobson's rules written in  Chanting the Hebrew Bible for determining qamats qatan. Raphael Finkel  completed the first-pass qamats qatan/sheva na detection code.   That  code (currently written in Perl) needs to be integrated into our  infrastructure (mostly XQuery/XSLT; might be able to work in Java). The  transliteration engine used in Efraim's early proof-of-concept Haggadah  is now incorporated into the code again.  It will need some tweaking  again once we integrate a system for indicating a definite sheva na in  the encoding, and it does not work properly unless the qamats qatan is  properly encoded).

</div>

<em>Documentation</em> (Efraim,  Aharon, Ze'ev)

<div style="padding-left: 30px;">We are still  looking for volunteers to just look over our documentation and help us  know how it reads and where we can make improvements. Anyone can freely  register to edit on our wiki.

Much thanks are due to Ze'ev  Clementson whose many questions posed on our discussion list helped us  clarify our documentation and fix bugs in our build processes.

Aharon  and Efraim, besides blogging on opensiddur.net,  they are also <a href="http://groups.google.com/group/jewish-tech/msg/b97320225bb29bc0" target="_blank" rel="noopener noreferrer">contributing</a> to the new <a href="http://groups.google.com/group/jewish-tech/" target="_blank" rel="noopener noreferrer">J-Tech</a> list set up by Dan Sieradski. If you're a Jewish technologist, we  recommend this list as a useful space for sharing knowledge and ideas.

</div>

<em>Organizational  Structure</em> (Aharon, Efraim)

<div style="padding-left: 30px;">After  some feedback, we've made an effort to merge all project resources  under the Open Siddur Project banner. If you look closely, you'll still  see the Jewish Liturgy Project. Hint: take a look at our XML encoding  documentation :)

Efraim and Aharon are looking into economic  models to keep this project  both free and sustainable in the long term.  One of these models is a  cooperative of contributors.  We are certainly looking for more input  here.

We are now <a href="http://www.razoo.com/story/The-Open-Siddur-Project-2" target="_blank" rel="noopener noreferrer">capable of  receiving tax deductible donations</a> via Razoo through a fiscal  sponsorship agreement with the United States 501(c)3 registered  non-profit, <a href="http://jewishcreativity.org" target="_blank" rel="noopener noreferrer">Center for Jewish Culture &amp; Creativity</a>. Money raised  this way can help us pay for our major operational expenses (server  costs, domain registration fees).

</div>

<em>Communications and  Promotion</em> (Aharon)

<div style="padding-left: 30px;">Aharon  gave a presentation at this year's Limmud NY and pitched the Open Siddur  Project. Answering his question, what's the siddur you've always  wanted, 11 year old Leora answered: "I've grown a lot since I was given  my first siddur in second grade, but I'm still using the same blue Shiloh siddur. I'd like to make a siddur that I can draw in, write my  own prayers, and share them with my friends." Help the Open Siddur  Project bring Leora's vision to fruition, there are <a href="https://opensiddur.org/contribute/">many ways to contribute</a>.

We  now have two discussion email lists and an announcement email list.  Much of the volume on our old jewishliturgy-discuss list was focused on  software development. To avoid having our non-developer list members  tune out of the discussion, we thought it better to divide the list into  <a href="http://groups.google.com/group/opensiddur-talk" target="_blank" rel="noopener noreferrer">opensiddur-talk</a> and <a href="http://groups.google.com/group/opensiddur-tech" target="_blank" rel="noopener noreferrer">opensiddur-tech</a>.

The  <a href="http://groups.google.com/group/opensiddur-announce" target="_blank" rel="noopener noreferrer">opensiddur-announcement</a> list will be used mainly for sending out regular updates like this one.  Announcements will also be shared via twitter (149 followers) and our  facebook group (nearly 300 users).

Since last November we have  had 3 Open Siddur Open Chats at irc://irc.freenode.net/jewisliturgy .  During these chats we've talked shop with all sorts of curious folks,  software developers, liturgy researchers, and Jewish educators. The  format and medium of the communication (Internet Relay Chat) is proving  difficult for a number of participants and we're investigating  alternatives. So far we've looked at DimDim and came away unimpressed.  Any suggestions for cross-platform group chat technology accessible to  users at no cost?

Thanks to quick action on the part of Azriel,  the Open Siddur Project now owns the opensiddur.org domain. Good work,  Azriel! :)

The logs of the chat are available on our wiki, here.

Our  next Open Chat is scheduled for February 21st, 1pm EST/10am PST/8pm  Israel.

Aharon will be speaking on the Open Siddur at the <a href="http://www.ajrsem.org" target="_blank" rel="noopener noreferrer">Academy for Jewish  Religion</a> in Riverdale, March 15th.

</div>

<em>Press</em> (Aharon, Efraim)

<div style="padding-left: 30px;">Since our last  update in November, two major articles appeared in Jewish media  concerning the Open Siddur Project. Hadara Graubart's "<a href="http://www.tabletmag.com/life-and-religion/21498/prayer-unbound/" target="_blank" rel="noopener noreferrer">Prayer  Unbound</a>", in Tablet Magazine and Steve Lipman's "<a href="http://groups.yahoo.com/group/shefa/message/2976" target="_blank" rel="noopener noreferrer">Taking  Prayer Into Their Own Hands</a>", in Jewish Week. Sociologist Dr.  Steven M. Cohen may have also been thinking of us when he wrote  concerning the use of New media by young Jewish innovators in an article  for the JPR Newsletter, "<a href="http://www.jpr.org.uk/news/detail.php?id=141" target="_blank" rel="noopener noreferrer">From Jewish people  to Jewish purpose: The new age of social innovation in American Jewish  life, and its implications for British Jewry</a>":
<div style="padding-left: 30px;">"The growth of Jewish culture may partly be  attributed to the expansion of the Internet and the decline in  production costs.  The Internet has allowed new music, videos and films  to be produced and distributed at almost no cost.  Much of the recent  Jewish innovation focuses on building websites, which typically empower  Jews to create their own Jewish lives on their own terms.  As the  Internet has become a two-way communications device, online innovations  often allow users to participate in interesting Jewish activities that  are free of any controlling authority.  Examples include online  facilities that allow people to create their own siddurim (prayer books)  or access midrashim  (Biblical commentaries) in ways that enable Jews  to discover traditional texts."</div>
</div>

<em>Team Member  Updates</em> (Azriel, Aharon)

<div style="padding-left: 30px;">Azriel  writes that this semester has kept him super busy and so hasn't been  able to give as much as he'd like to the Open Siddur this semester.  Everyone here misses him.

Most of our developers are either  working full time or studying full time. Aharon's fellowship at Yeshivat  Hadar is coming to a close in May and he's been busy thinking about  where he can go next to help improve awareness, increase compassion, and  inspire creativity through Jewish spiritual techniques and  technologies. If you're looking for someone <a href="http://aharon.varady.net/" target="_blank" rel="noopener noreferrer">multi-talented, capable, and visionary</a> all at once, reach out to him while he's still available. Your Jewish  institution could hardly do better and you'd be supporting the Open  Siddur Project at the same time.

</div>

Wishing you a happy  and warm Adar,
Aharon Varady
Founder &amp; Co-director
The Open Siddur Project
https://opensiddur.net/join-us/
</body>
</html>