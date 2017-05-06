# Dictionaries
Dictionary mei hum kisi bhi word ka meaning dhoondh paate hai.

# Activity
“Computer” word ka meaning ek printed dictionary (computer par nahi, balki kisi dictionary se jo paper par printed ho) mei dhoondh kar dekhiye.

Dictionary ka kaafi asaan sa kaam hai. Jo bhi word do, woh uska meaning deta hai. Isse aisa socho ki ek darwaza hai, jisme jab koi chaabi bharo, toh koi jawaab milta hai. Alag alag chaabi se, alag alag jawaab. Alag alag key se alag alag value. Aise data type ko hum dictionary kehte hai. 

## Ek example se dekhte hai:

Maanlo hum ek dictionary define karte hai jiski key student ka naam hai, aur woh key daalne se, uske marks milte hai. Uss dictionary ko hum aise define karenge.

```javascript
// marks ki dictionary, jismei student ke naam ke saamne unke marks stored hai
marks_dict = {
  "shivam": 15,
  "abhishek": 30,
  "rahul" : 25,
  "garima": 40
};
```

Maan lo ab humein iss dictionary mei se abhishek ke marks dekhne hai, toh hum aisa kuch karenge
- Abhishek ke marks dekhne ke liye, pehle abhishek naam ki key define karo
- marks_dict mei se "abhishek" key ki value nikalo, aur marks naam ke variable mei store kar do
- marks variable ko ab aap kahi bhi use kar sakte ho

```javascript
key = "abhishek";
marks = marks_dict["abhishek"];
console.log("abhishek ke marks hai", marks)
```

Ya phir siddha isse aise bhi kar sakte hai. shivam ko key ki tarah dictionary mei daalkar, woh value nikaal do
```javascript
marks = marks_dict["shivam"]
console.log("Shivam ke marks hai", marks_dict["shivam"]);
```


Javascript mei dictionary ki key ke liye, . (dot) ka bhi use kar sakte hai
```javascript
console.log("Rahul ke marks hai", marks_dict.rahul);
```

Isse bhi same output aayega.
Yaani marks_dict mei se "rahul" key wali, value mil jayegi.

## Kuch Dhyaan Rakhne Wali Baatein
- Dictionary aur functions alag hote hai. But ek dictionary ko loosely ek function tarah socha ja sakta hai, jo kuch keys ke liye, kuch specific values deta hai. Function mei argument dene ke liye round brackets (yaani ()) use hoti hai, par dictionary mei square brackets (yaani []) use hoti hai. Functions mei kitne bhi argument diye ja sakte hai, par dictionary mei ek hi key ja sakti hai.

- Ek khaali dictionary define karne ke liye, yeh likhe
...```javascript
empty_dict = {};
```
...
Curly braces use karne se ek empty yaani khaali dictionary ban jaati hai.
