---
chapter: अध्याय २
pageNumber: १०
---
# अध्याय २
# आधारभूत कुराहरू

यस पहिलो अध्यायमा हामी प्रोग्रामिंग र जाभास्क्रिप्ट भाषाको आधारभूत कुरा सिक्नेछौं।

प्रोग्रामिंगको अर्थ कोड लेख्ने हो। पुस्तक अध्याय, अनुच्छेद, वाक्य, शब्द र अन्तमा विराम चिह्न र अक्षरहरू मिलेर बनेको हुन्छ, त्यस्तै प्रोग्रामलाई पनि साना र साना कम्पोनेन्टहरूमा टुकराउन सकिन्छ। अहिलेको लागि, सबैभन्दा महत्त्वपूर्ण एक स्टेटमेन्ट हो। `Statement` स्टेटमेन्ट एक पुस्तकमा एक वाक्यको रूपैगी छ। आफैमा संरचना र उद्देश्य छ, तर वरपर अन्य स्टेटमेन्टहरूको सन्दर्भ बिना यो अर्थपूर्ण छैन।

स्टेटमेन्ट अधिक अनौपचारिक (र सामान्य रूपमा) *लाइन अफ कोड*को रूपमा परिचित छ। त्यो किनभने स्टेटमेन्ट व्यक्तिगत लाइनहरूमा लेखिएको हुन्छ। त्यस्तै, प्रोग्रामहरू माथिबाट तल पढिन्छ, बाँयाबाट दायाँ। तपाईं अझै पनि कोड(सोर्स कोड) के चाहि हो त भनेर सोच्दै हुनुहुन्छ होला। त्यो एउटा व्यापक शब्द हो जसले सम्पूर्ण प्रोग्राम वा सानो भागलाई जनाउन सक्छ। त्यसकारण, कोडको लाइन नै तपाईंको प्रोग्रामको लाइन हो।


यहाँ एक साधारण उदाहरण छ:

```javascript
let hello = "Hello";
let world = "World";

// Message equals "Hello World"
let message = hello + " " + world;
```
यो कोडलाई _इन्टपरपरेटर_ भनिने अर्को प्रोग्रामद्वारा एक्जिक्युट(execute) गर्न सकिन्छ जसले कोड पढ्छ, र सही क्रममा सबै स्टेटमेन्टहरू एक्जिक्युट गर्दछ।
