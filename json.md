# JSON
Aapne dictionaries ke baarei mei padha hoga. Dictionaries ka use karke hum kisi bhi information ko asaan tareeke se represent kar sakte hai.

Dictionaries use kar ke jab hum koi data do machines ke beech mei exchange karte hai, toh hum JSON use karte hai. Iski full form "JavaScript Object Notation" hai. Iska matlab, Javascript mei kisi bhi object ko kaise note ya represent karte hai, yaani likhte hai. 

Aap yeh samjhiye, ki jab mai kuch data kisi machine se kisi aur machine par bhej raha hu toh uske liye mujhe koi string pass karni hogi. Isliye halaki dictionaries kaafi complex ho sakti hai, JSON mei sirf woh information jaati hai jo Javascript string mei convert kar paata hai.

Jaise yeh dekho:

```javascript
marks_dict = {
  "shivam": 15,
  "abhishek": 30,
  "rahul" : 25,
  "garima": 40
};

json_string = JSON.stringify(marks_dict)

console.log(json_string)

// Aap iss JSON string se JSON object bhi aasaani se nikal sakte hai.

json_object = JSON.parse(json_string)

```