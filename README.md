# Το Μουσείο του Λούβρου

Ως πολιτιστικό περιεχόμενο για την ιστοσελίδα επιλέχθηκε το Μουσείο του Λούβρου. Για να εισέρθετε στον ιστότοπο που έχει δημοσιευθεί στο web πατήστε [εδώ]().

## Φάκελοι

Οι φάκελοι/υποφακέλοι ταξινομήθηκαν και αντιστοιχήθηκαν ανάλογα με τη λειτουργία που πραγματοποιεί το κάθε αρχείο που βρίσκεται μέσα σε αυτά.

```
│   index.html
├───css
│       slider.css
│       style.css
│
├───html
│       aphrodite.html
│       ares_and_aphrodite.html
│       ...
│
├───images
│   │   aphrodite.jpg
│   │   ares_and_aphrodite.jpg
│   │   ...
│   │
│   └───slider
│           garden.jpg
│           inside_1.jpg
│           ...
│
├───js
│       language.js
│       myScript.js
│       ...
│
└───sounds
        aphrodite.mp3
        ares_and_aphrodite.mp3
        ...
```

- Στο **css** φάκελο, βρίσκονται αρχεία με επέκταση .css που αφορούν τη μορφοποίηση της ιστοσελίδας.
- Στο **html** φάκελο, βρίσκονται όλα τα αρχεία (εκθέματα, έργα τέχνης και επικοινωνία) που αφορούν τη χρήση εσωτερικών δεσμών για το navigation.
- Στο φάκελο **images**, βρίσκονται οι φωτογραφίες που χρησιμοποιήθηκαν ως πολυμέσο για την παρουσίαση μνημείων και έργων τέχνης.
- Στο φάκελο **js** βρίσκονται JavaScript αρχεία όπου εμπεριέχονται διάφορες συναρτήσεις για την αλλαγή της γλώσσας και του Slider.
- Στο **sounds** φάκελο, εμπεριέχονται διάφορες προσωπικές ηχογραφήσεις και χρησιμοποιούνται ως πολυμέσο για την προφορική περιγραφή των κειμένων που υπάρχουν στην ιστοσελίδα.
- Για την αρχική σελίδα χρησιμοποιήθηκε το προεπιλεγμένο όνομα αρχείου index.html όπου βρίσκεται το περιεχόμενο της αρχικής σελίδας.

Όπως ζητείται, γίνεται αναφορά και παραπομπή των πηγών που χρησιμοποιήθηκαν για τις πληροφορίες του μουσείου. Οι φωτογραφίες που αναρτήθηκαν είναι, τραβηγμένες από συγγενικά πρόσωπα και από το διαδίκτυο τηρώντας τις προδιαγραφές άδειας περιεχομένου *CC0* (Creative Commons zero).

## Αρχική

Mε τη βοήθεια της JavaScript και της μεθόδου **alert()** εμφανίζεται ένα πλαίσιο ειδοποίησης στον επισκέπτη κάθε φορά που μπαίνει στην αρχική σελίδα. Στο πλαίσιο αυτό αναφέρεται ο σκοπός της ιστοσελίδας για να επισημανθεί ότι δεν αποτελεί προϊόν εμπορικής χρήσης.

> Ο συγκεκριμένος ιστότοπος πραγματοποιήθηκε στα πλαίσια εξέτασης του μαθήματος Τεχνολογίες Διαδικτύου του Tμήματος Πολιτισμικής Τεχνολογίας & Επικοινωνίας. Το περιεχόμενο της ιστοσελίδας έχει άδεια περιεχομένου CC0 (Creative Commons zero) και δεν αποτελεί προϊόν εμπορικής χρήσης.

Το **navigation bar** αντιπροσωπεύει μία ενότητα που βρίσκεται στο πάνω μέρος της ιστοσελίδας. Στη συγκεκριμένη ιστοσελίδα ο χρήστης έχει την δυνατότητα πλοήγησης:

- Αρχική
- Εκθέματα
  - Αφροδίτη της Μήλου
  - Νίκη της Σαμοθράκης
  - Άρτεμις των Βερσαλλιών
- Έργα τέχνης
  - Μόνα Λίζα
  - Μάχη του Σαν Ρομάνο
  - Άρης και Αφροδίτη
- Επικοινωνία
- Πλαίσιο αναζήτησης
- Αλλαγή γλώσσας (Ελληνικά - Αγγλικά)

```html
<!-- Navigation -->
<nav class="w3-bar w3-black">
  <a id="el" href="#home" class="w3-button w3-bar-item"><i class="fa fa-home"></i> Αρχική</a>
  <a id="en" href="#home" class="w3-button w3-bar-item"><i class="fa fa-home"></i> Home</a>
  <div class="w3-dropdown-hover">
    <button class="w3-button">Εκθέματα</button>
  <div class="w3-dropdown-content w3-bar-block w3-card-4">
  <a id="el" href="html/aphrodite.html" class="w3-bar-item w3-button">Αφροδίτη της Μήλου</a>
```

Για την αλλαγή γλώσσας προσαρμόστηκαν 2 κουμπιά που βρίσκονται δεξιά στο navbar, ένα για την ελληνική και ένα για την αγγλική γλώσσα. Πατώντας ο επισκέπτης το κουμπί που αναγράφει **English** ο τίτλος της ιστοσελίδας, οι ενότητες/υποενότητες του *navbar* και τα κείμενα που βρίσκονται στην ιστοσελίδα μετατρέπονται στα αγγλικά. Αυτό πραγματοποιείται με τη βοήθεια της **JavaScript** (αρχείο: language.js), όπως φαίνεται παρακάτω:

```javascript
if(langueOn.innerHTML == 'Ελληνικά'){
        afficher(el_txt, nb_el);
        cacher(en_txt, nb_en);
        document.title="Μουσείο του Λούβρου"
        document.getElementById("sound").style.visibility="visible";
    }

    else if(langueOn.innerHTML == 'English'){
        afficher(en_txt, nb_en);
        cacher(el_txt, nb_el);
        document.title="Louvre Museum"
        document.getElementById("sound").style.visibility="hidden";
        document.getElementById('player').pause();
    }
```

Αντίθετα, πατώντας το κουμπί που αναγράφει **Ελληνικά**, όλα τα προαναφερόμενα μετατρέπονται στην ελληνική γλώσσα.

Όπως έγινε αναφορά προηγουμένως, για την αναπαραγωγή ήχου χρησιμοποιήθηκαν προσωπικές ηχογραφήσεις, που περιγράφουν όλα τα κείμενα (μόνο στην ελληνική γλώσσα) της ιστοσελίδας.

```html
<audio id="player" src="sounds/museum.mp3"></audio>
<div id="sound" class="w3-right">
  <a onclick="document.getElementById('player').play()"><i class='fa fa-volume-up fa-  50x'></i></a>
  <a onclick="document.getElementById('player').pause()"><i class="fa fa-pausefa-50x"></i></a>
</div>
```

Ο παραπάνω κώδικας, έχει ως σκοπό να εμφανίσει στην ιστοσελίδα, τα εικονίδια του **play** και του **pause** δεξιά από κάθε τίτλο. Πατώντας πάνω στα εικονίδια η ηχογράφηση παίζει και σταματάει αντίστοιχα. Η υλοποίηση αυτής της επιπλέον λειτουργίας έχει σαν σκοπό να βοηθήσει άτομα με προβλήματα όρασης.

Σε περίπτωση που ο επισκέπτης επιλέξει την **αγγλική γλώσσα** τα εικονίδια του play και του pause εξαφανίζονται.

Για το **Slider** χρησιμοποιήθηκαν πέντε φωτογραφίες εκ των οποίων κάποιες απεικονίζουν το εξωτερικό μέρος και κάποιες άλλες το εσωτερικό μέρος του μουσείου. Η παρουσίαση των εικόνων γίνεται **μόνο** στην αρχική σελίδα.

Η αλλαγή της εικόνας πραγματοποιείται ανά 5 δευτερόλεπτα και αυτό οφείλεται διότι έχει προγραμματιστεί με **JavaScript** (αρχείο: slider.js) όπως φαίνεται παρακάτω.

```javascript
setTimeout(changeSlide, 5000);
```

Τα tags `<footer>...</footer>` ορίζουν ένα υποσέλιδο. Στο footer της ιστοσελίδας περιέχονται:

- Σχετικά εικονίδια των social media
- Αναφορά στο φορέα του template
- Αναφορά στον διασκευαστή
- Πληροφορίες πνευματικών δικαιωμάτων

```html
<footer class="w3-container w3-padding-64 w3-center w3-black w3-xlarge"><a href="https://el-gr.facebook.com/museedulouvre/" target="_blank"><i class="fa fa-facebook-official"></i></a>
```

Κάνοντας κλικ πάνω στα εικονίδια, ανοίγει νέο παράθυρο στο αντίστοιχο μέσο επικοινωνίας που αφορά το μουσείο.

## Head tags

H πρώτη ενότητα μιας HTML σελίδας είναι τα head tags, τα οποία αποτελούν τον πρόλογο για την HTML σελίδα, δηλαδή παρέχουν πληροφορίες στον Βrowser.

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Aρχική Σελίδα</title>
    <link rel="icon" href="images/logo.ico" type="image/Iconic">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css">
    <link rel="stylesheet" type="text/css" href="css/style.css"/>
    <link rel="stylesheet" type="text/css" href="css/slider.css"/>
    <script src="js/myScript.js"></script>
    <script src="js/language.js"></script>
    <script src="js/slider.js"></script>
    <script src="js/search.js"></script>
</head>
```

Το charset καθορίζει την κωδικοποίηση χαρακτήρων για το έγγραφο HTML. Ενώ UTF-8, χρειάζεται διότι καλύπτει σχεδόν όλους τους χαρακτήρες και τα σύμβολα στον κόσμο.

```html
<meta charset="UTF-8">
```

Η παρακάτω μέθοδος χρησιμοποιείται για να μην υπάρχει στατικός σχεδιασμός και σταθερό μέγεθος και να προσαρμόζεται ανάλογα τη συσκευή (κινητό, tablet).

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

Ορισμός για τον τίτλο της ιστοσελίδας. Αλλάζει ανάλογα με τη στιγμιαία σελίδα, με τη βοήθεια του navbar.

```html
<title>Αρχική σελίδα</title>
```

Όρισμα του εικονιδίου της ιστοσελίδας (favicon). Στην ιστοσελίδα χρησιμοποιήθηκε ως εικονίδιο ένα μουσείο.

```html
<link rel="icon" href="images/logo.ico" type="image/Iconic">
```

Χρησιμοποίηση βιβλιοθήκης ανοιχτού κώδικα από το **cdnjs.cloudflare.com**.

```html
<link rel="styleheet" href="https://cdnjs.cloudflare.com/ajax/libs/font- awesome/4.6.3/css/font-awesome.min.css">
```

Δήλωση εξωτερικών συνδέσμων για τα css αρχεία με όνομα style και slider.

```html
<link rel="styleheet" type="text/css" href="css/style.css">
<link rel="styleheet" type="text/css" href="css/slider.css">
```

Δήλωση εξωτερικών συνδέσμων για JavaScript αρχεία με όνομα MyScript, language, slider και search.

```html
<script src="js/MyScript.js"></script> 
<script src="js/language.js"></script> 
<script src="js/slider"></script> 
<script src="js/search"></script> 
```

## Body tags

Η δεύτερη ενότητα μιας HTML σελίδας ονομάζεται body και ορίζεται με το ανοιχτό tag <body> και την κλειστό tag </body>. Το ζευγάρι των tags <body>...</body> ορίζουν το κυρίως περιεχόμενο της σελίδας, περιέχουν όλα τα περιεχόμενα ενός εγγράφου HTML, όπως επικεφαλίδες, παραγράφους, εικόνες, υπερσυνδέσμους, πίνακες, λίστες κ.λπ.

## Οδηγίες για Συνεισφορά

Σε περίπτωση που έχεις απορίες για την συνεισφορά, μπορείς να δημιουργήσεις [issue](https://github.com/Effie375/louvre-museum/issues/new).
