---
layout: post
published: true
title: Wir sind so geil, ...
author-id: isotopp
date: 2004-02-12 18:01:46 UTC
tags:
- blog
- lang_de
feature-img: assets/img/background/rijksmuseum.jpg
---
<img border='1' hspace='5' align='left' src='/uploads/rss.png' alt='' /> Wir sind so geil, <a href="http://www.supergarv.de/serendipity/archives/311_s9y_Individualisierter_RSSFeed_per_Conditional_Get.html">wir sprechen XML</a>. Nicht irgendein XML, nein, sogar RSS.

Nicht, daß mich jemand falsch versteht: Ich liebe S9Y und ich respektiere Garvins Arbeit. Es ist nur einer dieser Tage, an denen ich glaube, daß ich mich an den Kopf fassen muß.

Da sitzt ein Haufen Leute aufeinander und schwallt sich mit "Blogriffen" und Wortblödungen zu, daß <a href="http://www.naomiwatts.info/serendipity/archives/104_Blogwhat__Blogroll_blogarama_blogtree_blogwise_blogcheck_blogoo.html">nicht nur mir</a> ganz blümerant im Schädel wird. Oder <a href="http://blogosfear.org/eintrag.php?id=29">wundert sich öffentlich</a>, warum nicht mehr Leute bloggen.

&nbsp;

Aber es ist nicht nur der Technobabble-Dummlall, der in der Szene rumschwappt, der dies alles schwierig macht. Es ist nicht nur die verwirrende Vielfalt von nicht richtig durchdachten und nicht richtig interoperablen Formaten mit Versionsnummern, die sich <a href="http://uckan.info/wasistrss.htm#a1">nur in Hundersteln unterscheiden</a>, aber alle mit 0 anfangen. Es ist auch nicht, daß diese Formate weder richtig spezifiziert sind, noch die Inhalte in diesen sogenannten Formaten in den meisten Fällen richtig validiert sind.

Es ist auch noch so, daß sich diese ganze Technik wie Dreck skaliert. Da habe ich nun also einen dieser megageilen RSS-Aggregatoren, die nur unter Windows zu kriegen sind und kann endlich 378 Blogs auf einmal lesen, ohne dabei sterben zu müssen (<a href="http://beissholz.de/pivot/entry.php?id=178">Manche Nisis</a> behaupten das ginge). Und dann pollt sich mein Feedreader bei 378 Sites tot, die alle sowieso nur alle Jubeljahre eine Änderung haben?

"Nein", höre ich da die Blog-Apologeten rufen, "das brauchst Du nicht, denn wir pingen ja einen von fünf Millionen Blogroll-Aggregator-Services, wenn es was neues gibt." Richtig, S9Y macht das sogar mit allen fünf Millionen gleichzeitig, wenn man will (Ok, es ist derzeit eine noch gerade mal einstellige Zahl). "Hier!", brüllt mein Blog, "Mein Meister hat was neues geschrieben."

Nur, wenn ich den Code in S9Y richtig gelesen habe, macht es genau dies - kein Stück mehr Informationsgehalt. Es wird der tatsächliche Content meines Eintrages nicht an den gepingten Service geposted. Dann kann er auch nicht von dort runtergeladen werden, sondern muß direkt von meinem Blog geholt werden.

Es wird nicht mal eine eindeutige ID generiert, oder die URL des neuen Eintrages abgeliefert, nur die Base-URL des Blogs und ggf. die Base-URL des RSS-Feeds. Also kann sich ein Client vom Pingservice nicht einmal eine Liste der Einträge, die neu sind, runterladen, sondern muß sich das einzeln von den Blogs geben lassen. Wieviel schlauer wäre es, den Content gezippt im Batch direkt vom Pingservice zu ziehen?

Garvin schreibt jetzt in seinem Artikel, daß man auch den RSS-Feed eines Blogs normal nicht nach "alle Artikel seit dem x.y.2004" fragen kann, oder alle Artikel seitdem URL z veröffentlicht wurde". Man kann auch nicht sagen "Ich hab schon r, s, t, x, y, z" und das Blog antwortet "Dann fehlen Dir u, v und w". Jeder <a href="http://www.ietf.org/rfc/rfc1036.txt">NNTP-Server</a> kann das, schon seit den 80ern.

Je mehr ich über die sogenannte Blogosphere lerne, desto weniger beeindruckt bin ich. Wenn Ihr schon USENET in bunt neu erfindet, dann denkt doch bitte vorher 15 Sekunden nach, wie ihr Eure Formate spezifiziert, wie sie sich skalieren und wie man sie validiert - nichts von dem habt Ihr gemacht. Selbst ZCONNECT hat mehr Hirnschmalz in seine Strukturen investiert als dieser Haufen mausschubsender Scriptkiddies, die das definieren, was <a href="http://www.iht.com/articles/126768.html">Konferenzen wie Davos</a> bis zur Unbrauchbarkeit für sinnvolle Themen dominiert.

So aber kann ich Euch nur ein fröhliches <a href="http://www.iks-jena.de/mitarb/lutz/usenet/Fachbegriffe.der.Informatik.html#67">FdI #67</a> an den Kopf werfen. Ihr suckt. Kapital.

news:blog.de.koehntopp.kris jetzt!