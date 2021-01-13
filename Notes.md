# Notes About Web Development

#### 23. Developer Fundementals.

* Kene pandai google stuff. through time kau akan ingat semua.
* DOCTYPE. hey, file ni akan guna HMTL file.
* grow the foundation. jangan tau copy paste je.
* Yang pro tahu, sebab untuk setiap tindakan diorang.
* Be that person yang always concious.

#### 24. About W3 Schools.
* bagus kalau kita baru nak start.
* tapi lagi bagus rujuk [MDN](https://developer.mozilla.org/my/)

#### 25. Macam mana nak tanya soalan.
* As developer, kita kene pandai problem solving. 
* Part of problem solving is asking the right question. 
* Kalau stuck,  try:
  i. [Rubber Ducking](https://rubberduckdebugging.com/)
  ii. Website macam [StackOverflow](https://stackoverflow.com/)
  ii. Reach Community kat Discord(ada link specific)

#### 26. HTML tag
* part ni kalau nak study, buat satu paragraph lorem ipsum pastu main lah dengan tag ni smua.
* letak side to side . baru nampak. 
* bnyak gila tag. kalau nak blajar.
* ada 20+- tag yg usually developer guna.
* patutnya semua benda kat dalam html kene ada tagging.
* nested = sesuatu nested dalam sesuatu tag lain.

#### 27. Tags 2
* macam mana nak buat list ol>>li
* ada ordered list dngn nested list.

#### 28. Self- Closing Tag
* tag yang cukup dia ada satu je.
* <br>
* ```<img src="kat mana kau amek image ni" alt="kalau gambar takde" width= height>```
* pergi w3schools. boleh cuba faham docmentation html cakap apa untuk setiap attribute.

#### 29. Anchor Tag
* ```<a href>```

#### 30. index.html
* by default. server akan hantar index.html tiap kali user minta apa2  dekat browser

#### Relative vs Absolute Paths
* Relative Path = refer untuk dalam local computer. so, kat mana dia relative kepada index file. daripada index.html kat mana kedudukan resource tu.
* Absolute path


---
## Advance HTML

#### 32. HTML Forms
* Buat form tag
* isi input.
* boleh guna Alt + Shift + atas/bawah nak cepat duplicate input
* input tag tu, self tag
* kalau letak type. kita boleh buat auto checking.
* type yang membantu, email, date.

* Macam mana nak guna radio
* Guna Alt + up/down untuk move line of code
#### 33. HTML Forms 2
* sambungan macam mana nak guna checkbox
* macam mana nak guna dropdown kene guna select
    ```
    Car<br>
    <select>
      <option value="optionA">Nama option A</option>
      <option value="optionB">Nama option B</option>
    </select>
    ```
* kalau nak select multiple. tambah multiple punya attribute.
    ``` <select multiple>
    <option>...</option>
    </select>
    ```

#### 34. Submit Form
* sebelum boleh submit. pastikan semua input tag dah bernama. contoh kat bawah fname adalah name kepada input First Name
  ``` First Name: <input type="text" name="fname"></input>```

* bila kita submit, nanti dia akan hantar url kat url chrome.
* post/get
* post tu kita tak tunjuk data yang akan disend ke server.
* action = "action.php", dia akan hantar ke mana.
* ? property and value.


#### 35. HTML Tags 3
* Comment untuk bagi orang lain faham code kau. kalau korang edit serentak.
* Div tag - untuk multiple line element.
* span tag - untuk inline element
* boleh letak style.

#### 36. HTML vs HTML 5
* Lain browser lain penerimaan terhadap sistem kita.
* So, pencipta internet dulu. buat satu bahasa atau standard yang semua developper kene follow supaya semua website atau web app boleh interact dngn browser lain.
* protocol
* html 5. latest evolution
* dah ada tagging baru
* article, aside, details, figcaption,... semantics element.
* supaya machine tu paham.


#### 37. Copy Website
*  view source 
* copy semua . paste.
* dah boleh guna.
* save dalam html. 
* buka dalam browser.

#### 38. HTML Challenge
* Dia suruh buat benda2 macam tadi.

#### 39. HTML Lesson Files.
* download dan push dalam git.

#### 40. Exercise: HTML QUiz

#### 41. Optional Exercise.
Quotes. > "use the current knowledge that you have to move onto the next section, as you will be constantly improving and learning new things about HTML as you code along in this course."

---
## CSS

#### CSS Properties
* Boleh inlcude file css. guna link punya tag.
``` <link>```
* [CSS Trick](https://css-tricks.com/); website untuk buat css.
* look up and learn.

     ```
    tag_apa{
      properties: value;

    }
    ```

#### Selector
* [Selector](https://www.w3schools.com/cssref/css_selectors.asp) dalam css.

#### Text n Font
* text-decoration : underline;
* line-height : 100px.
* font-size :
* font-style:weight; 

- font-style bergantung pada apa yang ada dalam localhost.
- klaau website kita nak letak custom font-style
- [Google font](https://fonts.google.com/) lepas tu select font. lepast tu. paste link ke file style kau.

#### Image in CSS


#### Box Model 
#### px vs em vs rem
