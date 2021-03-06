## Επικοινωνία Ανθρώπου-Υπολογιστή Τελική αναφορά
### Ονοματεπώνυμο: Δημήτρης Μισαηλίδης
### Αριθμός Μητρώου: Π2017066
### Εργασία Ανάπτυξης: Οπτικοποίηση δεδομένων εκπαιδευτικού συστήματος (USA) Τελική αναφορά

Η παρακάτω αναφορά αποτελεί την τελική αναφορά για την εργασία ανάπτυξης Data Visualization στο μάθημα της Επικοινωνίας ανθρώπου-υπολογιστή. Περιέχει αναλυτική περιγραφή των έργων, των εργαλείων καθώς και του τρόπου και της τεχνικής ανάπτυξης του κάθε παραδοτέου. Ακόμη, εμπεριέχει gifs και ενδεικτικά της δουλειάς που έγινε. Τέλος, παραθέτονται τα συμπεράσματα της εργασίας και φυσικά η βιβλιογραφία και οι σύνδεσμοι οι οποίοι χρησιμοποιήθηκαν για την κατανόηση και την ανάπτυξη των παραδοτέων.
#### [Εκτλεσιμο λινκ](https://dmisa.github.io/D3js-US-educational-attainment/)
#### [Προφιλ στο github](https://github.com/dmisa)
#### [Λινκ αποθετηρίου εργασίας](https://github.com/dmisa/D3js-US-educational-attainment/tree/gh-pages)
#### [Λινκ αποθετηρίου τελικής αναφοράς](https://github.com/dmisa/HCI-Final-Report)

## Εισαγωγή
Υλοποίησα όλα τα ζητούμενα του πρώτου παραδοτέου, καθώς και το πρώτο και το τρίτο ζητούμενο του δεύτερου παραδοτέου. Τα προβλήματα που αντιμετώπισα είναι ότι δεν κατάφερα να κάνω responsive όλα τα γραφήματα και δεν άλλαξα τα γραφήματα με άλλα στο 2ο παραδοτέο. Τα υπόλοιπα ζητούμενα υλοποιήθηκαν χωρίς ιδιαίτερα προβλήματα.
## Σύντομη ανάλυση σχετικών έργων και εργαλείων
Επειδή τα github pages είναι σχετικά αργά και οι αλλαγές δεν φαίνονται αμέσως, έγινε κατέβασμα του φακέλου της εργασίας και οι αλλαγές έγιναν offline μέσω notepad++ και του browser και έπειτα ανέβασμα στο github. Για το 2ο παραδοτέο, έγινε χρήση του codepen για την εύρεση και την κατανόηση των d3.js γραφημάτων, αφού χρησιμοποιήθηκαν εργασίες οι οποίες εξατομοικεύτηκαν για την επίτευξη του 3ου ζητήματος. Ακόμη, στο πρώτο παραδοτέο χρησιμοποιήθηκε η βιβλιοθήκη responsivevoice η οποία βοήθησε στο text to speech.

## Μέθοδος και τεχνικές ανάπτυξης
Η μέθοδος η οποία ακολούθησα για την υλοποίηση των 2 παραδοτέων της εργασίας ανάπτυξης ήταν η εξής:
* Αναζήτηση στον ιστό σχετικά με html javascript css, εκμάθηση των βασικών στοιχείων κάθε γλώσσας και έπειτα έρευνα σχετική με τα ζητούμενα του κάθε παραδοτέου. 

* Πιο αναλυτικά, στην αλλαγή των χρωμάτων έψαξα τα γραφήματα στα αρχεία js για χρώματα, και μετά απο την αλλαγή του καθενός λύθηκε το αρχικό πρόβλημα.

* Για τις διεπαφές, στο css αρχείο άλλαξα το layout, τα χρώματα και τα περιγράμματα όλων των κουμπιών

* Μετά απο αναζήτηση στο google έμαθα πως να βάζω ήχο στο mouseover του κάθε κουμπιού περιήγησης (αλλαγές στο html αρχείο). 

* Για το text-to-speech χρησιμοποίησα το responsive voice τοποθετώντας το σε κάθε κείμενο της σελίδας στο html αρχείο μέσω της js. 

* Για το responsive design χρησιμοποίησα ένα dropdown menu όταν η οθόνη προβολής δεν ήταν επαρκής (αλλαγές στο html και css αρχείο).

* Για την εμφάνιση-απόκρυψη του κάθε γραφήματος έγινε χρήση μιας συνάρτησης javascript η οποία εντάχθηκε στο html αρχείο

* Για την νέα σελίδα, πρόσθεσα ένα κουμπί στην αρχική σελίδα (index.html) η οποία οδηγούσε στο index2.html(την σελίδα με τα νέα γραφήματα). Έπειτα, βρήκα στατιστικά στοιχεία ( 2 από ΕΛΣΤΑΤ, 1 από Eurostat) καθώς και υλοποιήσεις γραφημάτων d3.js στο codepen. Συνδιάζοντας τα δεδομένα των στατιστικών στοιχείων με τα γραφήματα δημιούργησα την νέα σελίδα.(Τροποποιήσεις και στο css αρχικό αρχείο)

## Aποτελέσματα με λεζάντες σε ενδεικτικές οθόνες και animated gif, συμπεράσματα
### 1ο Παραδοτέο
[pull request](https://github.com/courses-ionio/hci/pull/707)
- [x] Αλλάξτε τα χρώματα στα 3 γραφήματα. 
![αλλαγή χρωμάτων](/color1.jpg)
- [x] Αντικαταστήστε τις διεπαφές στα "κουμπιά" του 2ου και 3ου γραφήματος με άλλες της επιλογής σας. 
![αλλαγή κουμπιων](/color2.jpg)
- [x] Όταν το ποντίκι διέρχεται επάνω από κάθε επιλογή του menu στην κορυφή της σελίδας, να ακούγεται κάποιος ήχος της επιλογής σας. 
- [x] Όταν το ποντίκι διέρχεται πάνω από κάποια πρόταση/κείμενο της σελίδας ή περιοχή που περιλαμβάνει γραπτή πληροφορία (π.χ. κάποιο τμήμα γραφήματος), να ακούγεται αυτόματα η αφήγηση του κειμένου (text-to-speech). 
- [x] Εφαρμόστε responsive design στη σελίδα και κυρίως στο αρχικό menu έτσι ώστε να προσαρμόζεται σε οθόνες διαφορετικών διαστάσεων (π.χ. Bootstrap).
![responsive](/responsive.gif)

### 2ο Παραδοτέο
- [x] Τροποποιήστε τον κώδικα και το μενού της εφαρμογής έτσι ώστε κάθε στιγμή να είναι εμφανές μόνο ένα από τα 3 γραφήματα, παραμένοντας πάντα στη σελίδα index.html. 
![2.1](/2.1.gif)
- [ ] Αντικαταστήστε το κάθε ένα από τα 3 γραφήματα με κάποιο άλλο διαδραστικό γράφημα της D3js. (Δέν έγινε)
- [x] Σε μια καινούργια σελίδα, να τοποθετήσετε αντίστοιχα 3 νέα διαδραστικά γραφήματα D3js της επιλογής σας, τα οποία θα οπτικοποιούν καινούργια στατιστικά δεδομένα που θα βρείτε από κάποια επίσημη στατιστική αρχή (π.χ. ΕΛΣΤΑΤ, Eurostat κ.λπ.).
![2.3](/2.3.gif)

Τα συμπεράσματα μου από την εργασία είναι ότι η html,javascript και css είναι πολύ ενδιαφέρουσες γλώσσες προγραμματισμού και ήταν ευχάριστη η ενασχόληση με αυτές. Επίσης τα d3 γραφήματα χρησιμοποιούνται ευραίως. Συνεπώς, η εργασία ήταν ενδιαφέρουσα και με έκανε να βελτιώσω τις γνώσεις μου για την επίτευξή της. Λόγω έλλειψης χρόνου δεν υλοποίησα το 2ο ζητούμενο του 2ου παραδοτέου.

## Βιβλιογραφία και συνδέσμους σε σχετικές εργασίες

Χρησιμοποιώντας το google ως κύρια μέθοδο πληροφόρησης η βιβλιογραφία-links τα οποία βοήθησαν είναι τα παρακάτω:

* [line chart](https://codepen.io/Yurchenko/pen/dGQZay)
* [pie chart](https://codepen.io/chiranjeeb/pen/KdXGoE)
* [bar chart](https://codepen.io/vks9009/pen/rWPaXz)
* [ΑΠΟΤΕΛΕΣΜΑΤΑ ΕΡΕΥΝΑΣ ΟΠΩΡΟΦΟΡΩΝ: Έτος 2017](http://www.statistics.gr/el/statistics?p_p_id=documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN&p_p_lifecycle=2&p_p_state=normal&p_p_mode=view&p_p_cacheability=cacheLevelPage&p_p_col_id=column-2&p_p_col_count=4&p_p_col_pos=1&_documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN_javax.faces.resource=document&_documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN_ln=downloadResources&_documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN_documentID=344529&_documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN_locale=el)
* [Ακαθάριστο εγχώριο προϊόν (2η εκτίμηση) (1995 - 2017)](http://www.statistics.gr/el/statistics/-/publication/SEL15/-)
* [1 in 4 deaths in the EU are due to cancer](https://ec.europa.eu/eurostat/web/products-eurostat-news/-/DDN-20181122-1?inheritRedirect=true&redirect=%2Feurostat%2Fnews%2Fwhats-new)
* [responsive voice](https://responsivevoice.org/)
* [stack overflow](https://stackoverflow.com/)
* [d3 github](https://github.com/d3/d3/wiki/Gallery)

* Η εργασία βασίστηκε στον [κώδικα της αρχικής εργασίας](https://github.com/ioniodi/D3js-US-educational-attainment).
