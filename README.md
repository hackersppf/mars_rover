
# Mars Rover
Η ομάδα μας αποτελείται από μαθητές και μαθήτριες του Ομίλου "Ταξίδι στο Διάστημα" ο οποίος λειτουργεί στο 5ο Δημοτικό Σχολείο Φλώρινας "Θεόδωρος Κάστανος" κατά το σχολικό έτος 2023-2024. Οι μαθητές και οι μαθήτριες του ομίλου είναι από τρία διαφορετικά σχολεία της πόλης μας και φοιτούν στις Δ, Ε και ΣΤ τάξεις του Δημοτικού. Το θέμα του ομίλου μας είναι ο εποικισμός του Άρη και το εξετάζουμε μέσα από διαφορετικές οπτικές (μεταφορά ανθρώπων, πρώτων υλών και μηχανών στον πλανήτη από την Γη, δημιουργία σταθμών διατήρησης της ζωής, πρώτες ύλες από τον Άρη, δημιουργία μιας νέα κοινωνίας κλπ) και μέσα από διαφορετικές εκπαιδευτικές τεχνολογίες (3Δ σχεδίαση και εκτύπωση, εκπαιδευτική ρομποτική, προγραμματισμός σε Scratch).
# Αναλυτική περιγραφή ιδέας
Ένα από τα στοιχεία τα οποία θα εξετάσουμε στον όμιλο μας είναι η εξερεύνηση του πλανήτη με αυτόνομα ρομπότ τα οποία θα αξιοποιούν τεχνολογίες τεχνητής νοημοσύνης για να λαμβάνουν αποφάσεις χωρίς τον άμεσο έλεγχο από ανθρώπους. Ήδη τέτοιες τεχνολογίες αξιοποιούνται από τα ρομπότ της NASA και ειδικότερα την πιο πρόσφατη αποστολή του Perseverence για την αποφυγή εμποδίων κατά την διάρκεια της πλοήγησης στην επιφάνεια του Άρη και για την εξέταση δεδομένων τα οποία λαμβάνονται από τα πετρώματα. 

Σκοπός μας είναι να δημιουργήσουμε ένα Mars Rover το οποίο να χρησιμοποιεί τεχνητή νοημοσύνη αξιοποιώντας μια κάμερα η οποία θα είναι τοποθετημένη σε αυτό για: 

 - να καθορίζει την πορεία του σε αποστολές εξερεύνησης αναγνωρίζοντας ενδιαφέροντα πετρώματα και σχηματισμούς στα οποία θα πρέπει να πηγαίνει. 
 - την αποφυγή εμποδίων
 - την μεταφορά δειγμάτων πίσω στον σταθμό βάσης

Το rover θα επικοινωνεί ασύρματα με τον σταθμό βάσης ενημερώνοντας τον για την πορεία της εξερεύνησης και των δεδομένων που έχει συλλέξει.

Ήδη έχουμε κατασκευάσει μια μακέτα η οποία αποτελεί την επιφάνεια του πλανήτη Άρη με την χρήση φελιζόλ τα οποία μορφοποιήσαμε με ένα πιστόλι θερμού αέρα και τα βάψαμε. Στην παρακάτω εικόνα φαίνεται η μακέτα με ένα απλό μοντέλο με τουβλάκια Lego που έχουμε κάνει για το rover.

![enter image description here](https://github.com/hackersppf/mars_rover/blob/main/fotos/lego%20rover.png?raw=true)

Επίσης έχουμε ήδη κάνει διάφορα σχέδια για τον σταθμό βάσης στο TinkerCAD όπως αυτό που φαίνεται στην παρακάτω εικόνα

![enter image description here](https://github.com/hackersppf/mars_rover/blob/main/fotos/base%20by%20jason.png?raw=true)

Για την κατασκευή του rover θα αξιοποιήσουμε 3Δ σχέδια τα οποία προσφέρονται ελεύθερα από την πλατφόρμα Thingiverse τα οποία θα τροποποιήσουμε με το TinkerCAD ώστε να ταιριάζουν στις λειτουργίες που θέλουμε να εκτελεί το rover. Ως βάση θα χρησιμοποιήσουμε το σχέδιο [SMARS modular robot](https://www.thingiverse.com/thing:2662828) το οποίο είναι ιδιαίτερα δημοφιλές και υπάρχουν πολλά remixes για χρήση αισθητήρων και άλλων μικροελεγκτών. Οι εκτυπώσεις θα γίνουν στον 3Δ εκτυπωτή του σχολείου μας με την χρήση υλικών PLA και TPU. 

Ως κεντρική πλατφόρμα ανάπτυξης θα αξιοποιήσουμε το Microbit και για τον έλεγχο του Rover αλλά και για τον σταθμό βάσης. Τα microbit θα επικοινωνούν μεταξύ τους ασύρματα, ενώ στο rover θα υπάρχει και μια κάμερα HuskyLens η οποία θα αναλαμβάνει:

 - την αναγνώριση αντικειμένων και το objcet tracking
 - την αναγνώριση χρωμάτων
 - την αναγνώριση tags στον σταθμό βάσης

# Eκπαιδευτικοί στόχοι του έργου
Οι βασικοί εκπαιδευτικοί στόχοι του έργου μας είναι οι μαθητές να:
 - Μελετήσουν διάφορες πτυχές για την εξερεύνηση του διαστήματος,
 - ενισχύσουν τις γνώσεις τους σχετικά με το διάστημα και την προσπάθεια του ανθρώπου να ιδρύσει αποικίες στον Άρη
 - αποκτήσουν δεξιότητες 3Δ σχεδίασης με την χρήση απλών προγραμμάτων
 - αποκτήσουν δεξιότητες χρήσης του 3Δ εκτυπωτή του εργαστηρίου
 - αποκτήσουν δεξιότητες προγραμματισμού και αξιοποίησης τεχνολογιών όπως η τεχνητή νοημοσύνη με την χρήση ενός απλού περιβάλλοντος ανάπτυξης όπως το BBC Microbit
 - κατανοήσουν τους τρόπους με τους οποίους η τεχνητή νοημοσύνη αξιοποιείτε σε τομείς που αφορούν το διάστημα.
# Λίστα προτεινόμενου εξοπλισμού
 - [PLA Fillament](https://grobotronics.com/creality-cr-pla-filament-1.75mm-1kg-grey.html) 2kg σε διαφορετικά χρώματα, κόστος 32 ευρώ
 - [TPU Fillament](https://grobotronics.com/3d-printer-filament-devil-tpu-1.75mm-white-1kg.html) 1kg, κόστος 34 ευρώ
 - [Microbit V2](https://grobotronics.com/bbc-micro-bit-v2-board.html) (X2), κόστος 32 ευρώ
 - [ZIP Halo for the BBC micro:bit](https://grobotronics.com/zip-halo-for-the-bbc-micro-bit.html) για τον σταθμό βάσης, κόστος 12 ευρώ
 - [Gravity HUSKYLENS](https://grobotronics.com/gravity-huskylens-an-easy-to-use-ai-machine-vision-sensor.html), κόστος 56 ευρώ
 - [micro:Driver - Driver Expansion Board](https://grobotronics.com/micro-driver-driver-expansion-board.html), κόστος 10 ευρώ
 - [Micro Metal Gearmotor](https://grobotronics.com/micro-metal-gearmotor-200rpm-12v.html) - 200RPM (X4), κόστος 24 ευρώ
 - [Μπαταριοθήκη 3xAA](https://grobotronics.com/battery-holder-3xaa-with-jst-ph-no-cover.html) - με JST PH, κόστος 0,70 ευρώ
 - [Κλιπ Μπαταρίας 9V](https://grobotronics.com/battery-clip-9v-wires.html) με Καλώδια, κόστος 0,16 ευρώ
 - Μπαταρίες 9V (X4), κόστος 5 ευρώ
 - Μπαταρίες ΑΑ (Χ6), κόστος 1,2 ευρώ
 - [Κατσαβίδια Ακριβείας Set](https://grobotronics.com/katsabidia-akribeias-set-6tmkh.-8pk-509.html), κόστος 5 ευρώ
 - Σετ βίδες Μ2 και Μ3, κόστος 6 ευρώ

**Συνολικό κόστος: 218 ευρώ**
# Υπεύθυνοι εκπαιδευτικοί

 - [Γιάννης Αρβανιτάκης](https://ioarvanit.gr/)
 - Κώστας Μπάτζιος
