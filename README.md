# مترجم لغة الإشارة الحي

هذا مترجم مباشر لحروف لغة الإشارة؛ فهو يقابل كل إشارة يدٍ بنظيرها من الحروف العربية، 
استعملت فيه شبكة يولو بطرازها الخامس لرصد الأجسام، ومرنتها على [هذه البيانات](https://data.mendeley.com/datasets/f63xhm286w/1) التي كانت قد أعدت لهذا الغرض.
أمررت كل البيانات على الشبكة ممرنا إياها مئتين وخمسين مرة، وقد بلغت من الدقة مبلغا مقبولا، وبنيت على ذلك هذا البرنامج المبسط للكتابة الحية.





# ASL Real-Time Translator
Introduction
This project is a real-time translator for Arabic Sign Language (ASL). It translates each hand gesture in ASL to its corresponding Arabic letter. The YOLO (You Only Look Once) v5 network architecture was used to detect and track hand gestures. The network was trained on a custom dataset specifically prepared for this purpose, which can be found [here](https://data.mendeley.com/datasets/f63xhm286w/1)

# Training
The YOLO v5 network was trained on the custom dataset for 250 epochs. The dataset consists of annotated images containing hand gestures representing Arabic letters. The model achieved a reasonable level of accuracy after training on this dataset.
