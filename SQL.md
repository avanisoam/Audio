SELECT Id, Name, Pronunciation, concat('**', Name ,'**') from DanishWord
where Pronunciation is null

UPDATE DanishWord
SET Pronunciation = concat('**', Name ,'**')
where Pronunciation is null

SELECT Id, Name, Pronunciation, concat('**', Name ,'**') from DanishWord
ORDER BY Name

SELECT Id, Name, Pronunciation, concat('**', Name ,'**') from DanishWord
WHERE Pronunciation NOT LIKE '%\*\*%'
ORDER BY Name

---

SELECT Id, Name, Pronunciation, concat('**', Name ,'**') from DanishWord
WHERE Pronunciation NOT LIKE '%\*\*%'
ORDER BY Name

SELECT Id, Name, Pronunciation, concat('**', Name ,'**') from DanishWord
WHERE Pronunciation NOT LIKE '%एअा%'
ORDER BY Name

UPDATE DanishWord
SET Pronunciation = 'वी'
where Id = 715

{
"Id": 0,
"Name": "-",
"Article": "string",
"Pronunciation": "-",
"GroupId": 0,
"OrderId": 0,
"Dk": "-",
"En": "-",
"Hi": "-",
"Scope": "",
"DanishWord_TypeId": 1,
"AddedOn": "2025-06-09T12:39:06.573Z"
}

{
"Id": 0,
"Name": "e-mailadresse",
"Article": "string",
"Pronunciation": "e-mailadresse",
"GroupId": 0,
"OrderId": 0,
"Dk": "e-mailadresse",
"En": "e-mailadresse",
"Hi": "e-mailadresse",
"Scope": "",
"DanishWord_TypeId": 1,
"AddedOn": "2025-06-09T12:39:06.573Z"
}

{
"Id": 0,
"Name": "make-up",
"Article": "string",
"Pronunciation": "मेखअप",
"GroupId": 0,
"OrderId": 0,
"Dk": "make-up",
"En": "make-up",
"Hi": "make-up",
"Scope": "",
"DanishWord_TypeId": 1,
"AddedOn": "2025-06-09T12:39:06.573Z"
}

{
"Id": 0,
"Name": "A-menneske",
"Article": "string",
"Pronunciation": "ऐ मैनिस्खा",
"GroupId": 0,
"OrderId": 0,
"Dk": "A-menneske",
"En": "A-menneske",
"Hi": "A-menneske",
"Scope": "",
"DanishWord_TypeId": 1,
"AddedOn": "2025-06-09T12:39:06.573Z"
}

{
"Id": 0,
"Name": "B-menneske",
"Article": "string",
"Pronunciation": "बी मैनिस्खा",
"GroupId": 0,
"OrderId": 0,
"Dk": "B-menneske",
"En": "B-menneske",
"Hi": "B-menneske",
"Scope": "",
"DanishWord_TypeId": 1,
"AddedOn": "2025-06-09T12:39:06.573Z"
}

{
"Id": 0,
"Name": "2-værelses",
"Article": "string",
"Pronunciation": "टूवैयलसैस",
"GroupId": 0,
"OrderId": 0,
"Dk": "2-værelses",
"En": "2-værelses",
"Hi": "2-værelses",
"Scope": "",
"DanishWord_TypeId": 1,
"AddedOn": "2025-06-09T12:39:06.573Z"
}

---

SELECT \* FROM DanishWord
WHERE Pronunciation = '**spansk**'

UPDATE DanishWord
SET Pronunciation = 'स्पैनश्क'
WHERE Id = 599
