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

---

SELECT \* FROM DanishWord
WHERE Pronunciation = '**spansk**'

UPDATE DanishWord
SET Pronunciation = 'स्पैनश्क'
WHERE Id = 599
