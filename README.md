# eSignature Platform

`1.0.0`: [
    - the client can easily read and sign their contract directly on the platform;
    - an e-mail is send to the each part (client and provider) with the PDF contract file;
    - GDPR information has been added to the contract;
    - each page has footer with the signature;
    - good pagination of the contract;
    - if `overview.php` is accessed from phone, the contract will be automatically downloaded as a PDF file;
    - using a Custom Attribute, the client can sign the contract only once;
    - useless functions `retrieveCurrentUser` and `curlQuery` have been removed from `main.php`;
    - a ticket is created after signing the contract to save the contract on the platform, in case the client delets the email;
    - the bug where the IDs of Custom Attributes were wrong has been solved #2.

    TODO: [
        - re-write the plugin using the last version of Laravel.
    ]
]

`1.0.0`: [
    - acum clientul poate citi si semna contractul direct de pe platforma;
    - cate un e-mail este trimis fiecarei parti (client & provider) cu fisierul .pdf al contractului semnat;
    - informatiile GDPR au fost adaugate contractului;
    - fiecare pagina are footer cu semnatura;
    - contractul are acum o buna paginare;
    - daca `overview.php` este accesat de pe telefon sau tableta, contractul va fi descarcat automat;
    - folosind un Custom Attribute, clientul poate semna o singura data contractul;
    - functiile nefolositoare `retreieveCurrentUser` si `curlQuery` au fost sterse din `main.php`;
    - un tichet este creat dupa semnarea contractului ce contine ca si atasament fisierul .pdf semnat al contractului;
    - bugul in care ID-urile atributelor erau gresite a fost rezolvat pentru #2.

    TODO: [
    - de rescris plugin-ul folosind ultima versiune Laravel.
    ]
]