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
]
