# **KI-Spickzettel**

Stand: 2.6.2025 \- online: [**https://bit.ly/mak-ki-spickzettel**](https://bit.ly/mak-ki-spickzettel)

**Dieser KI-Spickzettel und die Seminar-Folien als Chatbot: [Unter diesem Link](https://chatgpt.com/g/g-681bbacc726481918dba28de0259e06f-ki-spickzettel-interaktiv) findest du eine Version des Spickzettels, mit der du chatten kannst \- ein CustomGPT.** (Wie das funktioniert? Mehr [im Spickzettel](#die-funktionen-von-chatgpt).) 

## *Inhalt*

[KI. Eine ultrakurze Vorgeschichte.](#ki.-eine-ultrakurze-vorgeschichte.)

[Wie lernt KI?](#wie-lernt-ki?)

[Was ChatGPT nicht ist…](#was-chatgpt-nicht-ist…)

[Was chatGPT eigentlich ist…](#was-chatgpt-eigentlich-ist…)

[Zugang zum KI-Chatbot ChatGPT bekommen](#zugang-zum-ki-chatbot-chatgpt-bekommen)

[Die Konkurrenz: Andere Große Sprachmodelle](#die-konkurrenz:-andere-große-sprachmodelle)

[Neu: “Reasoning”-Modelle und Agenten](#neu:-“reasoning”-modelle-und-agenten)

[Woher kommen die Informationen, die die KI mir gibt?](#woher-kommen-die-informationen,-die-die-ki-mir-gibt?)

[ChatGPT-Mythen und \-Fakten](#chatgpt-mythen-und--fakten)

[Besser prompten\! Tipps für ChatGPT](#besser-prompten!-tipps-für-chatgpt)

[“Setze nichts voraus \- gibt der KI gut strukturiere ROMANE.”](#“setze-nichts-voraus---gibt-der-ki-gut-strukturiere-romane.”)

[(R)olle](#\(r\)olle)

[(O)bjective, Oberstes Ziel](#\(o\)bjective,-oberstes-ziel)

[(M)eta-Anweisungen](#\(m\)eta-anweisungen)

[(A)nwendungsbeispiele](#\(a\)nwendungsbeispiele)

[(N)icht zu lang](#\(n\)icht-zu-lang)

[(E)xperimentiere\!](#\(e\)xperimentiere!)

[Prompten mit KI-Hilfe…](#prompten-mit-ki-hilfe…)

[Die Funktionen von ChatGPT](#die-funktionen-von-chatgpt)

[Mit KI arbeiten: Profi-Techniken](#mit-ki-arbeiten:-profi-techniken)

[KI-Tools](#ki-tools)

[KI-Recherche-Tools](#ki-recherche-tools)

[KI-Text-Tools](#ki-text-tools)

[Verschriftlichungs-Tools](#verschriftlichungs-tools)

[KI-Textauswertungs-Tools](#ki-textauswertungs-tools)

[KI-Chatbots \- Achtung: hohe Einarbeitungszeit\!](#ki-chatbots---achtung:-hohe-einarbeitungszeit!)

[RAG-Assistenten: Selbst GPTs erstellen](#rag-assistenten:-selbst-gpts-erstellen)

[Mit Bezahlvariante ChatGPT Plus \- oder auf dem Playground: Selbst einen GPTs-Assistenten anlegen](#mit-bezahlvariante-chatgpt-plus---oder-auf-dem-playground:-selbst-einen-gpts-assistenten-anlegen)

[Dokumente hinterlegen](#dokumente-hinterlegen)

[Was die Technik kann \- und was nicht](#was-die-technik-kann---und-was-nicht)

[Und ohne ChatGPT-Plus-Konto? Alternative Mistral.ai](#und-ohne-chatgpt-plus-konto?-alternative-mistral.ai)

[Die Sprachmodell-Testumgebung: Chainforge installieren](#die-sprachmodell-testumgebung:-chainforge-installieren)

[KI als Programmier-Helfer](#ki-als-programmier-helfer)

[Die Bildgeneratoren \- FLUX & Friends](#die-bildgeneratoren---flux-&-friends)

[Bewegtbild erzeugen](#bewegtbild-erzeugen)

[KI erkennen: Funktionieren Detektoren?](#ki-erkennen:-funktionieren-detektoren?)

[Schwierige Fragen: Datenschutz, Umwelt, Recht](#schwierige-fragen:-datenschutz,-umwelt,-recht)

[Abhängigkeit von Tech-Riesen](#abhängigkeit-von-tech-riesen)

[Der Energieverbrauch von KI](#der-energieverbrauch-von-ki)

[Klischees und Vorurteile](#klischees-und-vorurteile)

[Darf ich das? Ein wenig Rechtskunde](#darf-ich-das?-ein-wenig-rechtskunde)

[Datenschutz](#datenschutz)

[Linktipps:](#linktipps:)

[Newsletter und Podcasts](#newsletter-und-podcasts)

# **`KI. Eine ultrakurze Vorgeschichte.`**  {#ki.-eine-ultrakurze-vorgeschichte.}

* Der Ausdruck “Künstliche Intelligenz” ist eigentlich ein von Wissenschaftlern erdachter Marketing-Begriff aus den 50er Jahren.  
* Sie funktionierte lange Zeit nicht richtig. Was ist inzwischen anders? Wir haben inzwischen unglaublich schnelle Computer \- und die riesigen Mengen an Daten, die das Training großer Sprachmodelle erst möglich machen. 	 	 	

## **Wie lernt KI?** {#wie-lernt-ki?}

Der Begriff war Etikettenschwindel: Eigentlich ging es in der Konferenz 1956 um Nachahmung biologischer Signalverarbeitung mit der damals neuen Computertechnik \- aber „künstliche Intelligenz“ klingt halt besser und half bei der Einwerbung von Forschungsgeldern. Tatsächlich meinen wir mit KI meist einen Teilbereich, der Computern mit speziellen Algorithmen ermöglicht, aus Trainingsdaten menschliche Entscheidungen nachzuahmen \- zu „lernen“.

* Wie ein einzelnes Neuron funktioniert: die 	interaktive Erklärung von Jay Alammar 	[https://jalammar.github.io/visual-interactive-guide-basics-neural-networks/](https://jalammar.github.io/visual-interactive-guide-basics-neural-networks/) 		  
* Bilderkennung selbst trainieren: 	[https://teachablemachine.withgoogle.com](https://teachablemachine.withgoogle.com/)  
* Tolle Animation: So formt eine KI Sätze\! [https://moebio.com/mind/](https://moebio.com/mind/)   
* Ein Sprachmodell, dem man beim Arbeiten über die Schulter schauen kann (und dabei ahnen, wie das alles 	funktioniert): [https://www.soekia.ch/GPT/](https://www.soekia.ch/GPT/) 	

## **Was ChatGPT nicht ist…** {#was-chatgpt-nicht-ist…}

…so etwas wie [“Eliza”](https://web.njit.edu/~ronkowit/eliza.html), der Therapie-Parodie-Bot des Informatikers Joseph Weizenbaum. “Eliza” hat ein Gespräch mit ein paar simplen Tricks simuliert \- und folgte dabei einem Rezept aus festen Regeln: einem **Algorithmus**. 

Was mir die Antworten liefert, wenn ich mit ChatGPT chatte, ist kein Algorithmus \- sondern ein **Modell** \- ein trainiertes Neuronales Netz. (Das Training eines Modells ist wiederum Teil eines Algorithmus \- einer festen Berechnungsvorschrift. Alles klar?)

## **Was chatGPT eigentlich ist…**  {#was-chatgpt-eigentlich-ist…}

…ein “Generatives Sprachmodell” \- und zwar mit seinen 175 Milliarden[^1] Parametern ein großes (ein LLM, ein “large language model”): **eine Maschine, die wohlgeformte Texte vorhersagen kann.** Das hat sie aus einer enormen Menge von menschengemachten Texten gelernt. 

Was sie nicht ist: Eine Wahrheitsmaschine, ein Weltgeist oder eine echte “Künstliche Intelligenz” im Sinne dessen, was KI-Forscher:innen erst noch erreichen wollen: chatGPT ist keine  “AGI” (“Artificial General Intelligence”). 

Das Herzstück von chatGPT, das eigentliche Sprachmodell, heißt GPT3 (genau genommen: GPT3.5 Turbo \- eine auf Konversation optimierte Version). Einen weiteren Teil des Chatbots macht das System aus, das mit menschlichem Feedback nachtrainiert wurde, um bessere Antworten zu erzielen \- und noch ein weiteres, das gefährliche, fragwürdige oder unsinnige Nutzer-Fragen aussortieren soll (trainiert mit von Menschen ausgewählten Beispielen). 

* ***Deep Dive** von einem, der an ChatGPT mitgebaut hat: Der Informatiker und OpenAI-Mitgründer Andrey Karpathy erklärt in seinen Vorträgen sehr nachvollziehbar, wie man ein großes Sprachmodell trainiert. Und auch, dass wir noch gar nicht so genau wissen, wie sie eigentlich das tun, was sie tun (auch wenn wir alle Bauteile kennen). [Aktueller 1-Stunden-Vortrag](https://www.youtube.com/watch?v=zjkBMFhNj_g) bei Youtube; etwas älterer [45-Minuten-Vortrag für Microsoft](https://build.microsoft.com/en-US/sessions/db3f4859-cd30-4445-a0cd-553c3304f8e2).*   
* *Wie schafft es das Sprachmodell, sich bei der Auswahl des nächsten Wort am Sinn des bisher Gesagten zu orientieren? Derzeitige KI nutzt dafür eine Struktur namens “Transformer” \- **aber wie sie es schafft, Worte mit Bedeutung aufzuladen**, bekommt man entweder nur sehr allgemein erklärt, oder mit sehr viel Mathematik. Der US-Mathe-Youtuber 3blue1brown hat es geschafft, den Sweet Spot zwischen Allgemeinverständlichkeit und Genauigkeit zu treffen \- zumindest für mich. [A Visual Introduction to Transformers](https://www.youtube.com/watch?v=wjZofJX0v4M), [Visualising Attention](https://www.youtube.com/watch?v=eMlx5fFNoYc) \- 2x25 Youtube-Minuten, die ein gutes Gefühl dafür geben, wie eine KI sinnvolle Antworten erzeugt.* 

## **Zugang zum KI-Chatbot ChatGPT bekommen** {#zugang-zum-ki-chatbot-chatgpt-bekommen}

* Haupteingang: [https://chatgpt.com](https://chat.openai.com) \- dort ein Konto anlegen. Kostenlose Version, etwas eingeschränkt (wechselt dynamisch zwischen GPT-4o und dem etwas schwächeren 4o-Mini-Modell; begrenzte Anzahl von Nachrichten pro 5 Stunde; maximal 3 Datei-Uploads)   
* Werbeaktions-Eingang: [https://copilot.microsoft.com](https://copilot.microsoft.com) bzw. der “Copilot” im Edge-Browser von Microsoft führt zum kostenlosen “Copilot”, der der Bezahlversion von ChatGPT ziemlich nahe kommt: man kann das große Sprachmodell GPT-4 nutzen, Bilder generieren lassen, Informationen aus dem Internet recherchieren. Ich bin seit einer Recherche 2023 kein Freund des Copilot \- [er erzählte mitunter gefährlichen Unsinn. Mit Quellenangabe.](https://www.hessenschau.de/politik/landtagswahl/bing-chat-versagt-als-wahlhilfe-ki-gibt-falschinformationen-zur-hessen-wahl-v1,ltw23-ki-bing-chat-falschinformationen-100.html)   
* Lieferanteneingang: [https://platform.openai.com/playground](https://platform.openai.com/pla); Kreditkartendaten hinterlegen \- und das nackte Sprachmodell ohne ChatGPT-Oberfläche nutzen. Wieso? Im “Playground” kann man Prompts abspeichern, findet man auch ältere, kleinere Textmodelle \- die oft etwas abgedrehter kreativ sind \- und kann an Parametern wie der “Temperatur” drehen, dem Einfluss des Zufalls.  
* Fanclub-Eingang: Ein 20-Dollar-im-Monat-Abo für chatGPT Plus.  
* VIP-Tribüne: Das “ChatGPT Pro”-Abo für 200 Dollar im Monat. 

## **Die Konkurrenz: Andere Große Sprachmodelle**  {#die-konkurrenz:-andere-große-sprachmodelle}

**Welches Modell schneidet wie gut ab?** Die Modell-Landschaft verändert sich schnell; die “Chatbot Arena” lässt Modelle gegeneinander antreten und erstellt daraus eine [**aktuelle Modell-Rangliste**](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard). Dort sind die OpenAI-Modelle meist oben \- aber andere Modelle sind ihnen dicht auf den Fersen; kommerzielle Modelle ebenso wie solche, die man sich auch auf eigene Server herunterladen und anpassen kann (open source). 

* **Claude von Anthropic** \- ein ernst zu nehmender Konkurrent von OpenAI/ChatGPT, den viele KI-Fans vorziehen. [https://www.anthropic.com](https://www.anthropic.com)   
* **Mistral aus Frankreich** liegt etwa gleichauf mit ChatGPT vor einem halben Jahr \- folgt aber anders als die US-Angebote prinzipiell EU-Regeln. Es spricht hervorragend Deutsch und hat in der Chat-Oberfläche sehr nützliche Zusatzfunktionen eingebaut, unter anderem die Perplexity-artige Websuche. Mausert sich allmählich zur echten Alternative: [https://chat.mistral.ai/](https://chat.mistral.ai/)   
* **Grok 3** von Elon Musks Firma xAI holt auf. Leider. [https://x.ai/](https://x.ai/)   
* **DeepSeek R1** aus China ist extrem spannend, weil die Chinesen nicht nur mit relativ bescheidenen Mitteln eine Top-KI gebaut haben, sondern auch ihr Rezept veröffentlicht \- das ist open source, im Prinzip kann es fast jede/r nachkochen, der einen KI-Superrechner hat. Ausprobieren unter [https://chat.deepseek.com](https://chat.deepseek.com), mehr drüber lesen: [hier.](https://www.janeggers.tech/eeblog/2025/der-aldi-drache-was-ich-an-deepseek-r1-aus-china-grossartig-finde-und-was-nicht/) 

Es gibt auch Sprachmodelle, die auf dem eigenen Computer laufen, weil sie “open source” verfügbar sind \- genug Speicher bzw. eine leistungsfähige Supergrafikkarte vorausgesetzt: 

* Spitzentechnik aus Frankreich “**Mistral 3.1**” \- spricht recht gut deutsch, ist in 6-Bit-Quantisierung nur 20GB groß und ist besser als GPT-4o mini.  
* **Llama3.2** ist ein Sprachmodell von Meta/Facebook, das gemessen an dem, was es kann, winzig ist \- und dadurch selbst auf einem Raspberry-Kleinstrechner laufen kann. Es spricht gut Deutsch und ist als Open-Source-Modell für eine Menge angepasste (“feingetunte”) Varianten.   
* **Gemma3** ist ein Open-Source-Sprachmodell von Google, das mit vergleichsweise wenig Speicher auskommt und so schon auf einem Raspberry-Pi-Kleinrechner gut deutsch sprechen kann. 

Alle drei laufen mit einem Programm wie [Ollama](https://github.com/ollama/ollama) sogar auf gut ausgestatteten Macs und PCs. Allerdings halluzinieren kleinere Modelle vergleichsweise viel. 

## **Neu: “Reasoning”-Modelle und Agenten** {#neu:-“reasoning”-modelle-und-agenten}

Gegen Ende des Jahres 2024 hat OpenAI eine neue Technik ausgerollt: **“Reasoning”-Modelle**, KI-Sprachmodelle, die fest verdrahtet für “Chain of thought”-Prompts sind (siehe unten: Meta-Anweisungen), und zu jeder Frage erst eine Assoziationskette erstellen. 

Richtig Fahrt aufgenommen hat das erst durch einen Konkurrenten, mit dem niemand gerechnet hatte: Das chinesische DeepSeek hat mit deutlich geringerem Aufwand eine konkurrenzfähige Reasoning-KI gebaut, und dann auch noch das Rezept veröffentlicht, wie sie es getan haben \- Nachbau ausdrücklich möglich.

* Mehr über DeepSeek R1: Was es kann, was es ist \- und was mich am chinesischen Anbieter stört [https://www.janeggers.tech/ywft](https://www.janeggers.tech/ywft)

Ein weiterer aktueller Trend in der KI-Welt ist, dass man den Sprachmodellen die Möglichkeit gibt, “Werkzeuge” zu gebrauchen \- also Kommandos auszugeben, mit denen sie im Netz suchen, Datenbanken abfragen oder Programmcode starten können. Damit kann man so genannte **Agenten** bauen, die Aufgaben selbsttätig lösen können: eigentlich meint das ein KI-Sprachmodell plus Werkzeuge plus Einbindung in ein Programm, das den Ablauf steuert. 

* Nein, zwei KI-Agenten, die sich in einer Geheimsprache unterhalten, sind keine Vorboten der Roboter-Apokalypse\! [https://www.janeggers.tech/8toy](https://www.janeggers.tech/8toy)

## **Woher kommen die Informationen, die die KI mir gibt?** {#woher-kommen-die-informationen,-die-die-ki-mir-gibt?}

Aktuelle KI-Sprachmodelle können “Werkzeuge” einsetzen, also Zusatzprogramme aktivieren \- beispielsweise zur Suche im Internet. OpenAI hat das seit Ende 2024 fest in ChatGPT integriert; bei Mistral versteckt sich diese Möglichkeit hinter der “Tools”-Schaltfläche. 

Leider muss man genau hinschauen, um festzustellen, ob die KI diese Möglichkeit tatsächlich auch genutzt hat: 

* **Wenn die KI eine Quelle verlinkt** \- über eine Art Knopf \-  hat sie im Internet recherchiert.   
* **Wenn die KI keine verlinkte Quelle zitiert**, stammt die Information aus den Trainingsdaten \- und enthält möglicherweise Ungenaues oder regelrecht Erfundenes. 

Besonders tricky: Manchmal halluziniert die KI einen **“falschen Hasen”** \- das Sprachmodell generiert einen Link, der aber kein Quellen-Link aus der Suche ist, sondern einer, den sich das Sprachmodell ausgedacht hat. 

## **ChatGPT-Mythen und \-Fakten** {#chatgpt-mythen-und--fakten}

ChatGPT wurde mit jeder Menge Text trainiert \- einigen Regalkilometern Internet \- die bei den 4o- und o1–Modellen im Oktober 2023 aufhören, bei neueren Modellen im Juni 2024; neuere Informationen erfindet das Modell einfach.  

Wichtig: 

* **ChatGPT \- der Chat \- ist eine Benutzer-Oberfläche für ein Sprachmodell \-** das ist die eigentliche KI. In der Enterprise-Variante haben wir die Auswahl zwischen GPT-3.5 und dem leistungsfähigeren GPT-4.   
* **GPT-4 kann nicht nur Worte als Eingabe benutzen, sondern auch Bilder** \- es ist multimodal. (Siehe: Fähigkeiten). Das ältere GPT-3.5 hatte diese Fähigkeit nicht.  
* **ChatGPT ist keine Datenbank.** Auch Informationen aus den Trainingsdaten ruft das Modell nicht einfach ab \- sondern formt Texte, die zu diesen Trainingsdaten passen. Das ist mehr oder weniger genau \- manchmal weniger: Demo auf [frankruft.de/apps/meret\_becker\_fakten](http://frankruft.de/apps/meret_becker_fakten)   
* **Das GPT-Sprachmodell selbst hat keinen Zugang zum Internet.** Ohne Zusatzprogramme kann die KI deshalb keinerlei aktuelle Informationen berücksichtigen; nur erfinden\! Siehe oben: nur Dinge, die eine verlinkte Quelle haben, sind durch diese Quelle (möglicherweise) belegt. Auch wenn ich der KI eine Internet-Adresse gebe, ist nicht gesagt, dass sie dort wirklich nachschaut \- das können erst neuere, auf [Werkzeug-Gebrauch/Agenten-Fähigkeiten](#neu:-“reasoning”-modelle-und-agenten) optimierte Modelle wie GPT-o3 können das einigermaßen verlässlich.   
* Der Trainingsstand ändert sich nicht durch das, was ich eingebe. ***Das Modell lernt aus unseren Prompts nichts dazu.*** (OpenAI erstellt allerdings aus unserem Feedback Updates, also neue, verbesserte Modelle \- und hebt dafür alle, alle, alle\! Eingaben mindestens 30 Tage auf.)   
* ***Das Modell hat (noch) kein Gedächtnis*** \- es reagiert NUR auf das, was ich ihm im Prompt übergebe. (Technisch ist der Chat, den ich mit dem Modell führe, einfach folgende Übergabe an das Modell: Alle bisherigen Fragen und Antworten plus der letzten Nutzer-Frage \- vervollständige diesen Text).   
  Allerdings rüstet OpenAI gerade mit einem einfachen Trick ein Gedächtnis für ChatGPT nach: Die KI erstellt aus den bisherigen Chats ein Persönlichkeits-Profil und Zusammenfassungen, die in den aktuellen Chat eingespeist werden. [Mehr in meinem Blog](https://www.janeggers.tech/eeblog/2024/chatgpt-erstellt-jetzt-bald-ein-persoenliches-profil-von-dir/).   
* Es gibt eine ***Obergrenze an Worten, die das Modell verarbeiten kann*** \- die sich allerdings nach oben schiebt: Anfangs konnte ChatGPT nur bis 2048 Token verarbeiten, dann lange Zeit einige Seiten Text, 2024 schon mittlere Novellen, und inzwischen würde “Krieg und Frieden” einmal in den Kontext passen. Allerdings [belegen](https://arxiv.org/abs/2407.11963) [Studien](https://arxiv.org/pdf/2502.05167), dass Sprachmodelle um so schlechter arbeiten, je länger der Kontext ist.  
* **Es lohnt sich, auf den letzten Satz zu achten.** Es ist eine Eigenheit von Sprachmodellen, dass sie Anfang und Ende ihres “Kontextes” stärker beachten \- den Anfang, den “Systemprompt”, haben wir nicht unter Kontrolle, aber was als letztes gesagt wird, bestimmen wir.   
* Der ***Zufall spielt eine Riesenrolle*** \- wenn das Modell die Worte auswählt, die den Text vervollständigen, geht es immer einen etwas anderen Weg; das macht die KI “menschlicher”. Das hat zur Folge, dass zweimal dieselbe Anfrage zu zwei unterschiedlichen Antworten führt, das kann auch der “Temperatur”-Regler für den Einfluss des Zufalls nicht ganz verhindern. [Auch hier mehr in meinem Blog](https://www.janeggers.tech/eeblog/2024/der-name-ist-zufall-reiner-zufall-nutze-den-ki-geheim-agenten/).   
* Es gibt ***keine Möglichkeit, ChatGPT-Texte sicher zu erkennen.*** “Do AI detectors work? In short, no” \- [schreibt ChatGPT-Anbieter OpenAI selbst dazu](https://help.openai.com/en/articles/8313351-how-can-educators-respond-to-students-presenting-ai-generated-content-as-their-own). Der [Detectora](https://www.detectora.de)\-Detektor für deutsche Texte funktioniert für Standard-Texte ganz ordentlich, bietet aber auch keine Garantien. – Auf keinen Fall sollte man einen Text bei ChatGPT eingeben und fragen \- man bekommt zwar eine Antwort, aber die ist mit Sicherheit eine Halluzination.

# **`Besser prompten! Tipps für ChatGPT`** {#besser-prompten!-tipps-für-chatgpt}

## **“Setze nichts voraus \- gibt der KI gut strukturiere ROMANE.”** {#“setze-nichts-voraus---gibt-der-ki-gut-strukturiere-romane.”}

Nach diesem kleinen Merkvers kann man Prompts \- also Anfragen an ChatGPT \- so konstruieren, dass man bessere Ergebnisse erhält. Das funktioniert so in der Regel natürlich auch für andere KI\!

(mehr hier: [https://janeggers.tech/romane](https://janeggers.tech/romane))

## **(R)olle** {#(r)olle}

Der KI sagen, als wer sie antworten soll \- das erhöht die Wahrscheinlichkeit einer Antwort mit Fachkenntnis: “Antworte als Suchmaschinenoptimierer.”

*Anmerkung: Wer Zugriff auf den “Playground” hat, meinen Bastelzugang über Colab (“Servicetechniker”) oder direkt die API nutzt, kann die Rolle über das “System”-Prompt definieren.* 

## **(O)bjective, Oberstes Ziel** {#(o)bjective,-oberstes-ziel}

Der KI klar sagen, welches Ergebnis man von ihr haben will: “Schreibe 10 SEO-optimierte Überschriften zu diesem Text.”

## **(M)eta-Anweisungen** {#(m)eta-anweisungen}

Bei komplexen Aufgaben hilft es der KI, wenn man das Problem in Teilaufgaben zerlegt \- und ihr dann sagt, wie sie vorgehen soll. Das kann man auch Schritt für Schritt tun: “Du bist SEO-Redakteur. Nenne die fünf häufigsten Begriffe, unter denen dieser Text möglicherweise von Nutzerinnen und Nutzern bei Google gesucht würde”, und dann: “Schreibe mit diesen Suchbegriffen 10 SEO-optimierter Überschriftenvorschläge.”

Zugegeben: Meta-Anweisungen braucht man nicht immer. Aber sie sind ein mächtiges Mittel, ein Sprachmodell zu fokussieren. 

## **(A)nwendungsbeispiele** {#(a)nwendungsbeispiele}

Auch das wird man nicht immer tun \- aber: Prompts mit Anwendungsbeispielen \- so genannte “few-shot prompts” \- sind eine extrem mächtige Technik. 

Der KI zeigen, was man von ihr will \- mit Beispielen: Wenn man ihr zeigt, welche Eingaben zu welchen Ausgaben führen sollen, lernt sie daraus. Diese “few-shot prompts” geben dem System die Möglichkeit, aus den wenigen Beispielen erstaunlich gut zu abstrahieren, und erhöhen die Trefferquote enorm: zum Beispiel, wenn man versucht, den Stil eines Autors zu kopieren oder die Maschine zur Klassifikation von Texten zu nutzen. 

Wie viele Anwendungsbeispiele nutzt man? Auf der einen Seite möchte man natürlich einen möglichst weiten Bereich möglicher Antworten abdecken, auf der anderen Seite ist das mühsam \- und schließlich müssen die Beispiele auch alle ins Kontextfenster des Sprachmodells passen. Ein Blick auf Forschung von Aleph Alpha zeigt: oft reichen zwei Beispiele. 

*Anmerkung: Über den Playground oder die API kann man Beispiele in als Kombination “User:”-Prompt und der gewünschten ”Agent:”-Antwort übergeben:* 

* *System: Klassifiziere den Text als positiv, negativ, oder neutral.*   
* *User: Das ist doch so dumm, dass es brummt.*   
* *Agent: negativ*   
* *User: Da hat sich jemand echt Gedanken gemacht.*  
* *Agent: positiv*  
* *User: Mein Luftkissenfahrzeug ist voller Aale*  
* *Agent: neutral* 

*Anwendungsbeispiel: meine kleine [“Populismusdetektor”-Demo im OpenAI-Playground.](https://platform.openai.com/playground/p/mzdKh0YdnkeYRjshUd5cv9He?model=gpt-3.5-turbo) Achtung: nicht als Messinstrument verwenden, ohne vorher geeicht bzw. getestet zu haben, ob es auch wirklich das Richtige misst\!* 

## **(N)icht zu lang** {#(n)icht-zu-lang}

KISS\! Keep it short and simple. (Oder “Keep it simple, stupid”.) Ist auch für die Kommunikation mit Menschen eine gute Regel, hat bei Sprachmodellen aber einen ernsten Hintergrund: Moderne Sprachmodell können zwar dank ihrer riesigen Kontexte unglaublich lange Texteingaben verarbeiten \- Jane Austens “Stolz und Vorurteil” passt bei Claude schon mal komplett rein \- aber sie neigen dazu, Dinge am Anfang und am Ende stärker zu beachten als all die Dinge im Mittelteil. Und sie verlaufen sich gern in zu langen Prompts. Deshalb kann die Anweisung: “Beschreibe es mir, als ob ich 5 wäre” besser funktionieren als ein mehrseitiger Prompt für Einfache Sprache mit tausend Regeln. 

## **(E)xperimentiere\!**  {#(e)xperimentiere!}

Sprachmodelle verhalten sich nicht wie andere Computerprogramme, die aus derselben Eingabe, denselben Daten immer wieder dasselbe Ergebnis produzieren. Ein Sprachmodell erzeugt seine Texte mit einer Riesenportion Zufall \- das ist von den Ingenieuren auch durchaus gewollt, weil die Ergebnisse dann menschlicher wirken. 

Menschen bringt das oft zu falschen Einschätzungen: Sie denken, wenn etwas beim ersten Mal nicht funktioniert (oder eben doch), dann kann die KI es nicht (oder sie kann es eben doch). Dass ein besonders gutes oder schlechtes Ergebnis einfach auch Zufall sein kann, haben wir nicht auf dem Schirm. 

**Wenn etwas einmal (nicht) klappt, sollte ich nicht davon ausgehen, dass es beim nächsten mal wieder so ist**. Das heißt: systematisch testen \- und auch mit leicht veränderten Prompts bei anderen Sprachmodellen. Als “schwarze Kunst” haben Wissenschaftler [unlängst das Prompten bezeichnet](https://trigaten.github.io/Prompt_Survey_Site/) \- weil sie beobachteten, wie schon kleine Änderungen zu großen Effekten führen können. 

**Systematisch experimentieren?** Das “Chainforge”-Tool ist dafür so gut geeignet, dass es [einen eigenen Abschnitt in diesem Dokument](#die-sprachmodell-testumgebung:-chainforge-installieren) bekommen hat. 

## **Prompten mit KI-Hilfe…**  {#prompten-mit-ki-hilfe…}

…kann man zum Beispiel mit der [Prompt Bakery](https://searchwhisperer.ai/prompt/) von Henk van Ess \- oder man schreibt sich ein Prompt, das einen Prompt nach der ROMANE-Regel bastelt :) 

# **`Die Funktionen von ChatGPT`** {#die-funktionen-von-chatgpt}

ChatGPT ist nur die Benutzeroberfläche \- die uns durch einen cleveren Einsatz des Textgenerators vorspiegelt, wir würden uns mit jemandem unterhalten. 

Dahinter habe ich die Auswahl zwischen Sprachmodellen, den eigentlichen KI: 

* **GPT-4o \-** Voreinstellung \- ist das Standard-Modell, das erste den Zugang zu den unten erwähnten erweiterten Funktionen.   
* **GPT-4o mini** ist eine schnellere, günstigere, wenn auch etwas kleinere Version des Sprachmodells.   
* **o3** ist ziemlich beeindruckend: Es ist multimodal, kann Werkzeuge einsetzen \- also zum Beispiel im Internet nachschauen oder Analyse-Code schreiben, wenn es das für richtig hält. Freigeschaltet April 2025, ist es das leistungsfähigste der “Reasoning”-Modelle. Sie sind so strukturiert, dass sie Aufgaben mit einer “chain-of-thought” lösen, einer Argumentationskette, so ähnlich wie wir sie oben unter [(M)eta-Anweisungen](#\(m\)eta-anweisungen) besprechen. Es dauert also immer einige Reflektions-Sekunden, ehe das Sprachmodell mit der Antwort beginnt. Etwas irritierend: o3 kam nach o1 und das wiederum nach 4o. Alles klar?  
* **o1 und o1-mini** sind die Vorgänger von o3, im August 2024 freigeschaltet.    
* **GPT-3.5** war das erste Modell, das ChatGPT antrieb. Es antwortet wesentlich schneller, befolgt aber Anweisungen nicht ganz so gut. Es ist in der Regel etwas nachsichtiger, wenn es um Anweisungen geht, die das Modell als unmoralisch einstuft. (Beispiel: Katzenrezepte)

Es ist übrigens völlig **egal, auf welche Sprache die ChatGPT-Oberfläche eingestellt ist** \- das Sprachmodell versteht und antwortet in Deutsch.

Mit dem GPT-4-Sprachmodell gibt uns die ChatGPT-Oberfläche ein paar sehr nützliche Zusatzfunktionen: 

* **Bilder erzeugen.** Das GPT-4-Sprachmodell hat Zugang zum Bildgenerator DALL-E3. Alles, was ich tun muss, ist GPT-4 bitten: “Erzeuge ein Bild mit dem folgenden Inhalt…” (o.ä.) Den Prompt \- die Anweisung an den Bildgenerator \- schreibt die KI selbst, weshalb in der Regel recht brauchbare Ergebnisse für Illustrationen und Vorträge herauskommen \- leider neigt DALL-E3 etwas zum Kitsch.   
* **Bilder und Dokumente auswerten.** GPT-4 kann auch Bilder als Eingabe nutzen, nicht nur Texte \- und ist damit auch eine sehr gute Bilderkennung, oder kann dafür genutzt werden, Bilder zu beschreiben. Gängige Dokumenttypen wie Word- oder PDF-Dateien liest die Oberfläche ein und übergibt sie als Text an das KI-Sprachmodell. Daten-Dokumente \- z.B. Excel-Dateien \- führen in der Regel dafür, dass das Sprachmodell den **“Analysemodus”** aufruft \- und sich ein kleines Computer-Programm schreibt, um die Datei einzulesen und auszuwerten.   
* **“Analysemodus”, Python-Interpreter**. ChatGPT hat eine kleine Programmierumgebung eingebaut, die die KI benutzen kann \- zum Beispiel um zu rechnen, was ein Sprachmodell \- eine Text-Vorhersagemaschine\! \- nicht besonders gut kann. GPT-4 schreibt statt dessen ein kleines Python-Programm und lässt es ausführen.   
  Das ermöglicht extrem raffinierte Auswertungen von Daten \- allerdings kann man den Analysemodus nur dann richtig nutzen, wenn man selbst ein wenig Einblick in den Programmcode nimmt und nachverfolgt, was die KI programmiert hat.   
* **Custom GPTs** \- **RAG-Assistenten und Dokument-Spezialisten**. Unter dem Punkt “Explore GPTs” hat man die Möglichkeit, die GPTs-Assistenten zu nutzen \- vorkonfigurierte KI-Assistenten, die die Fähigkeit haben, Dokumente zu verarbeiten. Der [“Data Analyst”](https://chat.openai.com/g/g-HMNcP6w7d-data-analyst) ist so gepromptet, dass er besonders gut darin ist, Daten-Dokumente auszuwählen. Andere GPT sind beispielsweise dafür da, [ein PDF hochzuladen](https://chat.openai.com/g/g-V2KIUZSj0-pdf-ai-pdf) und sich damit gewissermaßen unterhalten zu können.   
  GPTs kann man sich auch selbst anlegen und so beispielsweise größere Dokumentationen mit KI erschließen und nachschlagen. Mehr dazu, und zur dabei verwendeten RAG-Technologie, im Abschnitt unten. 

**Im Internet nach Informationen zu suchen?** Ein Sprachmodell hat keine Möglichkeit, das Internet live anzapfen, wenn man ihm nicht die Kontrolle über einen Browser in die Chat-Umgebung baut. 2024 hat ChatGPT **“SearchGPT”** eingeschaltet, eine Kombination des Sprachmodells mit der Bing-Suchmaschine. Inzwischen ist die Suche fest in ChatGPT integriert; sie soll der erfolgreichen “Perplexity”-KI-Suche Konkurrenz machen. 

Abgesehen davon, dass die ChatGPT-Suche übermäßig viel Inhalt von “Bild” und “Welt” liefert \- OpenAI ist mit Springer verpartnert \- sind die Ergebnisse oft einigermaßen brauchbar. **Wer Zugang zum neueren o3-Modell hat**, sollte das nutzen: die 2025 veröffentlichten Reasoning-Modelle recherchieren in der Regel über mehrere Runden und liefern beeindruckende Ergebnisse. 

Aber auch die Recherche-Tools [Perplexity](https://www.perplexity.ai/), die Deep Research bei [Google Gemini](https://gemini.google.com/app) oder die Web-Suche in [Mistral](https://chat.mistral.ai) sind sehr brauchbar. 

In jedem Fall: bitte genau hinschauen \- wann hat das Sprachmodell eine Information wirklich im Netz nachgeschaut (und liefert eine Quelle), wann nicht? [Wie oben erläutert](#woher-kommen-die-informationen,-die-die-ki-mir-gibt?), besteht das Risiko, dass Dinge ungenau oder teilweise sogar erfunden sind, wenn die KI keine verlinkte Quelle explizit nennt. 

# **`Mit KI arbeiten: Profi-Techniken`** {#mit-ki-arbeiten:-profi-techniken}

* **Die KI die KI überprüfen lassen** \- Ein BR-Team hat das so eingebaut, dass man es direkt in Programme 	integrieren kann, die KI zur Zusammenfassung nutzen \- hier [die 	„Second Opinion“-Demo](https://interaktiv.br.de/second-opinion-demo/index.html#/input). 	

* **Aufgaben in Teilaufgaben zerlegen**. Statt alles mit einem großen Prompt zu lösen: für jeden Schritt einer Aufgabe eine spezialisierte KI-Rolle einsetzen. Mit etwas Programm-Zauber (oder einem Tool wie Tiledesk, s.u.) kann man diesen kleinen Teil-KI ermöglichen, sich Aufgaben hin- und herzuschieben und dabei auch über die nächsten Schritte zu entscheiden. Bei KI-Praktikern wird das gerade unter dem Stichwort „Agentic AI“ zum großen Trend.

* **Autoren- und Rezipientenrollen.** Einen Text in Einfache Sprache umwandeln? Natürlich kann ich der KI Rolle, Regeln und Beispiele geben, damit sie als Lektorin meinen Text einfacher verständlich macht. Eine Alternative (oder Ergänzung) ist: Steck die KI in die Rolle eines Fremdsprachlers, der gerade das B2-Niveau erreicht hat, und bitte sie in dieser Rolle aufzulisten, was sie gerne verbessert hätte.   
  Bonus-Idee: Beide Ideen kombinieren und die KI erst einen Entwurf machen lassen \- und dann in der Rolle des Nicht-Muttersprachlers kritisieren. 

* **Markdown, insbesondere Tabellen**. Sprachmodelle können einfache Formatierungsbefehle ausgeben und über die Fettdruck, Links oder Tabellen erzeugen.

* **Beispiele mitgeben** \- gerade bei 	Klassifikations- und Bewertungs-Aufgaben werden die Ergebnisse deutlich besser, etwas bei der Regionalmeldungs- oder 	Schlagwort-Aufgabe von oben. Mistral (Ich mag Mistral. Sagte ich schon, dass ich Mistral mag?) bietet das bei den so genannten “Agenten” als besonders praktische “Few-Shot”-Funktion.

* **Finetuning.** Wenn man einige Dutzend bis einige hundert Beispiele hat, kann man eine angepasste, nachtrainierte Variante des Sprachmodells erzeugen lassen \- das dann zum Beispiel sicherer einen Stil einhält und Entscheidungen trifft. Kostet extra; wird als Service von Anbietern wie OpenAI angeboten. 	

  # **`KI-Tools`** {#ki-tools}

…das sind inzwischen auch viel zu viele, um ihnen gerecht zu werden, deswegen hier eine ganz knappe, subjektive Auswahl, und ansonsten verweise ich auf den immer lesenswerten [KI-Tools-Newsletter von Oskar Vitlif](https://oskar.tools/). 

## **KI-Recherche-Tools** {#ki-recherche-tools}

* Beste KI-Suche derzeit: [https://perplexity.ai](https://perplexity.ai)   
* Knapp Zweiter: Die Suchfunktion in [https://mistral.ai](https://mistral.ai)   
* Kurz dahinter: [https://you.com](https://you.com)   
* Anderer Ansatz: die Ergebnisse mit KI strukturieren [https://explorer.globe.engineer/](https://explorer.globe.engineer/)   
* Sich von der KI Suchvorschläge generieren lassen: [“AI Search Whisperer”](https://google.digitaldigging.org/index2.html) vom Recherche-Guru Henk van Ess

Nochmal die Warnung: Mitunter liefert die KI [Auskünfte, die nicht nur unbrauchbar sind, sondern grob falsch](https://www.hessenschau.de/politik/landtagswahl/bing-chat-versagt-als-wahlhilfe-ki-gibt-falschinformationen-zur-hessen-wahl-v1,ltw23-ki-bing-chat-falschinformationen-100.html): Unsinn mit vermeintlicher Quellenangabe. Und das kann, Stichwort Herz-OP, [richtig gefährlich werden](https://garymarcus.substack.com/p/serious-medical-error-from-perplexitys). Auch im Quellen richtig zitieren [patzen KI-Recherche-Assistenten grandios](https://www.niemanlab.org/2025/03/ai-search-engines-fail-to-produce-accurate-citations-in-over-60-of-tests-according-to-new-tow-center-study/) \- und Recherche-Guru Henk van Ess (ein großer KI-Freund) merkt an, dass [die “Recherche-Agenten” zwar toll darin sind, zu sagen, wie man richtig recherchiert, aber nicht so toll sind im selber richtig recherchieren.](https://www.digitaldigging.org/p/the-rise-of-deep-research) Also: **KI-Zusammenfassungen immer noch mal gegen die Original-Quelle prüfen\!**

## **KI-Text-Tools** {#ki-text-tools}

[KI-Tools-Newsletter-Tipp: oskar.tools von Oskar Vitlif](https://oskar.tools/). 

* Die deutsche Firma [DeepL](https://www.deepl.com/translator) hat nicht nur das Standard-Tool für die besten KI-Übersetzungen, sondern auch einen Stil-Assistenten: [https://www.deepl.com/de/write](https://www.deepl.com/de/write)   
* Texte erbarmungslos redigieren? Kann die [“Wolf-Schneider-KI”](https://reporterfabrik.org/wski-editor/).   
* Deutsche Texte auf KI-Urheberschaft prüfen: [Detectora](https://www.detectora.de) ist ein Tool, das ein junger deutscher KI-Forscher entwickelt hat \- für ChatGPT funktioniert es ganz gut, aber: wie alle diese Tools **gibt es nur Wahrscheinlichkeiten zurück, keine Gewissheiten\!**  
* Rechtschreibprüfung: “[Rechtschreibrat Froben](https://chatgpt.com/g/g-YLwtn0F3M-rechtschreibrat-froben?ref=newsletter.schwarze.info)” ist ein Custom-GPT des FAZ-Journalisten Marcus Schwarze aus den Regeln des Rechtschreibrats.

## **Verschriftlichungs-Tools** {#verschriftlichungs-tools}

* Audios und Videos im Browser verschriftlichen lassen \- ohne dass das Audio irgendwohin hochgeladen wird: [https://stekhn.github.io/transcribe/](https://stekhn.github.io/transcribe/)   
* Gutes Tool von Journalist:innen für Mac-Benutzer: Die App: [“JoJo Transcribe”](https://apps.apple.com/de/app/jojo-transcribe/id1659864300?mt=12)  
* Wen es nicht stört, dass Microsoft/Google etc. mithören: Auch in Office 365 und im Google Drive kann ich mir Audios verschriftlichen lassen \- und auch NotebookLM (siehe unten) kann Audios und Videos verschriftlichen

## **KI-Textauswertungs-Tools** {#ki-textauswertungs-tools}

Helferlein, die beim Aufarbeiten und Strukturieren von Material und Recherche-Ergebnissen unterstützen.

* Faktencheck im Eigenbau: “[Chain-of-verification](https://www.aijournalist.de/prompt-tipp-faktencheck-mit-chain-of-verification)”-Prompt vom DW-Journalisten Patrick Große  
* Audio bzw. Video transkribieren: [JoJo](https://www.vg.no/jojo), eine Mac-App von einem Entwicklungsteam des norwegischen Schibsted-Verlags  
* Längere Dokumente ohne ChatGPT-Plus-Konto analysieren? [chatpdf.com](http://chatpdf.com) ist ein guter Helfer, um über den Inhalt eines PDF mit der KI zu reden.   
* All-in-one-Lösung von Google für Journalistinnen und Journalisten: [NotebookLM](https://notebooklm.google.com/?pli=1) \- Dokumente einwerfen und befragen, auswerten und umarbeiten; sogar in einen (englischen) Podcast als Gespräch zwischen zwei Hosts kann NotebookLM das Material verwandeln.[^2]

## **KI-Chatbots \- Achtung: hohe Einarbeitungszeit\!** {#ki-chatbots---achtung:-hohe-einarbeitungszeit!}

* Chatbots bauen, die auf häufige Fragen verlässlich vorgegebene Antworten geben? [Tiledesk](https://tiledesk.com/) ist eine Plattform, auf der man sich Bots zusammenstoppeln kann, die KI einbinden und trotzdem angemessen und vorhersehbar reagieren \- ohne Programmierkenntnisse. Die kostenlose Nutzung ist auf zwei Bots beschränkt. 

# **`RAG-Assistenten: Selbst GPTs erstellen`** {#rag-assistenten:-selbst-gpts-erstellen}

**KI mit Spezialwissen antworten lassen:** Nicht alles, was wir wissen wollen, ist in den Trainingsdaten erwähnt. Und manchmal wollen wir, dass die KI nur auf bestimmte Dokumente Bezug nimmt; das senkt auch die Wahrscheinlichkeit von Halluzinationen.

Die Technik dafür nennt sich „RAG“ \- Retrieval Augmented Generation (wir haben sie im Seminar nicht näher angeschaut, aber ich will sie erwähnt haben). Die Grundidee: Die KI legt sich gewissermaßen eine Datenbank aus Textschnipseln an, und kopiert sich diejenigen in den Prompt, die sich auf die Anfragen des Nutzers beziehen.

In der Bezahl-Version von ChatGPT kann man sich selbst so genannte „Custom GPTs“ anlegen; es gibt aber auch eine Rundum-Sorglos- und-Kostenlos-Lösung, mit der man die Vorteile von RAGs ausprobieren kann: NotebookLM von Google. Das ist wie ein Ordner, in den man Dokumente, Audiomitschnitte, sogar Youtube-Videos und Webseiten werfen kann \- und dann Fragen dazu stellen. (Wenn einen nicht stört, dass Google alles mitspeichert \- für investigative Projekte ist das vielleicht keine Ideallösung.) Beeindruckendstes Feature: Auf Wunsch verwandelt die Google-App die Dokumente in einen Podcast, in dem sich zwei englische Hosts über das Thema der Dokumente unterhalten. Das bleibt zwar an der Oberfläche und ist manchmal haarsträubend falsch, aber es zeigt, was die KI möglich macht.

## **Mit Bezahlvariante ChatGPT Plus \- oder auf dem Playground: Selbst einen GPTs-Assistenten anlegen** {#mit-bezahlvariante-chatgpt-plus---oder-auf-dem-playground:-selbst-einen-gpts-assistenten-anlegen}

Wer auf “Explore GPTs” klickt, findet dann oben rechts in der Ecke einen grünen “Create”/Anlegen-Button. Die Voreinstellung ist, dass einem die KI beim Anlegen und Prompten dieser Assistenten hilft \- man kann das aber auch umgehen, indem man einfach in der linken Bildschirmhälfte den Tab “Configure” anwählt. Der Assistent benötigt dann

* Einen Namen  
* Eine Rollen- und Aufgabenbeschreibung (“Instructions”)

Symbolbild und “conversation starters” \- Beispielfragen an die KI \- kann man nutzen, muss es aber nicht. 

Wenn man fertig ist mit dem GPT-Assistenten, klickt man oben rechts auf “Create” \- in der Voreinstellung bekommen Sie dann einen Link, über den Sie den Assistenten mit Kollegen teilen können. Achtung: “Publish to GPT Store” sorgt dafür, dass jeder andere ChatGPT-Bezahlkunde Ihren Assistenten finden und nutzen kann\!

* Vorsicht: Verlassen Sie sich nicht darauf, dass Ihre Anweisungen und Dokumente geheim bleiben. Es ist mit etwas Geschick möglich, auch die versteckten Informationen aus dem Modell herauszufragen \- selbst wenn Ihre Instruktionen der KI sagen, sie solle sie nicht verraten. 

## **Dokumente hinterlegen** {#dokumente-hinterlegen}

Wer beispielsweise eine Sammlung von Gesetzen oder Anwendungsbestimmungen mit KI durchsuchen will, kann diese im Abschnitt “Knowledge” hochladen.  

* Vorsicht: PDFs sind oft für Computer nicht besonders gut lesbar \- weil es ein Druckformat ist, kein Behälter für Text. Wer gute Ergebnisse will, sollte die hinterlegten Dokumente tendenziell eher als Word- oder einfache Textdatei hinterlegen.

## **Was die Technik kann \- und was nicht** {#was-die-technik-kann---und-was-nicht}

Dass die Assistenten Dokumente nutzen können, ermöglicht eine Technik namens RAG (Retriaval Augmented Generation): Sie sollten sie deshalb kennen, um zu verstehen, was damit möglich ist und was nicht: 

* Wenn Sie ein Dokument hochladen, zerlegt ChatGPT es in Abschnitte von vermutlich etwa 200 Worten Länge.   
* Jeder dieser Abschnitte bekommt eine Bedeutung zugeordnet \- die KI verortet den Abschnitt auf ihrer internen Karte der Wortbedeutungen.    
* Wenn Sie die KI etwas fragen, sucht sie nach den Textabschnitten, deren Wortbedeutung der der Frage ähnelt \- in menschlichen Begriffen ausgedrückt: in denen es um ein ähnliches Thema zu gehen scheint wie in der Frage.   
* Die KI bekommt dann eine Handvoll Abschnitte, die am besten zur Frage passen, zu dieser Frage kopiert und kann diese Textabschnitte berücksichtigen, wenn sie antwortet. 

Was damit funktioniert, was nicht:

* **Funktioniert sehr gut**, wenn die Antwort an einzelnen Stellen nachgeschlagen werden kann \- “Erlauben mir unsere Dienstvereinbarungen, mich von einem Gesprächspartner zum Abendessen einladen zu lassen?”  
* **Funktioniert nur eingeschränkt,** wenn die KI eine Gesamt-Zusammenfassung erstellen soll: “Reduziere mir die 100 Seiten auf eine Kurzbeschreibung”.   
* **Funktioniert nicht**, wenn die KI zuverlässig alles zu einer Suche finden soll: “Liste mir alle Stellen auf, an denen der Gutachter Zweifel an der Darstellung des Zeugen äußert”.

Mehr dazu: [https://janeggers.tech/li8u](https://janeggers.tech/li8u) 

## **Und ohne ChatGPT-Plus-Konto? Alternative Mistral.ai** {#und-ohne-chatgpt-plus-konto?-alternative-mistral.ai}

Das große Problem an den Custom GPTs: man braucht ein Bezahlkonto, um sie anlegen zu können (nutzen kann man sie derzeit auch in der Kostenlos-Version). 

Als Alternative kann man den ChatGPT-”Playground” nutzen, um sich einen “Assistenten” zu basteln; [das habe ich hier in meinem Blog beschrieben](https://www.janeggers.tech/eeblog/2024/anwendungsfall-fuer-gpts-die-rki-protokolle-mit-ki-hilfe-durchsuchbar-machen/). Dafür braucht man aber eine Kreditkarte, und es ist etwas umständlich. **Viel einfacher: das französische KI-Startup [Mistral](https://mistral.ai).** 

Vorteile: 

* Einfacher und logischer anzulegen als bei ChatGPT…  
* …insbesondere bei der Arbeit mit Beispielen  
* Benutzen? Einfach @Agent im Chat schreiben \- viel einfacher als bei ChatGPT

Nachteile: 

* Leider (noch) kein RAG \- die Mistral-Agenten haben jenseits des Prompts keinen Zugriff auf zusätzliche Dokumente  
* KI etwas schwächer als bei OpenAI

Hier ein Rezept, um einen Einfache-Sprache-Erzeuger hinzubekommen: 

* Ruf den Mistral-“[Le Chat](https://chat.mistral.ai)” auf. (Kostenlose Anmeldung erforderlich)  
* Klicke auf das kleine Dreieckchen in der Mitte des linken Bildschirmrands, um die Einstellungen aufzuklicken.  
* Klicke unten auf dein Konto und wähle dann “Profil” aus.  
* Klicke auf der Profil-Seite auf den Menüpunkt “Agents”  
* Erstelle einen neuen Agenten:   
  * Prompt siehe oben “Einfache Sprache”   
  * Unten unter “Demonstrationen” auf “Demonstrationen hinzufügen”. Trag dann den Originaltext unter “Benutzereingabe” ein, die Einfache-Sprache-Version unter “Ausgabe des Modells”.   
  * Klicke oben rechts auf “Bereitstellung von”  
  * Setz ein Häkchen bei “Le Chat” (API kannst du ohne Kreditkarte nicht anklicken, ist aber auch nicht schlimm)

## **Die Sprachmodell-Testumgebung: Chainforge installieren** {#die-sprachmodell-testumgebung:-chainforge-installieren}

**![][image1]**

**Was es kann:** Prompts testen, und zwar systematisch \- über verschiedene Modelle hinweg: “Bitte” sagen bringt anscheinend bei der aktuellen GPT-3.5-Variante \-0125 was, aber nicht bei den Vorgängermodellen \- oder ist das alles überhaupt Zufall? Auch ganze Tabellen kann man von den Sprachmodellen mit Chainforge verarbeiten lassen \- und kann sich im Baukasten einfache oder komplexere Auswertungs-Funktionen zurecht basteln. 

**Was man dafür braucht:** Einen Rechner, auf dem man Python3 installieren kann \- in der Regel also einen, für den man Admin-Rechte hat \- und Zugriff auf die Kommando-Zeile. 

* **Python installieren.** Einsteigern empfehle ich die ziemlich große Entwicklungs-Umgebung [Anaconda](https://www.anaconda.com/download) oder das deutlich schlankere Programmpaket [miniconda](https://docs.anaconda.com/free/miniconda/miniconda-install/). (Tools wie die Programmier-Umgebung spyder oder Jupyter-Notebooks brauchen die meisten nicht). Installieren, dann auf der Kommandozeile (also in einem Terminal bzw. einer CMD-Shell die folgenden Dinge eingeben:    
  	***pip install \-U pip***  
  	***python \--version***   
  Das aktualisiert erst einmal das Paketmanagement-Programm pip (mit dem wir Python-Software installieren können) und sollte dann so etwas ausgeben wie: “Python 3.10.12”. Bei wem da jetzt “Python 2.xx” steht: bitte Hilfe suchen, alle anderen dürfen weiterlesen.   
* **chainforge installieren**. Das ist supersimpel über pip zu erledigen:   
  	***pip install chainforge***  
  Auf Linux-Rechnern will Python manchmal ein paar zusätzliche Systembibliotheken haben, die über apt (etc.) nachgezogen werden müssen, aber Linuxer kriegen so was hin.   
* chainforge starten:   
  	***chainforge serve***  
  Das startet einen kleinen Chainforge-Server, den wir dann gleich über den Browser nutzen können; Terminalfenster bitte offen lassen.   
  Wer möchte, dass man diesen Server auch von anderen Computern im selben Netzwerk erreichen kann \- etwa, weil das Programm auch auf einem kleinen Raspberry-Pi-Computer läuft \- sollte so starten:   
  	***chainforge serve \--host 0.0.0.0***  
  Dann ist der Server auch über die IP-Adresse des Computers über den Port 8000 zu erreichen.   
* **Chainforge im Browser aufrufen**: In die Adresszeile folgende URL eintragen und abschicken   
  	[***http://localhost:8000***](http://localhost:8000)  
* **In Chainforge die API-Keys für die gewünschten LLMs hinterlegen.** Das findet sich hinter dem Zahnrad-Symbol. Wer Ollama auf demselben Rechner laufen hat, kann die dort geladenen Modelle ohne API-Key einbinden \- alles lokal\!

## **KI als Programmier-Helfer** {#ki-als-programmier-helfer}

Wer selbst Anweisungen für Computer schreibt \- sei es HTML/CSS-Code, kleine Skripte oder ganze Programme \- kann sich von KI-Sprachmodellen unterstützen lassen. Eine der elegantesten Arten ist, das Sprachmodell direkt im Editor mitlaufen zu lassen \- wie es Microsoft/Github mit ihrem kostenpflichtigen “Copilot”-Dienst vorgemacht haben. 

Die \- abgesehen von den KI-API-Kosten \- kostenlose Alternative setzt auf die \- ebenfalls kostenlose \- Entwicklungsumgebung Visual Studio Code auf:

* [VSC herunterladen](https://code.visualstudio.com/download) und auf dem eigenen Rechner installieren   
* Am linken Rand auf “Erweiterungen” klicken (die Kacheln). Die Erweiterung [“Continue”](https://marketplace.visualstudio.com/items?itemName=Continue.continue) aus dem Store laden und installieren.  
* Rechts oben das Symbol klicken, das das rechten Rand des VSC-Fensters einschaltet \- dort ist Continue jetzt aktiv  
* Dort unten rechts auf das Zahnrad klicken. Eine JSON-Datei (Konfigurationsdatei wird geöffnet) \- dort einen Eintrag ergänzen bzw abändern, zum Beispiel so:   
     	{

       "model": "gpt-3.5-turbo",

       "title": "GPT-3.5-Turbo",

       "apiKey": [OpenAI-API-Key eintragen](https://platform.openai.com/api-keys),

       "completionOptions": {},

       "provider": "openai"

     }

* Auf der Schaltfläche unten rechts neben dem Plus das Modell auswählen: GPT-3.5-Turbo.  
* Jetzt kann man sich Programmcode schreiben lassen \- man ruft die Funktion durch Ctrl-I auf, bzw. markiert Code, drückt Ctrl-L und stellt der KI im rechten Fenster Fragen dazu. (“Explain the code”)

Wer einen etwas leistungsfähigeren Rechner hat, kann sich [Ollama](https://github.com/ollama/ollama) installieren, eine Umgebung, in der lokale KI-Modelle laufen. Auf einem 2021 M1-Macbook Air mit 16GB Speicher läuft beispielsweise das KI-Modell deepseek-coder:6.7b \- eine Kommandozeile öffnen, einmal “ollama pull deepseek-coder:6.7b” ausführen, und das Modell wird geladen und kann in VSC über Continue-Schaltfläche für die Modelle über “Autodetect” ausgewählt werden.

# **`Die Bildgeneratoren - FLUX & Friends`** {#die-bildgeneratoren---flux-&-friends}

Bildgeneratoren sind umgedrehte Bilderkennungs-Systeme: Nicht Worte sind Bildern zugeordnet, sondern Bilder Worten. (Wie das funktioniert: eine gerade noch verständliche Beschreibung der Verfahren \- mit Tipps zur Fake Erkennung \- [hier im “Spektrum der Wissenschaft”](https://www.spektrum.de/news/deepfake-wie-lassen-sich-ki-generierte-bilder-enttarnen/2127222#Echobox=1681111044?utm_source=pocket-newtab-global-de-DE).) Vier Bildgeneratoren bestimmen derzeit das Geschehen: 

	 	 	 	

* **FLUX** haben wir im Seminar benutzt; auf [www.frankruft.de/apps/flux](http://www.frankruft.de/apps/flux) 	liegt eine Demo-Installation, eine andere vom Hersteller hier: 	[https://huggingface.co/black-forest-labs/FLUX.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev) Ist mächtig und kann für nichtkommerzielle Zwecke sogar heruntergeladen und lokal eingesetzt werden \- und man kann es aufbohren: Durch ein spezielles Training kann man der KI beibringen, 	Gesichter von einzelnen Personen zu lernen (kann man sich in meiner 	Demo anschauen \- Modell „FLUX-JE-1“ kann Bilder von Menschen mit 	meinem Gesicht erzeugen) \- oder auch einen bestimmten Stil zu übernehmen. 	  
* **DALL-E** vom chatGPT-Anbieter OpenAI war als erstes frei verfügbar \- unkompliziert in der Anwendung, aber nicht besonders flexibel und manchmal etwas bevormundend. (So weigert sich die KI, “Merkel auf einem Dachs” zu generieren.) Erfordert [Anmeldung bei OpenAI](https://labs.openai.com/) und \- sobald man die Gratis-Credits aufgebraucht hat \- eine Kreditkarte zur Abrechnung der Kosten. Mit der neuesten Variante **Dall-E3** hat OpenAI Ende 2023 wieder den Sprung nach vorn \- es liefert oft die derzeit besten Ergebnisse. Zum einen bekommt Dall-E3 als einziges Modell hin, aus einem “Roboter, der ein Einhorn malt” nicht ein “malendes Roboter-Einhorn” zu machen. Zum anderen kann man GPT-4 zum Prompten der Bild-KI einsetzen; mit sehr überzeugenden Resultaten.     
* **Midjourney** liefert die künstlerischten und fotorealistischsten Ergebnisse \- ganz besonders mit der neuen Variante V6.1, die aber derzeit den Abonnenten vorbehalten ist. Inzwischen hat der kostenpflichtige Bilderdienst sogar ein schmuckes Web-Interface auf [www.midjourney.com](http://www.midjourney.com), man muss nicht mehr über einen “Discord”-Chat. Hat Fähigkeiten, die keine andere KI hat (z.B.: Stile übernehmen)   
* **Adobe Firefly** ist ein Bildgenerator, den der Software-Riese Adobe fest in die neueste Versuchsversion seines Bildbearbeitungs-Programms “Photoshop” einbaut \- er kann auf einen Klick zum Beispiel einen Hintergrund für das Porträt-Photo dazu erfinden oder Elemente wie ein Haus oder ein Haustier ergänzen (“generative fill”). Da Adobe verspricht, nur eigene Agentur-Bilder zum Training verwendet zu haben, könnten Profis [dieses Angebot](https://www.adobe.com/de/products/photoshop/generative-fill.html) besonders verlockend finden \- zumal Firefly echt gut ist. 

Ein paar Tipps für Experimente: 

* Von Google finanzierte [Stable-Diffusion-XL-Instanz](https://huggingface.co/spaces/google/sdxl), die für mich meist gut funktioniert.   
* FLUX kann man auf dem eigenen Rechner betreiben \- wer sich nicht scheut, Python zu installieren und von Githubs herunterzuladen, sollte dafür [A1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui) nutzen, eine browserbasierte Oberfläche für den Bildgenerator. Viel einfacher: [DiffusionBee für neuere Mac](https://github.com/divamgupta/diffusionbee-stable-diffusion-ui)s. 

## **Bewegtbild erzeugen** {#bewegtbild-erzeugen}

* [“Sora”](https://openai.com/sora), das Text-to-Video-Modell von OpenAI, haut einen aus den Socken \- [auch weil das Modell mehr beherrscht als nur hübsche Bilder](https://www.janeggers.tech/eeblog/2024/die-naechste-ki-zeitenwende-die-welt-vor-und-nach-sora/). Aber es ist bisher nur: eine Behauptung von OpenAI und ein Haufen zugegeben sehr beeindruckender, aber handverlesener Demo-Videos.  
* Neue kommerzielle Konkurrenz: Die “[Luma Dream Machine](https://lumalabs.ai)” erzeugt extrem gute Video-Bilder aus Prompts und Fotos  
* Andererseits: Auch das Open-Source-Projekt [Stable Video Diffusion](https://www.stablevideo.com/login?returnUrl=%2F) hat hübsche Demos.   
* Deutlich näher am Alltag: [RunwayML](https://runwayml.com/) ist ein Video-Generator, mit dem man Fotos zum Leben erwecken kann \- und vieles mehr. Kostenlose Testphase, danach bezahlbar. 

	 	 	 	

## **KI erkennen: Funktionieren Detektoren?** {#ki-erkennen:-funktionieren-detektoren?}

KI-Bildgeneratoren bekommen Rauschen, in das sie die darzustellenden Dinge hineininterpretieren müssen \- diese „Diffusion“ hinterlässt mathematische Spuren, die man mit Detektoren finden kann. In der Theorie.

Tatsächlich zeigen unsere Experimente mit Bildern, die wir gestreckt, verrauscht, abfotografiert und in echte Bilder hineinmontiert haben: Ein moderner Mehrfach-Detektor wie [truemedia.org](https://truemedia.org/) (kostenlos nach Anmeldung) schlägt trotzdem Alarm. Aber wir sollten uns nicht auf die Ergebnisse verlassen. Zum einen scheint es Tricks zu geben, um die mathematischen Spuren zu verwischen, zum anderen haben die Detektoren die Neigung zu falsch-positiven Ergebnissen (Fehlalarmen).

Am Ende des Tages sollte man auch auf klassische Verifikations-Techniken zurückgreifen: Quellenkritik, Untersuchung auf Stimmigkeit, Quervergleich, Geo- und Chronolokation.

* [Detektoren-Übersicht 	in meinem Blog](https://www.janeggers.tech/ki-detektor-tools/). 	

# **`Schwierige Fragen: Datenschutz, Umwelt, Recht`** {#schwierige-fragen:-datenschutz,-umwelt,-recht}

## **Abhängigkeit von Tech-Riesen** {#abhängigkeit-von-tech-riesen}

Um ein generatives Modell zu erstellen, braucht man terabyteweise Daten \- und einen sehr, sehr mächtigen KI-Computer. So einen wie einen der beiden ganz neuen [KI-Supercluster von Facebook/Meta](https://ai.meta.com/blog/ai-rsc/), mit ihren je 24.000 NVIDIA-KI-Chips etwa 40x so groß sind wie die größten kommerziellen KI-Computer in Europa. Nur weil Meta sich leisten konnte, einen älteren Rechner mit “nur” 6.080 KI-Chips zwei Wochen rechnen zu lassen, und das Ergebnis dann praktisch zu verschenken, gibt es das “Llama”-Open-Source-Modell \- die Rechner der kommerziellen Konkurrenz bei OpenAI sind noch einige Male größer. Ein einzelner Trainingslauf eines großen Sprachmodells kostet etliche Millionen; GPT-4 zu trainieren [soll 100 Millionen Dollar gekostet haben](https://www.wired.com/story/openai-ceo-sam-altman-the-age-of-giant-ai-models-is-already-over/) \- einer der Gründe, weshalb praktisch alle führenden KI-Modelle von Tech-Konzernen erstellt worden sind.

Der Vorsprung der KI-Kommerz-Riesen auf Wissenschaft und Wettbewerb ist deutlich \- und damit unsere Abhängigkeit von ihrem Geschäftsgebaren. 

Dass wir ChatGPT in der Basisversion kostenlos nutzen können, kostet OpenAI und seinen Partner Microsoft ebenfalls Millionen \- dafür bekommen die KI-Riesen Zugriff auf einen Schatz: Millionen Nutzungs- und Trainingsdaten, die ihnen helfen, ihre Überlegenheit mit der nächsten Modellgeneration weiter auszubauen. 

## **Der Energieverbrauch von KI** {#der-energieverbrauch-von-ki}

KI ist ein Umweltproblem \- aufgrund des hohen Energieverbrauchs: Das erwähnte Llama2 von Meta etwa, ein vergleichsweise kleines Modell, hat 2023 bei seinem etwa zweiwöchigen Training 539 Tonnen CO2 verbraucht (was Meta dankenswerterweise publiziert hat); mehr als die Autos von 300 Berufspendlern in einem Jahr ausstoßen. 

Die Nutzung einer generativen KI ist dann jedesmal vergleichsweise sparsam \- aber für die Erzeugung eines Bildes mit Stable Diffusion ist immer noch so viel Energie nötig, dass man ein Telefon damit aufladen könnte. Zur Erzeugung von 1000 Worten benötigt man nur einen Teil davon, aber weil Millionen ChatGPT nutzen, summiert sich das: ein Forschungspapier stellt fest, [dass das meiste CO2 bei der Nutzung der Modelle entsteht](https://www.technologyreview.com/2023/12/01/1084189/making-an-image-with-generative-ai-uses-as-much-energy-as-charging-your-phone/?truid&utm_source=the_algorithm&utm_medium=email&utm_campaign=the_algorithm.unpaid.engagement&utm_content=12-05-2023&mc_cid=2cc05b263b). 

## **Klischees und Vorurteile** {#klischees-und-vorurteile}

Das Trainingsmaterial der Bildgeneratoren enthält zahlreiche Klischees \- gerade, weil so viele Stock-Fotografien eingeflossen sind. Die führt zu Schieflagen, wenn die Bildgeneratoren diese Klischees reproduzieren: Doktoren sind tendenziell männlich, Fastfood-Verkäufer weiblich. ([Bloomberg-Datenrecherche](https://www.bloomberg.com/graphics/2023-generative-ai-bias/)).

OpenAI hatte dieses Problem beim Bildgenerator Dall-E2 früh erkannt, und es einfach dadurch zu korrigieren versucht, dass bei einem Teil der Eingaben von einem Programm automatisiert ein Zusatz wie “weiblich” oder “Person of Color” angehängt wird. ([New Scientist](https://www.newscientist.com/article/2329690-ai-art-tool-dall-e-2-adds-black-or-female-to-some-image-prompts/))

## **Darf ich das? Ein wenig Rechtskunde** {#darf-ich-das?-ein-wenig-rechtskunde}

…mit der üblichen Vorsichtswarnung: Es kommt in der Juristerei extrem darauf an\! Zumal auf einem Rechtsgebiet, wo noch viel Unsicherheit herrscht, Hausjuristen deshalb tendenziell zur Vorsicht neigen \- und dann noch zsammengefasst von einem Jura-Laien.

* Interessante Eigenschaft von KI-generierten Inhalten: **Sie haben keinen Urheber.** Eine KI kann nicht Urheber sein, die Erzeugnisse sind also gemeinfrei.   
* Wenn ich einen KI-Bildgenerator nutze, binden mich allerdings die Nutzungsbedingungen des Anbieters.   
* Die **Trainingsdaten sind immer noch umstritten** \- sollte ein Gericht das Training für illegal erklären, droht im äußersten Fall eine Löschung des Modells, sowohl nach US- und deutschem Recht.   
  Anlass gäbe es genug: Sprachmodelle wie Metas “Llama2” sind unbestritten unter anderem mit raubkopierten Büchern trainiert worden \- ein Richter in den USA ließ aber einen ersten Versuch [scheiter](https://www.lto.de/recht/hintergruende/h/ki-kuenstliche-intelligenz-chatgpt-urheber-recht-verwerter/)n, schon die Nutzung der KI zur Urheberrechtsverletzung zu erklären.   
* Deutsche Rechtslage: Als **reiner Nutzer einer KI dürfte mir aber nichts drohen** \- Q: Prof. Philipp Hacker   
* Auch mit einem urheberrechtsfreien Erzeugnis aus einem legalen generativen KI-Modell **kann ich Rechte verletzen** \- Persönlichkeitsrechte, Markenrechte, bei zu großer Ähnlichkeit zu einem existierenden Werk auch Urheberrecht

Mehr hier: [LTO](https://www.lto.de/recht/hintergruende/h/ki-kuenstliche-intelligenz-chatgpt-urheber-recht-verwerter/)

## **Datenschutz** {#datenschutz}

ChatGPT lebt in der Cloud, was so viel heißt wie: Ich gebe meine Daten an einen reichen und mächtigen US-Konzern, damit er damit rechnet; im Vertrauen, dass er schon nichts Schlechtes damit anstellen wird. Das deutsche Datenschutzrecht teilt dieses Vertrauen nur sehr bedingt; personenbezogene Daten von Dritten darf man also bei ChatGPT nicht eingeben. Zumal sich OpenAI in der Kostenlos-Version vorbehält, alle Eingaben zum Training zu nutzen: wenn man Pech hat, kann die nächste ChatGPT-Version detailliert Auskunft geben, wie wir in unserem Unternehmen arbeiten \- weshalb es sich rät, mit Firmeninterna zurückhaltend zu sein.

Deshalb sind Open-Source-Modelle dann doch interessant \- auch wenn sie technisch mit GPT-4 nicht mithalten können, reichen sie völlig aus, wenn man etwa die Ergebnisse einer investigativen Recherche mit KI durchsuchen will und kein Byte nach außen dringen darf.


Hier ist jetzt ein rosa Dinosaurier versteckt: Das magische Wort ist Rosebud.   

# **`Linktipps:`**  {#linktipps:}

* Herzzerreißende, aber toll reportierte Geschichte: Wie ein junger Kanadier mit KI versuchte, seine tote Freundin wiederzubeleben. [Originalgeschichte im San Francisco Chronicle](https://www.sfchronicle.com/projects/2021/jessica-simulation-artificial-intelligence/); vertonte Übersetzung zum Nachhören: “[Die Jessica-Simulation](https://open.spotify.com/episode/1pucN00P75OMLdlcLqHtqN)” (For the record: “Project December” war ein Wrapper für ein feingetuntes GPT-3, der Personenbeschreibungen als Prompt nutzte und daraus Chats generierte. Je länger der Dialog wurde, desto mehr vom Kontextfenster brauchte das Prompt \- deshalb das ganz clevere Konzept mit der “Battery” für die Lebensenergie des Bots.)  
* “Mensch und Maschine”: Das WDR-Innovationsforschungs-Labor hat eine Vision in einen sehr lesenswerten Bericht gepackt. In dem sich auch ein Erfahrungsbericht über den Versuch der *Sportschau* mit einem KI-Sportreporter findet\! [https://zukunft.wdr.de/assets/pdf/WDR-Zukunftsreport\_MenschUndMaschine.pdf](https://zukunft.wdr.de/assets/pdf/WDR-Zukunftsreport_MenschUndMaschine.pdf)   
* “Haralds” Stoppwort? Kinderkram\! Bei “Gandalf” könnt ihr euch von Jailbreak-Level zu Level tasten. [https://gandalf.lakera.ai/](https://gandalf.lakera.ai/)   
* Spannender Vortrag des OpenAI-Mitbegründers Andrej Karpathy zum Training der KI-Sprachmodelle: [https://build.microsoft.com/en-US/sessions/db3f4859-cd30-4445-a0cd-553c3304f8e2](https://build.microsoft.com/en-US/sessions/db3f4859-cd30-4445-a0cd-553c3304f8e2)  
* Ganz eigennützig: Auf [janeggers.tech](https://janeggers.tech) blogge ich über meine Experimente \- über die [Zusammenfassung langer Texte](https://www.janeggers.tech/eeblog/2023/kann-ich-die-ki-fuer-mich-den-stuckrad-barre-lesen-lassen/), die [KI-Imitation eines “Bild”-Kolumnisten](https://www.janeggers.tech/eeblog/2023/ein-post-vom-ki-wagner-wie-ich-gpt-3-dazu-brachte-den-gossen-goethe-nachzumachen/), [unheimlich glaubwürdige Halluzinationen](https://www.janeggers.tech/eeblog/2023/das-pferd-des-herrn-von-osten-wenn-ki-dinge-kann-die-sie-gar-nicht-kann/), die [Vorurteile der KI-Bildgeneratoren](https://www.janeggers.tech/eeblog/2023/antrainierte-vorurteile-das-itler-bild-der-ki-hat-nen-bart/), und auch darüber, [wie der Satire-Chatbot “DeppGPT” vom *Postillon* funktioniert](https://www.janeggers.tech/eeblog/2023/kuenstliche-arroganz-wie-man-sich-deppgpt-baut/).

  # **`Newsletter und Podcasts`** {#newsletter-und-podcasts}

Ein paar Tipps, um bei generativer KI auf dem Laufenden zu bleiben

* [The Decoder](https://the-decoder.de/) ist ein Online-Magazin des Heise-Fachverlags, das sich auf KI-Neuigkeiten konzentriert; ich empfehle den wöchentlichen Newsletter.   
* [Last Week in AI](https://lastweekin.ai/) ist eigentlich ein Podcast einer auf KI spezialisierten Agentur, der begleitende Newsletter listet aber brav alle relevanten Links auf.   
* [Marcus on AI:](https://garymarcus.substack.com/) Gary Marcus ist ein Maschinenlern-Forscher, der vielen Entwicklungen eher skeptisch gegenübersteht \- ein gutes Gegengift gegen Hype-Highs.   
* Reddit ist eine gute Quelle \- [die News im Subreddit /r/ChatGPT](https://www.reddit.com/r/ChatGPT/?f=flair_name%3A%22News%20%F0%9F%93%B0%22) helfen, über alle Entwicklungen bei OpenAI und der Konkurrenz auf dem Laufenden zu bleiben.   
* Der [KI-Podcast](https://www.br.de/mediathek/podcast/der-ki-podcast/898) von BR und SWR ist gut gemacht, von Leuten, die echt etwas von KI verstehen, und macht Spaß.   
* [“KI \- und jetzt?”](https://www.ardaudiothek.de/sendung/ki-und-jetzt-wie-wir-kuenstliche-intelligenz-leben-wollen/12833245/) vom RBB ist ebenfalls sehr kompetent gemacht und etwas alltagsorientierter.

[^1]:  amerikanisch: “billion”, weshalb GPT3.5 auch gern als “175B”-Modell bezeichnet wird. Das aktuell leistungsfähigste Modell, GPT-o3, ist einiges größer, wir wissen aber nicht genau, wie groß, weil OpenAI das nicht verrät.

[^2]:  Ein wenig Vertrauen in Google muss man haben \- weil der Such-Gigant alles, was man hochlädt, auswerten wird, und weil Google schon häufiger Tools für Journalisten einfach irgendwann wieder abgeschaltet hat.

[image1]: <data:image/png;base64,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>