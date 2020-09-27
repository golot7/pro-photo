---
weight: 10
title: "מילון מושגים"
#title_align: "left"
date: 2020-09-01
draft: false

authors: 
  - "eran"

profile: false

# taxonomies
categories: 
  - "מושגים"
tags:
  - "Photos"
  - "Game"
  - "React"
  - "Python"
  - "New"

---


### טווח דינמי - Dynamic Range
הטווח הדינמי של חיישן המסלמה (הסנסור) הוא הטווח ב-f-stops בין האזור הבהיר ביותר בתמונה לכהה ביותר, שהחיישן מסוגל לקלוט בלי לאבד מידע.  

למצלמות המתקדמות ביותר כיום יש טווח דינמי של כ-15 f-stops. כיוון שכל f-stop מכפיל את רמת הבהירות פי שתיים משמעות הטווח הזה היא שהאזור הבהיר ביותר בסצנה יכול להיות עד פי 2<sup>15</sup> (שזה 32,768) יותר בהיר מהאזור הכהה ביותר ועדיין להקלט ע"י החיישן בצורה תקינה. אם הניגודיות בתמונה (הקונטרסט) עולה על 15 f-stops הסנסור יאבד מידע כלשהו מהסצנה. לצורך השוואה, לעין האנושית יש טווח דינמי של כ-20 f-stops, כלומר האזור הבהיר ביותר יכול להיות בהיר פי כמיליון יותר מהכהה ביותר. לכן סצינות שניתן לראות בעין ללא בעיה מיוחדת עדיין עלולות להוות אתגר משמעותי למצלמות.
התופעה של קטימת המידע מהסצנה נקראת [Clipping](#קטימה---clipping) ובמקרים רבים היא הרסנית לתמונה. ניתן למזער אותה ע"י בחירה נכונה של נתוני החשיפה, ע"י צילום מספר תמונות בנתוני חשיפה שונים (Bracketing) וחיבור שלהם בשלב העריכה או ע"י שימוש בפיטרים מדורגים Graduated Neutral Density או GND בקיצור.  
ראו גם [ETTR](/posts/ettr).


### קטימה - Clipping
מצב בו הטווח הדינמי של חיישן המצלמה אינו מספיק רחב כדי להתמודד עם הניגודיות של הסצנה וחלק מהמידע בסצנה נקטם ואינו נרשם לקובץ התמונה. כאשר המידע שנקטם הוא בחלקים הבהירים הם נקראים "שרופים" (Burned highlights) ובמצב זה כל הגוונים הבהירים יותר מקצה הטווח הדינמי יירשמו כלבנים לגמרי.כאשר המידע שנקטם נמצא באזורים הכהים הם נקראים "מעוכים" (Crushed shadows) ובמצב זה כל הגוונים הכהים מקצה הטווח הדינמי יירשמו כשחורים לגמרי.
מידע נוסף בערך [טווח דינמי](#טווח-דינמי---dynamic-range).

### חשיפה לימין - Expose To The Right - ETTR
ראו [ETTR](/posts/ettr).