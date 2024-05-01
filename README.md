<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Platres 3on3 Basketball Tournament</title>
    <script>
        function translateTo(language) {
            var elements = document.querySelectorAll('[data-translate]');
            elements.forEach(function(element) {
                var key = element.getAttribute('data-translate');
                if (translations[key] && translations[key][language]) {
                    element.innerText = translations[key][language];
                }
            });
        }

        var translations = {
            "tournament_title": {
                "en": "Platres 3on3 Basketball Tournament",
                "el": "Πρωτάθλημα Καλαθοσφαίρισης Platres 3on3"
            },
            "date": {
                "en": "Date: 2nd June 2024",
                "el": "Ημερομηνία: 2 Ιουνίου 2024"
            },
            "location": {
                "en": "Location: <a href='https://platresarena.com/'>Platres Arena</a>, Platres.",
                "el": "Τοποθεσία: <a href='https://platresarena.com/'>Αρένα Πλατρών</a>, Πλάτρες."
            },
            "description": {
                "en": "After a successful season, the Platres 3on3 returns to the Upper Platres court for another event, with the main goal of supporting the Small Heroes Foundation and Europa Donna Cyprus, two non-profit organizations providing assistance and support to children fighting leukemia, as well as to women and men battling breast cancer.",
                "el": "Μετά από μια επιτυχημένη χρονιά, το Platres 3on3 επιστρέφει στο γήπεδο των Πάνω Πλατρών για μια ακόμη διοργάνωση, με κύριο στόχο την υποστήριξη του Ιδρύματος Μικροί Ήρωες και του Europa Donna Cyprus, δύο μη κερδοσκοπικών οργανισμών οι οποίοι παρέχουν βοήθεια και στήριξη σε παιδιά τα οποία παλεύουν με την λευχαιμία, σε γυναίκες και άντρες οι οποίοι αγωνίζονται κατά του καρκίνου του μαστού."
            },
            "initiative": {
                "en": "This initiative is led by a small team of young volunteers who, with enthusiasm, dedication, and determination, have embarked on this noble effort. Their aim is to provide an opportunity for both young and old basketball enthusiasts to actively support the efforts of our fellow citizens against cancer, and to showcase that youth can be pillars in the long-term and altruistic endeavors of these organizations.",
                "el": "Η πρωτοβουλία αυτή ηγείται από μικρή ομάδα νέων εθελοντών, οι οποίοι, με ενθουσιασμό, αφοσίωση και δυναμισμό, ξεκίνησαν αυτή την άοκνη προσπάθεια. Στόχος τους είναι αφενός να δώσουν την ευκαιρία σε μικρούς και μεγάλους φίλους της καθαλόσφαιρας να στηρίξουν έπρακτα την προσπάθεια των συνανθρώπων μας κατά του καρκίνου και αφετέρου να αναδείξουν ότι οι νέοι μπορούν να αποτελέσουν στηλοβάτες στην μακροχρόνια και αλτρουιστική προσπάθεια αυτών των οργανισμών."
            },
            "registration_dates": {
                "en": "Registrations will be open from May 1st to May 29th, 2024, through the link: <a href='https://forms.office.com/r/NkmdV3gJKs?origin=lprLink'>here</a>.",
                "el": "Οι εγγραφές θα είναι ανοικτές από 1 Μαίου έως 29 Μαΐου 2024 μέσω του συνδέσμου <a href='https://forms.office.com/r/NkmdV3gJKs?origin=lprLink'>εδώ</a>."
            },
            "registration_cost": {
                "en": "The registration cost for a team is €140 (for 4 people) which will cover:",
                "el": "Το κόστος εγγραφής για μια ομάδα είναι €140 (για 4 άτομα) και περιλαμβάνει:"
            },
            "registration_details": {
                "en": "<ul><li>Registration for the Platres 3on3 Basketball Tournament.</li><li>Double-sided basketball jersey.</li><li>Monetary contribution to the two organizations.</li></ul>",
                "el": "<ul><li>Εγγραφή στο Platres 3on3 Basketball Tournament.</li><li>Διπλής όψης καλαθοσφαιρική στολή.</li><li>Χρηματική συνεισφορά στους δύο οργανισμούς.</li></ul>"
            },
            "event_division": {
                "en": "Event Division:",
                "el": "Διαίρεση Αγώνων:"
            },
            "men": {
                "en": "Men",
                "el": "Άντρες"
            },
            "women": {
                "en": "Women",
                "el": "Γυναίκες"
            },
            "mixed": {
                "en": "Mixed",
                "el": "Μεικτό"
            },
            "more_info": {
                "en": "For more information:",
                "el": "Για περισσότερες πληροφορίες:"
            }
        };
    </script>
</head>
<body>
    <button onclick="translateTo('en')">English</button>
    <button onclick="translateTo('el')">Ελληνικά</button>
    <h1 data-translate="tournament_title">Platres 3on3 Basketball Tournament</h1>
    <ul>
        <li data-translate="date">Date: 2nd June 2024.</li>
        <li data-translate="location">Location: <a href="https://platresarena.com/">Platres Arena</a>, Platres.</li>
    </ul>
    <p data-translate="description"></p>
    <p data-translate="initiative"></p>
    <h5 data-translate="registration_dates"></h5>
    <h5 data-translate="registration_cost"></h5>
    <p data-translate="registration_details"></p>
    <h5 data-translate="event_division"></h5>
    <ul>
        <li data-translate="men"></li> 
        <li data-translate="women"></li>
        <li data-translate="mixed"></li>        
    </ul>
    <h5 data-translate="more_info"></h5>
    <p class="hidden">
        Email: <a href="mailto:platres3on3@outlook.com">platres3on3@outlook.com</a> <br>
        Phone:  99909580 / 99342037 <br>
        Instagram : <a href="https://www.instagram.com/platres3on3/?igsh=ZTFxa2R1MnJ0NGlk&utm_source=qr">platres3on3</a>
    </p>   
</body>
</html>
