**मुर्गा प्रभाव**: [अंदर](https://scratch.mit.edu/projects/435730522/editor)देखें{:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

`set color effect to`{:class="block3looks"} और `change color effect by`{:class="block3looks"} खंडों के पास ड्राप डाउन मेनू हैं जिसमें से आप विभिन्न ग्राफ़िक इफेक्ट्स चुन सकते हैं जो आपके स्प्राइट की दिखावट बदल सकती हैं:

+ `color`{:class="block3looks"} (रंग): `0` से `199` (इससे बड़ी संख्या वापस 0 से शुरू होंगे, तो `200` `0` के बराबर हैं)
+ `fisheye`{:class="block3looks"} (फ़िशिये): `0` का मतलब हैं की कुछ नहीं होगा, बड़ी संख्याएं एक बड़ा 'fisheye' प्रभाव पैदा करती हैं, और ऋणात्मक संख्याएं विपरीत 'fisheye' प्रभाव का कारण बनती हैं
+ `whirl`{:class="block3looks"} (चक्कर): `0` का मतलब हैं की कुछ नहीं होगा, बड़ी संख्याएं बाईं ओर एक बड़ा चक्कर बनाती हैं, और बड़ी ऋणात्मक संख्याएं दाईं ओर एक बड़ा चक्कर बनाती हैं
+ `pixelate`{:class="block3looks"} (पिक्सेलेट): `0` का मतलब हैं की कुछ नहीं होगा, और बड़ी संख्याएं अधिक पिक्सेल बनाती हैं
+ `mosaic`{:class="block3looks"} (मोज़ेक): `0` का मतलब हैं की कुछ नहीं होगा, और बड़ी या नकारात्मक संख्याएं प्रतियों की संख्या को प्रभावित करती हैं
+ `brightness`{:class="block3looks"} (चमक): `0` का मतलब हैं की कुछ नहीं होगा, `100` तक की संख्याएं स्प्राइट को हल्का बनाती हैं, और ऋणात्मक संख्याएं `-100` तक स्प्राइट को गहरा बनाती हैं
+ `ghost`{:class="block3looks"} (घोस्ट): `0` का मतलब हैं की कुछ नहीं होगा, और `100` तक की संख्या स्प्राइट को अधिक पारदर्शी बनाती है

प्रत्येक व्यक्ति क्या करता है, यह देखने के लिए विभिन्न प्रभाव मानों `सेट (set)`{:class="block3looks"} करने का प्रयास करें। देखे अलग अलग इफ़ेक्ट आपके स्प्राइट की दिखावट कैसे बदलती हैं ।

```blocks3
set [whirl v] effect to (100)

set [pixelate v] effect to (50)
```

**सुझाव:** `225` `color effect`{:class="block3looks"} (रंग इफ़ेक्ट) `25` `color effect`{:class="block3looks"} के बराबर हैं, तो आप बार बार रंग बदल सकते हैं। अन्य ग्राफिक प्रभावों के लिए, प्रभाव के लिए अधिकतम या न्यूनतम संख्या तक पहुंचने के बाद कोई अन्य परिवर्तन नहीं किया जाएगा।

```blocks3
forever
change [color v] effect by [25]
wait [0.5] seconds
```

फिर से शुरू करने के लिए `clear graphic effects`{:class="block3looks"} खंड का उपयोग करें। हरे झंडे पर क्लिक करने से भी सभी ग्राफिक प्रभाव मिट जाएंगे।

प्रोजेक्ट के शुरुआत में एक ग्राफ़िक इफ़ेक्ट का उपयोग करने के लिए, `set a graphic effect`{:class="block3looks"} खंड को `when green flag clicked`{:class="block3events"} खंड के निचे लगाए:

```blocks3
when green flag clicked
set [ghost v] effect to (25)
```

**सुझाव:** आप ग्राफ़िक प्रभाव को `सेट (set)`{:class="block3looks"} और `बदल (change)`{:class="block3looks"} भी कर सकते हैं।

